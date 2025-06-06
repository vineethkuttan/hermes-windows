# Contributing to Hermes
We want to make contributing to this project simple and convenient.

This document provides a high level overview of the contribution process,
please also review our [Coding Standards](doc/CodingStandards.md).

## Code of Conduct
Facebook has adopted a Code of Conduct that we expect project participants to
adhere to. Please [read the full text](https://code.fb.com/codeofconduct/) so
that you can understand what actions will and will not be tolerated.

As an official Microsoft fork, this project has also adopted the Microsoft Open
Source Code of Conduct available
[here](https://opensource.microsoft.com/codeofconduct/).

## Our Development Process
Facebook's internal repository remains the source of truth. It is
automatically synchronized with GitHub. Contributions can be made through
regular GitHub pull requests.

## Pull Requests
We actively welcome your pull requests. If you are planning on doing a larger
chunk of work or want to change an external facing API, make sure to file an
issue first to get feedback on your idea.

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. Ensure the test suite passes and your code lints.
4. Consider squashing your commits (`git rebase -i`). One intent alongside one
   commit makes it clearer for people to review and easier to understand your
   intention.
5. If you haven't already, complete the Contributor License Agreement ("CLA").

## Copyright Notice for files
Copy and paste this to the top of your new file(s):

```
/**
 * Copyright (c) Microsoft Corporation. All rights reserved.
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
 */
```

When contributing a new file back to facebook/hermes, change this header to:

```
/**
 * Copyright (c) Meta Platforms, Inc. and affiliates.
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
 */
```

## Contributor License Agreement ("CLA")
This project welcomes contributions and suggestions.  Most contributions require
you to agree to a Contributor License Agreement (CLA) declaring that you have
the right to, and actually do, grant us the rights to use your contribution. For
details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether
you need to provide a CLA and decorate the PR appropriately (e.g., status check,
comment). Simply follow the instructions provided by the bot. You will only need
to do this once across all repos using Microsoft's CLA.

## Issues
We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

Facebook has a [bounty program](https://www.facebook.com/whitehat/) for the
safe disclosure of security bugs. In those cases, please go through the process
outlined on that page and do not file a public issue.

Please see SECURITY.md for Microsoft's policies on reporting security
vulnerabilities.

## Coding Style
* The Hermes coding style is generally based on the
  [LLVM Coding Standards](https://llvm.org/docs/CodingStandards.html).
* Match the style you see used in the rest of the project. This includes
  formatting, naming things in code, naming things in documentation.
* Run `clang-format`, using the provided `.clang-format` configuration.

## License
By contributing to Hermes, you agree that your contributions will be licensed
under the LICENSE file in the root directory of this source tree.
