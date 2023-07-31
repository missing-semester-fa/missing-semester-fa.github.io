---
layout: page
title: ترم گمشده تحصیلات علوم کامپیوتر شما
nositetitle: true
---

کلاس‌ها همه چیز را در مورد موضوعات پیشرفته در علوم کامپیوتر، از سیستم‌عامل گرفته تا یادگیری ماشین، به شما می‌آموزند، اما یک موضوع مهم وجود دارد که به‌ندرت پوشش داده می‌شود و در عوض به خود دانشجویان واگذار می‌شود تا خودشان آن را کسب کنند: مهارت و زبردستی در ابزارهایشان. ما به شما یاد خواهیم داد که چگونه بر خط فرمان مسلط شوید، از یک ویرایشگر متن قدرتمند استفاده کنید، از ویژگی‌های فانتزی سیستم‌های کنترل نسخه استفاده کنید، و موارد بسیار دیگر!

دانشجویان صدها ساعت را در طول دوران تحصیل خود (و هزاران ساعت را در طول حرفه خود) با به استفاده از این ابزارها می‌گذرانند، بنابراین منطقی است که این تجربه را تا حد امکان روان و بدون اصطکاک کرد. تسلط بر این ابزارها نه تنها شما را قادر می‌سازد که زمان کمتری را صرف چگونگی تطبیق ابزارهای خود با هدفتان کنید، بلکه به شما این امکان را می‌دهد که مشکلاتی را که قبلاً پیچیده و غیرممکن به نظر می‌رسیدند، حل کنید.

درباره [انگیزه پشت این کلاس](/about/) بخوانید.

{% comment %}
# Registration

Sign up for the IAP 2020 class by filling out this [registration form](https://forms.gle/TD1KnwCSV52qexVt9).
{% endcomment %}

# برنامه درسی

{% comment %}
**Lecture**: 35-225, 2pm--3pm<br>
**Office hours**: 32-G9 lounge, 3pm--4pm (every day, right after lecture)
{% endcomment %}

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d/%y' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

ویدیوهای ضبط‌شده از سخنرانی‌ها (به زبان انگلیسی) [در یوتیوب](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J) موجود است. 

# درباره کلاس

**اعضا**: این کلاس توسط [Anish](https://www.anishathalye.com/)، [Jon](https://thesquareplanet.com/) و [Jose](http://josejg.com/) به‌طور مشترک تدریس می‌شود.<br>
**سؤالات**: به نگهدارندگان مخزن اصلی از طریق [missing-semester@mit.edu](mailto:missing-semester@mit.edu) ایمیل بزنید.

# فراتر از MIT

 به امید آنکه دیگران از این منابع بهره ببرند این کلاس فراتر از MIT به اشتراک گذاشته شده است. می‌توانید پست‌ها و مباحث مربوطه را در موارد زیر پیدا کنید:

 - [Hacker News](https://news.ycombinator.com/item?id=22226380)
 - [Lobsters](https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit)
 - [/r/learnprogramming](https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/)
 - [/r/programming](https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/)
 - [Twitter](https://twitter.com/jonhoo/status/1224383452591509507)
 - [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)

{% comment %}
Some more URLs:

- https://news.ycombinator.com/item?id=27154577
- https://news.ycombinator.com/item?id=34934216
- https://www.reddit.com/r/learnprogramming/comments/nca1v3/mit_the_missing_semester_of_your_cs_education/
- https://www.reddit.com/r/compsci/comments/eyywv8/the_missing_semester_of_your_cs_education_from_mit/
- https://www.reddit.com/r/programming/comments/io7nq3/the_missing_semester_of_your_cs_education_mit/
- https://twitter.com/MIT_CSAIL/status/1349766980413263873
- https://twitter.com/MIT_CSAIL/status/1481676163491659780
- https://twitter.com/MIT_CSAIL/status/1581313961093484545
{% endcomment %}

# ترجمه‌ها

- [Chinese (Simplified)](https://missing-semester-cn.github.io/)
- [Chinese (Traditional)](https://missing-semester-zh-hant.github.io/)
- [Japanese](https://missing-semester-jp.github.io/)
- [Korean](https://missing-semester-kr.github.io/)
- [Portuguese](https://missing-semester-pt.github.io/)
- [Russian](https://missing-semester-rus.github.io/)
- [Serbian](https://netboxify.com/missing-semester/)
- [Spanish](https://missing-semester-esp.github.io/)
- [Turkish](https://missing-semester-tr.github.io/)
- [Vietnamese](https://missing-semester-vn.github.io/)
- [Arabic](https://missing-semester-ar.github.io/)
- [Italian](https://missing-semester-it.github.io/)

توجه: موارد بالا پیوندهای خارجی به ترجمه‌های عمومی هستند و توسط ما بررسی نشده‌اند.

## سپاسگزاری‌ها

از Elaine Mello، Jim Cain و [MIT Open
Learning](https://openlearning.mit.edu/) که امکان ضبط ویدیوهای سخنرانی را  فراهم کردند؛ از  Anthony Zolnik و [MIT
AeroAstro](https://aeroastro.mit.edu/) برای تجهیزات صوتی و تصویری؛ و از Brandi Adams و
[MIT EECS](https://www.eecs.mit.edu/) برای پشتیبانی این کلاس تشکر می‌کنیم.

---

<div class="small center">
<p><a href="https://github.com/missing-semester-fa/missing-semester-fa.github.io">کد منبع</a>.</p>
<p>تحت مجوز CC BY-NC-SA.</p>
<p>برای مشارکت <a href="/license/">اینجا</a> را بخوانید.</p>
</div>
