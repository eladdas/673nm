![SerpBear](https://i.imgur.com/0S2zIH3.png)

# سيرب بير (SerpBear)

![Codacy Badge](https://app.codacy.com/project/badge/Grade/7e7a0030c3f84c6fb56a3ce6273fbc1d) ![GitHub](https://img.shields.io/github/license/towfiqi/serpbear) ![GitHub package.json version](https://img.shields.io/github/package-json/v/towfiqi/serpbear) ![Docker Pulls](https://img.shields.io/docker/pulls/towfiqi/serpbear) [![StandWithPalestine](https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/StandWithPalestine.svg)](https://www.youtube.com/watch?v=bjtDsd0g468&rco=1)

#### [الوثائق](https://docs.serpbear.com/) | [سجل التغييرات](https://github.com/towfiqi/serpbear/blob/main/CHANGELOG.md) | [صورة Docker](https://hub.docker.com/r/towfiqi/serpbear)

سيرب بير هو تطبيق مفتوح المصدر لتتبع ترتيب الكلمات المفتاحية في محركات البحث وإجراء البحوث حولها. يتيح لك متابعة ترتيب كلمات موقعك في جوجل والحصول على تنبيهات عند تغير ترتيبها.

![Easy to Use Search Engine Rank Tracker](https://serpbear.b-cdn.net/serpbear_readme_v2.gif)

#### المزايا

- **عدد غير محدود من الكلمات المفتاحية:** يمكنك إضافة عدد غير محدود من النطاقات والكلمات المفتاحية لتتبع ترتيبها في نتائج البحث.
- **التنبيهات عبر البريد الإلكتروني:** تصلك إشعارات بتغير ترتيب الكلمات المفتاحية يوميًا أو أسبوعيًا أو شهريًا عبر البريد الإلكتروني.
- **واجهة SERP API:** يوفر سيرب بير واجهة برمجة تطبيقات يمكنك استخدامها في أدوات التسويق والتقارير الخاصة بك.
- **بحث الكلمات المفتاحية:** إمكانية البحث عن الكلمات المفتاحية وتوليد أفكار تلقائيًا من محتوى موقعك عند دمج حساب إعلانات جوجل التجريبي.
- **تكامل Google Search Console:** الحصول على عدد الزيارات الفعلي والانطباعات والمزيد لكل كلمة مفتاحية.
- **تطبيق للهواتف:** أضف تطبيق PWA إلى هاتفك لتجربة استخدام أفضل.
- **تشغيل مجاني:** يمكنك تشغيل التطبيق مجانًا على mogenius.com أو Fly.io.

#### كيف يعمل

يستخدم التطبيق خدمات خارجية مثل ScrapingAnt وScrapingRobot وSearchApi وSerpApi وHasData أو عناوين البروكسي التي تقدمها لجلب نتائج البحث من جوجل ومعرفة ما إذا كان نطاقك يظهر للكلمة المطلوبة.

تعمل خاصية البحث عن الكلمات المفتاحية وتوليد الأفكار بدمج حساباتك التجريبية في Google Ads مع سيرب بير. كما يمكنك مشاهدة حجم البحث الشهري للكلمات بعد [دمج Google Ads](https://docs.serpbear.com/miscellaneous/integrate-google-ads).

عند [دمج Google Search Console](https://docs.serpbear.com/miscellaneous/integrate-google-search-console) ستتمكن من مشاهدة زيارات البحث الفعلية لكل كلمة مفتاحية. كما يمكنك اكتشاف كلمات جديدة والتعرف على أفضل الكلمات والبلدان والصفحات أداءً.

#### كيف تبدأ

- **الخطوة 1:** قم بنشر التطبيق وتشغيله.
- **الخطوة 2:** افتح التطبيق وسجل الدخول.
- **الخطوة 3:** أضف نطاقك الأول.
- **الخطوة 4:** احصل على مفتاح API مجاني من ScrapingRobot أو اختر مزودًا مدفوعًا (انظر أدناه). يمكنك التخطي إذا أردت استخدام بروكسي.
- **الخطوة 5:** أضف معلومات خدمة جلب النتائج أو البروكسي من إعدادات التطبيق.
- **الخطوة 6:** أضف كلماتك المفتاحية وابدأ التتبع.
- **الخطوة 7:** اختياري. من لوحة الإعدادات، قم بضبط بيانات SMTP لتصلك الإشعارات عبر البريد الإلكتروني. يمكنك استخدام خدمتي ElasticEmail أو Sendpulse المجانيتين.

#### يتكامل سيرب بير مع خدمات تحصيل نتائج البحث الشهيرة

إذا كنت لا ترغب في استخدام بروكسي، يمكنك الاعتماد على خدمات خارجية لجلب نتائج بحث جوجل.


| Service           | Cost          | SERP Lookup    | API |
| ----------------- | ------------- | -------------- | --- |
| scrapingrobot.com | Free          | 5000/mo        | Yes |
| serply.io         | $49/mo        | 5000/mo        | Yes |
| serpapi.com       | From $50/mo   | From 5,000/mo  | Yes |
| spaceserp.com     | $59/lifetime  | 15,000/mo      | Yes |
| SearchApi.io      | From $40/mo   | From 10,000/mo | Yes |
| valueserp.com     | Pay As You Go | $2.50/1000 req | No  |
| serper.dev        | Pay As You Go | $1.00/1000 req | No  |
| hasdata.com       | From $29/mo   | From 10,000/mo | Yes |

**التقنيات المستخدمة**

- Next.js للواجهة الأمامية والخلفية.
- Sqlite لقاعدة البيانات.
