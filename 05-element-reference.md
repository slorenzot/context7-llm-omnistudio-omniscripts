# Omniscript Element Reference

> Source: <https://help.salesforce.com/s/articleView?id=xcloud.os_omniscript_element_reference_10533.htm&type=5>
> Salesforce Help — Omnistudio Documentation

The available elements are Omniscripts are organized as groups, Data Mapper actions, standard actions, display elements, functions, input, and Omniscripts (to embed reusable Omniscripts). Each element uses an extendable Lightning web component (LWC).
When you drag an element to the canvas in an Omniscript, it shows the field label in the designer. In the designer for a managed package, it shows the element name.
Common Omniscript Element Properties
Each Omniscript element has settings, some of which are unique to that element. Some settings are common among the elements, though some of these setting aren’t available in all elements. To edit these settings, use the Properties pane on the Designer.
Activate Elements in the Omniscript Designer
Activate an inactive element by selecting the element in the Navigation Panel of the Omniscript Designer.
Omniscript Group Elements
From the group category, you can organize Omniscript elements. Use step elements to divide the Omniscript into sections. Use edit blocks to group input elements for users to add, edit, or delete records. Create a questionnaire with the radio group element. Use the type ahead block to display a list of results when a user begins typing in an input field.
Omniscript Data Mapper Action Elements
Use Data Mapper actions to retrieve, write, or restructure data from one or more related Salesforce objects.
Omniscript Action Elements
Use action elements in an Omniscript for executing actions, such as get or update data from one or more Salesforce objects, call a series of actions, send emails or documents for signature, redirect to different pages. Action elements can be either rendered as a button when placed in a Step or Block or run remotely if placed between steps. In either case, you can specify a redirect page, where the user can proceed to the next step or action, or if a button, back to the source step.
Omniscript Display Elements
Use the Omniscript Display elements to display rich text and images on the screen to enhance the user interface. The display elements include Line Break and Text Block.
Omniscript Function Elements
From the Omniscript function elements, use the formula element to preform calculations that require complex calculations. For array input, use the aggregate element for complex calculations. The Messaging element displays comments, requirements, success, and warning messaging depending on whether the validate expression is true or false.
Omniscript Input Elements
When users to change, add, or delete data, add an Omniscript element for a specific type of data, such as email addresses, files, dates, passwords. You can also show information and allow users to select from a list of options, such as radio, checkboxes, multi-select, select, and disclosure elements.
