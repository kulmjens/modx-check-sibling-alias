# modx-check-sibling-alias

The plugin checks on creation and update of a MODX ressource if there is a sibling (a ressource in the same container) which has the same alias. If there is it prompts a message and stays in the ressource so that the alias can be changed.

It is usefull to prevent duplicate aliases in one container.

## Requirements

- MODX Evolution 1.x (only tested with 1.0.10)

## Installation

- Create a new plugin named "CheckSiblingAlias"
- Fill in the description with `<strong>0.1</strong> Checks whether a sibling in a container has the same alias as the ressource beeing edited`
- Copy the content of the file checksiblingalias.plugin.txt in the plugin content field
- Switch to the event tab and check **OnDocFormSave**
