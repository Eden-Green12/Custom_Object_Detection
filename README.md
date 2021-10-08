# Custom_Object_Detection
Training a pretrained RESNET50 on a custom dataset 
The official link to the tutorial - https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html

Follow the initial installation as per the notebook.
And then follow then the tutorial for training on your own dataset.
The versions do create some issues. tensorflow-gpu version 2.6.0 get installed but separate installation of tensorflow 2.4.1 will enable training. Else will throw an error.
If tensorflow-gpu==2.4.1 is installed then also an error was thrown. 
So try installing tensorflow-gpu first (version 2.6 / any that gets installed ) and then you can install tensorflow 2.4.1 separately afterwards. 

ref to a youtube video that may help -- https://www.youtube.com/watch?v=XoMiveY_1Z4&t=170s
