# StatusBarDemo
三种方式设置状态栏颜色

#注意：
在xml布局中，有两个属性特别注意
 android:clipToPadding="true"
 android:fitsSystemWindows="true"
当status bar为透明或半透明时(4.4以上),系统会设置view的paddingTop值为一个适合的值(status bar的高度)让view的内容不被上拉到状态栏，当在不占据status bar的情况下(4.4以下)会设置paddingTop值为0(因为没有占据status bar所以不用留出空间)。
