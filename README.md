<img src="assets/img/r3-training-logo.png" height="150px"/>

# Advanced git course - Practice repository

## Make your changes

Copy the file `template.md` in the folder `_attendees` and rename it with your firstname:

```bash
$ cd _attendees
$ cp template.md myName.md
```

Then, make your changes with your favorite editor!

## Commit your changes and push

When you are done editing your file, add the file to the stage and commit it:
```bash
$ git add myName.md
$ git commit -m "Edit the content of the subpage myName.md"
```

Once you are done committing, you can push your branch to your fork:
```
$ git push origin myBranch
```

## Open a pull-request

If you now browse to your fork on Github, you can open a pull request and submit it for review.

:warning: Please make sure to select `develop` as the target branch.

:warning: Watch out for comments from the reviewer! If there are things to be changed, simply change locally, commit,
and then push again. The pull-request will update automatically.

Once the pull request has been accepted, you will be able to see your page online! :tada: