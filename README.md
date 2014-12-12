static-website-basic-src-v2
=================

タスクランナー (grunt, gulp) の使用を前提とする、サイト基本構造のテンプレートです。
ディレクトリの構造を維持するために空のディレクトリに .gitkeep を配置していますので、適宜削除してください。

このテンプレートは

<a href="http://jade-lang.com/" target="_blank">Jade</a>  
<a href="http://sass-lang.com/" target="_blank">Sass/SCSS</a> + <a href="http://compass-style.org/" target="_blank">Compass</a>  
<a href="http://coffeescript.org/" target="jade">CoffeeScript</a>

を使用する前提で構成しています。

`_data.json` は Jade コンパイル時に読み込まれ、変数の内容がコンパイル後の HTML に反映されます。

assets/css/_utils.scss には spritesmith(<a href="https://github.com/Ensighten/grunt-spritesmith" target="_blank">grunt-spritesmith</a>, <a href="https://github.com/twolfson/gulp.spritesmith" target="_blank">gulp-spritesmith</a>) を使用する前提の mixin が含まれています。

