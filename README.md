# chessboard-recognizer
A python script to recognize and convert placement of pieces on chess board
into FEN notation using plain OpenCV and image processing technique (no neural
network).

## Dependencies
 - [virtualenv-wrapper](https://github.com/kenkinming2002/virtualenv-wrapper)

## Usage
```sh
$ ./chessboard-recognizer path/to/image.png
```

Information that cannot be extracted from the image (e.g. castling right) but
nevertheless affect the FEN notation can be specfied on the command line. For
more details:
```sh
$ ./chessboard-recognizer --help
```

## Related Works
Related works are obviously a dime a dozen. One of the work that is closest in
spirit is:
 - [arashyeganeh/Chess-Piece-Object-Detection-using-OpenCV](https://github.com/arashyeganeh/Chess-Piece-Object-Detection-using-OpenCV)
