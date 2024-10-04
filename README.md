Guide to Using OutlineTextView
Quick Setup
1. Include Library
Using Gradle
To include OutlineTextView in your project via Gradle, follow these steps:

Add Jitpack to your repositories. Ensure this is added to your build.gradle file:
 
	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}
 
2. Add the dependency in your build.gradle file :




       dependencies {
       	        implementation 'com.github.Narenbairagi11:Components:cc4444d4e4'
       	}


 Example Usage
Here's an example of how to use OutlineTextView in your XML layout file:


    <in.narenbairagi.components.outlinetextview.OutlineTextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/app_name"
        android:layout_marginTop="200dp"
        android:textSize="50dp"
        app:outlineColor="#000"
        android:textColor="#00000000"
        app:outlineWidth="1"
        android:layout_gravity="center"/>


Attributes
android:text: The text to display within the OutlineTextView.
android:textColor: The color of the text itself.
android:textSize: The size of the text.
app:outlineColor: The color of the text outline.
app:outlineWidth: The width of the text outline. This determines how thick the outline is.
app:outlineOffset: The offset of the text outline from the actual text. This helps to adjust the position of the outline relative to the text.
Usage Scenarios
Headings and Titles: Use OutlineTextView to make headings and titles stand out with a distinctive outline.
Buttons and Labels: Create eye-catching buttons or labels with outlined text to enhance user interface elements.
Decorative Text: Add stylistic elements to text in your app to make it more visually appealing.
License
OutlineTextView is distributed under the MIT license. See LICENSE for details.   
