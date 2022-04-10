
# Rapport

I den här uppgiften skapades en mobilapp/webbapp med en extern och intern webview.  I content_main skrev jag:

```xml
<WebView 
    android:id="@+id/my_webview"
    android:layout_width="match_parent"
    android:layout_height="match_parent" 
/>
```
och i on_create under MainActivity.java:

```
WebViewPontus = findViewById(R.id.my_webview);
WebViewPontus.setWebViewClient(new WebViewClient());
WebSettings webSettings = WebViewPontus.getSettings();
webSettings.setJavaScriptEnabled(true);
```
internal webview
![](internal.jpg)
external webview
![](external.jpg)