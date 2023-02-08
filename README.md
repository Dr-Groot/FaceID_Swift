# FaceID_Swift

For creating FaceID using CoreML, we first need a model. This model will help us to detect the respective person to unlock the device.
We have used 3 animals image data - [Cat - Dog - Horse] and created a model using CreateML image classfication.

We have assumed that owner of the device is cat and it will unlock when it will get atleat 95% confident that the user is a cat.

> I request you to first check CoreML and CreateML for better understaning:
[CoreML - Object Detection](https://github.com/Dr-Groot/ObjectDetection_CoreML-Swift) || [CoreML - CreateML](https://github.com/Dr-Groot/CreateML_CoreML-Swift)

Now let's jump back to our project, when you will open the app it will appear like this:

![IMG_2101](https://user-images.githubusercontent.com/63160825/217430657-7a458469-642a-4cd4-9c09-e9886104dac8.PNG)

I have added tap gesture to the screen, this means when you will tap on the screen it will start scanning your face like this:

![IMG_2102](https://user-images.githubusercontent.com/63160825/217431388-299d0a91-68b7-41e8-9efc-ad61c6230cd1.PNG)

If identity is matched as cat with more than 95% confidence, it will unlock the screen. Don't worry i will provide model + data from which the model is created so that you can use this functionality.

![IMG_2104](https://user-images.githubusercontent.com/63160825/217431611-71dd6956-91fc-40eb-9709-344f1f9571e3.PNG)

Don't worry if you aren't able to match the face within 3 seconds, passcode screen will appear so that you can unlock the device.
and passcode is 123456.

![IMG_2103](https://user-images.githubusercontent.com/63160825/217432094-7403129a-7599-48ac-b453-186c8988cc3d.PNG)

> You can change the screening time (3 sec) and passcode (123456).

Happy Learning !
