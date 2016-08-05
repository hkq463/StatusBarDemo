# StatusBarDemo
三种方式设置状态栏颜色

#注意：
在xml布局中，有两个属性特别注意

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#ffff"
    android:orientation="vertical">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="140dp"
        android:background="@color/mask_tags_5"
        android:clipToPadding="true"
        android:fitsSystemWindows="true"
        android:text="你好，沉浸式状态栏"
        android:textSize="24dp" />

</LinearLayout>

```
另外三种方法在demo中有写到










