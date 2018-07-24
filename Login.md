<?xml version="1.0" encoding="utf-8"?>
<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_marginBottom="130dp"
    android:layout_marginLeft="60dp"
    android:layout_marginRight="60dp"
    android:layout_marginTop="50dp"
    android:background="#1d9496"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView4"
        android:layout_width="wrap_content"
        android:layout_height="25dp"
        android:layout_marginStart="175dp"
        android:layout_marginTop="50dp"
        android:background="#ffffff"
        android:text="نام کاربری"
        android:textStyle="bold" />

    <TextView
        android:id="@+id/textView5"
        android:layout_width="50dp"
        android:layout_height="25dp"
        android:layout_marginStart="175dp"
        android:layout_marginTop="100dp"
        android:background="#ffffff"
        android:text="گذرواژه"
        android:textStyle="bold" />

    <EditText
        android:id="@+id/editText"
        android:layout_width="109dp"
        android:layout_height="25dp"
        android:layout_marginStart="30dp"
        android:layout_marginTop="100dp"
        android:background="#ffffff"
        android:ems="10"
        android:inputType="textPassword" />

    <EditText
        android:id="@+id/editText2"
        android:layout_width="110dp"
        android:layout_height="25dp"
        android:layout_marginStart="30dp"
        android:layout_marginTop="50dp"
        android:background="#ffffff"
        android:ems="10"
        android:inputType="textPersonName"
         />

    <CheckBox
        android:id="@+id/checkBox"
        android:layout_width="wrap_content"
        android:layout_height="21dp"
        android:layout_marginStart="30dp"
        android:layout_marginTop="150dp"
        android:background="#ffffff"
        android:text="یادآوری"
        android:textStyle="bold" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="32dp"
        android:layout_marginStart="90dp"
        android:layout_marginTop="250dp"
        android:background="#ffffff"
        android:text="ورود"
        android:textStyle="bold" />

