Commit message format (version 1.9)
===================

## What is it?
This is a proposal of tags to be used in commit messages. The goal is to identify easily the different types of changes in a repo.

## Commit Message rules

Layout for a commit message
```
[tag>subtag] subject description

body: used to explain the what and why of a commit, not the how. Wrap the body at 72 characters in each line.

footer: used to reference issue tracker IDs.
```

####Subject desription (first line)
> 1. Prefix the line with an applicable tag
> 2. Limit to 50 characters
> 3. Use an imperative tone
> 4. Separate subject from body with a blank line
> 5. Capitalize the subject line
> 6. Do not end the subject line with a period


#### Tags and meaning for source code
**NOTE:** The first commit does not have a label, and the message always is "**Initial commit**" as convention.

>* **[core]** when functions, methods or classes have been added, modified or removed; method signatures or return types have changed
>* **[main]** when dealing with a file that is used as view, notebook or main script
>* **[test]** when adding tests, refactoring tests; no production code change

>* **[style]** when improving the format/structure of the code, without modifying the previous functionality
>* **[docs]** when writing documentation, formatting or comments on code; no code change


>* **[pkg]** when libraries, frameworks, packages or modules are added
>* **[misc]** anything not covered by the above categories, e.g. rename or move files, add configuration files, add dataset


**NOTE:** The tag **[feat]** is only used when you are doing a merge between a feature-branch and develop.

>* **[feat]** when adding a new feature

#### Subtags
Those subtags are used in order to provide the action that the commit does

>Example:
>  [core>new] Subject description

Can be used in combination with the tags: *core*, *main* and *test*
>* **new** when functionality has been added
>* **change** when changes in code have been made
>* **boost** when refactoring or improving performance
>* **fix** when fixing a bug


## REFERENCES

1. [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/#why-not-how) Chris Beams
2. [TYPO3 CMS](http://wiki.typo3.org/CommitMessage_Format_(Git))
3. [Udacity](https://udacity.github.io/git-styleguide/)
-------------
This document was last modified on : July 10th, 2018.
