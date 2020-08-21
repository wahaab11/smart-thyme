---
title: Get in Touch
img_path: images/contact.jpg
form_id: contactForm
form_fields:
  - type: form_field
    input_type: text
    name: name
    label: Name
    default_value: Your name
    is_required: true
  - type: form_field
    input_type: email
    name: email
    label: Email
    default_value: Your email address
    is_required: true
  - type: form_field
    input_type: select
    name: subject
    label: Subject
    default_value: Please select
    options:
      - Error on the site
      - Sponsorship
      - Other
  - type: form_field
    input_type: textarea
    name: message
    label: Message
    default_value: Your message
  - type: form_field
    input_type: checkbox
    name: consent
    label: I understand that this form is storing my submitted information so I can
      be contacted.
submit_label: Send Message
layout: contact
---
To get in touch fill the form below.

<!--StartFragment-->

```
<html>
<head>
  <title>A static website</title>

  <!-- include the widget -->
  <script type="text/javascript" src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
</head>
<body>
  <!-- Add a menu:
   Log in / Sign up - when the user is not logged in
   Username / Log out - when the user is logged in
  -->
  <div data-netlify-identity-menu></div>

  <!-- Add a simpler button:
    Simple button that will open the modal.
  -->
  <div data-netlify-identity-button>Login with Netlify Identity</div>
</body>
</html>
```

<!--EndFragment-->