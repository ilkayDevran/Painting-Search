# Where are you at MEF Universty ? 

>The main idea of the project to find your location in the MEF Univerty. Basicly the paintings around you is the key of the finding your location. The picture given by the user program makes some processes to find best macth through Database images then program shows specific location of you on the floor plan.

# Painting Matcher Project
This is a project developed by @Uluç Furkan Vardar and @ilkay Tevfik Devran for Computer Vision lecture (COMP 482). The aim of the project to compare the implemantations in below show test results.
  > SIFT implemantation for regocnation of paintings.
  >CNN (Convolutional Neural Network)implemantation for regocnation of paintings.

# How Does Program Do This?
 > Our SIFT implemantation steps in below:
 ![alt text](https://raw.githubusercontent.com/ilkayDevran/Painting-Search/master/Activity%20Diagram%20for%20ATM.png)

>Our CNN implemantation steps in below:
 ![alt text](https://34tzkp3af7ck1k675g1stf6n-wpengine.netdna-ssl.com/wp-content/uploads/2016/11/typical_cnn_architecture.png)



### Topic Research
If you want to learn more about these topics you can go for it:
* [Keras information](https://elitedatascience.com/keras-tutorial-deep-learning-in-python) - You can find needed information from this website.
* [Keras Script resource](https://gist.github.com/fchollet/0830affa1f7f19fd47b06d4cf89ed44d) - You can find how to use keras in python from here like us :)
* [SIFT information] (A. Rosebrock, Practical Python and OpenCV : Case Studies, 3rd ed. pyimagesearch, 2016, pp. 86-105.)

After you view, lets continue

### Installation

>Firstly you need python2.7 for to run *SIFT* implementation.
,also you need python3 to use *CNN* implementation.
>For production environments...
[Install python versions to your computer](https://www.python.org/downloads/)

| Required Libraries  | installation |
| ------ | ------ |
| numpy |  pip install numpy |
| cv2 |  pip install opencv-python |
| tensorflow |  pip3 install tensorflow |
| keras |  pip3 install keras |
| graphviz |  pip install graphviz |
| pydot |  pip install pydot |


# Usage
>Usage of *SIFT* on terminal


```sh
$  python PaintingFecherWSift.py -p 'PATH OF THE INPUT IMAGE'
```
ex:
```sh
$  python PaintingFecherWSift.py -p queries/query1.png
```
> A typical output of the program
![alt text](https://raw.githubusercontent.com/ilkayDevran/Painting-Search/master/Ekran%20Resmi%202018-05-23%2012.04.32.png)
 
 











