# Function-Library
A collection of function libraries to include in scripts.

## Keyboard Modifiers
Helps with retrieving the state of keyboard modifiers.

Works best if called early in a script before the user may have released the modifiers. To help with this these functions make use of a global variable *$G_LAST_KEYBOARD_MODIFIER_STATE* to cache the modifiers so subsequent calls operate on the starting states.

In addition to providing shortcuts to determine which keys are down there are also functions to convert the state to a string in various formats.
