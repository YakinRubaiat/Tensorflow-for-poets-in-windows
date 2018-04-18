# Tensorflow-for-poets-in-windows
Tensorflow for poets is a image classifier, you can use it for build your own classifier.  

Introductroy video : https://goo.gl/dKZAcR 

Google Research blog on Inception: https://goo.gl/CSrfJ1

TensorFlow for Poets Codelab: https://goo.gl/QTwZ3v


First You have to create a folder in C drive: 

GO to C:\ Users \ (your pc name)

Then create a folder name tf_file.

In you want to create a classifier that can classify 6 type flower or someting, Put 6 item image in 6 different folder name by item name.

In my fruit_photos folder contain :

Apple : 211 pic

Orange : 200 pic

Tomato : 138 pic

Grapes : 78 pic

Goava  : 98 pic



For retrain the model use retrain.py from my repository.

Take it to the tf_file folder.

In cammand line use this : 
           
           python C:\Users\Flying_Dutchman\tf_files\retrain.py --output_graph=retrained_graph.pb  --output_labels=retrained_labels.txt --image_dir=C:\Users\Flying_Dutchman\tf_files\fruit_photos
        

