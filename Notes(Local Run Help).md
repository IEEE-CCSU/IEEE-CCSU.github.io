## Setting up Git Academic Pages on Windows:

#### Install Ruby
- Download and Install: [RubyInstaller](https://rubyinstaller.org/)

#### Terminal Commands to run:
    
    1. Remove eventmachine:
        - gem uninstall eventmachine --force
    
    2. Install eventmachine Ruby:
        - gem install eventmachine --platform ruby
    
    3. Install tzinfo-data:
        - gem install tzinfo-data
        Add in if not there: Gemfile in 'group :jekyll_plugins do'
            - gem 'tzinfo'
            - gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]


#### Install Issues - Helper Urls
- (https://github.com/jekyll/jekyll/issues/5935)
- (https://github.com/tzinfo/tzinfo/wiki/Resolving-TZInfo::DataSourceNotFound-Errors)
- (https://github.com/oneclick/rubyinstaller2/issues/96)


---


## Github Pages/Jekyll Setup Help Links
- https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll
- https://academicpages.github.io/markdown/
- https://mmistakes.github.io/minimal-mistakes/docs/configuration/#site-footer
- https://mmistakes.github.io/minimal-mistakes/docs/collections/
- https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/
- https://jekyllrb.com/docs/step-by-step/09-collections/


--- 