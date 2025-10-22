# Contributions

**From Clone to Pull Request - a simple guide to contribute:**

This guide walks you through the essential Git workflow — from cloning a repository to opening a Pull Request (PR) a.k.a. make changes.

<div dir="rtl" lang="ar">
هذا الدليل يشرح لك الخطوات الأساسية في Git — بدءًا من استنساخ المستودع وصولًا إلى فتح طلب تعديل (Pull Request)للمساهمة في المشروع.
</div>

---
## Step 1: Download Intellij
[Link to intellij community](https://www.jetbrains.com/idea/download/) a tool that will help you make the necessary changes.

<div dir="rtl" lang="ar">
أداة ستساعدك على إجراء التغييرات اللازمة.
</div>

---
## Step 2: Clone the Repository

Cloning means **creating a local copy** of a remote repository on your computer through below command.

<div dir="rtl" lang="ar">
إنشاء نسخة محلية على جهازك عبر الامر التالي ادناه .
</div>

```shell
git clone https://github.com/aalsanie/luminous.git
```

---
## Step 3: Navigation and Changes
Run intellij and navigate and create the needed files of your changes under the correct folder type.

<div dir="rtl" lang="ar">
شغّل intellij وانتقل إلى المجلد الصحيح أو أنشئ الملفات اللازمة لتغييراتك داخل نوع المجلد او الملف المناسب
</div>

```shell
git checkout main
git pull origin main
git checkout -b feature/your-branch-name
git add .
git commit -m "message"
git push origin feature/your-feature-name
```

---
## Step 4: open a PR 

[What is a Pull Request? (GitHub Docs)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
- Navigate to the repository and click
- “Compare & pull request.” Click it
- Add a **title** and **description** of your changes.
- click **Create Pull Request**.

<div dir="rtl" lang="ar">
    <ul>
      <li><a>https://github.com/aalsanie/luminous/pulls</a> اضغط على</li>
      <li> "Compare & pull request" اضغط على .</li>
      <li> اضف عنوانا لتغييراتك</li>
      <li>اضغط على <b>Create Pull Request</b>.</li>
    </ul>
</div>

---
## Tips

- Use short, descriptive names for branches — e.g., `feature/neural-networks101`, `feature/federating-learning101`, `feature/transforms101` or `feature/block-gps-signal`.
- Use descriptive commit message
- There is no stupid PRs, only stupid bananas
- Always reach out for tech support through contacts in [README](./README)
- Your opinion matters, don't overthink! execute and contribute

<div dir="rtl" lang="ar">
    <ul>
      <li><a href="./README"></a> تواصل دائمًا مع الدعم الفني من خلال جهات الاتصال الموجودة في</li>
      <li>رأيك مهم، لا تفرط في التفكير! نفّذ وساهم.</li>
    </ul>
</div>

----
Message to contributors: I hope I will be able to pay you back in kindness

<div dir="rtl" lang="ar">
رسالة للمساهمين: آمل أن نحدث تغيير.
</div>