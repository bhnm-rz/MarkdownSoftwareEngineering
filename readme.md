# Markdown Software Engineering

This folder contains standard templates for software engineering written in Markdown. The Requirements Analysis Document and Software Design Documents are stored in a KabukiPress tree structure because it speeds up Markdown rendering, it helps block out distractions, and it's more programmer-friendly.

## Document Templates

* [Requirements Analysis Document Template](./rad/readme.md)
* [Software Design Document Template](./sdd/readme.md)
* [GitHub Docs](./docs/readme.md)
  * [bug_report_template.md](./docs/bug_report_template.md)
  * [code_of_conduct.md](./docs/code_of_conduct.md)
  * [contributing.md](./docs/contributing.md)
  * [feature_request_template.md](./docs/feature_request_template.md)
  * [issue_template.md](./docs/issue_template.md)
  * [mission_and_vision.md](./docs/mission_and_vision.md)
  * [pull_request_template.md](./docs/pull_request_template.md)
  * [roadmap.md](./docs/roadmap.md)
* [Standards](./standards/readme.md)
  * [change_control_procedure.md](./standards/change_control_procedure.md)
  * [code_of_conduct.md](./standards/code_of_conduct.md)
  * [secure_coding.md](./standards/secure_coding.md)

## Organization

 There are different Markdown templates for different tasks:

* Markdown Software Engineering
* [Markdown Game Design](https://github.com/kabuki-starship/markdown.game_dev)
* [Markdown Cookbook](https://github.com/kabuki-starship/markdown.cookbook)

 Each template shares the same GitHub markdown templates using the [docs repo](https://github.com/kabuki-starship/docs).

## Mission and Vision

The mission of Markdown Software Engineering is to help you start out or get your project onto the right foot and increase productivity with Don't Repeat Yourself (DRY) documentation. Our vision is to automate as much documentation as possible with [KabukiPress](https://github.com/kabuki-starship/kabukipress).

## MVP RoadMap

***When you're first starting out your project, your roadmap should be here in the root `readme.md` file because people have very low tolerance for non-working code, they will just move on in search of the easy thing and you can't blame them, so if you're trying to woo contributors, you must do it with your Mission and vision, then immediately after show the action plan that someone else things is a good idea achievable, and worth their time to contribute too.***

We can achieve a Minimum Viable Product by completing the following project phases:

1. Foo - In this phase we will say hello world.
1. Bar - In this phase we will say Foo and Bar.

This is a good idea because foo and bar are both common names for abstract functions.

## Quickstart Guide

**1.** Clone the repo recursively or else you don't get the `/docs` folder.

```BASH
git clone --recursive https://github.com/kabuki-starship/markdown.software_engineering.git
```

**2.** Copy the documents you want into your repo, but do not copy the .git folder because it will mess up the GitHub templates.

**3.** We've found [Visual Studio Code](code.visualstudio.com) to the best Markdown editor. Open Visual Studio Code, right click on the Explorer, and click on Add Folder to Workspace, then point it to your project repo's root folder.

**4.** Find and replace all instances of "Markdown Software Engineering" with your projects name, and find and replace all instances of "Your Name <<https://your-github-page.github.io>>" with your name and a pointer to your GitHub page. Please don't put your personal email on the copyright, you want to make them contact you through a website so you can keep your personal information private.

**5.** Delete the lines in the License you don't need.

**6.** To upload the files to the web, just upload them to your GitHub repo.

**7.** If you would like to create a statically generated website from the Markdown files, check out [KabukiPress](https://github.com/kabuki-starship/kabukipress). We are seeking Modern Embedded-C++ code contributors.

## License

***This template is not copyrighted. We're assuming you're making a commercial application so this is just an example strong closed-source license. If you are trying to create a source available license, which is the strongest open-source license, replace the license paragraph with "You must consult your personal license for permissions and restrictions."***

Copyright 2019 (C) Your Name <<https://your-github-page.github.io>>, the IP Owner; all rights reserved (R).

This file and the folder and repository it is contained in are private and contain intellectual property, trade secrets, copyrighted material, and other protected works, the IP, that are the property of the IP Owner. You must get explicit permission from the IP Owner to possess, view, modify, share, duplicate, discuss, or publicly display the IP.
