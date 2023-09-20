# Cognigy xApps

"Cognigy xApps are mobile first, micro web applications that empower enterprises to elevate and unify channel experiences with multimodal service uniting text, multimedia, and voice. Customize and seamlessly blend rich, interactive micro web applications into your conversational experiences. Cognigy xApps let you leverage the best of text, graphical, touch and voice interfaces to delight customers with outstanding service on their preferred channels, all within a single experience. [(Cognigy, 2023)](https://www.cognigy.com/platform/cognigy-xapps)"


## Contents

- [Get Started](https://docs.cognigy.com/ai/xApp/overview/)

## Overview

This repository contains the source code of existing xApps which can be used as blueprints for further developments. Therefore, all of them are provided under the [MIT license](./LICENSE).

You are subject to the terms of the third-party providers which you are connecting to when you use xApps. Cognigy cannot take responsibility for your use of the third-party services, systems or materials. Cognigy.AI xApps are licensed under the MIT license.

## Approval Process

If you want us to approve your xApp, please note the following approval process:

1. Add a `README.md` to your module and describe all nodes in detail.
2. Check your code for hardcoded passwords, tokens or outdated JavaScript/HTML/CSS usage (e.g. `var foo;`).
3. Create a new Pull Request for your xApp feature branch.
4. Send all information and data, which are required to use the xApp, to the following E-Mail address:
    - support at cognigy.com

**Important:** \
Please note, that Cogngiy does not provide enterprise support for developed xApps. This repository is licensed under MIT, in which the community is responsible for the shared modules. If you found a bug or want to improve yet developed functionalities, please don't hesitate to create a branch.

### Create a new xApp or fix a bug

In order to create a new xApp, please create a new feature branch:

- `git checkout -b feature/<your-feature>`

If you want to fix an existing module, please create a bug branch:

- `git checkout -b bug/<module-name>`

## New Feature Request

Next to the already published xApps, there are a lot of use-cases out there that could be used with Cognigy.AI in the future as well. Therefore, one can follow these steps to request a new xApp if there are no developer resources to develop it on their own:

1. [Check if there is a branch that already implements your requested xApps / feature](https://github.com/Cognigy/xApps/branches)
2. [Create a new Feature Request](https://github.com/Cognigy/xApps/issues/new?assignees=&labels=&template=feature_request.md&title=)