# AutoResizeEditText

[![](https://jitpack.io/v/VictorMinerva/AutoResizeEditText.svg)](https://jitpack.io/#VictorMinerva/AutoResizeEditText)

![Arsenal Android](https://img.shields.io/badge/Android%20Arsenal-AutoResizeEditText-green.svg?style=flat)

A EditText that resizes its text to be no larger than the width of the display.

![Example Image](/web/static/autoresizeedittext.gif?raw=true)

## Usage

**Step 1.** Add the JitPack repository to your build file 
  Add it in your root build.gradle at the end of repositories:

```cson
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```  
 
**Step 2.** Add the dependency:
  
```cson
dependencies {
  compile 'com.github.victorminerva:AutoResizeEditText:0.1.0'
}
```

**Step 3.** Add in your layout:

```xml
<com.victorminerva.widget.edittext.AutofitEdittext
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:background="@android:color/transparent"
    android:maxLength="50"
    android:maxLines="2"
    android:padding="8dp"
    android:textSize="44sp"/>
```



## MIT License

Copyright (c) 2017 Victor Minerva

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
