# l1t2_authorizationn

Lecture 1 - Task 2 : Authorizationn

## Getting Started

 - Show a splash screen with a full screen image for 3 seconds:
 
 We have a main() function which calls runApp() by taking any widget as an argument to create the layout. Then we have the home as MyHomePage() which is a stateful class(Mutable class). MyHomePage() returns a Container which has a child as FlutterLogo(which will be shown initially when app starts). Now, we have one most important method which is initState(). initState() method called once when the stateful widget is inserted in the widget tree. initState() first call super.initState() and then Timer of duration 4 seconds(Timer function has 2 arguments,first is Duration and second is action to be performed). After 4 seconds,Current screen will be replaced by new Screen i.e. SecondScreen() . We can also use Asset Image/Network Image instead of FlutterLogo.
 ### 26.10.2022

//TODO

 - Display a screen with input fields for "login", "password", a "remember" checkbox and a "next" button.
 - If login = "admin" and password = "123456" then show the following screen with the text "Congratulations!".
 - If login = "admin" and password = "123456" then show the following screen with the text "Congratulations!".
 - If the login and password are incorrect, show the user a message about this.
- If the login was correct and there was a "remember" checkmark, then the next time after the splash, immediately open the "Congratulations!" screen.