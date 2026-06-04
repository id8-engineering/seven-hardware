# Contributing

Thank you for showing interest in contributing. We hope you will find what youneed to get started
on this page.

This guide is largely based on 
https://github.com/EnAccess/Cicada-GSM-HW/blob/main/CONTRIBUTING.md/main/CONTRIBUTING.md

## Contributions

Contributions to
[seven-hardware](https://github.com/id8-engineering/seven-hardware/) are done by first creating
an issue [here](https://github.com/id8-engineering/seven-hardware/issues). The change request will
be disussed and if approved a pull-request can be opened.

## Getting started

Review the existing issues and the discussion thread to ensure your issue has not been previously 
addressed.

## Issues

Issues are created [here](https://github.com/id8-engineering/seven-hardware/issues/new/choose)

### How to Contribute to Issues

For any issue, there are fundamentally three ways an individual can contribute:

- **By opening the issue for discussion:** If you believe that you have found a
  new bug in this project, you should report it by creating a new issue in the
  [issue tracker](https://github.com/id8-engineering/seven-hardware/issues).
- **By helping to triage the issue:** You can do this either by providing
  assistive details (a reproducible test case that demonstrates a bug) or by
  providing suggestions to address the issue.
- **By helping to resolve the issue:** This can be done by demonstrating that
  the issue is not a bug or is fixed, but more often, by opening a pull request
  that changes the source in a concrete and reviewable manner.

## Submitting a Bug Report

To submit a bug report:

- When opening a new issue in the
  [issue tracker](https://github.com/id8-engineering/seven-hardware/issues/new/choose).
  The two most important pieces of information needed to evaluate the report are
  a description of the bug and a simple test case to recreate it. It is easier
  to fix a bug if it can be reproduced.
- See
  [How to create a Minimal, Complete, and Verifiable example](https://stackoverflow.com/help/mcve).

## Triaging a Bug Report

It's common for open issues to involve discussion. Some contributors may have differing 
opinions, including whether the behavior is a bug or a feature. This discussion is part of the
process and should be kept focused, helpful, and professional.

Terse responses that provide neither additional context nor supporting detail are not helpful or
professional. To many, such responses are annoying and unfriendly.

Contributors are encouraged to collaborate on solving issues and help one another make progress.
If you encounter an issue that you feel is invalid or that contains incorrect information, explain
why you feel that way with additional supporting context, and be willing to be convinced that you
may be wrong. By doing so, we can often reach the correct  outcome faster.

## Resolving a Bug Report

Most issues are resolved by opening a pull request. The process for opening and reviewing a pull
request is similar to that of opening and triaging issues, but carries with it a necessary review 
and approval workflow that ensures that the proposed changes meet the minimal quality and functional
guidelines of this project.

## Languages

We accept issues in **any** language. When an issue is posted in a language besides English, it is
acceptable and encouraged to post an English-translated copy as a reply. Anyone may post
the translated reply. In most cases, a quick pass through translation software is sufficient.
Having the original text as well as the translation can help mitigate translation errors.

Responses to posted issues may or may not be in the original language.

## Setting up your Environment

⚠️ **Heads up!** If you'd like to work on issues, please ensure you fork the repository, create a
new branch, and work on this branch to avoid pushing your changes directly to the master/main branch.

Follow the steps outlined in the repo's ReadMe file for local development.

Create a new branch by typing this command:

```bash
git switch -c <branch-name>
```

Change the branch name to whatever you want. For example:

```bash
git switch -c update-silcscreen
```
## Sign your work

This project is licensed under an open hardware license. To ensure license compatibility and
traceability, we need to keep track of the origin of all commits and make sure they comply with the
license terms.  To achieve this, we follow the same procedure as used by the Linux kernel and many
other open source projects: **every commit must be signed off**.

The sign-off is a simple line added at the end of your commit message which certifies that you wrote
the code or otherwise have the right to pass it on as an open source contribution.

The rules are simple: if you can certify the following statement
(from [developercertificate.org](http://developercertificate.org)), then you can sign off your work.

```
**Version 1.1**

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.  
660 York Street, Suite 102,  
San Francisco, CA 94110 USA  

Everyone is permitted to copy and distribute verbatim copies of this license document, but changing
it is not allowed.

#### Developer’s Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I have the right to submit it under 
    the open source license indicated in the file; or  

(b) The contribution is based upon previous work that, to the best   of my knowledge, is covered
    under an appropriate open source license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part by me, under the same open source
    license (unless I am permitted to submit under a different license), as indicated in the file;
    or

(c) The contribution was provided directly to me by some other person who certified (a), (b), or
    (c) and I have not modified it; and

(d) I understand and agree that this project and the contribution are public and that a record of
    the contribution (including all personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with this project or the open 
    source license(s) involved.
```

Then you just add a line to every git commit message:
```bash
Signed-off-by: Your Name your.email@example.com
````

Use your real name (no pseudonyms or anonymous contributions).

If you have set your `user.name` and `user.email` in Git, you can sign off your commits 
automatically by using:

```bash
git commit -s -m "feat: add new feature"
````

## Pull Requests

Pull Requests are the way concrete changes are made to the code, documentation, dependencies, and
tools contained in this project's repository.

Prior to creating a Pull Request, it is recommended to familiarize yourself with how a project can
be developed and tested locally.

### Local Hardware Checks

Contributors should use KiCad 10 when working on the hardware files.

Before committing and pushing changes, please run the local KiCad checks:

- DRC: Design Rule Check. This checks the PCB layout against the board design rules.
- ERC: Electrical Rule Check. This checks the schematic for electrical issues.

These tests are also executed in CI when when a pull-request is created or updated.

### Creating a Pull Request

To create a pull request, please ensure that an existing issue exists and that you have been
assigned to it, unless your change is minor, such as fixing a typo. This allows the maintainer to
provide guidance and prioritize tasks; otherwise, you may risk spending time on something that
doesn't get accepted for various reasons.

We acknowledge everyone's contributions and strive for transparent communication. We highly 
recommend clear communication before undertaking any work. Upon issue assignment, two options are
available to you:

1. Use the GitHub interface to fork the repo, make an edit right here in the GitHub client, and
   then submit a pull request (no code or terminals or IDE required).
   [This guide](https://guides.github.com/activities/hello-world/) shows just how to do that for a
   small personal repo. You would simply replace creating a new repository by navigating to this 
   one and forking it instead. This is a great idea if you simply plan to add to or edit one of the
   Markdown files we use for documentation in this project.

2. Fork the repo, create a local copy of that fork, and work on your changes that way.
   For that, [we recommend this guide](https://www.dataschool.io/how-to-contribute-on-github).

## Conventional Commits

When creating a Pull Request, please follow the official
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

## Waiting for Review

Waiting plays a pivotal role in your contributor journey. Please be patient if the maintainers do
not review your pull request immediately after submission. It might take time for one to be in the
right condition to review all submitted pull requests. We would rather not rush a response after
someone has taken the time and effort to submit it. If it has been over one week and you haven't
received any acknowledgement, you can post a comment on your PR as a reminder.

The purpose of reviews is to create the best experience we can for our contributors.
Please be aware of the following:

1. Reviews are always respectful, acknowledging that everyone did the best possible job with the
   knowledge they had at the time.
2. Reviews discuss content, not the person who created it.
3. Reviews are constructive and start a conversation around feedback. Embrace the feedback!

If the pull request looks good, a maintainer will typically provide feedback and merge the request
immediately. Otherwise, they will let you know what questions they have or what needs to
change before your work can be accepted. Once it is, you'll see your changes on the master branch,
and your open-source contribution will be complete!
