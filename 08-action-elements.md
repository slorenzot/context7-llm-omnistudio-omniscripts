# Omniscript Action Elements

> Source: <https://help.salesforce.com/s/articleView?id=xcloud.os_omniscript_action_elements_10951.htm&type=5>
> Salesforce Help — Omnistudio Documentation

Use action elements in an Omniscript for executing actions, such as get or update data from one or more Salesforce objects, call a series of actions, send emails or documents for signature, redirect to different pages. Action elements can be either rendered as a button when placed in a Step or Block or run remotely if placed between steps. In either case, you can specify a redirect page, where the user can proceed to the next step or action, or if a button, back to the source step.
You can prefill values to multiple fields in Omniscript by using Integration Procedure or Data Mapper action elements. If the result of an Integration Procedure or Data Mapper is an update to the Omniscript JSON, it prefills the fields in the Omniscript at run time.
NOTE
Use unique names for Omniscript elements and Omnistudio Data Mapper response nodes.
Common Action Element Properties
Review information about Omniscript action element properties.
Calling a Decision Matrix from an Omniscript
Call a decision matrix with specified inputs and return the matching results to an Omniscript.
Delete an Object Record from an Omniscript
Enable users to delete one or more sObject records by using the Delete Action. Use an Object's Record Id to determine which record to delete. The best practice is to use a merge field to refer to an Id or a list of IDs in the data JSON.
Calling Expression Sets from an Omniscript
From an Omniscript, call an expression set created in the Business Rules Engine, and return its results to the Omniscript. Expression sets evaluate conditions, perform mathematical operations, look up decision tables and matrices, and perform multiple transformations simultaneously.
Sending Email from Omniscripts
Use emails to send alerts or notifications as part of a workflow, such as sending a summary of a customer’s changes to their account information or a report of new customer cases to agents. An Omniscript can send an email from a template or a custom message, and you can use data from Salesforce objects or other data sources in the email address or body fields.
Fill a PDF with a PDF Action
You can fill an existing PDF form with the PDF action and an Omnistudio Data Mapper.
Calling Web Services with the Omniscripts HTTP Action
With the HTTP Action, call internal and external web services from an Omniscript without coding or making Salesforce API calls. You can call an HTTP API that allows Apex, Named Credentials, SOAP/XML, or Web, and use the Omniscript's JSON as input.
Retrieve Data with an Integration Procedure in an Omniscript
From an Omniscript, call an Integration Procedure to retrieve Salesforce data and external data. You can run multiple actions as a headless service (lacking a UI) through JavaScript or Apex Service.
Open Other Pages from Omniscripts with the Navigate Action
To open various Salesforce pages, apps, and resources from Omniscript, use the Navigate element.
Calling Apex from Omniscripts with the Remote Action
Call Apex classes from Omniscript using the Remote element, and use the Omniscript's JSON as input.
Use the DocuSign Signature Action to Sign Documents From Within an Omniscript
Users can sign a document from an Omniscript and download the signed document for their records. After you prepare the DocuSign template and map the fields from the Omniscript to the template using an Omnistudio Data Mapper Transform, you can create a DocuSign Signature Action in the Omniscript. When the action runs, a DocuSign window opens containing the prefilled document. The user must sign or decline to sign the document before continuing the Omniscript.
Use the DocuSign Envelope Action to Email Documents for Signature
Send an email with prefilled documents for signing or reviewing. It can be sent to one or more recipients. After you prepare the DocuSign template and map the fields from the Omniscript to the template using an Omnistudio Data Mapper Transform, you can create a DocuSign Envelope Action in the Omniscript. When the action runs, a DocuSign Envelope containing the prefilled document is emailed to one or more recipients for signing or reviewing.
Set Errors in an Omniscript
To handle potential end-user errors, add an error or validation message on one or more elements in a previous step based on conditions from future steps with the Set Errors element. For example, an email address isn't required during the initial step, but in a future step, the user states that they wish to be contacted by email. The Set Errors element runs after the step and returns the user to the initial step with custom error messages.
Set Values in an Omniscript
Use the Set Values action to set element values in subsequent steps, rename JSON nodes, create dynamic values, and concatenate data. Set Values actions use merge fields to access JSON data in other Omniscript elements.
Emailing an Omniscript
To email a link to an Omniscript to a Contact, Lead, or User, you create an Integration Procedure that uses a remote action to send the email and call the Integration Procedure from an Omniscript or from Apex code.
Set Up Access to Remote Action APIs
Configure access to Apex classes used by the remote actions (Vlocity Open Interface Apex classes) called from an Omniscript, Flexcard, Classic Card, or REST API, by profiles.
