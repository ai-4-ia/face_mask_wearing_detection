PART 1: INSTALLATION: 
1. Create a Python virtual environment named 'test' and activate it

$ virtualenv test

$ source test/bin/activate

2. in your Terminal/Command Prompt  run the following command to install the libraries required 
   	
   $ pip install -r requirements.txt
        
PART 2: WORKING

1. Open terminal, type the following command to train face mask detector model:

$ python MobileNetV2_tranning.py --dataset dataset (if you want to train model with MobileNet)
 
$ python Resnet50_tranning.py --dataset dataset (if you want to train model with Resnet50) 

2. To detect face masks in an image, type :
	
	$ python detect_mask_image.py --image images/nameofimagefile

3. To detect face masks in real-time video streams, type:

	$ python detect_mask_videostream.py

4. To open the Face Mask Detection web application, type:
		
	$ streamlit run webapp.py 




