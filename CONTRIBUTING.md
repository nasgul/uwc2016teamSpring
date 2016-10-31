Generally, uwc2016teamSpring follows a standard [fork and pull][0] model for contributions via GitHub pull requests. Thus, the
_contributing process_ looks as follows:

0. [Pick an issue](#pick-an-issue)
1. [Write code](#write-code)
2. [Write docs](#write-docs)
3. [Submit a PR](#submit-a-pr)

## Pick an issue

* On [Waffle][5], pick any issue from column "Ready"
* On Github, leave a comment on the issue you picked to notify others that the issues is taken
* On [Gitter][6] or Github, ask any question you may have while working on the issue

## Write Code
uwc2016teamSpring follows good code style guide. When in doubt, look around the codebase and see how it's done
elsewhere.

* Code and comments should be formatted to a width no greater than 120 columns
* Files should be exempt of trailing spaces
* Each implicit conversion (if possible) should be defined in the corresponding companion object

That said, the Scala style checker `sbt scalastyle` should pass on the code.

## Write Docs
Write clean and simple docs in the `docs` folder.

## Submit a PR
* PR should be submitted from a separate branch (use `git checkout -b "fix-123"`)
* PR should generally contain only one commit (use `git commit --amend` and `git --force push` or [squash][4] existing commits into one)
* PR should not decrease the code coverage more than by 1%
* PR's commit message should use present tense and be capitalized properly (i.e., `Fix #123: Add tests for Endpoint`)

[0]: https://help.github.com/articles/using-pull-requests/
[1]: http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html

