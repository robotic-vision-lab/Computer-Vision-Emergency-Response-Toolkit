# Computer-Vision-Emergency-Response-Toolkit

Release version can be found at: http://cver.hrail.crasar.org

## CVERT Competition
* Create a Fork of the "CVERT-Competition-Master" branch. This is a copy of the current release version.
* You can now freely work on your Forked version of the project.

### Submissions
* There are 3 submission branches, one for each category in the competition.
* To submit your project create a "New Pull Request" to the approriate "CVERT-Competition-Category-#" your project falls under. 
* You may include a "Competition-README.txt" file with anything important you might want to tell us about your project. This should at least include things such as, software and/or hardware requirements to run the project, any known issues, or anything that you wanted to highlight about your project.


# Setup

## Visual Studio
* Microsoft .NET Framework 4.6.1
* Microsoft Visual Studio 2017 Installer Projects Extension
  * This can be installed by clicking ```Tools -> Extensions and Updates... -> Online``` then entering the name of the extension in the search box
  
## Developer Note
* Note: Before building the project in Visual Studio, please verify that the ‘yolov3.weights’ file is present in the ‘Computer-Vision-Emergency-Response-Toolkit-CVERT-Competition-Master\Computer Vision Toolkit\Computer Vision Toolkit\lib\Algorithms’ folder . If it is not present, it can be downloaded from https://pjreddie.com/media/files/yolov3.weights. 

* Currently I am not able to commit large LFS file and issue regarding this already open in github community.
* https://github.com/git-lfs/git-lfs/issues/1449
* https://github.com/Fergex/Platformer445/issues/2
  

## Python Setup
* Python 3.6.4
  * https://www.python.org
  
* OpenCV
  * pip install opencv-python
  * pip install opencv-contrib-python
  * https://opencv.org
  * Tutorial
    * http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_tutorials.html
* Numpy
  * pip install numpy
  * http://www.numpy.org
* SciPy
  * pip install scipy
  * https://www.scipy.org
* Scikit-Learn
  * pip install scikit-learn
  * http://scikit-learn.org/stable/
* Spectral (SPy)
  * pip install spectral
    * http://www.spectralpython.net
* Argparse
  * pip install argparse
* Matplotlib
  * pip install matplotlib
  * https://matplotlib.org
* Tensorflow
  * pip install -v tensorflow
* keras
  * pip install -v keras
  
  ## Oputput
<br/> Sharing output image after analysis. We are successfully able to detect the person in images and hightlight area in boundary box. Click on the image for detail video description
[![Watch Video here](https://github.com/robotic-vision-lab/Computer-Vision-Emergency-Response-Toolkit/blob/master/Documentation/Image/result.JPG)](https://youtu.be/xPBmQ31Bv-Y)
