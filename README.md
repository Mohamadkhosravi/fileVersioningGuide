# file_versioning_guide
# نام‌گذاری نسخه‌های فایل‌ها در پروژه

## مقدمه

نام‌گذاری نسخه‌های فایل‌ها یکی از جنبه‌های مهم در مدیریت فایل‌ها، به ویژه در محیط‌های همکاری یا پیگیری تغییرات در طول زمان است. در این راهنما، یک روش ساده برای نام‌گذاری نسخه‌های فایل‌ها به شما معرفی خواهد شد.
#   #
ساختار کلی به این صورت است:

`projectName`_V(`Major Versions` ).(`Minor Versions`).( `Patch Versions`)

![Semver](https://github.com/Mohamadkhosravi/file_versioning_guide/assets/94738811/e1bb260b-0f0c-40a5-9476-36950979490f)

#   #
#  myProject_V1.2.3  مثال

1. `myProject`: نام پروژه است. این بخش می‌تواند هر نام توصیفی باشد که به پروژه اشاره دارد.

2. `V`:  برای ورژن است است و به عنوان جدا‌کننده بین نام پروژه و نسخه استفاده میشود V

3. `Version(نسخه) `:شماره نسخه پروژه است. این می‌تواند به شکل معمولی از شماره‌  1.0.0 شروع شود 

## ساختار نسخه بندی یا ورژن گذاری:  

ساختار نسخه‌بندی در اکثر موارد شامل سه بخش اصلی است:`Major` (نسخه اصلی) شماره اول،` Minor `(نسخه جزئی) شماره دوم و `Patch` (نسخه رفع خرابی) شماره سوم.

این سه بخش نشان‌دهنده انواع تغییرات می‌شوند:

1. Major Version (نسخه اصلی):
   - هنگامی که این عدد تغییر می‌کند، نشان‌دهنده تغییرات اساسی و بزرگ در پروژه است.
   - این تغییرات معمولاً باعث از بین رفتن سازگاری با نسخه‌های قبلی می‌شوند و احتمال دارد که نیاز به تغییرات گسترده در کد یا پروژه  داشته باشند.

2. Minor Version (نسخه جزئی):
   - هنگامی که این عدد تغییر می‌کند، نشان‌دهنده اضافه کردن ویژگی‌ها جدید به پروژه است.
   - تغییرات در این سطح معمولاً باعث می‌شوند که پروژه با نسخه‌های قبلی سازگار باشد و کاربران بتوانند از ویژگی‌های جدید استفاده کنند.

3. Patch Version (نسخه رفع خرابی):
   - هنگامی که این عدد  تغییر می‌کند، نشان‌دهنده رفع خطاها و مشکلات کوچک در پروژه است.
   - این تغییرات عمدتاً به منظور رفع خطاها، اصلاح باگ‌ها و مشکلات کوچک است که به‌صورت اضافه‌کردن یا اصلاح تنها یک یا چند خط کد یاتغیر در پروژه انجام می‌شود.

## مثال‌ها

فرض کنید نام پروژه "myProject" با نسخه 2.3.1 است.تاریخچه فایل‌ها با این ساختار ممکن است به صورت زیر باشند:

- `myProject_V2.3.1`: این نسخه اولیه با شماره نسخه 2.3.1 است.
- `myProject_V2.3.2`: این می‌تواندنشان دهنده اصلاح خطا اول باشد.
- `myProject_V2.3.3`: این می‌تواندنشان دهنده اصلاح خطا دوم باشد.
- `myProject_V2.4.0`: این می‌تواندنشان دهنده اضافه کردن ویژگی های جدید باشد که با نسخه های قبلی سازگار است.
- `myProject_V3.0.0`: این می‌تواند نشان دهنده تغیرات کلی در پروژه باشد.
  #  #
  برای مطالعه دقیق تر میتوانید به لینک ریر رجوع کنید :[رفرنس مطالب](https://semver.org//)
  #  #
  #  #




# File Versioning Guide
# File Versioning in Projects

## Introduction

File versioning is one of the crucial aspects of file management, especially in collaborative environments or when tracking changes over time. In this guide, a simple method for file versioning will be introduced to you.

The general structure is as follows:

`projectName`_V(`Major Versions`).(`Minor Versions`).(`Patch Versions`)

![Semver](https://github.com/Mohamadkhosravi/file_versioning_guide/assets/94738811/e1bb260b-0f0c-40a5-9476-36950979490f)

## Example: `myProject_V1.2.3`

1. `myProject`: This is the project name. This part can be any descriptive name referring to the project.

2. `V`: This stands for version and is used as a separator between the project name and the version.

3. `Version`: This is the project's version number. It can start with a regular number like 1.0.0.

## Versioning Structure:

The versioning structure typically consists of three main parts: `Major`, `Minor`, and `Patch` versions.

These three parts indicate different types of changes:

1. Major Version:
   - When this number changes, it indicates significant and major changes in the project.
   - These changes usually result in incompatibility with previous versions and may require extensive changes in code or the project.

2. Minor Version:
   - When this number changes, it indicates the addition of new features to the project.
   - Changes at this level usually maintain compatibility with previous versions, allowing users to utilize the new features.

3. Patch Version:
   - When this number changes, it indicates the resolution of minor bugs and issues in the project.
   - These changes are typically made to fix small problems, bugs, or minor issues, involving only a few lines of code or changes in the project.

## Examples:

Suppose the project name is "myProject" with version 2.3.1. The history of files with this structure might look like this:

- `myProject_V2.3.1`: This is the initial version with version number 2.3.1.
- `myProject_V2.3.2`: This could indicate the first bug fix.
- `myProject_V2.3.3`: This could indicate the second bug fix.
- `myProject_V2.4.0`: This could indicate the addition of new features that are compatible with previous versions.
- `myProject_V3.0.0`: This could indicate significant changes in the project.

For a more detailed study, you can refer to the [Semantic Versioning (SemVer) documentation](https://semver.org/).
