# sliding_switch

Sliding Switch - A simple switch widget. It can be fully customized with desired width, colors, text etc. It also maintains selection state.

## Live Demo (Codeapprun)

[![codeapprun.io](https://storage.googleapis.com/s3.codeapprun.io/assets/badge.svg)](codeapprun_widget_url)
## Getting Started

In the `pubspec.yaml` of your flutter project, add the following dependency:

```yaml
dependencies:
  ...
  sliding_switch: "latest"
```

Import it:

```dart
import 'package:sliding_switch/sliding_switch.dart';
```

## Usage Examples

### Minimum sliding switch configuration

```dart
SlidingSwitch(
 value: false,
 width: 250,
 onChanged: (bool value) {
   print(value);
 },
)
```

![sliding switch](https://storage.googleapis.com/s3.codeapprun.io/assets/sliding_gif.gif)

### sliding switch other configurations

```dart
SlidingSwitch(
 value: false,
 width: 250,
 onChanged: (bool value) {
   print(value);
 },
 height : 55,
 animationDuration : const Duration(milliseconds: 400),
 onTap:(){},
 onDoubleTap:(){},
 onSwipe:(){},
 textOff : "Female",
 textOn : "Male",
 colorOn : const Color(0xffdc6c73),
 colorOff : const Color(0xff6682c0),
 background : const Color(0xffe4e5eb),
 buttonColor : const Color(0xfff7f5f7),
 inactiveColor : const Color(0xff636f7b),
),
```
Licensed Under the [MIT License](LICENSE).

## Inspiration

[Jitu Raut](https://dribbble.com/shots/6190542-BMI-Calculator-Interaction)