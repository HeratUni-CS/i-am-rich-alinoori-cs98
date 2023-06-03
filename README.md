import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.blueGrey[900],
        appBar: AppBar(
          backgroundColor: Colors.blueGrey,
          title: Center(
            child: Text('I am Rich'),
          ),
        ),
        body: Center(
          child: Image(
            image: AssetImage('images/money.png'),
            )
        ),
      ),
    ),
  );
}
