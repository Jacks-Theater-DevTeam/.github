# Contributing Guidelines

Cool that you want to contribute to our projects. Please read the [Code of Conduct](CODE_OF_CONDUCT.md) before you start.

This is mostly a private organization so don't expect much.

## Where do I go from here?

If you've noticed a bug or have a feature request, make one! It's generally best if you get confirmation of your bug or approval for your feature request this way before starting to code.

## Fork & create a branch

If this is something you think you can fix, then fork our repository and create a branch with a descriptive name.

A good branch name would be (where issue #325 is the ticket you're working on):

```sh
git checkout -b 325-add-new-feature
```

## Implement your fix or feature

At this point, you're ready to make your changes!

## Make a Pull Request

At this point, you should switch back to your master branch and make sure it's up to date with our master branch:

```sh
git remote add upstream git@github.com:YourOrg/YourRepo.git
git checkout master
git pull upstream master
```

Then update your feature branch from your local copy of master, and push it!

```sh
git checkout 325-add-new-feature
git rebase master
git push --set-upstream origin 325-add-new-feature
```

Finally, go to GitHub and make a Pull Request

Honestly we don't really care if you open a ticket first or just make a PR. It's up to you.

All this text above is just guidelines, we don't actually care.

If you are still here, you are wasting your time.

This whole thing has been AI generated, with some edits.