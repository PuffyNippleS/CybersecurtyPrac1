# CybersecurtyPrac1
In this project, we're combining the ancient practice of steganography, which involves hiding information in plain sight, with cutting-edge Augmented Reality (AR) technology. Augmented Reality adds a digital layer to our physical world, incorporating visuals, sound, and sensory elements through technology. Our goal is to create an AR application that securely conceals sensitive content like videos or audio files. This hidden content can only be unlocked when viewed through a specific AR marker, which will be shared exclusively with the intended recipient.
github->https://github.com/PuffyNippleS/CybersecurtyPrac1

# Scenario
You are a member of a clandestine group that specializes in covert communication techniques. To amplify the security and intrigue of your exchanges, you've decided to combine the age-old art of steganography with cutting-edge Augmented Reality (AR) technology. Through a custom AR application, your group can now share hidden video messages within innocuous-looking images.

# Description
- App Functionality:
  - Utilizes Unity-based application on Android platform for image viewing and video display.
  
- Augmented Reality Technology:
  - Implements Vuforia to create an Augmented Reality environment viewed through the device's camera.
  - Transforms tracked images into a hidden video within the AR space.

- Camera Tracking:
  - Relies on Google AR Core to track images using the device's camera.
  - Continuously tracks images until the identified target image is recognized.

- Image Storage and Handling:
  - Utilizes an array to store images as 2D textures for efficient processing.
  - Employs event handlers to monitor the reception of images and ensures proper identification.

- Image Replacement and Video Playback:
  - Utilizes the event handler "OnTrackedImagesChange" to initiate tracking image changes.
  - Compares images in the array to the target images.
  - Upon finding a match:
    - Replaces the tracked image with the corresponding texture using Vuforia.
    - Places a plane over the identified image for visualization.
    - Initiates playback of the hidden video.

Additional Information:
- The app leverages a combination of Vuforia and Google AR Core technologies to provide a seamless augmented reality experience.
- Event handling, particularly the "OnTrackedImagesChange" event, plays a pivotal role in detecting changes in the tracked images.
- The integration of Vuforia allows for smooth replacement of tracked images with textures, facilitating video playback.


# Requirements
As the receiver all you require is a Mobile andriod phone with the following:
Andriod version 7.0 and Above.
Google AR Services

As the developer you require:
Unity Editor with Andriod SDK and NDK
Vuforia
Kindly note the Library file has not been uploaded due to size limitations

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

