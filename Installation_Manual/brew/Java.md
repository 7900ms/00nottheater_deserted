```
> brew tap caskroom/versions
> brew search java

> brew cask info java8
> brew cask install java8
> brew cask install java8 --no-quarantine
> ls /Library/Java/JavaVirtualMachines
Java will be installed at /Library/Java/JavaVirtualMachines/jdk1.8.0_181.jdk

> brew install jenv
> echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.bash_profile
> echo 'eval "$(jenv init -)"' >> ~/.bash_profile

```
```
> jenv versions
> jenv add /Library/Java/JavaVirtualMachines/jdk1.8.0_181.jdk/Contents/Home
> jenv versions
> jenv global oracle64-1.8.0.181
> java -version
```
