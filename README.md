# meizu_systemui_overlay
This is an overlay app for `com.android.systemui`,its only for **meizu 20 pro** with **Flyme 11.24.9.10 daily**
***
The next step is to redraw and supplement the status bar notification icon.The icon drawn by Meizu is located at`/res/values/arrays.xml`.There are two arrays defined here,`internal_app_icon_names`&`internal_app_icon_values`.The elements in them correspond to each other.First declare the package name in `internal_app_icon_names`, and then reference the resource placed in the `drawable` folder in the corresponding position of `internal_app_icon_values`
