# mkdocs-arabic-skelton

This is a skelton for mkdocs Arabic project which is RTL language uses mkdocs-material theme. you have to use `mkdocs` with `material` to generate the docs.

To generate the docs run the command `mkdocs build` , then the docs will be in `public` folder , copy `public` folder where you want. and the documentation website will look like:

Happy Extendying!

هذا مجرد مثال على موقع مستندات توثيق باللغة العربية يمكن توليده من خلال MkDocs يستخدم قالب mkdocs-material. يمكن استخدام هيكلية الملفات لبدء مشروع توثيق جديد ، ولا تنسى استبدال المحتويات هذة الصفحة بالمحتوى المناسب لك.

لإنشاء الوثائق، قم بتشغيل الأمر `mkdocs build`، ثم ستكون الوثائق في مجلد `public`. قم بنسخ مجلد `public` إلى الموقع الذي ترغب فيه. وموقع التوثيق سوف يكون شبيها بالموقع التالي:

![image](https://github.com/Extendy/mkdocs-arabic-skelton/assets/162535/6c9d38e5-6097-4cbc-b829-b07f7ec06816)


تكمن القوة في انشاء مواقع المستندات بهذة الطريقة قي تمكين المطورين من انشاء مستندات التوثيق (باللغة العربية) بشكل متلازم اثناء البرمجة وارفاق مستندات التوثيق ايضا مع الملفات البرمجة ضمن مستودع git
بل ويمكن لهم نشر المستتدات بشكل تلقائي من خلال اوامر deploy

# استخدام المستودع كقالب

يمكنك اخذ نسخه من هذا المستودع (كقالب) والبدء بمستودع جديد خاص بك ومن ثم البدء بمشروعك المستقل لانشاء مستندات التوثيق التي تريد.

من الصفحة الرئيسية للمستودع https://github.com/Extendy/mkdocs-arabic-skelton اختر Use this template الموجوده في اعلى صفحة المستودع على الجهة اليمنى واختر Create a new repository ومن ثم املئ النموذة الخاص بانشاء مستودع جديد كيفما تريد.


راجع الصورة التاليه:
![image](https://github.com/Extendy/mkdocs-arabic-skelton/assets/162535/cdd991a9-09b1-4d9f-bbef-b32871b2a9d0)

بعدها يمكنك العمل على مستودعك الخاص كيفما يحلو لك حيث انه سوف يكون منفصل تماما عن هذا المستودع.


## العمل على MkDocs

هذا القالب يتطلب توفر دعم ل MkDocs على جهازك وهذا بدورة يتطلب توفر لغة دعم python و دعم ل pip على جهازك، للمزيد راجع [https://www.mkdocs.org/user-guide/installation](https://www.mkdocs.org/user-guide/installation/)

(ان شرط توفر mkdocs هو من اجل تنفيذ امر `mkdocs build` الذي يقوم بتحويل ملفات .md المكتوبة بصيغة markdown الى ملفات html، وبالتالي في حال عدم تمكنك من تركيب mkdocs يمكنك الاستمرار في كتابه المستندات بالطريقه الاعتياديه ولكن لعمل build للمستندات لتكون ملفات html فانك سوف تحتاج mkdocs لهذا يمكن نقلها لجهاز متوافق وعمل build).

في حال كانت لغة python و pip موجودة على جهازك فانه يمكن تنصيب mkdocs من خلال الاوامر التالية:
```bash
pip install mkdocs
```

ولاستخدام قالب material هذا المستخدم في هذا الموقع كقالب للمستندات  من خلال Mkdocs فانه يجب عليك ايضا تركيب القالب ولمعرفة كيفية القيام بذلك راجع الرابط التالي [https://squidfunk.github.io/mkdocs-material/getting-started](https://squidfunk.github.io/mkdocs-material/getting-started/)

حيث يتم تركيب material في حال انه لم يكن منصبا بوقت سابق وذلك باستخدام الامر

```bash
pip install mkdocs-material
```

بعدها يمكنك انشاء المستندات وتوليدها عن طريق `mkdocs build` ومن ثم رفع المجلد الذي يتم توليده الى اي مكان فهو يعمل كملفات html ثابتة دون الحاجة لان يدعم الويب سيرفر لاي لغة برمجة ،
فالموقع هو عبارة عن ملفات html.

يجب كتابه ملفات التوثيق بتنسيق markdown وعند تنفيذ امر `mkdocs build` فانه سوف يتم تحويلها الى html ولمعرفة المزيد عن هذا الامر راجع الرابط
[https://www.mkdocs.org/user-guide/writing-your-docs](https://www.mkdocs.org/user-guide/writing-your-docs/)

اذا كنت بحاجة لتعلم طريقة الكتابة بواسطة markdown راجع الرابط التالي
[https://daringfireball.net/projects/markdown/syntax](https://daringfireball.net/projects/markdown/syntax)

## تنويه

في حال كان لديك مشروع برمجي جاهز وتود استخدام المستندات بداخله وبالتالي لا تود عمل git clone لهذا المستودع ، فبامكانك فقط نقل الملف `mkdocs.yaml` بداخل مشروعك في المجلد الذي تحب والبدء باستخدام mkdocs كيفما تحب حيث ان هذا الملف هو ما تحتاجة بالفعل للبدء (مع بعض التحرير لتحديد المجلد المصدر والهدف).


Happy Extendying,

Extendy Team.
