Commit message format (version 1.2.0)
===================

##What is it?
This is a proposal of tags to be used in commit messages. The goal is to identify easily the different types of changes in the project's repo.

##Commit Message rules

####Subject desription (first line)
>1. Prefix the line with an applicable emoji (tag)
>2. Limit the subject line to 50 characters
>3. Separate subject from body with a blank line
>4. Capitalize the subject line
>5. Do not end the subject line with a period
>6. Use the imperative mood in the subject line

####Message body
>7. Wrap the body at 72 characters
>8. Use the body to explain the problems, limitations, and why it is necessary. Then to explain how was addressed the issue and the effects.

A complete description, rules and tips can be seen in [here][1].

####Tags and meaning
**NOTE:** The first commit does not have a label, and the message always is "**Initial commit**" as convention.

>* [style] when formatting or comments on code; no code change
>* [docs] when writing documentation
>* [code] when improving the format/structure of the code
>* [bug] when fixing a bug
>* [new] when adding new feature (see *Rules* section)
>* [api] when functions, methods or classes have been added or removed; method signatures or return types have changed
>* [typo] when typos in words or minimal changes in comment sentences
>* [misc] anything not covered by the above categories, e.g. rename or move files, add configuration files, add dataset
>* [test] when adding tests, refactoring tests; no production code change
>* [boost] when improving performance
>* [pkg] when libraries, frameworks, packages  or modules are added

####Subtags
Those subtags are used in order to provide the action that the commite does
>* *add* when something new has been added
>* *modify* when changes in files have been made
>* *move* when files are moved between directories
>* *remove* when files or directories are deleted
>* *update* when a package's version is changed (see *Rules* section)

When fixing something on:
>* *linux*
>* *macos*
>* *win*
>* *and* (*Android*)
>* *ios*
>* *winp* (*Windows Phone*)

Those subtags must be used just in combination with other tags to specify a particular change related to an O.S.
>Example:
>  [api|macos] Subject description

####Rules
The tag [new] is only used when you are doing a merge between the master and other feature-branch It is used to describe a feature.

The tag [update] must be used just when a package is updates.

##REFERENCES

1. [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/#why-not-how) Chris Beams
2. [TYPO3 CMS](http://wiki.typo3.org/CommitMessage_Format_(Git))
3. [Atom](https://atom.io/docs/v0.186.0/contributing)
4. [Karma](http://karma-runner.github.io/0.8/dev/git-commit-msg.html)

-------------
This document was last modified on : April. 6th, 2015.
