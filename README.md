# UTS-Pemograman-Mobile
form login dan activity login
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_marginRight="30dp"
    android:layout_marginLeft="30dp"
    android:orientation="vertical"
    android:gravity="center"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="USER LOGIN"
        android:layout_margin="30dp"
        android:textStyle="bold"
        android:textSize="20sp" />
    <EditText
        android:id="@+id/txUsername"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="10dp"
        android:hint="Username"
        android:inputType="textPersonName" />
    <EditText
        android:id="@+id/txPassword"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="10dp"
        android:hint="Password"
        android:inputType="textPassword" />
    <Button
        android:id="@+id/btnLogin"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Login"
        android:layout_marginBottom="10dp"
        style="@style/Widget.AppCompat.Button.Colored"/>
    <TextView
        android:id="@+id/tvCreateAccount"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Create Account"
        android:layout_marginBottom="30dp"/>


</LinearLayout>
