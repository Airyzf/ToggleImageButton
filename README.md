ToggleImageButton
===============
[![Android
Arsenal](https://img.shields.io/badge/Android%20Arsenal-ToggleImageButton-green.svg?style=true)](https://android-arsenal.com/details/1/3297)

A library which extends ToggleButton to allow for a button that toggles between two images.

<img src="https://raw.githubusercontent.com/csdodd/ToggleImageButton/master/demo.gif" width="350">

Gradle
------
```groovy
dependencies {
    compile 'net.colindodd:toggleimagebutton:1.2'
}
```

Usage
-----
```xml
<net.colindodd.toggleimagebutton.ToggleImageButton
    xmlns:tib="http://schemas.android.com/apk/res-auto"
    android:layout_width="75dp"
    android:layout_height="75dp"
    tib:tib_drawable_on="@drawable/on_image"
    tib:tib_drawable_off="@drawable/off_image" />
```

License
-------

    Copyright 2016 Colin Dodd

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
