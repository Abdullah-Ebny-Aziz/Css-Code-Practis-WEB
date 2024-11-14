

1. **HTML কী, এবং এটি ওয়েব ডেভেলপমেন্টে কেন গুরুত্বপূর্ণ?**
   - HTML (HyperText Markup Language) হলো ওয়েব পেজের কাঠামো গঠনের জন্য ব্যবহৃত ভাষা। এটি ওয়েবসাইটের বিভিন্ন উপাদান (যেমন হেডার, প্যারা, ইমেজ) তৈরি ও তাদের সাজানোর কাজ করে, যা ওয়েব ডেভেলপমেন্টে অপরিহার্য।

2. **HTML ট্যাগ এবং অ্যাট্রিবিউট কী?**
   - HTML ট্যাগ হলো কোডের অংশ, যা ব্রাউজারকে নির্দেশ করে কোন কন্টেন্ট কীভাবে প্রদর্শিত হবে। অ্যাট্রিবিউট হলো ট্যাগের গুণাবলী যা ঐ ট্যাগের বৈশিষ্ট্য নির্ধারণ করে। যেমন, `<img src="image.jpg" alt="ছবি">` এখানে `src` এবং `alt` অ্যাট্রিবিউট।

3. **HTML এ inline, block, এবং inline-block এলিমেন্টের মধ্যে পার্থক্য কী?**
   - Inline এলিমেন্ট লাইন ধরেই প্রদর্শিত হয়, যেমন `<span>`, block এলিমেন্ট পূর্ণ লাইনে এককভাবে থাকে, যেমন `<div>`, এবং inline-block এলিমেন্ট inline থাকে কিন্তু block-এর মতো behave করে।

4. **HTML এ `DOCTYPE` ঘোষণার উদ্দেশ্য কী?**
   - `<!DOCTYPE html>` ডকুমেন্টের শুরুতে ব্যবহার করে ব্রাউজারকে বলে দেয় যে এটি HTML5 ডকুমেন্ট। এটি ব্রাউজারের সঠিক rendering নিশ্চিত করতে সাহায্য করে।

5. **HTML ডকুমেন্ট কীভাবে গঠন ও সংগঠিত করা হয়?**
   - একটি HTML ডকুমেন্টের প্রধান অংশ হলো `<html>`, যার মধ্যে `<head>` এবং `<body>` থাকে। `<head>` অংশে মেটাডাটা থাকে এবং `<body>` অংশে মূল কন্টেন্ট।

6. **HTML এর Semantic এলিমেন্ট কী এবং এগুলো কেন ব্যবহার করবেন?**
   - Semantic এলিমেন্টগুলো যেমন `<header>`, `<footer>`, `<article>`, এগুলো কন্টেন্টের অর্থ স্পষ্ট করে। এটি SEO এবং অ্যাক্সেসিবিলিটির জন্য ভালো।

7. **HTML এ একটি হাইপারলিংক কীভাবে তৈরি করবেন, এবং `<a>` ট্যাগের কিছু সাধারণ অ্যাট্রিবিউট কী?**
   - হাইপারলিংক তৈরি করতে `<a href="link">লিংক টেক্সট</a>` ব্যবহার করা হয়। এর সাধারণ অ্যাট্রিবিউট হলো `href` (লিংক ঠিকানা) এবং `target="_blank"` (নতুন ট্যাবে খুলতে)।

8. **HTML এ `<meta>` ট্যাগের উদ্দেশ্য কী?**
   - `<meta>` ট্যাগ SEO, রেস্পন্সিভনেস, এবং ক্যারেক্টার সেট সংজ্ঞায়নে ব্যবহৃত হয়। যেমন `<meta charset="UTF-8">` ডকুমেন্টের ক্যারেক্টার সেট নির্ধারণ করে।

9. **HTML এ ছবি কীভাবে প্রয়োগ করবেন এবং `src` এবং `alt` অ্যাট্রিবিউটের মধ্যে পার্থক্য কী?**
   - ছবি যোগ করতে `<img src="image.jpg" alt="ছবির বর্ণনা">` ট্যাগ ব্যবহার করা হয়। `src` হলো ছবির ফাইলের লিংক এবং `alt` ছবি লোড না হলে বর্ণনা দেখায় ও অ্যাক্সেসিবিলিটির জন্য গুরুত্বপূর্ণ।

10. **HTML5 এবং পূর্বের HTML সংস্করণের মধ্যে পার্থক্য কী?**
    - HTML5 নতুন সেম্যান্টিক ট্যাগ যেমন `<section>`, `<header>`, ভিডিও ও অডিও সাপোর্ট এবং উন্নত ফর্ম বৈশিষ্ট্য এনেছে, যা পূর্ববর্তী সংস্করণে ছিল না।


ফর্ম এবং টেবিল ট্যাগ সম্পর্কে কিছু প্রশ্ন ও উত্তর এখানে দেওয়া হলো:

### ফর্ম ট্যাগ সম্পর্কিত প্রশ্ন এবং উত্তর:

1. **HTML ফর্ম কী এবং এটি কেন ব্যবহৃত হয়?**
   - HTML ফর্ম ব্যবহারকারীদের থেকে ডেটা সংগ্রহের জন্য ব্যবহৃত হয়। এটি সাধারণত লগইন, রেজিস্ট্রেশন, অনুসন্ধান বা মন্তব্য প্রদানের জন্য ব্যবহৃত হয়। 

2. **ফর্মে অ্যাকশন এবং মেথড অ্যাট্রিবিউটের ভূমিকা কী?**
   - `action` অ্যাট্রিবিউটটি নির্ধারণ করে যে ফর্মের ডেটা কোথায় পাঠানো হবে এবং `method` অ্যাট্রিবিউটটি নির্ধারণ করে কীভাবে ডেটা পাঠানো হবে, যেমন `GET` বা `POST` মেথড ব্যবহার করে।

3. **ফর্মে `input` ট্যাগের বিভিন্ন ধরন কী কী?**
   - `input` ট্যাগের বিভিন্ন ধরন হলো `text` (টেক্সট ইনপুট), `password` (পাসওয়ার্ড ইনপুট), `email` (ইমেইল ইনপুট), `radio` (রেডিও বোতাম), `checkbox` (চেকবক্স), `submit` (সাবমিট বোতাম) ইত্যাদি।

4. **ফর্মের জন্য `label` ট্যাগ কেন ব্যবহৃত হয়?**
   - `label` ট্যাগ ব্যবহারকারীর অভিজ্ঞতা উন্নত করতে ইনপুট ফিল্ডের জন্য লেবেল তৈরি করে, যা অ্যাক্সেসিবিলিটির জন্য গুরুত্বপূর্ণ। এটি ব্যবহারকারীদের ফিল্ডের উদ্দেশ্য সহজে বোঝায়।

5. **`textarea` এবং `select` ট্যাগের উদ্দেশ্য কী?**
   - `textarea` ট্যাগ বড় টেক্সট ইনপুটের জন্য ব্যবহৃত হয় এবং `select` ট্যাগ ড্রপডাউন মেনু তৈরি করে, যা থেকে ব্যবহারকারী একটি অপশন বেছে নিতে পারে।

6. **`button` এবং `input type="submit"` এর মধ্যে পার্থক্য কী?**
   - `button` ট্যাগ বিভিন্ন কাজের জন্য ব্যবহার করা যেতে পারে, যেমন জাভাস্ক্রিপ্ট দিয়ে ইভেন্ট চালানো। তবে, `input type="submit"` বিশেষভাবে ফর্ম জমা দেওয়ার জন্য ব্যবহৃত হয়।

### টেবিল ট্যাগ সম্পর্কিত প্রশ্ন এবং উত্তর:

1. **HTML টেবিল কী এবং কেন ব্যবহৃত হয়?**
   - HTML টেবিল ডেটা সংগঠিতভাবে প্রদর্শনের জন্য ব্যবহৃত হয়, যেমন সারি ও কলাম আকারে। এটি রিপোর্ট, তালিকা বা সময়সূচি দেখাতে কার্যকর।

2. **টেবিলের প্রধান ট্যাগগুলি কী কী?**
   - HTML টেবিলের প্রধান ট্যাগগুলি হলো `<table>`, `<tr>` (সারি), `<td>` (কোষ), এবং `<th>` (শিরোনাম)। `<thead>`, `<tbody>`, এবং `<tfoot>` ট্যাগ টেবিলের অংশগুলো সংগঠিত করতে ব্যবহৃত হয়।

3. **`<th>` এবং `<td>` ট্যাগের মধ্যে পার্থক্য কী?**
   - `<th>` ট্যাগ টেবিলের হেডারের জন্য ব্যবহৃত হয় এবং স্বয়ংক্রিয়ভাবে বোল্ড হয়, যখন `<td>` সাধারণ টেবিল ডেটার জন্য ব্যবহৃত হয়।

4. **কীভাবে কলস্প্যান (colspan) এবং রোস্প্যান (rowspan) ব্যবহার করা হয়?**
   - `colspan` একটি সেলকে একাধিক কলাম জুড়ে বিস্তৃত করতে ব্যবহার করা হয়, এবং `rowspan` একটি সেলকে একাধিক সারি জুড়ে বিস্তৃত করতে ব্যবহার করা হয়। উদাহরণ: `<td colspan="2">` দুই কলাম বিস্তৃত করবে।

5. **HTML এ টেবিলে সীমানা (border) যোগ করবেন কীভাবে?**
   - টেবিলে সীমানা যোগ করতে `border` অ্যাট্রিবিউট ব্যবহার করা হয়। উদাহরণ: `<table border="1">` টেবিলের চারপাশে এবং কোষগুলোর মধ্যে সীমানা প্রদর্শন করবে।

6. **টেবিলে `caption` ট্যাগের উদ্দেশ্য কী?**
   - `caption` ট্যাগ টেবিলের উপরে একটি শিরোনাম বা ক্যাপশন প্রদর্শন করতে ব্যবহৃত হয়, যা টেবিলের বিষয়বস্তু সম্পর্কে বোঝায়।

7. **টেবিলে `thead`, `tbody`, এবং `tfoot` ট্যাগের ভূমিকা কী?**
   - `thead` ট্যাগ টেবিলের শিরোনাম অংশকে সনাক্ত করতে ব্যবহৃত হয়, `tbody` টেবিলের মূল কন্টেন্টের জন্য, এবং `tfoot` ট্যাগ টেবিলের ফুটার অংশের জন্য ব্যবহৃত হয়। এটি বৃহৎ টেবিলের জন্য গঠনগত সুবিধা দেয়।

এই প্রশ্নগুলোর মাধ্যমে ফর্ম এবং টেবিলের মূল ধারণা সম্পর্কে ভালো জ্ঞান অর্জন করা সম্ভব।
