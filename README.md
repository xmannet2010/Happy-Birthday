<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        android:src="@drawable/androidparty"
        android:scaleType="centerCrop"/>

    <TextView
        android:text="Happy Birthday Ahmed!"
        android:id="@+id/happy"
        android:textSize="36sp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:paddingLeft="20dp"/>
    <TextView
        android:text="From Adel"
        android:id="@+id/Adel"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="36sp"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:paddingRight="20dp"/>




</RelativeLayout>
