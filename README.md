# framework-css
[imagem]
breve introdução

**Texto Negrito**
*Texto Itálico*
link: http://github.com ou [GitHub](http://github.com)

###Lista
1. Item 1
  1. Sub Item 1
  2. Sub Item 2
  3. Sub Item 3
  4. Sub Item 4
2. Item 2
  * Sub Item A
  * Sub Item B
  * Sub Item C 


##Estrutura

###GRID
```
.grid-row{margin:0 -10px 10px;width: 960px;}
.grid-row:after{content:"";display:table;clear:both;}

.grid-1,
.grid-2,
.grid-3,
.grid-4,
.grid-5,
.grid-6,
.grid-7,
.grid-8,
.grid-9,
.grid-10,
.grid-11,
.grid-12 {
  display:inline;
  float:left;
  margin-left:10px;
  margin-right:10px;
}

.grid-row .grid-1 {
  width: 60px;
}

.grid-row .grid-2 {
  width: 140px;
}
.grid-row .grid-3 {
  width: 220px;
}
.grid-row .grid-4 {
  width: 300px;
}
.grid-row .grid-5 {
  width: 380px;
}
.grid-row .grid-6 {
  width: 460px;
}
.grid-row .grid-7 {
  width: 540px;
}
.grid-row .grid-8 {
  width: 620px;
}
.grid-row .grid-9 {
  width: 700px;
}
.grid-row .grid-10 {
  width: 780px;
}
.grid-row .grid-11 {
  width: 860px;
}
.grid-row .grid-12 {
  width: 940px;
}
```


##Normalização
```
html {}
body {}


article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}


audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}

audio:not([controls]) {
  display: none;
  height: 0;
}

[hidden],
template {
  display: none;
}

a {
  background-color: transparent;
}

a:active,
a:hover {
  outline: 0;
}

abbr[title] {
  border-bottom: 1px dotted;
}

b,
strong {
  font-weight: bold;
}

dfn {
  font-style: italic;
}


h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

mark {
  background: #ff0;
  color: #000;
}

small {
  font-size: 80%;
}

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sup {
  top: -0.5em;
}

sub {
  bottom: -0.25em;
}

img {
  border: 0;
}

svg:not(:root) {
  overflow: hidden;
}


figure {
  margin: 1em 40px;
}

hr {
  box-sizing: content-box;
  height: 0;
}

pre {
  overflow: auto;
}

code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}

button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}

button {
  overflow: visible;
}

button,
select {
  text-transform: none;
}

button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}

button[disabled],
html input[disabled] {
  cursor: default;
}

button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}

input {
  line-height: normal;
}

input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}

input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}

input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}

fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}

legend {
  border: 0;
  padding: 0;
}

textarea {
  overflow: auto;
}

optgroup {
  font-weight: bold;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

td,
th {
  padding: 0;
}
```