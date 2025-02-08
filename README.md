# PRODIGY_AD_01

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:background="#121212"
    android:padding="16dp">


    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="20dp"
        android:gravity="center"
        android:text="SIMPLE CALCULATOR"
        android:textColor="#FFFFFF"
        android:textSize="60sp"
        android:textStyle="bold" />

    <TextView
        android:id="@+id/resultTextView"
        android:layout_width="match_parent"
        android:layout_height="120dp"
        android:background="#1E1E1E"
        android:gravity="end|center_vertical"
        android:padding="16dp"
        android:text="0"
        android:textColor="#FFFFFF"
        android:textSize="70sp"
        android:layout_marginBottom="20dp"
        android:cornerRadius="15dp" />


    <GridLayout
        android:layout_width="match_parent"
        android:layout_height="323dp"
        android:columnCount="4"
        android:padding="15dp"
        android:rowCount="6">


        <Button
            android:id="@+id/button7"
            style="@style/CalcButton"
            android:text="7" />

        <Button
            android:id="@+id/button8"
            style="@style/CalcButton"
            android:text="8" />

        <Button
            android:id="@+id/button9"
            style="@style/CalcButton"
            android:text="9" />

        <Button
            android:id="@+id/buttonDivide"
            style="@style/OperatorButton"
            android:text="÷" />

        <!-- Row 2 -->
        <Button
            android:id="@+id/button4"
            style="@style/CalcButton"
            android:text="4" />

        <Button
            android:id="@+id/button5"
            style="@style/CalcButton"
            android:text="5" />

        <Button
            android:id="@+id/button6"
            style="@style/CalcButton"
            android:text="6" />

        <Button
            android:id="@+id/buttonMultiply"
            style="@style/OperatorButton"
            android:text="×" />

        <!-- Row 3 -->
        <Button
            android:id="@+id/button1"
            style="@style/CalcButton"
            android:text="1" />

        <Button
            android:id="@+id/button2"
            style="@style/CalcButton"
            android:text="2" />

        <Button
            android:id="@+id/button3"
            style="@style/CalcButton"
            android:text="3" />

        <Button
            android:id="@+id/buttonSubtract"
            style="@style/OperatorButton"
            android:text="−" />

        <!-- Row 4 -->
        <Button
            android:id="@+id/button0"
            style="@style/CalcButton"
            android:text="C" />

        <Button
            android:id="@+id/buttonClear"
            style="@style/FunctionButton"
            android:text="0" />

        <Button
            android:id="@+id/buttonEqual"
            style="@style/FunctionButton"
            android:text="=" />

        <Button
            android:id="@+id/buttonAdd"
            style="@style/OperatorButton"
            android:text="/" />

    </GridLayout>

</LinearLayout>
