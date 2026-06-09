# Omniscript Group Elements

> Source: <https://help.salesforce.com/s/articleView?id=xcloud.os_omniscript_group_elements_13946.htm&type=5>
> Salesforce Help — Omnistudio Documentation

From the group category, you can organize Omniscript elements. Use step elements to divide the Omniscript into sections. Use edit blocks to group input elements for users to add, edit, or delete records. Create a questionnaire with the radio group element. Use the type ahead block to display a list of results when a user begins typing in an input field.
Run Multiple Actions in an Action Block
Run multiple Omniscript Actions asynchronously by grouping them in an Action Block. Actions within the Action Block run in parallel and inherit the Action Block's settings.
Combine Elements Logically in a Block
Combine logical groups of elements in an Omniscript Step using a Block element. Blocks help to group information to create nested JSON data. Blocks are contained within steps and can be repeated to capture an array of data. For example, street, city, state, and postal code elements can be combined into an address block.
Manage Records with an Edit Block
Create, edit, and delete multiple Salesforce or external records on one page using Edit Block. For example, if you're collecting an Account's Contact information, you can add an Edit Block to your Omniscript to enable users to add a record for each Contact.
When to Use Omniscript Edit Blocks and Blocks
To decide when to use edit blocks and blocks, check if you need to limit repeating the block, directly modify sObjects, show fields when the block is collapsed, display the block in different layouts, or use the custom LWC element.
Create an Omniscript Questionnaire with a Radio Group
With an Omniscript's radio group, create and display questions in a questionnaire format.
Add Steps to an Omniscript
Each Step element in an Omniscript presents a page to the user that prompts for input or displays information. For navigation, all Steps except the first have a Next button, and all except the last have a Previous button.
Add a Type Ahead Block in an Omniscript
In edit blocks, suggest possible entries as a user types in a field, as an autosuggest or autocomplete.
