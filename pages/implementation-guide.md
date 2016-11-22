---
layout: page
title: "GSA Open Source Software Policy | Implementation Guide"
permalink: /guide/implementation/
description: ""
---

## Implementation Guide

If you are a GSA user that manages a source code repository, this guide will help you add your repository to the GSA source code inventory.

### What is a source code repository?

In this context, a *source code repository* is any place where source code is stored. This is often done in a version control system such as Git, Subversion, Mercurial, CVS, or Jazz SCM. The repository could be hosted on a public website or in internal agency systems.

### Does your repository need to be added to the inventory?

We need to account for all source code at GSA, regardless of whether the project is open source or closed source. You must add your repository to the GSA inventory if:

* it contains source code, and
* it has active development (i.e., creating or changing source code files) on or after August 9, 2016

Additionally, even if your source code has not had any active development since August 9, 2016, we still encourage you to include your code in the inventory.

When you submit your source code repository metadata to the inventory, the public will see the metadata. If your code is closed source, this does not change the fact that your project is closed source, and it will remain closed source. The public will only see the metadata and not the source code.

The only source code that should *not* be submitted to the inventory is code that is truly exploratory or disposable in nature, such as that written by a developer experimenting with a new language or library. If your repository only contains test code and does not serve as the foundation of a real app, tool, website, or other product, then do not include it in the GSA inventory.

### How to add your source code repository to the inventory

If you have determined that your source code repository should be included in the inventory, how you submit it depends on where it is located: [GitHub](https://github.com/) or elsewhere.

#### If your source code is on GitHub

This specifically refers to projects that are under the [GSA organization on GitHub](https://github.com/GSA/).

**Option 1 (preferred)**

Add a YAML or JSON metadata file to the root folder of your repository. This file should be named `.codeinventory.yml` or `.codeinventory.json`, and it should contain metadata about your project. [We have a tool to help you generate a YAML or JSON file](https://gsa.github.io/codeinventory-metadata-generator/). Once you add this metadata file to your repository, we can automatically scan it to include your project in the GSA source code inventory. Leave the file in your repository and keep it updated. We will regularly pull the metadata from the file to refresh the GSA inventory.

Please see the [GSA CTO Website repository](https://github.com/GSA/cto-website/blob/dev/.codeinventory.yml) for an example of how to use a `.codeinventory.yml` file.

**Option 2**

Manually submit your source code metadata via an [online form](https://goo.gl/forms/UgYwvEks2jsB59Kh2) (accessible only by GSA.gov users). You should only use this method if there is a specific reason you cannot use the automated approach in Option 1.

#### If your source code is *not* on GitHub

If your source code is in a version control system other than the GSA organization in GitHub, manually submit your source code information via an [online form](https://goo.gl/forms/UgYwvEks2jsB59Kh2) (accessible only by GSA.gov users).

*Note: GSA users are welcome to create a new open source repository under the GitHub GSA organization. [Learn how to create a GitHub account, join the GSA organization, and create a new public repository to publish your project as open source](https://github.com/GSA/GitHub-Administration/blob/master/README.md#workflows).*
