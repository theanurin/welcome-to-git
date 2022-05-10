# Welcome To Git (self-learning course)

A course will help you to practice basics of Git to meet minimum requirements for Junior Developer position.

This is a self-learning course with automated knowledge testing. [See more details](https://illegal-knowledges.stopshitcode.org) about an approach...

## Get Started

1. [Fork](./fork) the repository. DO NOT CHANGE REPOSITORY NAME.

    [![Fork the repository!](http://static.illegal-knowledges.stopshitcode.org//welcome.files/fork.thumbnail.png)](http://static.illegal-knowledges.stopshitcode.org//welcome.files/fork.png)

1. Turn on workflows in your forked repository.

    [![Turn on workflows!](http://static.illegal-knowledges.stopshitcode.org//welcome.files/actions-enable.thumbnail.png)](http://static.illegal-knowledges.stopshitcode.org//welcome.files/actions-enable.png)

1. Solve a task challenge CHALLANGE_1.

1. Commit results.

1. See [Actions](./actions) to ensure your solution is correct.

1. Move to next task challenge CHALLANGE_2, CHALLANGE_3, ..., etc.

1. The finish the course make green job icon in [Actions](./actions).

    [![Check actions for success](http://static.illegal-knowledges.stopshitcode.org//welcome.files/actions-check-green.thumbnail.png)](http://static.illegal-knowledges.stopshitcode.org//welcome.files/actions-check-green.png)

## Q&A

### How to roll back the repo to first commit and delete all history?

For the case we made a tag `startrepotag` on first commit. All of you need is just execute two command in a terminal:

```shell
git reset --hard startrepotag
git push --force origin
```

References:
* https://stackoverflow.com/questions/16499908/how-to-roll-back-git-repo-to-first-commit-and-delete-all-history