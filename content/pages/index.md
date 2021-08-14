---
title: Home
sections:
  - type: hero_section
    title: This Is A Big Hero Headline
    subtitle: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
      quis lorem malesuada luctus.
    actions:
      - label: Learn More
        url: /features
        style: primary
      - label: Contact Us
        url: /contact
        style: secondary
    align: left
    image: images/hero.svg
    image_alt: Hero placeholder image
    image_position: right
    has_background: true
    background:
      background_color: blue
      background_image: images/diagonal-lines.svg
      background_image_opacity: 20
      background_image_size: auto
      background_image_repeat: repeat
  - type: features_section
    title: Features
    features:
      - title: Feature 1
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla.
        align: left
        image: images/feature.svg
        image_alt: Feature 1 placeholder image
        image_position: right
        actions:
          - label: Learn More
            url: /features
            style: secondary
      - title: Feature 2
        content: >-
          Ac felis donec et odio pellentesque. Sagittis vitae et leo duis ut
          diam quam nulla. Ullamcorper a lacus vestibulum sed arcu non odio
          euismod lacinia.
        align: left
        image: images/feature.svg
        image_alt: Feature 2 placeholder image
        image_position: left
        actions:
          - label: Learn More
            url: /features
            style: secondary
      - title: Feature 3
        content: >-
          Id nibh tortor id aliquet lectus proin. Amet venenatis urna cursus
          eget nunc. Lacus sed turpis tincidunt id aliquet risus feugiat in
          ante.
        align: left
        image: images/feature.svg
        image_alt: Feature 3 placeholder image
        image_position: right
        actions:
          - label: Learn More
            url: /features
            style: secondary
  - type: blog_feed_section
    title: What's New
    show_recent: true
    recent_count: 3
  - type: cta_section
    title: This Is A CTA
    subtitle: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
      quis lorem malesuada luctus.
    actions:
      - label: Learn More
        url: /features
        style: primary
      - label: lorem-ipsum
        url: '#'
        style: link
        new_window: false
        no_follow: false
        type: action
    has_background: true
    background_color: gray
  - title: lorem-ipsum
    type: contact_section
- section_id: testimonials
    type: section_testimonials
    title: Testimonials
    subtitle: An optional subtitle of the section
    col_number: two
    testimonials:
      - author: Sean Salazar
        avatar: images/sean_salazar.jpg
        avatar_alt: Sean Salazar's photo
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla.
      - author: Aubrey Hoover
        avatar: images/aubrey_hoover.jpg
        avatar_alt: Aubrey Hoover's photo
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Deegan Wallace
        avatar: images/deegan_wallace.jpg
        avatar_alt: Deegan Wallace's photo
        content: >-
            hello
          Sedd laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam.
      - author: Deegan Wallace
        avatar_alt: Deegan Wallace's photo
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam.  
  - section_id: latest-posts
    type: section_posts
    title: Latest from the Blog
    subtitle: An optional subtitle of the section
    posts_number: 3
    col_number: three
    actions:
      - label: View Blog
        url: blog
        style: button
seo:
  title: Stackbit Starter Theme
  description: The preview of the Starter theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Starter Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Starter theme
      keyName: property
    - name: 'og:image'
      value: images/starter-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Starter Theme
    - name: 'twitter:description'
      value: The preview of the Starter theme
    - name: 'twitter:image'
      value: images/starter-preview.png
      relativeUrl: true
layout: advanced
---
