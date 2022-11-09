<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

TODO: Put a short description of the package here that helps potential users
know whether this package might be useful for them.

## Features

TODO: List what your package can do. Maybe include images, gifs, or videos.

## Getting started

TODO: List prerequisites and provide or point to information on how to
start using the package.

## Usage

TODO: Include short and useful examples for package users. Add longer examples
to `/example` folder.

```dart
// Example Code

class AppNewVersion extends StatefulWidget {
  const AppNewVersion({Key? key}) : super(key: key);

  @override
  State<AppNewVersion> createState() => _AppNewVersionState();
}

class _AppNewVersionState extends State<AppNewVersion> {

  @override
  void initState() {
    // TODO: implement initState
    super.initState();
    NewVersionCheck.newVersionCheck(context, "androidPackageName", "iosPackageName");
  }
  @override
  Widget build(BuildContext context) {
    return Container();
  }

}




```



[comment]: <> (<td>)

[comment]: <> (<img src="https://firebasestorage.googleapis.com/v0/b/mdfreefirefreediamond.appspot.com/o/Screenshot%202022-11-09%20at%201.00.21%20PM.png?alt=media&token=3c51bb95-55ba-42b7-aee3-c36974098712">)

[comment]: <> (</td>)

## Additional information

TODO: Tell users more about the package: where to find more information, how to
contribute to the package, how to file issues, what response they can expect
from the package authors, and more.
