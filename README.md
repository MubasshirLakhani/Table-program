import 'dart:io';

void main() {
  // print("Which Table do you wants to print?");
  // var tablenumber = int.parse(stdin.readLineSync()!);
  // print("Table of ${tablenumber} is given below");
  // for (var i = 1; i <= 10; i++) {
  //   print("$tablenumber X $i ${i * tablenumber}");
  // }
  var isloggedin = false;
  while (isloggedin == false) {
    print("Enter your Email");
    var email = stdin.readLineSync();
    print("Enter your Password");
    var password = stdin.readLineSync();
    if (email == "mubashirlakhani11@gmail.com" && password == "noormlakhani") {
      print("****************Login Successful****************");
      isloggedin = true;
    } else {
      print("XXXXXXXX Login Failed XXXXXXXX");
      isloggedin = false;
    }
  }
}
