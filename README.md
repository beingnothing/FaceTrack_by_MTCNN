# Face Detection, Tracking, Extract

This repo can **detect** , **track** and **extract** the **optimal** face in multi-target faces (exclude side face and select the optimal face) from a lot of videos.
   
## Introduction
* **Dependencies:**
	* Python 3.5+
	* Tensorflow
	* [**MTCNN**](https://github.com/davidsandberg/facenet/tree/master/src/align)
	* Dlib
	* Scikit-learn
	* Numpy
	* Scikit-image

## Run
* To run the python code you have to put all the input videos under a folder like **./media** and then provide the path of that folder as command line argument:
```sh
python3 start.py ./media 
```
* Then you can find faces extracted saved in the folder **./facepics** .
* If you want to draw 5 face landmarks on the face extracted,you can make the argument **face_landmarks** to be **True**
```sh
python3 start.py ./media  --face_landmarks True
```


## Results

## Special Thanks to:

## License
MIT LICENSE

