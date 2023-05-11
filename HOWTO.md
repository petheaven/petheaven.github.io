I ran the following commands in order to test locally:

1. brew install openssl
1. brew link --force openssl 
1. gem install eventmachine -- --with-cppflags=-I/usr/local/opt/openssl/include
1. bundle install


You can now run the following to test locally:
```
bundle exec jekyll serve
```