G6 Business Manager - Android APK project

मोबाइल से APK बनाने के चरण:
1. ZIP डाउनलोड करके फोन में Extract करें।
2. github.com पर लॉगिन करें और नया repository बनाएं: G6-Business-Manager
3. Extract किए गए प्रोजेक्ट की सभी फाइलें, खासकर छिपा हुआ .github/workflows/build-apk.yml,
   repository में upload करें। GitHub मोबाइल वेबसाइट में Add file > Upload files इस्तेमाल करें।
4. Repository के Actions टैब में "Build G6 Android APK" खोलें।
5. Run workflow दबाएं (या push के बाद अपने-आप build शुरू होगा)।
6. Build सफल होने पर run खोलें और Artifacts में G6-Business-Manager-APK.zip डाउनलोड करें।
7. ZIP extract करके app-debug.apk पर टैप करें और Android के निर्देशों से इंस्टॉल करें।

यह debug APK है, Play Store रिलीज़ नहीं। शुरुआती सॉफ्टवेयर की एंट्री इस फोन के ऐप स्टोरेज में
रहती हैं। लॉगिन, क्लाउड बैकअप, multi-user और पूरी GST invoice calculation अभी शामिल नहीं हैं।
