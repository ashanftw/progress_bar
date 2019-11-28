# simple_progress_bar

Curved Progressbar that customize color, font , dialog box and border.

## Demo

![Sample Demo](https://github.com/ashanftw/progress_bar/raw/master/Screenshot_1574790383.png)

## How to use

In your pubspec.yaml, include the package
```
dependencies:
  flutter:
    sdk: flutter

  simple_progress_bar: ^0.0.3
```

In your code, add import
```
import 'package:simple_progress_bar/progress_bar.dart';
```

Then add the widget to your screen
```
    new ProgressBar(
      padding: 5,
      barColor: Color(0XFF302F4D),
      barHeight: 15,
      barWidth: width,
      numerator: 3,
      denominator: 10,
      title: 'Annual leave',
      dialogTextStyle: new TextStyle(
          fontSize: 10,
          fontWeight: FontWeight.bold,
          color: Colors.white),
      titleStyle: new TextStyle(
          fontSize: 12,
          fontWeight: FontWeight.bold,
          color: Color(0XFF3C6E71)),
      boarderColor: Colors.grey,
    ),
    new ProgressBar(
      padding: 5,
      barColor: Color(0XFFFFA187),
      barHeight: 15,
      barWidth: width,
      numerator: 23,
      denominator: 25,
      title: 'Medical leave',
      dialogTextStyle: new TextStyle(
          fontSize: 10,
          fontWeight: FontWeight.bold,
          color: Colors.white),
      titleStyle: new TextStyle(
          fontSize: 12,
          fontWeight: FontWeight.bold,
          color: Color(0XFF3C6E71)),
      boarderColor: Colors.grey,
    ),
    new ProgressBar(
      padding: 5,
      barColor: Color(0XFF6B2737),
      barHeight: 15,
      barWidth: width,
      numerator: 6,
      denominator: 8,
      title: 'Casual leave',
      dialogTextStyle: new TextStyle(
          fontSize: 10,
          fontWeight: FontWeight.bold,
          color: Colors.white),
      titleStyle: new TextStyle(
          fontSize: 12,
          fontWeight: FontWeight.bold,
          color: Color(0XFF3C6E71)),
      boarderColor: Colors.grey,
    ),
```

Sample code: https://github.com/ashanftw/progress_bar
