##Android NumberProgressBar

-----

The NumberProgressBar is a bar, slim and sexy (every man wants! ). 

I decided to do this beacause I'was really tierd of android original progressbar. So, I made some change, added more color style for this.

And also you can contribute more color style, or new idea to me.

----
###Demo

![NumberProgressBar](http://ww3.sinaimg.cn/mw690/610dc034jw1efyrd8n7i7g20cz02mq5f.gif)

you can also set the progress text invisible (It's also very beautiful~ :-D ).

[Download Demo](https://github.com/daimajia/NumberProgressBar/releases/download/v1.0/NumberProgressBar-Demo-v1.0.apk)

###Usage
----

Use it in your own code:

```java
	<com.daimajia.numberprogressbar.NumberProgressBar
		android:id="@+id/number_progress_bar"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
	/>
```	

I made some predesign style. You can use them via `style` property.


![Preset color](http://ww1.sinaimg.cn/mw690/610dc034jw1efyslmn5itj20f30k074r.jpg)

Use the preset style just like below:

```java
	<com.daimajia.numberprogressbar.NumberProgressBar
		android:id="@+id/number_progress_bar"
		style="@style/NumberProgressBar_Default"
	/>
```	

In the above picture, the style is : 

`NumberProgressBar_Default`
`NumberProgressBar_Passing_Green`
`NumberProgressBar_Relax_Blue`
`NumberProgressBar_Grace_Yellow`
`NumberProgressBar_Warning_Red`
`NumberProgressBar_Funny_Orange`
`NumberProgressBar_Beauty_Red`
`NumberProgressBar_Twinkle_Night`

You can get more beautiful color from [kular](kuler.adobe.com), and you can also contribute your color style to NumberProgressBar!  

###Attributes

There are several attributes you can set:

![](http://ww2.sinaimg.cn/mw690/610dc034jw1efyttukr1zj20eg04bmx9.jpg)

The **reached area** and **unreached area**:

* color
* height 

The **text area**:

* color
* text size
* visibility
* distance between **reached area** and **unreached area**

The **bar**:

* max progress
* current progree

for example, the default style:

```java
	<com.daimajia.numberprogressbar.NumberProgressBar
	        android:layout_width="wrap_content"
	        android:layout_height="wrap_content"
	        
	        custom:progress_unreached_color="#CCCCCC"
	        custom:progress_reached_color="#3498DB"
	        
	        custom:progress_unreached_bar_height="0.75dp"
	        custom:progress_reached_bar_height="1.5dp"
	        
	        custom:progress_text_size="10sp"
	        custom:progress_text_color="#3498DB"
	        custom:progress_text_offset="1dp"
	        custom:progress_text_visibility="visible"
	        
	        custom:max="100"
	        custom:progress="80"
	         />
```

### About me:

A student in China mainland, I like Google, like Android, like open source, like doing something interesting. :)

If you have some new idea or internship opportunity, please [email me](mailto:daimajia@gmail.com) !

PS: Welcome to visit the site I am maintaining, which is a site to share graceful Android library for every Android developer.

It's name is [Moo Droid](http://moodroid.com) :-D , and also welcome submit your beautiful library to [Moo Droid](http://moodroid.com). 