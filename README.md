# python-face-recognition-
This python face recognition model will show you how to detect and recognize faces using python, opencv and some other sweet python modules. I start by explaining how to download the required software and modules and then walk you through how to use the provided script. To add faces to recognize simply put then in the faces folder. To test the script on your own image rename it test.jpg and place it into the downloaded folder.

1.First download the zip code and extract it in a folder.

2.Then setup the environment

3.Install all requirements using cmd : pip install -r requirements.txt

4.Now finally run the application with cmd : python face_rec.py

## Outputs:

 here the sample detect and recognition on input images:
# 1:

 <img width="960" alt="1" src="https://user-images.githubusercontent.com/76062756/141056064-2228094a-c46e-4b9a-a555-8a47aa73c135.png">

# 2:
  
  <img width="960" alt="2" src="https://user-images.githubusercontent.com/76062756/141056976-82f8b956-6394-4190-937c-5c2a79688d8e.png">

# TIP:
  This is a tip for who having failed with installation of dlib library.
  please follow below instructions it might solve your problem,for my case it is working.
  
  Install Dlib from source 
     Windows Dlib > 19.7.0

     1.Download the CMake installer and install it: https://cmake.org/download/
     
     2.Add CMake executable path to the Enviroment Variables:

     set PATH="%PATH%;C:\Program Files\CMake\bin"

     note: The path of the executable could be different from C:\Program Files\CMake\bin, just set the PATH accordingly.

     note: The path will be set temporarily, to make the change permanent you have to set it in the “Advanced system settings” → “Environment Variables” tab.

     3.Restart The Cmd or PowerShell window for changes to take effect.

     4.Download the Dlib source(.tar.gz) from the Python Package Index : https://pypi.org/project/dlib/#files extract it and enter into the folder.
     
     5.Check the Python version: python -V. This is my output: Python 3.7.2 so I'm installing it for Python3.x and not for Python2.x

     note: You can install it for both Python 2 and Python 3, if you have set different variables for different binaries i.e: python2 -V, python3 -V

     6.Run the installation: python setup.py install
