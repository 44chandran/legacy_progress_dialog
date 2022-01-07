# progress_dialog

Helps developers improve user-experience using a progress indicator and a loading message.

# Deprecation warning

## Now embedded in [`dialogs`](https://pub.dev/packages/dialogs)

## Getting Started
### Install
Add dependency to pubspec.yaml file :
`legacy_progress_dialog: ^0.0.9`

Run this command :
`$ flutter pub get`

### Import
Import class in your project :
`import 'package:legacy_progress_dialog/legacy_progress_dialog.dart';`

### Show progress dialog :
<Img src="https://raw.githubusercontent.com/asadamatic/Progress-Dialog/master/open.png" align = "top" height = "350" height="300em" />

```
//Create an instance of ProgressDialog
ProgressDialog progressDialog = ProgressDialog(
                  context: context,
                  backgroundColor: Colors.blue,
                  textColor: Colors.White,
                );
// show dialog
progressDialog.show();

//close dialog
progressDialog.dismiss();
```
