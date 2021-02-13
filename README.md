# Install requirements

Best practice create your own environment to avoid clash of version.
### Example for windows USERS

1.  virtualenv myenvironment
2.  .\myenvironment\Scripts\activate
3.  pip install -r requirements.txt

# Training the model (training_model_for_Mask_Detection.ipynb)

I provided a trained model if you don't want to wait for the model to be trained "mask_detector_version_moez.model"

For the ones who want to train their own model you must first download the dataset and put it under a directory
named "Face-Mask-Detection".

Here is a link https://drive.google.com/drive/folders/1-62-gtVRANF5a5ylnFrYO1Y--q-OiFgr

It must look like this after you downloaded it  "Face-Mask-Detection/dataset/without_mask/..."

I also  provided two files one .py and another .ipynb.

You can play with the model and try to modify it.

# Testing 
This phase include face detection before using the previous model of mask detection !

We don't want to detect a flying mask HAHAHAHA! 


# Preview 

![](https://github.com/moez-RT/Real-Time-Mask-Detection/blob/master/preview-mask-detection.gif)
