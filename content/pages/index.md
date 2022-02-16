---
title: Home
layout: PageLayout
colors: colors-a
backgroundImage:
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - colors: colors-f
    elementId: ''
    variant: variant-a
    text: "Hi, my name is Ohad. I’m a programmer, entrepreneur, and occasional investor living in San Francisco. You can contact me at\_**me \\[at] this domain \\[dot] com**,\_[@ohadpr](https://twitter.com/ohadpr),\_[linkedin.com/in/ohadpr](https://linkedin.com/in/ohadpr)\n"
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - colors: colors-f
    elementId: ''
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Present
        text: "*   Co-founder & CEO of\_[Stackbit](https://www.stackbit.com/)\_which is a platform for building Jamstack websites\n\n*   Early-stage investor in startups like\_[Cased](https://www.cased.com/),\_[Riverside](https://riverside.fm/),\_[Sanity](https://www.sanity.io/),\_[Dev](https://dev.to/),\_[Chromatic](https://www.chromatic.com/),\_[Domestika](https://www.domestika.org/en),\_[Netlify](https://www.netlify.com/),\_[PeerSpace](https://www.peerspace.com/),\_[Bottomless](https://www.bottomless.com/),\_[Loop Commerce](https://www.loopcommerce.com/),\_[IFTTT](https://ifttt.com/), and others\n\n*   On the Board of Directors of\_[Netlify](https://www.netlify.com/), which is changing the way people build, deploy, and manage modern web projects\\* Co-founder & President of\_[AppSharp](https://www.appsharp.com/), which builds software to help small businesses thrive\n\n"
        actions:
          - type: Button
            label: ''
            showIcon: true
            icon: arrowRight
            url: /
            style: primary
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Past
        text: "*   Founded and was CEO of\_[3D3R Software](https://www.3d3r.com/), which\_[Chegg](https://www.chegg.com/)\_(NYSE:CHGG) acquired, I served as Chegg’s VP R\\&D until 2016\n\n*   Co-founded\_[GarageGeeks](http://garagegeeks.org/), which was a physical & virtual space for multi-disciplinary creative people to meet, innovate and build\n\n*   Developed\_[games for the PalmPilot](https://www.ohadpr.com/etc/pilot/pilot), including the world’s best selling Checkers game for the platform\n\n*   Started the\_[Demoscene](http://en.wikipedia.org/wiki/Demoscene)\_group\_[IMR](http://www.pouet.net/groups.php?which=1651)\_which won several international awards, wrote lots of 0x86 assembly code\n\n"
        actions:
          - type: Button
            label: ''
            showIcon: true
            icon: arrowRight
            url: /
            style: primary
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: I'm Focused
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: ''
            showIcon: true
            icon: arrowRight
            url: /
            style: primary
        styles:
          self:
            textAlign: left
    actions: []
    columns: 1
    spacingX: 16
    spacingY: 16
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: 'Projects:'
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-seven.md
      - content/pages/blog/post-six.md
      - content/pages/blog/post-one.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
