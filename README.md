![Imandra Inc.](https://storage.googleapis.com/imandra-assets/images/github/ipl_lang_examples_head-3.svg)

---
### Welcome to Imandra Protocol Language examples repo.

For further documentation, please see: [https://docs.imandra.ai](https://docs.imandra.ai).

Download the IPL VS Code Plug-in for these models at the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=aestheticintegration.ipl-vscode).


- [ordersOnly.ipl](ordersOnly.ipl) - Minimal model that accepts/rejects `NewOrderSingle`
- [ordersWithFills.ipl](ordersWithFills.ipl) - Model accepting/rejecting `NewOrderSingle` messages and generating fills
- [ordersWithFillsSet.ipl](ordersWithFillsSet.ipl) - as [ordersWithFills.ipl](ordersWithFills.ipl) but with some set reasoning
- [repeatingGroupsSimple.ipl](repeatingGroupsSimple.ipl) - Example of repeating groups usage
- [repeatingGroupsComplex.ipl](repeatingGroupsComplex.ipl) - Implicit foralls in validate statements for repeating groups
- [importedOptionaField.ipl](importedOptionaField.ipl) - Example optional treatment of imported optional value
- [ordersOnlyCustomMessage.ipl](ordersOnlyCustomMessage.ipl) - Example message extension with enum extension
- [ambiguousOptionalitySimple.ipl](ambiguousOptionalitySimple.ipl) - Example with minimal example optional and ambiguous import logic 
- [ambiguousOptionalityComplex.ipl](ambiguousOptionalityComplex.ipl) - Complex treatment of ambiguous type fields
- [sentFieldsRecordComplete.ipl](sentFieldsRecordComplete.ipl) - Setting sent fields using an internal record (successfully)
- [sentFieldsRecordIncomplete.ipl](sentFieldsRecordIncomplete.ipl) - Setting sent fields using an internal record requiring addition explicit "with" statements
- [sentFieldsRecordAssignable.ipl](sentFieldsRecordAssignable.ipl) - Setting sent fields using assignable records
- [ordersOnlyExplicitFrom42.ipl](ordersOnlyExplicitFrom42.ipl) - FIX 4.4 example of importing a message explicitly from 4.2
- [ordersOnlyExplicitFrom44.ipl](ordersOnlyExplicitFrom44.ipl) - FIX 4.2 example of importing a message explicitly from 4.4
- [ordersWithFillsOverride.ipl](ordersWithFillsOverride.ipl) - Example with a field from the library with an overridden type
- [tutorialActions.ipl](tutorialActions.ipl) - Example of introducing actions from the tutorial [here](https://docs.imandra.ai/ipl/tutorialActions/)
- [tutorialAdvanced.ipl](tutorialAdvanced.ipl) - Full example from the tutorial [here](https://docs.imandra.ai/ipl/tutorialAdvanced)
- [tutorialBasic.ipl](tutorialBasic.ipl) - Example from the tutorial [here](https://docs.imandra.ai/ipl/tutorialBasic/)
- [tutorialCustom.ipl](tutorialCustom.ipl) - Example of introducing custom extenions from the tutorial [here](https://docs.imandra.ai/ipl/tutorialCustom)
- [tutorialRepeating.ipl](tutorialRepeating.ipl) - Example of repeating groups from the tutorial [here](https://docs.imandra.ai/ipl/tutorialRepeatingGroups)
- [tutorialSideEffects.ipl](tutorialSideEffects.ipl) - Example of multiple imports from the tutorial [here](https://docs.imandra.ai/ipl/tutorialSideEffects)
- [tutorialState.ipl](tutorialState.ipl) - Example of introducing state from the tutorial [here](https://docs.imandra.ai/ipl/tutorialState)
- [wolfCabbageGoat.ipl](wolfCabbageGoat.ipl) - Example shown [here](https://medium.com/imandra/the-wolf-goat-and-cabbage-exchange-97e7f3ff8d5a)
