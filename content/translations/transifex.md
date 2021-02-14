---
title: ControlsFX Transifex
---
# ControlsFX Transifex

ControlsFX uses [Transifex](https://www.transifex.com), which provides a web application allowing translators to write, submit, and manage their translations.

ControlsFX is very fortunate to have a team of people who support it by translating the English strings into localized strings.
We are always on the lookout for more people to translate ControlsFX into additional languages.
If you are able to help, and especially if the language is not already being translated, or is not completed for the next release, then read on! And, thanks so much in advance for helping out!

## Getting Started

The amount of work to translate ControlsFX is minimal. You can gauge this for yourself by having a look at the [existing translation files in our repository](https://github.com/controlsfx/controlsfx/blob/master/controlsfx/src/main/resources/controlsfx.properties).

## Transifex

Go to https://www.transifex.com/signup/contributor/ and fill out the form to create your free Transifex account, if you don’t already have one.

### Join a Translation Team

1. Once you’ve set up your account, visit https://www.transifex.com/controlsfx/controlsfx/ to become a translator for your language.
2. When you visit the project page, it looks like this. If your language is listed, click on the name of the language to go to the language’s page. Here is an example of choosing the Lithuanian translation project:

![Transifex 1.png](/images/i18n/transifex-1.png)

3. Once you’re on the language’s page, click “Join team” to become part of the translation team for that language:

![Transifex 2.png](/images/i18n/transifex-2.png)

Once you’ve joined a translation team, you can begin translating strings immediately! 

### Translate With Transifex

When you are on a language page you will see the available resource to translate.

![Transifex 3.png](/images/i18n/transifex-3.png)

Click on it and select "Translate now". 

![Transifex 4.png](/images/i18n/transifex-4.png)

This will open the Transifex web editor in which you can edit the translations. For more help regarding the web editor visit [Introduction to the Web Editor](http://support.transifex.com/customer/portal/articles/972120-introduction-to-the-web-editor).

## Requesting A New Language

If your language is not listed, click the “Request language” button on the main project page to start a new translation project for your language:

Keep in mind that variants of your language may exist (“Portuguese” versus “Portuguese (Brazil)”), and these variants may meet your needs.

A ControlsFX translation team member will respond to your request. If your language is approved, you will become the Language Coordinator for this particular language. As a Language Coordinator you will be responsible for the translation of the project. You can add additional coordinators, reviewers, and translators as you wish.
You should also ensure that the translations are **completely translated and reviewed** as only such translations will be a part of the ControlsFX release.

## Downloading translations when building locally

ControlsFX build script automatically tries to download the translations when building locally. You just have to set **transifex.username** and **transifex.password** properties in your **gradle.properties** file.
If these properties are not set then the build will still continue with a warning, and you'll just be missing all but the English file.