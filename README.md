# Ruby Goof

Open a terminal and open the `ruby-goof` directory.

1. Build the project

   ```console
   bundle install
   ```

2. Test the project

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

All of these screenshots demonstrate the extra value provided when scanning a
project using the Snyk CLI tool

### Vulnerability detection

This screenshot shows vulnerabilities and potential remediation when such remediation exist

![Vulnerability detection screenshot](screenshots/vulnerabilities-screen.png "Vulnerability detection")
