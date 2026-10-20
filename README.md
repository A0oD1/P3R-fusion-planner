# P3R Fusion Planner

**مخطط دمج البيرسوناز في Persona 3 Reload — تطوير A0oD**  
**A Persona 3 Reload fusion and skill inheritance planner — developed by A0oD**

واجهة عربية وإنجليزية تساعدك على الوصول إلى بيرسونا محددة انطلاقًا من البيرسوناز المسجلة عندك، مع مراعاة لفلك، وبكجات DLC، وشروط الفتح، والمهارات المطلوبة.

A bilingual Arabic / English tool for finding fusion routes from your registered Personas to a chosen target, with level limits, DLC packs, unlock requirements, and optional skill inheritance planning.

**[العربية](#العربية) · [English](#english)**

---

## العربية

### عن الأداة

بدل البحث عن كل دمجة بشكل منفصل، حدد البيرسوناز المسجلة في الـCompendium، ثم اختر الهدف. تعرض الأداة قائمة الاستدعاءات وتكلفتها وخطوات الدمج بالترتيب. ويمكنك إضافة المهارات التي تريدها على الهدف ليبحث المخطط عن طريق ينقلها إليه.

المشروع مخصص **للقصة الأساسية من Persona 3 Reload**، ويعمل داخل المتصفح من ملف `index.html` واحد، بدون تثبيت أو خادم أو مكتبات خارجية. ويمكن فتح الملف محليًا أو استضافته على GitHub Pages.

### المميزات

- **عربي / English:** زر تبديل اللغة، مع حفظ اختيارك وتغيير اتجاه الواجهة تلقائيًا بين RTL وLTR.
- **سجل البيرسوناز:** بحث بالاسم أو الأركانا، تحديد المسجل، وإضافة مجموعة أسماء دفعة واحدة.
- **أولوية المسار:** أقل تكلفة استدعاء أو أقل عدد دمجات.
- **حد اللفل:** تقييد الهدف والبيرسوناز الوسيطة باللفل المحدد.
- **بكجات DLC:** تفعيل البكجات التي تملكها لتعديل نتائج الدمج وفقها.
- **شروط الفتح:** السوشال لينكس الـ22 عند Rank 10، وطلبات إليزابيث، والتقدم، وروابط أحداث الفريق.
- **دمج عادي وخاص:** حساب المكونات الوسيطة والوصفات الخاصة متعددة البيرسوناز.
- **تخطيط المهارات:** اختيار حتى 8 مهارات، مع فحص أنواع التوريث والمهارات الخاصة وخانات التوريث.
- **اقتراح بيلد:** اقتراح مبدئي حسب الدور، مثل الضرر بعنصر محدد أو الدعم والعلاج.
- **مهارات المصادر:** تعديل المهارات الفعلية على نسخك المسجلة بدل الاعتماد على الافتراضات الأصلية.
- **Skill Cards:** تحديد البطاقات التي تملكها لاستخدامها على الهدف بعد آخر دمجة.
- **أسعار قابلة للتعديل:** إدخال سعر الاستدعاء الفعلي أو تحديد نسبة خصم للأسعار الافتراضية.
- **حفظ ونسخ احتياطي:** حفظ محلي، وتصدير واستيراد ملف JSON، ونسخ الخطة كنص.
- **تشخيص الفشل:** توضيح شروط المكونات أو قيود المهارات التي قد تمنع العثور على خطة.

تبقى أسماء البيرسوناز والمهارات بالإنجليزي في اللغتين لتسهيل مطابقتها مع اللعبة ومصدر البيانات. أوصاف المهارات وشروط المصدر الإنجليزية ليست معرّبة بالكامل.

### الاستخدام

1. افتح `index.html` في المتصفح أو افتح رابط الموقع المنشور.
2. حدد لفلك الحالي وبكجات DLC التي تملكها.
3. حدد البيرسوناز **المسجلة فعلًا** في الـCompendium. يمكنك لصق الأسماء الإنجليزية، اسم بكل سطر أو مفصولة بفواصل.
4. من **شروط الفتح**، حدد فقط الروابط والشروط التي أكملتها. مثال: `Hierophant · MAX` يفتح `Kohryu`.
5. اختر بيرسونا الهدف.
6. اختياريًا، أضف المهارات المطلوبة أو اضغط **اقترح بيلد**. عدّل مهارات المصادر إذا كانت نسخك تختلف عن الأصلية، وحدد بطاقات المهارات التي تملكها فقط.
7. اختر **أقل تكلفة** أو **أقل عدد دمجات**، ثم اضغط **احسب مسار الدمج**.
8. اتبع قائمة الاستدعاءات وخطوات الدمج والتدريب والتوريث بالترتيب. استدعِ النسخ المتكررة عند الحاجة؛ لا يلزم حملها كلها معًا.

### الأسعار ودقة النتائج

- الأسعار الافتراضية تقديرية، وتعتمد على الستاتس الأساسية. للحصول على حساب أقرب للعبتك، أدخل سعر كل استدعاء كما يظهر داخل اللعبة.
- السعر اليدوي له الأولوية، ولا تطبق عليه نسبة الخصم مرة ثانية.
- التكلفة تشمل استدعاء كل نسخة مطلوبة، ولا تشمل وقت التدريب أو تكلفة اكتساب البطاقات.
- **أقل عدد دمجات** يعني تقليل عدد عمليات الدمج، وليس قياس الوقت الفعلي داخل اللعبة.
- يستخدم الحساب اللفل الأساسي للبيرسوناز، ويقيد تعلم المهارات الطبيعي بحد التدريب المحدد عبر لفلك الحالي.
- افتراضيًا، يفترض مخطط المهارات أن المصادر تحتفظ بمهاراتها الطبيعية ويمكن تدريبها. عند إدخال قائمة مهارات يدوية، يستخدمها كما هي دون إضافة مهارات تدريب تلقائيًا.
- مسارات البيرسونا فقط تُحسّن ضمن الأسعار والإعدادات ونموذج استدعاء مستقل لكل نسخة. **بحث المهارات لا يضمن إيجاد أرخص بيلد عالميًا أو جميع المسارات الممكنة**؛ يحتفظ بأفضل مرشح لكل مجموعة مهارات ويستخدم فحصًا محافظًا لخانات التوريث.
- اقتراح البيلد نقطة بداية قابلة للتعديل، ولا يضمن إمكان جمع كل المهارات المقترحة في طريق واحد.
- لا يُحسب المخزون المحمول، أو إعادة استخدام تسجيلات جديدة أنشأتها أثناء الخطة، أو الاستدعاء المجاني الأول للـDLC، أو نتائج حوادث الدمج وSkill Mutation العشوائية.
- لا تعدّل الأداة ملفات اللعبة أو الحفظ، ولا تقرأ الـCompendium من اللعبة تلقائيًا. Episode Aigis غير مدعوم حاليًا.

### إذا لم تظهر خطة

- تأكد من اللفل وبكجات DLC وأسماء البيرسوناز المسجلة.
- راجع شروط **المكونات الوسيطة**؛ فتح الهدف وحده لا يفتح كل مكوناته. قد يتطلب مكوّن Linked Episodes بينما يتطلب الهدف Social Link مختلفًا.
- أضف مصادر أخرى من سجلك. تحديد شرط الفتح لا يوفر البيرسونا أو مكوناتها تلقائيًا.
- جرّب حساب الهدف بدون مهارات أولًا. إذا نجح، راجع مهارات المصادر وأنواع التوريث والخانات والبطاقات المطلوبة.
- إذا ظهرت مهارة خاصة غير قابلة للتوريث، اختر هدفًا يتعلمها طبيعيًا أو غيّر المهارة.

### الحفظ والخصوصية

تجري الحسابات داخل متصفحك. تستخدم الأداة `localStorage` لحفظ سجلك وإعداداتك واللغة، ولا تتضمن تسجيل حساب أو إرسال بياناتك إلى خادم أو أدوات تحليل مدمجة.

قد لا يعمل الحفظ المحلي في بعض إعدادات الخصوصية أو المتصفحات عند فتح الملفات مباشرة. استخدم **تصدير بياناتي** للاحتفاظ بنسخة، خصوصًا قبل مسح بيانات المتصفح أو الانتقال إلى جهاز أو متصفح أو رابط موقع مختلف. بيانات الملف المحلي والموقع المنشور ليست بالضرورة مشتركة.

### التشغيل والنشر على GitHub Pages

ملف التشغيل الوحيد المطلوب هو `index.html`. ملف `README.md` يوثق المشروع ولا يلزم لتشغيله. لا توجد خطوة بناء أو أوامر تثبيت.

1. ارفع `index.html` و`README.md` إلى جذر المستودع العام.
2. افتح **Settings → Pages**.
3. في **Source** اختر **Deploy from a branch**.
4. اختر الفرع **main** والمجلد **/ (root)**، ثم **Save**.
5. بعد اكتمال النشر، افتح الرابط الظاهر في صفحة Pages.

لتحديث الموقع، استبدل `index.html` بالنسخة الجديدة واحفظ التغيير في الفرع المستخدم للنشر.

[دليل GitHub Pages الرسمي](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

### الإبلاغ عن المشاكل والمساهمة

عند فتح Issue، أرفق الهدف، واللفل، وبكجات DLC، وشروط الفتح، وأسماء المصادر، والمهارات المطلوبة، ورسالة الخطأ أو لقطة للنتيجة. يمكنك إرفاق تصدير JSON بعد مراجعة محتواه لتسهيل إعادة التجربة.

اقتراحات التحسين وتصحيحات البيانات مرحب بها. اشرح السلوك المتوقع والفعلي، وأرفق مصدرًا عند اقتراح تعديل في قواعد اللعبة.

### المطور والحقوق والمصادر

**تطوير الأداة: A0oD**  
**© 2026 A0oD. حقوق تطوير المشروع والواجهة والتعديلات الخاصة به محفوظة.**

تعتمد بيانات البيرسوناز والمهارات وجداول ووصفات الدمج وقواعدها على مشروع **Megaten Fusion Tool** للمطور **aqiu384**:

- [حاسبة Persona 3 Reload الأصلية](https://aqiu384.github.io/megaten-fusion-tool/p3r/personas)
- [مستودع المصدر](https://github.com/aqiu384/megaten-fusion-tool)
- [ترخيص المصدر — Public Domain / Unlicense](https://github.com/aqiu384/megaten-fusion-tool/blob/master/LICENSE.md)

نسبة تطوير هذه الأداة إلى A0oD لا تنسب إليه إنشاء بيانات المصدر أو ملكية اللعبة. حقوق المواد الخارجية تخضع لشروط أصحابها. **Persona 3 Reload** وأسماؤها وعلاماتها مملوكة لأصحاب الحقوق المعنيين، بما في ذلك ATLUS وSEGA. هذا مشروع جماهيري مستقل وغير تابع أو معتمد رسميًا منهم.

---

## English

### About

Select the Personas registered in your Compendium and choose a target. The planner provides the required summons, estimated costs, and ordered fusion steps. Optionally request skills and search for a route that carries them to the target.

This project supports the **main story of Persona 3 Reload**. It runs entirely in the browser from a single `index.html` file, with no installation, backend, external libraries, or build step. Open it locally or host it on GitHub Pages.

### Features

- Arabic / English switching, saved language preference, and RTL / LTR layout.
- Searchable Compendium selection and bulk name entry.
- Lowest summoning cost or fewest-fusions priorities.
- Player-level limits for the target and intermediate Personas.
- Configurable DLC packs that change fusion results.
- All 22 MAX Social Link unlocks, requests, story progression, and teammate Linked Episode requirements.
- Normal and special fusion recipes with intermediate ingredients.
- Up to 8 requested build skills, with inheritance-type, exclusive-skill, and slot checks.
- Editable role-based build suggestions and actual source skill lists.
- Optional use of Skill Cards explicitly marked as owned.
- Editable summon prices and a discount for default estimates.
- Local saving, JSON import / export, and copyable route text.
- Explanations for unsuccessful searches and missing ingredient unlocks.

Persona and skill names remain in English in both interface languages. Source skill descriptions and unlock conditions are also retained in English where applicable.

### How to use

1. Open `index.html` or the published website.
2. Set your current level and enable the DLC packs you own.
3. Select the Personas actually registered in your Compendium. Bulk entry accepts full English names separated by lines or commas.
4. Mark only completed requirements under **Unlocks**. For example, `Hierophant · MAX` unlocks `Kohryu`.
5. Choose your target Persona.
6. Optionally request skills or select **Suggest a build**. Edit source skills if your registered copies differ from their natural skills, and only mark Skill Cards you own.
7. Choose **Lowest cost** or **Fewest fusions**, then calculate.
8. Follow the summons, training, inheritance selections, and fusions in order. Summon repeated copies as needed; you do not need to carry everything at once.

### Accuracy and limitations

- Default prices estimate base stats. Enter your actual in-game summoning prices for more accurate cost comparisons. Manual prices take priority and are not discounted again.
- Costs include each required summon, not training time or acquiring Skill Cards. Fewest fusions minimizes fusion operations, not elapsed gameplay time.
- Calculations use base Persona levels. Natural skill training is capped at your selected player level.
- Default sources are assumed to retain their natural skills and be trainable. Manually entered skill lists are used as entered, without automatically adding later natural skills.
- Persona-only routes are optimized within the selected prices, settings, and independent summoning model. **Skill search does not guarantee the globally cheapest build or exhaustive discovery of every valid route.** It retains the best candidate per skill set and uses conservative inheritance-slot checks.
- Suggested builds are editable starting points, not guarantees that all suggested skills can be combined.
- Carried inventory, reuse of newly created Compendium registrations, first-time free DLC summons, fusion accidents, and random Skill Mutation outcomes are not modeled.
- This is a standalone planner: it does not edit saves, modify the game, or automatically read your Compendium. Episode Aigis is not currently supported.

### Troubleshooting

Check your level, enabled DLC, source names, and intermediate ingredient unlocks. Unlocking the target does not unlock or provide every ingredient. Add more registered sources if necessary.

Try calculating without requested skills first. If that works, check actual source skills, inheritance types, slot limits, and owned Skill Cards. An exclusive skill must be naturally available to the appropriate target rather than inherited from another Persona.

### Saving and privacy

Calculations run in your browser. `localStorage` holds the Compendium, settings, and language preference. The tool includes no account system, embedded analytics, or server-side transmission of your saved data.

Local saving can be restricted by privacy settings or when opening local files. Export a JSON backup before clearing browser data or moving to another device, browser, or website address. Local-file storage and hosted-site storage are not necessarily shared.

### GitHub Pages deployment

Only `index.html` is needed to run the tool. `README.md` documents the project. No package manager or build process is required.

1. Upload both files to the root of a public repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch** as the source.
4. Choose **main** and **/ (root)**, then save.
5. Once deployment completes, open the URL shown on the Pages settings screen.

To update the site, replace `index.html` and commit the change to the publishing branch.

[Official GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

### Issues and contributions

Include your target, level, DLC packs, unlocks, registered sources, requested skills, and the error or result when reporting an issue. An exported JSON profile can help reproduce the problem; review its contents before sharing it.

Improvements and data corrections are welcome. Describe expected versus actual behavior and include a source when proposing changes to game rules.

### Developer, attribution, and rights

**Developed by A0oD**  
**Copyright © 2026 A0oD. Rights to project-specific development, interface, and modifications are reserved.**

Persona data, skill data, fusion charts, recipes, and underlying game rules are based on **aqiu384's Megaten Fusion Tool**:

- [Original Persona 3 Reload calculator](https://aqiu384.github.io/megaten-fusion-tool/p3r/personas)
- [Upstream repository](https://github.com/aqiu384/megaten-fusion-tool)
- [Upstream public-domain / Unlicense terms](https://github.com/aqiu384/megaten-fusion-tool/blob/master/LICENSE.md)

A0oD's project credit does not claim authorship of the upstream data or ownership of the game. Third-party material remains subject to its applicable terms. **Persona 3 Reload**, its names, and trademarks belong to their respective rights holders, including ATLUS and SEGA. This is an independent fan project and is not officially affiliated with or endorsed by them.
