## Stay Tangible and Pixinote React Native Coding Challenge
Please read the instructions carefully. Projects that do not include all elements of this challenge will be sadly rejected.

## Overview
To complete this challenge, you will need to write a simple React Native app and provide us the source files with version control(.git). The primary purpose of this challenge is to assess your coding, structural, naming, and state management skills as well as your approach to composing a simple app given a set of screens and a REST API.

It is expected to take about 2-4 hours. Please do not spend any more time on it than that.

## The Challenge
It's pretty simple. Using the provided screens as a reference, you'll need to build a set of components to render the app. You'll also need to request a JSON resource.

## App Details
You will need to build the following screens:

A "Home" screen<br />
An "Albums" screen<br />
An "Album" screen

##### Home
Refer to the `screens/home.jpg` screen. Show a list of "liked" albums.

##### Albums
Refer to the `screens/albums.jpg` screen. The user should be able to like or dislike an album.

##### Album
Refer to the `screens/album.jpg` screen. The user should be able to read some text about the album.

You can fetch JSON resources from here [JSON Placeholder](https://jsonplaceholder.typicode.com/). You'll have to replace the album images with images of your choice. Please use a unique image for each album. We have used [Place Kitten](https://placekitten.com) in our example and you are welcome to use it too. Assets are located in `/assets`—use them.

You will also need to handle the loading and error states of fetching the JSON resources. How you do that is up to you.

## Additional Requirements
We want to run this project and see it working! Please submit your project on GitHub or similar platform, and include a README file with complete install and setup instructions and other documentation you created as part of your solution.

Add the following info to your README:

- Complete setup instructions
- How did you decide on the technical and architectural choices used as part of your solution?
- Are there any improvements you could make to your submission?
- What would you do differently if you were allocated more time?

One last thing–We prefer it if you did not use any third party CSS frameworks and _keep your dependencies to a minimum_.

## Bonus points
- Commit history. We want to see your thought process and revisions.
- Display how scalable your app is. What would the organizational structure look like if you knew it would have 50+ screens and hundreds of components?

## FAQ
- What language, framework, build tool, etc should I use?<br />
You may use whatever you like as long as the solution is built using React Native.
- Can I use Expo or similar?<br />
Yes! In fact, we welcome it.
- Can I use a starter kit or other boilerplate for my project?<br />
We'd prefer you didn't, but if you have a project structure you've worked with before, then by all means, use it. However, if there is any code in your repo that is not specific to this project, we won't be able to accept it your submission.
- What should I use for state management?<br />
Although this challenge is simple enough that you may not need a state management library, we would like to see some version of global state management to assess your skills. We use Redux, but you are welcome to use whatever library you are comfortable with.
