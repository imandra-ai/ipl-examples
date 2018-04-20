![Aesthetic Integration](https://storage.googleapis.com/imandra-assets/images/github/ipl_lang_examples_head.svg)
---
Welcome to Imandra Protocol Language examples repo.

- [ordersOnly.ipl](ordersOnly.ipl) - Minimal model that accepts/rejects `NewOrderSingle`
- [ordersWithFills.ipl](ordersWithFills.ipl) - Model accepting/rejecting `NewOrderSingle` messages and generating fills
- [repeatingGroupsSimple.ipl](repeatingGroupsSimple.ipl) - Example of repeating groups usage
- [repeatingGroupsComplex.ipl](repeatingGroupsComplex.ipl) - Implicit foralls in validate statements for repeating groups
- [importedOptionaField.ipl](importedOptionaField.ipl) - Example optional treatment of imported optional value
- [ordersOnlyCustomMessage.ipl](ordersOnlyCustomMessage.ipl) - Example message extension with enum extension
- [ambiguousOptionalitySimple.ipl](ambiguousOptionalitySimple.ipl) - Example with minimal example optional and ambiguous import logic 
- [ambiguousOptionalityComplex.ipl](ambiguousOptionalityComplex.ipl) - Complex treatment of ambiguous type fields
- [sentFieldsRecordComplete.ipl](sentFieldsRecordComplete.ipl) - Setting sent fields using an internal record (successfully)
- [sentFieldsRecordIncomplete.ipl](sentFieldsRecordIncomplete.ipl) - Setting sent fields using an internal record requiring addition explicit "with" statements
- [sentFieldsRecordAssignable.ipl](sentFieldsRecordAssignable.ipl) - Setting sent fields using assignable records.
- [ordersOnlyExplicitFrom42.ipl](ordersOnlyExplicitFrom42.ipl) - FIX 4.4 Example of importing a message explicitly from 4.2
- [ordersOnlyExplicitFrom44.ipl](ordersOnlyExplicitFrom44.ipl) - FIX 4.2 Example of importing a message explicitly from 4.4
- [ordersWithFillsOverride.ipl](ordersWithFillsOverride.ipl) - Example with a field from the library with an overridden type
- [stopSpreadOrder.ipl](stopSpreadOrder.ipl) - FIX 4.4 Example of a new order type from the tutorial [here](https://docs.imandra.ai/ipl/tutorials/)
