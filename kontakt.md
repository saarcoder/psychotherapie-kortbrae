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
    add-text: >
      Bitte benutzen Sie für den E-Mail-Kontakt meine u.a. Kontaktadresse!
    Psychotherapeutische Praxis Sabine Kortbrae
    Wolfsgangstraße 65
    60322 Frankfurt
    Telefon: 069 – 13 39 12 67
    E-Mail: kontakt@psychotherapie-kortbrae.de
    Eingetragen im Psychotherapeutenregister der Kassenärztlichen Vereinigung Hessen, Nr. 89142


    Anfahrt mit öffentlichen Verkehrsmitteln
    S-Bahn  Hauptwache
    U-Bahn  Grüneburgweg
    Anfahrt mit dem Auto
    Parkhaus Turmcenter 15 Min. Fußweg

    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Dein Name
        is_required: true
      - input_type: email
        name: email
        label: E-Mail
        default_value: Deine E-Mail-Adresse
        is_required: true
      - input_type: select
        name: subject
        label: Wonach suchst Du?
        default_value: Bitte auswählen
        options:
          - Ayurveda-Beratung
          - Kursanmeldung
          - Newsletter
      - input_type: textarea
        name: message
        label: Nachricht
        default_value: Deine Nachricht
      - input_type: checkbox
        name: consent
        label: >-
          Ich habe verstanden, dass mit diesem Formular meine Daten online
          übermittelt werden, damit ich kontaktiert werden kann.
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
