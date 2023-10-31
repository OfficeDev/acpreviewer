# Microsoft Adaptive Card Previewer 

The Microsoft Adaptive Card Previewer is an extension for Visual Studio Code. It uses the latest rendering stack for Microsoft Teams to provide a more accurate preview of Adaptive Cards. You can open a side-by-side preview to view changes live, toggle between light, dark, and high-contrast themes.

![ACP](https://github.com/OfficeDev/TeamsFx/assets/11220663/359ae4f3-568b-4476-89e3-b8fa58fc93e7)

## Features

Adaptive Card Previewer supports:

- Instant preview of adaptive cards in VS Code editor through CodeLens or Command Palette.
  ![previewCommands](https://github.com/OfficeDev/TeamsFx/assets/10163840/d9431473-c641-4de8-a81e-f4f972dc6be0)

  ![preview](https://github.com/OfficeDev/TeamsFx/assets/10163840/3e6bac96-3375-4922-9a77-2a649d837fd6)

- Switch between different themes (Light/Dark/High-Contrast) to preview your cards so you can design with confidence.
  ![Theme](https://github.com/OfficeDev/acpreviewer/assets/11220663/371cad96-bc13-4a33-9c42-f276221ea4d5)


- Separation of **data** from the **layout** in an Adaptive Card [template language](https://learn.microsoft.com/adaptive-cards/templating/). Use the command `Adaptive Card: New Data File` to add a data file for a template. This will generate an empty file where you can bind data to your adaptive card template.

- Seamless integration with Teams Toolkit that allows a Just-In-Time installation of Adaptive Card Previewer when you are iterating on adaptive cards generated from Teams Toolkit project creation.
  ![image](https://github.com/OfficeDev/TeamsFx/assets/10163840/20e9f6b3-dd6d-430c-ab56-eaea37b02613)

- Configure default theme through Visual Studio Code extension settings `adaptiveCardPreviewer.defaultTheme`.
  ![settings](https://github.com/OfficeDev/TeamsFx/assets/10163840/70e13ca7-cab1-4a97-ade2-c7cbb9877ebe)

## Limitations

Some features of an Adaptive Card are not supported:

- [People picker](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/people-picker)
- [Dynamic type-ahead search](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/dynamic-search)
- [User mention](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#sample-adaptive-card-with-a-mention)
- [Image stage view](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#stage-view-for-images-in-adaptive-cards)
- [Full-width control](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#full-width-adaptive-card)

Please stay tuned for updates as we continue to expand the capabilities of Adaptive Card Previewer.

## Feedback

- [Request a new feature](https://github.com/OfficeDev/acpreviewer/issues/new?assignees=&labels=&projects=&template=feature_request.md&title=)
- [File an issue](https://github.com/OfficeDev/acpreviewer/issues/new?assignees=&labels=&projects=&template=bug_report.md&title=)
- Send an email to ttkfeedback@microsoft.com to chat with the product team
- Report security issues and bugs to the Microsoft Security Response Center (MSRC) via secure@microsoft.com. Further information can be found in the [Security TechCenter](https://www.microsoft.com/msrc/faqs-report-an-issue?rtc=1).

## Support Policy

Adaptive Card Previewer will follow [Modern Lifecycle Policy](https://docs.microsoft.com/lifecycle/policies/modern).

## Telemetry

Adaptive Card Previewer collects usage data and sends it to Microsoft to help improve our products and services. Read our [Privacy Statement](https://privacy.microsoft.com/privacystatement) and [Data Collection Notice](https://docs.opensource.microsoft.com/content/releasing/telemetry.html) to learn more. Learn more in our [FAQ](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.
