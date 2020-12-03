---
title: Contato
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      Olá, obrigado pelo interesse em trabalhar comigo. Você pode preencher o
      formulário abaixo ou enviar um e-mail diretamente para
      [murilopesr@gmail.com](mailto:murilopesr@gmail.com).
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nome
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: E-mail
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Assunto
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Mensagem
        default_value: Não poupe palavras
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
template: advanced
---
