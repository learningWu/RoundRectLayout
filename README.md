# RoundRectLayout
任意圆角的layout

## 效果图

![效果图](https://img-blog.csdnimg.cn/20190531155835360.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FsZWFybmluZ1d1,size_16,color_FFFFFF,t_70)

## 使用方法
**属性：**

    <declare-styleable name="RoundRectLayout">
        <attr name="round" format="dimension"/>
        <attr name="leftTopRound" format="dimension" />
        <attr name="rightTopRound" format="dimension" />
        <attr name="leftBottomRound" format="dimension" />
        <attr name="rightBottomRound" format="dimension" />
    </declare-styleable>

ImageView

      <com.eddie.roundrectlayout.view.RoundRectLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            app:round="20dp"
            app:layout_constraintLeft_toLeftOf="parent"
            app:layout_constraintTop_toTopOf="parent">

            <ImageView
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:background="@mipmap/spid" />
        </com.eddie.roundrectlayout.view.RoundRectLayout>
