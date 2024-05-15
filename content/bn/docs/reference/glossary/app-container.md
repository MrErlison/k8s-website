---
title: অ্যাপ কন্টেইনার
id: app-container
date: 2019-02-12
full_link:
short_description: >
  কোনো ওয়ার্কলোডের একটি অংশ চালানোর জন্য ব্যবহৃত কন্টেইনার। init কন্টেইনারের সাথে তুলনা করুন।

aka:
tags:
- workload
---
অ্যাপ্লিকেশন কন্টেইনার (অথবা অ্যাপ কন্টেইনার) হল একটি {{< glossary_tooltip text="পড" term_id="pod" >}}-এর মধ্যে থাকা {{< glossary_tooltip text="কন্টেইনার" term_id="container" >}}গুলি, যা যেকোনো {{< glossary_tooltip text="ইনিশিয়ালাইজেশন কন্টেইনার" term_id="init-container" >}} সম্পন্ন হওয়ার পর চালু হয়।

<!--more-->

একটি ইনিট কন্টেইনার আপনাকে ইনিশিয়ালাইজেশনের বিবরণ পৃথক করতে দেয় যা সার্বিকভাবে {{< glossary_tooltip text="ওয়ার্কলোড" term_id="workload" >}} এর জন্য গুরুত্বপূর্ণ, এবং যা অ্যাপ্লিকেশন কন্টেইনার চালু হওয়ার পরে চালানোর প্রয়োজন নেই।
যদি একটি পডে কোনো ইনিট কন্টেইনার কনফিগার করা না হয়, তবে সেই পডের সব কন্টেইনারই অ্যাপ কন্টেইনার হয়।