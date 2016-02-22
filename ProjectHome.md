This project aims on releasing a javascript formvalidator for quick and easy clientside formvalidation using regexes, but will have support for plugins for custom validations

It was originally developed as part of the (non-released) P.O.R.K. framework but works with any site.

The validation method is triggered by an onsubmit of your form which loops all elements that have a validation="" property in their tag, and displays the message shown in the message="" property.

Currently validates: inputs, textareas, checkboxes and radios.