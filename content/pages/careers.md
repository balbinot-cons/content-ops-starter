---
title: Careers
slug: careers
sections:
  - title:
      text: Uma equipe que trabalha em estreita colaboração
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    text: >+
      Colaboração em equipe é a força que potencializa cada habilidade
      individual, criando um todo mais forte e inovador. É o processo onde
      diferentes perspectivas e especialidades se encontram, se entrelaçam e se
      complementam. Quando todos os membros se engajam com propósito e empenho,
      o grupo consegue superar desafios e alcançar metas que seriam impossíveis
      de atingir isoladamente. A verdadeira magia da colaboração está na
      habilidade de combinar o conhecimento coletivo para resolver problemas
      complexos e gerar soluções criativas. É uma dança constante de
      comunicação, confiança e respeito mútuo, onde cada contribuição é valiosa
      e essencial para o sucesso final.

    actions: []
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
