[![](https://jitpack.io/v/pao11/RCImageViewRelease.svg)](https://jitpack.io/#pao11/RCImageViewRelease)

# 概况

## RCImageView
圆型或者圆角图片（带有边框效果），适配了ImageView的ScaleType属性

## RoundImageView
定义圆角图片，四个角圆角弧度可各自定义，也可不定义默认角度为20px.

<table>
    <tr>
        <td><img src="/image/image.png"></td>
        <td><img src="/image/image_two.png"></td>
    </tr>
</table>

## Gradle 添加引用
```
compile 'com.github.pao11:RCImageViewRelease:v1.1.0' 
```
## How to use 如何使用
```
        <com.pao11.view.RCImageView
           android:layout_width="wrap_content"
           android:layout_height="wrap_content"
           android:scaleType="centerCrop"
           android:src="@drawable/mine"
           app:type="circle" />
           
        <com.pao11.view.RoundImageView
           android:layout_width="wrap_content"
           android:layout_height="wrap_content"
           android:scaleType="centerCrop"
           android:src="@drawable/mine"
           app:round_leftUp="3dp"
           app:round_rightUp="3dp"/>
```

## about attrs 关于自定义的属性
```
	    <declare-styleable name="RCImageView">
    		<attr name="borderRadius" format="dimension"/>
    		<attr name="type">
    			<enum name="normal" value="-1"/>
    			<enum name="circle" value="0"/>
    			<enum name="round" value="1"/>
    		</attr>
    		<attr name="borderWidth" format="dimension" />
    		<attr name="borderColor" format="integer" />
    	</declare-styleable>
    
    	<declare-styleable name="RoundImageView">
    		<attr name="round_leftUp" format="dimension"/>
    		<attr name="round_leftDown" format="dimension"/>
    		<attr name="round_rightUp" format="dimension"/>
    		<attr name="round_rightDown" format="dimension"/>
    		<attr name="round_corner" format="dimension"/>
    	</declare-styleable>
 ```
 ##更新记录
 
 **v1.1.0**　`2017.10.09`　发布第二个版本
 
 **v1.0.0**　`2017.09.30`　发布第一个版本
 
 ## Copyright Notice ##
 ``` 
 Copyright (C) 2017 pao11
 
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
 

