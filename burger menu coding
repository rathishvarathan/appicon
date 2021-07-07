import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData(
        // This is the theme of your application.
        //
        // Try running your application with "flutter run". You'll see the
        // application has a blue toolbar. Then, without quitting the app, try
        // changing the primarySwatch below to Colors.green and then invoke
        // "hot reload" (press "r" in the console where you ran "flutter run",
        // or simply save your changes to "hot reload" in a Flutter IDE).
        // Notice that the counter didn't reset back to zero; the application
        // is not restarted.
        primarySwatch: Colors.blue,
      ),
      home: MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

class MyHomePage extends StatefulWidget {
  MyHomePage({Key? key, required this.title}) : super(key: key);

  // This widget is the home page of your application. It is stateful, meaning
  // that it has a State object (defined below) that contains fields that affect
  // how it looks.

  // This class is the configuration for the state. It holds the values (in this
  // case the title) provided by the parent (in this case the App widget) and
  // used by the build method of the State. Fields in a Widget subclass are
  // always marked "final".

  final String title;

  @override
  _MyHomePageState createState() => _MyHomePageState();
}

class _MyHomePageState extends State<MyHomePage> {
  int _counter = 0;

  void _incrementCounter() {
    setState(() {
      // This call to setState tells the Flutter framework that something has
      // changed in this State, which causes it to rerun the build method below
      // so that the display can reflect the updated values. If we changed
      // _counter without calling setState(), then the build method would not be
      // called again, and so nothing would appear to happen.
      _counter++;
    });
  }

  @override
  Widget build(BuildContext context) {
    // This method is rerun every time setState is called, for instance as done
    // by the _incrementCounter method above.
    //
    // The Flutter framework has been optimized to make rerunning build methods
    // fast, so that you can just rebuild anything that needs updating rather
    // than having to individually change instances of widgets.
    return Scaffold(
      appBar: AppBar(
        backgroundColor:Colors.blueAccent,
        centerTitle: true,
        title:Text("session 3",style: TextStyle(fontSize:35.0)),
        //leading: Icon(Icons.home),
        actions: [
          Icon(Icons.login),
          Icon(Icons.login),
        ],
      ),
      drawer: Drawer(
        child:Column(children: 
        [
          //Container(
            
            //child: Text("welcome userA")),
          ListTile(
            title:Text("log in"),
            trailing:Icon(Icons.login),
          ),
            Divider(thickness: 2,color: Colors.black),
            ListTile(
            title:Text("log out"),
            trailing:Icon(Icons.logout),
            ), 
            Divider(thickness: 2,color: Colors.black), 
            ListTile(
            title:Text(" help"),
            trailing:Icon(Icons.help),
            ),
            Divider(thickness: 2,color: Colors.black),
            ListTile(
            title:Text("support"),
            trailing:Icon(Icons.support),
            ),
        ],),
    ),
      body: Center(
        child:ListView(
          //mainAxisAlignment: MainAxisAlignment.center,
          children: <Widget>[
          Row(
            children: [
              Icon(Icons.ac_unit_sharp,size:90.0,color:Colors.blue),
              Icon(Icons.accessibility_new_sharp,size:90.0,color:Colors.lightGreen),
              Icon(Icons.add_alarm_outlined,size:90.0,color:Colors.lightGreen),
            ],
          ),
      
          ElevatedButton(onPressed:(){

          },child:Text ("submit")),
            Container(
              child: Row(
                crossAxisAlignment: CrossAxisAlignment.center,
                children:[
                Expanded(child:Image.network("https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/YouTube_social_white_square_%282017%29.svg/1200px-YouTube_social_white_square_%282017%29.svg.png")),
                
                Expanded(
                  flex: 2,
                  child:Image.network("https://image.shutterstock.com/image-photo/valencia-spain-march-05-2017-260nw-593204357.jpg")),
                
                Expanded(
                flex :3,
                child: Image.network("https://play-lh.googleusercontent.com/8r-ZTPoTIywU_aK2OXmLKg5WOdzXRxv7UUpiIk7kY7Du12fXKDwxUb2M_vBFp4pPvmpK")),
                ],
              ),
            ),
            Image .network("https://upload.wikimedia.org/wikipedia/en/a/a9/MarioNSMBUDeluxe.png"),
          
            Text(
              'WELCOME', style:TextStyle(color:Colors.amberAccent,fontSize: 45.0)
            ),
            Text(
              '$_counter',
              style: Theme.of(context).textTheme.headline4,
            ),
          ],
        ),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: _incrementCounter,
        tooltip: 'Increment',
        child: Icon(Icons.add),
      ), // This trailing comma makes auto-formatting nicer for build methods.
    );
  }
}
