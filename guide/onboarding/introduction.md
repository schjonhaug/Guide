---
layout: guide
title: Onboarding
description: An overview of some of the concepts to consider when building onboarding experiences.
has_children: true
nav_order: 4
permalink: /guide/onboarding/introduction/
main_classes: -no-top-padding
image: https://bitcoin.design/assets/images/guide/onboarding/onboarding-preview.png
---

<!--

Editor's notes

A brief introduction and summary of all pages in this section. The idea is that readers
scan this page to get an overview of the section and then decide which topics to dive into.

-->

{% include picture.html
   image = "/assets/images/guide/onboarding/onboarding-main.png"
   retina = "/assets/images/guide/onboarding/onboarding-main@2x.png"
   mobile = "/assets/images/guide/onboarding/onboarding-main-mobile.png"
   mobileRetina = "/assets/images/guide/onboarding/onboarding-main-mobile@2x.png"
   alt-text = "Onboarding landing page header"
   width = 1600
   height = 600
   layout = "full-width"
%}

# Onboarding

Onboarding, the first use, can make or break someone’s experience of a product. Therefore it is important to identify your target audience and design specifically with its context, expectations, and needs in mind.

Some new users bring years of traditional financial experience to Bitcoin. They have bank accounts, debit cards, and ingrained ideas about what money is. This makes onboarding tricky, as the user might assume that the patterns and habits from prior experience will apply. If you design a user experience that is superior to the traditional system, convincing users to switch to a different financial system will be a lot easier.

On the other hand, close to [two billion](https://globalfindex.worldbank.org/sites/globalfindex/files/chapters/2017%20Findex%20full%20report_chapter2.pdf) people have no exposure to traditional financial institutions. This, along with designing for younger people whose ideas about money aren’t fully formed, represents a very different challenge.

Onboarding, for this guide, refers to anything that helps users set up the product or learn its interface (such as dedicated flows and UI elements) and initially focuses on mobile applications. But onboarding isn’t just for first-time users. Experienced users also need to be onboarded, especially when new features are added.

Remember: Onboarding should not be a crutch for bad design. Avoid trying to explain too much and then shooting users into a poorly designed app. Rather, think about onboarding flows as a smooth on-ramp into a great user experience.

---

### [First use]({{ '/guide/onboarding/first-use/' | relative_url }})

An overview of common tasks when using a wallet application for the first time.

---

### [Backing up a wallet]({{ 'guide/onboarding/backing-up-a-wallet' | relative_url }})

An overview of the tradeoffs between using [manual backup]({{ 'guide/onboarding/backing-up-a-wallet/manual-backup' | relative_url }}) vs [automatic cloud backup]({{ 'guide/onboarding/backing-up-a-wallet/cloud-backup' | relative_url }}).

---

### [Restoring a wallet]({{ 'guide/onboarding/restoring-a-wallet' | relative_url }})

What options to consider if a user has lost their device, had it stolen or deleted and redownloaded a particular wallet application.

---

### [Protecting a wallet]({{ 'guide/onboarding/protecting-a-wallet' | relative_url }})

An overview of how to add extra layers of securtiy to protect sensitive user data.

---

### [Funding a wallet]({{ 'guide/onboarding/funding-a-wallet' | relative_url }})

An overview of how users are likely to fund their wallets

---

{% include next-previous.html
   previousUrl = "/guide/designing-products/design-resources/"
   previousName = "Design resources"
   nextUrl = "/guide/onboarding/first-use/"
   nextName = "First use"
%}
