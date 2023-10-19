# Accessibility Resources

This repository is an open-source project seeking contributions for resources and tools relating to web accessibility, and making the web better for everyone.

Currently this repo is a mess of notes and links... help us make it better!

## 📖 Table of Contents

- [What is accessibility?](#what-is-accessibility)
- [Things to consider when creating web and digital products](#accessibility-things-to-consider-when-creating-web-and-digital-products)
- [Tools and Resources](#tools-and-resources)
- [Questions for digital teams and organisations to ask?](#questions-for-digital-teams-and-organisations-to-ask)
- [Who in an org should be responsible for accessibilitiy?](#who-in-an-org-should-be-responsible-for-accessibilitiy)
- [Assistive technology in action](#assistive-technology-in-action)
- [Other notes and incomplete thoughts](#other-notes-and-incomplete-thoughts)

## What is accessibility?
**[`^  back to top  ^`](#accessibility-resources)**

On the web, accessibility ensures that users with disabilities are able to use all facets of a website. The World Wide Web Consortium (W3C) defines accessibility standards and guidelines that all website designers and developers should comply with.

Accessibility is often pooled together with other web standards like performance, usability and security at the end of developing a web project though our aim is to make it a priority throughout all stages of web development.

## Accessibility things to consider when creating web and digital products:
**[`^  back to top  ^`](#accessibility-resources)**
- POUR principles: Perceivable, operable, understandable, robust
- HTML: use sematic elements (nav, section, article, aside, footer, header, etc) instead of divs - to assist with screen readers
- Video captions
- Color blindness
- Bionic reading
- Sensory considerations
- Autoplay of sound and video
- Design features that are meaningful vs decorative
- Separate css stylesheets for different access requirements (print, screen readers, colour blind, dark mode, slow connections)
- Image descriptions and alt text
- Text should always be written, not in a flat image
- Building websites for slow internet connections, with technologies e.g Lazy Load, optimized images, fallback, SWR etc

## Tools and Resources:
**[`^  back to top  ^`](#accessibility-resources)**
- [W3C Markup Validation Service](https://validator.w3.org/): This validator checks the markup validity of Web documents in HTML, XHTML, SMIL, MathML, etc.
- [Who Can Use](https://www.whocanuse.com/)
- [Digital NSW Colour Contrast resource](https://www.digital.nsw.gov.au/delivery/accessibility-and-inclusivity-toolkit/inclusive-design/colour-contrast)
- [Vic government typography and accessibility colour digital guide](https://www.vic.gov.au/typography-and-accessible-colour-digital-guide)
- [Bionic Reading chrome extension](https://chrome.google.com/webstore/detail/bionic-reading/kdfkejelgkdjgfoolngegkhkiecmlflj/related)
- A11y project [WCAG compliance checklist](https://www.a11yproject.com/checklist/)
- Otter AI
- https://www.w3.org/WAI/business-case/
- https://www.w3.org/WAI/standards-guidelines/wcag/
- https://fonts.google.com/knowledge/readability_and_accessibility/introducing_accessibility_in_typography
- https://css-tricks.com/making-calendars-with-accessibility-and-internationalization-in-mind/
- https://www.tawdis.net/#
- https://chrome.google.com/webstore/detail/arc-toolkit/chdkkkccnlfncngelccgbgfmjebmkmce
- https://www.st-andrews.ac.uk/itsnew/web/accessibility/cynthia_validator.shtml
- https://www.w3.org/TR/2015/REC-ATAG20-20150924/
- https://achecks.org/achecker
- https://wave.webaim.org/
- https://www.linkedin.com/learning/accessibility-first-design
- [Quick accessibility tests](https://youtu.be/ahDuaWKSGZA?si=QCTquw10i9R3h-MT) (YouTube playlist)

### Assistive technology
**[`^  back to top  ^`](#accessibility-resources)**

Manual accessibility testing using assistive technology is a key part of ensuring your website is accessible.

#### Screen readers

##### VoiceOver for Mac

- VoiceOver comes built-in with Mac
- [A11ycasts tutorial](https://www.youtube.com/watch?v=5R-6WvAihms&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g&index=9)
- [Testing template](https://accessibility-manual.dwp.gov.uk/best-practice/screen-reader-testing#voiceover-on-os-x)

##### NVDA for Windows

- [Free download](https://www.nvaccess.org/download/)
- [A11ycasts tutorial](https://www.youtube.com/watch?v=Jao3s_CwdRU&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g&index=9)
- [Testing template](https://accessibility-manual.dwp.gov.uk/best-practice/screen-reader-testing#nvda-on-windows)

##### ChromeVox for ChromeBook

- ChromeVox comes built-in with Chromebook
- [A11ycasts tutorial](https://www.youtube.com/watch?v=fpbIsN31hLM)

##### VoiceOver on iOS

- [A11ycasts tutorial](https://www.youtube.com/watch?v=bCHpdjvxBws&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g&index=28)

##### TalkBack for Android

- [A11ycasts tutorial](https://www.youtube.com/watch?v=0Zpzl4EKCco&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g&index=27)

#### Voice controllers

##### Voice Control for iOS

- BBC News process for [testing with Voice Control](https://bbc.github.io/accessibility-news-and-you/assistive-technology/testing-steps/voice-control-ios.html)

##### Voice Access for Android

- BBC News process for [testing with Voice Access](https://bbc.github.io/accessibility-news-and-you/assistive-technology/testing-steps/voice-access-android.html)

#### Screen magnifiers

##### Zoom on OS X

- DWP UK's template for [testing Zoom on OS X](https://accessibility-manual.dwp.gov.uk/best-practice/screen-magnifier-testing)

#### Assistive technology in action

- [Kristy Viers uses voiceover and braille keyboard on the iphone](https://www.youtube.com/watch?v=wueLXCbm_KY)
- [Kristy Viers uses voiceover and braille keyboard on the ipad](<https://www.youtube.com/watch?v=vpQEQU3ExA0\ >)
- [Jared Smith on his difficulties accessing the web as a blind user](https://youtu.be/yx7hdQqf8lE)
- [How Jared uses a sip and puff to control his computer](https://www.youtube.com/watch?v=Bhj5vs9P5cw)
- [Rakesh Babu's experiences as a blind user](https://youtu.be/qL4shFJHOvc)
- [How Christina uses email and twitter as a blind user](https://youtu.be/_OO9w_oK6dQ)
- [Using an iphone as a blind user (filling out form)](https://www.youtube.com/watch?v=nw6-eDJXWzY)
- [Jeff playing Assassins Creed with a quadstick](https://youtu.be/eFkhFxJZvho)
- [Carrie on Accessibility](https://www.youtube.com/channel/UCraSGW8s4NMaFKrJ5YbjB4w)
- [Web AIM perspective videos](https://www.w3.org/WAI/perspective-videos/)
- [Web AIM user stories](https://www.w3.org/WAI/people-use-web/user-stories/)
- [Aimee Mullins TED talk on her prosthetic legs](https://youtu.be/JQ0iMulicgg)
- [Endless Thread episode about how reddit failed it's blind moderators](https://www.wbur.org/endlessthread/2023/06/28/reddit-api-blind)

## Questions for digital teams and organisations to ask:
**[`^  back to top  ^`](#accessibility-resources)**
- What would an accessibility-first process for digital products look like?
- What would an accessibility pledge look like?
- How can digital teams bake accessibility into their process?
- How does an organisation prioritise accecessibility?

## Who in an org should be responsible for accessibilitiy?
**[`^  back to top  ^`](#accessibility-resources)**
- Designers:
- Content Writers:
- Devs and techies:
- QA and testers:
- Accessibility committees:
- EVERYONE!

## Assistive technology in action
**[`^  back to top  ^`](#accessibility-resources)**
- [Kristy Viers uses voiceover and braille keyboard on the iphone](https://www.youtube.com/watch?v=wueLXCbm_KY)
- [Kristy Viers uses voiceover and braille keyboard on the ipad]( https://www.youtube.com/watch?v=vpQEQU3ExA0\ )
- [Jared Smith on his difficulties accessing the web as a blind user](https://youtu.be/yx7hdQqf8lE)
- [How Jared uses a sip and puff to control his computer](https://www.youtube.com/watch?v=Bhj5vs9P5cw)
- [Rakesh Babu's experiences as a blind user](https://youtu.be/qL4shFJHOvc)
- [How Christina uses email and twitter as a blind user](https://youtu.be/_OO9w_oK6dQ)
- [Using an iphone as a blind user (filling out form)](https://www.youtube.com/watch?v=nw6-eDJXWzY)
- [Jeff playing Assassins Creed with a quadstick](https://youtu.be/eFkhFxJZvho)
- [Carrie on Accessibility](https://www.youtube.com/channel/UCraSGW8s4NMaFKrJ5YbjB4w)
- [Web AIM perspective videos](https://www.w3.org/WAI/perspective-videos/)
- [Web AIM user stories](https://www.w3.org/WAI/people-use-web/user-stories/)
- [Aimee Mullins TED talk on her prosthetic legs](https://youtu.be/JQ0iMulicgg)
- [Endless Thread episode about how reddit failed it's blind moderators](https://www.wbur.org/endlessthread/2023/06/28/reddit-api-blind)

## Other notes and incomplete thoughts
**[`^  back to top  ^`](#accessibility-resources)**
- Accessibility on Instagram - how does Instagram incorporate accessibility?
- The Roboto font - apparently this font is accessibility friendly, was it designed with this in mind?
- Other fonts that are dyslexia friendly
- [Person sues Coles for poor accessibility](https://www.business-humanrights.org/en/latest-news/australia-customer-sues-coles-supermarkets-over-alleged-disability-discrimination-re-accessibility-of-website/)
- "Digital" isn't just about web - how do we consider accessibility in webinars and online events, emails, audio, etc
- Sometimes the robot is good - can we use AI tools ethically for accessibility,e g. Otter AI for transcripts and meeting summaries, ChatGPT for digesting information and reducing overwhelm etc
- Autoplay of music and video - MySpace songs. Context is key. TikTok "mute on entry" setting.
- Dark patterns e.g. cannot unsubscribe to service.
- How do we consider people who aren't as tech savvy in how we set up our websites / apps/ digital products?
- [Helping blind people learn to code](https://www.freecodecamp.org/news/helping-blind-people-learn-to-code-c47c68d4a237/)
- Accessibility workshops?
- An accessibility-first website project would be a great portfolio piece (e.g. for someone looking for an internship)