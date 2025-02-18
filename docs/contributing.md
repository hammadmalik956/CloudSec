We're thrilled that you'd like to contribute to this project! This is a community-driven effort, so every contribution counts. It doesn't even have to be anything major, it could be as simple as fixing a typo you came across. We welcome any and all contributions, as long as they follow basic and simple rules. Please read this page before making your first contribution.

## What can I contribute?

Anything and everything related to cloud security or related topics. Got a tip for how to secure Azure Functions? Awesome! Got an open source project you use to help you write more secure Infrastructure as Code and want to share? Go for it. As long as it's related to cloud security and it's free to use, open a PR and we'll take a look!

## How to contribute

Contriburing is simple:

1. [ :octicons-link-external-16: Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) to create your own version of [ :octicons-link-external-16: this repository](https://github.com/Cybr-Inc/CloudSec)
2. Add your changes to your own local version
3. [ :octicons-link-external-16: Create a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) back into [ :octicons-link-external-16: this repository](https://github.com/Cybr-Inc/CloudSec)
4. Maintainers will review the pull request and approve or request changes

This project uses MkDocs Material theme and has multiple extensions/plugins installed. Refer to their documentation on [ :octicons-link-external-16: plugins](https://squidfunk.github.io/mkdocs-material/plugins/) and [ :octicons-link-external-16: reference](https://squidfunk.github.io/mkdocs-material/reference/) to learn how to use it, and refer to our [ :octicons-link-external-16: config file](https://github.com/Cybr-Inc/CloudSec/blob/main/mkdocs.yml) to see what's available. 

## How to display links

If your contribution includes links, please follow these guidelines:

- For internal links, meaning links that go to another page on this website/domain, you can simply link by using brackets `[]` immediately followed by paranthesis `()` wrapping the URL, like this (but without spaces): `[example]( /aws/iam/about-iam )`. Note that you don't need to put in the entire URL either. The end result: [example](/aws/iam/about-iam)
- For external links, meaning any link that points to a different domain than this one, you must add an external link icon (with `:octicons-link-external-16:`) to indicate that it will take the user to a different website _before_ the text, like this: `[:octicons-link-external-16: example](https://cybr.com)`. The end result: [:octicons-link-external-16: example](https://cybr.com)

As you can see, this cleanly and easily helps differentiate between internal and external links.

### Links must not require registration or payment

If you want to add a link to a resource that requires registration or payment, you must become a sponsor.

### Open source tools only please

If you want to add or reference a tool in your contribution, it must be an open source tool that's available and accessible for free and without requiring registation.

If you want to link to a tool or resource that requires registration and/or a payment you can [ :octicons-link-external-16: contact us](https://cybr.com/contact) to become a sponsor.

## Why so strict about open source and free content?

We are doing it this way because we don't want every other link to turn into a paywall. Plus, sponsorships will help fund cool perks for this project.

## Commonly used icons:

- For links - :octicons-link-external-16: `:octicons-link-external-16:` 
- For button-like links - :octicons-arrow-right-24: `:octicons-arrow-right-24:` (refer to the home page to see what we mean)

## Commonly used for code:

- For code blocks, use three backticks (```) to start and end a code block. You want the backticks on their own lines so you can end up with this:
```
#!/bin/bash

echo "What's your name?"

read name

echo "Hello, $name! Nice to meet you."

```

- For inline code, `like this`, you can use a single backtick (`) to start and a single backtick to end
- For providing examples, notes, warnings, etc...use admonitions like this:
!!! example "Example of an admonition"

    This is an example admonition where you can provide examples of outputs or commands

These blocks start with three exclamation marks (!!!) [ :octicons-link-external-16: View the documentation on how it works here.](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)

- You can also make them collapsible by using three question marks instead (???)

??? note "Some useful but not critical info"

    If you have something extra to share that adds value but isn't the primary point

- Tips are also pretty cool:

??? tip "Tip about access keys"

    Long-term access keys always start with `AKIA...` while temporary credentials start with `ASIA...`

- Or warnings:

??? warning "This permission can lead to PrivEsc"

    The `iam:SetDefaultPolicyVersion` can lead to nasty privilege escalation attacks. Only give that permissions to admins.

- Or for an extreme warning:

??? danger "Do NOT do this!"

    Do NOT share this secret access key with anyone! Not even your bestie!

- You can [ :octicons-link-external-16: add annotations](https://squidfunk.github.io/mkdocs-material/reference/annotations/) to general text and [ :octicons-link-external-16: also to code](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/#adding-annotations). This is a great way to add commentary or extra information without mucking up the code or whatever else