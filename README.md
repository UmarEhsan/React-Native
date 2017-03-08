# React-Native
<h1>React native for Beginners</h1>

<h2>What is React Native?</h2>

1)Framework for building mobile apps using javascript and the react library<br>
2)Build cross platform apps(Android/IOS)<br>
3)Uses almost all react.js concepts including components, state, props, lifecycle, etc<br>
4)React Native apps are not hybrid apps<br>
  a)They don't run in webview.<br>
  b)They uses the same fundamental building blocks as a native app built with swift/Objective-C/java<br>
  c)Better and faster than Cordova/PhneGap/Ionic<br>


<h3>Development Environment</h3>
<h2>Windows</h2><br>
  a)Android Studio<br>
  b)Android SDK(6.0 Marshmallow)<br>
  c)Android AVD<br>


<h3>Installation</h3>
Make Sure you have install nodejs
If you install nodejs then install react-native-cli

Open your command prompt(cmd) and run
1#)npm install -g react-native-cli
2#)npm install -g yarn

create your app by following command
react-native init "App Name"

<p>navigate to your project</p> 
<p>cd "App Name" then run react-native start inside the newly created folder to start the packager.</p>
<p>Open a new command prompt and run <strong>react-native run-android</run> inside the same folder to launch the app on your AVD.</p>

<p>If you get any error something like this<br>
* What went wrong:<br>
A problem occurred configuring project ':app'.<br>
> SDK location not found. Define location with sdk.dir in the local.properties file or with an ANDROID_HOME environment variable.<br></p>

<h4>Solution</h4><br>

<ul>
<li>Go to the android/ directory of your react-native project<li>
<li>Create a file called local.properties with this line:</li>
</ul>
<p>sdk.dir=C\:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk<br>
properly write this formate, and also check / slas using for path</p>
