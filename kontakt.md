---
title: Kontakt
hide_title: true
sections:
  - type: form_section
    section_id: contact-form
    title: Kontakt
    subtitle: Nachricht senden
    content: >
      Wenn Sie eine Frage haben oder einen Termin für ein Erstgespräch
      vereinbaren möchten, senden Sie mir eine Nachricht.
    add-text: "Bitte benutzen Sie für den E-Mail-Kontakt meine u.a. Kontaktadresse!\n\n#### Psychotherapeutische Praxis Sabine Kortbrae\n\nWolfsgangstraße 65\n\n60322 Frankfurt\n\nTelefon: 069 – 13 39 12 67\n\nE-Mail: <kontakt@psychotherapie-kortbrae.de>\n\nEingetragen im Psychotherapeutenregister der Kassenärztlichen Vereinigung Hessen, Nr. 89142\n\n#### Anfahrt mit öffentlichen Verkehrsmitteln\n\n**<mark>S-Bahn</mark>**\_ Hauptwache\n\n**<mark>U-Bahn</mark>**\_ Grüneburgweg (U1, U2, U3, U8)\n\n#### Anfahrt mit dem Auto\n\nParkhaus Turmcenter 15 Min. Fußweg\n"
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Ihr Name
        is_required: true
      - input_type: email
        name: email
        label: E-Mail
        default_value: Ihre E-Mail-Adresse
        is_required: true
      - input_type: tel
        name: phone
        label: Telefonnummer
        default_value: Ihre Telefonnummer
        is_required: true
      - input_type: textarea
        name: message
        label: Ihre Nachricht
        default_value: Geben Sie hier Ihre Nachricht ein
        is_required: true
      - input_type: checkbox
        name: consent
        label: Ich habe die <a href="/datenschutz">Datenschutzbestimmungen</a> gelesen und erkenne sie an.
        is_required: true
    submit_label: Nachricht senden
seo:
  title: Kontakt
  description: Dies ist die Kontaktseite
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Kontakt
      keyName: property
    - name: 'og:description'
      value: Dies ist die Kontaktseite
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Kontakt
    - name: 'twitter:description'
      value: Dies ist die Kontaktseite
layout: advanced
---
