# Microsoft Adaptive Card Previewer VS Code Extension

A VS Code extension to instantly preview adaptive card built for Teams Bot, Message Extension and Copilot Plugin while editing them in VS Code.

## Key Features

### Quick preview
- Use command palette:

  Open your adaptive card file in editor, run command `Adaptive Card: Open Preview to the Side` or `Adaptive Card: Open Preview` from VS Code command palette:

  ![previewCommands](https://github.com/OfficeDev/TeamsFx/assets/10163840/d9431473-c641-4de8-a81e-f4f972dc6be0)

- Use CodeLens:

  Open your adaptive card file in editor, and click the CodeLens `Preview Adaptive Card` to open the preview:
  
  ![preview](https://github.com/OfficeDev/TeamsFx/assets/10163840/3e6bac96-3375-4922-9a77-2a649d837fd6)

### Switch theme
Users can easily preview their cards in different themes by using theme selection in the web view:

![switch-theme](https://github.com/OfficeDev/TeamsFx/assets/10163840/40e30d72-e2b3-404e-8be6-2ed51fc873e5)

### Template language 
Adaptive Card Previewer supports [template language](https://learn.microsoft.com/adaptive-cards/templating/), which enables the separation of **data** from the **layout** in an Adaptive Card. The Previewer lets you preview your templates at design time by including "sample data".

To add a data file for a template, you can use command `Adaptive Card: New Data File`. This will generate an empty file where you can bind data to your adaptive card template. Read on [Adaptive Card Templating](https://learn.microsoft.com/en-us/adaptive-cards/templating/) for more details.

### Preview card from Copilot plugin template response
Template response is used to describe the API response return by API plugin, which follow the [JSON schema](https://developer.microsoft.com/json-schemas/teams/vDevPreview/MicrosoftTeams.ResponseRenderingTemplate.schema.json). The response can be represented by an adaptive card specified in `responseCardTemplate` property, and you can use CodeLens to preview the card embedded in a template response:

![image](https://github.com/OfficeDev/TeamsFx/assets/10163840/20e9f6b3-dd6d-430c-ab56-eaea37b02613)

## Extension Settings

This extension contributes the following settings:

* `adaptiveCardPreviewer.defaultTheme`: Configure default theme for the previewer.

  ![settings](https://github.com/OfficeDev/TeamsFx/assets/10163840/70e13ca7-cab1-4a97-ade2-c7cbb9877ebe)

## Limitations
Currently certain features of Adaptive Card is not supported, these include:
- [People picker](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/people-picker)
- [Dynamic typeahead search](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/dynamic-search)
- [User mention](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#sample-adaptive-card-with-a-mention)
- [Image stage view](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#stage-view-for-images-in-adaptive-cards)
- [Full width control](https://learn.microsoft.com/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#full-width-adaptive-card)

Please stay tuned for updates as we continue to refine and expand the capabilities of our product.

## Telemetry

Adaptive Card Previewer collects usage data and sends it to Microsoft to help improve our products and services. Read our [Privacy Statement](https://privacy.microsoft.com/privacystatement) and [Data Collection Notice](https://docs.opensource.microsoft.com/content/releasing/telemetry.html) to learn more. Learn more in our [FAQ](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).
