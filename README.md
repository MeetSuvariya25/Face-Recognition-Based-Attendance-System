# Face-Recognition-Based-Attendance-System-with-GUI-using-OpenCV

There are some problems with the current attendance system like if we maintain the attendance data in paper then there is lots of paperwork we have to do for maintaining all data in the paper that is also time-consuming.

### PurPose:
The basic purpose of this project is to take attendance using face detection. This program makes CSV file of present attendees automatically After successful face detection. Also, It will make a CSV file for registered student's info.

I made this program using these libraries. OpenCV, Numpy, OS, Pandas, Tkinter.

There are total 4 parts of this projects.
1. GUI
2. Take Images of students(Face detection)
3. Save Profile(Train Images)
4. Taking Attandance(Face Recognition)


### Working 
If you don't have required laibreries then firat you need to install that.

OpenCV
>pip install OpenCV-python

Numpy
>pip install numpy

Pandas
>pip install pandas

Os 
>pip install os

Tkinter 
>pip install tkinter

Now For run this project you need 'haarcascade_frontalface_default.xml' along with this python file which contains the haar cascade features of a face.
Now you are good to go.  

when you run this project you will see the simple GUI of this attendance system.were user can easily intract with this system.
First user have to register new students for that they have to enter student name and ID no. and they have to take 100 images of that student. That images will store into one perticuler folder and at the time of train our recognizer that images will be userd.When you save that profile recognizer will train and it will genrate one trainer.yml file which is used at the time of taking attendance. Now when user wants to take attendance they have to click Take attendance button and it will start webcam. A person who are standing in front of webcam if he recognize succesfuly than it will show you a name of person other wise it will show the 'Unknown' at the bottom rectengle which was displayed for face detection.

If person will detected succesfully then it will save attendance in one CSV file and it will save that CSV file into one perticuler folder.This Auto genratation of CSV file is date wise which means it will save the attendance of one day in one CSV file.  

---
For a detailed description, you can read my blog from the following link.

https://medium.com/@meetsuvariya/face-recognition-based-attendance-system-with-gui-using-opencv-and-tkinter-2d5ce7422aa5

