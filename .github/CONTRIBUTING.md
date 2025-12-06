<!-- markdownlint-disable MD033 -->
# Contributing to FOSSBilling

:+1::tada: First off, thanks for expressing an interest in contributing to FOSSBilling! :tada:

Whether open-source projects thrive or fade depends on community participation and involvement. This one is no exception, so we appreciate and welcome every contribution.

The document is a set of guidelines for contributing to FOSSBilling code and documentation, which are hosted in the [FOSSBilling Organization](https://github.com/FOSSBilling) on GitHub. These are strong guidelines but not set in stone rules. Please use your best judgement, feel free to propose changes to this document in a pull request, and don't be afraid to ask questions.

We've tried to keep this document as short as possible but there is a lot of information to get through. Don't worry if you're new to open source or FOSSBilling; we're happy to help you get started! If you are looking for something specific then you can use the table of contents to skip to that section:

## Contents

* [Why Should I Contribute to FOSSBilling?](#why-should-i-contribute)

* [Before You Get Started](#before-you-get-started)
  * [Code of Conduct](#code-of-conduct)

* [How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Improvements](#suggesting-improvements-or-new-features)
  * [Contributing Code](#contributing-code)
  * [Writing Documentation](#writing-documentation)
  * [Translating FOSSBilling](#translating-fossbilling)
  * [Sponsoring the Project](#sponsoring-the-project)

* [Style Guides](#style-guides)

* [But, I Still Have a Question](#but-i-still-have-a-question)

## Why Should I Contribute?

In one simple sentence, every contribution means not just that you give something back to the community but also that you get to use and enjoy better software.

If you need more reasons than that though, then because...

* __Shape the project's future__. There are likely open issues in this repository (and the main FOSSBilling repo), by taking part in the discussion and submitting code contributions to work on the ones that are most important to you, you get to shape the future of the project.
* __Develop your skills__. Whether you are writing PHP or writing documentation, being a part of a collaborative project with others actively reviewing your work helps you to build your skills.
* __It's fun__. We are building modern and exciting open source software, there are going to be a lot of challenges along the way, and taking part in solving them is fun and satisfying.

## Before You Get Started

### Code of Conduct

First off, no matter how you plan to take part, please take a couple of minutes to read our code of conduct before contributing anything.

This project and everyone participating in it are governed by the [FOSSBilling Code of Conduct](.github/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the moderators on our [Discord](https://fossbilling.org/discord) server.

## How Can I Contribute?

There are a lot of different ways that you can get involved in the FOSSBilling project. Let's take a look at some of the main ones:

### Reporting Bugs

If you find a bug in FOSSBilling, please report it. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer:, and find related reports :mag_right:.

#### Before Submitting a Bug Report

⚠️ If your report is for a potential security exploit, please do not make it public by creating an Issue, but instead, follow the instructions in our [Security Policy](https://github.com/FOSSBilling/.github/security/policy).

Firstly, __search existing issues__ to see if the problem has already been reported. If it has __and the issue is still open__, add a comment to the existing issue instead of opening a new one.

> __Important Note:__ If you find a _Closed__ issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which project your bug is related to, create an issue in the appropriate repository and provide the following information by filling in [the template](https://github.com/FOSSBilling/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

__Include these key details:__

* __Use a clear and descriptive title__ for the issue to identify the problem.
* __Describe the exact steps which reproduce the problem__ in as much detail as possible. For example, start by explaining what section exactly you used in the browser, or which API call you were using. When listing steps, __don't just say what you did but explain how you did it__.
* __Provide specific examples to demonstrate the steps__. Include links to files or GitHub projects, or copy/pastable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* __Describe the behavior you observed after following the steps__ and point out what exactly is the problem with that behavior.
* __Explain which behavior you expected to see instead and why.__
* __Include screenshots and animated GIFs__ which show you following the described steps and demonstrate the problem.
* __If the problem wasn't triggered by a specific action__, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* __Can you reliably reproduce the issue?__ If not, provide details about how often the problem happens and under which conditions it normally happens.
* If the problem is related to working with files (e.g. opening and editing files), __does the problem happen for all files and projects or only some?__ Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or Python files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?

Include details about your configuration and environment:

* __If applicable, which version of FOSSBilling are you using?__ For the main project, you can get the exact version by running `https://<your domain>/api/guest/system/version` in your browser.
* __What's the name and version of the server OS your FOSSBilling installation is running?__
* __What's the PHP version your server is using?__
* __What's the MySQL version your server is using?__
* **What's the Web Server and version you're using?__

### Suggesting Improvements or New Features

⚠️ Please note the title is __*Suggesting*__, not __*Demanding*__. Be polite, appreciate other people's time, and explain in detail, and you are far more likely to get what you want!

FOSSBilling is not designed to be everything for everyone, but we do want it to be as useful and usable as possible for billing and client management. If you have a suggestion for a new feature or an improvement to an existing one then please do submit it. Please be as clear and explicit as you can and provide as much detail as you can, this will make it much easier for the community and maintainers to understand your suggestion and take action.

Before creating enhancement suggestions, please check through the existing issues in this repository and the main [FOSSBilling repository](https://github.com/FOSSBilling/FOSSBilling/issues) and see if somebody has already made the same suggestion. If they have then please don't create a new issue, but instead, add your thoughts and comments to the existing one.

### Contributing Code

The source code is the heart of FOSSBilling, and we are always interested in quality contributions to improve it, squash bugs, and close open issues. Please follow these guidelines to make things easier for yourself and other contributors.

#### What to Work On

Check out our upcoming Milestones (if available) for an overview of what needs to be done. See the Good first issue label for a list of issues that should be relatively easy to get started with. If there's anything you're unsure of, don't hesitate to ask! All of us were just starting once.

If you're planning to go ahead and work on something, please leave a comment on the relevant issue or create a new one explaining what you are doing. This helps us divide our efforts more sensibly by ensuring that we are not all doing the same thing at the same time.

#### Local Development

Instructions on how to do this are usually provided in this repository's README file, or check the main [FOSSBilling repository](https://github.com/FOSSBilling/FOSSBilling) for general guidance.

#### Making a Pull Request

The process described here has several goals:

* Maintain FOSSBilling's quality
* Fix problems that are important to users
* Engage the community in working toward the best possible FOSSBilling
* Enable a sustainable system for FOSSBilling's maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow the [Style Guides](#style-guides)
2. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

Before a PR can be merged it must pass all of the automated tests and also be reviewed by two maintainers. All of the above requirements must be met before your pull request will be reviewed. Please ensure your code includes appropriate tests where applicable, and be aware that reviewers may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

### Writing Documentation

Great code is only one-half of any successful project, and great documentation is just as important. The reality is that open source projects can stand or fall based on the quality of their documentation.

For the main FOSSBilling project, documentation is hosted here: [FOSSBilling Docs](https://fossbilling.org/docs)

Documentation is built using [Nextra](https://nextra.site/) from this [GitHub repository](https://github.com/FOSSBilling/docs). You can contribute directly to the repo on GitHub or using the _Edit this page_ links on each page of the docs site.

Please try to be thorough and clear when writing directions. Something might seem obvious to you, but do not assume that it is to everybody else.

### Translating FOSSBilling

We would like FOSSBilling to be available to as many people in as many languages as possible. *This primarily applies to the main FOSSBilling project and user-facing interfaces.*

The software is primarily written in English. If you are a native or fluent speaker of another language then we could use your help with the translations.

We use Crowdin to manage translations. You can take a look at the [getting started guide](https://support.crowdin.com/crowdin-intro/), and then get involved in translating at [https://translate.fossbilling.org](https://translate.fossbilling.org).

### Sponsoring the Project

If you do not have the time or necessary skills to actively take part in the development or documentation of the project then you can still play a part by making a financial contribution to the project. This could be a one-time contribution or a recurring monthly donation.

You can do this using [GitHub Sponsors](https://github.com/sponsors/FOSSBilling) or on [Open Collective](https://opencollective.com/FOSSBilling).

## Style Guides

### Commit Messages Style Guide

Please be as clear and descriptive as possible in your commit messages, it makes it much easier for everyone to follow them.

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move the cursor to..." not "Moves the cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title

__Example:__

```text
Fix login redirect issue when session expires
Resolves #123
```

### AI and LLM Usage

Usage of AI assistance is generally acceptable, but you are responsible for ensuring the quality of the output meets the project's standards. Currently, AI-generated content is often too verbose and its quality is typically subpar compared to what most human contributors produce.

Do not use an AI or LLM to generate changes, respond to issues, or interact with PRs without holding the output to the same standards as human-written content. All contributions, whether AI-assisted or not, must undergo the same review process and meet the same quality requirements.

### PHP Style Guide

If this repository contains PHP code, it should adhere to [PSR-12](https://www.php-fig.org/psr/psr-12/) (unless otherwise specified).

### Documentation Style Guide

Good documentation is clear, concise, and helpful. We follow the [GitHub Docs style guide](https://docs.github.com/en/contributing/style-guide-and-content-model/style-guide) as our foundation.

__Key principles to keep in mind:__

* __Write for your audience:__ Use clear, everyday language. If you need technical terms, explain them
* __Be concise:__ Get to the point quickly, but don't sacrifice clarity for brevity
* __Use active voice:__ "Click the button" is better than "The button should be clicked"
* __Include examples:__ Show, don't just tell. Code snippets and screenshots are your friends
* __Structure content logically:__ Use headings, lists, and tables to break up information

__For technical details:__

* We use Markdown for documentation (with MDX support where available)
* If you're working on the main documentation site, it's built with [Nextra](https://nextra.site/docs/guide/markdown)
* Follow the existing format and tone in the documentation you're contributing to

When in doubt, read it out loud; if it sounds natural and clear to you, it'll probably sound clear to others too.

## But, I Still Have a Question

Ask in the [forum](https://forum.fossbilling.org/) or drop a message to the [Discord](https://fossbilling.org/discord) community with a question. Sometimes it takes time to respond; please be patient!
