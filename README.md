# Shop24x7-Engage
Shop24x7 is a demonstration of platform for you to get products recommended according to your requirement. This platform was built during Engage’22. If you want to dive in directly and use the platform for your shopping requirements, you can refer to this video.

## Features
1. 	Make your user profile and on basis of attributes you’ll get recommended products.
2.	Sign up/ Sign In users.
3.	Face recognition.
4.	Responsive UI.
5.	Manage your user profile.
---
## Technologies used
-	**Node.js** – An open-source, cross-platform, back-end JavaScript runtime environment used to run the applications.
-	**React JS** - a free and open-source front-end JavaScript library for building user interfaces or UI components. Maintained by Facebook React is used to develop single page progressive web apps
-	**Firebase** – A cloud-hosted Realtime NoSQL database used to store and sync data between users in Realtime. Also used to authenticate and manage users.
-	**Azure API** – The Azure Face service provides AI algorithms that detect, recognize, and analyze human faces in images. Facial recognition software is important in many different scenarios, such as identity verification, touchless access control, and face blurring for privacy.
---
## Azure API used
Shop24x7 uses the Azure Face service provides AI algorithms that detect, recognize, and analyze human faces in images for creating RealTime communication applications. 
> There were few attributes/features which can be detected by Face – Detect API. The following attributes can be detected:
>- ***Accessories. *** Whether the given face has accessories. This attribute returns possible accessories including headwear, glasses, and mask, with confidence score between zero and one for each accessory.
>- ***Age. *** The estimated age in years of a particular face.
>- ***Blur. *** The blurriness of the face in the image. This attribute returns a value between zero and one and an informal rating of low, medium, or high.
>- ***Emotion. *** A list of emotions with their detection confidence for the given face. Confidence scores are normalized, and the scores across all emotions add up to one. The emotions returned are happiness, sadness, neutral, anger, contempt, disgust, surprise, and fear.
>- ***Exposure. *** The exposure of the face in the image. This attribute returns a value between zero and one and an informal rating of underExposure, goodExposure, or overExposure.
>- ***Facial hair. *** The estimated facial hair presence and the length for the given face.
>- ***Gender. *** The estimated gender of the given face. Possible values are male, female, and genderless.
>- ***Glasses. *** Whether the given face has eyeglasses. Possible values are NoGlasses, ReadingGlasses, Sunglasses, and Swimming Goggles.
>- ***Hair. *** The hair type of the face. This attribute shows whether the hair is visible, whether baldness is detected, and what hair colours are detected.
>- ***Head pose. *** The face's orientation in 3D space. This attribute is described by the roll, yaw, and pitch angles in degrees, which are defined according to the right-hand rule. The order of three angles is roll-yaw-pitch, and each angle's value range is from -180 degrees to 180 degrees. 3D orientation of the face is estimated by the roll, yaw, and pitch angles in order. 
>- ***Makeup. *** Whether the face has makeup. This attribute returns a Boolean value for eyeMakeup and lipMakeup.
>- ***Mask. *** Whether the face is wearing a mask. This attribute returns a possible mask type, and a Boolean value to indicate whether nose and mouth are covered.
>- ***Noise. *** The visual noise detected in the face image. This attribute returns a value between zero and one and an informal rating of low, medium, or high.
>- ***Occlusion. *** Whether there are objects blocking parts of the face. This attribute returns a Boolean value for eyeOccluded, foreheadOccluded, and mouthOccluded.
>- ***Smile. *** The smile expression of the given face. This value is between zero for no smile and one for a clear smile.
>- ***Quality For Recognition*** The overall image quality regarding whether the image being used in the detection is of sufficient quality to attempt face recognition on. The value is an informal rating of low, medium, or high. Only "high" quality images are recommended for person enrollment, and quality at or above "medium" is recommended for identification scenarios.
I went on to use few attributes which suits the best for my application requirements. For more details refer to [Project Documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/face/concepts/face-detection).
---
## Installation
In the project directory, run `npm install` to install all the dependencis. then run `npm start` to run the application on localhost. Use `npm run build` to create a production build (in **\build** folder) for deployment.
### Dependencies
Shop24x7 runs on **Node js** and uses **React JS** for front end and
Following the dependencies used by Shop24x7 :
- @emotion/react
- @emotion/styled
- @mui/icons-material
- @mui/material
- @testing-library/jest-dom
- @testing-library/react
- @testing-library/user-event
- axios
- firebase
- react
- react-dom
- react-firebase-hooks
- react-router-dom
- react-scripts
- react-webcam
- web-vitals

# Getting Started with Create React App

This project was created with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
