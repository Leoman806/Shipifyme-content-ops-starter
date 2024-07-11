---
type: PageLayout
title: aboutus
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Shipifyme - 良心社會企業
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: 初心不是為了賺錢，而是為消息者提供可靠網購及物流平台
    text: >
      本網站是由三位熱愛網購的人士成立，他們都在網購上有不愉快經驗，其中兩人最高損失有6位數字。在一次閒談中，三人一拍即合並一起建立一個網上平台協助網友海外購物。之後在天使基金引荐下得到韓國樂天集團前電子商貿總經理Kim
      Jae Jun投資本網站。幾個月後，曾在美國eBay任職28年並退休的 David Rhonda Hunter
      更加入我們成為非執行董事並提供策略性建議。
    actions: []
    colors: bg-neutral-fg-dark
    backgroundImage:
      type: BackgroundImage
      url: /images/abstract-background.svg
      altText: Placeholder image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
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
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: Shipifyme 成員
      color: text-dark
      styles:
        self:
          textAlign: center
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
    actions: []
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
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: 聯絡我們
        tagline: Feature 1
        subtitle: ''
        text: |
          Email: xxx\@xxx.com
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Featured item
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
slug: aboutus
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
