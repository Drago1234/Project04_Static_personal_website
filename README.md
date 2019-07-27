# Project04_Static_personal_website


### How to get started? (For window user)

* ridk install --> Install the rubyinstaller for window user after download (choose 1, 2, 3 based on your preference, I suggesst try 1 --> 2 --> 3, 3 can be useful for rails, 1 is base set up, allow you to use ruby. 2 is update your current version of ruby)
* ruby -v --> Check your current ruby version
* where ruby --> Checking you ruby.exe path
* set PATH=%PATH%;C:\Ruby200-x64\bin --> add Ruby to the PATH variable on Windows

Open your cmd from project folder
* gem install bundler --> An package management tool
* bundle update 
* bundle install --> Update and install your required gem library based on your Gemfile specification. (Which assume you had download a useable project from somebody)
* gem install middleman --> Install this gem if you don't have (A static page generator that used to implement this project)
* middleman build --> Build the static pages, and go to build folder click the index.html to visit at the website
Alternative: 
* middleman server --> The website will be automatically deploied in your local host without build(Recommended)
