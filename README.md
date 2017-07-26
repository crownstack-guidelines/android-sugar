

## Welcome to Sugar classes Guidelines:

* [FileUtils](https://github.com/CrownStack/android-sugar/blob/dev/README.md#fileutils)
* [Gallery](https://github.com/CrownStack/android-sugar/blob/dev/README.md#gallery)
* [ImageHelper](https://github.com/CrownStack/android-sugar/blob/dev/README.md#imagehelper)
* [IntentHelper](https://github.com/CrownStack/android-sugar/blob/dev/README.md#intenthelper)
* [Message](https://github.com/CrownStack/android-sugar/blob/dev/README.md#message)
* [NetworkHelper](https://github.com/CrownStack/android-sugar/blob/dev/README.md#networkhelper)
* [ProgressHelper](https://github.com/CrownStack/android-sugar/blob/dev/README.md#progresshelper)

### [FileUtils](https://github.com/CrownStack/android-sugar/blob/dev/FileUtils.java)
* getPath(final Context context, final Uri uri): To get file path from Uri.

### [Gallery](https://github.com/CrownStack/android-sugar/blob/dev/Gallery.java)
* openPhoto(final int RequestCode): To choose image from Gallery.

### [ImageHelper](https://github.com/CrownStack/android-sugar/blob/dev/ImageHelper.java)
* getBitmapFromGalleryIntent(Context context, Intent data): Convert it into bitMap from gallery Intent.

### [IntentHelper](https://github.com/CrownStack/android-sugar/blob/dev/IntentHelper.java)
* openWebBrowserIntent(String url): Open url in web browser.
* callNumberIntent(String phoneNumber): Make a call on passing number.
  
### [Message](https://github.com/CrownStack/android-sugar/blob/dev/Message.java)
* message(Context context, String message): To show toast message.

### [NetworkHelper](https://github.com/CrownStack/android-sugar/blob/dev/NetworkHelper.java)
* IsOn(final Context ctx): To check Internet connection.

### [ProgressHelper](https://github.com/CrownStack/android-sugar/blob/dev/ProgressHelper.java)
* start(Context context, String message): To start ProgressDialog.
* stop(): To stop ProgressDialog.

