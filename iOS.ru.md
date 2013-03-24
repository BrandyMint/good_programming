Гайдлайны и нотации для Objective-C/XCode/iOS
=============================================

Naming conventions
------------------

```
-getCacheDirectory; should probably be named as -cacheDirectory.
-convertToJson should probably be named as -jsonValue
```

Active subclassing
------------------

So, instead of

```
@interface MyAppFeaturedYouTubeVideosViewController : UIViewController
```

it would be

```
@interface MyAppFeaturedYouTubeVideosFeaturedViewController : MyAppViewController
@interface MyAppViewController : UIViewController
```

Ссылки
======

* [Google Objective-C Style Guide](http://google-styleguide.googlecode.com/svn/trunk/objcguide.xml) 
* [Trail Map](https://learn.thoughtbot.com/ios)
* [iOS programming architecture and design
  guidelines](http://blog.mugunthkumar.com/articles/ios-programming-architecture-and-design-guidelines/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+MugunthKumar+%28Mugunth+Kumar%27s+Blog%29)
* [Official Apple iOS App Programming
  Guide](http://developer.apple.com/library/ios/#documentation/iphone/conceptual/iphoneosprogrammingguide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40007072-CH1-SW1)
* [Official Coding Guidelines for Cocoa](https://developer.apple.com/library/mac/#documentation/Cocoa/Conceptual/CodingGuidelines/CodingGuidelines.html)
