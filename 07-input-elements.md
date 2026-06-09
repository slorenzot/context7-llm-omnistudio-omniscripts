# Omniscript Input Elements

> Source: <https://help.salesforce.com/s/articleView?id=xcloud.os_omniscript_input_elements_16001.htm&type=5>
> Salesforce Help — Omnistudio Documentation

When users to change, add, or delete data, add an Omniscript element for a specific type of data, such as email addresses, files, dates, passwords. You can also show information and allow users to select from a list of options, such as radio, checkboxes, multi-select, select, and disclosure elements.
To add any of these elements, drag the element to the canvas.
In the properties for an input element, set the name, label (that users see), and other properties.
Omniscripts Checkbox Element
Enable users to select a checkbox by adding the Checkbox element to your Omniscript. For example, map the user's yes or no answer to a true or false field in a record. Checkbox is a boolean input control and returns true or false to the Data JSON.
Omniscripts Currency Element
Enable users to enter a currency amount by adding the Currency element to your Omniscript. Update default format options such as the number of decimal places to display, minimum and maximum currency value, and more.
Custom LWC Element
Add a custom Lightning web component that does not extend an Omniscript element component to an Omniscript using the Custom LWC element.
Omniscripts Date Element
Enable users to select a date from a date picker by adding a Date element to your Omniscript. Set the minimum and maximum dates and the date format.
Omniscripts Time Element
Enable users to select from a list of times by adding the Time element to your Omniscript. Format the display and set the time intervals.
Set Date and Time Ranges
The Date, Date/Time, and Time elements enable users to input dates and times into an Omniscript form. Each element has different properties that enable you to present a selectable range of dates or times to the User.
Omniscripts Date/Time Element
Enable users to select a date from a date picker and a time from a list by adding the Date/Time element to your Omniscript. Set the minimum and maximum dates, and the date and time formats.
Omniscripts Disclosure Element
To allow users to agree to a disclosure statement, add a Disclosure element to your Omniscript. Enter the copy in a rich text editor.
Enter an Email Address in Omniscripts
Enable users to enter an email address by adding the Email element to your Omniscript. Update the default allowable format with Validation Options.
Query Salesforce Data from an Omniscipt with the Lookup Element
Run a query using text input to retrieve Salesforce data using the Lookup element. The retrieved data is returned in value-label pairs and becomes available for selection in a dropdown list.
Omniscripts Number Element
Enable users to enter a number by adding the Number element to your Omniscript. Limit what the user can enter by setting a mask.
Omniscripts Password Element
Enable users to enter a password by adding the Password element to your Omniscript. Set the minimum and maximum lengths of the password.
Omniscripts Multi-Select Element
Enable users to select from multiple items by adding the Multi-select element to your Omniscript. Display options vertically, horizontally, or as an image. Read-only Multi-Select images show in grayscale, but you can use a custom CSS to them in color.
Omniscripts Select Element
Enable users to select from a dropdown by adding a Select element to your Omniscript. Users can enter text to filter the options. Omnistudio pulls the options from an Apex class and method or from a Salesforce object.
Omniscripts Radio Element
Enable users to select one from multiple items by adding the Radio element to your Omniscript. Display options vertically, horizontally, or as an image.
Add Options for Selects, Multi-Selects, and Radio Buttons
To add options for Select, Multi-Select, and Radio Button elements, go to the Options section of the element properties and click + Add New Option. If no values are defined for a Select element, an Undefined Value is returned.
Omniscripts Range Element
Enables users to select a number from a specified range by adding the Range element to your Omniscript. Specify the increment values and use static values to define the minimum and maximum values for the range.
Omniscripts Telephone Element
Enable users to enter a phone number by adding a Telephone element to your Omniscript. Limit the length and format of the number the user can enter.
Omniscripts Text Area Element
Enable users to enter multiple lines of text by adding a Text Area element to your Omniscript. Limit the number of characters the user can enter.
Omniscripts Text Element
Enable users to enter a line of text by adding the Text element to your Omniscript. Limit the length of the text using minimum and maximum values and set allowable information using the mask property.
Omniscripts URL Element
Enable users to enter a website address by adding the URL element to your Omniscript. For example, a user can enter https://salesforce.com, or https://www.salesforce.com, and so on.
Upload Files and Images in Omniscripts
To upload files in an Omniscript, add a File input element. To upload an image, add an Image input element. Details about uploads are added to the Files node of the Omniscript's Data JSON.
