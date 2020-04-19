# .garaio-githooks

You can skip this checking with ```git commit --no-verify'```

Validates that you don't commit forbidden keywords to the repo

Validates that you don't commit on master branch

Validates that you don't commit forbidden files to the repo

## install

```bash
git clone https://github.com/garaio/.garaio-githooks.git ~/.garaio-githooks

git config --global core.hooksPath ~/.garaio-githooks
```
