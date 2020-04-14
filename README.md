[![Build Status](https://travis-ci.org/kevmoo/stats.svg?branch=master)](https://travis-ci.org/kevmoo/stats)
![Pub](https://img.shields.io/pub/v/stats.svg)

```dart
import 'package:stats/stats.dart';

void main() {
  final input = [1, 2, 3, 4, 5, 6, 7, 8];
  print('Input: $input');
  final stats = Stats.fromData(input);
  print(stats.withPrecision(3));
  // {
  //  "count": 8,
  //  "average": 4.5,
  //  "min": 1,
  //  "max": 8,
  //  "median": 4.5,
  //  "standardDeviation": 2.29
  // }
}
```
