## [Mood-Detection](https://github.com/PrasanthMolleti/Mood-Detection)

The mood detector can be used to detect the person's mood(happy, angry and sad) from an image or a webcam feed, and highlight it with a box.

The [Tensor Flow Object Detection](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwje0onp8tX-AhXgSGwGHWsGA_YQFnoECBEQAQ&url=https%3A%2F%2Fgithub.com%2Ftensorflow%2Fmodels%2Ftree%2Fmaster%2Fresearch%2Fobject_detection&usg=AOvVaw3O83I4dttSDLh4RJs_AH0-) api is used along with a [TFOD Model Zoo](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjy49j98tX-AhWbSWwGHXl_BLEQFnoECAgQAQ&url=https%3A%2F%2Fgithub.com%2Ftensorflow%2Fmodels%2Fblob%2Fmaster%2Fresearch%2Fobject_detection%2Fg3doc%2Ftf2_detection_zoo.md&usg=AOvVaw3GBqU__mZH7Q9mCroNgVyj) model to transfer learn the custom mood detector.
The data for training is collected from a webcam or pre-collected images of a person using **OpenCV** and the images are manually labelled using **labelImg**.

The trained model can be used to identify the person's mood by passing an image or the webcam feed using OpenCV.
The output is the image with highlighted box around the person's face and the predicted mood.

The **Future Scope** of this work includes exporting the trained model to create a light-weighted app for mobile or an app for websites.
