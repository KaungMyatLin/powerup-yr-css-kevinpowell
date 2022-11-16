## this folder structure is for using SASS, SCSS.

##  .sass and .scss files are compile to regular css file. 
##  Css file then loaded as linkhref onto html, therefore it is pre-processor.
##  All css files can be bundled as one with webpack plugin "postcss-import".
##  That one file can be written in future syntaxes, drafted stage, with webpack plugin "postcss-preset-env".
##  That one file and all css in it can be minified with webpack plugin "cssnano".
##  That one file can either be loaded as linkhref onto html or an external regular css file with webpack plugin MiniCssExtractPlugin.