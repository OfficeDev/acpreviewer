# Microsoft Adaptive Card Previewer for Visual Studio Code

The Microsoft Adaptive Card Previewer uses the latest rendering stack for Microsoft Teams to provide a more accurate preview of Adaptive Cards. You can open a side-by-side preview to view changes live, toggle between light, dark, and high contrast themes.

![image](https://github.com/OfficeDev/acpreviewer/assets/1501196/e9ff722c-6ea3-4883-81d2-85329bb98ad3)

## Features

### Quick preview

**Using the command palette:** Open your Adaptive Card JSON file in the editor and run the command `Adaptive Card: Open Preview to the Side` or `Adaptive Card: Open Preview` from the VS Code command palette:

![previewCommands](https://github.com/OfficeDev/TeamsFx/assets/10163840/d9431473-c641-4de8-a81e-f4f972dc6be0)

**Using CodeLens hints:** Open your Adaptive Card JSON file in editor and select the CodeLens hint `Preview Adaptive Card` to open the preview:
  
![preview](https://github.com/OfficeDev/TeamsFx/assets/10163840/3e6bac96-3375-4922-9a77-2a649d837fd6)

You can also quickly preview an Adaptive Card used as a response to a Copilot plugin response, defined in the app manifest's `responseCardTemplate` property.

![image](https://github.com/OfficeDev/TeamsFx/assets/10163840/20e9f6b3-dd6d-430c-ab56-eaea37b02613)

### Switch themes

You can preview your cards with different themes by using the theme selection drop-down menu in the preview window:

![switch-theme](https://github.com/OfficeDev/TeamsFx/assets/10163840/40e30d72-e2b3-404e-8be6-2ed51fc873e5)

### Adaptive Card Templating

Adaptive Card Previewer supports templating using the [Template Language](https://learn.microsoft.com/adaptive-cards/templating/), which enables the separation of **data** from the **layout** in an Adaptive Card.

To add a data file for a template, you can use the command `Adaptive Card: New Data File`. This will generate an empty file where you can bind data to your Adaptive Card template. Visit [Adaptive Card Templating](https://learn.microsoft.com/en-us/adaptive-cards/templating/) for more details.

## Extension Settings

Use these settings to customize the behavior of the extension.

* `adaptiveCardPreviewer.defaultTheme`: Configure default theme for the previewer.

  ![settings](https://github.com/OfficeDev/TeamsFx/assets/10163840/70e13ca7-cab1-4a97-ade2-c7cbb9877ebe)

## Limitations
Some features of an Adaptive Card are not supported::
- [People picker](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/people-picker)
- [Dynamic typeahead search](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/dynamic-search)
- [User mention](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#sample-adaptive-card-with-a-mention)
- [Image stage view](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#stage-view-for-images-in-adaptive-cards)
- [Full width control](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#full-width-adaptive-card)

## Telemetry

Adaptive Card Previewer collects usage data and sends it to Microsoft to help improve our products and services. Read our [Privacy Statement](https://privacy.microsoft.com/privacystatement) and [Data Collection Notice](https://docs.opensource.microsoft.com/content/releasing/telemetry.html) to learn more. Learn more in our [FAQ](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).
