App42_Push_Sample_Unity
=======================

App42 Push Sample for Unity

=======================
# About Application

1. It’s a sample application is show integration between Android Framework and Unity3D platform.
2. This application shows how can we integrate our Unity3D game with PushNotification using android Framework.
3. Once a game registered for PushNotification Unity3D game get Notification message accordingly.

# Running Sample

This is a sample Android gaming app is made by using App42 backend platform. It uses Push Notification of App42 platform.
Here are the few easy steps to run this sample app.

1. [Register] (https://apphq.shephertz.com/register) with App42 platform.
2. Create an app once you are on Quick start page after registration.
3. If you are already registered, login to [AppHQ] (http://apphq.shephertz.com) console and create an app from App Manager Tab.
4. [To use Push Notification see video] (http://www.youtube.com/watch?feature=player_embedded&v=4FtpoRkPuPo).
5. To use push Notification service in your application go to https://code.google.com/apis/console,create a new project here.
6. Click on services option in Google console and enable Google Cloud Messaging for Android service.
7. Click on API Access tab and create a new server key for your application with blank server information.
8. Go to AppHQ console and click on Push Notification and select Android setting in Settings option.
9. Select your app and copy server key that is generated by using Google API console, and submit it.
10. Download the Unity project from this repo and open the same.
11. Open Constants.cs file in sample app and make these changes.
       a. Change apiKey and secretKey that you have received in step 2 or 3.
       b. Change projectNo with your Google Project Number.
       c. Change gameObjectName with your GameObjectName you are using in Game.
       d. Change callBackMethod with your method name on which you have to get PushNotification Callback from Android ex : Success.
12.  Create a mathod in your main cs file that you have declared as callBackMethod in Constants.cs file that as one argument String type ex : Success
13. Build and Run 
