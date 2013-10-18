RobustImageView
===============

RobustImageView is a collection of common ImageViews that we usually need to deal with.
It's easy to implement and has decent performance.

Usage
----------------
Define the view in xml, e.g. using RoundedImageView
```xml
<com.roytang.robustimageview.RoundedImageView
    android:id="@+id/roundedimage" 
    android:src="@drawable/profile_pic"
```

Implementation
```java
RoundedImageView profile_pic = (RoundedImageView)findViewById(R.id.profile_pic);
```
