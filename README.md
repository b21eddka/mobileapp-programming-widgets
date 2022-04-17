
Jag lade till en LinearLayout och gjorde den vertilkal. Därefter gjordes det tre widgets, en Textview, ImageView och Button och gav dem attributer.
Sist så ändrade jag positioneringen på widgets då att margin på ImageView var större och Button var horisontellt centrerad med hjälp av gravity.

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:contentDescription="@string/Mountains"
        android:layout_marginTop="50dp"
        android:src="@drawable/mountains" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="@string/Quote"
            android:textSize="14sp" />

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center_horizontal"
            android:onClick=""
            android:text="@string/Button" />

</LinearLayout>
```



![](Screenshot_20220417_222719.png)

