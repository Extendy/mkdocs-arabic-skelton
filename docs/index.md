#الصفحة الرئيسية

هذا مجرد مثال على موقع مستندات توثيق باللغة العربية يمكن توليده من خلال MkDocs. يمكن استخدام هيكلية الملفات لبدء مشروع توثيق جديد ، ولا تنسى استبدال محتوى هذة الصفحة بالمحتوى المناسب لك.

تكمن القوة في انشاء مواقع المستندات بهذة الطريقة قي تمكين المطورين من انشاء مستندات التوثيق بشكل متلازم اثناء البرمجة وارفاق مستندات التوثيق ايضا مع الملفات البرمجة ضمن مستودع git
بل ويمكن لهم نشر المستتدات بشكل تلقائي من خلال اوامر deploy

## تركيب MkDocs

من اجل انشاء المستندات يجب على جهازك ان يحتوي على Mkdocs والذي يمكن معرفة كيفية تركيبه من خلال الرابط التالي
[https://www.mkdocs.org/user-guide/installation](https://www.mkdocs.org/user-guide/installation/)
حيث انه يجب على جهازك ان يحتوي على دعم ل python و pip ومن ثم تركيب MkDocs.

ولاستخدام قالب material هذا المستخدم في هذا الموقع كقالب للمستندات  من خلال Mkdocs فانه يجب عليك ايضا تركيب القالب ولمعرفة كيفية القيام بذلك راجع الرابط التالي
[https://squidfunk.github.io/mkdocs-material/getting-started](https://squidfunk.github.io/mkdocs-material/getting-started/)

بعدها يمكنك انشاء المستندات وتوليدها عن طريق `mkdocs build` ومن ثم رفع المجلد الذي يتم توليده الى اي مكان فهو يعمل كملفات html ثابتة دون الحاجة لان يدعم الويب سيرفر لاي لغة برمجة ،
فالموقع هو عبارة عن ملفات html.

يجب كتابه ملفات التوثيق بتنسيق markdown وعند تنفيذ امر `mkdocs build` فانه سوف يتم تحويلها الى html ولمعرفة المزيد عن هذا الامر راجع الرابط
[https://www.mkdocs.org/user-guide/writing-your-docs](https://www.mkdocs.org/user-guide/writing-your-docs/)

اذا كنت بحاجة لتعلم طريقة الكتابة بواسطة markdown راجع الرابط التالي
[https://daringfireball.net/projects/markdown/syntax](https://daringfireball.net/projects/markdown/syntax)


تمتلك markdown قدرة ممتازه لمساعده المطورين اثناء التوثيق بما في ذلك قدرتهم على ارفاق الاكواد البرمجية كامثله للمساعدة على التوضيح ، مثال:

```php title="index.php" linenums="1" hl_lines="3 4"
<h1>This is just a test</h1>
<?php
echo "<p>Hello World</p>";
echo "<p>Thanks</p>";
?>
```
لمعرفة اكثر حول الاكواد راجع
[https://squidfunk.github.io/mkdocs-material/reference/code-blocks/](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/)
