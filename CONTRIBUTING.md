# Contributing to discord-fs

When contributing to the development of discord-fs, please first discuss the change
you wish to make via an [issue][issues] or any other contacting method with the maintainers
**before making a change**.

Please note we have a [Code of Conduct][code_of_conduct], please follow it in all
your interactions with the project.

# Table of contents

1. [Creating an issue](#issues-issues-and-more-issues)
1. [Template](#issue-template)
1. [Example of a good issue](#example-of-a-good-issue)
1. [Pull requests](#pull-request-process)

# Issues, issues and more issues!

There are many ways you can contribute to discord-fs, and all of them involve creating issues
in the [issue tracker][issues]. This is the entry point for your contribution.

To create an effective and high quality ticket, try to put the following information on your
ticket:

1.  An expressive title which allows the project maintainers to get a general
    understanding of your issue or feature request.
2.  A detailed description of the issue or feature request
    -   For issues, please add the necessary steps to reproduce the issue.
    -   For feature requests, add a detailed description of your proposal.

## Issue template

We provide multiple issue templates for different kinds of requests which we encourage you to use.
If for some reason none of the issue template currently available addresses the kind of ticket
you're trying to create. Please try to put as much information in your ticket as possible.

An simplified example can be found below:
```
[Title of the issue or feature request]

Detailed description of the issue. Put as much information as you can, potentially
with images showing the issue or mockups of the proposed feature.

If it's an issue, add the steps to reproduce and information
about your operating system like this:

System:
  - OS: Windows 10 (x64)
  - CPU: Intel Core i9-9900K
  - Ram: 32 GB DDR4 RAM
  - ...


Steps to reproduce:

1. Open VSCode
2. Open CONTRIBUTING.md
3. ...
```

## Example of a good issue

---

#### Example: Add CONTRIBUTING.md to describe how others may contribute user-generated content to the project.

We should add a CONTRIBUTING.md because it will clarify how contributors should contribute user-generated content
to the project. This will support new contributors just like the project maintainers, because once it's written,
the contribution guidelines are clear. Project maintainers can redirect new contributors or contributors which
don't follow the contribution guidelines to them, instead of replicating the same answers over and over again.
New contributors can read the contribution guidelines on their own instead of asking for them over and over again.

Some examples for projects using a CONTRIBUTING.md are:

-   https://example.com/project
-   https://example.com/project2
-   https://example.com/project3

For more information, there is a blog article from github on that<br/>
https://github.blog/2012-09-17-contributing-guidelines/

...

---

# Pull Request Process

Please ensure your pull request adheres to the following guidelines:

-   Search previous suggestions, as yours may be a duplicate.
-   Make sure your contribution is useful and relevant.
-   Make an individual pull request for each suggestion.
-   The pull request should be given a meaningful title.
-   All commits should be valid with the commitlint config.

    ```
          type(scope): summary

          A paragraph explaining your change in detail (optional).

          ref: <link to the bug ticket>
    ```

-   Ensure your text editor removes trailing whitespace and adds a final newline.
-   Ensure your code works and passes any tests (if available).
-   Ensure your code is properly documented.
-   Check your spelling and grammar.

You may merge the pull request in once you have the sign-off of the maintainers, or if you
do not have permission to do that, you may request the reviewer to merge it for you.

Copyright (c) 2022 [UnlimitedBytes][unlimitedbytes]

[unlimitedbytes]: https://unlimitedbytes.ovh
[code_of_conduct]: CODE_OF_CONDUCT.md
[issues]: https://github.com/unlimitedbytes/discord-fs/issues
