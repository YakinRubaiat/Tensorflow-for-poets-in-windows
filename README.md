# Tensorflow-for-poets-in-windows
Tensorflow for poets is a image classifier, you can use it for build your own classifier.  

Introductroy video : https://goo.gl/dKZAcR 

Google Research blog on Inception: https://goo.gl/CSrfJ1

TensorFlow for Poets Codelab: https://goo.gl/QTwZ3v


Create a folder name tf_file in C drive:

my tf_file location : C:\Users\Flying_.....\tf_files

In you want to create a classifier that can classify 6 type flower or someting, Put 6 differnt item image in 6 different folder and give name by item name.

C:\Users\Flying_Dutchman\tf_files\fruit_photos

In my fruit_photos folder contain :

Apple : 211 pic

Orange : 200 pic

Tomato : 138 pic

Grapes : 78 pic

Goava  : 98 pic


For retrain the model use retrain.py from my repository.

Take it to the tf_file folder.

In cammand line use this : 
           
           python C:\Users\Flying_Dutchman\tf_files\retrain.py --output_graph=output_graph.pb  --output_labels=output_labels.txt --image_dir=C:\Users\Flying_Dutchman\tf_files\fruit_photos
        

It create 2 file name :

output_labels.txt and output_graph.pb

Next we take a test image and cheak it in our classifier :

We use label_image.py program for that.

Edit the output_labels.txt and output_graph.pb file path in label_image.py file.

In Command line :
    
      python C:\Users\(PC name)\tf_files\label_image.py C:\Users\(PC name)\tf_files\test\testPic.jpg
      
 First python
 Second label_image.py with it's location.
 Then a jpg pic with it's location.
 
 
