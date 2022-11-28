# git-last 🤔

Are you tired of going over merged PRs just to find the last branch you were working on?<br />
Fear not - we got you covered!

By adding the following alias to your terminal, you'll be able to **view the last 10 branches** that you checked-out to:

```
alias git-last="git for-each-ref --sort=-committerdate refs/heads/ --count=10 --format='%(refname:short)'"
```


Then it's as easy as it gets:

<img width="233" alt="image" src="https://user-images.githubusercontent.com/20545256/204351557-18b94544-651c-480a-98e0-8c922f1aa650.png">


Note this depends on the directory you're in - it'll show the relevant branches per repository.
