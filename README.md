# Firebase Phone Authentication on Android Java
## Configuration Steps
- After clone the application, we create an application from the firebase console.
- While creating the firebase application, we put the google-services.json file into our project in the place specified in instruction.
- In the firebase console, enable the Phone option from the sign-in method section of the authentication section.
![image](https://user-images.githubusercontent.com/46637720/117214210-2c864a80-ae05-11eb-82b2-dbb4914443d3.png)

- After receiving SHA-1 and SHA-256 by double clicking on the image in right side of android studio, we add it to the sha certificate fingerprints section in the project settings in the firebase console.
- ![image](https://user-images.githubusercontent.com/46637720/117212327-df08de00-ae02-11eb-8985-76c76d1541b2.png)
- For recaptcha cancellation, in the google cloud console of application enable "Android Device Verification" from library
![image](https://user-images.githubusercontent.com/46637720/117213473-52f7b600-ae04-11eb-8f2c-e5e423d2045c.png)

- If you run it from the emulator, it may ask for recaptcha so run it on a real device
- And enter phone number as + (country code) (number) on the first screen of the application
## UI Views
![image](https://user-images.githubusercontent.com/46637720/117212908-9bfb3a80-ae03-11eb-913f-fb825be4c503.png)
![image](https://user-images.githubusercontent.com/46637720/117213003-b9c89f80-ae03-11eb-9ae9-533463871e60.png)

For more informations:
https://firebase.google.com/docs/auth/android/phone-auth
