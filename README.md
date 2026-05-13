<div dir="rtl">

# 🔴 BUG HUNTER RECON 

<p align="center">
  <img src="https://img.shields.io/badge/Commands-750%2B-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tools-90%2B-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/HTML-One-green?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/No_Installation-✓-blue?style=for-the-badge"/>
</p>

<p align="center">
منصة استطلاع احترافية للـ Bug Bounty — جميع الأدوات والأوامر في ملف HTML واحد لا يحتاج إنترنت ولا خادم
</p>

---

## 📋 جدول المحتويات

- [نظرة عامة](#-نظرة-عامة)
- [المميزات](#-المميزات)
- [طريقة الاستخدام](#-طريقة-الاستخدام)
- [مراحل الاستطلاع والأدوات](#️-مراحل-الاستطلاع-والأدوات)
- [Pipelines الجاهزة](#️-pipelines-الجاهزة)
- [متغيرات القالب](#️-متغيرات-القالب)
- [اختصارات لوحة المفاتيح](#️-اختصارات-لوحة-المفاتيح)
- [تصدير الأوامر](#-تصدير-الأوامر)
- [متطلبات التشغيل](#-متطلبات-التشغيل)

---

## 🔎 نظرة عامه BUG HUNTER RECON





يحتوي على أكثر من **750 أمرًا جاهزًا** لأكثر من **90 أداة احترافية**، مُقسّمة إلى **3 مراحل رئيسية** من مراحل الاستطلاع (Recon) في مجال الـ Bug Bounty.
```
افتح الملف في المتصفح  ←  أدخل الهدف  ←  انسخ الأمر  ←  شغّله في Terminal
```

---

## ✨ المميزات

| # | الميزة | التفاصيل |
|:-:|---|---|
| 🎯 | **Template Engine** | أوامر ديناميكية تتحدث فورياً عند تغيير الهدف |
| 🔍 | **بحث فوري** | فلترة الأدوات بالاسم أو الفئة أو الوصف أو نص الأوامر |
| ⭐ | **المفضلة** | حفظ الأدوات المهمة للوصول السريع في أي وقت |
| ✅ | **تتبع التقدم** | تأشير الأوامر المنجزة مع شريط تقدم مرئي لكل أداة |
| 📋 | **Pipelines** | سلاسل أوامر جاهزة تربط الأدوات تلقائياً |
| 💾 | **حفظ الأهداف** | حفظ حتى 8 أهداف والتبديل بينها بنقرة واحدة |
| 📝 | **ملاحظات** | كتابة ملاحظات خاصة لكل أداة تُحفظ تلقائياً |
| 📤 | **تصدير** | تصدير الأوامر كملف `.txt` بأربعة خيارات مختلفة |
| 🖥️ | **اكتشاف الأدوات** | توليد سكريبت Bash يفحص الأدوات المثبتة على نظامك |
| 🌙 | **Dark Mode** | واجهة داكنة كاملة مناسبة لبيئة العمل الليلية |
| 📱 | **Responsive** | متوافق مع الشاشات الكبيرة والمتوسطة |

---

## 🚀 طريقة الاستخدام

### الخطوة 1 — تشغيل الملف

```bash
# macOS
open Recone_fixed.html

# Linux
xdg-open Recone_fixed.html

# Windows
start Recone_fixed.html
```

> أو اسحب الملف مباشرةً إلى نافذة المتصفح

---

### الخطوة 2 — إدخال الهدف

اكتب الهدف في حقل **الهدف / Target** في الشريط الجانبي. الملف يقبل عدة صيغ:

| الصيغة | مثال |
|---|---|
| نطاق | `example.com` |
| عنوان IP | `192.168.1.1` |
| CIDR | `192.168.1.0/24` |
| URL كامل | `https://example.com` |
| Wildcard | `*.example.com` |

> ✅ **تحقق تلقائي:** يُضاء الحقل بالأخضر عند صيغة صحيحة، وبالأحمر عند صيغة خاطئة

---

### الخطوة 3 — اختيار الأداة وتشغيل الأوامر

- اضغط على أي أداة من الشريط الجانبي لفتح لوحة أوامرها
- اضغط **نسخ** بجانب أي أمر لنسخه منفرداً
- اضغط **الكل** في رأس اللوحة لنسخ جميع الأوامر دفعةً واحدة
- الصق الأمر في Terminal وشغّله مباشرةً

---

## 🗂️ مراحل الاستطلاع والأدوات

### 1️⃣ Recon & Scanning — الاستطلاع الفعال

أدوات الفحص النشط للنطاقات والشبكات والثغرات.

<details>
<summary>📂 عرض جميع الأدوات (38 أداة)</summary>

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

</details>

---

### 🕵️ OSINT Intelligence — الاستخبارات المفتوحة

أدوات جمع المعلومات من المصادر المفتوحة.

<details>
<summary>📂 عرض جميع الأدوات (20 أداة)</summary>

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

</details>

---

### 🔎 Search Dorks — استعلامات البحث

قوالب بحث جاهزة لاكتشاف الأصول المكشوفة على محركات البحث والشبكة.

<details>
<summary>📂 عرض جميع الأدوات (33 أداة)</summary>

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

</details>

---

## ⛓️ Pipelines الجاهزة

سلاسل أوامر تربط الأدوات تلقائياً لتنفيذ سيناريوهات كاملة بأمر واحد.
افتح أي أداة ثم اضغط **Pipelines** في رأس لوحة الأوامر.

| Pipeline | الوصف |
|---|---|
| 🔗 **Subfinder → HTTPX → Nuclei** | اكتشاف النطاقات ← فحص الحياة ← فحص الثغرات |
| 🔗 **Katana → GF → Nuclei + Dalfox** | زحف الروابط ← فلترة الأنماط ← استغلال XSS |
| 🔗 **GAU → URO → Param Fuzz** | URLs تاريخية ← تنظيف ← فازينج XSS + SQLi |
| 🔗 **Full Recon Pipeline** | خط استطلاع كامل من الصفر حتى النتائج |
| 🔗 **Secrets & JS Deep Analysis** | تحليل JS عميق وكشف الأسرار والمفاتيح |
| 🔗 **CORS + Open Redirect + SSRF** | فحص ثغرات CORS وإعادة التوجيه وSSRF |
| 🔗 **Directory & API Fuzzing** | اكتشاف مسارات وـ API Endpoints خفية |
| 🔗 **Cloud & S3 Asset Discovery** | اكتشاف S3 Buckets وCloud Misconfigs |

---

## ⚙️ متغيرات القالب

جميع الأوامر تدعم متغيرات تُستبدل تلقائياً عند تغيير أي قيمة:

| المتغير | الوصف | الافتراضي |
|---|---|---|
| `{{T}}` أو `{{TARGET}}` | نطاق الهدف | قيمة حقل الهدف |
| `{{THREADS}}` | عدد الخيوط المتزامنة | `50` |
| `{{RATE}}` | معدل الطلبات / الثانية | `150` |
| `{{OUTPUT}}` | مجلد حفظ المخرجات | `output` |
| `{{PROTO}}` | البروتوكول | `https` |
| `{{WORDLIST}}` | مسار قائمة الكلمات | `/usr/share/seclists/...` |
| `{{DATE}}` | تاريخ اليوم | تلقائي `YYYY-MM-DD` |
| `{{YEAR}}` | السنة الحالية | تلقائي |

> لتغيير القيم: اضغط **متغيرات القالب** في الشريط الجانبي

---

## ⌨️ اختصارات لوحة المفاتيح

| الاختصار | الوظيفة |
|:-:|---|
| `Ctrl` + `K` | التركيز على صندوق البحث |
| `Ctrl` + `E` | فتح نافذة التصدير |
| `J` | الانتقال للأداة التالية |
| `K` | الانتقال للأداة السابقة |
| `F` | إضافة / إزالة الأداة من المفضلة |
| `N` | فتح / إغلاق لوحة الملاحظات |
| `C` | نسخ جميع أوامر الأداة الحالية |
| `Esc` | إغلاق اللوحة أو النافذة المفتوحة |

---

## 📤 تصدير الأوامر

اضغط **تصدير** في أسفل الشريط الجانبي واختر النوع المناسب:

| الخيار | المحتوى |
|---|---|
| 📄 **جميع الأوامر** | كامل الـ 750+ أمر لجميع الأدوات |
| 🎯 **المرحلة الحالية** | أوامر المرحلة المفتوحة فقط |
| ⭐ **المفضلة فقط** | أوامر الأدوات المميّزة بنجمة |
| ✅ **المنجزة فقط** | الأوامر التي تم تأشيرها كمنجزة |

الملف المُصدَّر بصيغة `.txt` منظّم بـ Headers وفواصل واضحة وجاهز للـ Terminal.

---


### 💾 البيانات المحفوظة محلياً

كل البيانات تُحفظ في `localStorage` داخل المتصفح ولا تُرسل لأي خادم:

| المفتاح | المحتوى |
|---|---|
| `bhr_favs` | الأدوات المفضلة |
| `bhr_checks` | الأوامر المؤشّرة كمنجزة |
| `bhr_notes` | الملاحظات لكل أداة |
| `bhr_profiles` | الأهداف المحفوظة |
| `bhr_recent` | آخر 10 أدوات تمت زيارتها |
| `bhr_done_tools` | الأدوات المكتملة 100% |

---

## 💻 متطلبات التشغيل

| المتطلب | التفاصيل |
|---|---|
| **المتصفح** | Chrome 90+ / Firefox 88+ / Edge 90+ / Safari 14+ |
| **الإنترنت** | غير مطلوب — يعمل بالكامل offline |
| **الخادم** | غير مطلوب — يعمل كـ `file://` مباشرة |
| **التثبيت** | غير مطلوب — ملف HTML واحد فقط |


---





<p align="center">
 

</div>
