# homebrew-php56
In a perfect world such things would not be necessary.

```bash
# *sigh*
brew tap bryonbean/homebrew-php56 git@github.com:bryonbean/homebrew-php56.git 
brew reinstall php@5.6
```
## Update...
My multiple versions of php were originally set up by way of this [great post](https://getgrav.org/blog/macos-mojave-apache-multiple-php-versions). I should have checked it before creating this because the author keeps it up-to-date in spectacular fashion. Sure enough it seems that there is already `homebrew-deprecated` being maintained which services both php@5.6 and php@7.0.

```bash
brew tap exolnet/homebrew-deprecated
```
