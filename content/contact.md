---
title: Contact Us
hide_title: false
sections:
- type: section_form
  template: section_form
  section_id: contact-form
  content: To get in touch please fill the form below.
  form_id: contactForm
  form_action: "/thank-you"
  form_fields:
  - type: form_field
    template: form_field
    input_type: text
    name: name
    label: Name
    default_value: Your name
    is_required: true
    options: []
  - type: form_field
    template: form_field
    input_type: email
    name: email
    label: Email
    default_value: Your email address
    is_required: true
    options: []
  - type: form_field
    template: form_field
    input_type: select
    name: subject
    label: Subject
    default_value: Please select
    options:
    - Error on the site
    - Sponsorship
    - Other
    is_required: false
  - type: form_field
    template: form_field
    input_type: textarea
    name: message
    label: Message
    default_value: Your message
    options: []
    is_required: false
  - type: form_field
    template: form_field
    input_type: checkbox
    name: consent
    label: I understand that this form is storing my submitted information so I can
      be contacted.
    default_value: ''
    options: []
    is_required: false
  submit_label: Send Message
  title: ''
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Contact
  description: This is the contact page
  extra:
  - name: og:type
    value: website
    keyName: property
    relativeUrl: false
  - name: og:title
    value: Contact
    keyName: property
    relativeUrl: false
  - name: og:description
    value: This is the contact page
    keyName: property
    relativeUrl: false
  - name: twitter:card
    value: summary
    keyName: ''
    relativeUrl: false
  - name: twitter:title
    value: Contact
    keyName: ''
    relativeUrl: false
  - name: twitter:description
    value: This is the contact page
    keyName: ''
    relativeUrl: false
  robots: []
layout: advanced
excerpt: ''

---
