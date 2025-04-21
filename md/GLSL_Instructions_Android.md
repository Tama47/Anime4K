# Usage Instructions (GLSL / mpv-android) (v4.x)

## Installing and Setting Up GLSL for mpv-android on Android and Android TV
*The current version of mpv-android from the Play Store no longer support accessing the shaders files via an absolute path.
You will need ADB to access the shader files in `/storage/emulated/0/Android/data/is.xyz.mpv/files/shaders` or use the `api29` APK.*

Method 1: APK (Simplest, Recommended)

  1. Download the latest release of mpv-android `api29` APK [**here**](https://github.com/mpv-android/mpv-android/releases).
  2. After downloading the APK, click on it to install the app.
  3. After installing, you will want to grant the app access to your files.
     <br>
     <img src="https://github.com/user-attachments/assets/ada11c4f-7894-4f77-b84b-fd47e8e60ba1" width="400" />
  4. Create a folder called `mpv` in `Internal Storage`.
  5. Download and extract the shaders from <a href="https://github.com/bloc97/Anime4K/releases">releases</a> and put them in the `shaders` folder inside `mpv`.
  6. Edit your `mpv.conf` inside the app.
