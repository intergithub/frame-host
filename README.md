# frame-host


# Homebrew Apache

class Httpd24 < Formula
  desc "HTTP server"
  homepage "https://httpd.apache.org/"
  url "https://archive.apache.org/dist/httpd/httpd-2.4.25.tar.bz2"
  sha256 "f87ec2df1c9fee3e6bfde3c8b855a3ddb7ca1ab20ca877bd0e2b6bf3f05c80b2"

## How do I install these formulae?
`brew install homebrew/apache/<formula>`

Or `brew tap homebrew/apache` and then `brew install <formula>`.

Or install via URL (which will not receive updates):

```
brew install https://raw.githubusercontent.com/Homebrew/homebrew-apache/master/<formula>.rb
```

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://github.com/Homebrew/brew/tree/master/docs#readme).

## Configuration
After installing `httpd22` or `httpd24`, the configuration files will be in `$(brew --prefix)/etc/apache2/2.2` and `$(brew --prefix)/etc/apache2/2.4`, respectively.
