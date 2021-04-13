# How to set pre-commit

## gem install
```
gem install pre-commit
```

## confirm file
```
ls -la .git/hooks/
```

## confirm setting list
```
pre-commit list
```

## pre-commit settingｓ for using rubocop
```
git config pre-commit.checks rubocop
```
## how to cancel the setting
```
# Either way
rm .git/hooks/pre-commit # remove file
mv .git/hooks/pre-commit .git/hooks/pre-commit.ruby.sample # rename file
```
