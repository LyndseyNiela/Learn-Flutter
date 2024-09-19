import 'package:flutter/material.dart';

// The main function is the entry point of the Flutter app.
void main() {
runApp(MyApp());
}

// MyApp is a stateless widget that represents the app itself.
class MyApp extends StatelessWidget {
@override
Widget build(BuildContext context) {
return MaterialApp(
// The MaterialApp is the root of the app and provides basic structure.
home: Scaffold(
appBar: AppBar(
// AppBar widget to display a title at the top of the screen.
title: Text('Flutter Demo'),
),
body: Center(
// Center widget to center the text widget.
child: Text(
'Hello, World There!',
style: TextStyle(fontSize: 24), // Sets the text size to 24.
),
),
),
);