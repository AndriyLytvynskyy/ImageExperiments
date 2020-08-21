# Image Experiments with Pillow
This is a simple project which shows interaction with library called Pillow and is based on one of the Coursera courses.
Basically it creates nine different variants of one image. 

## How to run?
Just execute from command line: 
```python ImagePillow.py```


##How it works?
Normal RGB image is represented with a matrix like the following: 
```
(1, 0, 0, 0,
 0, 1, 0, 0,
 0, 0, 1, 0)
``
Row0 is basically Red color plus some constant.
Row1 is basically Green color plus some constant.
Row2 is Blue color plus constant.

Here we can easily switch off particular channels/colors - e.g. if we want to remove Red -
switch 1 to zero in first row. 

 