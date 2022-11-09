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

TODO: check your app new version

## Features

TODO: esy to check new app version and beautifully alert dialog .

## Getting started

TODO: To use this package, add new_app_version_alert as a dependency in your pubspec.yaml file.

## Usage

TODO: NewVersionCheck.newVersionCheck(context, "androidPackageName", "iosPackageName");

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



<td>
<img src="https://firebasestorage.googleapis.com/v0/b/mdfreefirefreediamond.appspot.com/o/Screenshot%202022-11-09%20at%201.00.21%20PM.png?alt=media&token=3c51bb95-55ba-42b7-aee3-c36974098712">
</td>


