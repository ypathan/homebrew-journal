# cli journal application that feels like yazi

## how to install ?
1. `brew tap ypathan/journal`
2. `brew tap ypathan/journal/journal`


### pushing new update
1. `git tag v0.1.3`
2. `git push origin v0.1.3`
3. `curl -sL https://github.com/ypathan/journal/archive/refs/tags/v0.1.3.tar.gz | shasum -a 256` >> git
4. update values in Formula/journal.rb
5. push to github main branch
6. when users run `brew update` they will be notified of this change

