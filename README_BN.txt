এই template-টা একটি clean fullscreen Android WebView app template.

এখানে কী কী বদলাতে হবে:

1) Website URL বদলাও:
ফাইল: app/src/main/java/com/example/webviewapp/MainActivity.kt
লাইন: START_URL = "https://example.com/"

2) App name বদলাও:
ফাইল: app/src/main/res/values/strings.xml
লাইন: <string name="app_name">My WebView App</string>

3) App icon বদলাও:
Android Studio-তে Image Asset দিয়ে launcher icon replace করতে হবে
অথবা mipmap folder-এ icon files বসাতে হবে

4) Top bar থাকবে না:
এই template-এ NoActionBar theme + fullscreen mode ব্যবহার করা হয়েছে
তাই app-এর নিজের extra top bar থাকবে না

5) Website-এর নিজের header/top bar থাকলে:
ওটা app-এর মধ্যে দেখা যাবে, কারণ সেটা website-এর অংশ

Build করতে যা লাগবে:
- Android Studio
- অথবা কোনো build service / GitHub Actions / অন্য কারও PC

Note:
এই template-টা source project, ready APK না
