import 'package:flutter/material.dart';

void main() {
  runApp(MyApp(
    TextInput: new Text("Hello "),
  ));
}

class MyApp extends StatelessWidget {
  final Widget TextInput;
  MyApp({this.TextInput});

  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    return new MaterialApp(
      title: "MyApp",
      home: new Scaffold(
        appBar: new AppBar(
          title: new Text("Hello Flutter"),
        ),
        body: new Center(
          child: new Column(
            children: <Widget>[
              TextInput
            ],
          ),
        ),
      ),
    );
  }
}
