modx-check-sibling-alias
========================

The plugin checks on creation and update of a MODX ressource if there is a sibling (a ressource in the same container) which has the same alias. If there is it prompts a message and stays in the ressource so that the alias can be changed.

It is usefull to prevent duplicate aliases in one container.

Requirements
------------

Requires MODX Evolution 1.x
(only tested with 1.0.10)

Installation
------------

Create a new plugin. Fill in the following fields:

name: CheckSiblingAlias<br>
description: <strong>0.1</strong> Checks whether a sibling in a container has the same alias as the ressource beeing edited<br>
Copy the content of the file checksiblingalias.plugibn.txt in the plugin content field.<br>
Switch to event-tab and check "OnDocFormSave".
