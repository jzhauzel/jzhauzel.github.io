<!DOCTYPE html>
<!-- saved from url=(0054)file:///C:/Users/PC/Downloads/Final+Project%20(1).html -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Final Project</title><script src="./Final Project_files/require.min.js.download"></script>
<script src="./Final Project_files/jquery.min.js.download"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
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
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
[dir="rtl"] #ipython_notebook {
  float: right !important;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
[dir="rtl"] #tabs li {
  float: right;
}
ul#tabs {
  margin-bottom: 4px;
}
[dir="rtl"] ul#tabs {
  margin-right: 0px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons {
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-right {
  padding-top: 1px;
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-left {
  float: right !important;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
[dir="rtl"] #tree-selector a {
  float: right;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
[dir="rtl"] #new-menu {
  text-align: right;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
[dir="rtl"] #running .col-sm-8 {
  float: right !important;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}

@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="file:///C:/Users/PC/Downloads/custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="./Final Project_files/MathJax.js.download" id=""></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config;executed=true">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --><style type="text/css">.MathJax_Hover_Frame {border-radius: .25em; -webkit-border-radius: .25em; -moz-border-radius: .25em; -khtml-border-radius: .25em; box-shadow: 0px 0px 15px #83A; -webkit-box-shadow: 0px 0px 15px #83A; -moz-box-shadow: 0px 0px 15px #83A; -khtml-box-shadow: 0px 0px 15px #83A; border: 1px solid #A6D ! important; display: inline-block; position: absolute}
.MathJax_Menu_Button .MathJax_Hover_Arrow {position: absolute; cursor: pointer; display: inline-block; border: 2px solid #AAA; border-radius: 4px; -webkit-border-radius: 4px; -moz-border-radius: 4px; -khtml-border-radius: 4px; font-family: 'Courier New',Courier; font-size: 9px; color: #F0F0F0}
.MathJax_Menu_Button .MathJax_Hover_Arrow span {display: block; background-color: #AAA; border: 1px solid; border-radius: 3px; line-height: 0; padding: 4px}
.MathJax_Hover_Arrow:hover {color: white!important; border: 2px solid #CCC!important}
.MathJax_Hover_Arrow:hover span {background-color: #CCC!important}
</style><style type="text/css">#MathJax_About {position: fixed; left: 50%; width: auto; text-align: center; border: 3px outset; padding: 1em 2em; background-color: #DDDDDD; color: black; cursor: default; font-family: message-box; font-size: 120%; font-style: normal; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; z-index: 201; border-radius: 15px; -webkit-border-radius: 15px; -moz-border-radius: 15px; -khtml-border-radius: 15px; box-shadow: 0px 10px 20px #808080; -webkit-box-shadow: 0px 10px 20px #808080; -moz-box-shadow: 0px 10px 20px #808080; -khtml-box-shadow: 0px 10px 20px #808080; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
#MathJax_About.MathJax_MousePost {outline: none}
.MathJax_Menu {position: absolute; background-color: white; color: black; width: auto; padding: 2px; border: 1px solid #CCCCCC; margin: 0; cursor: default; font: menu; text-align: left; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; z-index: 201; box-shadow: 0px 10px 20px #808080; -webkit-box-shadow: 0px 10px 20px #808080; -moz-box-shadow: 0px 10px 20px #808080; -khtml-box-shadow: 0px 10px 20px #808080; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
.MathJax_MenuItem {padding: 2px 2em; background: transparent}
.MathJax_MenuArrow {position: absolute; right: .5em; padding-top: .25em; color: #666666; font-size: .75em}
.MathJax_MenuActive .MathJax_MenuArrow {color: white}
.MathJax_MenuArrow.RTL {left: .5em; right: auto}
.MathJax_MenuCheck {position: absolute; left: .7em}
.MathJax_MenuCheck.RTL {right: .7em; left: auto}
.MathJax_MenuRadioCheck {position: absolute; left: 1em}
.MathJax_MenuRadioCheck.RTL {right: 1em; left: auto}
.MathJax_MenuLabel {padding: 2px 2em 4px 1.33em; font-style: italic}
.MathJax_MenuRule {border-top: 1px solid #CCCCCC; margin: 4px 1px 0px}
.MathJax_MenuDisabled {color: GrayText}
.MathJax_MenuActive {background-color: Highlight; color: HighlightText}
.MathJax_MenuDisabled:focus, .MathJax_MenuLabel:focus {background-color: #E8E8E8}
.MathJax_ContextMenu:focus {outline: none}
.MathJax_ContextMenu .MathJax_MenuItem:focus {outline: none}
#MathJax_AboutClose {top: .2em; right: .2em}
.MathJax_Menu .MathJax_MenuClose {top: -10px; left: -10px}
.MathJax_MenuClose {position: absolute; cursor: pointer; display: inline-block; border: 2px solid #AAA; border-radius: 18px; -webkit-border-radius: 18px; -moz-border-radius: 18px; -khtml-border-radius: 18px; font-family: 'Courier New',Courier; font-size: 24px; color: #F0F0F0}
.MathJax_MenuClose span {display: block; background-color: #AAA; border: 1.5px solid; border-radius: 18px; -webkit-border-radius: 18px; -moz-border-radius: 18px; -khtml-border-radius: 18px; line-height: 0; padding: 8px 0 6px}
.MathJax_MenuClose:hover {color: white!important; border: 2px solid #CCC!important}
.MathJax_MenuClose:hover span {background-color: #CCC!important}
.MathJax_MenuClose:hover:focus {outline: none}
</style><style type="text/css">.MathJax_Preview .MJXf-math {color: inherit!important}
</style><style type="text/css">.MJX_Assistive_MathML {position: absolute!important; top: 0; left: 0; clip: rect(1px, 1px, 1px, 1px); padding: 1px 0 0 0!important; border: 0!important; height: 1px!important; width: 1px!important; overflow: hidden!important; display: block!important; -webkit-touch-callout: none; -webkit-user-select: none; -khtml-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none}
.MJX_Assistive_MathML.MJX_Assistive_MathML_Block {width: 100%!important}
</style><style type="text/css">#MathJax_Zoom {position: absolute; background-color: #F0F0F0; overflow: auto; display: block; z-index: 301; padding: .5em; border: 1px solid black; margin: 0; font-weight: normal; font-style: normal; text-align: left; text-indent: 0; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; -webkit-box-sizing: content-box; -moz-box-sizing: content-box; box-sizing: content-box; box-shadow: 5px 5px 15px #AAAAAA; -webkit-box-shadow: 5px 5px 15px #AAAAAA; -moz-box-shadow: 5px 5px 15px #AAAAAA; -khtml-box-shadow: 5px 5px 15px #AAAAAA; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true')}
#MathJax_ZoomOverlay {position: absolute; left: 0; top: 0; z-index: 300; display: inline-block; width: 100%; height: 100%; border: 0; padding: 0; margin: 0; background-color: white; opacity: 0; filter: alpha(opacity=0)}
#MathJax_ZoomFrame {position: relative; display: inline-block; height: 0; width: 0}
#MathJax_ZoomEventTrap {position: absolute; left: 0; top: 0; z-index: 302; display: inline-block; border: 0; padding: 0; margin: 0; background-color: white; opacity: 0; filter: alpha(opacity=0)}
</style><style type="text/css">.MathJax_Preview {color: #888}
#MathJax_Message {position: fixed; left: 1em; bottom: 1.5em; background-color: #E6E6E6; border: 1px solid #959595; margin: 0px; padding: 2px 8px; z-index: 102; color: black; font-size: 80%; width: auto; white-space: nowrap}
#MathJax_MSIE_Frame {position: absolute; top: 0; left: 0; width: 0px; z-index: 101; border: 0px; margin: 0px; padding: 0px}
.MathJax_Error {color: #CC0000; font-style: italic}
</style><style type="text/css">.MJXp-script {font-size: .8em}
.MJXp-right {-webkit-transform-origin: right; -moz-transform-origin: right; -ms-transform-origin: right; -o-transform-origin: right; transform-origin: right}
.MJXp-bold {font-weight: bold}
.MJXp-italic {font-style: italic}
.MJXp-scr {font-family: MathJax_Script,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-frak {font-family: MathJax_Fraktur,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-sf {font-family: MathJax_SansSerif,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-cal {font-family: MathJax_Caligraphic,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-mono {font-family: MathJax_Typewriter,'Times New Roman',Times,STIXGeneral,serif}
.MJXp-largeop {font-size: 150%}
.MJXp-largeop.MJXp-int {vertical-align: -.2em}
.MJXp-math {display: inline-block; line-height: 1.2; text-indent: 0; font-family: 'Times New Roman',Times,STIXGeneral,serif; white-space: nowrap; border-collapse: collapse}
.MJXp-display {display: block; text-align: center; margin: 1em 0}
.MJXp-math span {display: inline-block}
.MJXp-box {display: block!important; text-align: center}
.MJXp-box:after {content: " "}
.MJXp-rule {display: block!important; margin-top: .1em}
.MJXp-char {display: block!important}
.MJXp-mo {margin: 0 .15em}
.MJXp-mfrac {margin: 0 .125em; vertical-align: .25em}
.MJXp-denom {display: inline-table!important; width: 100%}
.MJXp-denom > * {display: table-row!important}
.MJXp-surd {vertical-align: top}
.MJXp-surd > * {display: block!important}
.MJXp-script-box > *  {display: table!important; height: 50%}
.MJXp-script-box > * > * {display: table-cell!important; vertical-align: top}
.MJXp-script-box > *:last-child > * {vertical-align: bottom}
.MJXp-script-box > * > * > * {display: block!important}
.MJXp-mphantom {visibility: hidden}
.MJXp-munderover {display: inline-table!important}
.MJXp-over {display: inline-block!important; text-align: center}
.MJXp-over > * {display: block!important}
.MJXp-munderover > * {display: table-row!important}
.MJXp-mtable {vertical-align: .25em; margin: 0 .125em}
.MJXp-mtable > * {display: inline-table!important; vertical-align: middle}
.MJXp-mtr {display: table-row!important}
.MJXp-mtd {display: table-cell!important; text-align: center; padding: .5em 0 0 .5em}
.MJXp-mtr > .MJXp-mtd:first-child {padding-left: 0}
.MJXp-mtr:first-child > .MJXp-mtd {padding-top: 0}
.MJXp-mlabeledtr {display: table-row!important}
.MJXp-mlabeledtr > .MJXp-mtd:first-child {padding-left: 0}
.MJXp-mlabeledtr:first-child > .MJXp-mtd {padding-top: 0}
.MJXp-merror {background-color: #FFFF88; color: #CC0000; border: 1px solid #CC0000; padding: 1px 3px; font-style: normal; font-size: 90%}
.MJXp-scale0 {-webkit-transform: scaleX(.0); -moz-transform: scaleX(.0); -ms-transform: scaleX(.0); -o-transform: scaleX(.0); transform: scaleX(.0)}
.MJXp-scale1 {-webkit-transform: scaleX(.1); -moz-transform: scaleX(.1); -ms-transform: scaleX(.1); -o-transform: scaleX(.1); transform: scaleX(.1)}
.MJXp-scale2 {-webkit-transform: scaleX(.2); -moz-transform: scaleX(.2); -ms-transform: scaleX(.2); -o-transform: scaleX(.2); transform: scaleX(.2)}
.MJXp-scale3 {-webkit-transform: scaleX(.3); -moz-transform: scaleX(.3); -ms-transform: scaleX(.3); -o-transform: scaleX(.3); transform: scaleX(.3)}
.MJXp-scale4 {-webkit-transform: scaleX(.4); -moz-transform: scaleX(.4); -ms-transform: scaleX(.4); -o-transform: scaleX(.4); transform: scaleX(.4)}
.MJXp-scale5 {-webkit-transform: scaleX(.5); -moz-transform: scaleX(.5); -ms-transform: scaleX(.5); -o-transform: scaleX(.5); transform: scaleX(.5)}
.MJXp-scale6 {-webkit-transform: scaleX(.6); -moz-transform: scaleX(.6); -ms-transform: scaleX(.6); -o-transform: scaleX(.6); transform: scaleX(.6)}
.MJXp-scale7 {-webkit-transform: scaleX(.7); -moz-transform: scaleX(.7); -ms-transform: scaleX(.7); -o-transform: scaleX(.7); transform: scaleX(.7)}
.MJXp-scale8 {-webkit-transform: scaleX(.8); -moz-transform: scaleX(.8); -ms-transform: scaleX(.8); -o-transform: scaleX(.8); transform: scaleX(.8)}
.MJXp-scale9 {-webkit-transform: scaleX(.9); -moz-transform: scaleX(.9); -ms-transform: scaleX(.9); -o-transform: scaleX(.9); transform: scaleX(.9)}
.MathJax_PHTML .noError {vertical-align: ; font-size: 90%; text-align: left; color: black; padding: 1px 3px; border: 1px solid}
</style><style type="text/css">.MathJax_Display {text-align: center; margin: 0; position: relative; display: block!important; text-indent: 0; max-width: none; max-height: none; min-width: 0; min-height: 0; width: 100%}
.MathJax .merror {background-color: #FFFF88; color: #CC0000; border: 1px solid #CC0000; padding: 1px 3px; font-style: normal; font-size: 90%}
.MathJax .MJX-monospace {font-family: monospace}
.MathJax .MJX-sans-serif {font-family: sans-serif}
#MathJax_Tooltip {background-color: InfoBackground; color: InfoText; border: 1px solid black; box-shadow: 2px 2px 5px #AAAAAA; -webkit-box-shadow: 2px 2px 5px #AAAAAA; -moz-box-shadow: 2px 2px 5px #AAAAAA; -khtml-box-shadow: 2px 2px 5px #AAAAAA; filter: progid:DXImageTransform.Microsoft.dropshadow(OffX=2, OffY=2, Color='gray', Positive='true'); padding: 3px 4px; z-index: 401; position: absolute; left: 0; top: 0; width: auto; height: auto; display: none}
.MathJax {display: inline; font-style: normal; font-weight: normal; line-height: normal; font-size: 100%; font-size-adjust: none; text-indent: 0; text-align: left; text-transform: none; letter-spacing: normal; word-spacing: normal; word-wrap: normal; white-space: nowrap; float: none; direction: ltr; max-width: none; max-height: none; min-width: 0; min-height: 0; border: 0; padding: 0; margin: 0}
.MathJax:focus, body :focus .MathJax {display: inline-table}
.MathJax.MathJax_FullWidth {text-align: center; display: table-cell!important; width: 10000em!important}
.MathJax img, .MathJax nobr, .MathJax a {border: 0; padding: 0; margin: 0; max-width: none; max-height: none; min-width: 0; min-height: 0; vertical-align: 0; line-height: normal; text-decoration: none}
img.MathJax_strut {border: 0!important; padding: 0!important; margin: 0!important; vertical-align: 0!important}
.MathJax span {display: inline; position: static; border: 0; padding: 0; margin: 0; vertical-align: 0; line-height: normal; text-decoration: none}
.MathJax nobr {white-space: nowrap!important}
.MathJax img {display: inline!important; float: none!important}
.MathJax * {transition: none; -webkit-transition: none; -moz-transition: none; -ms-transition: none; -o-transition: none}
.MathJax_Processing {visibility: hidden; position: fixed; width: 0; height: 0; overflow: hidden}
.MathJax_Processed {display: none!important}
.MathJax_ExBox {display: block!important; overflow: hidden; width: 1px; height: 60ex; min-height: 0; max-height: none}
.MathJax .MathJax_EmBox {display: block!important; overflow: hidden; width: 1px; height: 60em; min-height: 0; max-height: none}
.MathJax_LineBox {display: table!important}
.MathJax_LineBox span {display: table-cell!important; width: 10000em!important; min-width: 0; max-width: none; padding: 0; border: 0; margin: 0}
.MathJax .MathJax_HitBox {cursor: text; background: white; opacity: 0; filter: alpha(opacity=0)}
.MathJax .MathJax_HitBox * {filter: none; opacity: 1; background: transparent}
#MathJax_Tooltip * {filter: none; opacity: 1; background: transparent}
@font-face {font-family: MathJax_Main; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Main-Regular.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Main-Regular.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Main-bold; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Main-Bold.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Main-Bold.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Main-italic; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Main-Italic.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Main-Italic.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Math-italic; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Math-Italic.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Math-Italic.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Caligraphic; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Caligraphic-Regular.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Caligraphic-Regular.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Size1; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Size1-Regular.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Size1-Regular.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Size2; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Size2-Regular.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Size2-Regular.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Size3; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Size3-Regular.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Size3-Regular.otf?V=2.7.1') format('opentype')}
@font-face {font-family: MathJax_Size4; src: url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/woff/MathJax_Size4-Regular.woff?V=2.7.1') format('woff'), url('https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/fonts/HTML-CSS/TeX/otf/MathJax_Size4-Regular.otf?V=2.7.1') format('opentype')}
.MathJax .noError {vertical-align: ; font-size: 90%; text-align: left; color: black; padding: 1px 3px; border: 1px solid}
</style></head>
<body style=""><div style="visibility: hidden; overflow: hidden; position: absolute; top: 0px; height: 1px; width: auto; padding: 0px; border: 0px; margin: 0px; text-align: left; text-indent: 0px; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal;"><div id="MathJax_Hidden"></div></div><div id="MathJax_Message" style="display: none;"></div>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="CMSC320-Final-Project-(PokeAnalysis)">CMSC320 Final Project (PokeAnalysis)<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#CMSC320-Final-Project-(PokeAnalysis)">¶</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Jason-Hauzel">Jason Hauzel<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Jason-Hauzel">¶</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Tutorial-Content">Tutorial Content<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Tutorial-Content">¶</a></h1><p><a href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Introduction">Introduction</a></p>
<p><a href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Install">Installing Libraries</a></p>
<p><a href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Data">Data Acquisition</a></p>
<p><a href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#analysis">Analysis and ML</a></p>
<p><a href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#conlusion">Conclusion</a></p>
<p><a href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#future">Future Outlook</a></p>
<p><a href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#sources">Sources</a></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id="Introduction"></a></p>
<h1 id="Introduction">Introduction<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Introduction">¶</a></h1><p>Ever since its creation in 1995, Pokemon has become a common household name all around the world. One of the largest contributors to its popularity are the video games, which first released in 1998 on GameBoy and GameBoy Color. Although the game has simple RPG (Role-Playing Game) elements akin to all games in the genre, there are quite a few hidden and complex mechanics involved that make the gameplay fun and interesting for everyone.</p>
<p>In this tutorial we will talk about some of these mechanics and how they affect gameplay, as well as how these mechanics have changed over the generations. We will do this by first collecting data on the first six generations of the Pokemon video games, processing the data to understand/visualize it, and finally utilize machine learning to analyze the complexities involved in the Pokemon games and how it has changed over time.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id="Install"></a></p>
<h1 id="Installing-Libraries">Installing Libraries<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Installing-Libraries">¶</a></h1><p>Here are few libraries I will be using throughout this tutorial.</p>
<p><code>$ pip install numpy</code></p>
<p><code>$ pip install scipy</code></p>
<p><code>$ pip install scikit-learn</code></p>
<p><code>$ pip install pandas</code></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id="Data"></a></p>
<h1 id="Data-Acuisition">Data Acuisition<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Data-Acuisition">¶</a></h1><p>The data used here will be from a pokemon database on kaggle.com</p>
<p>After importing the necessary libraries, we can read in cvs files using the pandas function read_csv</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[215]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Importing libraries</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">matplotlib</span>

<span class="n">pokeDex</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">"Pokemon.csv"</span><span class="p">)</span>
<span class="n">pokeDex</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[215]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>Total</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Bulbasaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>318</td>
      <td>45</td>
      <td>49</td>
      <td>49</td>
      <td>65</td>
      <td>65</td>
      <td>45</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Ivysaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>405</td>
      <td>60</td>
      <td>62</td>
      <td>63</td>
      <td>80</td>
      <td>80</td>
      <td>60</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>525</td>
      <td>80</td>
      <td>82</td>
      <td>83</td>
      <td>100</td>
      <td>100</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>VenusaurMega Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>625</td>
      <td>80</td>
      <td>100</td>
      <td>123</td>
      <td>122</td>
      <td>120</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Charmander</td>
      <td>Fire</td>
      <td>NaN</td>
      <td>309</td>
      <td>39</td>
      <td>52</td>
      <td>43</td>
      <td>60</td>
      <td>50</td>
      <td>65</td>
      <td>1</td>
      <td>False</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Here I've created the pokeDex object of type pandas.DataFrame. It stores the data in an array-like matrix with column and row values as values that can be used to manipulate the data.</p>
<p>As we can see, the dataset contains the name, type, stats and other information about each pokemon.</p>
<p>With each new generation of pokemon, there is an introduction of new mechanics. One of them being Mega evolutions and Primal versions of pokemon. For this dataset, it considers these new features as part of the old generation but I will have it so each pokemon version is associated with the generation it was introduced in.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[216]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">re</span>

<span class="k">def</span> <span class="nf">is_mega_primal</span><span class="p">(</span><span class="n">row</span><span class="p">):</span>
    <span class="n">mega</span> <span class="o">=</span> <span class="n">re</span><span class="o">.</span><span class="n">search</span><span class="p">(</span><span class="s1">'Mega'</span><span class="p">,</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Name'</span><span class="p">])</span>
    <span class="n">primal</span> <span class="o">=</span> <span class="n">re</span><span class="o">.</span><span class="n">search</span><span class="p">(</span><span class="s1">'Primal'</span><span class="p">,</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Name'</span><span class="p">])</span>
    <span class="k">if</span> <span class="n">mega</span> <span class="ow">or</span> <span class="n">primal</span><span class="p">:</span>
        <span class="n">row</span><span class="p">[</span><span class="s1">'Generation'</span><span class="p">]</span> <span class="o">=</span> <span class="mi">6</span>
        
    <span class="c1">#for i,v in row.iteritems():</span>
        <span class="c1">#print(type(v))</span>
    <span class="k">return</span> <span class="n">row</span>

<span class="n">pokeDex</span> <span class="o">=</span> <span class="n">pokeDex</span><span class="o">.</span><span class="n">apply</span><span class="p">(</span><span class="k">lambda</span> <span class="n">x</span><span class="p">:</span> <span class="n">is_mega_primal</span><span class="p">(</span><span class="n">x</span><span class="p">),</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">pokeDex</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[216]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>Total</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Bulbasaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>318</td>
      <td>45</td>
      <td>49</td>
      <td>49</td>
      <td>65</td>
      <td>65</td>
      <td>45</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Ivysaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>405</td>
      <td>60</td>
      <td>62</td>
      <td>63</td>
      <td>80</td>
      <td>80</td>
      <td>60</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>525</td>
      <td>80</td>
      <td>82</td>
      <td>83</td>
      <td>100</td>
      <td>100</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>VenusaurMega Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>625</td>
      <td>80</td>
      <td>100</td>
      <td>123</td>
      <td>122</td>
      <td>120</td>
      <td>80</td>
      <td>6</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Charmander</td>
      <td>Fire</td>
      <td>NaN</td>
      <td>309</td>
      <td>39</td>
      <td>52</td>
      <td>43</td>
      <td>60</td>
      <td>50</td>
      <td>65</td>
      <td>1</td>
      <td>False</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now that we've corrected some parts of our data, we can add more to it.</p>
<p>In the pokemon video games, all the player typically sees when assess his/her pokemon are the statistics (i.e. HP, Attack, Defense, etc...). Unbeknownst to most players, there is actually more to what goes behind calculating each stat and thus the total power of the pokemon.</p>
<p>The first hidden mechanic is called an Individual Value (IV), which is the pokemon's inherent value for each stat. IV's take a value anywhere in the range of 0-31, and when a pokemon reaches level 100, the IV is added on top of the Base stat. In the game, the value is randomly assigned, meaning each pokemon is not created equal and it could make the difference between winning or losing a fight. There are certain ways to obtain pokemon with high IV's but mostly through chance.</p>
<p>Additionally, there is a mechanic called Effort Values (EV), which taken into consideration which pokemon have been fought. These values also add onto each Base stat and increases the overall power level of the pokemon. Certain pokemon, when fought, give an EV for a particular stat. For example, say your pikachu battles and defeats an Ekans (wild or trainer), then it will get +1 EV towards its Attack stat because that is the stat Ekans modifies. Four EV's for a given stat equate to an increase by 1 of the overall stat. Each pokemon can gain a total of 510 EV points but only 255 towards any given stat.</p>
<p>For generation I and II, calculation of total stat is done by "Oak's Theorem", and by "Birch's Theorem" for gen III and above. Additionally, the HP stat is calculated differently from the other stats by each Theorem.</p>
<h3 id="Oak&#39;s-Theorem:">Oak's Theorem:<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Oak&#39;s-Theorem:">¶</a></h3><span class="MathJax_Preview" style="color: inherit; display: none;"></span><div class="MathJax_Display" style="text-align: center;"><span class="MathJax" id="MathJax-Element-1-Frame" tabindex="0" style="text-align: center; position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;&gt;&lt;msub&gt;&lt;mi&gt;&amp;#x03C1;&lt;/mi&gt;&lt;mrow class=&quot;MJX-TeXAtom-ORD&quot;&gt;&lt;mi&gt;H&lt;/mi&gt;&lt;mi&gt;P&lt;/mi&gt;&lt;/mrow&gt;&lt;/msub&gt;&lt;mo&gt;=&lt;/mo&gt;&lt;mfrac&gt;&lt;mrow&gt;&lt;mo stretchy=&quot;false&quot;&gt;(&lt;/mo&gt;&lt;mn&gt;2&lt;/mn&gt;&lt;mo stretchy=&quot;false&quot;&gt;(&lt;/mo&gt;&lt;mi&gt;B&lt;/mi&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mi&gt;I&lt;/mi&gt;&lt;mo stretchy=&quot;false&quot;&gt;)&lt;/mo&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mfrac&gt;&lt;msqrt&gt;&lt;mi&gt;&amp;#x03C3;&lt;/mi&gt;&lt;/msqrt&gt;&lt;mn&gt;4&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo stretchy=&quot;false&quot;&gt;)&lt;/mo&gt;&lt;mo&gt;&amp;#x2217;&lt;/mo&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;/mrow&gt;&lt;mn&gt;100&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mn&gt;10&lt;/mn&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-1" style="width: 19.646em; display: inline-block;"><span style="display: inline-block; position: relative; width: 16.372em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(0.003em 1016.31em 3.098em -999.997em); top: -2.199em; left: 0em;"><span class="mrow" id="MathJax-Span-2"><span class="msubsup" id="MathJax-Span-3"><span style="display: inline-block; position: relative; width: 1.729em; height: 0px;"><span style="position: absolute; clip: rect(3.396em 1000.54em 4.408em -999.997em); top: -3.985em; left: 0em;"><span class="mi" id="MathJax-Span-4" style="font-family: MathJax_Math-italic;">ρ</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; top: -3.807em; left: 0.539em;"><span class="texatom" id="MathJax-Span-5"><span class="mrow" id="MathJax-Span-6"><span class="mi" id="MathJax-Span-7" style="font-size: 70.7%; font-family: MathJax_Math-italic;">H<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span><span class="mi" id="MathJax-Span-8" style="font-size: 70.7%; font-family: MathJax_Math-italic;">P<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span></span></span><span class="mo" id="MathJax-Span-9" style="font-family: MathJax_Main; padding-left: 0.301em;">=</span><span class="mfrac" id="MathJax-Span-10" style="padding-left: 0.301em;"><span style="display: inline-block; position: relative; width: 8.932em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(2.682em 1008.75em 4.586em -999.997em); top: -4.878em; left: 50%; margin-left: -4.402em;"><span class="mrow" id="MathJax-Span-11"><span class="mo" id="MathJax-Span-12" style="font-family: MathJax_Main;">(</span><span class="mn" id="MathJax-Span-13" style="font-family: MathJax_Main;">2</span><span class="mo" id="MathJax-Span-14" style="font-family: MathJax_Main;">(</span><span class="mi" id="MathJax-Span-15" style="font-family: MathJax_Math-italic;">B</span><span class="mo" id="MathJax-Span-16" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mi" id="MathJax-Span-17" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">I<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span><span class="mo" id="MathJax-Span-18" style="font-family: MathJax_Main;">)</span><span class="mo" id="MathJax-Span-19" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mfrac" id="MathJax-Span-20" style="padding-left: 0.241em;"><span style="display: inline-block; position: relative; width: 1.134em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(3.336em 1001.01em 4.408em -999.997em); top: -4.64em; left: 50%; margin-left: -0.473em;"><span class="msqrt" id="MathJax-Span-21"><span style="display: inline-block; position: relative; width: 1.015em; height: 0px;"><span style="position: absolute; clip: rect(3.515em 1000.42em 4.17em -999.997em); top: -3.985em; left: 0.598em;"><span class="mrow" id="MathJax-Span-22"><span class="mi" id="MathJax-Span-23" style="font-size: 70.7%; font-family: MathJax_Math-italic;">σ<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.003em;"></span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.955em 1000.42em 1.313em -999.997em); top: -1.604em; left: 0.598em;"><span style="display: inline-block; overflow: hidden; vertical-align: -0.057em; border-top: 1.2px solid; width: 0.42em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span><span style="position: absolute; clip: rect(3.217em 1000.6em 4.289em -999.997em); top: -3.926em; left: 0em;"><span><span style="font-size: 70.7%; font-family: MathJax_Main;">√</span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.336em 1000.36em 4.17em -999.997em); top: -3.568em; left: 50%; margin-left: -0.176em;"><span class="mn" id="MathJax-Span-24" style="font-size: 70.7%; font-family: MathJax_Main;">4</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1001.13em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 1.134em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-25" style="font-family: MathJax_Main;">)</span><span class="mo" id="MathJax-Span-26" style="font-family: MathJax_Main; padding-left: 0.241em;">∗</span><span class="mi" id="MathJax-Span-27" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">α</span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.158em 1001.49em 4.17em -999.997em); top: -3.271em; left: 50%; margin-left: -0.771em;"><span class="mn" id="MathJax-Span-28" style="font-family: MathJax_Main;">100</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1008.93em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 8.932em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-29" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mi" id="MathJax-Span-30" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">α</span><span class="mo" id="MathJax-Span-31" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mn" id="MathJax-Span-32" style="font-family: MathJax_Main; padding-left: 0.241em;">10</span></span><span style="display: inline-block; width: 0px; height: 2.205em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.925em; border-left: 0px solid; width: 0px; height: 3.432em;"></span></span></nobr><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mi>ρ</mi><mrow class="MJX-TeXAtom-ORD"><mi>H</mi><mi>P</mi></mrow></msub><mo>=</mo><mfrac><mrow><mo stretchy="false">(</mo><mn>2</mn><mo stretchy="false">(</mo><mi>B</mi><mo>+</mo><mi>I</mi><mo stretchy="false">)</mo><mo>+</mo><mfrac><msqrt><mi>σ</mi></msqrt><mn>4</mn></mfrac><mo stretchy="false">)</mo><mo>∗</mo><mi>α</mi></mrow><mn>100</mn></mfrac><mo>+</mo><mi>α</mi><mo>+</mo><mn>10</mn></math></span></span></div><script type="math/tex; mode=display" id="MathJax-Element-1">\rho_{HP} = \frac{(2(B+I)+\frac{\sqrt{\sigma}}{4})*\alpha}{100} + \alpha + 10</script><span class="MathJax_Preview" style="color: inherit; display: none;"></span><div class="MathJax_Display" style="text-align: center;"><span class="MathJax" id="MathJax-Element-2-Frame" tabindex="0" style="text-align: center; position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;&gt;&lt;msub&gt;&lt;mi&gt;&amp;#x03C1;&lt;/mi&gt;&lt;mrow class=&quot;MJX-TeXAtom-ORD&quot;&gt;&lt;mi&gt;s&lt;/mi&gt;&lt;mi&gt;t&lt;/mi&gt;&lt;mi&gt;a&lt;/mi&gt;&lt;mi&gt;t&lt;/mi&gt;&lt;/mrow&gt;&lt;/msub&gt;&lt;mo&gt;=&lt;/mo&gt;&lt;mfrac&gt;&lt;mrow&gt;&lt;mo stretchy=&quot;false&quot;&gt;(&lt;/mo&gt;&lt;mn&gt;2&lt;/mn&gt;&lt;mo stretchy=&quot;false&quot;&gt;(&lt;/mo&gt;&lt;mi&gt;B&lt;/mi&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mi&gt;I&lt;/mi&gt;&lt;mo stretchy=&quot;false&quot;&gt;)&lt;/mo&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mfrac&gt;&lt;msqrt&gt;&lt;mi&gt;&amp;#x03C3;&lt;/mi&gt;&lt;/msqrt&gt;&lt;mn&gt;4&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo stretchy=&quot;false&quot;&gt;)&lt;/mo&gt;&lt;mo&gt;&amp;#x2217;&lt;/mo&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;/mrow&gt;&lt;mn&gt;100&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mn&gt;5&lt;/mn&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-33" style="width: 16.908em; display: inline-block;"><span style="display: inline-block; position: relative; width: 14.051em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(0.003em 1013.99em 3.098em -999.997em); top: -2.199em; left: 0em;"><span class="mrow" id="MathJax-Span-34"><span class="msubsup" id="MathJax-Span-35"><span style="display: inline-block; position: relative; width: 1.789em; height: 0px;"><span style="position: absolute; clip: rect(3.396em 1000.54em 4.408em -999.997em); top: -3.985em; left: 0em;"><span class="mi" id="MathJax-Span-36" style="font-family: MathJax_Math-italic;">ρ</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; top: -3.807em; left: 0.539em;"><span class="texatom" id="MathJax-Span-37"><span class="mrow" id="MathJax-Span-38"><span class="mi" id="MathJax-Span-39" style="font-size: 70.7%; font-family: MathJax_Math-italic;">s</span><span class="mi" id="MathJax-Span-40" style="font-size: 70.7%; font-family: MathJax_Math-italic;">t</span><span class="mi" id="MathJax-Span-41" style="font-size: 70.7%; font-family: MathJax_Math-italic;">a</span><span class="mi" id="MathJax-Span-42" style="font-size: 70.7%; font-family: MathJax_Math-italic;">t</span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span></span></span><span class="mo" id="MathJax-Span-43" style="font-family: MathJax_Main; padding-left: 0.301em;">=</span><span class="mfrac" id="MathJax-Span-44" style="padding-left: 0.301em;"><span style="display: inline-block; position: relative; width: 8.932em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(2.682em 1008.75em 4.586em -999.997em); top: -4.878em; left: 50%; margin-left: -4.402em;"><span class="mrow" id="MathJax-Span-45"><span class="mo" id="MathJax-Span-46" style="font-family: MathJax_Main;">(</span><span class="mn" id="MathJax-Span-47" style="font-family: MathJax_Main;">2</span><span class="mo" id="MathJax-Span-48" style="font-family: MathJax_Main;">(</span><span class="mi" id="MathJax-Span-49" style="font-family: MathJax_Math-italic;">B</span><span class="mo" id="MathJax-Span-50" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mi" id="MathJax-Span-51" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">I<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span><span class="mo" id="MathJax-Span-52" style="font-family: MathJax_Main;">)</span><span class="mo" id="MathJax-Span-53" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mfrac" id="MathJax-Span-54" style="padding-left: 0.241em;"><span style="display: inline-block; position: relative; width: 1.134em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(3.336em 1001.01em 4.408em -999.997em); top: -4.64em; left: 50%; margin-left: -0.473em;"><span class="msqrt" id="MathJax-Span-55"><span style="display: inline-block; position: relative; width: 1.015em; height: 0px;"><span style="position: absolute; clip: rect(3.515em 1000.42em 4.17em -999.997em); top: -3.985em; left: 0.598em;"><span class="mrow" id="MathJax-Span-56"><span class="mi" id="MathJax-Span-57" style="font-size: 70.7%; font-family: MathJax_Math-italic;">σ<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.003em;"></span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.955em 1000.42em 1.313em -999.997em); top: -1.604em; left: 0.598em;"><span style="display: inline-block; overflow: hidden; vertical-align: -0.057em; border-top: 1.2px solid; width: 0.42em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span><span style="position: absolute; clip: rect(3.217em 1000.6em 4.289em -999.997em); top: -3.926em; left: 0em;"><span><span style="font-size: 70.7%; font-family: MathJax_Main;">√</span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.336em 1000.36em 4.17em -999.997em); top: -3.568em; left: 50%; margin-left: -0.176em;"><span class="mn" id="MathJax-Span-58" style="font-size: 70.7%; font-family: MathJax_Main;">4</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1001.13em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 1.134em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-59" style="font-family: MathJax_Main;">)</span><span class="mo" id="MathJax-Span-60" style="font-family: MathJax_Main; padding-left: 0.241em;">∗</span><span class="mi" id="MathJax-Span-61" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">α</span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.158em 1001.49em 4.17em -999.997em); top: -3.271em; left: 50%; margin-left: -0.771em;"><span class="mn" id="MathJax-Span-62" style="font-family: MathJax_Main;">100</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1008.93em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 8.932em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-63" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mn" id="MathJax-Span-64" style="font-family: MathJax_Main; padding-left: 0.241em;">5</span></span><span style="display: inline-block; width: 0px; height: 2.205em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.925em; border-left: 0px solid; width: 0px; height: 3.432em;"></span></span></nobr><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mi>ρ</mi><mrow class="MJX-TeXAtom-ORD"><mi>s</mi><mi>t</mi><mi>a</mi><mi>t</mi></mrow></msub><mo>=</mo><mfrac><mrow><mo stretchy="false">(</mo><mn>2</mn><mo stretchy="false">(</mo><mi>B</mi><mo>+</mo><mi>I</mi><mo stretchy="false">)</mo><mo>+</mo><mfrac><msqrt><mi>σ</mi></msqrt><mn>4</mn></mfrac><mo stretchy="false">)</mo><mo>∗</mo><mi>α</mi></mrow><mn>100</mn></mfrac><mo>+</mo><mn>5</mn></math></span></span></div><script type="math/tex; mode=display" id="MathJax-Element-2">\rho_{stat} = \frac{(2(B+I)+\frac{\sqrt{\sigma}}{4})*\alpha}{100} + 5</script><h3 id="Birch&#39;s-Theorem:">Birch's Theorem:<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Birch&#39;s-Theorem:">¶</a></h3><span class="MathJax_Preview" style="color: inherit; display: none;"></span><div class="MathJax_Display" style="text-align: center;"><span class="MathJax" id="MathJax-Element-3-Frame" tabindex="0" style="text-align: center; position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;&gt;&lt;msub&gt;&lt;mi mathvariant=&quot;normal&quot;&gt;&amp;#x0393;&lt;/mi&gt;&lt;mrow class=&quot;MJX-TeXAtom-ORD&quot;&gt;&lt;mi&gt;H&lt;/mi&gt;&lt;mi&gt;P&lt;/mi&gt;&lt;/mrow&gt;&lt;/msub&gt;&lt;mo&gt;=&lt;/mo&gt;&lt;mfrac&gt;&lt;mrow&gt;&lt;mo stretchy=&quot;false&quot;&gt;(&lt;/mo&gt;&lt;mn&gt;2&lt;/mn&gt;&lt;mi&gt;B&lt;/mi&gt;&lt;mi&gt;I&lt;/mi&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mfrac&gt;&lt;mi&gt;&amp;#x03C3;&lt;/mi&gt;&lt;mn&gt;4&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo stretchy=&quot;false&quot;&gt;)&lt;/mo&gt;&lt;mo&gt;&amp;#x2217;&lt;/mo&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;/mrow&gt;&lt;mn&gt;100&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mn&gt;10&lt;/mn&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-65" style="width: 16.67em; display: inline-block;"><span style="display: inline-block; position: relative; width: 13.872em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(0.36em 1013.81em 3.098em -999.997em); top: -2.199em; left: 0em;"><span class="mrow" id="MathJax-Span-66"><span class="msubsup" id="MathJax-Span-67"><span style="display: inline-block; position: relative; width: 1.848em; height: 0px;"><span style="position: absolute; clip: rect(3.158em 1000.6em 4.17em -999.997em); top: -3.985em; left: 0em;"><span class="mi" id="MathJax-Span-68" style="font-family: MathJax_Main;">Γ</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; top: -3.807em; left: 0.658em;"><span class="texatom" id="MathJax-Span-69"><span class="mrow" id="MathJax-Span-70"><span class="mi" id="MathJax-Span-71" style="font-size: 70.7%; font-family: MathJax_Math-italic;">H<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span><span class="mi" id="MathJax-Span-72" style="font-size: 70.7%; font-family: MathJax_Math-italic;">P<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span></span></span><span class="mo" id="MathJax-Span-73" style="font-family: MathJax_Main; padding-left: 0.301em;">=</span><span class="mfrac" id="MathJax-Span-74" style="padding-left: 0.301em;"><span style="display: inline-block; position: relative; width: 6.313em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(3.039em 1006.13em 4.586em -999.997em); top: -4.878em; left: 50%; margin-left: -3.092em;"><span class="mrow" id="MathJax-Span-75"><span class="mo" id="MathJax-Span-76" style="font-family: MathJax_Main;">(</span><span class="mn" id="MathJax-Span-77" style="font-family: MathJax_Main;">2</span><span class="mi" id="MathJax-Span-78" style="font-family: MathJax_Math-italic;">B</span><span class="mi" id="MathJax-Span-79" style="font-family: MathJax_Math-italic;">I<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span><span class="mo" id="MathJax-Span-80" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mfrac" id="MathJax-Span-81" style="padding-left: 0.241em;"><span style="display: inline-block; position: relative; width: 0.539em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(3.515em 1000.42em 4.17em -999.997em); top: -4.402em; left: 50%; margin-left: -0.176em;"><span class="mi" id="MathJax-Span-82" style="font-size: 70.7%; font-family: MathJax_Math-italic;">σ<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.003em;"></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.336em 1000.36em 4.17em -999.997em); top: -3.568em; left: 50%; margin-left: -0.176em;"><span class="mn" id="MathJax-Span-83" style="font-size: 70.7%; font-family: MathJax_Main;">4</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1000.54em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 0.539em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-84" style="font-family: MathJax_Main;">)</span><span class="mo" id="MathJax-Span-85" style="font-family: MathJax_Main; padding-left: 0.241em;">∗</span><span class="mi" id="MathJax-Span-86" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">α</span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.158em 1001.49em 4.17em -999.997em); top: -3.271em; left: 50%; margin-left: -0.771em;"><span class="mn" id="MathJax-Span-87" style="font-family: MathJax_Main;">100</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1006.31em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 6.313em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-88" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mi" id="MathJax-Span-89" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">α</span><span class="mo" id="MathJax-Span-90" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mn" id="MathJax-Span-91" style="font-family: MathJax_Main; padding-left: 0.241em;">10</span></span><span style="display: inline-block; width: 0px; height: 2.205em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.925em; border-left: 0px solid; width: 0px; height: 2.932em;"></span></span></nobr><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mi mathvariant="normal">Γ</mi><mrow class="MJX-TeXAtom-ORD"><mi>H</mi><mi>P</mi></mrow></msub><mo>=</mo><mfrac><mrow><mo stretchy="false">(</mo><mn>2</mn><mi>B</mi><mi>I</mi><mo>+</mo><mfrac><mi>σ</mi><mn>4</mn></mfrac><mo stretchy="false">)</mo><mo>∗</mo><mi>α</mi></mrow><mn>100</mn></mfrac><mo>+</mo><mi>α</mi><mo>+</mo><mn>10</mn></math></span></span></div><script type="math/tex; mode=display" id="MathJax-Element-3">\Gamma_{HP} = \frac{(2BI+\frac{\sigma}{4})*\alpha}{100} + \alpha + 10</script><span class="MathJax_Preview" style="color: inherit; display: none;"></span><div class="MathJax_Display" style="text-align: center;"><span class="MathJax" id="MathJax-Element-4-Frame" tabindex="0" style="text-align: center; position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;&gt;&lt;msub&gt;&lt;mi mathvariant=&quot;normal&quot;&gt;&amp;#x0393;&lt;/mi&gt;&lt;mrow class=&quot;MJX-TeXAtom-ORD&quot;&gt;&lt;mi&gt;s&lt;/mi&gt;&lt;mi&gt;t&lt;/mi&gt;&lt;mi&gt;a&lt;/mi&gt;&lt;mi&gt;t&lt;/mi&gt;&lt;/mrow&gt;&lt;/msub&gt;&lt;mo&gt;=&lt;/mo&gt;&lt;mo stretchy=&quot;false&quot;&gt;(&lt;/mo&gt;&lt;mfrac&gt;&lt;mrow&gt;&lt;mo stretchy=&quot;false&quot;&gt;(&lt;/mo&gt;&lt;mn&gt;2&lt;/mn&gt;&lt;mi&gt;B&lt;/mi&gt;&lt;mi&gt;I&lt;/mi&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mfrac&gt;&lt;mi&gt;&amp;#x03C3;&lt;/mi&gt;&lt;mn&gt;4&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo stretchy=&quot;false&quot;&gt;)&lt;/mo&gt;&lt;mo&gt;&amp;#x2217;&lt;/mo&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;/mrow&gt;&lt;mn&gt;100&lt;/mn&gt;&lt;/mfrac&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mn&gt;5&lt;/mn&gt;&lt;mo stretchy=&quot;false&quot;&gt;)&lt;/mo&gt;&lt;mi&gt;&amp;#x03D5;&lt;/mi&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-92" style="width: 15.539em; display: inline-block;"><span style="display: inline-block; position: relative; width: 12.92em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(0.36em 1012.92em 3.098em -999.997em); top: -2.199em; left: 0em;"><span class="mrow" id="MathJax-Span-93"><span class="msubsup" id="MathJax-Span-94"><span style="display: inline-block; position: relative; width: 1.908em; height: 0px;"><span style="position: absolute; clip: rect(3.158em 1000.6em 4.17em -999.997em); top: -3.985em; left: 0em;"><span class="mi" id="MathJax-Span-95" style="font-family: MathJax_Main;">Γ</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; top: -3.807em; left: 0.658em;"><span class="texatom" id="MathJax-Span-96"><span class="mrow" id="MathJax-Span-97"><span class="mi" id="MathJax-Span-98" style="font-size: 70.7%; font-family: MathJax_Math-italic;">s</span><span class="mi" id="MathJax-Span-99" style="font-size: 70.7%; font-family: MathJax_Math-italic;">t</span><span class="mi" id="MathJax-Span-100" style="font-size: 70.7%; font-family: MathJax_Math-italic;">a</span><span class="mi" id="MathJax-Span-101" style="font-size: 70.7%; font-family: MathJax_Math-italic;">t</span></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span></span></span><span class="mo" id="MathJax-Span-102" style="font-family: MathJax_Main; padding-left: 0.301em;">=</span><span class="mo" id="MathJax-Span-103" style="font-family: MathJax_Main; padding-left: 0.301em;">(</span><span class="mfrac" id="MathJax-Span-104"><span style="display: inline-block; position: relative; width: 6.313em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(3.039em 1006.13em 4.586em -999.997em); top: -4.878em; left: 50%; margin-left: -3.092em;"><span class="mrow" id="MathJax-Span-105"><span class="mo" id="MathJax-Span-106" style="font-family: MathJax_Main;">(</span><span class="mn" id="MathJax-Span-107" style="font-family: MathJax_Main;">2</span><span class="mi" id="MathJax-Span-108" style="font-family: MathJax_Math-italic;">B</span><span class="mi" id="MathJax-Span-109" style="font-family: MathJax_Math-italic;">I<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.063em;"></span></span><span class="mo" id="MathJax-Span-110" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mfrac" id="MathJax-Span-111" style="padding-left: 0.241em;"><span style="display: inline-block; position: relative; width: 0.539em; height: 0px; margin-right: 0.122em; margin-left: 0.122em;"><span style="position: absolute; clip: rect(3.515em 1000.42em 4.17em -999.997em); top: -4.402em; left: 50%; margin-left: -0.176em;"><span class="mi" id="MathJax-Span-112" style="font-size: 70.7%; font-family: MathJax_Math-italic;">σ<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.003em;"></span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.336em 1000.36em 4.17em -999.997em); top: -3.568em; left: 50%; margin-left: -0.176em;"><span class="mn" id="MathJax-Span-113" style="font-size: 70.7%; font-family: MathJax_Main;">4</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1000.54em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 0.539em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-114" style="font-family: MathJax_Main;">)</span><span class="mo" id="MathJax-Span-115" style="font-family: MathJax_Main; padding-left: 0.241em;">∗</span><span class="mi" id="MathJax-Span-116" style="font-family: MathJax_Math-italic; padding-left: 0.241em;">α</span></span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(3.158em 1001.49em 4.17em -999.997em); top: -3.271em; left: 50%; margin-left: -0.771em;"><span class="mn" id="MathJax-Span-117" style="font-family: MathJax_Main;">100</span><span style="display: inline-block; width: 0px; height: 3.991em;"></span></span><span style="position: absolute; clip: rect(0.836em 1006.31em 1.253em -999.997em); top: -1.307em; left: 0em;"><span style="display: inline-block; overflow: hidden; vertical-align: 0em; border-top: 1.3px solid; width: 6.313em; height: 0px;"></span><span style="display: inline-block; width: 0px; height: 1.074em;"></span></span></span></span><span class="mo" id="MathJax-Span-118" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mn" id="MathJax-Span-119" style="font-family: MathJax_Main; padding-left: 0.241em;">5</span><span class="mo" id="MathJax-Span-120" style="font-family: MathJax_Main;">)</span><span class="mi" id="MathJax-Span-121" style="font-family: MathJax_Math-italic;">ϕ</span></span><span style="display: inline-block; width: 0px; height: 2.205em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.925em; border-left: 0px solid; width: 0px; height: 2.932em;"></span></span></nobr><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mi mathvariant="normal">Γ</mi><mrow class="MJX-TeXAtom-ORD"><mi>s</mi><mi>t</mi><mi>a</mi><mi>t</mi></mrow></msub><mo>=</mo><mo stretchy="false">(</mo><mfrac><mrow><mo stretchy="false">(</mo><mn>2</mn><mi>B</mi><mi>I</mi><mo>+</mo><mfrac><mi>σ</mi><mn>4</mn></mfrac><mo stretchy="false">)</mo><mo>∗</mo><mi>α</mi></mrow><mn>100</mn></mfrac><mo>+</mo><mn>5</mn><mo stretchy="false">)</mo><mi>ϕ</mi></math></span></span></div><script type="math/tex; mode=display" id="MathJax-Element-4">\Gamma_{stat} = (\frac{(2BI+\frac{\sigma}{4})*\alpha}{100} + 5)\phi</script><p>B = Base stat
I = Individual Value
<span class="MathJax_Preview" style="color: inherit; display: none;"></span><span class="MathJax" id="MathJax-Element-5-Frame" tabindex="0" style="position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;&gt;&lt;mi&gt;&amp;#x03C3;&lt;/mi&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-122" style="width: 0.658em; display: inline-block;"><span style="display: inline-block; position: relative; width: 0.539em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(1.551em 1000.54em 2.324em -999.997em); top: -2.14em; left: 0em;"><span class="mrow" id="MathJax-Span-123"><span class="mi" id="MathJax-Span-124" style="font-family: MathJax_Math-italic;">σ<span style="display: inline-block; overflow: hidden; height: 1px; width: 0.003em;"></span></span></span><span style="display: inline-block; width: 0px; height: 2.146em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.068em; border-left: 0px solid; width: 0px; height: 0.646em;"></span></span></nobr><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>σ</mi></math></span></span><script type="math/tex" id="MathJax-Element-5">\sigma</script> = Effort Value
<span class="MathJax_Preview" style="color: inherit; display: none;"></span><span class="MathJax" id="MathJax-Element-6-Frame" tabindex="0" style="position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-125" style="width: 0.836em; display: inline-block;"><span style="display: inline-block; position: relative; width: 0.658em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(1.551em 1000.6em 2.324em -999.997em); top: -2.14em; left: 0em;"><span class="mrow" id="MathJax-Span-126"><span class="mi" id="MathJax-Span-127" style="font-family: MathJax_Math-italic;">α</span></span><span style="display: inline-block; width: 0px; height: 2.146em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.068em; border-left: 0px solid; width: 0px; height: 0.718em;"></span></span></nobr><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>α</mi></math></span></span><script type="math/tex" id="MathJax-Element-6">\alpha</script> = Level
<span class="MathJax_Preview" style="color: inherit; display: none;"></span><span class="MathJax" id="MathJax-Element-7-Frame" tabindex="0" style="position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;&gt;&lt;mi&gt;&amp;#x03D5;&lt;/mi&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-128" style="width: 0.717em; display: inline-block;"><span style="display: inline-block; position: relative; width: 0.598em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(1.253em 1000.6em 2.503em -999.997em); top: -2.14em; left: 0em;"><span class="mrow" id="MathJax-Span-129"><span class="mi" id="MathJax-Span-130" style="font-family: MathJax_Math-italic;">ϕ</span></span><span style="display: inline-block; width: 0px; height: 2.146em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.282em; border-left: 0px solid; width: 0px; height: 1.218em;"></span></span></nobr><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>ϕ</mi></math></span></span><script type="math/tex" id="MathJax-Element-7">\phi</script> = Nature</p>
<p>Note: In gen III and above a feature called nature was created that determines a multiplier for 2 stats, increasing one by 1.1 and decreasing another by 0.9. I will keep it as 1 (the benign nature) in the rest of the tutorial to make comparisons between generations more accurate.</p>
<p>Now, in order to properly assess the <a href="https://en.wikipedia.org/wiki/Metagaming">meta</a> of types between generations, I will maximize all the stats for each pokemon. Using the Base stats in the given dataset I will give a max IV of 31 for each stat, have a level of 100, and distribute EV's to the highest Base stats. Since only 255 EV's can be given to any one stat, and you need 4 to accumulate a point, it is useful to get 252 (63 points) to one stat since the last 3 would be wasted. So I can give 63 points to two stats and 1 point to one other stat with a remainder of 2 EV's leftover.</p>
<p><span class="MathJax_Preview" style="color: inherit; display: none;"></span><span class="MathJax" id="MathJax-Element-8-Frame" tabindex="0" style="position: relative;" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;&gt;&lt;mn&gt;63&lt;/mn&gt;&lt;mo&gt;&amp;#x2217;&lt;/mo&gt;&lt;mn&gt;2&lt;/mn&gt;&lt;mo&gt;&amp;#x2217;&lt;/mo&gt;&lt;mn&gt;2&lt;/mn&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mn&gt;4&lt;/mn&gt;&lt;mo&gt;&amp;#x2217;&lt;/mo&gt;&lt;mn&gt;1&lt;/mn&gt;&lt;mo&gt;+&lt;/mo&gt;&lt;mn&gt;2&lt;/mn&gt;&lt;mo&gt;=&lt;/mo&gt;&lt;mn&gt;510&lt;/mn&gt;&lt;/math&gt;" role="presentation"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-131" style="width: 14.17em; display: inline-block;"><span style="display: inline-block; position: relative; width: 11.789em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(1.372em 1011.73em 2.443em -999.997em); top: -2.199em; left: 0em;"><span class="mrow" id="MathJax-Span-132"><span class="mn" id="MathJax-Span-133" style="font-family: MathJax_Main;">63</span><span class="mo" id="MathJax-Span-134" style="font-family: MathJax_Main; padding-left: 0.241em;">∗</span><span class="mn" id="MathJax-Span-135" style="font-family: MathJax_Main; padding-left: 0.241em;">2</span><span class="mo" id="MathJax-Span-136" style="font-family: MathJax_Main; padding-left: 0.241em;">∗</span><span class="mn" id="MathJax-Span-137" style="font-family: MathJax_Main; padding-left: 0.241em;">2</span><span class="mo" id="MathJax-Span-138" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mn" id="MathJax-Span-139" style="font-family: MathJax_Main; padding-left: 0.241em;">4</span><span class="mo" id="MathJax-Span-140" style="font-family: MathJax_Main; padding-left: 0.241em;">∗</span><span class="mn" id="MathJax-Span-141" style="font-family: MathJax_Main; padding-left: 0.241em;">1</span><span class="mo" id="MathJax-Span-142" style="font-family: MathJax_Main; padding-left: 0.241em;">+</span><span class="mn" id="MathJax-Span-143" style="font-family: MathJax_Main; padding-left: 0.241em;">2</span><span class="mo" id="MathJax-Span-144" style="font-family: MathJax_Main; padding-left: 0.301em;">=</span><span class="mn" id="MathJax-Span-145" style="font-family: MathJax_Main; padding-left: 0.301em;">510</span></span><span style="display: inline-block; width: 0px; height: 2.205em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.139em; border-left: 0px solid; width: 0px; height: 1.075em;"></span></span></nobr><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>63</mn><mo>∗</mo><mn>2</mn><mo>∗</mo><mn>2</mn><mo>+</mo><mn>4</mn><mo>∗</mo><mn>1</mn><mo>+</mo><mn>2</mn><mo>=</mo><mn>510</mn></math></span></span><script type="math/tex" id="MathJax-Element-8">63*2*2 + 4*1 + 2 = 510</script></p>
<p>Note: In gen I and II, there is a root function for the EV's but not in gen III onward. This is because EV's were represented as values on a larger scale, from 0-510^2. So to make calculations easier I have ommitted the root function to use the normal values instead in the following code.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[217]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># import math library</span>
<span class="kn">import</span> <span class="nn">math</span>

<span class="c1"># define parameters for max stats</span>
<span class="n">IV</span> <span class="o">=</span> <span class="mi">31</span>
<span class="n">Level</span> <span class="o">=</span> <span class="mi">100</span>


<span class="c1"># max stat calculation for gen I and II</span>
<span class="k">def</span> <span class="nf">Omax</span><span class="p">(</span><span class="n">base</span><span class="p">,</span> <span class="n">stype</span><span class="p">,</span> <span class="n">num</span><span class="p">):</span>
    
    <span class="n">EV</span> <span class="o">=</span> <span class="n">num</span>
    
    <span class="k">if</span> <span class="n">stype</span> <span class="o">==</span> <span class="s1">'HP'</span><span class="p">:</span>
        <span class="k">return</span> <span class="nb">int</span><span class="p">(((</span><span class="mi">2</span><span class="o">*</span><span class="p">(</span><span class="n">base</span> <span class="o">+</span> <span class="n">IV</span><span class="p">)</span> <span class="o">+</span> <span class="p">(</span><span class="n">EV</span> <span class="o">/</span> <span class="mi">4</span><span class="p">))</span><span class="o">*</span><span class="n">Level</span> <span class="o">/</span> <span class="mi">100</span><span class="p">)</span> <span class="o">+</span> <span class="n">Level</span> <span class="o">+</span> <span class="mi">10</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="k">return</span> <span class="nb">int</span><span class="p">(((</span><span class="mi">2</span><span class="o">*</span><span class="p">(</span><span class="n">base</span> <span class="o">+</span> <span class="n">IV</span><span class="p">)</span> <span class="o">+</span> <span class="p">(</span><span class="n">EV</span> <span class="o">/</span> <span class="mi">4</span><span class="p">))</span><span class="o">*</span><span class="n">Level</span> <span class="o">/</span> <span class="mi">100</span><span class="p">)</span> <span class="o">+</span> <span class="mi">5</span><span class="p">)</span>

<span class="c1"># max stat calculation for gen III+</span>
<span class="k">def</span> <span class="nf">Bmax</span><span class="p">(</span><span class="n">base</span><span class="p">,</span> <span class="n">stype</span><span class="p">,</span> <span class="n">num</span><span class="p">):</span>

    <span class="n">EV</span> <span class="o">=</span> <span class="n">num</span>
    
    <span class="k">if</span> <span class="n">stype</span> <span class="o">==</span> <span class="s1">'HP'</span><span class="p">:</span>
        <span class="k">return</span> <span class="nb">int</span><span class="p">(((</span><span class="mi">2</span><span class="o">*</span><span class="n">base</span> <span class="o">+</span> <span class="n">IV</span> <span class="o">+</span> <span class="p">(</span><span class="n">EV</span> <span class="o">/</span> <span class="mi">4</span><span class="p">))</span><span class="o">*</span><span class="n">Level</span> <span class="o">/</span> <span class="mi">100</span><span class="p">)</span> <span class="o">+</span> <span class="n">Level</span> <span class="o">+</span> <span class="mi">10</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="k">return</span> <span class="nb">int</span><span class="p">(((</span><span class="mi">2</span><span class="o">*</span><span class="n">base</span> <span class="o">+</span> <span class="n">IV</span> <span class="o">+</span> <span class="p">(</span><span class="n">EV</span> <span class="o">/</span> <span class="mi">4</span><span class="p">))</span><span class="o">*</span><span class="n">Level</span> <span class="o">/</span> <span class="mi">100</span><span class="p">)</span> <span class="o">+</span> <span class="mi">5</span><span class="p">)</span>
    
<span class="c1"># maximize stats for given pokemon row</span>
<span class="k">def</span> <span class="nf">max_stats</span><span class="p">(</span><span class="n">row</span><span class="p">):</span>

    <span class="n">gen</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Generation'</span><span class="p">]</span>
    <span class="n">stats</span> <span class="o">=</span> <span class="p">{}</span>
    <span class="n">stats</span><span class="p">[</span><span class="s1">'HP'</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'HP'</span><span class="p">]</span>
    <span class="n">stats</span><span class="p">[</span><span class="s1">'Attack'</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Attack'</span><span class="p">]</span>
    <span class="n">stats</span><span class="p">[</span><span class="s1">'Defense'</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Defense'</span><span class="p">]</span>
    <span class="n">stats</span><span class="p">[</span><span class="s1">'Sp. Atk'</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Sp. Atk'</span><span class="p">]</span>
    <span class="n">stats</span><span class="p">[</span><span class="s1">'Sp. Def'</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Sp. Def'</span><span class="p">]</span>
    <span class="n">stats</span><span class="p">[</span><span class="s1">'Speed'</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Speed'</span><span class="p">]</span>
    
    <span class="n">vals</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">stats</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
        <span class="n">vals</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">v</span><span class="p">)</span>
    
    <span class="n">max1</span> <span class="o">=</span> <span class="nb">max</span><span class="p">(</span><span class="n">vals</span><span class="p">)</span>
    <span class="n">vals</span><span class="o">.</span><span class="n">remove</span><span class="p">(</span><span class="n">max1</span><span class="p">)</span>
    
    <span class="n">max2</span> <span class="o">=</span> <span class="nb">max</span><span class="p">(</span><span class="n">vals</span><span class="p">)</span>
    <span class="n">vals</span><span class="o">.</span><span class="n">remove</span><span class="p">(</span><span class="n">max2</span><span class="p">)</span>
    
    <span class="n">max3</span> <span class="o">=</span> <span class="nb">max</span><span class="p">(</span><span class="n">vals</span><span class="p">)</span>
    <span class="n">vals</span><span class="o">.</span><span class="n">remove</span><span class="p">(</span><span class="n">max3</span><span class="p">)</span>
    
    <span class="n">i</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">stats</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
        
        <span class="n">c</span> <span class="o">=</span> <span class="mi">0</span>
        <span class="k">if</span> <span class="n">v</span> <span class="o">==</span> <span class="n">max1</span> <span class="ow">or</span> <span class="n">v</span> <span class="o">==</span> <span class="n">max2</span><span class="p">:</span>
            <span class="n">c</span> <span class="o">=</span> <span class="mi">252</span>
        <span class="k">elif</span> <span class="n">v</span> <span class="o">==</span> <span class="n">max3</span><span class="p">:</span>
            <span class="n">c</span> <span class="o">=</span> <span class="mi">6</span>
        <span class="k">if</span> <span class="n">c</span> <span class="o">!=</span> <span class="mi">0</span><span class="p">:</span>
            <span class="n">i</span> <span class="o">+=</span> <span class="mi">1</span>
            <span class="k">if</span> <span class="n">gen</span> <span class="o">&lt;</span> <span class="mi">3</span><span class="p">:</span>
                <span class="n">row</span><span class="p">[</span><span class="n">k</span><span class="p">]</span> <span class="o">=</span> <span class="n">Omax</span><span class="p">(</span><span class="n">v</span><span class="p">,</span><span class="n">k</span><span class="p">,</span><span class="n">c</span><span class="p">)</span>
            <span class="k">else</span><span class="p">:</span>
                <span class="n">row</span><span class="p">[</span><span class="n">k</span><span class="p">]</span> <span class="o">=</span> <span class="n">Bmax</span><span class="p">(</span><span class="n">v</span><span class="p">,</span><span class="n">k</span><span class="p">,</span><span class="n">c</span><span class="p">)</span>
        <span class="k">if</span> <span class="n">i</span> <span class="o">==</span> <span class="mi">3</span><span class="p">:</span>
            <span class="k">break</span>
    <span class="n">row</span><span class="p">[</span><span class="s1">'Total'</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">'HP'</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Attack'</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Defense'</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Sp. Atk'</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Sp. Def'</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">'Speed'</span><span class="p">]</span>
    <span class="k">return</span> <span class="n">row</span>
    
   
<span class="n">pokeDex</span> <span class="o">=</span> <span class="n">pokeDex</span><span class="o">.</span><span class="n">apply</span><span class="p">(</span><span class="k">lambda</span> <span class="n">x</span><span class="p">:</span> <span class="n">max_stats</span><span class="p">(</span><span class="n">x</span><span class="p">),</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
<span class="n">pokeDex</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">50</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[217]:</div>


<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>Total</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Bulbasaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>747</td>
      <td>45</td>
      <td>166</td>
      <td>166</td>
      <td>260</td>
      <td>65</td>
      <td>45</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Ivysaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>956</td>
      <td>60</td>
      <td>62</td>
      <td>194</td>
      <td>290</td>
      <td>290</td>
      <td>60</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>1136</td>
      <td>80</td>
      <td>82</td>
      <td>234</td>
      <td>330</td>
      <td>330</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>VenusaurMega Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>1225</td>
      <td>80</td>
      <td>100</td>
      <td>345</td>
      <td>343</td>
      <td>277</td>
      <td>80</td>
      <td>6</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Charmander</td>
      <td>Fire</td>
      <td>NaN</td>
      <td>814</td>
      <td>39</td>
      <td>172</td>
      <td>43</td>
      <td>250</td>
      <td>50</td>
      <td>260</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>5</th>
      <td>5</td>
      <td>Charmeleon</td>
      <td>Fire</td>
      <td>NaN</td>
      <td>958</td>
      <td>58</td>
      <td>64</td>
      <td>58</td>
      <td>290</td>
      <td>198</td>
      <td>290</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>6</th>
      <td>6</td>
      <td>Charizard</td>
      <td>Fire</td>
      <td>Flying</td>
      <td>1156</td>
      <td>78</td>
      <td>84</td>
      <td>78</td>
      <td>348</td>
      <td>238</td>
      <td>330</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>6</td>
      <td>CharizardMega Charizard X</td>
      <td>Fire</td>
      <td>Dragon</td>
      <td>1240</td>
      <td>78</td>
      <td>359</td>
      <td>259</td>
      <td>359</td>
      <td>85</td>
      <td>100</td>
      <td>6</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>6</td>
      <td>CharizardMega Charizard Y</td>
      <td>Fire</td>
      <td>Flying</td>
      <td>1247</td>
      <td>78</td>
      <td>245</td>
      <td>78</td>
      <td>417</td>
      <td>329</td>
      <td>100</td>
      <td>6</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>7</td>
      <td>Squirtle</td>
      <td>Water</td>
      <td>NaN</td>
      <td>821</td>
      <td>44</td>
      <td>48</td>
      <td>260</td>
      <td>168</td>
      <td>258</td>
      <td>43</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>10</th>
      <td>8</td>
      <td>Wartortle</td>
      <td>Water</td>
      <td>NaN</td>
      <td>958</td>
      <td>59</td>
      <td>63</td>
      <td>290</td>
      <td>198</td>
      <td>290</td>
      <td>58</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>11</th>
      <td>9</td>
      <td>Blastoise</td>
      <td>Water</td>
      <td>NaN</td>
      <td>1148</td>
      <td>79</td>
      <td>83</td>
      <td>330</td>
      <td>238</td>
      <td>340</td>
      <td>78</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>12</th>
      <td>9</td>
      <td>BlastoiseMega Blastoise</td>
      <td>Water</td>
      <td>NaN</td>
      <td>1235</td>
      <td>79</td>
      <td>103</td>
      <td>339</td>
      <td>369</td>
      <td>267</td>
      <td>78</td>
      <td>6</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>10</td>
      <td>Caterpie</td>
      <td>Bug</td>
      <td>NaN</td>
      <td>753</td>
      <td>325</td>
      <td>30</td>
      <td>138</td>
      <td>20</td>
      <td>20</td>
      <td>220</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>11</td>
      <td>Metapod</td>
      <td>Bug</td>
      <td>NaN</td>
      <td>773</td>
      <td>335</td>
      <td>20</td>
      <td>240</td>
      <td>25</td>
      <td>25</td>
      <td>128</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>12</td>
      <td>Butterfree</td>
      <td>Bug</td>
      <td>Flying</td>
      <td>963</td>
      <td>60</td>
      <td>45</td>
      <td>50</td>
      <td>310</td>
      <td>290</td>
      <td>208</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>13</td>
      <td>Weedle</td>
      <td>Bug</td>
      <td>Poison</td>
      <td>753</td>
      <td>315</td>
      <td>138</td>
      <td>30</td>
      <td>20</td>
      <td>20</td>
      <td>230</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>14</td>
      <td>Kakuna</td>
      <td>Bug</td>
      <td>Poison</td>
      <td>768</td>
      <td>325</td>
      <td>25</td>
      <td>230</td>
      <td>25</td>
      <td>25</td>
      <td>138</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>18</th>
      <td>15</td>
      <td>Beedrill</td>
      <td>Bug</td>
      <td>Poison</td>
      <td>968</td>
      <td>65</td>
      <td>310</td>
      <td>40</td>
      <td>45</td>
      <td>290</td>
      <td>218</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>19</th>
      <td>15</td>
      <td>BeedrillMega Beedrill</td>
      <td>Bug</td>
      <td>Poison</td>
      <td>1105</td>
      <td>65</td>
      <td>399</td>
      <td>40</td>
      <td>15</td>
      <td>197</td>
      <td>389</td>
      <td>6</td>
      <td>False</td>
    </tr>
    <tr>
      <th>20</th>
      <td>16</td>
      <td>Pidgey</td>
      <td>Normal</td>
      <td>Flying</td>
      <td>747</td>
      <td>253</td>
      <td>220</td>
      <td>148</td>
      <td>35</td>
      <td>35</td>
      <td>56</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>21</th>
      <td>17</td>
      <td>Pidgeotto</td>
      <td>Normal</td>
      <td>Flying</td>
      <td>976</td>
      <td>361</td>
      <td>188</td>
      <td>55</td>
      <td>50</td>
      <td>50</td>
      <td>272</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>22</th>
      <td>18</td>
      <td>Pidgeot</td>
      <td>Normal</td>
      <td>Flying</td>
      <td>1176</td>
      <td>401</td>
      <td>228</td>
      <td>75</td>
      <td>70</td>
      <td>70</td>
      <td>332</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>23</th>
      <td>18</td>
      <td>PidgeotMega Pidgeot</td>
      <td>Normal</td>
      <td>Flying</td>
      <td>1258</td>
      <td>308</td>
      <td>80</td>
      <td>80</td>
      <td>369</td>
      <td>80</td>
      <td>341</td>
      <td>6</td>
      <td>False</td>
    </tr>
    <tr>
      <th>24</th>
      <td>19</td>
      <td>Rattata</td>
      <td>Normal</td>
      <td>NaN</td>
      <td>645</td>
      <td>30</td>
      <td>242</td>
      <td>138</td>
      <td>25</td>
      <td>138</td>
      <td>72</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>25</th>
      <td>20</td>
      <td>Raticate</td>
      <td>Normal</td>
      <td>NaN</td>
      <td>989</td>
      <td>55</td>
      <td>292</td>
      <td>60</td>
      <td>50</td>
      <td>208</td>
      <td>324</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>26</th>
      <td>21</td>
      <td>Spearow</td>
      <td>Normal</td>
      <td>Flying</td>
      <td>865</td>
      <td>253</td>
      <td>250</td>
      <td>30</td>
      <td>31</td>
      <td>31</td>
      <td>270</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>27</th>
      <td>22</td>
      <td>Fearow</td>
      <td>Normal</td>
      <td>Flying</td>
      <td>1033</td>
      <td>303</td>
      <td>310</td>
      <td>198</td>
      <td>61</td>
      <td>61</td>
      <td>100</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>28</th>
      <td>23</td>
      <td>Ekans</td>
      <td>Poison</td>
      <td>NaN</td>
      <td>785</td>
      <td>35</td>
      <td>250</td>
      <td>44</td>
      <td>40</td>
      <td>176</td>
      <td>240</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>29</th>
      <td>24</td>
      <td>Arbok</td>
      <td>Poison</td>
      <td>NaN</td>
      <td>1010</td>
      <td>60</td>
      <td>300</td>
      <td>69</td>
      <td>65</td>
      <td>226</td>
      <td>290</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>30</th>
      <td>25</td>
      <td>Pikachu</td>
      <td>Electric</td>
      <td>NaN</td>
      <td>741</td>
      <td>35</td>
      <td>240</td>
      <td>40</td>
      <td>168</td>
      <td>168</td>
      <td>90</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>31</th>
      <td>26</td>
      <td>Raichu</td>
      <td>Electric</td>
      <td>NaN</td>
      <td>1165</td>
      <td>60</td>
      <td>310</td>
      <td>55</td>
      <td>310</td>
      <td>80</td>
      <td>350</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>32</th>
      <td>27</td>
      <td>Sandshrew</td>
      <td>Ground</td>
      <td>NaN</td>
      <td>943</td>
      <td>273</td>
      <td>280</td>
      <td>300</td>
      <td>20</td>
      <td>30</td>
      <td>40</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>33</th>
      <td>28</td>
      <td>Sandslash</td>
      <td>Ground</td>
      <td>NaN</td>
      <td>1168</td>
      <td>323</td>
      <td>330</td>
      <td>350</td>
      <td>45</td>
      <td>55</td>
      <td>65</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>34</th>
      <td>29</td>
      <td>Nidoran♀</td>
      <td>Poison</td>
      <td>NaN</td>
      <td>862</td>
      <td>345</td>
      <td>162</td>
      <td>234</td>
      <td>40</td>
      <td>40</td>
      <td>41</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>35</th>
      <td>30</td>
      <td>Nidorina</td>
      <td>Poison</td>
      <td>NaN</td>
      <td>997</td>
      <td>375</td>
      <td>192</td>
      <td>264</td>
      <td>55</td>
      <td>55</td>
      <td>56</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>36</th>
      <td>31</td>
      <td>Nidoqueen</td>
      <td>Poison</td>
      <td>Ground</td>
      <td>1207</td>
      <td>415</td>
      <td>314</td>
      <td>242</td>
      <td>75</td>
      <td>85</td>
      <td>76</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>37</th>
      <td>32</td>
      <td>Nidoran♂</td>
      <td>Poison</td>
      <td>NaN</td>
      <td>859</td>
      <td>265</td>
      <td>244</td>
      <td>40</td>
      <td>40</td>
      <td>40</td>
      <td>230</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>38</th>
      <td>33</td>
      <td>Nidorino</td>
      <td>Poison</td>
      <td>NaN</td>
      <td>996</td>
      <td>295</td>
      <td>274</td>
      <td>57</td>
      <td>55</td>
      <td>55</td>
      <td>260</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>39</th>
      <td>34</td>
      <td>Nidoking</td>
      <td>Poison</td>
      <td>Ground</td>
      <td>1167</td>
      <td>81</td>
      <td>334</td>
      <td>77</td>
      <td>300</td>
      <td>75</td>
      <td>300</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>40</th>
      <td>35</td>
      <td>Clefairy</td>
      <td>Fairy</td>
      <td>NaN</td>
      <td>951</td>
      <td>375</td>
      <td>45</td>
      <td>48</td>
      <td>188</td>
      <td>260</td>
      <td>35</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>41</th>
      <td>36</td>
      <td>Clefable</td>
      <td>Fairy</td>
      <td>NaN</td>
      <td>1196</td>
      <td>425</td>
      <td>70</td>
      <td>73</td>
      <td>320</td>
      <td>248</td>
      <td>60</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>42</th>
      <td>37</td>
      <td>Vulpix</td>
      <td>Fire</td>
      <td>NaN</td>
      <td>807</td>
      <td>38</td>
      <td>41</td>
      <td>40</td>
      <td>168</td>
      <td>260</td>
      <td>260</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>43</th>
      <td>38</td>
      <td>Ninetales</td>
      <td>Fire</td>
      <td>NaN</td>
      <td>1114</td>
      <td>73</td>
      <td>76</td>
      <td>75</td>
      <td>230</td>
      <td>330</td>
      <td>330</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>44</th>
      <td>39</td>
      <td>Jigglypuff</td>
      <td>Normal</td>
      <td>Fairy</td>
      <td>970</td>
      <td>465</td>
      <td>220</td>
      <td>20</td>
      <td>220</td>
      <td>25</td>
      <td>20</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>45</th>
      <td>40</td>
      <td>Wigglytuff</td>
      <td>Normal</td>
      <td>Fairy</td>
      <td>1163</td>
      <td>515</td>
      <td>208</td>
      <td>45</td>
      <td>300</td>
      <td>50</td>
      <td>45</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>46</th>
      <td>41</td>
      <td>Zubat</td>
      <td>Poison</td>
      <td>Flying</td>
      <td>741</td>
      <td>253</td>
      <td>220</td>
      <td>35</td>
      <td>30</td>
      <td>148</td>
      <td>55</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>47</th>
      <td>42</td>
      <td>Golbat</td>
      <td>Poison</td>
      <td>Flying</td>
      <td>1056</td>
      <td>323</td>
      <td>290</td>
      <td>70</td>
      <td>65</td>
      <td>218</td>
      <td>90</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>48</th>
      <td>43</td>
      <td>Oddish</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>843</td>
      <td>45</td>
      <td>50</td>
      <td>178</td>
      <td>280</td>
      <td>260</td>
      <td>30</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>49</th>
      <td>44</td>
      <td>Gloom</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>953</td>
      <td>60</td>
      <td>65</td>
      <td>208</td>
      <td>300</td>
      <td>280</td>
      <td>40</td>
      <td>1</td>
      <td>False</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now that we have maxed out each pokemon in their respective generations stat, we can properly compare different types within each generation and see which type, on average is the strongest. We will do this comparison using the Total column as our estimator for power levels for any given pokemon.</p>
<p>To do this, we can use the properties of pandas dataframe to group each row based on some value, function, mapping, etc... In this case we will group them by the column 'Generation'.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[218]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">gens</span> <span class="o">=</span> <span class="n">pokeDex</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="n">pokeDex</span><span class="p">[</span><span class="s1">'Generation'</span><span class="p">])</span>
<span class="k">for</span> <span class="n">name</span> <span class="ow">in</span> <span class="n">gens</span><span class="o">.</span><span class="n">groups</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">name</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>1
2
3
4
5
6
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Here we can see that we have 6 groups, corresponding to each gen. Next, in order to compute the average power level of each type in each group, we can group by the 'Generation' and 'Type 1' columns. This will split each gen into subcategories corresponding to each pokemons' main type. We can also then find the average by simply calling the mean function on the 'Total' column for each of these groups.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[219]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">gen_type</span> <span class="o">=</span> <span class="n">pokeDex</span><span class="o">.</span><span class="n">groupby</span><span class="p">([</span><span class="s1">'Generation'</span><span class="p">,</span><span class="s1">'Type 1'</span><span class="p">])</span>
<span class="k">for</span> <span class="n">name</span><span class="p">,</span> <span class="n">group</span> <span class="ow">in</span> <span class="n">gen_type</span><span class="o">.</span><span class="n">groups</span><span class="p">:</span>
    <span class="n">mean</span> <span class="o">=</span> <span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
    <span class="nb">print</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">),</span> <span class="s1">':'</span> <span class="p">,</span> <span class="n">mean</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>(1, 'Bug') : 921.6666666666666
(1, 'Dragon') : 1070.6666666666667
(1, 'Electric') : 1056.0
(1, 'Fairy') : 1073.5
(1, 'Fighting') : 1046.7142857142858
(1, 'Fire') : 1030.1666666666667
(1, 'Ghost') : 962.3333333333334
(1, 'Grass') : 1036.25
(1, 'Ground') : 1038.5
(1, 'Ice') : 1189.0
(1, 'Normal') : 1007.8636363636364
(1, 'Poison') : 992.2857142857143
(1, 'Psychic') : 1128.5
(1, 'Rock') : 1073.3333333333333
(1, 'Water') : 1022.9285714285714
(2, 'Bug') : 1056.3
(2, 'Dark') : 1075.6
(2, 'Electric') : 986.0
(2, 'Fairy') : 927.6
(2, 'Fighting') : 977.5
(2, 'Fire') : 1067.375
(2, 'Ghost') : 1080.0
(2, 'Grass') : 936.375
(2, 'Ground') : 1107.0
(2, 'Ice') : 955.25
(2, 'Normal') : 1044.2666666666667
(2, 'Poison') : 1273.0
(2, 'Psychic') : 1138.142857142857
(2, 'Rock') : 1148.25
(2, 'Steel') : 1193.0
(2, 'Water') : 1087.9444444444443
(3, 'Bug') : 796.8333333333334
(3, 'Dark') : 917.75
(3, 'Dragon') : 1119.857142857143
(3, 'Electric') : 872.5
(3, 'Fighting') : 890.25
(3, 'Fire') : 956.1666666666666
(3, 'Ghost') : 859.0
(3, 'Grass') : 925.9166666666666
(3, 'Ground') : 990.0
(3, 'Ice') : 1034.3333333333333
(3, 'Normal') : 928.9444444444445
(3, 'Poison') : 1028.6666666666667
(3, 'Psychic') : 1021.9090909090909
(3, 'Rock') : 989.75
(3, 'Steel') : 1050.7777777777778
(3, 'Water') : 967.7916666666666
(4, 'Bug') : 869.1
(4, 'Dark') : 1112.6666666666667
(4, 'Dragon') : 1027.6666666666667
(4, 'Electric') : 1027.5
(4, 'Fairy') : 1110.0
(4, 'Fighting') : 894.0
(4, 'Fire') : 1052.0
(4, 'Ghost') : 1171.0
(4, 'Grass') : 1011.2142857142857
(4, 'Ground') : 1118.25
(4, 'Ice') : 1110.6666666666667
(4, 'Normal') : 1028.0588235294117
(4, 'Poison') : 924.0
(4, 'Psychic') : 1071.2857142857142
(4, 'Rock') : 1002.1666666666666
(4, 'Steel') : 1097.3333333333333
(4, 'Water') : 982.3076923076923
(5, 'Bug') : 930.8333333333334
(5, 'Dark') : 961.0
(5, 'Dragon') : 1208.6666666666667
(5, 'Electric') : 969.25
(5, 'Fighting') : 1015.7142857142857
(5, 'Fire') : 1037.3333333333333
(5, 'Flying') : 1156.0
(5, 'Ghost') : 936.4
(5, 'Grass') : 949.4
(5, 'Ground') : 1034.8
(5, 'Ice') : 924.6666666666666
(5, 'Normal') : 995.7222222222222
(5, 'Poison') : 922.5
(5, 'Psychic') : 966.2857142857143
(5, 'Rock') : 1059.0
(5, 'Steel') : 990.75
(5, 'Water') : 1009.7777777777778
(6, 'Bug') : 1019.4285714285714
(6, 'Dark') : 1104.8333333333333
(6, 'Dragon') : 1220.4
(6, 'Electric') : 1004.8
(6, 'Fairy') : 1058.6666666666667
(6, 'Fighting') : 1073.8
(6, 'Fire') : 1081.75
(6, 'Flying') : 914.0
(6, 'Ghost') : 971.4166666666666
(6, 'Grass') : 1089.5555555555557
(6, 'Ground') : 1495.0
(6, 'Ice') : 1086.0
(6, 'Normal') : 1050.75
(6, 'Poison') : 918.0
(6, 'Psychic') : 1215.5
(6, 'Rock') : 1096.8181818181818
(6, 'Steel') : 1146.7777777777778
(6, 'Water') : 1115.6363636363637
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>This is now a list of average total power for each type in each generation. For a more natural look, we can plot this information as a bar graph to compare the rankings of types within each gen.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[222]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># create plot object</span>
<span class="n">bar_width</span> <span class="o">=</span> <span class="mf">0.5</span>
<span class="n">opacity</span> <span class="o">=</span> <span class="mf">0.8</span>

<span class="c1"># index for each type per gen</span>
<span class="n">gen1_types</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen1_means</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen2_types</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen2_means</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen3_types</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen3_means</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen4_types</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen4_means</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen5_types</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen5_means</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen6_types</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">gen6_means</span> <span class="o">=</span> <span class="p">[]</span>

<span class="c1"># sort mean of each type and type per gen</span>
<span class="k">for</span> <span class="n">name</span><span class="p">,</span> <span class="n">group</span> <span class="ow">in</span> <span class="n">gen_type</span><span class="o">.</span><span class="n">groups</span><span class="p">:</span>
    <span class="k">if</span> <span class="n">name</span> <span class="o">==</span> <span class="mi">1</span><span class="p">:</span>
        <span class="n">gen1_types</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">group</span><span class="p">)</span>
        <span class="n">gen1_means</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
    <span class="k">elif</span> <span class="n">name</span> <span class="o">==</span> <span class="mi">2</span><span class="p">:</span>
        <span class="n">gen2_types</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">group</span><span class="p">)</span>
        <span class="n">gen2_means</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
    <span class="k">elif</span> <span class="n">name</span> <span class="o">==</span> <span class="mi">3</span><span class="p">:</span>
        <span class="n">gen3_types</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">group</span><span class="p">)</span>
        <span class="n">gen3_means</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
    <span class="k">elif</span> <span class="n">name</span> <span class="o">==</span> <span class="mi">4</span><span class="p">:</span>
        <span class="n">gen4_types</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">group</span><span class="p">)</span>
        <span class="n">gen4_means</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
    <span class="k">elif</span> <span class="n">name</span> <span class="o">==</span> <span class="mi">5</span><span class="p">:</span>
        <span class="n">gen5_types</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">group</span><span class="p">)</span>
        <span class="n">gen5_means</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
    <span class="k">elif</span> <span class="n">name</span> <span class="o">==</span> <span class="mi">6</span><span class="p">:</span>
        <span class="n">gen6_types</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">group</span><span class="p">)</span>
        <span class="n">gen6_means</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>

<span class="c1"># plotting each type for each gen</span>
<span class="k">for</span> <span class="n">x</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">7</span><span class="p">):</span>
    <span class="n">f</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">()</span>
    <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">1</span><span class="p">:</span>
        <span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen1_means</span><span class="p">)),</span> <span class="n">gen1_means</span><span class="p">,</span> <span class="n">bar_width</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="n">opacity</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'R'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">'Generation 1 Type Comparisons'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticks</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen1_means</span><span class="p">)</span> <span class="o">+</span> <span class="n">bar_width</span> <span class="o">/</span> <span class="mi">2</span><span class="p">))</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">gen1_types</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="s1">'vertical'</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">2</span><span class="p">:</span>
        <span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen2_means</span><span class="p">)),</span> <span class="n">gen2_means</span><span class="p">,</span> <span class="n">bar_width</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="n">opacity</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'G'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">'Generation 2 Type Comparisons'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticks</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen2_means</span><span class="p">)</span> <span class="o">+</span> <span class="n">bar_width</span> <span class="o">/</span> <span class="mi">2</span><span class="p">))</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">gen2_types</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="s1">'vertical'</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">3</span><span class="p">:</span>
        <span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen3_means</span><span class="p">)),</span> <span class="n">gen3_means</span><span class="p">,</span> <span class="n">bar_width</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="n">opacity</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'B'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">'Generation 3 Type Comparisons'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticks</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen3_means</span><span class="p">)</span> <span class="o">+</span> <span class="n">bar_width</span> <span class="o">/</span> <span class="mi">2</span><span class="p">))</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">gen3_types</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="s1">'vertical'</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">4</span><span class="p">:</span>
        <span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen4_means</span><span class="p">)),</span> <span class="n">gen4_means</span><span class="p">,</span> <span class="n">bar_width</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="n">opacity</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'Y'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">'Generation 4 Type Comparisons'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticks</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen4_means</span><span class="p">)</span> <span class="o">+</span> <span class="n">bar_width</span> <span class="o">/</span> <span class="mi">2</span><span class="p">))</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">gen4_types</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="s1">'vertical'</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">5</span><span class="p">:</span>
        <span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen5_means</span><span class="p">)),</span> <span class="n">gen5_means</span><span class="p">,</span> <span class="n">bar_width</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="n">opacity</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'Cyan'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">'Generation 5 Type Comparisons'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticks</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen5_means</span><span class="p">)</span> <span class="o">+</span> <span class="n">bar_width</span> <span class="o">/</span> <span class="mi">2</span><span class="p">))</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">gen5_types</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="s1">'vertical'</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">x</span> <span class="o">==</span> <span class="mi">6</span><span class="p">:</span>
        <span class="n">plt</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen6_means</span><span class="p">)),</span> <span class="n">gen6_means</span><span class="p">,</span> <span class="n">bar_width</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="n">opacity</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">'Purple'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">'Generation 6 Type Comparisons'</span><span class="p">)</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticks</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">gen6_means</span><span class="p">)</span> <span class="o">+</span> <span class="n">bar_width</span> <span class="o">/</span> <span class="mi">2</span><span class="p">))</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">gen6_types</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="s1">'vertical'</span><span class="p">)</span>
                      
    <span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">'Average Total Power'</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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%0ADHwYuDf6Xg/+du6GuiPws4j4taR9y25cp52lhGFN1VTPUePkLyKukHQ76QpUwEER8WyF7V8k1TTs%0ACrO1ny0saeE6Pcn6wm0eLRS7v0p6ICLeX1hXeebZvN0ogIiY3oe4HgTWa3Tvy90i746ItcrGlc/o%0ANiBNFPjfhVUvA9dExPMVY1ogmqamb7WslzKKdcC1Pt+m8t7bwYbS0cw5XuS6GuUsROoZN4w0pchi%0AwFl9jVM1u493kqTrSNP51x0DUyzrWtLJ2T6kk6JppO94pSnIJV0JfCZmH9h3bkRUnhdKaT659Zl9%0Adu17I+LQiuVcHU0zRLdaVqKc7UkJu9F+tiLwQNX2s77ylUdrxX+C5q6wpbOtUqPE0aQrjmF50dvA%0ASVUbprOzSJMqXpRfbw+cnQ9M95cpIPfMulvSH0g9vt7JsQ6n3qyjN5GvGnpZ1jasHp7XdYuku0gD%0AKC+rezYs6fukA8UkZu/uWSl55M/2ktwW8y41unm2Uav7eIc12hcuo4/tC6TP+3OkWZGfVpqM9Pga%0A5YxqJI4cy/OqN0MzEfENpXtybJ4XjYuIP5TdXtICpOlxlspJrDjF/+gaIX2HDrSf9ZWTR2sfkPQS%0A6Y+8YH5Ofr1Az5vN4RBSveYHI+JxAKV7e5ws6ZCI+N8qQUXEtyVdDmyaFx0QERPz86oD/q4gdT1s%0ATNexYF62aY9bFGjWPS8WlLQhs/9DjKwYS7vPu07d+Rqk3+3zwE8kjQdOi4iHK5azE7Bm5MFhdUUa%0AV/OupMWi5uC5hqYeacNJ3a3H96XMDng8P/rcvpCrBX9ceP036lXJvaPZZ8RekT6cmES6YdPvc1nD%0AJO0WEWf1slnDF4GDSVcKxcGcL5OqyKvqSPtZXzl5tBARwztU1B6k7oIz6zUjTQu+O+lAXSl55O3/%0AojSP/wIAqj9n1gKNtpNc7itK/c7LKt7zoniGWfmeFx38vBvlBWmW4CvzWdmZpNmQ7yaNGbi5ZFGP%0AAe+hQo+YNl4B7s3VKcVxNV+tWE6xR1rt7uOdkq+qFomIr/exnOY5qVT8WeME4pukGbGvzWX8M6mN%0ArkpMi5JmHh5NGg/VmHn668DdzBr/05ubSAl+54g4SdJepDbPv5IawatqtJ9dT9/az/rEbR5dpDZ3%0AZWu3rk15HRkrkMu6EfhKo1eU0n3WfxoRH65YTifvedERStOI7E5K3s+QeuxcTGrrOb+37q6STiId%0A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%0AAABJRU5ErkJggg==">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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%0ARK5CYII=">
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id="analysis"></a></p>
<h1 id="Analysis-and-Machine-Learning">Analysis and Machine Learning<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Analysis-and-Machine-Learning">¶</a></h1><p>In order to make games that are repeated interations of their predecessors, something new has to be introduced. In pokemon, what changes is which types are the most powerful from generation to generation. This makes it so the in-game, and real-world competitive gaming competition doesn't turn stale and instead becomes dynamic.</p>
<p>Now that we have seen the meta for each of the generations, we will observe the change of the meta over the generations. We will do this by finding the strongest of each type per generation and seeing how they all changed from generation to generation. My null hypothesis will be that there is no significant difference in power level from generation to generation and my alternative will be that there is. We can decide whether or not to reject the null by creating a linear regression line for each of the strongest types from each generation and plot the average power level over the generations. Evidence for rejecting the null will produce lines with positive or negative values. If we obtain relatively straight lines, there will not be enough evidence to reject the null.</p>
<p>From visual inspection it looks as though this is the case:</p>
<p>Gen 1: Ice</p>
<p>Gen 2: Poison</p>
<p>Gen 3: Dragon</p>
<p>Gen 4: Ghost</p>
<p>Gen 5: Dragon</p>
<p>Gen 6: Ground</p>
<p>We can then confirm by finding the actual values and comparing.</p>
<p>Note: There are some types that do not appear in certain generations, but from our data, all of the strongest types belong to all generations. So this issue will not come into play for our analysis</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[175]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">strongest</span> <span class="o">=</span> <span class="p">{}</span>

<span class="k">for</span> <span class="n">name</span><span class="p">,</span> <span class="n">group</span> <span class="ow">in</span> <span class="n">gen_type</span><span class="o">.</span><span class="n">groups</span><span class="p">:</span>
    <span class="n">mean</span> <span class="o">=</span> <span class="n">gen_type</span><span class="o">.</span><span class="n">get_group</span><span class="p">((</span><span class="n">name</span><span class="p">,</span> <span class="n">group</span><span class="p">))[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
    <span class="k">if</span> <span class="n">name</span> <span class="ow">in</span> <span class="n">strongest</span><span class="p">:</span>
        <span class="k">if</span> <span class="n">strongest</span><span class="p">[</span><span class="n">name</span><span class="p">][</span><span class="mi">1</span><span class="p">]</span> <span class="o">&lt;</span> <span class="n">mean</span><span class="p">:</span>
            <span class="n">strongest</span><span class="p">[</span><span class="n">name</span><span class="p">]</span> <span class="o">=</span> <span class="p">[</span><span class="n">group</span><span class="p">,</span> <span class="n">mean</span><span class="p">]</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">strongest</span><span class="p">[</span><span class="n">name</span><span class="p">]</span> <span class="o">=</span> <span class="p">[</span><span class="n">group</span><span class="p">,</span> <span class="n">mean</span><span class="p">]</span>
        
<span class="n">strongest</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt output_prompt">Out[175]:</div>



<div class="output_text output_subarea output_execute_result">
<pre>{1: ['Ice', 1189.0],
 2: ['Poison', 1273.0],
 3: ['Dragon', 1119.857142857143],
 4: ['Ghost', 1171.0],
 5: ['Dragon', 1208.6666666666667],
 6: ['Ground', 1495.0]}</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>As we suspected from our visual inspection, the strongest types are Ice, Poison, Dragon, Ghost, and Ground.</p>
<p>Next, I will calculate a new Total power level for each of the strongest Base stats for each pokemon. I will do this by creating a fucntion to calculate the new stat with either Oak's or Birch's Theorem. Then after calculating these values, we can using them for the linear regression analysis with help from the scipy and sklearn libraries.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[294]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">scipy</span> <span class="k">import</span> <span class="n">stats</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="k">import</span> <span class="n">linear_model</span> <span class="k">as</span> <span class="n">lin</span>

<span class="n">strongest_types</span> <span class="o">=</span> <span class="p">[]</span>

<span class="n">strongest_values</span> <span class="o">=</span> <span class="p">[{},{},{},{},{},{}]</span>

<span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">strongest</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">v</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span> <span class="ow">not</span> <span class="ow">in</span> <span class="n">strongest_types</span><span class="p">:</span>
        <span class="n">strongest_types</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">v</span><span class="p">[</span><span class="mi">0</span><span class="p">])</span>
        <span class="k">for</span> <span class="n">dic</span> <span class="ow">in</span> <span class="n">strongest_values</span><span class="p">:</span>
            <span class="n">dic</span><span class="p">[</span><span class="n">v</span><span class="p">[</span><span class="mi">0</span><span class="p">]]</span> <span class="o">=</span> <span class="p">[]</span>

<span class="k">for</span> <span class="n">gen</span> <span class="ow">in</span> <span class="n">gens</span><span class="o">.</span><span class="n">groups</span><span class="p">:</span>
    <span class="n">data</span> <span class="o">=</span> <span class="n">gens</span><span class="o">.</span><span class="n">get_group</span><span class="p">(</span><span class="n">gen</span><span class="p">)</span>
    <span class="n">i</span> <span class="o">=</span> <span class="n">gen</span><span class="o">-</span><span class="mi">1</span>
    <span class="n">dic</span> <span class="o">=</span> <span class="n">strongest_values</span><span class="p">[</span><span class="n">i</span><span class="p">]</span>
    <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">dic</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
        <span class="n">d1</span> <span class="o">=</span> <span class="n">data</span><span class="p">[</span><span class="n">data</span><span class="p">[</span><span class="s1">'Type 1'</span><span class="p">]</span> <span class="o">==</span> <span class="n">k</span><span class="p">]</span>
        <span class="n">dic</span><span class="p">[</span><span class="n">k</span><span class="p">]</span> <span class="o">=</span> <span class="n">d1</span><span class="p">[</span><span class="s1">'Total'</span><span class="p">]</span><span class="o">.</span><span class="n">tolist</span><span class="p">()</span>
        
<span class="k">def</span> <span class="nf">append_data</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">d</span><span class="p">,</span> <span class="n">t</span><span class="p">):</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">d</span><span class="p">:</span>
        <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">i</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
            <span class="k">if</span> <span class="n">k</span> <span class="o">==</span> <span class="n">t</span><span class="p">:</span>
                <span class="n">x</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">v</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">x</span>

<span class="n">index</span> <span class="o">=</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">,</span><span class="mi">6</span><span class="p">]</span>

            
<span class="k">for</span> <span class="n">t</span> <span class="ow">in</span> <span class="n">strongest_types</span><span class="p">:</span>
    <span class="n">f</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">()</span>
    <span class="n">c</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">y</span> <span class="o">=</span> <span class="p">[]</span>
    <span class="n">x</span> <span class="o">=</span> <span class="p">[]</span>

    <span class="k">if</span> <span class="n">t</span> <span class="o">==</span> <span class="s1">'Ice'</span><span class="p">:</span>

        <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">strongest_values</span><span class="p">:</span>
            <span class="n">c</span> <span class="o">+=</span> <span class="mi">1</span>
            <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">i</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
                <span class="k">if</span> <span class="n">k</span> <span class="o">==</span> <span class="n">t</span><span class="p">:</span>
                    <span class="n">y</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">v</span><span class="p">)</span>
                    <span class="n">z</span> <span class="o">=</span> <span class="p">[</span><span class="n">c</span> <span class="k">for</span> <span class="n">b</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">v</span><span class="p">))]</span>
                    <span class="n">x</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">z</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">t</span> <span class="o">==</span> <span class="s1">'Poison'</span><span class="p">:</span>
        <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">strongest_values</span><span class="p">:</span>
            <span class="n">c</span> <span class="o">+=</span> <span class="mi">1</span>
            <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">i</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
                <span class="k">if</span> <span class="n">k</span> <span class="o">==</span> <span class="n">t</span><span class="p">:</span>
                    <span class="n">y</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">v</span><span class="p">)</span>
                    <span class="n">z</span> <span class="o">=</span> <span class="p">[</span><span class="n">c</span> <span class="k">for</span> <span class="n">b</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">v</span><span class="p">))]</span>
                    <span class="n">x</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">z</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">t</span> <span class="o">==</span> <span class="s1">'Dragon'</span><span class="p">:</span>
        <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">strongest_values</span><span class="p">:</span>
            <span class="n">c</span> <span class="o">+=</span> <span class="mi">1</span>
            <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">i</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
                <span class="k">if</span> <span class="n">k</span> <span class="o">==</span> <span class="n">t</span><span class="p">:</span>
                    <span class="n">y</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">v</span><span class="p">)</span>
                    <span class="n">z</span> <span class="o">=</span> <span class="p">[</span><span class="n">c</span> <span class="k">for</span> <span class="n">b</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">v</span><span class="p">))]</span>
                    <span class="n">x</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">z</span><span class="p">)</span>

    <span class="k">if</span> <span class="n">t</span> <span class="o">==</span> <span class="s1">'Ghost'</span><span class="p">:</span>
        <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">strongest_values</span><span class="p">:</span>
            <span class="n">c</span> <span class="o">+=</span> <span class="mi">1</span>
            <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">i</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
                <span class="k">if</span> <span class="n">k</span> <span class="o">==</span> <span class="n">t</span><span class="p">:</span>
                    <span class="n">y</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">v</span><span class="p">)</span>
                    <span class="n">z</span> <span class="o">=</span> <span class="p">[</span><span class="n">c</span> <span class="k">for</span> <span class="n">b</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">v</span><span class="p">))]</span>
                    <span class="n">x</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">z</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">t</span> <span class="o">==</span> <span class="s1">'Ground'</span><span class="p">:</span>
        <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">strongest_values</span><span class="p">:</span>
            <span class="n">c</span> <span class="o">+=</span> <span class="mi">1</span>
            <span class="k">for</span> <span class="n">k</span><span class="p">,</span><span class="n">v</span> <span class="ow">in</span> <span class="n">i</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
                <span class="k">if</span> <span class="n">k</span> <span class="o">==</span> <span class="n">t</span><span class="p">:</span>
                    <span class="n">y</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">v</span><span class="p">)</span>
                    <span class="n">z</span> <span class="o">=</span> <span class="p">[</span><span class="n">c</span> <span class="k">for</span> <span class="n">b</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">v</span><span class="p">))]</span>
                    <span class="n">x</span><span class="o">.</span><span class="n">extend</span><span class="p">(</span><span class="n">z</span><span class="p">)</span>

    <span class="n">slope</span><span class="p">,</span> <span class="n">intercept</span><span class="p">,</span> <span class="n">r_value</span><span class="p">,</span> <span class="n">p_value</span><span class="p">,</span> <span class="n">std_err</span> <span class="o">=</span> <span class="n">stats</span><span class="o">.</span><span class="n">linregress</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
    <span class="n">line</span> <span class="o">=</span> <span class="n">slope</span><span class="o">*</span><span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">x</span><span class="p">)</span> <span class="o">+</span> <span class="n">intercept</span>
        
    <span class="n">ax</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span><span class="p">,</span><span class="n">y</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="n">t</span><span class="o">+</span><span class="s1">' Type'</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s1">'Generation'</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">'Total Power'</span><span class="p">)</span>
        
    <span class="n">x1</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
    <span class="n">y1</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">y</span><span class="p">)</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x1</span><span class="p">,</span><span class="n">y1</span><span class="p">,</span><span class="s1">'o'</span><span class="p">,</span><span class="n">x</span><span class="p">,</span><span class="n">line</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">'slope: '</span><span class="p">,</span> <span class="n">slope</span><span class="p">,</span><span class="s1">'intercept: '</span><span class="p">,</span> <span class="n">intercept</span><span class="p">,</span><span class="s1">'r_value: '</span><span class="p">,</span> <span class="n">r_value</span><span class="p">,</span><span class="s1">'p_value: '</span><span class="p">,</span> <span class="n">p_value</span><span class="p">,</span><span class="s1">'std_err: '</span><span class="p">,</span> <span class="n">std_err</span><span class="p">)</span>
            


<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">
<div class="prompt"></div>

<div class="output_subarea output_stream output_stdout output_text">
<pre>slope:  -13.3192771084 intercept:  1071.4623494 r_value:  -0.118239093821 p_value:  0.58213778316 std_err:  23.8479458595
slope:  -18.7826086957 intercept:  1028.91304348 r_value:  -0.213219102142 p_value:  0.275978442679 std_err:  16.8787254902
slope:  34.6377161238 intercept:  1010.37756333 r_value:  0.236563537057 p_value:  0.192384400369 std_err:  25.973799492
slope:  -2.86183206107 intercept:  1010.79312977 r_value:  -0.0228629579413 p_value:  0.901154675328 std_err:  22.8474409854
slope:  14.4854651163 intercept:  1011.82848837 r_value:  0.13398138845 p_value:  0.464739499992 std_err:  19.5611290968
</pre>
</div>
</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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%0AD6mDSh13fjG7AAAAAElFTkSuQmCC">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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%0AeERED/C1BvXFrHDecW1WH3lyHrdKOgu4Fni51BgR3YX1qkmcSG19Jx09eYecR3m7meWXJ3icnH7+%0ADRCA0s8pRXWqGZxIbQ+l/5f+JcFs93iTYHLwgpsqznt3SDzyrePr2TUzswGrbpsEJQ2XNF/SJen5%0AmyV9qB6dHEicSDUzyy/PUt3L0nXvTc/XARcU1qMmcSLVzCy/PMFjWkRcAGwBiIhXyPIeLcWlq83M%0A8suTMH9N0jCyJDmpZPprhfaqCZxINbPBrNGrRXeZMJd0HDAfOJSsJPqfA6dFxO2F9aoOXFXXzNpF%0A79WiJf25d0vdEuYR8e/AJ4HTgRuAmQM9cJiZtZNmlN3Z5bSVpMuBXwJ3RcSawnpiZoVox82v7fad%0Am7FaNE/C/GrgIOCfJT0i6VpJ8wrrkZnVTWk6o/SPSGnz6zlLVjW5Z8Vpx+/cjNWieaatbiO7hezf%0AAguBdwJ/XViPzKxu2rGKcDt+52asFs0zbXULsA9wD3AXMCsi1hXWIzOrm3bc/NqO37kZq0XzLNX9%0APXAkMA14GnhK0jMR0XLLdc1aTYdUtexOq2rH7wxZAGlkXifPtNUXI+I9wF8CLwJXpZ9mNsC14+bX%0AdvzOzZBn2upMstIk7yArTXIl2fSVmQ1w7bj5tR2/czPk2SQ4nyxY3DOYpqr6s0mw3Zb3mZn1lneT%0A4C5HHhFxoaTpwGeVzRneFRGr69DHAcX38zAzyy/PtNU8YB6wJDUtlvT9iLi40J41WGkZ33Q9xleG%0A/JSn4w2sj/14+p79YcZxMGoCjJ4Aw0Y3uadmZs2XZ7XV58hKkrwEIOkC4NdAn8FD0mXACcCGiDgs%0Ate1HdjvbqcBjwIkR8Xw6twA4DegBvhQRt6T2o4DLgeHATcCXo4A7WJVWZ4zgVQ7Uc7xtj0cYo3Sn%0A3at+uP3CvUbB6PFZIBk9EUaVHY8en/3ce39o8ZUdNnh4OtaKkCd4iB2r6G4hX0n2y4F/Ikuwl8wH%0Abk9TYfPT87MlHQrMBaYDE4CfSXpLRPQAl5DV1VpOFjyOIyvQWFel5X13x1v58GvfAmAorzFeL3DH%0AmYdA9zro7oLu9ennOnjkF/DSUxCv93qzoTDqwBRQJvR6pIAzchx05PnPb9Z/no61ouT51+sqYLmk%0A69PzjwJX7OpFEXGnpKm9mmcDx6TjK4A7gLNT+zURsRl4VNIaYKakx4DREbEMQNKVwBwKCB4nHT15%0A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">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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%0AAElFTkSuQmCC">
</div>

</div>

<div class="output_area">
<div class="prompt"></div>



<div class="output_png output_subarea ">
<img src="data:image/png;base64,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">
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>If we are to assume a confidence interval of 95% with an <span class="MathJax_Preview" style="color: inherit; display: none;"></span><span class="MathJax" id="MathJax-Element-9-Frame" tabindex="0" data-mathml="&lt;math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;&gt;&lt;mi&gt;&amp;#x03B1;&lt;/mi&gt;&lt;/math&gt;" role="presentation" style="position: relative;"><nobr aria-hidden="true"><span class="math" id="MathJax-Span-146" style="width: 0.836em; display: inline-block;"><span style="display: inline-block; position: relative; width: 0.658em; height: 0px; font-size: 120%;"><span style="position: absolute; clip: rect(1.551em 1000.6em 2.324em -999.997em); top: -2.14em; left: 0em;"><span class="mrow" id="MathJax-Span-147"><span class="mi" id="MathJax-Span-148" style="font-family: MathJax_Math-italic;">α</span></span><span style="display: inline-block; width: 0px; height: 2.146em;"></span></span></span><span style="display: inline-block; overflow: hidden; vertical-align: -0.068em; border-left: 0px solid; width: 0px; height: 0.718em;"></span></span></nobr><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>α</mi></math></span></span><script type="math/tex" id="MathJax-Element-9">\alpha</script> of 0.05, the p-value from each of the models does not provide sufficient evidence to reject the null hypothesis. Therefore we cannot conclude that, on average, there is a significant difference in power level of the strongest types from each generation from generation to generation.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id="conclusion"></a></p>
<h1 id="Conclusion">Conclusion<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Conclusion">¶</a></h1><p>Based on the linear regression models, even though the stronest types can change from generation to generation, there is not a significant power level difference between the generations. From our first models that compared different types within each generation, we can see that even though there might be some differences between average power levels, the distribution is quite uniform. For generation 6, ground typed looked significantly different but there was only one data point, effectively skewing the graph.</p>
<p>In actuality, this conclusion makes some sense. If the makers of the pokemon video games wish to keep the game fun and interesting, there must be new metas created. And although the meta changes from generation to generation, the difference between the strongest types between generations do not have a significant difference in power levels. This is a good approach to game making since if one type becomes too powerful, it must be fixed by either lowering the overall power level or increasing the power level of other types. The game makers have achieved a good overall fair system for introducing new pokemon every generation without completely overpowering or underpowering the different types.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id="future"></a></p>
<h1 id="Future-Outlook">Future Outlook<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Future-Outlook">¶</a></h1><p>Our analysis looked at only the main type (Type 1) of each pokemon, even though there exist some pokemon with dual types. This might have led to skewed or statistically unsound results. The issue here is that when comparing average power levels, using a pokemon in more than one computation for a given type also seems statistically unsound. A better approach might be to classify each dual type as their own category, but this then leads to the problems of taking them out of other categories creating an effect of having fewer data points for any given type. This problem of finding the correct way to measure power levels based on types and considering dual types is still an issue and is worth looking into for future studies.</p>
<p>Additionally, the analysis provided does not consider type advantages and weaknesses. For example, if a fire type was the strongest for any given generation, but there was a water type (water is super-effective against fire, and fire not-effective against water), that was close behind in terms of power level, it is arguable to say that the water type should be the strongest. This serves as another way for the game makers to add complexity to the game. Since if one type is too strong in one generation, they can introduce a new type or even a dual typed pokemon to counter this without breaking the meta. For example, in gen 1, it is known that psychic types were some of the most powerful pokemon, but in gen 2, dark types were introduced. Since psychic types were weak against dark types, they weren't as powerful before in the newer generations. But to make sure dark types weren't overpowered, they were weak against fighting types and fighting types were weak against psychic types. This effectively created an advantage triangle and made sure that new types introduced weren't overpowered. In future studies it would also be appropriate to consider the type advatanges as well.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><a id="sources"></a></p>
<h1 id="Sources">Sources<a class="anchor-link" href="file:///C:/Users/PC/Downloads/Final+Project%20(1).html#Sources">¶</a></h1><p>Here is a list of sources used in this tutorial:</p>
<p><a href="https://anaconda.org/">Anaconda</a></p>
<p><a href="http://jupyter.org/">Jupyter Notebook</a></p>
<p><a href="http://matplotlib.org/">Matplotlib</a></p>
<p><a href="http://www.numpy.org/">Numpy</a></p>
<p><a href="https://pandas.pydata.org/">Pandas</a></p>
<p><a href="https://www.scipy.org/">Scipy</a></p>
<p><a href="http://scikit-learn.org/stable/">Scikit-learn</a></p>
<p><a href="https://docs.python.org/3.4/library/re.html">Regular Expressions</a></p>
<p><a href="https://www.kaggle.com/abcsds/pokemon">Pokemon Database</a></p>
<p><a href="https://bulbapedia.bulbagarden.net/wiki/Main_Page">Bulbapedia</a></p>
<p><a href="https://pokemondb.net/ev">Pokemondb</a></p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

</div>
</div>
</div>

</div>
    </div>
  </div>


 



<div style="position: absolute; width: 0px; height: 0px; overflow: hidden; padding: 0px; border: 0px; margin: 0px;"><div id="MathJax_Font_Test" style="position: absolute; visibility: hidden; top: 0px; left: 0px; width: auto; padding: 0px; border: 0px; margin: 0px; white-space: nowrap; text-align: left; text-indent: 0px; text-transform: none; line-height: normal; letter-spacing: normal; word-spacing: normal; font-size: 40px; font-weight: normal; font-style: normal; font-family: MathJax_Main, sans-serif;"></div></div></body></html>
