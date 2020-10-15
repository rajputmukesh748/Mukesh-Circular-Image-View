# Mukesh-Circular-Image-View
<h3> Mukesh Rajput </h3>
</br>

<h3>To get a Git project into your build:<h3>

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.rajputmukesh748:Mukesh-Circular-Image-View:1.0.0'
	}


<h2><center>Simple circular image view</center></h2>

<h5>Add code in your xml for create a simple circular image view.</h5>

    <com.mukesh.mukeshcircleimageview.MukeshCircleImageView
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        android:layout_margin="20dp"
        android:src="@drawable/profile_image"
        />

<h6>Output Simple Circular Image</h6>

![MukeshCircleImageView](https://github.com/rajputmukesh748/Mukesh-Circular-Image-View/blob/main/Circular%20Image%20View.png)

</br>
<h2><center>Border circular image view</center></h2>

<h5>Add code in your xml for create a border circular image view.</h5>

    <com.mukesh.mukeshcircleimageview.MukeshCircleImageView
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        android:layout_margin="20dp"
        app:miv_border_color="@color/colorAccent"
        app:miv_border_overlay="true"
        app:miv_border_width="5dp"
        app:miv_circle_background_color="@color/colorPrimary"
        android:src="@drawable/profile_image"
        />
        
        
<h6>Output Border Circular Image</h6>

![MukeshCircleImageView](https://github.com/rajputmukesh748/Mukesh-Circular-Image-View/blob/main/Border%20Circular%20Image%20View.png)


<p>For fetch online images you can user Glide or Picasso libraries.</p>

<b><h3>Thanks for your support. Please try and support it.</h3></b>
