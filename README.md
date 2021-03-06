# HorizontalWithIndicator
一个简单的带有Indicator的Android滑动控件
#### 效果图

![](https://github.com/NelsonJs/MyHorizontalWithIndicator/blob/master/temp.gif)
![](https://github.com/NelsonJs/MyHorizontalWithIndicator/blob/master/temp_1.gif)
![](https://github.com/NelsonJs/MyHorizontalWithIndicator/blob/master/temp_2.gif)
![](https://github.com/NelsonJs/MyHorizontalWithIndicator/blob/master/temp_3.gif)

#### gradle导入

 implementation 'com.aioyoo:HorizontalWithIndicator:1.0.3-alph1'




#### XML使用  
```
<nelson.com.myhorizontal.PHorizontalView
        app:fontSize="14"
        app:textColor="@color/gray"
        app:indicatorColor="@color/e5"
        app:canLines="true"
        app:indicatorDrawable="@drawable/indicator_normal"
        app:backGroundColor="@color/colorAccent"
        app:contentPaddingTop="10dp"
        app:contentPaddingBottom="20dp"
        app:indicatorMarginTop="2dp"
        app:separateContentAndIndicator="true"
        app:indicatorParentColor="@color/colorPrimaryDark"
        app:contentPaddingLeft="40dp"
        app:contentPaddingRight="40dp"
        app:selectTxtBgColor="@color/green"
        app:normalTxtBgColor="@color/yaMa"
        app:goneIndicator="false"
        android:id="@+id/scro"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
```  
#### 部分属性含义  
```
canLines="true" 每一个item标题是否能够换行显示（ture），否则超过则以末尾加省略号..表示
indicatorDrawable 指示器的形状，暂时不支持纯图片的指示器
backGroundColor 全局背景颜色
contentPaddingTop 标题上边距
indicatorMarginTop 指示器上边距
separateContentAndIndicator 是否可以设置指示器所在行的颜色
indicatorParentColor 设置指示器所在行的颜色
contentPaddingLeft 标题左边距
selectTxtBgColor 选中时的标题背景颜色
normalTxtBgColor 未选中时的标题背景颜色
selectFontSize 选中时标题大小
selectTxtColor 选中时标题颜色
goneIndicator 是否隐藏标题栏
indicatorWidth （sameOfTxt 指示器的宽度跟标题宽度一样，halfOfTxt 指示器的宽度是标题宽度的一半）
setIndicatorWidth 设置指示器的宽度
indicatorHeight 设置指示器的高度
```
