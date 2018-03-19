# msf-with-rubymine
How to use metasploit with RubyMine

## 1. Set up your dev environnement 
Install the packages in the first step of this :
https://github.com/rapid7/metasploit-framework/wiki/Setting-Up-a-Metasploit-Development-Environment

## 2. Add a Gemfile in ~/.msf4 :
```
# ~/.msf4/Gemfile
source 'https://rubygems.org'
gem 'metasploit-framework', path:'/usr/share/metasploit-framework'
```

## 3. Run 'bundle install --path vendor/bundle' in ~/.msf4

## 4. Open rubymine \o/
```
~/.msf4$ mine .
```
Or open ~/msf4 as a rubymine project
