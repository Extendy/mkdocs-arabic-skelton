# mkdocs-arabic-skelton

This is a skelton for mkdocs Arabic project which is RTL language. you have to use `mkdocs` with `material` to generate the docs.

To generate the docs run the command `mkdocs build` , then the docs will be in `public` folder , copy `public` folder where you want.

Happy Extendying!

هذا مجرد مثال على موقع مستندات توثيق باللغة العربية يمكن توليده من خلال MkDocs. يمكن استخدام هيكلية الملفات لبدء مشروع توثيق جديد ، ولا تنسى استبدال محتوى هذة الصفحة بالمحتوى المناسب لك.

تكمن القوة في انشاء مواقع المستندات بهذة الطريقة قي تمكين المطورين من انشاء مستندات التوثيق بشكل متلازم اثناء البرمجة وارفاق مستندات التوثيق ايضا مع الملفات البرمجة ضمن مستودع git
بل ويمكن لهم نشر المستتدات بشكل تلقائي من خلال اوامر deploy

# استخدام المستودع كقالب

يمكنك اخذ نسخه من هذا المستودع (كقالب) والبدء بمستودع جديد خاص بك ومن ثم البدء بمشروعك المستقل لانشاء مستندات التوثيق التي تريد.

من الصفحة الرئيسية للمستودع https://github.com/Extendy/mkdocs-arabic-skelton اختر Use this template الموجوده في اعلى صفحة المستودع على الجهة اليمنى واختر Create a new repository ومن ثم املئ النموذة الخاص بانشاء مستودع جديد كيفما تريد.


راجع الصورة التاليه:
![image](https://github.com/Extendy/mkdocs-arabic-skelton/assets/162535/cdd991a9-09b1-4d9f-bbef-b32871b2a9d0)

بعدها يمكنك العمل على مستودعك الخاص كيفما يحلو لك حيث انه سوف يكون منفصل تماما عن هذا المستودع.


## العمل على MkDocs

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

