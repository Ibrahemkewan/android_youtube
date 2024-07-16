
# Android YouTube Clone

This is an Android application that mimics the basic functionality of YouTube. Users can register, log in, upload videos, and view a list of uploaded videos. Each video has a detailed view as well.

## Features

- User Registration and Login
- Add and Upload Videos
- List of Uploaded Videos
- Detailed View for Each Video

## Layout Files

- `activity_add_video.xml` - Layout for adding new videos.
- `activity_login.xml` - Layout for the login screen.
- `activity_main.xml` - Main layout file.
- `activity_register.xml` - Layout for user registration.
- `activity_video_detail.xml` - Layout for the video detail view.
- `activity_video_list.xml` - Layout for listing all videos.
- `item_video.xml` - Layout for each video item in the list.

## Java Classes

- `AddVideoActivity.java` - Handles the functionality for adding videos.
- `LoginActivity.java` - Manages user login functionality.
- `MainActivity.java` - The main entry point of the application.
- `RegisterActivity.java` - Manages user registration functionality.
- `Video.java` - Model class for video objects.
- `VideoAdapter.java` - Adapter class for binding video data to the list.
- `VideoDetailActivity.java` - Manages the detailed view of each video.
- `VideoListActivity.java` - Displays the list of all videos.

## Installation and Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Ibrahemkewan/android_youtube.git
   cd android_youtube
   ```

2. **Open the project in Android Studio:**
   - Launch Android Studio.
   - Select `Open an existing project`.
   - Navigate to the cloned directory and select it.

3. **Build the project:**
   - Allow Android Studio to build the project and resolve any dependencies.
   - Ensure you have the latest Android SDK and necessary build tools installed.

4. **Run the application:**
   - Connect an Android device or start an emulator.
   - Click on the `Run` button in Android Studio or use `Shift + F10`.

## Dependencies

Ensure you have the following dependencies in your `build.gradle` file:
```gradle
dependencies {
    implementation("androidx.appcompat:appcompat:1.6.1")
    implementation("com.google.android.material:material:1.11.0")
    implementation("androidx.constraintlayout:constraintlayout:2.1.4")
    testImplementation("junit:junit:4.13.2")
    androidTestImplementation("androidx.test.ext:junit:1.1.5")
    androidTestImplementation("androidx.test.espresso:espresso-core:3.5.1")
    implementation("com.github.bumptech.glide:glide:4.12.0")
    annotationProcessor("com.github.bumptech.glide:compiler:4.12.0")
    implementation("com.google.code.gson:gson:2.8.8")
}
```

## Permissions

Ensure the following permission is added to your `AndroidManifest.xml`:
```xml
<uses-permission android:name="android.permission.INTERNET" />
```

## Usage

- **Register**: Create a new user account.
- **Login**: Access the app using registered credentials.
- **Add Video**: Upload a new video.
- **View Videos**: Browse the list of uploaded videos.
- **Video Detail**: View details of a selected video.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests for any improvements.

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, please reach out to [your email].

