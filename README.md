

# ParallaxViewPager


## Demo 

<img src="https://github.com/ybq/ParallaxViewPager/raw/master/art/screen.gif" width="120px" height="213px"/>

 

## Usage
```xml
 <com.github.ybq.parallaxviewpager.ParallaxViewPager
        android:id="@+id/viewpager"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        pv:interpolator="@anim/decelerate_interpolator"
        pv:mode="right_overlay"
        pv:outset="62%"
        pv:shadow_width="30dp"/>
``` 

## Gradle Dependency
 1. Add the JitPack repository to your build file

	```gradle
	allprojects {
				repositories {
					...
					maven { url "https://jitpack.io" }
				}
	}
	```

 2. Add the dependency

    ``` gradle
    dependencies {
       implementation 'com.github.Mystery00:ParallaxViewPager:3.0.0'
     }
``` 


##LICENSE
```
Copyright 2015 ybq

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```



