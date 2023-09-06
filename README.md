# CSCI 7850 - Deep Learning
CSCI 7850 - Deep Learning class at MTSU in teh Fall of 2023.

This repo `will` serve for the labs being worked on in this class.

## GII Push and Commit
I use the following commands to push to GIT:
```
git add .
git commit -a -m "Commit Message"
git push
```
You can also add the following to your `~/.bashrc` file like this:
```
gitpush() {
    git add .
    git commit -m "$*"
    git push
}
alias gp=gitpush
```

## Setup GIT on Linux Servers
I setup git on the MTSU servers by using a Persoanl Access token that is open to only the `public` repos I have for class. This can be done by creating the following:
<ol>
<li>Create a file in `~/.git-credentials`</li>
<li>Add a single line in thsi file like this: `https://richardhoehn:{personal_access_token}@github.com`</li>
<li>Run teh following command: `git config --global credential.helper store`</li>
</ol>
