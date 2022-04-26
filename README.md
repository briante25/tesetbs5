#深碗網頁介紹
<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>程式設計-深碗(網頁)</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="0409159b-1bc7-4155-88b1-a9117471ec3d" class="page sans"><header><img class="page-cover-image" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/photo-60b4ac5a3f355.jpg" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><span class="icon">🧭</span></div><h1 class="page-title">程式設計-深碗(網頁)</h1></header><div class="page-body"><figure class="block-color-orange callout" style="white-space:pre-wrap;display:flex" id="6da90bf3-2498-4ae5-a5ee-f1fecf3d1e2f"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%">HTML是一種標記型文檔，用來標記一個文本內容意義的文檔。最外層的HTML標籤標記整個文檔的內容屬於HTML。裡面的head就是文檔的屬性，如文檔類型，文檔大小，文檔名等；body就是文檔主要內容。而後來HTML被用作網頁開發，因此head就成了描述網站屬性的標記，而body就成了網站內容的標記。</div></figure><figure id="ba0e1118-84cc-4b56-ac7c-89e6b7d44130" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled.png"><img style="width:804px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled.png"/></a></figure><pre id="2b8b80b7-5052-48ac-85f4-6c49f61f1801" class="code"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;

&lt;head&gt;
    &lt;meta charset=&quot;utf-8&quot;&gt;
    &lt;title&gt;My test page&lt;/title&gt;
    &lt;style&gt;
        
    &lt;/style&gt;
&lt;/head&gt;

&lt;body&gt;
    &lt;table style=&quot;border:3px #cccccc solid;&quot; cellpadding=&quot;10&quot; border=&#x27;1&#x27;&gt;
        &lt;tr&gt;
            &lt;th&gt;班級&lt;/th&gt;
            &lt;th&gt;學號&lt;/th&gt;
            &lt;th&gt;姓名&lt;/th&gt;
        &lt;/tr&gt;
        &lt;tr&gt;
            &lt;td&gt;一甲&lt;/td&gt;
            &lt;td&gt;410411XX&lt;/td&gt;
            &lt;td&gt;XXX&lt;/td&gt;
        &lt;/tr&gt;
    &lt;/table&gt;
&lt;/body&gt;

&lt;/html&gt;</code></pre><p id="00d8b084-117c-460c-be1b-c617c78ed844" class=""><a href="https://www.webtech.tw/info.php?tid=HTML_head_%E6%A8%99%E7%B1%A4">https://www.webtech.tw/info.php?tid=HTML_head_標籤</a></p><ul id="8bcb282a-899e-4a29-8a0b-650e1871377f" class="bulleted-list"><li style="list-style-type:disc"><code>&lt;!DOCTYPE html&gt;</code> — 文件類型（doctype）文件類型是用來連結一些應遵守的規則，有點像自動校正的功能。然而，現在大家其實不太管文件類型，它就是個必須放在程式碼中的東西，現階段大家只需要知道這點就夠了。</li></ul><ul id="1cc80d26-5290-4bf2-9ec8-563b061945ef" class="bulleted-list"><li style="list-style-type:disc"><code>&lt;html&gt;&lt;/html&gt;</code> — <code>&lt;html&gt;</code> 元素，又被視為根元素（root element），包含了所有顯示在這個頁面上的內容。</li></ul><ul id="8c3e1777-1350-4cdc-b872-5502d04ff62d" class="bulleted-list"><li style="list-style-type:disc"><code>&lt;head&gt;&lt;/head&gt;</code> — <code>&lt;head&gt;</code> 元素，裡面放的是你想涵括的重要資訊，但<strong>不會顯示於網頁瀏覽者眼前的</strong>。例如，顯示於搜尋結果的關鍵字、頁面說明<em>、</em>CSS、字元實體集...等。</li></ul><ul id="66731e1d-5826-49f0-ba76-72e520cd3dd7" class="bulleted-list"><li style="list-style-type:disc"><code>&lt;body&gt;&lt;/body&gt;</code> — <code>&lt;body&gt;</code> 元素，包含了<strong>所有會顯示於網頁瀏覽者眼前的內容。</strong> 無論是文字、圖片、影面、互動遊戲...等。</li></ul><ul id="611d9a2a-fad1-4886-9b70-8371cb71a690" class="bulleted-list"><li style="list-style-type:disc"><code>&lt;meta charset=&quot;utf-8&quot;&gt;</code> — 這個元素指定了你的文件<strong>使用utf-8字元編碼</strong>， 建議大家都要使用這個元素，它會幫助你免去許多文字無法正確呈現的煩惱。</li></ul><ul id="eb6ca687-64db-4483-b5f7-90e24dd2b0d5" class="bulleted-list"><li style="list-style-type:disc"><code>&lt;title&gt;&lt;/title&gt;</code> — 呈現於網頁瀏覽者眼前的網頁標題。<hr id="208fa747-b816-4d6f-a8c2-559fa3706009"/><h2 id="32b008c3-cec0-48c2-afaa-dd9ec4f1ec96" class="">3/10</h2><figure id="689f509f-8314-48b6-ad35-a7edf00549d2" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%201.png"><img style="width:960px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%201.png"/></a></figure><pre id="2d161223-78ef-43e0-879a-e87c15094cdd" class="code"><code>&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;

&lt;head&gt;
    &lt;meta charset=&quot;UTF-8&quot;&gt;
    &lt;meta http-equiv=&quot;X-UA-Compatible&quot; content=&quot;IE=edge&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
    &lt;title&gt;Document&lt;/title&gt;
    &lt;script&gt;
        function check() {
            if (document.form1.phone.value == &quot;&quot;) {
                alert(&quot;連絡電話,不可空白!&quot;);
                return false;
            }
            return true;
        }
    &lt;/script&gt;
&lt;/head&gt;

&lt;body&gt;
    0&lt;br&gt;1
    &lt;br&gt;2
    &lt;p&gt;A&lt;/p&gt;
    &lt;p&gt;B&lt;/p&gt;
    &lt;form name=&quot;form1&quot; action=&quot;&quot; onsubmit=&quot;return check();&quot;&gt;
        &lt;table style=&quot;margin-top:50px;&quot; border=&quot;5&quot; align=&quot;center&quot;&gt;
            &lt;tr&gt;
                &lt;td colspan=&quot;2&quot; align=&quot;center&quot;&gt;民宿預約網&lt;/td&gt;
            &lt;/tr&gt;
            &lt;tr&gt;
                &lt;td&gt;姓名&lt;/td&gt;
                &lt;td&gt;&lt;input type=&quot;text&quot; name=&quot;name&quot;&gt;&lt;/td&gt;
            &lt;/tr&gt;
            &lt;tr&gt;
                &lt;td&gt;連絡電話&lt;/td&gt;
                &lt;td&gt;&lt;input type=&quot;text&quot; name=&quot;phone&quot;&gt;&lt;/td&gt;
            &lt;/tr&gt;
            &lt;tr&gt;
                &lt;td&gt;入住日期&lt;/td&gt;
                &lt;td&gt;&lt;input type=&quot;date&quot; name=&quot;checkIn&quot;&gt;&lt;/td&gt;
            &lt;/tr&gt;
            &lt;tr&gt;
                &lt;td&gt;退房日期&lt;/td&gt;
                &lt;td&gt;&lt;input type=&quot;time&quot; name=&quot;checkOut&quot;&gt;&lt;/td&gt;
            &lt;/tr&gt;
            &lt;tr&gt;
                &lt;td&gt;&lt;input type=&quot;submit&quot; value=&quot;確認預約&quot;&gt;&lt;/td&gt;
                &lt;td&gt;&lt;/td&gt;
            &lt;/tr&gt;
        &lt;/table&gt;
    &lt;/form&gt;
&lt;/body&gt;

&lt;/html&gt;
&lt;/html&gt;</code></pre><ul id="037efa62-f953-4af9-8e5a-ca2cb7fc8be1" class="bulleted-list"><li style="list-style-type:circle"><code>&lt;form name=&quot;form1&quot; action=&quot;&quot; onsubmit=&quot;return </code><mark class="highlight-yellow"><code>check()</code></mark><code>;&quot;&gt;</code> — 藉由抓取submit回傳的功能，按下按鈕後執行回傳(type=”submit”)的動作，並且呼叫寫好的名為”check”的功能。</li></ul><hr id="fa3a16cc-67c7-4f7e-b4ef-98ae50a07ec1"/><p id="d0f4b9d3-8a55-4d01-99b4-c88219447f3a" class="">
</p></li></ul><h2 id="34b5bfa0-9f61-4f40-9d65-492636886461" class="">3/17</h2><figure id="97496874-6bcd-4bb6-897f-3aff22a81a6a" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%202.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%202.png"/></a></figure><pre id="ea8e0e61-3763-4638-b83c-f1a5d31f5357" class="code"><code>&lt;!doctype html&gt;
&lt;html lang=&quot;en&quot;&gt;

&lt;head&gt;
    &lt;title&gt;Title&lt;/title&gt;
    &lt;!-- Required meta tags --&gt;
    &lt;meta charset=&quot;utf-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1, shrink-to-fit=no&quot;&gt;

    &lt;!-- Bootstrap CSS v5.0.2 --&gt;
    &lt;!--link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css&quot; integrity=&quot;sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC&quot; crossorigin=&quot;anonymous&quot;!--&gt;
    &lt;style&gt;
        .jumbotron3 {
            padding: 8rem 8rem;
            margin-bottom: 2rem;
            background-color: #47be5b3a;
            border-radius: .5rem;
        }
    &lt;/style&gt;
&lt;/head&gt;

&lt;body&gt;
    &lt;div class=&quot;container&quot; style=&quot;margin-top:100px;&quot;&gt;
        &lt;div class=&quot;jumbotron3&quot; style=&quot;box-shadow: 5px 10px #030303af&quot;&gt;
            &lt;h1 class=&quot;display-4&quot;&gt;Hello, world!&lt;/h1&gt;
            &lt;p class=&quot;lead&quot;&gt;This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.&lt;/p&gt;
            &lt;hr class=&quot;my-4&quot;&gt;
            &lt;p&gt;It uses utility classes for typography and spacing to space content out within the larger container.&lt;/p&gt;
            &lt;a class=&quot;btn btn-primary btn-lg&quot; href=&quot;#&quot; role=&quot;button&quot;&gt;Learn more&lt;/a&gt;
        &lt;/div&gt;
    &lt;/div&gt;

    &lt;!-- Bootstrap JavaScript Libraries --&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js&quot; integrity=&quot;sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js&quot; integrity=&quot;sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
&lt;/body&gt;

&lt;/html&gt;</code></pre><ul id="abe6e831-7fda-4540-a650-26c93fc7cadf" class="bulleted-list"><li style="list-style-type:disc">bootstrap的應用，詳細內容可以到官網去查詢</li></ul><h2 id="4e2047d4-76d2-49a5-abf6-8f59a7f7845c" class="">3/24 Navbar</h2><div id="ae9d70b6-82aa-44d7-93cb-d35f650c72d9" class="column-list"><div id="af0f535e-2b8a-452a-bf2b-75e6acd001a6" style="width:50%" class="column"><figure id="dfddf8d0-0c3e-4e98-9095-2c094c23dee2" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%203.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%203.png"/></a></figure></div><div id="8beb4ee3-c140-4482-98d7-dc339fee0b9e" style="width:50%" class="column"><figure id="7df18f2b-2674-4b8c-854c-a72395b31275" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%204.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%204.png"/></a></figure></div></div><pre id="724fd3d0-ad72-4c96-9a6a-7d8064be41fd" class="code"><code>&lt;!doctype html&gt;
&lt;html lang=&quot;en&quot;&gt;

&lt;head&gt;
    &lt;title&gt;Title&lt;/title&gt;
    &lt;!-- Required meta tags --&gt;
    &lt;meta charset=&quot;utf-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1, shrink-to-fit=no&quot;&gt;

    &lt;!-- Bootstrap CSS v5.0.2 --&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css&quot; integrity=&quot;sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC&quot; crossorigin=&quot;anonymous&quot;&gt;

&lt;/head&gt;

&lt;body&gt;

    &lt;!-- Bootstrap JavaScript Libraries --&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js&quot; integrity=&quot;sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js&quot; integrity=&quot;sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;nav class=&quot;navbar navbar-expand-lg navbar-light bg-light&quot;&gt;
        &lt;div class=&quot;container-fluid&quot;&gt;
            &lt;a class=&quot;navbar-brand&quot; href=&quot;#&quot;&gt;Navbar&lt;/a&gt;
            &lt;button class=&quot;navbar-toggler&quot; type=&quot;button&quot; data-bs-toggle=&quot;collapse&quot; data-bs-target=&quot;#navbarSupportedContent&quot; aria-controls=&quot;navbarSupportedContent&quot; aria-expanded=&quot;false&quot; aria-label=&quot;Toggle navigation&quot;&gt;
            &lt;span class=&quot;navbar-toggler-icon&quot;&gt;&lt;/span&gt;
          &lt;/button&gt;
            &lt;div class=&quot;collapse navbar-collapse&quot; id=&quot;navbarSupportedContent&quot;&gt;
                &lt;ul class=&quot;navbar-nav me-auto mb-2 mb-lg-0&quot;&gt;
                    &lt;li class=&quot;nav-item&quot;&gt;
                        &lt;a class=&quot;nav-link active&quot; aria-current=&quot;page&quot; href=&quot;#&quot;&gt;首頁&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item&quot;&gt;
                        &lt;a class=&quot;nav-link&quot; href=&quot;#&quot;&gt;Link&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item dropdown&quot;&gt;
                        &lt;a class=&quot;nav-link dropdown-toggle&quot; href=&quot;#&quot; id=&quot;navbarDropdown&quot; role=&quot;button&quot; data-bs-toggle=&quot;dropdown&quot; aria-expanded=&quot;false&quot;&gt;
                  Dropdown
                &lt;/a&gt;
                        &lt;ul class=&quot;dropdown-menu&quot; aria-labelledby=&quot;navbarDropdown&quot;&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Another action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;
                                &lt;hr class=&quot;dropdown-divider&quot;&gt;
                            &lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Something else here&lt;/a&gt;&lt;/li&gt;
                        &lt;/ul&gt;
                    &lt;/li&gt;

                &lt;/ul&gt;
                &lt;form class=&quot;d-flex&quot;&gt;

                    &lt;button data-bs-toggle=&quot;modal&quot; data-bs-target=&quot;#exampleModal&quot; class=&quot;btn btn-outline-success&quot; type=&quot;button&quot;&gt;登入&lt;/button&gt;
                &lt;/form&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/nav&gt;

    &lt;!-- Modal --&gt;
    &lt;div class=&quot;modal fade&quot; id=&quot;exampleModal&quot; tabindex=&quot;-1&quot; aria-labelledby=&quot;exampleModalLabel&quot; aria-hidden=&quot;true&quot;&gt;
        &lt;div class=&quot;modal-dialog&quot;&gt;
            &lt;div class=&quot;modal-content&quot;&gt;
                &lt;div class=&quot;modal-header&quot;&gt;
                    &lt;h5 class=&quot;modal-title mx-auto&quot; id=&quot;exampleModalLabel&quot;&gt;會員帳號登入&lt;/h5&gt;

                &lt;/div&gt;
                &lt;div class=&quot;modal-body&quot;&gt;
                    &lt;form&gt;
                        &lt;div class=&quot;mb-3&quot;&gt;
                            &lt;label for=&quot;exampleInputEmail1&quot; class=&quot;form-label&quot;&gt;帳號&lt;/label&gt;
                            &lt;input type=&quot;email&quot; class=&quot;form-control&quot; id=&quot;exampleInputEmail1&quot; aria-describedby=&quot;emailHelp&quot;&gt;

                        &lt;/div&gt;
                        &lt;div class=&quot;mb-3&quot;&gt;
                            &lt;label for=&quot;exampleInputPassword1&quot; class=&quot;form-label&quot;&gt;密碼&lt;/label&gt;
                            &lt;input type=&quot;password&quot; class=&quot;form-control&quot; id=&quot;exampleInputPassword1&quot;&gt;
                        &lt;/div&gt;
                        &lt;div class=&quot;mb-3 form-check&quot;&gt;
                            &lt;input type=&quot;checkbox&quot; class=&quot;form-check-input&quot; id=&quot;exampleCheck1&quot;&gt;
                            &lt;label class=&quot;form-check-label&quot; for=&quot;exampleCheck1&quot;&gt;記住我&lt;/label&gt;
                        &lt;/div&gt;

                        &lt;div class=&quot;text-center&quot;&gt;
                            &lt;button type=&quot;submit&quot; class=&quot;btn btn-primary&quot;&gt;登入&lt;/button&gt;
                            &lt;button type=&quot;button&quot; class=&quot;btn btn-secondary&quot; data-bs-dismiss=&quot;modal&quot;&gt;關閉&lt;/button&gt;
                        &lt;/div&gt;
                    &lt;/form&gt;
                &lt;/div&gt;

            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/div&gt;
&lt;/body&gt;

&lt;/html&gt;</code></pre><ul id="05bfdf80-9fd7-4705-a949-4df5fd3bb75e" class="bulleted-list"><li style="list-style-type:disc">如何觸發按鈕，並呼叫另一個浮動視窗</li></ul><hr id="33c015c6-f9f0-4b09-847d-ede909a1682f"/><figure id="42e3a27d-9ce4-4563-8c78-4c69308706d6" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%205.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%205.png"/></a></figure><h2 id="b9521dea-6ccb-44d4-b31f-2b6406c9c566" class="">3/31 Carousel</h2><p id="a36c6113-afc7-4665-82f9-14a24dd63003" class=""><a href="https://stackoverflow.com/questions/30538967/how-to-center-image-in-carousel">https://stackoverflow.com/questions/30538967/how-to-center-image-in-carousel</a></p><figure id="0920051d-8be4-4d0e-a7ca-0343fb208cdf" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%206.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%206.png"/></a></figure><pre id="c16800ef-d0ad-4e3a-b752-68fb20a3aa65" class="code"><code>&lt;!doctype html&gt;
&lt;html lang=&quot;en&quot;&gt;

&lt;head&gt;
    &lt;title&gt;Title&lt;/title&gt;
    &lt;!-- Required meta tags --&gt;
    &lt;meta charset=&quot;utf-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1, shrink-to-fit=no&quot;&gt;

    &lt;!-- Bootstrap CSS v5.0.2 --&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css&quot; integrity=&quot;sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC&quot; crossorigin=&quot;anonymous&quot;&gt;
    &lt;style&gt;
        .carousel-item img {
            margin: auto;
        }
    &lt;/style&gt;
&lt;/head&gt;

&lt;body&gt;

    &lt;!-- Bootstrap JavaScript Libraries --&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js&quot; integrity=&quot;sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js&quot; integrity=&quot;sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;nav class=&quot;navbar navbar-expand-lg navbar-dark bg-danger &quot;&gt;
        &lt;div class=&quot;container-fluid &quot;&gt;
            &lt;a class=&quot; navbar-brand &quot; href=&quot;# &quot;&gt;Navbar&lt;/a&gt;
            &lt;button class=&quot;navbar-toggler &quot; type=&quot;button &quot; data-bs-toggle=&quot;collapse &quot; data-bs-target=&quot;#navbarSupportedContent &quot; aria-controls=&quot;navbarSupportedContent &quot; aria-expanded=&quot;false &quot; aria-label=&quot;Toggle navigation &quot;&gt;
                &lt;span class=&quot;navbar-toggler-icon &quot;&gt;&lt;/span&gt;
            &lt;/button&gt;
            &lt;div class=&quot;collapse navbar-collapse &quot; id=&quot;navbarSupportedContent &quot;&gt;
                &lt;ul class=&quot;navbar-nav me-auto mb-2 mb-lg-0 &quot;&gt;
                    &lt;li class=&quot;nav-item &quot;&gt;
                        &lt;a class=&quot;nav-link active &quot; aria-current=&quot;page &quot; href=&quot;# &quot;&gt;首頁&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item &quot;&gt;
                        &lt;a class=&quot;nav-link &quot; href=&quot;# &quot;&gt;Link&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item dropdown &quot;&gt;
                        &lt;a class=&quot;nav-link dropdown-toggle &quot; href=&quot;# &quot; id=&quot;navbarDropdown &quot; role=&quot;button &quot; data-bs-toggle=&quot;dropdown &quot; aria-expanded=&quot;false &quot;&gt;
                            Dropdown
                        &lt;/a&gt;
                        &lt;ul class=&quot;dropdown-menu &quot; aria-labelledby=&quot;navbarDropdown &quot;&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item &quot; href=&quot;# &quot;&gt;Action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item &quot; href=&quot;# &quot;&gt;Another action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;
                                &lt;hr class=&quot;dropdown-divider &quot;&gt;
                            &lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item &quot; href=&quot;# &quot;&gt;Something else here&lt;/a&gt;&lt;/li&gt;
                        &lt;/ul&gt;
                    &lt;/li&gt;

                &lt;/ul&gt;
                &lt;form class=&quot;d-flex &quot;&gt;

                    &lt;button data-bs-toggle=&quot;modal &quot; data-bs-target=&quot;#exampleModal &quot; class=&quot;btn btn-outline-success &quot; type=&quot;button &quot;&gt;登入&lt;/button&gt;
                &lt;/form&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/nav&gt;

    &lt;div id=&quot;carouselExampleCaptions&quot; class=&quot;carousel slide&quot; data-bs-ride=&quot;carousel&quot;&gt;
        &lt;div class=&quot;carousel-indicators&quot;&gt;
            &lt;button type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide-to=&quot;0&quot; class=&quot;active&quot; aria-current=&quot;true&quot; aria-label=&quot;Slide 1&quot;&gt;&lt;/button&gt;
            &lt;button type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide-to=&quot;1&quot; aria-label=&quot;Slide 2&quot;&gt;&lt;/button&gt;
            &lt;button type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide-to=&quot;2&quot; aria-label=&quot;Slide 3&quot;&gt;&lt;/button&gt;
        &lt;/div&gt;
        &lt;div class=&quot;carousel-inner&quot;&gt;
            &lt;div class=&quot;carousel-item active&quot;&gt;
                &lt;img src=&quot;image/P1.png&quot; class=&quot;d-block w-50&quot; alt=&quot;...&quot;&gt;
                &lt;div class=&quot;carousel-caption d-none d-md-block&quot;&gt;
                    &lt;h5&gt;First slide label&lt;/h5&gt;
                    &lt;p&gt;Some representative placeholder content for the first slide.&lt;/p&gt;
                &lt;/div&gt;
            &lt;/div&gt;
            &lt;div class=&quot;carousel-item&quot;&gt;
                &lt;img src=&quot;image/P2.png&quot; class=&quot;d-block w-50&quot; alt=&quot;...&quot;&gt;
                &lt;div class=&quot;carousel-caption d-none d-md-block&quot;&gt;
                    &lt;h5&gt;Second slide label&lt;/h5&gt;
                    &lt;p&gt;Some representative placeholder content for the second slide.&lt;/p&gt;
                &lt;/div&gt;
            &lt;/div&gt;
            &lt;div class=&quot;carousel-item&quot;&gt;
                &lt;img src=&quot;image/P3.jpg&quot; class=&quot;d-block w-50&quot; alt=&quot;...&quot;&gt;
                &lt;div class=&quot;carousel-caption d-none d-md-block&quot;&gt;
                    &lt;h5&gt;Third slide label&lt;/h5&gt;
                    &lt;p&gt;Some representative placeholder content for the third slide.&lt;/p&gt;
                &lt;/div&gt;
            &lt;/div&gt;
        &lt;/div&gt;
        &lt;button class=&quot;carousel-control-prev&quot; type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide=&quot;prev&quot;&gt;
            &lt;span class=&quot;carousel-control-prev-icon&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
            &lt;span class=&quot;visually-hidden&quot;&gt;Previous&lt;/span&gt;
        &lt;/button&gt;
        &lt;button class=&quot;carousel-control-next&quot; type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide=&quot;next&quot;&gt;
            &lt;span class=&quot;carousel-control-next-icon&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
            &lt;span class=&quot;visually-hidden&quot;&gt;Next&lt;/span&gt;
        &lt;/button&gt;
    &lt;/div&gt;
    &lt;!-- Modal --&gt;
    &lt;div class=&quot;modal fade &quot; id=&quot;exampleModal &quot; tabindex=&quot;-1 &quot; aria-labelledby=&quot;exampleModalLabel &quot; aria-hidden=&quot;true &quot;&gt;
        &lt;div class=&quot;modal-dialog &quot;&gt;
            &lt;div class=&quot;modal-content &quot;&gt;
                &lt;div class=&quot;modal-header &quot;&gt;
                    &lt;h5 class=&quot;modal-title mx-auto &quot; id=&quot;exampleModalLabel &quot;&gt;會員帳號登入&lt;/h5&gt;

                &lt;/div&gt;
                &lt;div class=&quot;modal-body &quot;&gt;
                    &lt;form&gt;
                        &lt;div class=&quot;mb-3 &quot;&gt;
                            &lt;label for=&quot;exampleInputEmail1 &quot; class=&quot;form-label &quot;&gt;帳號&lt;/label&gt;
                            &lt;input type=&quot;email &quot; class=&quot;form-control &quot; id=&quot;exampleInputEmail1 &quot; aria-describedby=&quot;emailHelp &quot;&gt;

                        &lt;/div&gt;
                        &lt;div class=&quot;mb-3 &quot;&gt;
                            &lt;label for=&quot;exampleInputPassword1 &quot; class=&quot;form-label &quot;&gt;密碼&lt;/label&gt;
                            &lt;input type=&quot;password &quot; class=&quot;form-control &quot; id=&quot;exampleInputPassword1 &quot;&gt;
                        &lt;/div&gt;
                        &lt;div class=&quot;mb-3 form-check &quot;&gt;
                            &lt;input type=&quot;checkbox &quot; class=&quot;form-check-input &quot; id=&quot;exampleCheck1 &quot;&gt;
                            &lt;label class=&quot;form-check-label &quot; for=&quot;exampleCheck1 &quot;&gt;記住我&lt;/label&gt;
                        &lt;/div&gt;

                        &lt;div class=&quot;text-center &quot;&gt;
                            &lt;button type=&quot;submit &quot; class=&quot;btn btn-primary &quot;&gt;登入&lt;/button&gt;
                            &lt;button type=&quot;button &quot; class=&quot;btn btn-secondary &quot; data-bs-dismiss=&quot;modal &quot;&gt;關閉&lt;/button&gt;
                        &lt;/div&gt;
                    &lt;/form&gt;
                &lt;/div&gt;

            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/div&gt;

&lt;/body&gt;

&lt;/html&gt;</code></pre><h2 id="4596a1b6-3119-44cb-b511-0a393418be29" class="">4/7-14 Bootstrap youtube <strong>Embeds responsive </strong><a href="https://getbootstrap.com/docs/4.0/utilities/embed/"><strong>(官網連結)</strong></a></h2><h3 id="fd704d87-3407-4bd5-98d3-bbc5b692b966" class="">首頁</h3><pre id="4729890e-ca02-4623-964a-17bb5af77603" class="code"><code>&lt;!doctype html&gt;
&lt;html lang=&quot;en&quot;&gt;

&lt;head&gt;
    &lt;title&gt;Title&lt;/title&gt;
    &lt;!-- Required meta tags --&gt;
    &lt;meta charset=&quot;utf-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1, shrink-to-fit=no&quot;&gt;

    &lt;!-- Bootstrap CSS v5.0.2 --&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css&quot; integrity=&quot;sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC&quot; crossorigin=&quot;anonymous&quot;&gt;
    &lt;style&gt;
        .carousel-item img {
            margin: auto;
        }
    &lt;/style&gt;

&lt;/head&gt;

&lt;body&gt;

    &lt;!-- Bootstrap JavaScript Libraries --&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js&quot; integrity=&quot;sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js&quot; integrity=&quot;sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;nav class=&quot;navbar navbar-expand-md navbar-dark bg-dark fixed-top&quot;&gt;
        &lt;div class=&quot;container-fluid&quot;&gt;
            &lt;a class=&quot;navbar-brand&quot; href=&quot;#&quot;&gt;NavBar&lt;/a&gt;
            &lt;button class=&quot;navbar-toggler&quot; type=&quot;button&quot; data-bs-toggle=&quot;collapse&quot; data-bs-target=&quot;#navbarSupportedContent&quot; aria-controls=&quot;navbarSupportedContent&quot; aria-expanded=&quot;false&quot; aria-label=&quot;Toggle navigation&quot;&gt;
                &lt;span class=&quot;navbar-toggler-icon&quot;&gt;&lt;/span&gt;
            &lt;/button&gt;

            &lt;div class=&quot;collapse navbar-collapse&quot; id=&quot;navbarSupportedContent&quot;&gt;
                &lt;ul class=&quot;navbar-nav me-auto mb-2 mb-lg-0&quot;&gt;
                    &lt;li class=&quot;nav-item&quot;&gt;
                        &lt;a class=&quot;nav-link active&quot; aria-current=&quot;page&quot; href=&quot;index.html&quot;&gt;Home&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item&quot;&gt;
                        &lt;a class=&quot;nav-link&quot; href=&quot;product.html&quot;&gt;商品介紹&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item dropdown&quot;&gt;
                        &lt;a class=&quot;nav-link dropdown-toggle&quot; href=&quot;#&quot; id=&quot;navbarDropdown&quot; role=&quot;button&quot; data-bs-toggle=&quot;dropdown&quot; aria-expanded=&quot;false&quot;&gt;
                            Dropdown
                        &lt;/a&gt;
                        &lt;ul class=&quot;dropdown-menu&quot; aria-labelledby=&quot;navbarDropdown&quot;&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Another action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;
                                &lt;hr class=&quot;dropdown-divider&quot;&gt;
                            &lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Something else here&lt;/a&gt;&lt;/li&gt;
                        &lt;/ul&gt;
                    &lt;/li&gt;

                &lt;/ul&gt;
                &lt;form class=&quot;d-flex&quot;&gt;
                    &lt;button class=&quot;btn btn-outline-success&quot; type=&quot;button&quot; data-bs-toggle=&quot;modal&quot; data-bs-target=&quot;#exampleModal&quot;&gt;LogIn&lt;/button&gt;
                &lt;/form&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/nav&gt;

    &lt;!-- Modal --&gt;
    &lt;div class=&quot;modal fade&quot; id=&quot;exampleModal&quot; tabindex=&quot;-1&quot; aria-labelledby=&quot;exampleModalLabel&quot; aria-hidden=&quot;true&quot; style=&quot;margin:auto;&quot;&gt;
        &lt;div class=&quot;modal-dialog&quot;&gt;
            &lt;div class=&quot;modal-content&quot;&gt;
                &lt;div class=&quot;modal-header&quot;&gt;
                    &lt;h5 class=&quot;modal-title mx=-auto&quot; id=&quot;exampleModalLabel&quot;&gt;帳號登入&lt;/h5&gt;
                    &lt;button type=&quot;button&quot; class=&quot;btn-close&quot; data-bs-dismiss=&quot;modal&quot; aria-label=&quot;Close&quot;&gt;&lt;/button&gt;
                &lt;/div&gt;
                &lt;form&gt;
                    &lt;div class=&quot;mb-3&quot;&gt;
                        &lt;label for=&quot;exampleInputEmail1&quot; class=&quot;form-label&quot;&gt;帳號&lt;/label&gt;
                        &lt;input type=&quot;email&quot; class=&quot;form-control&quot; id=&quot;exampleInputEmail1&quot; aria-describedby=&quot;emailHelp&quot;&gt;
                        &lt;div id=&quot;emailHelp&quot; class=&quot;form-text&quot;&gt;We&#x27;ll &quot;never&quot; share your email with anyone else.&lt;/div&gt;
                    &lt;/div&gt;
                    &lt;div class=&quot;mb-3&quot;&gt;
                        &lt;label for=&quot;exampleInputPassword1&quot; class=&quot;form-label&quot;&gt;密碼&lt;/label&gt;
                        &lt;input type=&quot;password&quot; class=&quot;form-control&quot; id=&quot;exampleInputPassword1&quot;&gt;
                    &lt;/div&gt;
                    &lt;div class=&quot;mb-3 form-check&quot;&gt;
                        &lt;input type=&quot;checkbox&quot; class=&quot;form-check-input&quot; id=&quot;exampleCheck1&quot;&gt;
                        &lt;label class=&quot;form-check-label&quot; for=&quot;exampleCheck1&quot;&gt;記憶&lt;/label&gt;
                    &lt;/div&gt;
                    &lt;div class=&quot;text-center&quot;&gt;
                        &lt;button type=&quot;submit&quot; class=&quot;btn btn-primary&quot;&gt;認證&lt;/button&gt;
                        &lt;button type=&quot;button&quot; class=&quot;btn btn-secondary&quot; data-bs-dismiss=&quot;modal&quot;&gt;Close&lt;/button&gt;
                    &lt;/div&gt;
                &lt;/form&gt;
                &lt;div class=&quot;modal-footer&quot;&gt;

                &lt;/div&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/div&gt;

    &lt;div id=&quot;carouselExampleCaptions&quot; class=&quot;carousel slide&quot; data-bs-ride=&quot;carousel&quot;&gt;
        &lt;div class=&quot;carousel-indicators&quot;&gt;
            &lt;button type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide-to=&quot;0&quot; class=&quot;active&quot; aria-current=&quot;true&quot; aria-label=&quot;Slide 1&quot;&gt;&lt;/button&gt;
            &lt;button type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide-to=&quot;1&quot; aria-label=&quot;Slide 2&quot;&gt;&lt;/button&gt;
            &lt;button type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide-to=&quot;2&quot; aria-label=&quot;Slide 3&quot;&gt;&lt;/button&gt;
        &lt;/div&gt;
        &lt;div class=&quot;carousel-inner&quot;&gt;
            &lt;div class=&quot;carousel-item active&quot;&gt;
                &lt;img src=&quot;image/P1.png&quot; class=&quot;d-block w-70&quot; alt=&quot;...&quot;&gt;
                &lt;div class=&quot;carousel-caption d-none d-md-block&quot;&gt;
                    &lt;h5&gt;First slide label&lt;/h5&gt;
                    &lt;p&gt;Some representative placeholder content for the first slide.&lt;/p&gt;
                &lt;/div&gt;
            &lt;/div&gt;
            &lt;div class=&quot;carousel-item&quot;&gt;
                &lt;img src=&quot;image/P2.png&quot; class=&quot;d-block w-70&quot; alt=&quot;...&quot;&gt;
                &lt;div class=&quot;carousel-caption d-none d-md-block&quot;&gt;
                    &lt;h5&gt;Second slide label&lt;/h5&gt;
                    &lt;p&gt;Some representative placeholder content for the second slide.&lt;/p&gt;
                &lt;/div&gt;
            &lt;/div&gt;
            &lt;div class=&quot;carousel-item&quot;&gt;
                &lt;img src=&quot;image/P3.jpg&quot; class=&quot;d-block w-70&quot; alt=&quot;...&quot;&gt;
                &lt;div class=&quot;carousel-caption d-none d-md-block&quot;&gt;
                    &lt;h5&gt;Third slide label&lt;/h5&gt;
                    &lt;p&gt;Some representative placeholder content for the third slide.&lt;/p&gt;
                &lt;/div&gt;
            &lt;/div&gt;
        &lt;/div&gt;
        &lt;button class=&quot;carousel-control-prev&quot; type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide=&quot;prev&quot;&gt;
            &lt;span class=&quot;carousel-control-prev-icon&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
            &lt;span class=&quot;visually-hidden&quot;&gt;Previous&lt;/span&gt;
        &lt;/button&gt;
        &lt;button class=&quot;carousel-control-next&quot; type=&quot;button&quot; data-bs-target=&quot;#carouselExampleCaptions&quot; data-bs-slide=&quot;next&quot;&gt;
            &lt;span class=&quot;carousel-control-next-icon&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
            &lt;span class=&quot;visually-hidden&quot;&gt;Next&lt;/span&gt;
        &lt;/button&gt;
    &lt;/div&gt;
    &lt;div class=&quot;container&quot;&gt;
        &lt;div class=&quot;row&quot;&gt;
            &lt;h1 class=&quot;text-center my-5&quot;&gt;最新上傳影片&lt;/h1&gt;
            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;!--總長度12 每種不同框架長度為6/12、4/12...等--&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;
        &lt;/div&gt;

        &lt;div class=&quot;row&quot;&gt;
            &lt;h1 class=&quot;text-center my-5&quot;&gt;最熱門上傳影片&lt;/h1&gt;
            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;embed-responsive embed-responsive-16by9&quot;&gt;
                    &lt;iframe class=&quot;embed-responsive-item&quot; src=&quot;https://www.youtube.com/embed/Ti_VHbuyTAs&quot; allowfullscreen&gt;&lt;/iframe&gt;
                &lt;/div&gt;
            &lt;/div&gt;
        &lt;/div&gt;

    &lt;/div&gt;

    &lt;div class=&quot;footer&quot;&gt;
        &lt;p class=&quot;bg-danger text-white text-center p-1 fixed-bottom&quot;&gt;版權宣告，翻印必究&lt;/p&gt;
    &lt;/div&gt;

&lt;/html&gt;</code></pre><h3 id="3ebaf570-7a58-44c6-87fe-8b30df048187" class="">分頁1</h3><pre id="8d885f4d-bae4-4975-acee-225e43a7d3f7" class="code"><code>&lt;!doctype html&gt;
&lt;html lang=&quot;en&quot;&gt;

&lt;head&gt;
    &lt;title&gt;Title&lt;/title&gt;
    &lt;!-- Required meta tags --&gt;
    &lt;meta charset=&quot;utf-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1, shrink-to-fit=no&quot;&gt;

    &lt;!-- Bootstrap CSS v5.0.2 --&gt;
    &lt;link rel=&quot;stylesheet&quot; href=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css&quot; integrity=&quot;sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC&quot; crossorigin=&quot;anonymous&quot;&gt;
    &lt;style&gt;
        .carousel-item img {
            margin: auto;
        }
    &lt;/style&gt;

&lt;/head&gt;

&lt;body&gt;

    &lt;!-- Bootstrap JavaScript Libraries --&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js&quot; integrity=&quot;sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js&quot; integrity=&quot;sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF&quot; crossorigin=&quot;anonymous&quot;&gt;&lt;/script&gt;
    &lt;nav class=&quot;navbar navbar-expand-md navbar-dark bg-dark fixed-top&quot;&gt;
        &lt;div class=&quot;container-fluid&quot;&gt;
            &lt;a class=&quot;navbar-brand&quot; href=&quot;#&quot;&gt;NavBar&lt;/a&gt;
            &lt;button class=&quot;navbar-toggler&quot; type=&quot;button&quot; data-bs-toggle=&quot;collapse&quot; data-bs-target=&quot;#navbarSupportedContent&quot; aria-controls=&quot;navbarSupportedContent&quot; aria-expanded=&quot;false&quot; aria-label=&quot;Toggle navigation&quot;&gt;
                &lt;span class=&quot;navbar-toggler-icon&quot;&gt;&lt;/span&gt;
            &lt;/button&gt;

            &lt;div class=&quot;collapse navbar-collapse&quot; id=&quot;navbarSupportedContent&quot;&gt;
                &lt;ul class=&quot;navbar-nav me-auto mb-2 mb-lg-0&quot;&gt;
                    &lt;li class=&quot;nav-item&quot;&gt;
                        &lt;a class=&quot;nav-link active&quot; aria-current=&quot;page&quot; href=&quot;index.html&quot;&gt;Home&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item&quot;&gt;
                        &lt;a class=&quot;nav-link&quot; href=&quot;product.html&quot;&gt;商品介紹&lt;/a&gt;
                    &lt;/li&gt;
                    &lt;li class=&quot;nav-item dropdown&quot;&gt;
                        &lt;a class=&quot;nav-link dropdown-toggle&quot; href=&quot;#&quot; id=&quot;navbarDropdown&quot; role=&quot;button&quot; data-bs-toggle=&quot;dropdown&quot; aria-expanded=&quot;false&quot;&gt;
                            Dropdown
                        &lt;/a&gt;
                        &lt;ul class=&quot;dropdown-menu&quot; aria-labelledby=&quot;navbarDropdown&quot;&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Another action&lt;/a&gt;&lt;/li&gt;
                            &lt;li&gt;
                                &lt;hr class=&quot;dropdown-divider&quot;&gt;
                            &lt;/li&gt;
                            &lt;li&gt;&lt;a class=&quot;dropdown-item&quot; href=&quot;#&quot;&gt;Something else here&lt;/a&gt;&lt;/li&gt;
                        &lt;/ul&gt;
                    &lt;/li&gt;

                &lt;/ul&gt;
                &lt;form class=&quot;d-flex&quot;&gt;
                    &lt;button class=&quot;btn btn-outline-success&quot; type=&quot;button&quot; data-bs-toggle=&quot;modal&quot; data-bs-target=&quot;#exampleModal&quot;&gt;LogIn&lt;/button&gt;
                &lt;/form&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/nav&gt;

    &lt;!-- Modal --&gt;
    &lt;div class=&quot;modal fade&quot; id=&quot;exampleModal&quot; tabindex=&quot;-1&quot; aria-labelledby=&quot;exampleModalLabel&quot; aria-hidden=&quot;true&quot; style=&quot;margin:auto;&quot;&gt;
        &lt;div class=&quot;modal-dialog&quot;&gt;
            &lt;div class=&quot;modal-content&quot;&gt;
                &lt;div class=&quot;modal-header&quot;&gt;
                    &lt;h5 class=&quot;modal-title mx=-auto&quot; id=&quot;exampleModalLabel&quot;&gt;帳號登入&lt;/h5&gt;
                    &lt;button type=&quot;button&quot; class=&quot;btn-close&quot; data-bs-dismiss=&quot;modal&quot; aria-label=&quot;Close&quot;&gt;&lt;/button&gt;
                &lt;/div&gt;
                &lt;form&gt;
                    &lt;div class=&quot;mb-3&quot;&gt;
                        &lt;label for=&quot;exampleInputEmail1&quot; class=&quot;form-label&quot;&gt;帳號&lt;/label&gt;
                        &lt;input type=&quot;email&quot; class=&quot;form-control&quot; id=&quot;exampleInputEmail1&quot; aria-describedby=&quot;emailHelp&quot;&gt;
                        &lt;div id=&quot;emailHelp&quot; class=&quot;form-text&quot;&gt;We&#x27;ll &quot;never&quot; share your email with anyone else.&lt;/div&gt;
                    &lt;/div&gt;
                    &lt;div class=&quot;mb-3&quot;&gt;
                        &lt;label for=&quot;exampleInputPassword1&quot; class=&quot;form-label&quot;&gt;密碼&lt;/label&gt;
                        &lt;input type=&quot;password&quot; class=&quot;form-control&quot; id=&quot;exampleInputPassword1&quot;&gt;
                    &lt;/div&gt;
                    &lt;div class=&quot;mb-3 form-check&quot;&gt;
                        &lt;input type=&quot;checkbox&quot; class=&quot;form-check-input&quot; id=&quot;exampleCheck1&quot;&gt;
                        &lt;label class=&quot;form-check-label&quot; for=&quot;exampleCheck1&quot;&gt;記憶&lt;/label&gt;
                    &lt;/div&gt;
                    &lt;div class=&quot;text-center&quot;&gt;
                        &lt;button type=&quot;submit&quot; class=&quot;btn btn-primary&quot;&gt;認證&lt;/button&gt;
                        &lt;button type=&quot;button&quot; class=&quot;btn btn-secondary&quot; data-bs-dismiss=&quot;modal&quot;&gt;Close&lt;/button&gt;
                    &lt;/div&gt;
                &lt;/form&gt;
                &lt;div class=&quot;modal-footer&quot;&gt;

                &lt;/div&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/div&gt;

    &lt;div class=&quot;container&quot;&gt;
        &lt;div class=&quot;row&quot;&gt;
            &lt;h1 class=&quot;text-center my-5&quot;&gt;最新上傳影片&lt;/h1&gt;
            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;card&quot; style=&quot;width: 18rem;&quot;&gt;
                    &lt;img src=&quot;http://fakeimg.pl/440x300/#ececec/#fff/?text=PJCHENder&quot; class=&quot;card-img-top&quot; alt=&quot;...&quot;&gt;
                    &lt;div class=&quot;card-body&quot;&gt;
                        &lt;h5 class=&quot;card-title&quot;&gt;商品標題&lt;/h5&gt;
                        &lt;p class=&quot;card-text&quot;&gt;商品規格與特色介紹&lt;/p&gt;
                        &lt;a href=&quot;#&quot; class=&quot;btn btn-primary&quot;&gt;GOGO!&lt;/a&gt;
                    &lt;/div&gt;
                &lt;/div&gt;

            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;card&quot; style=&quot;width: 18rem;&quot;&gt;
                    &lt;img src=&quot;http://fakeimg.pl/440x300/#ececec/#fff/?text=PJCHENder&quot; class=&quot;card-img-top&quot; alt=&quot;...&quot;&gt;
                    &lt;div class=&quot;card-body&quot;&gt;
                        &lt;h5 class=&quot;card-title&quot;&gt;商品標題&lt;/h5&gt;
                        &lt;p class=&quot;card-text&quot;&gt;商品規格與特色介紹&lt;/p&gt;
                        &lt;a href=&quot;#&quot; class=&quot;btn btn-primary&quot;&gt;GOGO!&lt;/a&gt;
                    &lt;/div&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;div class=&quot;col-sm-12 col-md-6 col-lg-4 mb-5&quot;&gt;
                &lt;div class=&quot;card&quot; style=&quot;width: 18rem;&quot;&gt;
                    &lt;img src=&quot;http://fakeimg.pl/440x300/#ececec/#fff/?text=PJCHENder&quot; class=&quot;card-img-top&quot; alt=&quot;...&quot;&gt;
                    &lt;div class=&quot;card-body&quot;&gt;
                        &lt;h5 class=&quot;card-title&quot;&gt;商品標題&lt;/h5&gt;
                        &lt;p class=&quot;card-text&quot;&gt;商品規格與特色介紹&lt;/p&gt;
                        &lt;a href=&quot;#&quot; class=&quot;btn btn-primary&quot;&gt;GOGO!&lt;/a&gt;
                    &lt;/div&gt;
                &lt;/div&gt;

            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;footer&quot;&gt;
        &lt;p class=&quot;bg-danger text-white text-center p-1 fixed-bottom&quot;&gt;版權宣告，翻印必究&lt;/p&gt;
    &lt;/div&gt;

&lt;/html&gt;</code></pre><figure id="08434a5c-d5fb-4c79-95a4-1923a68c58cf" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%207.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%207.png"/></a></figure><figure id="ecf7b59f-625b-4db5-85d6-f6d454cf8a92" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%208.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%208.png"/></a></figure><figure id="1bf11b29-5bae-476f-b89b-8e626b6d6b4d" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%209.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%209.png"/></a></figure><p id="4aadf02b-edca-478d-be86-084a7a36a858" class="">lg是螢幕目前最大的規格，即便沒有定義也會有。<a href="https://getbootstrap.com/docs/5.0/components/modal/#embedding-youtube-videos">https://getbootstrap.com/docs/5.0/components/modal/#embedding-youtube-videos</a></p><p id="4d5fe4a5-2af8-4616-9387-116c7378711b" class="">
</p><h2 id="6bab12e9-f9e6-41c7-9f4b-72f11c61a785" class="">Github教學</h2><figure id="b0e77232-8a07-45fc-a029-5d0844af9ff9" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2010.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2010.png"/></a></figure><figure id="a17cb59d-cf55-4564-88ea-d784f4bf5d75" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2011.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2011.png"/></a></figure><figure id="3d4e69bf-d2e4-4b01-afe0-05185666d9ac" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2012.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2012.png"/></a></figure><figure id="9e98664f-0904-43d2-9765-65b2b83ff022" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2013.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2013.png"/></a></figure><figure id="55ca3d43-5254-44dd-839f-399f1c17929c" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2014.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2014.png"/></a></figure><figure id="93c94a61-50a1-405d-bf4e-e3d0c7a819d4" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2015.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2015.png"/></a></figure><figure id="20aed2e6-65b4-464f-9afe-fa1d09ea79f8" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2016.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2016.png"/></a></figure><figure id="2e998720-9e82-4804-92db-b7d68f601fdd" class="image"><a href="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2017.png"><img style="width:1920px" src="%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88-%E6%B7%B1%E7%A2%97(%E7%B6%B2%E9%A0%81)%20ba0e111884cc4b56ac7c89e6b7d44130/Untitled%2017.png"/></a></figure><h3 id="f0a4c232-7ba9-4307-86ae-89862739600a" class="">接著save檔案，等待網站跑完就好了。</h3></div></article></body></html>
