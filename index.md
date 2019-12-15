<html>
<head><meta charset="utf-8" />

<title>Final Project</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



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
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
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
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
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
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
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
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
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
.fa-facebook-f:before,
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
.fa-feed:before,
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
.fa-gittip:before,
.fa-gratipay:before {
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
.fa-pied-piper-pp:before {
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
.fa-resistance:before,
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
.fa-y-combinator-square:before,
.fa-yc-square:before,
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
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
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
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
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
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
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
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
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
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
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
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
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
.modal-header {
  cursor: move;
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
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
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
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
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
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
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
  vertical-align: text-bottom;
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
[dir="rtl"] .list_item > div input {
  margin-right: 0;
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
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
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
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
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
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
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
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
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
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
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
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
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
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
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
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
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
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
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
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
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
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
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
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
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
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
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
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
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
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
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
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
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
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
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
div.output_area .mglyph > img {
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
  padding: 1px 0 1px 0;
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
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
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
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
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
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
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
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
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
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
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
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
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
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
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
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
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
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
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
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
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
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
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
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
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
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
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
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
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
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
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
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
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
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
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
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
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
.toolbar-btn-label {
  margin-left: 6px;
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
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
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
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
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
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
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
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
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
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
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
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
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
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Winning-in-the-UFC">Winning in the UFC<a class="anchor-link" href="#Winning-in-the-UFC">&#182;</a></h1><p><strong>By Shane Dugan and Erik Schmidt</strong></p>
<h2 id="Introduction">Introduction<a class="anchor-link" href="#Introduction">&#182;</a></h2><p>The Ultimate Fighting Championship (UFC) first premiered on March 11, 1993. The basic premise of the first event was to determine which style of fighting is superior. There were fighters representing boxing, wrestling, kickboxing, Brazilian Jiu Jitsu, and many more martial arts all competing to show that their method of fighting was superior. Ultimately Brazilian Jiu Jitsu was superior, and since then, the sport of Mixed Martial Arts has grown and evolved into a worldwide spectacle. Currently, you won't find fighters that only focus in one martial art. The fighters that participate have evolved to incorporate a variety of different styles into their arsenal in order to maximize their skill set. The main styles of martial arts practiced by fighter today include, Brazilian Jiu Jitsu, wrestling, boxing, and Muay Thai. This makes predicting who has a better chance of winning much more complicated than it was compared to back in 1993. The variety of styles and disciplines interfuse and make it very difficult for the average viewer to predict who is the winner. In the UFC, a fighter can win through 3 different methods: a submission, where the opponent either concedes, or is finished by the submission; a knockout/technical knockout, where the opponent is deemed unconcious or incoherent; or through a judges decision.</p>
<p>In this tutorial, we would like to use stats collected by a dataset retrieved from kaggle.com to try and predict who will be the victor in a fight based on their prior stats, including both fighters win ratios, reach, height, prefered stance, and others.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Getting-Started">Getting Started<a class="anchor-link" href="#Getting-Started">&#182;</a></h2><p>In this project, we used Python 3, with some imported libraries. The libraries we used were <a href="https://pandas.pydata.org/pandas-docs/stable/">pandas</a>, <a href="numpy.org">numpy</a>, <a href="https://scikit-learn.org/stable/index.html">scikit-learn</a>, <a href="https://matplotlib.org/contents.html">matplotlib</a>, and <a href="https://seaborn.pydata.org/">seaborn</a>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[129]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="k">import</span> <span class="n">linear_model</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="k">import</span> <span class="n">LabelEncoder</span> 
<span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="k">import</span> <span class="n">LinearRegression</span>
<span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="k">import</span> <span class="n">LogisticRegression</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="k">import</span> <span class="n">train_test_split</span>
<span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="k">import</span> <span class="n">LogisticRegression</span>
<span class="kn">import</span> <span class="nn">warnings</span>
<span class="n">warnings</span><span class="o">.</span><span class="n">filterwarnings</span><span class="p">(</span><span class="s1">&#39;ignore&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[115]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fights</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;data.csv&quot;</span><span class="p">,</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;,&#39;</span><span class="p">)</span>
<span class="n">fights</span> <span class="o">=</span> <span class="n">fights</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="n">n</span> <span class="o">=</span> <span class="mi">4000</span><span class="p">)</span>
<span class="n">fights</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[115]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>R_fighter</th>
      <th>B_fighter</th>
      <th>date</th>
      <th>Winner</th>
      <th>weight_class</th>
      <th>no_of_rounds</th>
      <th>B_current_lose_streak</th>
      <th>B_current_win_streak</th>
      <th>B_draw</th>
      <th>B_longest_win_streak</th>
      <th>...</th>
      <th>R_win_by_TKO_Doctor_Stoppage</th>
      <th>R_wins</th>
      <th>R_Stance</th>
      <th>R_Height_cms</th>
      <th>R_Reach_cms</th>
      <th>R_Weight_lbs</th>
      <th>B_age</th>
      <th>R_age</th>
      <th>B_avg_SIG_STR_pct</th>
      <th>R_avg_SIG_STR_pct</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Henry Cejudo</td>
      <td>Marlon Moraes</td>
      <td>6/8/2019</td>
      <td>Red</td>
      <td>Bantamweight</td>
      <td>5</td>
      <td>0</td>
      <td>4</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>0</td>
      <td>8</td>
      <td>Orthodox</td>
      <td>162.56</td>
      <td>162.56</td>
      <td>135.0</td>
      <td>31.0</td>
      <td>32.0</td>
      <td>0.466000</td>
      <td>0.466000</td>
    </tr>
    <tr>
      <td>1</td>
      <td>Valentina Shevchenko</td>
      <td>Jessica Eye</td>
      <td>6/8/2019</td>
      <td>Red</td>
      <td>Women's Flyweight</td>
      <td>5</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>3</td>
      <td>...</td>
      <td>0</td>
      <td>5</td>
      <td>Southpaw</td>
      <td>165.10</td>
      <td>167.64</td>
      <td>125.0</td>
      <td>32.0</td>
      <td>31.0</td>
      <td>0.399000</td>
      <td>0.575714</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Tony Ferguson</td>
      <td>Donald Cerrone</td>
      <td>6/8/2019</td>
      <td>Red</td>
      <td>Lightweight</td>
      <td>3</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>8</td>
      <td>...</td>
      <td>1</td>
      <td>14</td>
      <td>Orthodox</td>
      <td>180.34</td>
      <td>193.04</td>
      <td>155.0</td>
      <td>36.0</td>
      <td>35.0</td>
      <td>0.496129</td>
      <td>0.430000</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Jimmie Rivera</td>
      <td>Petr Yan</td>
      <td>6/8/2019</td>
      <td>Blue</td>
      <td>Bantamweight</td>
      <td>3</td>
      <td>0</td>
      <td>4</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>0</td>
      <td>6</td>
      <td>Orthodox</td>
      <td>162.56</td>
      <td>172.72</td>
      <td>135.0</td>
      <td>26.0</td>
      <td>29.0</td>
      <td>0.550000</td>
      <td>0.366250</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Tai Tuivasa</td>
      <td>Blagoy Ivanov</td>
      <td>6/8/2019</td>
      <td>Blue</td>
      <td>Heavyweight</td>
      <td>3</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>3</td>
      <td>Southpaw</td>
      <td>187.96</td>
      <td>190.50</td>
      <td>264.0</td>
      <td>32.0</td>
      <td>26.0</td>
      <td>0.310000</td>
      <td>0.545000</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>3995</td>
      <td>Jon Fitch</td>
      <td>Paulo Thiago</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Welterweight</td>
      <td>3</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>9</td>
      <td>Orthodox</td>
      <td>182.88</td>
      <td>193.04</td>
      <td>170.0</td>
      <td>28.0</td>
      <td>31.0</td>
      <td>0.290000</td>
      <td>0.523000</td>
    </tr>
    <tr>
      <td>3996</td>
      <td>Brock Lesnar</td>
      <td>Frank Mir</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Heavyweight</td>
      <td>5</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>0</td>
      <td>2</td>
      <td>Orthodox</td>
      <td>190.50</td>
      <td>205.74</td>
      <td>265.0</td>
      <td>30.0</td>
      <td>31.0</td>
      <td>0.543846</td>
      <td>0.750000</td>
    </tr>
    <tr>
      <td>3997</td>
      <td>Georges St-Pierre</td>
      <td>Thiago Alves</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Welterweight</td>
      <td>5</td>
      <td>0</td>
      <td>7</td>
      <td>0</td>
      <td>7</td>
      <td>...</td>
      <td>0</td>
      <td>12</td>
      <td>Orthodox</td>
      <td>180.34</td>
      <td>193.04</td>
      <td>185.0</td>
      <td>25.0</td>
      <td>28.0</td>
      <td>0.524545</td>
      <td>0.585714</td>
    </tr>
    <tr>
      <td>3998</td>
      <td>Dan Henderson</td>
      <td>Michael Bisping</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Middleweight</td>
      <td>3</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>0</td>
      <td>4</td>
      <td>Orthodox</td>
      <td>180.34</td>
      <td>187.96</td>
      <td>185.0</td>
      <td>30.0</td>
      <td>38.0</td>
      <td>0.480000</td>
      <td>0.545000</td>
    </tr>
    <tr>
      <td>3999</td>
      <td>Yoshihiro Akiyama</td>
      <td>Alan Belcher</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Middleweight</td>
      <td>3</td>
      <td>0</td>
      <td>2</td>
      <td>0</td>
      <td>2</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>Orthodox</td>
      <td>177.80</td>
      <td>185.42</td>
      <td>170.0</td>
      <td>25.0</td>
      <td>33.0</td>
      <td>0.373750</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>4000 rows × 42 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The dataset we found was pulled from <a href="kaggle.com">Kaggle</a>, which is a site that allows its users to upload and share datasets, projects, and compete in data science challenges. The dataset is a CSV (Comma Separated Value) file, which contains almost every fight in the UFC from March 1993 till June 2019. The actual data can be found <a href="https://www.kaggle.com/rajeevw/ufcdata">here</a>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Data-Pre-processing">Data Pre-processing<a class="anchor-link" href="#Data-Pre-processing">&#182;</a></h2><p>The dataset itself had a lot of columns that we did not need and that were duplicates. The dataset is organized with information about the fight coming first, then about each fighter, labeld Red (R) and Blue (B). From the general fight information, we deleted columns referee, location, and title_bout, because they were not useful to our analysis. For each fighter the column types <code>BODY, CLINCH, DISTANCE, GROUND, HEAD, KD, LEG, PASS, REV, SIG_STR, SUB_ATT, TD, TD_pct</code>, and <code>TOTAL_STR</code> were not only not needed, but also duplicated in the <code>avg_opp_</code> columns. In addition to those, we also deleted the columns <code>total_rounds_fought, total_time_fought(seconds)</code>, and <code>total_title_bouts</code>, as they were not relevant to the analysis. We went from 145 columns down to 42.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="The-Data-Itself">The Data Itself<a class="anchor-link" href="#The-Data-Itself">&#182;</a></h2><p>In the dataset, each row represents a fight. For each fight, listed is the Red fighter, Blue figther, date, winner, weight class, and number of rounds. For each of the fighters (R, B) is listed their stats at the time of the fight. <code>R_</code> represents red corner while <code>B_</code> represents blue corner. After the data that was dropped, the columns that were left were those containing general stats about the fighter before the round. These include:</p>
<ol>
<li><code>current_lose_streak</code>: Losing streak of the fighter</li>
<li><code>current_win_streak</code>: Winning streak of the fighter</li>
<li><code>draw</code>: Number of draws in the fighter's career</li>
<li><code>longest_win_streak</code>: Longest win streak of the fighter</li>
<li><code>losses</code>: Number of losses overall</li>
<li><code>win_by_Decision_Majority</code>: Number of fights won by majority judges decision</li>
<li><code>win_by_Decision_Split</code>: Number of fights won by split judges decision</li>
<li><code>win_by_Decision_Unanimous</code>: Number of fights won by unanimous judges decision</li>
<li><code>win_by_KO/TKO</code>: Wins by knockout</li>
<li><code>win_by_Submission</code>: Wins by submission</li>
<li><code>win_by_TKO_Doctor_Stoppage</code>: Wins by doctor stoppage</li>
<li><code>wins</code>: Total wins of the fighter</li>
<li><code>Stance</code>: Stance of the fighter</li>
<li><code>Height_cms</code>: Height in centimeters of the fighter</li>
<li><code>Reach_cms</code>: Arm span in centimeters of the fighter</li>
<li><code>Weight_lbs</code>: Weight in pounds of the fighter</li>
<li><code>age</code>: Age of the fighter</li>
<li><code>avg_SIG_STR_pct</code>: Percentage of significant strikes by the fighter</li>
</ol>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[116]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">blue</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;B_fighter&#39;</span><span class="p">,</span> <span class="s1">&#39;weight_class&#39;</span><span class="p">,</span> <span class="s1">&#39;B_current_lose_streak&#39;</span><span class="p">,</span> <span class="s1">&#39;B_current_win_streak&#39;</span><span class="p">,</span> <span class="s1">&#39;B_draw&#39;</span><span class="p">,</span> <span class="s1">&#39;B_longest_win_streak&#39;</span><span class="p">,</span>\
        <span class="s1">&#39;B_losses&#39;</span><span class="p">,</span> <span class="s1">&#39;B_win_by_Decision_Majority&#39;</span><span class="p">,</span> <span class="s1">&#39;B_win_by_Decision_Split&#39;</span><span class="p">,</span> <span class="s1">&#39;B_win_by_Decision_Unanimous&#39;</span><span class="p">,</span>\
       <span class="s1">&#39;B_win_by_KO/TKO&#39;</span><span class="p">,</span> <span class="s1">&#39;B_win_by_Submission&#39;</span><span class="p">,</span> <span class="s1">&#39;B_win_by_TKO_Doctor_Stoppage&#39;</span><span class="p">,</span> <span class="s1">&#39;B_wins&#39;</span><span class="p">,</span> <span class="s1">&#39;B_Stance&#39;</span><span class="p">,</span>\
       <span class="s1">&#39;B_Height_cms&#39;</span><span class="p">,</span> <span class="s1">&#39;B_Reach_cms&#39;</span><span class="p">,</span> <span class="s1">&#39;B_Weight_lbs&#39;</span><span class="p">,</span> <span class="s1">&#39;B_age&#39;</span><span class="p">,</span> <span class="s1">&#39;B_avg_SIG_STR_pct&#39;</span><span class="p">]</span>
<span class="n">red</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;R_fighter&#39;</span><span class="p">,</span> <span class="s1">&#39;weight_class&#39;</span><span class="p">,</span> <span class="s1">&#39;R_current_lose_streak&#39;</span><span class="p">,</span> <span class="s1">&#39;R_current_win_streak&#39;</span><span class="p">,</span> <span class="s1">&#39;R_draw&#39;</span><span class="p">,</span> <span class="s1">&#39;R_longest_win_streak&#39;</span><span class="p">,</span>\
        <span class="s1">&#39;R_losses&#39;</span><span class="p">,</span> <span class="s1">&#39;R_win_by_Decision_Majority&#39;</span><span class="p">,</span> <span class="s1">&#39;R_win_by_Decision_Split&#39;</span><span class="p">,</span> <span class="s1">&#39;R_win_by_Decision_Unanimous&#39;</span><span class="p">,</span>\
       <span class="s1">&#39;R_win_by_KO/TKO&#39;</span><span class="p">,</span> <span class="s1">&#39;R_win_by_Submission&#39;</span><span class="p">,</span> <span class="s1">&#39;R_win_by_TKO_Doctor_Stoppage&#39;</span><span class="p">,</span> <span class="s1">&#39;R_wins&#39;</span><span class="p">,</span> <span class="s1">&#39;R_Stance&#39;</span><span class="p">,</span>\
       <span class="s1">&#39;R_Height_cms&#39;</span><span class="p">,</span> <span class="s1">&#39;R_Reach_cms&#39;</span><span class="p">,</span> <span class="s1">&#39;R_Weight_lbs&#39;</span><span class="p">,</span> <span class="s1">&#39;R_age&#39;</span><span class="p">,</span> <span class="s1">&#39;R_avg_SIG_STR_pct&#39;</span><span class="p">]</span>

<span class="n">r_win</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">b_win</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">fights</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="k">if</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Winner&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Red&#39;</span><span class="p">:</span>
        <span class="n">r_win</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
        <span class="n">b_win</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="kc">False</span><span class="p">)</span>
    <span class="k">elif</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;Winner&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;Blue&#39;</span><span class="p">:</span>
        <span class="n">r_win</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="kc">False</span><span class="p">)</span>
        <span class="n">b_win</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">r_win</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="kc">False</span><span class="p">)</span>
        <span class="n">b_win</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="kc">False</span><span class="p">)</span>

<span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">,</span> <span class="s1">&#39;weight_class&#39;</span><span class="p">,</span> <span class="s1">&#39;current_lose_streak&#39;</span><span class="p">,</span> <span class="s1">&#39;current_win_streak&#39;</span><span class="p">,</span> <span class="s1">&#39;draw&#39;</span><span class="p">,</span> <span class="s1">&#39;longest_win_streak&#39;</span><span class="p">,</span>\
        <span class="s1">&#39;losses&#39;</span><span class="p">,</span> <span class="s1">&#39;win_by_Decision_Majority&#39;</span><span class="p">,</span> <span class="s1">&#39;win_by_Decision_Split&#39;</span><span class="p">,</span> <span class="s1">&#39;win_by_Decision_Unanimous&#39;</span><span class="p">,</span>\
       <span class="s1">&#39;win_by_KO/TKO&#39;</span><span class="p">,</span> <span class="s1">&#39;win_by_Submission&#39;</span><span class="p">,</span> <span class="s1">&#39;win_by_TKO_Doctor_Stoppage&#39;</span><span class="p">,</span> <span class="s1">&#39;wins&#39;</span><span class="p">,</span> <span class="s1">&#39;Stance&#39;</span><span class="p">,</span>\
       <span class="s1">&#39;Height_cms&#39;</span><span class="p">,</span> <span class="s1">&#39;Reach_cms&#39;</span><span class="p">,</span> <span class="s1">&#39;Weight_lbs&#39;</span><span class="p">,</span> <span class="s1">&#39;age&#39;</span><span class="p">,</span> <span class="s1">&#39;avg_SIG_STR_pct&#39;</span><span class="p">,</span> <span class="s1">&#39;won&#39;</span><span class="p">]</span>

<span class="n">B_fights</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">fights</span><span class="p">,</span> <span class="n">columns</span> <span class="o">=</span> <span class="n">blue</span><span class="p">)</span>
<span class="n">R_fights</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">data</span> <span class="o">=</span> <span class="n">fights</span><span class="p">,</span> <span class="n">columns</span> <span class="o">=</span> <span class="n">red</span><span class="p">)</span>
<span class="n">B_fights</span><span class="p">[</span><span class="s1">&#39;won&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">b_win</span>
<span class="n">R_fights</span><span class="p">[</span><span class="s1">&#39;won&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">r_win</span>
<span class="n">B_fights</span><span class="o">.</span><span class="n">columns</span> <span class="o">=</span> <span class="n">columns</span>
<span class="n">R_fights</span><span class="o">.</span><span class="n">columns</span> <span class="o">=</span> <span class="n">columns</span>
<span class="n">fights2</span> <span class="o">=</span> <span class="n">B_fights</span><span class="o">.</span><span class="n">copy</span><span class="p">()</span>
<span class="n">fights2</span> <span class="o">=</span> <span class="n">fights2</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">R_fights</span><span class="p">)</span>
<span class="n">fights2</span> <span class="o">=</span> <span class="n">fights2</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">drop</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="n">win_ratio</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">win_by_KO_pct</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">win_by_Submission_pct</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">fights2</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="n">KO</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;win_by_KO/TKO&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;win_by_TKO_Doctor_Stoppage&#39;</span><span class="p">]</span>
    <span class="n">fght</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;wins&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;draw&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;losses&#39;</span><span class="p">]</span>
    <span class="k">if</span> <span class="p">(</span><span class="n">fght</span> <span class="o">!=</span> <span class="mi">0</span><span class="p">):</span>
        <span class="n">win_ratio</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;wins&#39;</span><span class="p">]</span><span class="o">/</span><span class="n">fght</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">win_ratio</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mf">0.0</span><span class="p">)</span>
    <span class="k">if</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;wins&#39;</span><span class="p">]</span> <span class="o">!=</span> <span class="mi">0</span><span class="p">:</span>
        <span class="n">win_by_KO_pct</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">KO</span><span class="o">/</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;wins&#39;</span><span class="p">])</span>
        <span class="n">win_by_Submission_pct</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;win_by_Submission&#39;</span><span class="p">]</span><span class="o">/</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;wins&#39;</span><span class="p">])</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">win_by_KO_pct</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
        <span class="n">win_by_Submission_pct</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>    
<span class="n">fights2</span><span class="p">[</span><span class="s1">&#39;win_ratio&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">win_ratio</span>
<span class="n">fights2</span><span class="p">[</span><span class="s1">&#39;win_by_KO_pct&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">win_by_KO_pct</span>
<span class="n">fights2</span><span class="p">[</span><span class="s1">&#39;win_by_Submission_pct&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">win_by_Submission_pct</span>

<span class="n">fights2</span> <span class="o">=</span> <span class="n">fights2</span><span class="p">[</span><span class="n">fights2</span><span class="o">.</span><span class="n">Stance</span> <span class="o">!=</span> <span class="s1">&#39;Open Stance&#39;</span><span class="p">]</span>

<span class="n">fights3</span> <span class="o">=</span> <span class="n">fights2</span><span class="o">.</span><span class="n">copy</span><span class="p">()</span>
<span class="n">fights3</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">[</span><span class="n">fights3</span><span class="o">.</span><span class="n">win_ratio</span> <span class="o">!=</span> <span class="mf">0.0</span><span class="p">]</span>
<span class="n">fights3</span> <span class="o">=</span> <span class="n">fights3</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">drop</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">fights3</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[116]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>weight_class</th>
      <th>current_lose_streak</th>
      <th>current_win_streak</th>
      <th>draw</th>
      <th>longest_win_streak</th>
      <th>losses</th>
      <th>win_by_Decision_Majority</th>
      <th>win_by_Decision_Split</th>
      <th>win_by_Decision_Unanimous</th>
      <th>...</th>
      <th>Stance</th>
      <th>Height_cms</th>
      <th>Reach_cms</th>
      <th>Weight_lbs</th>
      <th>age</th>
      <th>avg_SIG_STR_pct</th>
      <th>won</th>
      <th>win_ratio</th>
      <th>win_by_KO_pct</th>
      <th>win_by_Submission_pct</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Marlon Moraes</td>
      <td>Bantamweight</td>
      <td>0</td>
      <td>4</td>
      <td>0</td>
      <td>4</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>167.64</td>
      <td>170.18</td>
      <td>135.0</td>
      <td>31.0</td>
      <td>0.466000</td>
      <td>False</td>
      <td>0.800000</td>
      <td>0.500000</td>
      <td>0.250000</td>
    </tr>
    <tr>
      <td>1</td>
      <td>Jessica Eye</td>
      <td>Women's Flyweight</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>3</td>
      <td>6</td>
      <td>0</td>
      <td>2</td>
      <td>1</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>167.64</td>
      <td>167.64</td>
      <td>125.0</td>
      <td>32.0</td>
      <td>0.399000</td>
      <td>False</td>
      <td>0.400000</td>
      <td>0.250000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Donald Cerrone</td>
      <td>Lightweight</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>8</td>
      <td>8</td>
      <td>0</td>
      <td>0</td>
      <td>7</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>185.42</td>
      <td>185.42</td>
      <td>155.0</td>
      <td>36.0</td>
      <td>0.496129</td>
      <td>False</td>
      <td>0.741935</td>
      <td>0.434783</td>
      <td>0.260870</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Petr Yan</td>
      <td>Bantamweight</td>
      <td>0</td>
      <td>4</td>
      <td>0</td>
      <td>4</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>2</td>
      <td>...</td>
      <td>Switch</td>
      <td>170.18</td>
      <td>170.18</td>
      <td>135.0</td>
      <td>26.0</td>
      <td>0.550000</td>
      <td>True</td>
      <td>1.000000</td>
      <td>0.500000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Blagoy Ivanov</td>
      <td>Heavyweight</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>Southpaw</td>
      <td>180.34</td>
      <td>185.42</td>
      <td>250.0</td>
      <td>32.0</td>
      <td>0.310000</td>
      <td>True</td>
      <td>0.500000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>5986</td>
      <td>George Sotiropoulos</td>
      <td>Lightweight</td>
      <td>0</td>
      <td>2</td>
      <td>0</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>177.80</td>
      <td>180.34</td>
      <td>155.0</td>
      <td>32.0</td>
      <td>0.630000</td>
      <td>True</td>
      <td>1.000000</td>
      <td>0.500000</td>
      <td>0.500000</td>
    </tr>
    <tr>
      <td>5987</td>
      <td>Jon Fitch</td>
      <td>Welterweight</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>8</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>4</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>182.88</td>
      <td>193.04</td>
      <td>170.0</td>
      <td>31.0</td>
      <td>0.523000</td>
      <td>True</td>
      <td>0.900000</td>
      <td>0.111111</td>
      <td>0.333333</td>
    </tr>
    <tr>
      <td>5988</td>
      <td>Brock Lesnar</td>
      <td>Heavyweight</td>
      <td>0</td>
      <td>2</td>
      <td>0</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>190.50</td>
      <td>205.74</td>
      <td>265.0</td>
      <td>31.0</td>
      <td>0.750000</td>
      <td>True</td>
      <td>0.666667</td>
      <td>0.500000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <td>5989</td>
      <td>Georges St-Pierre</td>
      <td>Welterweight</td>
      <td>0</td>
      <td>5</td>
      <td>0</td>
      <td>5</td>
      <td>2</td>
      <td>0</td>
      <td>1</td>
      <td>4</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>180.34</td>
      <td>193.04</td>
      <td>185.0</td>
      <td>28.0</td>
      <td>0.585714</td>
      <td>True</td>
      <td>0.857143</td>
      <td>0.416667</td>
      <td>0.166667</td>
    </tr>
    <tr>
      <td>5990</td>
      <td>Dan Henderson</td>
      <td>Middleweight</td>
      <td>0</td>
      <td>2</td>
      <td>0</td>
      <td>2</td>
      <td>2</td>
      <td>0</td>
      <td>2</td>
      <td>2</td>
      <td>...</td>
      <td>Orthodox</td>
      <td>180.34</td>
      <td>187.96</td>
      <td>185.0</td>
      <td>38.0</td>
      <td>0.545000</td>
      <td>True</td>
      <td>0.666667</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
  </tbody>
</table>
<p>5991 rows × 24 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Tidying-Up">Tidying Up<a class="anchor-link" href="#Tidying-Up">&#182;</a></h2><p>In order to aid in data analysis, we first only used the first 4000 rows, which dropped around 1100 rows that had data that had a lot of missing values. This effectively gives us the data from the past 10 years. Then, we decided to create two separate dataframes, with each fighter from each fight. We split up the data by blue or red corner, and created a new dataframe with all the information for each fighter, plus the name of the fighter, in two dataframes, called B_fights and R_fights. We also went through each row and created an array of booleans for each side, which represented whether or not the fighter on that side one, and appended those arrays to their corresponding dataframes.</p>
<p>We then renamed all the columns in these two fighter dataframes to be the same, by removing the <code>B_</code> and <code>R_</code> prefixes. Once the column names were the same, we appended them together under a new dataframe, fights2. We also noticed that there were a few columns with the Stance "Open Stance", and decided to delete those as they were skewing some of the data. We also created a new dataframe that contains no fighters with 0% win rate, as these were likely the stats for fighters who had just started out, therefore skewing the data.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Exploratory-Data-Analysis">Exploratory Data Analysis<a class="anchor-link" href="#Exploratory-Data-Analysis">&#182;</a></h1><p>Before we did any EDA (Exploratory Data Analysis), we had to add a few more columns for ease of plotting data. The first column we added was wins/# of fights. We found number of fights by adding the draw, wins, and losses columns, then divided wins by that number.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We then plotted age vs. win ratio on a bar plot. This plot shows that the younger the fighter, the higher their win ratio. This would make sense, as the younger the fighter, the better they are able to perform.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[117]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">style</span> <span class="o">=</span> <span class="s2">&quot;whitegrid&quot;</span><span class="p">)</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;age&quot;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;win_ratio&quot;</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">ax</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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AACKCEsAAAAAFBGWAAAAACgiLAEAAABQRFgCAAAAoIiwBAAAAEARYQkAAACAIsISAAAAAEWEJQAAAACKCEsAAAAAFBGWAAAAACgiLAEAAABQRFgCAAAAoEhHsy70+OOP58Ybb8y+ffty/PHH54477khPT0/daz796U/n3nvvTa1WS0dHR66//vpceOGFzZoIAAAAQAOaFpZuueWWrF27NitXrszdd9+dm2++OV/4whfqXrN48eJce+21mTlzZh599NH88i//cu6///4cc8wxzZoJAAAAwFFqylvh9uzZkx07dmTFihVJkhUrVmTHjh3Zu3dv3esuvPDCzJw5M0ly5plnZnR0NPv27WvGRAAAAAAa1JSwtGvXrsyZMye1Wi1JUqvVMnv27Ozates1z7nrrruyYMGCnHTSSc2YCAAAAECDmvZWuEY88MAD+cM//MP86Z/+acPnbt++fezjJUuWjOeshj344IOv+vmq7kqqu62qu5LqbqvqrqS626q6K6nutqruSqq7raq7kupuq+qupLXbqrorqe62qu5KqrutqruS6m6r6q6kutuquiup7raq7kr8/3mJyfhj9rOaEpa6u7vz7LPPZmRkJLVaLSMjI9m9e3e6u7uPeO1DDz2U3/7t385nPvOZvOUtb2n4WosWLUpXV9d4zH7DWv2T4LVUdVdS3W1V3ZVUd1tVdyXV3VbVXUl1t1V1V1LdbVXdlVR3m12Nq+q2qu5KqrutqruS6m6r6q6kutuquiup7raq7kqqu62qu5Lqbnt519DQUN1NPK/UlLfCnXDCCent7c3WrVuTJFu3bk1vb29mzZpV97qHH344119/fT75yU/mbW97WzOmAQAAAFCoKWEpSW699dZs2rQpy5Yty6ZNm7Jhw4Ykybp167Jt27YkyYYNG/LTn/40N998c1auXJmVK1fmBz/4QbMmAgAAANCApj1jaeHChdm8efMRn9+4cePYx1/+8pebNQcAAACAN6hpdywBAAAAMLUISwAAAAAUEZYAAAAAKCIsAQAAAFBEWAIAAACgiLAEAAAAQBFhCQAAAIAiwhIAAAAARYQlAAAAAIoISwAAAAAUEZYAAAAAKCIsAQAAAFBEWAIAAACgiLAEAAAAQBFhCQAAAIAiwhIAAAAARYQlAAAAAIoISwAAAAAUEZYAAAAAKCIsAQAAAFBEWAIAAACgiLAE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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Then a bar plot for stance vs. win ratio. This plot shows that the <code>Switch</code> stance often have a higher win ratio than the other two stances.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[118]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">style</span> <span class="o">=</span> <span class="s2">&quot;whitegrid&quot;</span><span class="p">)</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;Stance&quot;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;win_ratio&quot;</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">ax</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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eyZ6hEnPfg5MBfbzs7OfA1PBVNrPWxKWOjo6cujQoQwPD6fRaGR4eDiHDx9OR0fHqHVz584def6rv/qr6ejoyP79+7N06dJz/qzFixenvb19zGYHuBD4IRvg/GA/Bzg/TKb9/MSJE697iKcll8LNmTMnnZ2d6e/vT5L09/ens7Mzs2fPHrXu0KFDI8+feuqpfP/7388VV1zRihEBAAAAaFLLLoXbtGlTNmzYkPvvvz9vfvObs2XLliTJunXr8rGPfSxXX311Pv3pT+c///M/M23atMyYMSP33XffqFNMAAAAAEweLQtLixYtyo4dO854fevWrSPPX41NAAAAAEx+LbkUDgAAAIDzj7AEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABASSksvfLKKzl8+HBeeeWVsZ4HAAAAgCmiqbB0/Pjx3H333bnmmmtyww035Jprrsn69evzwgsvjNd8AAAAAExSTYWle+65Jy+99FIeeuihPPnkk3nooYfy0ksv5Z577hmv+QAAAACYpKY3s/jrX/96vvKVr+Siiy5KklxxxRW59957s3z58nEZDgAAAIDJq6kTS+3t7Tl69Oio13784x9n5syZYzoUAAAAAJNfUyeWVq9enbVr1+bDH/5wFixYkB/84AfZtm1bfu/3fm+85gMAAABgkmoqLN1xxx2ZN29e+vv7c/jw4cybNy+33XZbVq9ePV7zAQAAADBJNRWW2trasnr1aiEJAAAAgLOHpQcffDC33HJLkuRLX/rSz10nNgEAAABcWM4alr785S+PhKWdO3e+5ppXTzIBAAAAcOE4a1jaunXryPN/+qd/GtdhAAAAAJg6pjWz+NWTS//bqlWrxmQYAAAAAKaOpsLS//zP/5zx2unTp/O9731vzAYCAAAAYGo4p98Kd/fddydJTp06NfL8Vd///vdz5ZVXjv1kAAAAAExq5xSW3vGOd7zm8yS59tprc/PNN4/tVAAAAABMeucUlv74j/84SfLe9743y5YtG9eBAAAAAJgaziksvWrZsmU5efJkDhw4kB//+Mc5ffr0yN/9yq/8ypgPBwAAAMDk1VRY+ta3vpVPfOITOXnyZI4fP55LLrkkL774Yt72trflq1/96njNCAAAAMAk1NRvhbv33ntz22235fHHH8/FF1+cxx9/PHfccUd6enrO+t4DBw5kzZo16erqypo1a3Lw4MGfu/a///u/8973vjdbtmxpZjwAAAAAWqipsHTw4MHceuuto1776Ec/mm3btp31vb29venp6ckjjzySnp6ebNy48TXXDQ8Pp7e3Nx/4wAeaGQ0AAACAFmsqLF166aU5fvx4kmTu3Ln5r//6r/zkJz/J0NDQ677vyJEjGRgYSHd3d5Kku7s7AwMDOXr06BlrP//5z+fXf/3Xs3DhwmZGAwAAAKDFmgpLy5cvz3/8x38kSVavXp1bb701q1atys033/y67xscHMz8+fPTaDSSJI1GI/Pmzcvg4OCodU8//XR27dqVD3/4w82MBQAAAMAEaOrm3Z/61KdGnq9duzbXXHNNXnzxxSxbtuwND3Lq1Kn85V/+Ze69996RAFWxb9++NzzLWFqyZMlEjwBwVnv27JnoESY9+zkwFdjPz85+DkwFU2k/P+ewNDw8nK6urjz88MOZOXNmkuS66647p/d2dHTk0KFDGR4eTqPRyPDwcA4fPpyOjo6RNc8//3yeffbZfPSjH02S/OQnP8np06dz/Pjx/NVf/dU5/4MWL16c9vb2c14PgB+yAc4X9nOA88Nk2s9PnDjxuod4zjksNRqNNBqNnDhxYiQsnas5c+aks7Mz/f39WblyZfr7+9PZ2ZnZs2ePrFmwYEG+8Y1vjHz92c9+NkNDQ1m/fn1TnwUAAABAazR1j6Vbb701n/jEJ/L444/n2WefzXPPPTfy52w2bdqUvr6+dHV1pa+vL5s3b06SrFu3Lnv37q1NDwAAAMCEaeoeS69ekvbYY4+Ner2trS1PPfXU67530aJF2bFjxxmvb9269TXX/8mf/EkzowEAAADQYk2Fpaeffnq85gAAAABgimnqUrhzce211471twQAAABgEhrzsHT69Omx/pYAAAAATEJjHpba2trG+lsCAAAAMAmNeVgCAAAA4MIgLAEAAABQ4h5LAAAAAJSMeVjaunXrWH9LAAAAACah6c0sfu655/I3f/M3eeqppzI0NDTq7x599NEkyXXXXTdmwwEAAAAweTUVlv7sz/4sl19+edavX5+LLrpovGYCAAAAYApoKizt378///zP/5xp09zzGwAAAOBC11Qhet/73peBgYHxmgUAAACAKaSpE0tvf/vb85GPfCQ33XRTfvEXf3HU33384x8f08EAAAAAmNyaCksvvfRS3v/+9+fll1/OD3/4w/GaCQAAAIApoKmwdO+9947XHAAAAABMMWcNS9/73vdy2WWXJUmee+65n7vu8ssvH7upAAAAAJj0zhqWVqxYkSeeeCJJsnz58tdc09bWlqeeempsJwMAAABgUjtrWHo1KiXJgw8+mKuuumpcBwIAAABgamjqHku33357XnrppSxZsiRLly7N0qVL09nZmba2tvGaDwAAAIBJqqmw9Oijj+a5557LN7/5zXzzm99MX19fjh07liVLluTv//7vx2tGAAAAACahpsJS8rObdL/88ss5depUTp48mV27duXIkSPjMRsAAAAAk1hTYenOO+/Mt7/97cyfPz9Lly7Nb//2b2fz5s255JJLxms+AAAAACapac0s3rdvXxqNRq666qqRP6ISAAAAwIWpqRNL//7v/57nn39+5B5Ln//853PixIlcd911+eu//uvxmhEAAACASaipE0tJMnfu3FxxxRV55zvfmbe//e15/vnn87WvfW08ZgMAAABgEmvqxNLtt9+eb3/727n44ovzvve9L+9///uzfv36LFy4cJzGAwAAAGCyaios3XTTTfnUpz6Vyy+/fLzmAQAAAGCKaCosrVq1arzmAAAAAGCKafoeSwAAAACQCEsAAAAAFAlLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUCEsAAAAAlAhLAAAAAJQISwAAAACUTG/VBx04cCAbNmzIsWPHMmvWrGzZsiULFy4cteaBBx7Itm3bMm3atLzyyiv53d/93dx6662tGhEAAACAJrQsLPX29qanpycrV67Mzp07s3Hjxmzfvn3Umq6urqxatSptbW05fvx4VqxYkaVLl+aqq65q1ZgAAAAAnKOWXAp35MiRDAwMpLu7O0nS3d2dgYGBHD16dNS6Sy65JG1tbUmSn/70pzl16tTI1wAAAABMLi05sTQ4OJj58+en0WgkSRqNRubNm5fBwcHMnj171NqvfvWr+fSnP51nn302f/qnf5r3vOc9TX3Wvn37xmzusbBkyZKJHgHgrPbs2TPRI0x69nNgKrCfn539HJgKptJ+3rJL4c7VjTfemBtvvDE/+MEP8kd/9Ee54YYb8q53veuc37948eK0t7eP44QA5x8/ZAOcH+znAOeHybSfnzhx4nUP8bTkUriOjo4cOnQow8PDSZLh4eEcPnw4HR0dP/c9CxYsyNVXX51HH320FSMCAAAA0KSWhKU5c+aks7Mz/f39SZL+/v50dnaecRncd7/73ZHnR48ezTe+8Y28+93vbsWIAAAAADSpZZfCbdq0KRs2bMj999+fN7/5zdmyZUuSZN26dfnYxz6Wq6++Ov/6r/+axx57LNOnT8/p06fzoQ99KL/2a7/WqhEBAAAAaELLwtKiRYuyY8eOM17funXryPO/+Iu/aNU4AAAAALxBLbkUDgAAAIDzj7AEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAibAEAAAAQImwBAAAAECJsAQAAABAyfRWfdCBAweyYcOGHDt2LLNmzcqWLVuycOHCUWs+97nP5eGHH06j0cj06dNz5513ZtmyZa0aEQAAAIAmtCws9fb2pqenJytXrszOnTuzcePGbN++fdSaa665JmvXrs1FF12Up59+Oh/60Ieya9euvOlNb2rVmAAAAACco5ZcCnfkyJEMDAyku7s7SdLd3Z2BgYEcPXp01Lply5bloosuSpK85z3vyenTp3Ps2LFWjAgAAABAk1oSlgYHBzN//vw0Go0kSaPRyLx58zI4OPhz3/Pggw/mHe94R972tre1YkQAAAAAmtSyS+Ga8fjjj+czn/lM/uEf/qHp9+7bt28cJqpbsmTJRI8AcFZ79uyZ6BEmPfs5MBXYz8/Ofg5MBVNpP29JWOro6MihQ4cyPDycRqOR4eHhHD58OB0dHWesfeKJJ/Lnf/7nuf/++/Oud72r6c9avHhx2tvbx2JsgAuGH7IBzg/2c4Dzw2Taz0+cOPG6h3hacincnDlz0tnZmf7+/iRJf39/Ojs7M3v27FHrnnzyydx5553527/92/zyL/9yK0YDAAAAoKglYSlJNm3alL6+vnR1daWvry+bN29Okqxbty579+5NkmzevDk//elPs3HjxqxcuTIrV67MM88806oRAQAAAGhCy+6xtGjRouzYseOM17du3Try/IEHHmjVOAAAAAC8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QGRkJHZ2djg5OdG9e3fs7e2ZMWMGhw8fJjAwkJdeegmA7OxsYmNj6dKlCz169GDhwoWWus6cOYOfnx+ZmZn07NmT4OBgFi9ebDleWVnJkiVL6N27N4GBgcTFxVFcXAxAQUEBw4YNIygoiD59+rBt27YG/BVEREREatKMJREREZFaaNeuHXZ2dkyaNImIiAg6d+5M8+bN8fLyYubMmaxbt441a9ZYyjdt2pTU1FR8fHzIz89n+PDhBAQE0Lt3b0uZ3377jR07dlBYWMibb77JG2+8gZeXF+np6WzdupWlS5fSrl07Tp48iZOTE9euXWP48OEkJCSQlpbGyZMnGT58OD4+Pvj4+DTGzyIiIiL/cZqxJCIiIlILLi4u/Pjjj9jY2PD5558TGhrKqFGjuHDhwh3LBwcH4+fnh62tLf7+/vTr148DBw7UKDNmzBicnJzw9/fH39+fEydOALBu3To++eQTPD09sbGxwd/fH1dXV7Kzs3n22WcZMGAATZo04YUXXqBPnz7s3LnzoV+/iIiIyJ1oxpKIiIhILXl5eZGSkgJULUmbOHEiX375Jd27d7+t7JEjR5g7dy5//PEHJpMJo9FIeHh4jTJPP/205e+mTZty7do1AEpKSmjbtu1tdZ49e5bc3FzLcjuoWjYXHR1dL9cnIiIicr+UWBIRERGpAy8vL+Li4sjIyOCVV1657fj48eN55513WLZsGY6OjnzxxRdUVFTUqu7WrVtTVFSEr69vjf0eHh5069aN9PT0erkGERERkQelpXAiIiIitVBQUMCKFSsoKSkBoLi4mKysLDp16oS7uzvnzp3DaDRayl+9epXmzZvj6OhIbm4uWVlZtW5r4MCBzJ8/n8LCQsxmMydOnKCiooKePXtSWFjIxo0bMZlMmEwmcnNzKSgoqPfrFREREakNzVgSERERqQUXFxeOHDlCeno6ly9fplmzZrz22mskJibi4OCAt7c33bt3x8bGhv379zNjxgxSU1OZNWsWQUFB9O3bl0uXLtWqrWHDhmE0Ghk+fDgVFRV4enry7bff4urqyvLly0lJSSElJQWz2Yyfnx9Tpkx5yFcvIiIicmc2ZrPZ3NhBiIiIiIiIiIjI40dL4UREREREREREpE6UWBIRERERERERkTpRYklEREREREREROpEiSUREREREREREakTJZZERERERERERKROlFgSEREREREREZE6UWJJRERERERERETqRIklERERERERERGpEyWWRERERERERESkTv4XhAEeBaydGnQAAAAASUVORK5CYII=
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Then a bar plot for longest win streak vs. win ratio. This shows that the higher the current win streak of the fighter, the higher their win ratio usually is. This doesn't really reveal anything groundbreaking (someone who is currently on a high win streak has clearly won a lot of games, duh.), but it is interesting to see the distribution.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[119]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">style</span> <span class="o">=</span> <span class="s2">&quot;whitegrid&quot;</span><span class="p">)</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;longest_win_streak&quot;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;win_ratio&quot;</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">ax</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>In order to compare things like weight or height and significant strike percentage, we need to analyze based on weight class. This is due to the fact that in each weight class, the fighters are going to be more similar, which will amplify the differences in things like weight and height. We then split up the dataframe of data from all fighters into a few dataframes that represented fighters in the same weight class. We chose welterweight, middleweight, light heavyweight, and heavyweight to see how the win ratio of these fighters varied based on things like height and weight, which are somewhat indicative of their weight class.</p>
<p>For each weight class we plotted the fighters reach in centimeters vs. their significant strike percentage. Some of the classes (such as light heavyweights) show a definite trend upwards as reach increases, while others (such as welterweights) show no trend.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[120]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Welterweights</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">[</span><span class="n">fights3</span><span class="o">.</span><span class="n">weight_class</span> <span class="o">==</span> <span class="s2">&quot;Welterweight&quot;</span><span class="p">]</span>
<span class="n">Middleweights</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">[</span><span class="n">fights3</span><span class="o">.</span><span class="n">weight_class</span> <span class="o">==</span> <span class="s2">&quot;Middleweight&quot;</span><span class="p">]</span>
<span class="n">Light_Heavyweights</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">[</span><span class="n">fights3</span><span class="o">.</span><span class="n">weight_class</span> <span class="o">==</span> <span class="s2">&quot;Light Heavyweight&quot;</span><span class="p">]</span>
<span class="n">Heavyweights</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">[</span><span class="n">fights3</span><span class="o">.</span><span class="n">weight_class</span> <span class="o">==</span> <span class="s2">&quot;Heavyweight&quot;</span><span class="p">]</span>


<span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">style</span> <span class="o">=</span> <span class="s2">&quot;whitegrid&quot;</span><span class="p">)</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;Reach_cms&quot;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;avg_SIG_STR_pct&quot;</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">Welterweights</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">ax</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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AAAAil+v3hXuuuuu22dYKikpiQceeKDPBwMAAACguPUYloYNGyYcAQAAALCXHu+xBAAAAABvx827AQAAAEjSY1h69NFH93rsueeei5/85Cfx4osv9stQAAAAABS/HsPSl770pVi9enXX53fffXfU1NTEF77whfjIRz4SP//5z/t1QAAAAACKU49h6ac//WmcdNJJXZ/feOONcd1110VTU1MsWbIkbrnlln4dEAAAAIDi1GNYam1tjfHjx0dExPr162Pbtm0xf/78iIg488wz4/nnn+/XAQEAAAAoTj2GpYMOOii2bNkSERGPPPJITJ48OSoqKiIiYs+ePW7uDQAAADBElfW0w+zZs+PKK6+MD3/4w7F8+fKora3t+tpjjz0WBx98cL8OCAAAAEBx6vGMpauuuir+5E/+JP7rv/4rzj333DjvvPO6vvbkk0/GggUL+nVAAAAAAIpTj2cslZeXx2c+85m3/doFF1zQ7fPFixfH4sWL+2QwAAAAAIpbj2cs7Y977rmnL58OAAAAgCLWp2HJjbwBAAAAho4+DUslJSV9+XQAAAAAFLE+DUsAAAAADB0uhQMAAAAgSZ+GpTPPPLMvnw4AAACAIlbW0w6vv/56PPXUU3HSSSdFRMTXv/712LNnT9fXP/WpT8W73/3uiIhYsmRJP40JAAAAQLHpMSx961vfirKysq6w9C//8i9xxhlnRETEiy++GHv27InPfe5z/TslAAAAAEWnx7D005/+NL75zW/+/28oK4svf/nLERHxyiuvRG1trbAEAAAAMAT1eI+lzZs3x7hx47o+P/fcc7s+HjduXGzatKl/JgMAAACgqPXq5t2tra1dH1999dVv+zgAAAAAQ0uPYWnKlCmxatWqt/3aqlWr4oQTTujzoQAAAAAofj3eY+nyyy+P888/PzZv3hwzZ86M9773vfHqq6/Gv//7v8eqVavitttu69WBNm7cGNdee21s27YtRowYEUuXLo2JEyd222fVqlXR0NAQpaWl0dHREfPnz4/zzz8/6YUBAAAA0L96DEvHHntsfOtb34p//Md/jO9+97vR0dERpaWlcdxxx8U3v/nNOO6443p1oPr6+li4cGHMnTs3Vq9eHXV1dbFixYpu+8yaNSvOPvvsKCkpiTfeeCPmzJkT06ZNi6OPPjrt1QEAAADQb3oMSxG/vRzu9ttvj7feeiu2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Xbt2VWpqqrp166aMjAwdP35c7dq1k9Rwasdjjz2mvLw8nThxQk8++aR27Ngh6U4ONAzDpTyYkpKigwcPqlWrVpo2bZq6d+9eq/tSGxzF625M4uPjdejQIRmGoT/+8Y8VbicrK0tt27a1/x4SEqLs7GxJ7l03nImfs+d9lc03d60bUtXxcyYvusIdakf5cxBH53au5DtH9cGda4ezsXQlF5ZXl+YbVyzVgOTkZFNXjFRl165d6tSpkw4ePKi0tDQdO3bsnm9m3IWj+L3yyivy8/PTuHHjHG5j7969atu2bYX3oR45ckRr167VH/7whxoZb11SUez+8pe/aPv27UpOTpZhGFqyZInDbVQUH6vVqlOnTmnTpk3605/+pLS0NH300UcPZB/qEkdzsarjvKEcr2VlZXrrrbe0YcMGffrpp9q4caOmT5+umzdvurytQYMGKSUlRbt379ZHH32ks2fPqrS0VAsXLlRCQoK98LoTZ+NXVe5zNN/cdS5WFTtncp+z88sd64azc6+qXDd37lzl5eVp+PDhWrZsmfr06WP/Br+h1I5mzZpp9erVWr58uUaOHKn8/Hz5+/u7/DyaF154QZ988ol27Nih3/zmN4qJiVFhYeEDGvXD40y8li1bpv3792v69OlauXKlS9t397pRVfycPe9zNN/ctW5IjuNXk+c0kvvUDmc/f7nCUX1w59rhaixdyYV1bb7RWKqmnJwcHT16VMOGDbO/FhISopycHFmtVkl3Dpbc3FyHt+BU5M9//rOee+45WSwWNWvWTAMHDtThw4drdPwPW0XxuysxMVHnz5/XmjVrqrzVobIT4ePHj2v27NlKSkrS448/XmPjrgsqi93deebj46OxY8fqyy+/rHQblcWnbdu2Gjp0qHx8fNS0aVMNGjRIJ06ceDA7Ukc4mouOlt3VEI5XSUpPT1dubq79m8zQ0FA1btxYZ86cMZ372rZtq27dumn//v26fPmyLly4oJdfflkDBw7Ue++9pw8++EALFy584PtWGxzF7y5ncp+j+eauc7Gq2DmT+5yZX+5aN5yZe87kuqCgIL3++uvavn273nzzTRUVFemJJ56Q1LBqR9++fbVlyxb985//1Lhx41RcXKz27du7lAdbtWolb29vSVK/fv0UEhKi7777rlb3o7ZUFq8fGjFihA4fPlxhgy0kJOSe24OzsrLUpk0bt68bkuP4OXve52i+uWvduKuy+DmTF53lLrXjh+cgjnKaK/nOUX1w19rhSix/yFEulOrmfKOxVE0ffvihIiMj1bx5c/trLVq0UJcuXbRz505J0s6dO9WlSxeXboOTpHbt2iktLU3SnVu9Pv/8c/3oRz+qucHXARXFT5JWr16tb775RklJSfZnJlUmOztb//nPf+z3q9514sQJTZ8+XW+88Uall/TXZxXFrqioyH6fuGEYSk1NrfAqLslxfKKionTw4EEZhqHS0lJ98cUX6ty584PbmTqgsrlY1bK7GsLxKklt2rRRdna2zp49K+nOpc15eXl65JFHXMp95U/aCgoKdPjwYXXs2FFt27bV4cOHtW/fPu3bt08TJkzQ888/r1deeaV2dvABcxQ/yfnc52i+uetcdBQ7Z3NfVfPLnetGVXNPci7XFRYWqqysTJL0+eef6/Tp0/c8L6Kh1I7Lly9LunObw6pVq/TCCy/Iz8/PpTyYk5Nj/zk9PV2XLl2yPwfG3VQWr5s3byorK8u+3r59+xQQEKDAwMD7tjF06FBt3bpVNptNBQUF2rt3r4YMGeL2dUOqPH6unPc5mm/uWjfuqix+zuRFZ7hL7ajoHMRRTnMl3zmqD+5YO1yNpSu5sK7ONw/DMIyHPYi6bunSpdqzZ4/y8vLUvHlzBQYGKiUlRZI0ZMgQxcfHq3///vf8mzNnzmju3Lm6du2a/P39lZiYaO8mTpo0SbGxserWrZuOHTumGTNm6MaNGzIMQ82aNdOyZcsUERGhCxcuaPHixcrLy5PValXv3r0VHx9f7/70p6vx++677xQVFaVHH31UjRo1knSn4CUlJUm6N36StHHjRp0+fVqrV6++531HjRqlS5cu3fPwwZUrV9qf41IfuBq7ixcvatq0abJarbLZbHriiSe0YMEC+5+WLR87R/Gx2WxKTExUWlqaLBaLwsPDFRcXZ+ohuXWJmWPZ0bLy8XSX47W8yuK1fft2vfPOO/Z732NjYzV48GBJzue+V199VYcOHZKXl5cMw1B0dLTGjx9/3xjWrVunoqKievlno12Nnyu5z9F8c4e56GrsXMl95f1wfrlD3ZDMHbuSc7nu3//+t5YtWyaLxaLmzZtr0aJF9g+y7lg7KotlfHy8vvzyS5WWlqpfv36aP3++/WGzzubBuLg4ffvtt7JYLPL29lZsbKwiIyMf5u5Wm6vxysvLU0xMjG7duiWLxaKAgADFxcXZPyyVj5fVatWSJUt06NAh+7IxY8bcNwZ3rBuVxc+V3OdovrlD3ZDMHa+O8qKzn9ncoXY4OgdxlNOczXeO6oO71Q4zsXQlF9bV+UZjCQAAAAAAAKbUzzYgAAAAAAAAHjoaSwAAAAAAADCFxhIAAAAAAABMobEEAAAAAAAAU2gsAQAAAAAAwBQaSwAAAAAAADCFxhIAAMADdvjwYfXv3/9hDwMAAKDGeT3sAQAAANS2gQMHKi8vT56envLz81NERIQWLlyoJk2aPOyhAQAA1CtcsQQAABqkN998U8ePH9e2bdt08uRJvf322w97SAAAAPUOjSUAANCgtWrVSuHh4UpPT5cklZSUKDExUQMGDFDfvn21aNEiFRcXS5KuXr2qyZMnq0+fPurVq5cmT56s7Oxs+7auXLmiefPmKTw8FLt1YwAABJZJREFUXL169VJMTMw97/Xuu+/qJz/5icLDw5WcnFzl2IqLi7VixQo9/fTTCg0N1S9/+UsVFxcrIyNDnTp1UnJysiIjI9WrVy9t2bJFJ06c0LBhw9SzZ08tWbLEvp3z589r3LhxCg0NVe/evfX73/++JkIHAADArXAAAKBhy87O1oEDB9S7d29J0muvvaaLFy9q27Zt8vLy0qxZs5SUlKSZM2fKZrNp5MiRWrNmjaxWq+bPn68lS5Zow4YNkqQ5c+bIz89PKSkp8vPz0/Hjx+3vk5eXp+vXrystLU2fffaZYmNjNXjwYAUEBFQ6tsTERP3vf//T3/72N7Vs2VJfffWVLJb//17wq6++0p49e3T06FFNmTJFERER2rx5s8rKyjRixAgNHTpUYWFhWrt2rfr166f3339fpaWl+vrrrx9QNAEAQEPDFUsAAKBBmjp1qrp3767IyEgFBQUpNjZWhmFo69atmj9/vgIDA9W0aVNNnjxZKSkpkqTmzZtryJAhaty4sZo2baopU6bo6NGjkqTc3FylpaUpISFBAQEB8vb2VlhYmP39vLy8NHXqVHl7eysyMlJ+fn46d+5cpeOz2WxKTk5WfHy8goOD5enpqR49esjHx+eeffD19VV4eLj8/PwUFRWlFi1aKDg4WD179tTJkyft752Zmanc3Fz5+vqqZ8+eDyKkAACgAeKKJQAA0CAlJSWpb9++OnLkiGbOnKnCwkKVlpbq1q1bGjlypH09wzBks9kkSbdu3dLy5ct14MABXb16VZJ08+ZNWa1WZWdnKyAgoNIrkAIDA+Xl9f+nXo0bN1ZRUVGl4yssLNTt27fVvn37Stdp0aKF/WdfX9/7fr+7/dmzZ2vt2rUaPXq0AgIC9NJLL2n06NGOwgMAAOAUGksAAKBBCwsL08iRI5WYmKj169erUaNGSklJUXBw8H3rvvvuuzp37pw++OADtWrVSunp6RoxYoQMw1CbNm109epVXbt2Tf7+/tUeV/PmzeXr66uLFy+qc+fO1dpWq1attHTpUknSsWPH9NJLL6lXr17q0KFDtccJAAAaNm6FAwAADd6ECRP02Wef6dSpU4qOjtarr76q/Px8SVJOTo4OHDgg6c7VSb6+vvL399eVK1e0fv16+zZat26t/v37KyEhQVevXlVpaan9NjkzLBaLRo0apeXLlysnJ0dWq1XHjx9XSUmJy9v6+OOP7Q8ZDwgIkIeHxz3PagIAADCLMwoAANDgBQUFafjw4dqwYYNmz56tDh066Pnnn1ePHj3061//2v4spAkTJuj27dvq06ePxowZo4iIiHu2s3LlSnl5eenZZ59V37599d5771VrXHFxcerYsaNGjx6tsLAwvf766/bb8lzx9ddfKzo6Wt27d9eUKVMUHx/v8BY7AAAAZ3kYhmE87EEAAAAAAACg/uGKJQAAAAAAAJjCw7sBAAAeop///OfKzMy87/WEhAQ999xzD2FEAAAAzuNWOAAAAAAAAJjCrXAAAAAAAAAwhcYSAAAAAAAATKGxBAAAAAAAAFNoLAEAAAAAAMAUGksAAAAAAAAw5f8Asf2+HC6+L/gAAAAASUVORK5CYII=
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[121]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">style</span> <span class="o">=</span> <span class="s2">&quot;whitegrid&quot;</span><span class="p">)</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;Reach_cms&quot;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;avg_SIG_STR_pct&quot;</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">Middleweights</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">ax</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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W7fGli1borKyMn8TAgAAAFCSen3z7ssvvzyeeuqpbs899dRT8elPfzrnQwEAAABQ+nodlp599tk47rjjuj137LHHxjPPPJPzoQAAAAAofb0OS0OGDIn169d3e279+vUxePDgnA8FAAAAQOnrdViaPHlyXHvttbFy5cp455134tlnn43rr78+pkyZks/5AAAAAChRvQ5L11xzTYwdOzYuvPDCmDBhQsycOTMOPfTQuPbaa/M5HwAAAAAlqsfvCveuqqqqaGxsjIaGhnj99dfjgAMOiLKysnzOBgAAAEAJ63VYiohYs2ZN/Md//EesW7cuRowYEVOmTIkxY8bkaTQAAAAASlmvL4X7yU9+Euedd148++yzMXjw4Fi5cmWcd9558ZOf/CSf8wEAAABQonp9xtLXv/71+Pa3vx0nnnhi13OPP/54fP7zn4+pU6fmZTgAAAAASlevz1h6++234/jjj+/23HHHHRcdHR05HwoAAACA0tfrsHTZZZfFLbfcEps3b46IiE2bNsWtt94al112Wd6GAwAAAKB09fpSuLvuuivWr18f3//+92PIkCGxcePG6OzsjOHDh8fdd9/dddwvf/nLfMwJAAAAQInpdVj62te+ls85AAAAANjL9DosnXTSST0ec+WVV/bqOAAAAAD2fr2+x1JvPP7447l8OQAAAABKWE7DEgAAAAADh7AEAAAAQBJhCQAAAIAkOQ1LnZ2duXw5AAAAAEpYn8NSe3t718dXXXVVX18OAAAAgL1Er8PS66+/Htu3b+/6fP369fGVr3wlzjrrrK7n/uZv/ia30wEAAABQsnoMS7/73e/i9NNPj1NOOSU++MEPxn//93/HHXfcEZMnT45XX3017rzzzkLMCQAAAECJqejpgHnz5sX06dPj3HPPjR//+Mfxuc99Lo444oj44Q9/GIcddlghZgQAAACgBPV4xtLzzz8ff/d3fxdjx46Nq6++OjZu3Bi33XabqAQAAAAwwPUYlrZt2xbl5X88rLKyMt773vfG/vvvn/fBAAAAAChtPV4Kt2XLlvj85z/f9XlHR0e3zyMibr755txPBgAAAEBJ6zEsXXXVVbv9HAAAAICBqcewNGbMmKirqyvELAAAAADsRXq8x1JDQ0Mh5gAAAABgL9NjWOrs7CzEHAAAAADsZXq8FG779u3R0tKy28D0gQ98IKdDAQAAAFD6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pY985CNdN+fu7OzsdqPu8vLy+PCHPxyNjY1x4IEH5n5KAAAAAEpOry+Fu+mmm2Lq1Knx0EMPxbJly+LBBx+Mc889NxobG+O+++6Lbdu2xdy5c/M5KwAAAAAlpNdnLN12223xs5/9LKqqqiIi4pBDDok5c+ZEbW1tPPLII/HVr341Jk+enLdBAQAAACgtvT5jafv27fHSSy91e+6VV16J7du3R0TEe97znshms7mdDgAAAICS1eszli699NK49NJL4/zzz49Ro0bFq6++Gj/60Y/ikksuiYiIX/3qV3H88cfnbVAAAAAASkuvw1J9fRlHcocAACAASURBVH0cddRR8eCDD8ZTTz0Vw4cPjy996Utx2mmnRUTE2WefHWeffXbeBgUAAACgtPQ6LLW3t8dpp53WFZIAAAAAGNh6fY+lM888M+rr6+O+++6Ld955J58zAQAAALAX6HVY+sUvfhFnnHFG3H333XHKKafE7Nmz4z//8z9j27Zt+ZwPAAAAgBLV67A0dOjQ+MQnPhF333133H///XH00UfHrbfeGh/60IfyOR8AAAAAJarXYelPrV+/PtavXx+vv/56DBkyJNczAQAAALAX6PXNu5977rlobm6O5ubm2LRpU0yZMiXmz58fxx57bD7nAwAAAKBE9TosXXTRRTF58uS46aabYtKkSVFWVpbPuQAAAAAocb0OS4899lhs3Lgxli1bFj/60Y+is7Oz62sXXHBBXoYDAAAAoHT1Oiw98sgjcd1118UhhxwSzz33XBx++OGxatWqOOGEE4QlAAAAgAGo12Hp61//enz5y1+OKVOmxIknnhiLFy+ORYsWxXPPPZfP+QAAAAAoUb3+rnCvvPJKTJkypdtz5513XixevDjnQwEAAABQ+nodloYNGxbr16+PiIiDDjoonnjiiXjxxRdj+/bteRsOAAAAgNLV67B04YUXxtKlSyMi4lOf+lRccsklMW3atLjooovyNhwAAAAApavX91i68soruz6ePn16nHTSSfHOO+/E2LFj8zIYAAAAAKWt12Hpz40ePTqXcwAAAACwl+n1pXAAAAAA8KeEJQAAAACSCEsAAAAAJBGWAAAAAEgiLAEAAACQRFgCAAAAIImwBAAAAEASYQkAAACAJMISAAAAAEmEJQAAAACSCEsAAAAAJBGWAAAAAEgiLAEAAACQRFgCAAAAIImw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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[122]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">style</span> <span class="o">=</span> <span class="s2">&quot;whitegrid&quot;</span><span class="p">)</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;Reach_cms&quot;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;avg_SIG_STR_pct&quot;</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">Light_Heavyweights</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">ax</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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AAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAABAirAEAAAAQIqwBAAAAECKsAQAAEDFa29vj6VLl0Z7e3vRo8CYUlP0AAAAAFC0lpaW2LhxY3R0dERjY2PR48CY4YwlAAAAKl5HR0efLTAwwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAAAAKcISAAAAACnCEgAAAAApwhIAAACjQndnT9EjFKrSPz9jU03RAwAAAEBERHVNVbS3bCnk2C/t6OrdFjVD4/lTCjkuDIUzlgAAAABIEZYAAAAASBGWAAAAAEgRlgAAAABIEZYAAAAASBGWAAAAAEgRlgAAAABIEZYAAAAASBGWAAAAAEgRlgAAAABIEZYAAAAASBGWAAAAAEgRlgAAAABIEZYAAAAASBGWAAAAAEgRlgAAAABIEZYAAAAASBGWAAAAAEgRlgAAAABIEZYAAAAASBGWAAAAAEgRlgAAAABIEZYAAAAASBGW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b48jjzxy2IeC3/behsnRsN/r4r0Nk4seBQDgNdXOPS5KM94UtXOPK3oUABhx/d5j6cMf/nCce+65sWXLlpg3b17st99+8cwzz8R3v/vduP322+Pmm28ux5xUuCOnvz6OnP76oscAAOhXzYGzoubAWUWPAQBl0W9Yetvb3hZf+tKX4m//9m/jq1/9anR3d0d1dXXMmTMnvvjFL8acOXPKMScAAAAAo0y/YSni15fDfe1rX4sXX3wxduzYEePHj4/6+vqRng0AAACAUazfsNTd3d37c11dXUyePPllj1dXu6EyAAAAQKXpNywdfvjhUVVV9YrP9fT0RFVVVfz4xz8e9sEAAAAAGN36DUv33XdfOeYAAAAAYIzpNyztv//+r/j4r371q3jDG94w7AMBAAAAMDb0e3OkVatWxQ9+8IPe39euXRsnnHBCNDY2xvz58+Pxxx8f0QEBijRuXN8tAAAA/63fsPTlL3+594bdERHLli2LY489Nu6666449thj49Of/vSIDghQpKOPqI7pU6vi6CN8SQEAjLSq2ro+WwBGv34vhdu0aVMccsghvT9v2LAhbrrpppgwYUJccsklMW/evBEfEqAobz6gOt58QNFTAEBleN0xTfHij74f9UeeUvQoAAxQv2GpVCrFnj17oq6uLh566KE46KCDYsKECRERUV9fHy+99NKIDwkAAOz9amfOjtqZs4seA4BB6Pfajrlz58a1114b69evj6985Stx0kkn9T73+OOP97lMDgAAAIDK0W9YuuKKK2LdunVx9tlnR319fTQ3N/c+d+edd8bxxx8/ogMCAAAAMDr1eync1KlT45ZbbnnF5/7iL/6iz+9tbW3R1NQ0PJMBAAAAMKoN69ccLVu2bDjfDgAAAIBRbFjDUk9Pz3C+HQAAAACj2LCGpaqqquF8OwAAAABGsWENSwAAAABUDmEJAAAAgJRhDUszZswYzrcDAAAAYBSrGeiOv/jFL17x8dra2pg8eXJUV1dHW1vbsA0GAAAAwOg24LD0rne9q/fm3D09PX1u1F1dXR3vfOc7Y/ny5bHffvsN/5QAAAAAjDoDvhTuyiuvjFNPPTXuvffeWLNmTdxzzz1x2mmnxfLly+Ouu+6Kzs7OWLly5UjOCgAAAMAoMuAzlq677rr43ve+F3V1dRERceCBB8aKFSti/vz5cf/998enPvWpmDdv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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[123]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">style</span> <span class="o">=</span> <span class="s2">&quot;whitegrid&quot;</span><span class="p">)</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;Reach_cms&quot;</span><span class="p">,</span> <span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;avg_SIG_STR_pct&quot;</span><span class="p">,</span> <span class="n">data</span> <span class="o">=</span> <span class="n">Heavyweights</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">ax</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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5gAAAABgP9PjpXA7d+6M5ubmvQamd7/73XkdCgAAAIDS16ufCnfjjTfuMSyVlZXFgw8+mPfBAAAAAChtPYalwYMHC0cAAAAA7KLHeywBAAAAwO64eTcAAAAASXoMS4899tguzz3//PPx05/+NF588cVMhgIAAACg9PUYlr7yla/EsmXLuj5funRp1NXVxRe+8IX44Ac/GL/85S8zHRAAAACA0tRjWPrZz34WEydO7Pr8lltuiRtvvDGam5tj3rx58c1vfjPTAQEAAAAoTT2Gpba2thg9enRERKxatSpee+21uOiiiyIi4rzzzou1a9dmOiAAAAAApanHsHTggQfGhg0bIiLi0UcfjXHjxkVlZWVEROzYscPNvQEAAAAGqIqeDpg6dWpcc801ce6558bChQtj9uzZXV97/PHH47DDDst0QAAAAABKU49nLF177bVx6qmnxn/913/FRz7ykbj44ou7vvbUU0/FzJkzMx0QAAAAgNLU4xlLgwYNik9/+tO7/dpll13W7fO5c+fG3Llz8zIYAAAAAKWtxzOW9sU999yTz5cDAAAAoITlNSy5kTcAAADAwJHXsFRWVpbPlwMAAACghOU1LAEAAAAwcLgUDgAAAIAkeQ1L5513Xj5fDgAAAIASVtHTAa+//no8/fTTMXHixIiI+Jd/+ZfYsWNH19c/9rGPxTve8Y6IiJg3b15GYwIAAABQanoMS9/5zneioqKiKyz967/+a5xzzjkREfHiiy/Gjh074u///u+znRIAAACAktNjWPrZz34W3/72t//3Gyoq4qtf/WpERLz88ssxe/ZsYQkAAABgAOrxHkvr16+PUaNGdX3+kY98pOvjUaNGxbp167KZDAAAAICS1qubd7e1tXV9fN111+32eQAAAAAGlh7D0imnnBJLlizZ7deWLFkSJ510Ut6HAgAAAKD09XiPpU996lNx6aWXxvr162PKlCnxzne+M1555ZX4yU9+EkuWLIk77rijEHMCAAAAUGJ6DEvjx4+P73znO/FP//RP8W//9m+xc+fOKC8vjxNOOCG+/e1vxwknnFCIOQEAAAAoMT2GpYg/Xg531113xZtvvhmbNm2KIUOGxODBg7OeDQAAAIAS1mNY2rlzZ9fHVVVVMXz48F2eLy/v1T3AAQAAAOhHegxLxx9/fJSVle32a52dnVFWVhZPPfVU3gcDAAAAoLT1GJYefPDBQswBAAAAwH6mx7B0yCGH7Pb5P/zhD/GOd7wj7wMBAAAAsH/o8eZIS5cujV/96lddn69YsSLOPPPMmDx5ctTW1sbzzz+f6YAAAAAAlKYew9J3v/vdrht2R0TU19fHaaedFvfcc0+cdtppcfPNN2c6IAAAAAClqcdL4VpbW+OYY47p+njVqlWxcOHCOOigg+Laa6+NKVOmZD4kAAAAAKWnxzOWcrlcbN++PSIiHnvssTjyyCPjoIMOioiIwYMHx5YtW7KdEAAAAICS1GNYmjRpUtx6663x9NNPx/e+97143/ve1/W1559/vttlcgAAAAAMHD2GpRtvvDFaWlri4osvjsGDB8fs2bO7vrZs2bI4/fTTMx0QAAAAgNLU4z2WRo4cGXfeeeduv/YP//AP3T5vamqKurq6/EwGAAAAQEnr8YylfVFfX5/PlwMAAACghOU1LHV2dubz5QAAAAAoYXkNS2VlZfl8OQAAAABKWF7DEgAAAAADh7AEAAAAQJK8hqXRo0fn8+UAAAAAKGEVvT3wd7/73W6fr6ysjOHDh0d5eXk0NTXlbTAAAAAASluvw9K5557bdXPuzs7ObjfqLi8vj/e///3R0NAQ73znO/M/JQAAAAAlp9eXwt10000xbdq0eOCBB+KJJ56I+++/P84777xoaGiIe+65J3bs2BHz5s3LclYAAAAASkivz1i67bbb4qc//WlUVVVFRMThhx8ec+fOjdra2njooYfiK1/5SkyZMiWzQQEAAAAoLb0+Y2nnzp3x4osvdnvupZdeip07d0ZExNve9rbo6OjY4/evWbMmZs6cGbW1tTFz5sxYu3btLscsWbIkpk2bFtOnT49p06bFnXfe2dvxAAAAACiwXp+xdNlll8Vll10WF1xwQYwaNSpefvnl+MEPfhCXXnppRET88pe/jJNOOmmP39/Q0BCzZs2K6dOnx7Jly6K+vn6XcFRbWxsf/vCHo6ysLDZv3hzTpk2LSZMmxXHHHZf4ywMAAAAgK70OS7Nnz45jjz027r///njyySdj+PDh8cUvfjHOOOOMiIg455xz4pxzztnt927cuDFaWlpi4cKFERFRV1cXN910U7S1tcXQoUO7jnv729/e9fGWLVti+/bt3W4SDgAAAEDp6HVYamtrizPOOKMrJO2L1tbWGDlyZORyuYiIyOVyMWLEiGhtbe0WliIiHnzwwbjlllvihRdeiGuvvTaOPfbYfXqvlStX7vXrEyZM2LfhB4Dly5f3+TXsdVd93aud7p69ZsNes2Gv2bDX/PN7gWz4azUb9poNe82GvWbDXvOvLzvtdVh63/veF5MmTYpp06bFueeeG4MHD05+0705++yz4+yzz46XXnopPvWpT8UZZ5wRRx55ZK+/f9y4cV03GKd3/E2VDXvNhr1mw16zYa/ZsNf8s9Ns2Gs27DUb9poNe82Gvebf3na6devWvZ7E0+ubd//85z+Ps846K+6+++447bTTYs6cOfGf//mfsWPHjh6/t0O1lIwAACAASURBVLq6OtatW9d1c++Ojo5Yv359VFdX7/F7Ro8eHePHj49f/OIXvR0RAAAAgALqdVgaOnRofPSjH42777477r333jjuuOPi1ltvjfe+9709fu+wYcOipqYmmpqaIiKiqakpampqdrkM7rnnnuv6uK2tLX7961/HMccc09sRAQAAACigXl8K91YbNmyIDRs2xKuvvhpDhgzp1ffMnTs3brjhhrj99ttjyJAhMX/+/Ij4403Br7766hg/fnz8x3/8RzzyyCNRUVERnZ2dcckll/QqXAEAAABQeL0OS88++2w0NTVFU1NTbNmyJaZOnRq33357nHDCCb36/rFjx8bixYt3eX7BggVdH3/+85/v7TgAAAAAFFmvw9LFF18cU6ZMiZtuuikmT54cZWVlWc4FAAAAQInrdVh65JFHYtOmTfHEE0/ED37wg+js7Oz62oUXXpjJcAAAAACUrl6HpYceeiiuu+66OPzww+PZZ5+No446KlavXh2nnHKKsAQAAAAwAPU6LH3ta1+LL33pSzF16tSYOHFiLF26NJYsWRLPPvtslvMBAAAAUKLKe3vgSy+9FFOnTu323Pnnnx9Lly7N+1AAAAAAlL5eh6Vhw4bFhg0bIiLikEMOicceeyxeeOGF2LlzZ2bDAQAAAFC6eh2WLrrooli+fHlERHz84x+PSy+9NKZPnx4XX3xxZsMBAAAAULp6fY+lK6+8suvjGTNmxKRJk+LNN9+MsWPHZjIYAAAAAKWt12Hpz40ePTqfcwAAAACwn+n1pXAAAAAA8FbCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIUlGoN1qzZk3ccMMN8dprr8VBBx0U8+fPjzFjxnQ75pvf/Gbcd999kcvloqKiIq655po4/fTTCzUiAAAAAPugYGGpoaEhZs2aFdOnT49ly5ZFfX193Hnnnd2OOeGEE+KKK66IwYMHx9NPPx2XXHJJPPzww3HAAQcUakwAAAAAeqkgl8Jt3LgxWlpaoq6uLiIi6urqoqWlJdra2rodd/rpp8fgwYMjIuLYY4+Nzs7OeO211woxIgAAAAD7qCBhqbW1NUaOHBm5XC4iInK5XIwYMSJaW1v3+D1Lly6Nv/zLv4xRo0YVYkQAAAAA9lHBLoXbF7/5zW/in//5n+O73/3uPn/vypUr9/r1CRMmpI7Vby1fvrzPr2Gvu+rrXu109+w1G/aaDXvNhr3mn98LZMNfq9mw12zYazbsNRv2mn992WlBwlJ1dXWsW7cuOjo6IpfLRUdHR6xfvz6qq6t3Ofaxxx6L6667Lm6//fY48sgj9/m9xo0bF1VVVfkYe8DwN1U27DUb9poNe82GvWbDXvPPTrNhr9mw12zYazbsNRv2mn972+nWrVv3ehJPQS6FGzZsWNTU1ERTU1NERDQ1NUVNTU0MHTq023FPPPFEXHPNNfH1r3893vWudxViNAAAAAASFSQsRUTMnTs3Fi1aFLW1tbFo0aKYN29eRETMnj07VqxYERER8+bNiy1btkR9fX1Mnz49pk+fHs8880yhRgQAAABgHxTsHktjx46NxYsX7/L8ggULuj5esmRJocYBAAAAoI8KdsYSAAAAAP2LsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIIiwBAAAAkERYAgAAACCJsAQAAABAEmEJAAAAgCTCEgAAAABJhCUAAAAAkghLAAAAACQRlgAAAABIUrCwtGbNmpg5c2bU1tbGzJkzY+3atbsc8/DDD8eHP/zhGDduXMyfP79QowEAAACQoGBhqaGhIWbNmhUPPPBAzJo1K+rr63c55rDDDot//Md/jE984hOFGgsAAACARAUJSxs3boyWlpaoq6uLiIi6urpoaWmJtra2bscd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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The last thing we plotted was a histogram of the win ratios. There is a spike in the range from .5 to .6.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[153]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">20</span><span class="p">,</span> <span class="mi">12</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">x</span> <span class="o">=</span> <span class="n">fights3</span><span class="p">[</span><span class="s1">&#39;win_ratio&#39;</span><span class="p">],</span> <span class="n">bins</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">arange</span><span class="p">(</span><span class="n">start</span> <span class="o">=</span> <span class="mi">0</span><span class="p">,</span> <span class="n">stop</span> <span class="o">=</span> <span class="mi">1</span><span class="p">,</span> <span class="n">step</span> <span class="o">=</span> <span class="mf">0.1</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[153]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>(array([   0.,   10.,  122.,  323.,  277., 1680., 1149.,  799.,  478.]),
 array([0. , 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9]),
 &lt;a list of 9 Patch objects&gt;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Predictions-Based-On-Fighter-Statistics">Predictions Based On Fighter Statistics<a class="anchor-link" href="#Predictions-Based-On-Fighter-Statistics">&#182;</a></h1><p>In this section, we will analyze the potential to predict both win ratio and outcome of a fight. Using linear regression, we will try to predict winning ratio, and analyze which stats best predict this. Then, using logistic regression, we will try to predict the outcome of a fight based on certain stats of the two fighters, and analyze which stats best predict this.</p>
<h2 id="Linear-Regression:-Can-We-Predict-Winning-Ratio?">Linear Regression: Can We Predict Winning Ratio?<a class="anchor-link" href="#Linear-Regression:-Can-We-Predict-Winning-Ratio?">&#182;</a></h2><p>Before doing any linear regression, we needed to transform the stance of the fighters into an encoded variable, in order to be able to use it in linear regression. After doing so, we chose a few statistics to try to predict with: stance (encoded), height, reach, and age.</p>
<h3 id="Null-Hypothesis-for-Winning-Ratio:">Null Hypothesis for Winning Ratio:<a class="anchor-link" href="#Null-Hypothesis-for-Winning-Ratio:">&#182;</a></h3><p>The set of four stats: stance, height, reach, and age, do not affect the winning ratio.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[138]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fights4</span> <span class="o">=</span> <span class="n">fights3</span><span class="o">.</span><span class="n">copy</span><span class="p">()</span>
<span class="n">fights4</span> <span class="o">=</span> <span class="n">fights4</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
<span class="n">le</span> <span class="o">=</span> <span class="n">LabelEncoder</span><span class="p">()</span>
<span class="n">le</span><span class="o">.</span><span class="n">fit</span><span class="p">([</span><span class="s2">&quot;Orthodox&quot;</span><span class="p">,</span> <span class="s2">&quot;Southpaw&quot;</span><span class="p">,</span> <span class="s2">&quot;Switch&quot;</span><span class="p">])</span>
<span class="n">encoded_stance</span> <span class="o">=</span> <span class="n">le</span><span class="o">.</span><span class="n">transform</span><span class="p">(</span><span class="n">fights4</span><span class="p">[</span><span class="s1">&#39;Stance&#39;</span><span class="p">])</span>
<span class="n">fights4</span><span class="p">[</span><span class="s1">&#39;encoded_stance&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">encoded_stance</span>

<span class="n">stats</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;encoded_stance&quot;</span><span class="p">,</span> <span class="s2">&quot;Height_cms&quot;</span><span class="p">,</span> <span class="s2">&quot;Reach_cms&quot;</span><span class="p">,</span> <span class="s2">&quot;age&quot;</span><span class="p">]</span>
<span class="n">fighter_stats</span> <span class="o">=</span> <span class="n">fights4</span><span class="p">[</span><span class="n">stats</span><span class="p">]</span>
<span class="n">fighter_stats</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[138]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>encoded_stance</th>
      <th>Height_cms</th>
      <th>Reach_cms</th>
      <th>age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>0</td>
      <td>167.64</td>
      <td>170.18</td>
      <td>31.0</td>
    </tr>
    <tr>
      <td>1</td>
      <td>0</td>
      <td>167.64</td>
      <td>167.64</td>
      <td>32.0</td>
    </tr>
    <tr>
      <td>2</td>
      <td>0</td>
      <td>185.42</td>
      <td>185.42</td>
      <td>36.0</td>
    </tr>
    <tr>
      <td>3</td>
      <td>2</td>
      <td>170.18</td>
      <td>170.18</td>
      <td>26.0</td>
    </tr>
    <tr>
      <td>4</td>
      <td>1</td>
      <td>180.34</td>
      <td>185.42</td>
      <td>32.0</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>5986</td>
      <td>0</td>
      <td>177.80</td>
      <td>180.34</td>
      <td>32.0</td>
    </tr>
    <tr>
      <td>5987</td>
      <td>0</td>
      <td>182.88</td>
      <td>193.04</td>
      <td>31.0</td>
    </tr>
    <tr>
      <td>5988</td>
      <td>0</td>
      <td>190.50</td>
      <td>205.74</td>
      <td>31.0</td>
    </tr>
    <tr>
      <td>5989</td>
      <td>0</td>
      <td>180.34</td>
      <td>193.04</td>
      <td>28.0</td>
    </tr>
    <tr>
      <td>5990</td>
      <td>0</td>
      <td>180.34</td>
      <td>187.96</td>
      <td>38.0</td>
    </tr>
  </tbody>
</table>
<p>5829 rows × 4 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[126]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="n">fighter_stats</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">fights4</span><span class="p">[</span><span class="s1">&#39;win_ratio&#39;</span><span class="p">]</span>
<span class="n">lr</span> <span class="o">=</span> <span class="n">LinearRegression</span><span class="p">()</span>
<span class="n">model</span> <span class="o">=</span> <span class="n">lr</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
<span class="n">lr</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[126]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0.045420135626618514</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We fit the model to the data and found that this model has an R-square value of .04, which means this model does not describe the variance for winning ratio. This means we accept the null hypothesis.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[128]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">rating_coeffs</span> <span class="o">=</span> <span class="n">lr</span><span class="o">.</span><span class="n">coef_</span><span class="o">.</span><span class="n">tolist</span><span class="p">()</span>
<span class="k">for</span> <span class="n">stat</span><span class="p">,</span> <span class="n">coef</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">stats</span><span class="p">,</span> <span class="n">rating_coeffs</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Stat: </span><span class="si">{}</span><span class="s2">, Coefficient: </span><span class="si">{}</span><span class="s2">&quot;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">stat</span><span class="p">,</span> <span class="n">coef</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Stat: encoded_stance, Coefficient: 0.015981084038739397
Stat: Height_cms, Coefficient: -0.00171906042518197
Stat: Reach_cms, Coefficient: 0.0023987006597275483
Stat: age, Coefficient: -0.010316108764445765
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Here is the coefficients for each of the statistics. We cannot draw any conclusions from this, as this model does not predict the values at all.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Logistic-Regression:-Can-We-Predict-the-Outcome-of-a-Fight?">Logistic Regression: Can We Predict the Outcome of a Fight?<a class="anchor-link" href="#Logistic-Regression:-Can-We-Predict-the-Outcome-of-a-Fight?">&#182;</a></h2><p>Before we were able to do logistic regression, we had to do a bit of manipulation on the original dataframe of all fights. We first dropped all rows that had some value of NaN (not a number), as the stance columns had a couple of rows that had NaN in them. We then removed all rows with the stance Open Stance, as these entries were so few that they skewed the data. 
We then encoded the stances as we did in linear regression, except for both the Red and Blue fighters. We also encoded the winner of the fight as Red -&gt; 0, Blue -&gt; 1, and dropped any Draws. Lastly, we computed the win ratio for both the Red and Blue fighters, and dropped any rows where the win ratio was 0.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[152]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fights5</span> <span class="o">=</span> <span class="n">fights</span><span class="o">.</span><span class="n">copy</span><span class="p">()</span>
<span class="n">fights5</span> <span class="o">=</span> <span class="n">fights5</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
<span class="n">fights5</span> <span class="o">=</span> <span class="n">fights5</span><span class="p">[</span><span class="n">fights5</span><span class="o">.</span><span class="n">B_Stance</span> <span class="o">!=</span> <span class="s2">&quot;Open Stance&quot;</span><span class="p">]</span>
<span class="n">fights5</span> <span class="o">=</span> <span class="n">fights5</span><span class="p">[</span><span class="n">fights5</span><span class="o">.</span><span class="n">R_Stance</span> <span class="o">!=</span> <span class="s2">&quot;Open Stance&quot;</span><span class="p">]</span>
<span class="n">B_encoded_stance</span> <span class="o">=</span> <span class="n">le</span><span class="o">.</span><span class="n">transform</span><span class="p">(</span><span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;B_Stance&#39;</span><span class="p">])</span>
<span class="n">R_encoded_stance</span> <span class="o">=</span> <span class="n">le</span><span class="o">.</span><span class="n">transform</span><span class="p">(</span><span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;R_Stance&#39;</span><span class="p">])</span>

<span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;B_encoded_stance&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">B_encoded_stance</span>
<span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;R_encoded_stance&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">R_encoded_stance</span>

<span class="n">le2</span> <span class="o">=</span> <span class="n">LabelEncoder</span><span class="p">()</span>
<span class="n">le2</span><span class="o">.</span><span class="n">fit</span><span class="p">([</span><span class="s2">&quot;Red&quot;</span><span class="p">,</span> <span class="s2">&quot;Blue&quot;</span><span class="p">])</span>
<span class="n">fights5</span> <span class="o">=</span> <span class="n">fights5</span><span class="p">[</span><span class="n">fights5</span><span class="o">.</span><span class="n">Winner</span> <span class="o">!=</span> <span class="s2">&quot;Draw&quot;</span><span class="p">]</span>
<span class="n">encoded_winner</span> <span class="o">=</span> <span class="n">le2</span><span class="o">.</span><span class="n">transform</span><span class="p">(</span><span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;Winner&#39;</span><span class="p">])</span>
<span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;encoded_winner&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">encoded_winner</span>

<span class="n">B_win_ratio</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">R_win_ratio</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">fights5</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="n">B_fght</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;B_wins&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;B_draw&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;B_losses&#39;</span><span class="p">]</span>
    <span class="n">R_fght</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;R_wins&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;R_draw&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;R_losses&#39;</span><span class="p">]</span>
    <span class="k">if</span> <span class="p">(</span><span class="n">B_fght</span> <span class="o">!=</span> <span class="mi">0</span><span class="p">):</span>
        <span class="n">B_win_ratio</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;B_wins&#39;</span><span class="p">]</span><span class="o">/</span><span class="n">B_fght</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">B_win_ratio</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mf">0.0</span><span class="p">)</span>
    <span class="k">if</span> <span class="p">(</span><span class="n">R_fght</span> <span class="o">!=</span> <span class="mi">0</span><span class="p">):</span>
        <span class="n">R_win_ratio</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;R_wins&#39;</span><span class="p">]</span><span class="o">/</span><span class="n">R_fght</span><span class="p">)</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="n">R_win_ratio</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mf">0.0</span><span class="p">)</span>
<span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;B_win_ratio&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">B_win_ratio</span>
<span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;R_win_ratio&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">R_win_ratio</span>

<span class="n">fights5</span> <span class="o">=</span> <span class="n">fights5</span><span class="p">[</span><span class="n">fights5</span><span class="o">.</span><span class="n">B_win_ratio</span> <span class="o">!=</span> <span class="mf">0.0</span><span class="p">]</span>
<span class="n">fights5</span> <span class="o">=</span> <span class="n">fights5</span><span class="p">[</span><span class="n">fights5</span><span class="o">.</span><span class="n">R_win_ratio</span> <span class="o">!=</span> <span class="mf">0.0</span><span class="p">]</span>

<span class="n">fights5</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[152]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>R_fighter</th>
      <th>B_fighter</th>
      <th>date</th>
      <th>Winner</th>
      <th>weight_class</th>
      <th>no_of_rounds</th>
      <th>B_current_lose_streak</th>
      <th>B_current_win_streak</th>
      <th>B_draw</th>
      <th>B_longest_win_streak</th>
      <th>...</th>
      <th>R_Weight_lbs</th>
      <th>B_age</th>
      <th>R_age</th>
      <th>B_avg_SIG_STR_pct</th>
      <th>R_avg_SIG_STR_pct</th>
      <th>B_encoded_stance</th>
      <th>R_encoded_stance</th>
      <th>encoded_winner</th>
      <th>B_win_ratio</th>
      <th>R_win_ratio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Henry Cejudo</td>
      <td>Marlon Moraes</td>
      <td>6/8/2019</td>
      <td>Red</td>
      <td>Bantamweight</td>
      <td>5</td>
      <td>0</td>
      <td>4</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>135.0</td>
      <td>31.0</td>
      <td>32.0</td>
      <td>0.466000</td>
      <td>0.466000</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0.800000</td>
      <td>0.800000</td>
    </tr>
    <tr>
      <td>1</td>
      <td>Valentina Shevchenko</td>
      <td>Jessica Eye</td>
      <td>6/8/2019</td>
      <td>Red</td>
      <td>Women's Flyweight</td>
      <td>5</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>3</td>
      <td>...</td>
      <td>125.0</td>
      <td>32.0</td>
      <td>31.0</td>
      <td>0.399000</td>
      <td>0.575714</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0.400000</td>
      <td>0.714286</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Tony Ferguson</td>
      <td>Donald Cerrone</td>
      <td>6/8/2019</td>
      <td>Red</td>
      <td>Lightweight</td>
      <td>3</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>8</td>
      <td>...</td>
      <td>155.0</td>
      <td>36.0</td>
      <td>35.0</td>
      <td>0.496129</td>
      <td>0.430000</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0.741935</td>
      <td>0.933333</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Jimmie Rivera</td>
      <td>Petr Yan</td>
      <td>6/8/2019</td>
      <td>Blue</td>
      <td>Bantamweight</td>
      <td>3</td>
      <td>0</td>
      <td>4</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>135.0</td>
      <td>26.0</td>
      <td>29.0</td>
      <td>0.550000</td>
      <td>0.366250</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>1.000000</td>
      <td>0.750000</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Tai Tuivasa</td>
      <td>Blagoy Ivanov</td>
      <td>6/8/2019</td>
      <td>Blue</td>
      <td>Heavyweight</td>
      <td>3</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>264.0</td>
      <td>32.0</td>
      <td>26.0</td>
      <td>0.310000</td>
      <td>0.545000</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>0.500000</td>
      <td>0.750000</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>3993</td>
      <td>George Sotiropoulos</td>
      <td>George Roop</td>
      <td>8/8/2009</td>
      <td>Red</td>
      <td>Lightweight</td>
      <td>3</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>155.0</td>
      <td>27.0</td>
      <td>32.0</td>
      <td>0.275000</td>
      <td>0.630000</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0.500000</td>
      <td>1.000000</td>
    </tr>
    <tr>
      <td>3995</td>
      <td>Jon Fitch</td>
      <td>Paulo Thiago</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Welterweight</td>
      <td>3</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>170.0</td>
      <td>28.0</td>
      <td>31.0</td>
      <td>0.290000</td>
      <td>0.523000</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>1.000000</td>
      <td>0.900000</td>
    </tr>
    <tr>
      <td>3996</td>
      <td>Brock Lesnar</td>
      <td>Frank Mir</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Heavyweight</td>
      <td>5</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>265.0</td>
      <td>30.0</td>
      <td>31.0</td>
      <td>0.543846</td>
      <td>0.750000</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0.769231</td>
      <td>0.666667</td>
    </tr>
    <tr>
      <td>3997</td>
      <td>Georges St-Pierre</td>
      <td>Thiago Alves</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Welterweight</td>
      <td>5</td>
      <td>0</td>
      <td>7</td>
      <td>0</td>
      <td>7</td>
      <td>...</td>
      <td>185.0</td>
      <td>25.0</td>
      <td>28.0</td>
      <td>0.524545</td>
      <td>0.585714</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0.818182</td>
      <td>0.857143</td>
    </tr>
    <tr>
      <td>3998</td>
      <td>Dan Henderson</td>
      <td>Michael Bisping</td>
      <td>7/11/2009</td>
      <td>Red</td>
      <td>Middleweight</td>
      <td>3</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>4</td>
      <td>...</td>
      <td>185.0</td>
      <td>30.0</td>
      <td>38.0</td>
      <td>0.480000</td>
      <td>0.545000</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0.875000</td>
      <td>0.666667</td>
    </tr>
  </tbody>
</table>
<p>2357 rows × 47 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We chose the stats stance (encoded), height, reach, age, and win ratio for both fighters as the independent variables of the regression, and the encoded winner as the dependend variable.</p>
<h3 id="Null-Hypothesis-for-Outcome:">Null Hypothesis for Outcome:<a class="anchor-link" href="#Null-Hypothesis-for-Outcome:">&#182;</a></h3><p>The set of 5 stats for each fighter in a fight do not affect the outcome of a fight: stance, height, reach, age, and win ratio.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[146]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">stats</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;B_encoded_stance&quot;</span><span class="p">,</span> <span class="s2">&quot;B_Height_cms&quot;</span><span class="p">,</span> <span class="s2">&quot;B_Reach_cms&quot;</span><span class="p">,</span> <span class="s2">&quot;B_age&quot;</span><span class="p">,</span> <span class="s2">&quot;B_win_ratio&quot;</span><span class="p">,</span> <span class="s2">&quot;R_encoded_stance&quot;</span><span class="p">,</span>\
         <span class="s2">&quot;R_Height_cms&quot;</span><span class="p">,</span> <span class="s2">&quot;R_Reach_cms&quot;</span><span class="p">,</span> <span class="s2">&quot;R_age&quot;</span><span class="p">,</span> <span class="s2">&quot;R_win_ratio&quot;</span><span class="p">]</span>
<span class="n">fighter_stats</span> <span class="o">=</span> <span class="n">fights5</span><span class="p">[</span><span class="n">stats</span><span class="p">]</span>
<span class="n">fighter_stats</span>

<span class="n">x</span> <span class="o">=</span> <span class="n">fighter_stats</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">fights5</span><span class="p">[</span><span class="s1">&#39;encoded_winner&#39;</span><span class="p">]</span>
<span class="n">lr</span> <span class="o">=</span> <span class="n">LogisticRegression</span><span class="p">()</span>
<span class="n">model</span> <span class="o">=</span> <span class="n">lr</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
<span class="n">lr</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[146]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>0.605006364022062</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We fit the model to the data and found that this model has an R-squared of .61, which means this model predics the outcome of a fight fairly well. This means we reject the null hypothesis.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[149]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">rating_coeffs</span> <span class="o">=</span> <span class="n">lr</span><span class="o">.</span><span class="n">coef_</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="o">.</span><span class="n">tolist</span><span class="p">()</span>
<span class="k">for</span> <span class="n">stat</span><span class="p">,</span> <span class="n">coef</span> <span class="ow">in</span> <span class="nb">zip</span><span class="p">(</span><span class="n">fighter_stats</span><span class="p">,</span> <span class="n">rating_coeffs</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Stat: </span><span class="si">{}</span><span class="s2">, Coefficient: </span><span class="si">{}</span><span class="s2">&quot;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">stat</span><span class="p">,</span> <span class="n">coef</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Stat: B_encoded_stance, Coefficient: -0.08529378550641614
Stat: B_Height_cms, Coefficient: 0.015362312616847227
Stat: B_Reach_cms, Coefficient: -0.018093308253343873
Stat: B_age, Coefficient: 0.0762790350084375
Stat: B_win_ratio, Coefficient: -0.28762072590755255
Stat: R_encoded_stance, Coefficient: 0.10614395124735776
Stat: R_Height_cms, Coefficient: -0.019988704173974955
Stat: R_Reach_cms, Coefficient: 0.019077211922674395
Stat: R_age, Coefficient: -0.06230404638908249
Stat: R_win_ratio, Coefficient: 0.7405461486232735
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Here is listed the statistics and their coefficients. It appears that for both corners, win ratio has the greatest effect on the outcome of the fight.</p>
<h1 id="Conclusion">Conclusion<a class="anchor-link" href="#Conclusion">&#182;</a></h1><h2 id="On-Predictions-of-Win-Ratio-and-Fight-Outcome">On Predictions of Win Ratio and Fight Outcome<a class="anchor-link" href="#On-Predictions-of-Win-Ratio-and-Fight-Outcome">&#182;</a></h2><p>We found that we can predict the fight outcome with some accuracy. There is room for improvement, however, so there are likely some interaction terms that would help with prediction.
We found that the model for predicting win ratio does not seem to predict the win ratio at all. There are likely other factors that could be used, or interaction terms that would likely predict much better.</p>

</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>
