# Convert a native android custom control to Xamarin Android
We are going to convert android MaterialCalendarView to xamarin.<br/>
To get more ida about java library binding please follow this link https://developer.xamarin.com/guides/android/advanced_topics/binding-a-java-library/
<br/>
* Step 1: Download lasted version of MaterialCalendarView from GitHub https://github.com/prolificinteractive/material-calendarview
* Step 2: Open it in android Studio.
* Step 3: Build it in android Studio.
* Step 4: Find **.aar** file in android Studio (To Know More about .aar Binding https://developer.xamarin.com/guides/android/advanced_topics/binding-a-java-library/binding-an-aar/)
* Step 5: Open Visual Studio and create a xamarin android project.
* Step 6: Add **Binding Library (Android)** project to your solution.
* Step 7: Copy **.aar** file to the root of your project.
* Step 8: Set build action of that **.aar** file is **LibraryProjectZip**
* Step 9: Set necessary Transforms. More about Transforms please follow this link. https://developer.xamarin.com/guides/android/advanced_topics/binding-a-java-library/customizing-bindings/java-bindings-metadata/
* Step 10: Reference it to your android project and Enjoy. 
