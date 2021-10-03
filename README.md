
Rounded Letter View
---------------------
- Add rectangular and circle shape background to your text
- Adding rectangular support to https://github.com/pavlospt/RoundedLetterView

<img src="https://github.com/Nageshks/android_rounded_letter_view/blob/main/screenshot.png" width="360" height="780">

Usage
-------

```xml
    <com.nageshempire.roundedletterview.RoundedLetterView
        android:layout_width="48dp"
        android:layout_height="48dp"
        app:rlv_backgroundColor="@color/black"
        app:rlv_round="0.25"
        app:rlv_titleColor="@android:color/holo_red_dark"
        app:rlv_titleSize="30dp"
        app:rlv_titleText="C" />
```

### Control Shape
``` xml
app:rlv_round="@dimen/rlv_shape_circle"
app:rlv_round="@dimen/rlv_shape_rectangle"
app:rlv_round="@dimen/rlv_shape_rounded_rectangle"
app:rlv_round="0.25"
```

``` java
letterView.setRounding(floatValue)
```
Download
--------

```groovy
implementation("io.github.nageshks.roundedletterview:roundedletterview:1.0.0")
```

License
-------

    Copyright (C) 2021 Nagesh Empire

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

