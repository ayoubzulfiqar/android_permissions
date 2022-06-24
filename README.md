# android_permissions
This repo contain all the android permissions which will be add inside the app according to the requirement in our app


# Flutter Example

## AndroidManifest.xml

```xml


<manifest xmlns:android="http://schemas.android.com/apk/res/android"

    package="com.useme.useme">
    <!-- Here you have to place your permission lines -->


   <application

        android:label="useme"

        android:name="${applicationName}"

        android:icon="@mipmap/ic_launcher">

        <activity

            android:name=".MainActivity"

            android:exported="true"

            android:launchMode="singleTop"

            android:theme="@style/LaunchTheme"

            android:configChanges="orientation|keyboardHidden|keyboard|screenSize|smallestScreenSize|locale|layoutDirection|fontScale|screenLayout|density|uiMode"

            android:hardwareAccelerated="true"

            android:windowSoftInputMode="adjustResize">

            <!-- Specifies an Android theme to apply to this Activity as soon as

                 the Android process has started. This theme is visible to the user

                 while the Flutter UI initializes. After that, this theme continues

                 to determine the Window background behind the Flutter UI. -->

            <meta-data

              android:name="io.flutter.embedding.android.NormalTheme"

              android:resource="@style/NormalTheme"

              />

            <intent-filter>

                <action android:name="android.intent.action.MAIN"/>

                <category android:name="android.intent.category.LAUNCHER"/>

            </intent-filter>

        </activity>

        <!-- Don't delete the meta-data below.

             This is used by the Flutter tool to generate GeneratedPluginRegistrant.java -->

        <meta-data

            android:name="flutterEmbedding"

            android:value="2" />

    </application>

</manifest>
```
