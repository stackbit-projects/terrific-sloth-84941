---
title: Contato
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      Olá, obrigado pelo interesse em trabalhar comigo. Você pode preencher o
      formulário abaixo ou enviar um e-mail diretamente para
      [murilopesr@gmail.com](mailto:someone@microsoft.com?subject=Hello%20again)
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nome
        default_value: Seu nome
        is_required: true
      - input_type: email
        name: email
        label: E-mail
        default_value: Digite aqui o seu melhor e-mail
        is_required: true
      - input_type: select
        name: Escolha um
        label: Assunto
        default_value: Selecione um assunto
        options:
          - Orçamento
          - Dúvidas
          - Outro
      - input_type: textarea
        name: message
        label: Mensagem
        default_value: Digite aqui a sua mensagem
      - input_type: checkbox
        name: consent
        label: >-
          Eu entendo que este formulário está armazenando minhas informações
          enviadas para que eu possa ser contatado.
        is_required: true
      - input_type: tel
        name: lorem-ipsum
        label: lorem-ipsum
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
    submit_label: Enviar
template: advanced
---
