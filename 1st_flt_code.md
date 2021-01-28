import 'package:flutter/material.dart';

void main() {
  runApp(ExploreWidgets());
}

class ExploreWidgets extends StatelessWidget{
  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Exploring Widgets")
        ),
        body: Container(
          child: Center(
            child: Text("Hello Flutter", style: TextStyle(color: Colors.white))
          ),
          color: Colors.blue
        ),
      ),
    );
  }
}