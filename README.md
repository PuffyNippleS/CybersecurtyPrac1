# CybersecurtyPrac1
In this project, we're combining the ancient practice of steganography, which involves hiding information in plain sight, with cutting-edge Augmented Reality (AR) technology. Augmented Reality adds a digital layer to our physical world, incorporating visuals, sound, and sensory elements through technology. Our goal is to create an AR application that securely conceals sensitive content like videos or audio files. This hidden content can only be unlocked when viewed through a specific AR marker, which will be shared exclusively with the intended recipient.

# Scenario
You are a member of a clandestine group that specializes in covert communication techniques. To amplify the security and intrigue of your exchanges, you've decided to combine the age-old art of steganography with cutting-edge Augmented Reality (AR) technology. Through a custom AR application, your group can now share hidden video messages within innocuous-looking images.

# Description
The following app uses Unity-based application on Android to view images via the camera and display a hidden video. Using Vuforia to create Augmented Reality space viewed through the camera to change the tracked image into the secret video. Using Google AR Core, the camera tracks the images until the image that is being tracked is identified.Using an array I store the images as 2D textures. I use Event handlers to tack if the images are being received and if not to allow to identify the correct image.

Using the event handler called OnTrackedImgaesChange  look the the images in my array and then find if its equal to the images we are looking for. Once Found It replaces the Image that is found/ Being tracked with the Texture usign Vuforia it then places a plane over it and plays the video 
# Requirements
As the receiver all you require is a Mobile andriod phone with the following:
Andriod version 7.0 and Above.
Google AR Services

As the developer you require:
Unity Editor with Andriod SDK and NDK
Vuforia


# App installation
The apk to install on the android device.
https://drive.google.com/drive/folders/1XkHikFFkGYTqSaOm0gDYW74wButVGEVo
# How to video
Watch this video to understand how the app works.
https://drive.google.com/drive/folders/1XkHikFFkGYTqSaOm0gDYW74wButVGEVo
# Key Images
The following images should be scanned with the application to reveal the hidden video.


![plot](https://github.com/PuffyNippleS/CybersecurtyPrac1/blob/main/Assets/Image1.jpg)
![plot](https://github.com/PuffyNippleS/CybersecurtyPrac1/blob/main/Assets/Image2.jpg)

References:
https://developer.vuforia.com/support
https://www.youtube.com/watch?v=gpaq5bAjya8&feature=youtu.be

