[![Build Status](https://travis-ci.org/pstember/ruby-goof.svg?branch=master)](https://travis-ci.org/pstember/ruby-goof)

# Ruby Goof

1. Open a terminal and clone the repository

   ```console
   git clone git@github.com:pstember/ruby-goof.git
   ```

Open a terminal and open the `ruby-goof` directory.

2. Build the project

   ```console
   bundle install
   ```

3. Test the project

   ```console
   snyk test --file=Gemfile.lock
   ```

All-in-one to clone and run:

```console
git clone git@github.com:pstember/ruby-goof.git && \
cd ruby-goof && \
bundle install && \
snyk test --file=Gemfile.lock
```

## Screenshots

The following screenshot demonstrates the extra value provided when scanning a
project using the Snyk CLI tool

### Vulnerability detection

This screenshot shows vulnerabilities and potential remediation when such remediation exist

![Vulnerability detection screenshot](screenshots/vulnerabilities-screen.png "Vulnerability detection")

# Installing Ruby
```console
brew install rbenv
rbenv init
rbenv install 2.6.3
rbenv rehash
gem install bundler
rbenv rehash
```
Don't forget to update your `.bashrc` or `.zshrc` to include `eval "$(rbenv init -)"`
