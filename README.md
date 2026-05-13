# 🔴 BUG HUNTER RECON v7 PRO

> منصة استطلاع احترافية للـ Bug Bounty — جميع الأدوات والأوامر في ملف HTML واحد لا يحتاج إنترنت ولا خادم.

---

## 📋 جدول المحتويات

- [نظرة عامة](#نظرة-عامة)
- [المميزات](#المميزات)
- [طريقة الاستخدام](#طريقة-الاستخدام)
- [مراحل الاستطلاع والأدوات](#مراحل-الاستطلاع-والأدوات)
- [Pipelines الجاهزة](#pipelines-الجاهزة)
- [متغيرات القالب](#متغيرات-القالب)
- [اختصارات لوحة المفاتيح](#اختصارات-لوحة-المفاتيح)
- [الميزات التفاعلية](#الميزات-التفاعلية)
- [تصدير الأوامر](#تصدير-الأوامر)
- [البنية التقنية](#البنية-التقنية)
- [متطلبات التشغيل](#متطلبات-التشغيل)

---

## نظرة عامة

**BUG HUNTER RECON v7 PRO** هو ملف HTML تفاعلي يعمل مباشرةً في المتصفح دون أي تثبيت أو اتصال إنترنت. يجمع أكثر من **750+ أمر جاهز** لـ **90+ أداة احترافية** مقسّمة على **3 مراحل رئيسية** من مراحل الاستطلاع في Bug Bounty.

```
الملف → افتحه في المتصفح → أدخل الهدف → انسخ الأوامر → شغّلها في Terminal
```

---

## المميزات

| الميزة | التفاصيل |
|---|---|
| 🎯 **Template Engine** | أوامر ديناميكية تتحدث فورياً عند تغيير الهدف |
| 🔍 **بحث فوري** | فلترة الأدوات بالاسم أو الفئة أو الوصف أو الأوامر |
| ⭐ **المفضلة** | حفظ الأدوات المهمة للوصول السريع |
| ✅ **تتبع التقدم** | تأشير الأوامر المنجزة مع شريط تقدم لكل أداة |
| 📋 **Pipeline** | سلاسل أوامر جاهزة تربط الأدوات تلقائياً |
| 💾 **حفظ الأهداف** | حفظ ما يصل 8 أهداف وتبديل بينها بنقرة |
| 📝 **ملاحظات** | كتابة ملاحظات لكل أداة تُحفظ تلقائياً |
| 📤 **تصدير** | تصدير الأوامر كملف `.txt` (كل / مرحلة / مفضلة / منجز) |
| 🖥️ **اكتشاف الأدوات** | توليد سكريبت Bash يفحص الأدوات المثبتة على نظامك |
| 🌙 **Dark Mode** | واجهة داكنة كاملة مناسبة لبيئة العمل |
| 📱 **Responsive** | يعمل على الشاشات الكبيرة والمتوسطة |

---

## طريقة الاستخدام

### 1. تشغيل الملف
```bash
# افتح الملف مباشرة في المتصفح
open Recone_fixed.html          # macOS
xdg-open Recone_fixed.html      # Linux
start Recone_fixed.html         # Windows
```
أو اسحب الملف مباشرةً إلى نافذة المتصفح.

### 2. إدخال الهدف
اكتب اسم النطاق في حقل **الهدف / Target** في الشريط الجانبي:
```
example.com          ← نطاق
192.168.1.1          ← عنوان IP
192.168.1.0/24       ← CIDR
https://example.com  ← URL كامل
*.example.com        ← Wildcard
```
الملف يتحقق تلقائياً من صحة الصيغة ويعطي تأشير بالأخضر أو الأحمر.

### 3. اختيار الأداة
اضغط على أي أداة من الشريط الجانبي لفتح لوحة الأوامر الخاصة بها.

### 4. نسخ الأوامر
- اضغط **نسخ** بجانب أي أمر لنسخه
- اضغط **الكل** في رأس اللوحة لنسخ جميع أوامر الأداة دفعة واحدة

---

## مراحل الاستطلاع والأدوات

### 1️⃣ Recon & Scanning — الاستطلاع الفعال

أدوات الفحص النشط للنطاقات والشبكات والثغرات.

| الأداة | الفئة | الوصف |
|---|---|---|
| **Amass ⭐** | Subdomain Enumeration | تعداد النطاقات من 30+ مصدر مع Brute Force |
| **Subfinder** | Subdomain Discovery | تعداد سريع Passive من مصادر متعددة |
| **Findomain** | Ultra-Fast Finder | تعداد عبر 16 مصدر API بالتوازي |
| **Assetfinder** | Multi-Source Finder | اكتشاف من crt.sh, Certspotter, HackerTarget |
| **Sublist3r** | Search Engine Subdomains | جمع من Google, Bing, Yahoo, Netcraft |
| **ShuffleDNS** | DNS Brute Force | Brute-Force فائق السرعة بالاعتماد على MassDNS |
| **MassDNS** | Ultra-Fast DNS Resolver | حل 350,000+ استعلام DNS في الثانية |
| **DNSx** | DNS Toolkit | حل A, AAAA, CNAME, MX, NS, TXT بالتوازي |
| **httpx ⭐** | Prober & Tech Detect | فحص الحياة وكشف التقنيات وبصمات الخوادم |
| **httprobe** | Host Prober | فحص سريع وبسيط لـ HTTP/HTTPS |
| **Nmap ⭐** | Port Scanning | المعيار الذهبي لفحص المنافذ والخدمات |
| **Masscan** | Fast Port Scanner | يفحص الإنترنت كله في 6 دقائق |
| **FFUF ⭐** | Fuzzing Engine | محرك Fuzzing الأسرع لـ Directory, Param, VHost |
| **Dirsearch** | Directory Scanner | فحص المجلدات والملفات الخفية |
| **GoBuster** | DNS/Dir Buster | سريع وموثوق لـ DNS وDirectory وS3 |
| **Nuclei ⭐** | Vulnerability Scanner | آلاف الثغرات بقوالب YAML محدّثة يومياً |
| **Katana** | Web Crawler | زاحف يدعم JavaScript Rendering |
| **GAU** | URL Collector | جمع URLs تاريخية من Wayback, Common Crawl |
| **Waybackurls** | Historical URLs | استخراج URLs من Internet Archive |
| **GoSpider** | Concurrent Crawler | زاحف Go سريع مع حماية من الحظر |
| **Hakrawler** | Go Web Crawler | استخراج Links من HTML وJS في آنٍ واحد |
| **SQLMap ⭐** | SQL Injection | أتمتة حقن SQL الكاملة لجميع قواعد البيانات |
| **FFUF (XSS/SSRF)** | Advanced Fuzzing | فازينج متخصص للـ XSS, SSRF, Open Redirect |
| **Arjun** | Parameter Discovery | اكتشاف المعلمات المخفية في GET, POST, JSON |
| **ParamSpider** | URL Parameter Hunter | اكتشاف Parameters من Wayback Machine |
| **LinkFinder** | JS Endpoint Extractor | استخراج Endpoints وروابط API من JS |
| **SecretFinder** | JS Secret Scanner | البحث عن API Keys وTokens في JavaScript |
| **Subdomainizer** | JS Subdomain Extractor | استخراج النطاقات والـ Cloud Services من JS |
| **Gxss + Kxss** | XSS Detection | اكتشاف XSS بالحقن وكسر الـ Context |
| **Semgrep (gf)** | Pattern Matcher | grep للبحث عن أنماط الثغرات في URLs |
| **Nikto** | Web Server Scanner | فحص outdated software والملفات الخطيرة |
| **Wafw00f** | WAF Detector | كشف نوع جدار الحماية من 150+ نوع |
| **Gowitness** | Chrome Screenshots | لقطات شاشة بـ Chrome Headless بالجملة |
| **Aquatone** | Visual Recon | تصوير المواقع وتوليد تقرير HTML مرئي |
| **TruffleHog** | Git Secret Scanner | البحث العميق في تاريخ Git عن Secrets |
| **gitleaks** | Git Leak Scanner | فحص Repositories بـ Regex محدّثة |
| **CeWL** | Custom Wordlist | توليد قوائم كلمات من محتوى الموقع |
| **Subzy** | Subdomain Takeover | فحص استيلاء النطاقات الفرعية |

---

### 🕵️ OSINT Intelligence — الاستخبارات المفتوحة

أدوات جمع المعلومات من المصادر المفتوحة.

| الأداة | الفئة |
|---|---|
| **theHarvester ⭐** | Email & Domain OSINT |
| **Shodan ⭐** | IoT & Network Search |
| **Censys** | Certificate & IP Intel |
| **crt.sh / CT Logs ⭐** | Certificate Transparency |
| **WHOIS & ASN** | Domain Registration |
| **Recon-ng** | OSINT Framework |
| **SpiderFoot** | Automated OSINT |
| **Sherlock** | Username OSINT |
| **Maigret** | People OSINT |
| **Holehe** | Email Registration Check |
| **GHunt** | Google Account OSINT |
| **Hunter.io / Email** | Email Discovery |
| **FOCA / Metagoofil** | Metadata Extraction |
| **LinkedIn OSINT** | Professional Network Intel |
| **SecurityTrails** | Passive DNS |
| **VirusTotal + Threat Intel** | Threat Intelligence |
| **Fofa / ZoomEye / Netlas** | Network Search Engines |
| **PassiveTotal / RiskIQ** | Passive DNS & Threat Intel |
| **Leaked Data Hunt** | Data Breach Search |
| **Twint / Social OSINT** | Social Media OSINT |

---

### 🔎 Search Dorks — استعلامات البحث

قوالب بحث جاهزة لاكتشاف الأصول المكشوفة.

| الأداة | الفئة |
|---|---|
| **Google Dorks ⭐** | Search Engine |
| **GitHub Dorks ⭐** | Source Code |
| **GitLab Dorks** | Source Code |
| **Bitbucket Dorks** | Source Code |
| **Shodan Dorks ⭐** | Network Search |
| **Censys Dorks** | Network Search |
| **FOFA Dorks** | Network Search |
| **ZoomEye Dorks** | Network Search |
| **Grep.app** | Source Code Search |
| **PublicWWW** | Web Source Search |
| **Wayback Machine** | Historical Data |
| **Common Crawl** | Web Archive |
| **LeakIX** | Leak Search |
| **URLScan.io** | URL Analysis |
| **VirusTotal** | Threat Intel |
| **FullHunt** | Attack Surface |
| **IntelX** | Intelligence Search |
| **crt.sh** | Certificate Search |
| **BuiltWith** | Tech Detection |
| **Netlas** | Network Search |
| **BinaryEdge** | Attack Surface |
| **GrayHatWarfare** | S3 Buckets |
| **Searchcode** | Source Code |
| **Sourcegraph** | Code Search |
| **npm Registry** | Package Intelligence |
| **Docker Hub** | Container Intelligence |
| **Postman Workspaces** | API Documentation |
| **Swagger / OpenAPI** | API Documentation |
| **Firebase Endpoints** | Cloud Misconfiguration |
| **Pastebin & Pastes** | Paste Sites |
| **Reddit OSINT** | Social Intelligence |
| **Discord OSINT** | Messaging Platform |
| **Telegram OSINT** | Messaging Platform |

---

## Pipelines الجاهزة

سلاسل أوامر تربط الأدوات تلقائياً لتنفيذ سيناريوهات كاملة بأمر واحد:

| Pipeline | الهدف |
|---|---|
| **Subfinder → HTTPX → Nuclei** | اكتشاف النطاقات → فحص الحياة → فحص الثغرات |
| **Katana → GF → Nuclei + Dalfox** | زحف الروابط → فلترة الأنماط → استغلال XSS |
| **GAU → URO → Param Fuzz** | URLs تاريخية → تنظيف → فازينج XSS + SQLi |
| **Full Recon Pipeline** | خط استطلاع كامل من البداية للنهاية |
| **Secrets & JS Deep Analysis** | تحليل JS وكشف الأسرار والمفاتيح |
| **CORS + Open Redirect + SSRF** | فحص ثغرات CORS وإعادة التوجيه وSSRF |
| **Directory & API Fuzzing** | اكتشاف مسارات وـ API Endpoints خفية |
| **Cloud & S3 Asset Discovery** | اكتشاف S3 Buckets وCloud Misconfigs |

> افتح أي أداة ثم اضغط **Pipelines** في رأس لوحة الأوامر لرؤية السلاسل المتاحة.

---

## متغيرات القالب

يدعم الملف متغيرات تُستبدل تلقائياً في جميع الأوامر:

| المتغير | الوصف | القيمة الافتراضية |
|---|---|---|
| `{{T}}` / `{{TARGET}}` | نطاق الهدف | قيمة حقل الهدف |
| `{{THREADS}}` | عدد الخيوط المتزامنة | `50` |
| `{{RATE}}` | معدل الطلبات في الثانية | `150` |
| `{{OUTPUT}}` | مجلد حفظ المخرجات | `output` |
| `{{PROTO}}` | البروتوكول المستخدم | `https` |
| `{{WORDLIST}}` | مسار قائمة الكلمات | `/usr/share/seclists/...` |
| `{{DATE}}` | تاريخ اليوم | تلقائي `YYYY-MM-DD` |
| `{{YEAR}}` | السنة الحالية | تلقائي |

لتغيير القيم: اضغط **متغيرات القالب** في الشريط الجانبي.

---

## اختصارات لوحة المفاتيح

| الاختصار | الوظيفة |
|---|---|
| `Ctrl + K` | التركيز على صندوق البحث |
| `Ctrl + E` | فتح نافذة التصدير |
| `J` | الانتقال للأداة التالية |
| `K` | الانتقال للأداة السابقة |
| `F` | إضافة/إزالة الأداة من المفضلة |
| `N` | فتح/إغلاق لوحة الملاحظات |
| `C` | نسخ جميع أوامر الأداة الحالية |
| `Esc` | إغلاق اللوحة/النافذة المفتوحة |

---

## الميزات التفاعلية

### 🎯 التحقق من الهدف
يتحقق الملف تلقائياً من صيغة الهدف:
- ✅ أخضر: صيغة صحيحة (Domain, IP, CIDR, URL, Wildcard)
- ❌ أحمر: صيغة غير صحيحة

### 📊 تتبع التقدم
- **شريط التقدم الكلي**: نسبة الأوامر المنجزة من إجمالي 750+ أمر
- **تقدم كل أداة**: شريط منفصل داخل كل لوحة أوامر
- **تقدم كل مرحلة**: شريط صغير بجانب اسم كل مرحلة في القائمة

### ⭐ المفضلة والتبويبات
القائمة الجانبية تحتوي على 4 تبويبات:
- **الكل**: جميع الأدوات (90+)
- **مفضلة**: الأدوات المحفوظة بنجمة
- **أخيرة**: آخر 10 أدوات تمت زيارتها
- **منجز**: الأدوات المكتملة 100%

### 🔍 البحث الذكي
البحث يغطي: اسم الأداة + الفئة + الوصف + أسماء الأوامر الفردية.  
النتائج المطابقة تُظلَّل باللون البرتقالي داخل النص.

### 🖥️ اكتشاف الأدوات
زر **اكتشاف الأدوات** يولّد سكريبت Bash جاهز يفحص:
- معلومات نظام التشغيل والـ Shell
- بيئات تشغيل Go, Python, Ruby, Node
- 20+ أداة Bug Bounty مع رقم الإصدار
- مسار Nuclei Templates وSecLists

```bash
# الصق السكريبت في Terminal وشغّله
bash detection_script.sh
```

---

## تصدير الأوامر

اضغط **تصدير** في أسفل الشريط الجانبي لاختيار نوع التصدير:

| النوع | المحتوى |
|---|---|
| **جميع الأوامر** | كل أوامر الـ 90+ أداة |
| **المرحلة الحالية** | أوامر المرحلة المفتوحة فقط |
| **المفضلة فقط** | أوامر الأدوات المميّزة بنجمة |
| **المنجزة فقط** | الأوامر التي تم تأشيرها كمنجزة |

الملف المُصدَّر بصيغة `.txt` منظّم بـ Headers وفواصل واضحة.

---

## البنية التقنية

```
Recone_fixed.html
├── CSS           — تصميم كامل بـ CSS Variables (Dark Theme)
├── HTML          — واجهة Sidebar + Command Panel + Main Area
└── JavaScript
    ├── DB[]             — قاعدة بيانات الأدوات والأوامر
    ├── Template Engine  — استبدال {{T}}, {{THREADS}}, ...
    ├── LS (Storage)     — إدارة localStorage للحفظ التلقائي
    ├── renderCmds()     — عرض أوامر الأداة المختارة
    ├── renderPipelines() — عرض سلاسل الأوامر
    ├── buildSidebar()   — بناء قائمة الأدوات مع البحث والفلترة
    ├── exportAll/Phase/Favs/Done() — تصدير الأوامر
    └── generateDetectionScript()  — توليد سكريبت الاكتشاف
```

### البيانات المحفوظة محلياً (localStorage)
| المفتاح | المحتوى |
|---|---|
| `bhr_favs` | قائمة الأدوات المفضلة |
| `bhr_checks` | الأوامر المؤشّرة كمنجزة |
| `bhr_notes` | الملاحظات لكل أداة |
| `bhr_profiles` | الأهداف المحفوظة |
| `bhr_recent` | آخر 10 أدوات تمت زيارتها |
| `bhr_done_tools` | الأدوات المكتملة 100% |

---

## متطلبات التشغيل

| المتطلب | التفاصيل |
|---|---|
| **المتصفح** | Chrome 90+ / Firefox 88+ / Edge 90+ / Safari 14+ |
| **الإنترنت** | غير مطلوب (الخطوط تُحمَّل من Google Fonts عند أول فتح) |
| **الخادم** | لا يلزم — يعمل كـ `file://` مباشرة |
| **التثبيت** | لا يلزم — ملف واحد فقط |

> **ملاحظة:** بعض خصائص `clipboard.writeText()` قد تتطلب `https://` أو `localhost`. إذا فشل النسخ التلقائي، الملف يستخدم `document.execCommand('copy')` كبديل تلقائي.



<div align="center">

**BUG HUNTER RECON v7 PRO — DARK EDITION**  
`750+ Command` • `90+ Tool` • `3 Phases` • `8 Pipelines`

</div>
