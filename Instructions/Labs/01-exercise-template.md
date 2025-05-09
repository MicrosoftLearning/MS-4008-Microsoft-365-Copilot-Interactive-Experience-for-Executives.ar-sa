---
lab:
  title: عنوان التدريب
  module: Learn module title
---
<!--
Edit the metadata above to manage the list of exercises in the home page of the GitHub site that gets generated.
You can delete the module and edit index.md in the root of the repo to customize the display so that only the exercises are listed
To enable GitHub page publishing, edit the Page settings for the repo and publish from the main branch
-->

# عنوان التدريب <!-- match title in metadata above (and Learn Exercise unit and ILT slide)-->

في هذا التدريب سوف <!-- provide a description of what they'll do and why it;s important -->

يجب أن يستغرق هذا التدريب حوالي <b>XX</b> دقيقة لإكماله. <!-- update with estimated duration -->

## قبل أن تبدأ

<!--
Add steps to get the learner to the starting point" for the exercise.
This might be cloning the repo and running a script or performing some manual steps.
Only include this section if its necessary to do some pre-exercise setup AND the same setup steps are required for self-paced (on Learn) and managed (in hosted ILT lab profiles) scenarios. Otherwise delete this section.
If self-paced /ILT-specific setup steps are required, include them in the Learn "Exercise" unit from where they open this exercise and in the Skillable lab profile instructions before this markdown file is imported.
 -->

قبل أن تتمكن من البدء في هذا التدريب، ستحتاج إلى...

1. الخطوة 1
1. الخطوة 2
1. وغيرها

## مهمة <!-- Change to an appropriate task title with an imperative verb phrase (e.g. "Do something") -->

أولًا، عليك أن...
<ol dir='rtl'>
<li>
الخطوة 1
</li>
<li>
1تضمن هذه الخطوة مثالًا لـ <code>inline code formatting</code>، والذي يتم استخدامه عندما يحتاج المُتعلم إلى كتابة شيء ما (أي شيء، وليس مجرد تعليمة برمجية) لأنه ينشئ رابط [T] في بيئة Skillable المستضافة.
</li>
<li>
إذا كنت تريد من المتعلم فتح موقع ويب، فقم بتضمين رابط (حتى يتمكن من فتحه بالنقر فوق صفحة HTML على GitHub) وعنوان URL بتنسيق تعليمة برمجية (حتى يتمكن من كتابته في متصفح VM المستضاف). على سبيل المثال، "افتح موقع الويب <code>https://www.bing.com</code> على <a href="https://www.bing.com">[Bing]</a>".
</li>
<li>
1ذا كنت تريد من المتعلم تنزيل ملف (أو مجموعة من الملفات في ملف مضغوط)، فخزّن الملف في مجلد Allfiles في مخزن البيانات الخاصة هذا واستخدم عنوان URL <b>الخام</b> - مثل هذا: "تنزيل <a href="https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json">[اسم الملف]</a> من <code>https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json</code>.
</li>
<li>
بدلًا من ذلك، بالنسبة لجمهور المطورين، يمكنك أن تطلب منهم استنساخ مخزن البيانات الخاصة هذا إذا كان ذلك يبدو أكثر ملاءمة.
</li>
<li>
إذا كنت بحاجة إلى تضمين كتلة تعليمات برمجية متعددة الأسطر، فضع مسافة بادئة لها لتتوافق مع المسافة البادئة للقائمة ذات التعداد النقطي:
<pre><code>    
    # This is an example of an
    # indented code block.
</code></pre>    
</li>
<li>
إذا كنت بحاجة إلى تضمين لقطة شاشة، فغيّر حجمها إلى الحجم المناسب (لذلك فإن أي نص منسق "عادي" في لقطة شاشة جزئية يكون بنفس حجم هذا النص تقريبًا - حاول عمومًا إنشاء لقطات شاشة لنوافذ التطبيق الكاملة بحجم 800 × 600 بكسل (تقريبًا)). خزّن الصور في المجلد الفرعي <b>الوسائط</b> واستخدم Markdown لإضافتها إلى الصفحة (تذكر أن أسماء الملفات والمجلدات حساسة لحالة الأحرف). إذا كانت الصورة موجودة في قائمة، غيّر المسافة البادئة لها، مثل هذا:
<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives.ar-sa/blob/main/Instructions/Labs/Media/edge-copilot.png"><img src="https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives.ar-sa/blob/main/Instructions/Labs/Media/edge-copilot.png" alt="لقطة شاشة للتطبيق."> </a></p>

</li>
<li>

1ذا كنت بحاجة إلى شرح سبب القيام بشيء ما بالطريقة التي يتم بها، أو تقديم سياق إضافي أو روابط للمعلومات، فاستخدم ملاحظة مثل هذه:

<blockquote>
      <b>ملاحظة</b>: هذه ملاحظة.
</blockquote>

</li>
<li>
كن مرنًا عند تقديم الإرشادات التي قد تختلف بين بيئة نشاط عملي ذاتية التعلم وتلك المستضافة. على سبيل المثال:
  <ul dir='rtl'>
<li>
    "تسجيل الدخول باستخدام بيانات اعتماد Azure" (على افتراض وجود تعليمات خاصة بـ Learn لاستخدام اشتراك شخصي أو إنشاء نسخة تجريبية في صفحة تمرين Learn، وتعليمات خاصة بـ ILT لاستخدام بيانات اعتماد cloudslice المقدمة في ملف تعريف النشاط العملي Skillable)
</li>
<li>
    "حدد مجموعة موارد موجودة أو أنشئ مجموعة موارد جديدة" (على افتراض أنه إذا تم استخدام Skillable CS-R cloudslice، فقد قمت بتضمين ملاحظة في ملف تعريف النشاط العملي تخبر المتعلم بمجموعة الموارد التي يجب أن يستخدمها)
    <!-- The key point is that this markdown file should be environment-agnostic - you need to provide explicit details of things that can vary OUTSIDE of this file (in the Learn exercise page or the Skillable lab profile instructions) -->
</li>
</ul>

<li>وغيرها
</li>
</ol>

## المهمة التالية

الآن دعونا، ...

1. الخطوة 1
1. الخطوة 2
1. وغيرها

## مهمة ذات مهام فرعية

في بعض الأحيان قد ترغب في تقسيم مهمة إلى أجزاء أصغر.

### المهمة الفرعية 1

1. الخطوة 1
1. الخطوة 2
1. إلخ...

### المهمة الفرعية 2

1. الخطوة 1
1. الخطوة 2
1. وغيرها

## تنظيف

<!-- Good practice - especially as self-paced learners will be using their own subscriptions -->
<!-- Delete this section if it is not needed -->

الآن بعد أن انتهيت من التدريب، يجب عليك حذف موارد السحابة التي قمت بإنشائها لتجنب استخدام الموارد غير الضرورية.

1. الخطوة 1
2. وغيرها
