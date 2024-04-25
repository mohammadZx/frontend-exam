<div class="description-html" id="description_html-183309"><p dir="auto">ظاهر کلی برنامه بدین صورت است:</p>
<p dir="auto"><img src="https://s29.picofile.com/file/8463783334/graph.gif" alt="ظاهر برنامه" style="cursor: pointer;"></p>
<h1 dir="auto" id="پروژه-اولیه">پروژه اولیه<a class="anchorLink" href="#پروژه-اولیه" style="visibility: hidden;">🔗</a></h1>
<p dir="auto">پروژه اولیه را از
 <a href="/contest/assignments/54144/download_problem_initial_project/183309/" target="_blank">این لینک</a> 
دانلود کنید.</p>
<details class="green" dir="auto">
<summary dir="auto"> ساختار فایل‌ها </summary>
<div class="code-toolbar"><pre class="code-block language-none" dir="ltr" tabindex="0"><code data-filename="undefined" class="language-none">graph
├── public
│   ├── favicon.ico
│   └── index.html
├── src
│   ├── App.js
│   ├── Graph.js
│   ├── index.css
│   └── index.js
├── package-lock.json
└── package.json</code></pre><div class="toolbar"><div class="toolbar-item"><span>Plain text</span></div><div class="toolbar-item"><button class="copy-to-clipboard-button" type="button" data-copy-state="copy"><span>Copy</span></button></div></div></div></details>
<details class="violet" dir="auto">
<summary dir="auto"> راه اندازی پروژه</summary>
<p dir="auto">برای اجرای پروژه، باید<code dir="ltr">NodeJS</code> و <code dir="ltr">npm</code> را از قبل نصب کرده باشید.</p>
<ul dir="auto">
<li>ابتدا پروژه‌ی اولیه را دانلود و از حالت فشرده خارج کنید.</li>
<li>در پوشه‌ی <code dir="ltr">steps</code> ، دستور <code dir="ltr">npm install</code> را برای نصب نیازمندی‌ها اجرا کنید.</li>
<li>در همین پوشه، دستور <code dir="ltr">npm start</code> را برای راه‌اندازی پروژه اجرا کنید.</li>
</ul>
</details>
<h1 dir="auto" id="توضیحات">توضیحات<a class="anchorLink" href="#توضیحات" style="visibility: hidden;">🔗</a></h1>
<p dir="auto">در این سوال شما باید الگوریتم‌های <code dir="ltr">BFS</code> و <code dir="ltr">DFS</code> که را طوری تغییر دهید مسیری که این الگوریتم‌ها سرچ را انجام میدهند تا هدف نمایش داده شود.</p>
<h3 dir="auto" id="پراپرتی‌های-کامپوننت-graph:">پراپرتی‌های کامپوننت Graph:<a class="anchorLink" href="#پراپرتی‌های-کامپوننت-graph:">🔗</a></h3>
<ul dir="auto">
<li><code dir="ltr">highlightNode</code>: ایدی گره برای <em>highlight</em> کردن که برای نمایش مسیر استفاده میشود.</li>
<li><code dir="ltr">startNode</code>: ایدی گره شروع که با اولین کلیک روی گره مشخص میشود.</li>
<li><code dir="ltr">goalNode</code>: ایدی گره‌ای که برای ‌آن جستجو انجام میدهیم که با دومین کلیک روی گره مشخص میشود.</li>
<li><code dir="ltr">onNodeClick</code>: تابعی که هنگام کلیک شدن گره با ایدی ان گره صدا زده میشود.</li>
<li><code dir="ltr">graph</code>: گراف برای نمایش </li>
</ul>
<p dir="auto">اولین کلیک روی هر گرهی، گره شروع و دومین کلیک روی هر گرهی گره پایان را مشخص میکند. وقتی دکمه "Clear" کلیک شد باید این دو گره پاک شوند.</p>
<p dir="auto">زمانی که بین هر بار highlight کردن مسیر 500 میلی‌ثانیه است. بعداز کلیک شدن روی "DFS" یا "BFS" الگورتیم مربوطه از گره شروع، شروع به نمایش میشود و بعداز اینکه گره هدف را پیدا کرد یا بعداز جستجوی تمام گره‌ها به هدف نرسید، 500 میلی‌ثانیه بعد از highlight اخرین گره، از highlight خارج میشود.</p>
<h1 dir="auto" id="نکات">نکات<a class="anchorLink" href="#نکات">🔗</a></h1>
<ul dir="auto">
<li>شما تنها مجاز به اعمال تغییرات درون فایل <code dir="ltr">App.js</code>  هستید.</li>
<li>برای آشنایی بیشتر با الگوریتم <code dir="ltr">Depth-first search</code> می‌توانید به این <a href="https://en.wikipedia.org/wiki/Depth-first_search" target="_blank">لینک</a> و برای الگوریتم <code dir="ltr">Breadth-first search</code> به این <a href="https://en.wikipedia.org/wiki/Breadth-first_search" target="_blank">لینک</a> مراجعه کنید.</li>
<li>به هنگام ثبت پاسخ، فقط فایل <code dir="ltr">App.js</code> یا پروژه را با ساختار زیر ارسال کنید:<div class="code-toolbar"><pre class="code-block language-none" dir="ltr" tabindex="0"><code data-filename="undefined" class="language-none">[your-zip-file-name].zip
├── public
│   ├── favicon.ico
│   └── index.html
├── src
│   ├── App.js
│   ├── Graph.js
│   ├── index.css
│   └── index.js
├── package-lock.json
└── package.json</code></pre><div class="toolbar"><div class="toolbar-item"><span>Plain text</span></div><div class="toolbar-item"><button class="copy-to-clipboard-button" type="button" data-copy-state="copy"><span>Copy</span></button></div></div></div></li>
</ul>
<div class="ui basic modal" id="img-modal">
            <div class="image content" style="justify-content: center; align-items: center">
                <img class="image" style="max-width: 100%" src="">
            </div>
        </div></div>
