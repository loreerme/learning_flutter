import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return new MaterialApp(
      title: "MySample",
      home: new Scaffold(
        appBar: new AppBar(
          title: new Text("My Second Flutter App")
        ),
        body: new Center(
          child: new Column(
            children: <Widget>[
              new Text("Hello"),
              new Text("World")
            ]

          )

      ),
      ),
    );
  }
}
