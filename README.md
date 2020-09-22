# virtual_env_quick_reference
'I'm throwing this together quickly, because I am tired of making small syntax errors based on the language of the day.'


#[Virtual Environment(s) Quick Reference]

#rbenv

$ [brew install rbenv # Installation for mac]

$ [rbenv init    initialize rbenv ] 

$ rbenv install -l  [ist all available versions ] 

$ rbenv install 2.0.0-p247 (install a Ruby version)

$ rbenv local 1.9.3-p327 (sets the local ruby version )

$ rbenv local -unset (unset the local version)

$ rbenv global 1.9.3-p327  (set the global system version of ruby)

$ rbenv versions (list all ruby versions known to rbenv)

$ rbenv shell 1.9.3  (set shell specific ruby.)


##jEnv

(download)
$git clone https://github.com/jenv/jenv.git ~/.jenv

#install

#bash
$ echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.bash_profile
$ echo 'eval "$(jenv init -)"' >> ~/.bash_profile


#zscrc
$ echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.zshrc
$ echo 'eval "$(jenv init -)"' >> ~/.zshrc
-->installl configured itsetlf on Catalina :), but here are more steps if needed for others

#configure 

$ jenv add /System/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home
  oracle64-1.6.0.39 added
$ jenv add /Library/Java/JavaVirtualMachines/jdk17011.jdk/Contents/Home
  oracle64-1.7.0.11 added


