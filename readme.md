# Markdown Software Engineering

This folder contains standards and templates for software engineering written in Markdown. The Requirements Analysis Document and Software Design Documents are stored in a tree structure because many MarkDown renderers will chunk on you when you edit large documents, it helps block out distractions, and it's more programmer-friendly.

## Documents

* [Requirements Analysis Document Template](./rad/readme.md)
* [Software Design Document Template](./sdd/readme.md)
* [GitHub Templates](./docs/readme.md)
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

## Mission and Vision

The mission of Markdown Software Engineering is to help you start out or get your project onto the right foot and increase productivity. Our vision is to automate as much documentation as possible with [KabukiPress](https://github.com/kabuki-starship/kabukipress).

## Quickstart Guide

**1.** Clone the repo recursively or else you don't get the `/docs` folder.

```BASH
git clone --recursive https://github.com/kabuki-starship/markdown.software_engineering.git
```

**2.** Copy the documents you want into your repo.

**3.** We've found [Visual Studio Code](code.visualstudio.com) to the best Markdown editor. Open Visual Studio Code, right click on the Explorer, and click on Add Folder to Workspace, then point it to your project repo's root folder.

**4.** Find and replace all instances of "Markdown Software Engineering" with your projects name, and find and replace all instances of "Your Name <<https://your-github-page.github.io>>" with your name and a pointer to your GitHub page. Please don't put your personal email on the copyright, you want to make them contact you through a website so you can keep your personal information private.

**5.** Delete the lines in the License you don't need.

**6.** To upload the files to the web, just upload them to your GitHub repo.

**7.** This step isn't working yet but we're seeking contributors. If you would like to create a statically generated website from the Markdown files, check out [KabukiPress](https://github.com/kabuki-starship/kabukipress).

## License

***This template is not copyrighted, this is just an example license.***

Copyright 2019 (C) Your Name <<https://your-github-page.github.io>>, the IP Owner; all rights reserved (R).

This file and the folder and repository it is contained in are private and contain intellectual property, trade secrets, copyrighted material, and other protected works, the IP, that are the property of the IP Owner. You must get explicit permission from the IP Owner to possess, view, modify, share, duplicate, discuss, or publicly display the IP.

***If you are trying to create a source available license, which is the strongest open-source license, all you need is the Copyright line with the Copyright holder and you can delete the prior paragraph.***
