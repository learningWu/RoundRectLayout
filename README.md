# RoundRectLayout
任意圆角的layout

## 效果图

![效果图](https://github.com/learningWu/RoundRectLayout/blob/master/app/image/effect.png?raw=true)

## 使用方法

      <com.eddie.roundrectlayout.RoundRectLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            app:round="20dp">

            <ImageView
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:background="@mipmap/spid" />
        </com.eddie.roundrectlayout.RoundRectLayout>

只需要在需要圆角的view和ViewGroup外面套上RoundRectLayout即可
