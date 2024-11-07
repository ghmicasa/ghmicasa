---
title: Contact
form:
  to: contact@roopesh-singh.com
  subject: New submission!
  redirect: /
  form_engine: formspree
  placeholders: false
  fields:
    - name: name
      input_type: text
      placeholder: Name
      required: true
    - name: email
      input_type: email
      placeholder: Email address
      required: true
    - name: sex
      input_type: radio
      placeholder: male
      required: true
    - name: sex
      input_type: radio
      placeholder: female
      required: true
    - name: message
      input_type: textarea
      placeholder: Message
      required: false
    - name: terms
      input_type: checkbox
      placeholder: I accept the terms and conditions
      required: true
    - name: submit
      input_type: submit
      placeholder: Submit form
      required: true
description: Feel free to leave me a (nice) message. Connect with me, and share your thoughts. You can contact me via filling this form, or by e-mail.
---

### Feel free to leave me a (nice) message. Have a nice day!
Please read <a href="/terms">terms and conditions</a> before for filling out this form, or sending an e-mail.

### Contact form
<br/>
{% include form.html %}

<!--
### Contact e-mail
<br/>
You can contact me through e-mail at <a href="mailto:contact@roopesh-singh.com">contact@roopesh-singh.com</a>.
-->
