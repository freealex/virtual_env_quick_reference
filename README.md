# virtual_env_quick_reference
'I'm throwing this together quickly, because I am tired of making small syntax errors based on the language of the day.'


#Virtual Environment(s) Quick Reference

##rbenv

$ brew install rbenv # Installation for mac
$ rbenv init    # initialize rbenv
$ rbenv install -l  # list all available versions:
$ rbenv install 2.0.0-p247 # install a Ruby version
$ rbenv local 1.9.3-p327 # sets the local ruby version
$ rbenv local -unset #unset the local version
$ rbenv global 1.9.3-p327 # set the global system version of ruby
$ rbenv versions #list all ruby versions known to rbenv
$ rbenv shell 1.9.3 # set shell specific ruby.


##jEnv

$ brew cask install java #this will install java10
# To install java 8, you can use the below commands
$ brew tap caskroom/versions
$ brew cask install java8

$ brew install jenv #install jenv in mac OS
$ jenv add /System/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home
$ jenv add /Library/Java/JavaVirtualMachines/jdk17011.jdk/Contents/Home


$ jenv versions #shows all the jenv added versions
$ jenv global oracle64-1.6.0.39 # Configure global version
$ jenv local oracle64-1.6.0.39 # Configure local version (per directory)
$ jenv shell oracle64-1.6.0.39 # Configure shell instance version

#credits -> Bhagavathi Dhass. Thanks for the notes!
check out his medium article! : https://medium.com/@bhagavathidhass/virtual-environments-for-python-ruby-and-java-87743478ae38 




