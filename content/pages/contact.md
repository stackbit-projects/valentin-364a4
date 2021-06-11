---
title: Contact
sections:
  - type: hero_section
    title: Contactez - Moi
    subtitle: >-
      Remplissez le formulaire ci-dessous et je vous contacterai dans un délai
      d'un jour ouvrable.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >+
      ## Prix



      Après un court appel d'intégration, je serai en mesure de vous fournir un
      prix approximatif, suivi d'une proposition détaillée une fois que nous
      aurons discuté des détails.


      ### &#xA;Proposition



      Votre proposition comprendra plusieurs choix en termes de structure de
      prix et de calendrier des livrables.


      ### &#xA;Termes



      Si, à un moment quelconque, vous souhaitez annuler notre projet, vous
      devez fournir un préavis écrit de 30 jours, après quoi je vous
      transférerai tous vos actifs afin que vous puissiez les utiliser à tout
      moment.

    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nom
        default_value: Votre nom
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Votre adresse email
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Votre message
      - input_type: checkbox
        name: consent
        label: >-
          Je comprends que ce formulaire stocke mes informations soumises afin
          que je puisse être contacté.
        is_required: true
    submit_label: Envoyer
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
