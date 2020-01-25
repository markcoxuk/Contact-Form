# Contact-Form
This is a test contact form created within the requested test parameters.

The form uses the following third party frameworks / libraries:

* jQuery - Latest
* Font Awesome - 5.11.2
* Google Fonts - Yantramanav

## Features
The form leverages jQuery and basic javascript.

### Token Check
Checks for the existence and correct formatting of the test submission token in the URL parameters and warns if the token is missing of malformed.

### Mobile First
The form is responsive and designed for any size / orientation viewport.

### Field validation
Client side checking of field entry for the 4 required fields. Additionally the Phone field only allows positive integers and the Email field checks for valid email address formatting.

### Accessibility
Sturctured <h> tags with relevant information. Form fields have Labels and for= elements. Fieldsets and legends left out as they are unnecessary for this form (the privacy and consect checkboxes are 2 independant questions) and would cause confusion for screen readers in this instance. Clear / Reset button left out as it is rarely useful and can also be inadvertently selected by screen reader users. Large and clear submit button for ease of use on multiple devices.

### User Feedback
Validation failure mesages at the point of failure (next to the relevant field(s)). Submission success / failure messages, colour coded with the traffic light system.

### SEO
Soft SEO in the form of properly structured html / headers and address / alternate contact information.
Hard SEO (meta tags, mapping, relevant copy, indexed images, social plugins and links / livechat) not integrated as it is beyond the scope of this test.

## Features intentionally left out
Features that have not been added to this test form that may be featured in other circumstances:

### Captcha
We do not have access to the form processing server. Client side captcha is inadequate.

### Phone field formatting validation
Internationalisation is beyond the scope of this test and we do not know the origin of our form users. Phone number formatting is intentionally left fuzzy to allow for regionalised variations in phone number formats.

### Custom success / failure messages
We do not have access to the form processing server. The response message is green for soft success along with the data response from the processing server. Hard errors are red with a static message.