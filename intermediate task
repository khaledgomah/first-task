import 'dart:io';

import 'dart:math';

void main(List<String> args) {
  // area();
  // extension();
  // difference();
  // prime();
  //colors();
  //vowel();
  //backward();
  //trim();
  randomNumber();
}

void area() {
  const double pay = 3.14;
  print('Enter the radius of a circle');
  double r = double.parse(stdin.readLineSync()!);
  double area = r * pay * pay;
  print('Area = $area');
}

void extension() {
  print('Enter the file name');
  String file = stdin.readLineSync()!;
  List<String> extension = file.split('.');
  print(extension[1]);
}

void difference() {
  const int ref = 23;
  int res;
  print('Enter the number');
  int num = int.parse(stdin.readLineSync()!);
  if (num > ref) {
    res = 2 * (num - ref);
  } else {
    res = ref - num;
  }
  print(res);
}

void prime() {
  int x;
  for (var i = 2; i <= 100; i++) {
    x = 0;
    for (var j = i - 1; j >= 2; j--) {
      if (i % j == 0) {
        x++;
      }
    }
    if (x == 0) {
      print('  $i');
    }
  }
}

void colors() {
  List color = ["Red", "Green", "White", "Black"];
  print('First color is ${color.first}');
  print('Last color is ${color.last}');
}

void vowel() {
  print('Enter the letter');
  String letter = stdin.readLineSync()!;
  letter.toLowerCase();
  if (letter == 'a' ||
      letter == 'u' ||
      letter == 'o' ||
      letter == 'y' ||
      letter == 'e') {
    print('the letter is vowel');
  } else {
    print('the letter is not vowel');
  }
}

void backward() {
  print('Enter the a long string containing multiple words');
  String words = stdin.readLineSync()!;
  List<String> splited = words.split(' ');
  Iterable<String> reversed = splited.reversed;
  print(reversed);
}

void whiteSpaceRemover() {
  print('Enter the String');
  String x = stdin.readLineSync()!;
  print(x.replaceAll(' ', ''));
}

void randomNumber() {
  int? x = generateRandom();
  int status = 0;
  if (x == 100) {
    status = 100;
  }

  print(status);
}

int? generateRandom() {
  Random random = new Random();
  bool x = random.nextBool();
  int? returnNum;

  if (x == true) {
    returnNum = 100;
  } else {
    returnNum = null;
  }
  return returnNum;
}
