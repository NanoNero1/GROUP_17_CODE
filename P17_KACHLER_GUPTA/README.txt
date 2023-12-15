THIS IS THE README FILE FOR PROJECT_17
TEAM MEMBERS: ALIND GUPTA, DIMITRI KACHLER

Github for the Godot Project: https://github.com/NanoNero1/GROUP_17_CODE
############
Please note, due to the way that the Godot Game engine works, you cannot currently dynamically change textures,
hence the outputs for the notebooks will not work. However, you are welcome to try out the build "finalBuild.exe"
in the code from the github, it should run fine and uses the files generated from the notebooks
############

Welcome to the Instructions on building a virtual world from a real life image. In order to test out our system, you may use the pre-packaged file "demoImg.jpg", in which case running the notebooks without modifications should be fine. 

##IMPORTANT 
- These Notebooks are meant to be run on Google Colab, so please upload both Edge_Detection.ipynb, and 
Circle_Dectection.ipynb to Colab.
- If you do have a custom image, it must absolutely be a .jpg, .png files will unfortunately not work.
##VERY IMPORTANT
-Please run Edge_Detection.ipynb first, Circle_Detection.ipynb must be run later to get coordinates that match


1. First go to Edge_Detection.ipynb and upload the demoImg.jpg file to colab's file system. Do not put it in a folder.

Then, you can run the entire notebook in one go without issues as long as the image file is still called "demoImg.jpg",
if not, please re-named it or change the path in the notebook accordingly.

You will have new files in colab's file system, e.g. "demoImgRot.jpg", if not, please refresh the folder.
You will also see "coords_b.txt" these are the coordinates of the final line.



2. Download and upload demoImgRot.jpg to Circle_Detection.ipynb as you did before with demoImg.
In this case, you can just run the entire notebook again in one go.

There should be two outputs:
object_detections.txt - for the coordinates of the detected circles
object_removal_image.jpg - for the image with the objects removed with inpainting

Otherwise, please enjoy all the outputted image to visualize some of the processes