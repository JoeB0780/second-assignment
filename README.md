This Flutter app demonstrates navigation using a bottom navigation bar and a drawer, featuring three screens: SignInScreen, SignUpScreen, and CalculatorScreen. Here's a brief summary:

Main Function: Starts the app with MyApp as the root widget.

MyApp:

Stateless widget that sets up a MaterialApp with a blue theme and HomeScreen as the home page.
HomeScreen:

Stateful widget managing the current index of selected navigation tab.
Defines a list of screens (SignInScreen, SignUpScreen, and CalculatorScreen).
Uses a Drawer for navigation, allowing users to select a screen from the menu.
Uses a BottomNavigationBar for tab navigation at the bottom.
SignInScreen:

Stateless widget providing a sign-in form with username and password fields.
Contains a sign-in button triggering a dialog upon successful sign-in.
SignUpScreen:

Stateless widget providing a sign-up form with name, gender, phone number, password, and confirm password fields.
Contains a sign-up button triggering a dialog upon successful sign-up.
CalculatorScreen:

Stateful widget implementing a basic calculator.
Manages calculator logic, including number input, operations, and clearing the display.
Displays the result on the screen and provides buttons for digits and operations
