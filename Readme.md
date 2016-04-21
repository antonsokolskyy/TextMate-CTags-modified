##### Modified tmctags file for TextMate CTags budle. Allows to add ruby gems to ctag file.  

##### Requirements:  

- TextMate variable RUBY_GEMS_PATH_FOR_CTAGS with gems path (for example '/Users/user/.rvm/gems')  
- .ruby-version and .ruby-gemset files inside your project  

##### How to install:  

- install CTags bundle in TextMate preferences
- copy tmctags in '~/Library/Application Support/TextMate/Managed/Bundles/CTags.tmbundle/Support/bin'  

##### Features:  

- TM_CTAGS_EXCLUDED_DIRECTORIES variable allows to exclude specific folders from being added to ctags(for example 'node_modules,bower_components,vendor')  
  *  "*.js,*.coffee,*.css,*.scss" works as well