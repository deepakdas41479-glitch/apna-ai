APNA AI — VERSION 0.1

Bhai, ye Apna AI ka pehla working UI prototype hai.

ABHI KYA KARTA HAI
- Phone-friendly chat interface
- Google, Bing, Google Images ke search links
- Public Instagram/Facebook/LinkedIn pages ke liye search shortcuts
- Basic offline cache (jab HTTPS website par host ho)

ABHI KYA NAHI KARTA
- Ye abhi khud AI model nahi hai; built-in LLM/API nahi juda hai.
- Ye search results ko khud read ya verify nahi karta; browser mein links kholta hai.
- Ye private accounts, login walls, ya inaccessible photos ko bypass nahi karta.

ANDROID PAR INSTALL
1. ZIP ko extract karo.
2. Is folder ko HTTPS hosting par upload karna hoga (jaise GitHub Pages ya kisi static hosting service).
3. Apne Android phone par us HTTPS website ko Chrome mein kholo.
4. Chrome menu (⋮) > "Install app" ya "Add to Home screen" select karo.
5. App icon home screen par aa jayega.

IMPORTANT
Is ZIP mein APK file nahi hai. Is build environment mein Android SDK/Gradle available nahi tha, isliye main fake APK link nahi de raha. Ye installable PWA source bundle hai; HTTPS par host karne ke baad browser se install hoga.

NEXT VERSION
Agle version mein proper AI backend, safe web search, multi-step search planning aur result summaries add kar sakte hain. Iske liye server-side API key ya hosted model chahiye—API key ko public HTML file mein mat daalna.
