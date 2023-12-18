---
_layout: landing
---

<style>
.jumbotron {
    text-align: center;
}

.jumbotron .screenshot {
    margin: 1.5em;
}

.jumbotron h1.title {
    font-weight: bold;
    font-size: 3em;
    margin: 0.4em;
}

.jumbotron h2.subtitle {
    font-weight: normal;
    font-size: 1.4em;
    margin: 1em;
}

.jumbotron .download {
    margin: 2.5em 0 0.5em 0;
}

.jumbotron .download a {
    color: white;
    background-color: #4CAF50;
    border: solid 0.5px #224e24;
    border-radius: 0.3em;
    padding: 0.6em 0.8em;
    text-decoration: none;
    font-size: 1.2em;
}

.jumbotron .download a svg {
    width: 1.1em;
    height: 1.1em;
    margin-bottom: 0.2em;
}
</style>

<div class="container">
    <div class="jumbotron">
        <h1 class="title">Techie's Quick Launcher</h1>
        <h2 class="subtitle">Techie's Quick Launcher, a quick launcher for IT professionals</h2>
        <div class="download">
            <a href="https://github.com/TQLApp/TQL/releases/latest">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="white">
                    <!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2023 Fonticons, Inc.-->
                    <path d="M288 32c0-17.7-14.3-32-32-32s-32 14.3-32 32V274.7l-73.4-73.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l128 128c12.5 12.5 32.8 12.5 45.3 0l128-128c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L288 274.7V32zM64 352c-35.3 0-64 28.7-64 64v32c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V416c0-35.3-28.7-64-64-64H346.5l-45.3 45.3c-25 25-65.5 25-90.5 0L165.5 352H64zm368 56a24 24 0 1 1 0 48 24 24 0 1 1 0-48z"/>
                </svg>
                Download from GitHub
                </a>
            </div>
        <img class="screenshot" src="Images/MainWindow1x.png" srcset="Images/MainWindow2x.png 2x" />
    </div>
</div>

Techie's Quick Launcher (TQL) is a launcher app for modern software development
tools. It's useful for anybody doing software development, from developers to
testers and product owners.

The primary use of the app is to quickly navigate to things you need every day,
like Agile boards in JIRA or Azure DevOps, work items and issues, Azure Portal
resources, and even people if you want to quickly start a teams chat.

## Beta

The project is currently in beta and I'm working on putting on the finishing
touches to be able to do a release. See
[1.0 milestone](https://github.com/TQLApp/TQL/milestone/1) for the progress
towards the first release.

## Features

- Support for Azure, Azure DevOps, JIRA, Confluence, GitHub, Outlook and
  Microsoft Teams.
- Built in plugin system to be able to add your own plugins.
- Quick start tutorial to get you up and running quickly.
- Advanced search capabilities. You'll forget how to use the web apps once you
  get used to TQL 😀.

## Installation

You need to download and install the setup to run Techie's Quick Launcher. Go to
the [latest release](https://github.com/TQLApp/TQL/releases/latest) page and
under **Assets**, download the **MSI** file. Have a look at the
[Getting started](https://github.com/TQLApp/TQL/wiki/Getting-started) page to
see how you can get yourself up and running.

## Getting started

When you first run the app, the quick start tutorial will guide you through the
setup of TQL. Just follow the steps to start using Techie's Quick Launcher.

<center>
    <img class="screenshot" src="Images/QuickStart1x.png" srcset="Images/QuickStart2x.png 2x" />
</center>

There's more in depth documentation available at
[the wiki](https://github.com/TQLApp/TQL/wiki).

## Contribution guide

There are two ways in which you can contribute. If you have an idea for a plugin
for TQL, you can write your own. Have a look at the
[Create a plugin](https://tqlapp.github.io/TQL/Documentation/Create-a-plugin.html)
documentation on the developers website on how to do this. You don't have to
create a PR for this! You can publish your own plugin from your own repository
and have it work with TQL.

If you want to contribute to TQL directly, we welcome PRs. See the
[Development environment](https://tqlapp.github.io/TQL/Documentation/Development-environment.html)
wiki page for information on how to setup a local development environment for
TQL.

You can have a look at the issue log and find an issue you'd like to pick up. If
you have an idea for a feature request, best is to create a
[feature request issue](https://github.com/TQLApp/TQL/issues/new?assignees=&labels=&projects=&template=feature_request.md&title=)
for this and mention that you'd like to contribute it yourself. We'll use the
comments on the issue to discuss whether the feature is a good fit for the tool.

We also welcome localization of TQL. See the
[Localize TQL](https://tqlapp.github.io/TQL/Documentation/Localize-TQL.html)
wiki page for instructions on how to do this. I maintain English and Dutch
myself, and I welcome contributions for any other language.

## License

[MIT License](https://github.com/TQLApp/TQL/blob/main/LICENSE).

## Contributions

I've used assets from other projects in this app. Thank you for making this
available!

- The logo and some other icons for the application came from
  https://www.flaticon.com/packs/universe-16.
- The theme came from https://github.com/AngryCarrot789/WPFDarkTheme.
- Some icons came from https://github.com/microsoft/fluentui-system-icons
  (search engine is at https://fluenticons.co/).
- The original grab cursor came from
  https://www.svgrepo.com/svg/372329/cursor-hand-grab. The one I'm using is
  modified to better support high DPI.
