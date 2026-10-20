# ## Nalanda It Zone 
* ** Project report under Nalanda It Zone internship program.
 # Name : **Divya Bharti 
 # Course : **BSC (5th Semester)
 # Session : **(2024-2028)
 # University Roll Number : **(24281200454)
 # University Registration NUMBER : **(24120023228)
 # College Name : **S.N.Sinha College 
 # Institute Name : **Nalanda It Zone 
 # Application ID : **(2PFWM0BB)
 # Project TOPIC : image - as - data - arrays 

# ## Understanding Picture and Images.
  ** Topic:** Understanding Pictures and Images as Data Arrays.

  This repository demonstrates how computer pereceive and process digital images. For a computer, every image is foundamentally a **Data Array (Matrix)** of numbers representing pixel intensities Using, Python, OpenCV, and Numpy, we can analyze and manipulate these image arrays.
--- 
## Core Concept
 * ** Grayscale Images (2D Array):** Represented as a tow - dimensional gride of pixels. Each pixel contains a single value ranging'o' (pure black) to '255' pure white).
 * ** Colour Images (3D Array):** Represented as a three - dimensional grid containing three colour layers or channels. opencv reads colour images in the **BGR** (Blue Green Red) from at.


## Project Structure 
''' text 
 image - arrays.py # Python Script to analyze image matrics
 README.md         # Documentation(this file)
'''

'''
# good implementation ('image - arias.py')
Here is the clean python script to visualize an image as a numerical matrix:

''' Python 
import cv2
import Numpy as np

# 1. Create a dummy 5×5 gray scal  image arrays manually 
Print("---1. Manually Created 2D Pixel Array ---")
Sample_arry = np.array[
   ' [100 , 150 , 200 , 255 , 0]
     [150 , 200 , 255 , 0 , 50]
     [200 , 255 , 0 ,50 , 100]
] , dtyp = np.unit8
Print ("Image Array Matrix:\n", Samp-array)
print("Array Shape (Height,Width)", Sample-array.shape) # Output:(5,5)

# 2. Loading a real image file to check its data Layout.

# Note: Replace 'sample.JPG' with any image present in your directory

try:
  img = cv2.imready('sample.JPG')
  Print("\n---2.Real Image Data Analysis---")
  
 Print("Image Shape ( Height,Width,Channels): ", imag,shape)

 Print("Data Type of Elements img.dtype)

 # Slice the matrix to print BGR pixel values of a small 3×3 region
 Print("\n BGR Values of the top-
 '''
 ---
 except Exception as e: 
       Print("\n[Tip] Place a 'sample 'jpg'file in the directory to analyze real image matrice."

## Key Takeaways 

1. ** Pixel Ranges: **Every pixel value inside the matrix operates within a standard '0 to 255' scale.

2. ** Matrix Slicing: **Modifying an  image (like cropping or colour changes) is achieved inside the data array.

3. **AI and Computer Vision: **Machine Learning models do not see visual content the perform mathematical operation directly on these numerical arrays.


   # Thank You 🌿

     * Respectful thanks to the teacher for guidance and checking my project file.
       
 

 
 
