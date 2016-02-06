# 7-1 pattern SASS boilerplate
Create organized stylesheets using [SASS](http://sass-lang.com) with the [7-1 pattern](http://sass-guidelin.es/#the-7-1-pattern).

Within the sass folder, each subfolder contains a category of files that have specific functions. Those files get accumulated into '_import-***.scss'. Then, 'sass/main.scss' takes in all of the imports and interprets them into 'css/main.css'.

Import order ensures that important rules don't get overriden and that proper cascading is preserved.

A basic reset and clearfix are included in sass/base/reset.scss and sass/base/base.scss.
