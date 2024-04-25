---
Title: '.toInt()'
Description: 'Turns numberic values into integers and returns them.'
Subjects:
  - 'Computer Science'
  - 'Web Development'
Tags:
  - 'Methods'
  - 'Dart'
  - 'Numbers'
  - 'Types'
CatalogContent:
  - 'learn-dart'
  - 'paths/computer-science'
---

In Dart, the **`.toInt()`** method converts numeric values into integers. This method is the most useful when numeric values need to be treated as integers.

## Syntax

```pseudo
number.toInt()
```

- `number`: Chosen numeric value that needs to be converted into an integer value.

## Example

In the following example, the `.toInt()` method is used to turn `myNumber` (10.4) into an integer value.

```dart
void main() {
  var myNumber = 10.4;
  myNumber = myNumber.toInt();
  print(myNumber);
```

The code will return the following output

```dart
10
```