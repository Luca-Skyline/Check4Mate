# check4mate
In-Development computer vision and machine learning project, hopefully to be a "Chess Vision" chess analysis app for iOs and Android.

Roboflow Dataset I created, used for "Chess Vision" (identifying pieces). This is also where I trained/fitted the model to the data. Roboflow hosts the API that I'm considering using for the finished app: <br>
<a href="https://universe.roboflow.com/luca-dalcanto-lrlwg/chess-piece-detector-y2t9p"> <img src="https://app.roboflow.com/images/download-dataset-badge.svg"></img> </a> <br>
(images credit Daylen Yang under Open Data Commons Attribution License: http://opendatacommons.org/licenses/by/1.0/.).

Here's the Google Colab I'm using to train that CNN using Tensorflow: <br>
<a href="https://colab.research.google.com/github/Luca-Skyline/check4mate/blob/main/Chess_Piece_Detector.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg"> </a> <br>
(I may not be using this if I end up using the Roboflow API)...

To-do:
- Piece image classification model
- Split chess board into squares and run that model on each one
- Incorporate stockfish so we can get a live analysis through the phone camera
- GUI/nav of app itself
- Export to chess.com, lichess, etc.
- Chess game note scanner using handwriting detection (and more segmentation 🫠)
- more to come...

## Resources:
Image dataset - [Daylen Yang](https://github.com/daylen/chess-id)

ML/CV model training and fitting - [Roboflow?](https://universe.roboflow.com/luca-dalcanto-lrlwg/chess-piece-detector-sv3nm)

Free, open source chess analysis engine - [Stockfish](https://github.com/official-stockfish/Stockfish)

Handwriting detection with python - [handprint](https://pypi.org/project/handprint/)

more to come!!!!
