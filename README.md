class MyHomePage extends StatelessWidget {
   MyHomePage({Key key, this.title}) : super(key: key); 
   final String title; 

   
   Widget build(BuildContext context) {
      return Scaffold( 
         appBar: ( title: Text(this.title), ), 
         body: Center( child: Image.asset("smiley.png")),
      ); 
   }
}
