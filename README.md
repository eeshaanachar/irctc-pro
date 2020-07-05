# IRCTC Pro
Pro for prototype! IRCTC Pro is a very basic prototype of the official irctc app.

### Objective(s)
* Emphasize on the use of databases for applications.
* Create a prototype of a railway system with as many options as possible.

### Platform
* Android version: Android 4.3 Jellybean (API 18) or above
* Authentication: Firebase
* IDE: Android Studio
* Languages: Java, XML
* Local Storage: SQLite

### Instructions
The .apk file, which is the software developed, has been provided which can be installed on any Android Smartphone running Android Jellybean (4.3) or above. If the installation fails, we've also provided the source code files which can be opened on Android Studio and run on an emulator or Smartphone.

On opening the app, the first page would be the Google sign-in page, and once you are signed in you will be taken to the home screen where you'll be presented with 4 options. You'll also see a 3 dot menu (kebab menu) on the upper right corner where you can sign out or view the 'About Us' section. The 4 options mentioned are:
1. Admin login: The username and password are both "admin" (without quotes). Once signed in, you can go to trains option where you can add, delete and view trains (tapping on any train in view trains will show further information); you can go to stations option where again you can add, delete and view stations; you can go to train timings option where you can enter the train timings as per station (if no timings are added, then the train remains without any source nor destination); and you can add delay to the trains using delay option.
2. Book Tickets: Enter the source and destination station codes, enter a date, and tap search trains. Select from the available train(s) and then select from available compartments. Now select seat(s). Available seats are shown in green, booked in grey, and selected in blue. Tap book and now enter personal details. The fare shown is calculated as "number of journey hours x number of seats selected x 50". Tap confirm and you'll see a thank you message and also the generated PNR.
3. PNR Enquiry: Enter PNR no and you'll get the related info if PNR is valid and the train hasn't been deleted. Else you'll see appropriate messages. Any train delay is also shown.
4. Train information: Enter the train number and you'll get the train details in a dialog box. If the train number is invalid, you'll get the appropriate message.

### Present Scope
For a prototype without any fixed requirements, this software can be considered complete. However, it is still a prototype and NOT DEPLOYMENT READY.