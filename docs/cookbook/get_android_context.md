<!---
This is the API of version 1.1.1
-->
    
You can use LocalContext.current to receive the context of your Android App inside a Compose Function

```kotlin 
@Composable
fun AndroidContextComposeDemo() {
    val context = LocalContext.current
    Text(text = "Read this string from Context: "+context.getString(R.string.app_name))
}
```

## See also:
* [Full Example Code]({{ site.samplefolder }}/other/AndroidContextComposeDemo.kt)
