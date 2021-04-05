# Conversion-of-an-Image-into-Cartoon
This report presents the process of generating a cartoonification from the image using Python and Opencv

#### OpenCV
Python is a strong collection of effective libraries. It has many libraries for practical applications in the real world aspects. OpenCV is one such library. OpenCV is a computer vision multi-platform library. It involves video and image capture and editing applications. It is utilized in several incredible utilizations that including image transformation, shape identification, facial recognition and many others.

#### Objective
The goal of this project is to transform an image into a cartoon. Building a python application that will convert an image into a corresponding cartoon using openCV.

### Steps involved in developing Cartoonifier Application

#### Step-1: Importing the required libraries

- CV2 library - Imported to utilize OpenCV for the aspects of image processing [CV2](https://pypi.org/project/opencv-python/) [CV2 Tools](https://pypi.org/project/cv2-tools/) [OpenCV Tutorials](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_image_display/py_image_display.html) [OpenCV](https://opencv.org/)
- EASYGUI library - Imported for opening a file box. It will allow the user to select any file from the user's system. [EASYGUI](https://pypi.org/project/easygui/#:~:text=EasyGUI%20is%20a%20module%20for,invoked%20by%20simple%20function%20calls.) [EASYGUI Documents](https://easygui.readthedocs.io/en/latest/)
- NUMPY - Images will be stored and processed as numbers. These are taken as arrays. Usually, everyone utilize NUMPY to deal with arrays. [NUMPY](https://numpy.org/) [Wikipedia](https://en.wikipedia.org/wiki/NumPy)
- IMAGEIO - Imported for reading the file that is selected by file box along with the path od the image. [IMAGEIO](https://pypi.org/project/imageio/) [IMAGEIO Documents](https://imageio.readthedocs.io/en/stable/)
- MATPLOTLIB - Imported for the purpose of visualization and plotting. In this aspect, It is imported to plot the images. [MATPLOTLIB](https://matplotlib.org/) [Wikipedia](https://en.wikipedia.org/wiki/Matplotlib)
- SYS - It provides functions and variables used to manipulate different parts of the Python runtime environment.[SYS Documents](https://docs.python.org/3/library/sys.html) [SYS Module Understanding](https://www.python-course.eu/sys_module.php)
- OS - Imported for the OS interaction. The main purpose of this library is to read the path and save the selected images to that path. [OS](https://docs.python.org/3/library/os.html)
- TKINTER - It is an GUI toolkit. It is imported for generation of GUI(Graphical User Interface). [TKINTER](https://docs.python.org/3/library/tkinter.html) [Wikipedia](https://en.wikipedia.org/wiki/Tkinter)
- PIL - The full form of PIL is "Python Image Library". It is a free open source additional library for python programming language that adds support for opening, Manipulating and Saving various image file formats. [Wikipedia](https://en.wikipedia.org/wiki/Python_Imaging_Library) [pillow](https://pypi.org/project/Pillow/)

#### Step-2: Generation of a file box to select an interesting file
Building the main window fo the developing application will be done through this step. this window or this step includes buttons, labels, and images. Title can be genaerted by utilizing title().

#### Step-3: Storing of an image using CV2 library
CV2 library will be utilized for storing of images in the form of numbers in arrays format. It will help us to perform operations as per our necessities.

#### Step-4: Transform the input image into grayscale image

#### Step-5: Smoothening the transformed grayscale image

#### Step-6: The edges of the image to be retrieved

#### Step-7: Image Mask is to be generated

#### Step-8: Generating the Cartoon Effect on the image

#### Step-9: All the transitions will be plotted.

#### Step-10: User can save the cartoon generated using save button

#### Step-11(i): Develop the main window for the application

#### Step-11(ii): Develop the Cartoonifier button in the main window of the application

#### Step-11(iii): Develop the save button in the main window of the application.
The steps-11(i)(ii)(iii) will be made with the aid of TKINTER library.

### Limitations
1. Selct the image with good quality
2. Select the image with light colored background.
