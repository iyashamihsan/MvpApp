# MvpApp

(Forked version) from Rukey7 MvpApp https://github.com/Rukey7/MvpApp

##### The application of MVP architecture development is a summary of the knowledge that I have learned. I have done it for a while, the interface is more, the amount of code is still there, and there is a lot of packaging inside, the whole code is very well organized. clean. There are some libraries and classes that I have encapsulated in it, which can be used as a reference for reference. Any questions can be raised and discussed. There are good ideas and suggestions for modification. Welcome to submit the code.
##### Now Netease's image interface can't be used, so the "beauty" interface can't get the data. If you want to see the effect, you can try to change the interface under the "benefits" tab to the "beauty" interface. In the past, I just used my own hands. I don’t want to change the code.
## Screenshot

##### Project structure：

![](https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/project.png)

##### 应用截图：

<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E4%B8%BB%E9%A1%B5.png" height = "400" alt="主页" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E6%96%B0%E9%97%BB%E4%B8%BB%E9%A1%B5.png" height = "400" alt="新闻主页" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E6%96%B0%E9%97%BB%E8%AF%A6%E6%83%85.png" height = "400" alt="新闻详情" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E4%B8%93%E9%A2%98.png" height = "400" alt="专题" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E6%A0%8F%E7%9B%AE%E7%AE%A1%E7%90%86.png" height = "400" alt="栏目管理" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E5%9B%BE%E7%89%87%E6%96%B0%E9%97%BB.png" height = "400" alt="图片新闻" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E5%9B%BE%E7%89%87%E5%88%97%E8%A1%A8.png" height = "400" alt="图片列表" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E5%A4%A7%E5%9B%BE.png" height = "400" alt="大图" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E4%B8%8B%E8%BD%BD%E7%AE%A1%E7%90%86.png" height = "400" alt="下载管理" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E8%A7%86%E9%A2%91%E6%92%AD%E6%94%BE.png" height = "400" alt="视频播放" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E5%9B%BE%E7%89%87%E5%8A%A8%E5%9B%BE.gif" height = "400" alt="图片动图" align=center />
<img src="https://raw.githubusercontent.com/Rukey7/ScreenShot/master/MvpApp/%E4%B8%8B%E8%BD%BD%E5%8A%A8%E5%9B%BE.gif" height = "400" alt="下载管理" align=center />

## Third-party library used

- [leakcanary](https://github.com/square/leakcanary)
: Detecting application memory leaks, this one knows
- [butterknife](https://github.com/JakeWharton/butterknife)
: Helping Android controls and callbacks with dependency injection, JakeWharton's masterpiece
- [dagger2](https://github.com/google/dagger)
: Android and Java dependency injection libraries
- [rxjava](https://github.com/ReactiveX/RxJava)
: A library that implements asynchronous operations, it's very hot now
- [RxAndroid] (https://github.com/ReactiveX/RxAndroid)
: Rxjava binding library for Android
- [RxBinding](https://github.com/JakeWharton/RxBinding)
: With Rxjava processing control asynchronous call
- [RxLifecycle] (https://github.com/trello/RxLifecycle)
: Preventing a memory leak from a subscription in RxJava
- [RxPermissions](https://github.com/tbruyelle/RxPermissions)
: Based on RxJava development to help handle runtime permission detection in Android 6.0
- [retrofit](https://github.com/square/retrofit)
: The best network communication library currently used should be used.
- [okhttp](https://github.com/square/okhttp)
: okhttp and retrofit do network communication is a perfect match
- [greenDAO](https://github.com/greenrobot/greenDAO)
: ORM database, can be used with rxjava
- [logger] (https://github.com/orhanobut/logger)
:Log library, making the printed Log very beautiful
- [glide](https://github.com/bumptech/glide)
: Google's image loading library, there is a very good guidance document: https://mrfu.me/2016/02/27/Glide_Getting_Started/
- [BaseRecyclerViewAdapterHelper] (https://github.com/CymChad/BaseRecyclerViewAdapterHelper)
: Very good RecyclerView multi-function adapter library, I did not directly use this library in the project, but made some changes to its earlier code according to my own habits.
- [recyclerview-animators](https://github.com/wasabeef/recyclerview-animators)
: RecyclerView's animation library with a lot of animation effects built in
- [CircleImageView](https://github.com/hdodenhof/CircleImageView)
: Very common library for displaying round avatars
- [PhotoView](https://github.com/chrisbanes/PhotoView)
: Image library that can be scaled according to gestures, this is also very common
- [AndroidImageSlider](https://github.com/daimajia/AndroidImageSlider)
: Show the library of the head Banner, the animation effect is a lot, that is, you need to rely on the two libraries picasso and nineoldandroids
- [NumberProgressBar](https://github.com/daimajia/NumberProgressBar)
: Sexy digital progress bar
- [FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout)
: Tab library with more style than TabLayout
- [FlycoDialog](https://github.com/H07000223/FlycoDialog_Master)
: Versatile Dialog
- [FlycoLabelView] (https://github.com/H07000223/FlycoLabelView)
: Adding a library of corners
- [gson](https://github.com/google/gson)
: Help Json and Object conversion, this is also commonly used
- [ijkplayer](https://github.com/Bilibili/ijkplayer)
: Video decoding library produced by station B
- [DanmakuFlameMaster] (https://github.com/Bilibili/DanmakuFlameMaster)
:The same barrage library produced by station B
- [ShineButton] (https://github.com/ChadCSong/ShineButton)
: The cool effect click button is mainly used to display animations such as favorites.
- [RichText](https://github.com/zzhoujay/RichText)
: Rich text processing library, it is very convenient to use it is a memory leak -
- [Android-SpinKit] (https://github.com/ybq/Android-SpinKit)
: Drawable integrated with a variety of animation effects, before looking at the source code, I feel that the code is well packaged, and the animation can only be used on the View.
- [filepicker](https://github.com/Angads25/android-filepicker)
: This is used to process the file selection library of PreferenceScreen. PreferenceScreen feels that it is not usually seen in the usual use.
- [tinker](https://github.com/Tencent/tinker)
: WeChat Android hot patch program, powerful, and other hot patching scheme comparison here [wiki] (https://github.com/Tencent/tinker/wiki)
- [DragSlopLayout](https://github.com/Rukey7/DragSlopLayout)
: A library that assists in the development of drag-and-drop functionality. This is the library I have packaged for some of the features of this app - and it is now also useful on working projects.
- [IjkPlayerView] (https://github.com/Rukey7/IjkPlayerView)
: Based on the player developed by ijkplayer, it is also a library for the video playback function of this app. - It has a barrage function inside, so you can watch it with interest.
- [TagLayout](https://github.com/Rukey7/TagLayout)
: Tag library, which can be used as a custom button
	
Thanks
---

- Thanks to all the excellent open source projects.
- [OuNews](https://github.com/oubowu/OuNews)
: I started watching this project and started to learn a lot.

Statement
---
This project is for exchange learning only. If there is copyright infringement, you can notify me to delete it in time.
