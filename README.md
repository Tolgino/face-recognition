# face-recognition

# 🚀 Usage

To run the server with the sample model
python3 api.py
To train your own KNN classifier with your dataset, place your images according to the structure below:
images/train/
        ├── <person1_name>/
        │   ├── <someimage1>.jpeg
        │   ├── <someimage2>.jpeg
        │   ├── ...
        ├── <person2_name>/
        │   ├── <someimage1>.jpeg
        │   └── <someimage2>.jpeg
        └── ...
python3 train.py
The trained model will be placed in the root folder, named as "trained_knn_model.clf"

Send POST requests to the /upload endpoint with a file on them as form-data Postman

!(https://github.com/tolgino/face-recognition/blob/master/demo_results/obama-biden.png?raw=true)

# Sample results of using it as the backend of a web page

!(https://github.com/tolgino/face-recognition/blob/master/demo_results/faceapi-demo.gif?raw=true)

Frontend
