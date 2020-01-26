# 8BallApp

This is my first IOS application.  It has been created by using XCode and by using Swift!  The app mimics the function of an actual 8 ball (the one that you shake around and get a random answer to your question).

This application's functionality is fairly simple.  I have created a UI in Xcode by using the storyboard.  The UI consists of "Shake it!" button and a label.  There is also a MotionEnded event listener function incorporated into the application.  

When the "Shake it!" button is pressed, the label's text (which previously had default text inserted into it's textbox) is changed to a random phrase.  The phrase is derived from a String array with 30 phrases inside of it.  An Int.Random() function is used to decide which of the phrases is chosen. The text inside the label is also changed whenever the Iphone is shaken.
