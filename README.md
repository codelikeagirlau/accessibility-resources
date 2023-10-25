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

<<<<<<< HEAD
=======
## Who in an org should be responsible for accessibilitiy?

**[`^  back to top  ^`](#accessibility-resources)**

- Designers:
- Content Writers:
- Devs and techies:
- QA and testers:
- Accessibility committees:
- EVERYONE!

>>>>>>> 3225ec206f29ebafea30c90aec7d19e2fdc7916e
## Assistive technology in action

**[`^  back to top  ^`](#accessibility-resources)**

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

## People to Follow in Web Accessibility

Below is a list of individuals who are strong advocates for Accessibility and Inclusivity in the digital world. Some of the names on this list draw inspiration from the repo of [@Joe Watkins](https://github.com/joe-watkins/top-people-to-follow-in-web-accessibility).
| Name | Twitter |
| --- | --- |
|Jennison Asuncion|[@Jennison](https://twitter.com/Jennison)|
|Steve Faulkner|[@stevefaulkner](https://twitter.com/stevefaulkner)|
|Léonie Watson|[@LeonieWatson](https://twitter.com/LeonieWatson)|
|Marcy Sutton Todd|[@marcysutton](https://twitter.com/marcysutton)|
|Jennison Asuncion|[@Jennison](https://twitter.com/Jennison)|
|Billy Gregory|[@thebillygregory](https://twitter.com/thebillygregory)|
|Karl Groves|[@karlgroves](https://twitter.com/karlgroves)|
|Joe Dolson|[@joedolson](https://twitter.com/joedolson)|
|Henny Swan|[@iheni](https://twitter.com/iheni)|
|Derek Featherstone|[@feather](https://twitter.com/feather)|
| Accessibility is important | [@a11yisimportant](https://twitter.com/a11yisimportant) |
| Adrian Roselli | [@aardrian](https://twitter.com/aardrian) |
| Alistair Duggin | [@dugboticus](https://twitter.com/dugboticus) |
| Anand Chowdhary | [@anandchowdhary](https://twitter.com/anandchowdhary) |
| Andrea Skeries | [@Artistic_Abode](https://twitter.com/Artistic_Abode) |
| Andrew Arch | [@amja](https://twitter.com/amja) |
| Andy Ronksley | [@RooRonks](https://twitter.com/RooRonks) |
| Arthur Rigaud | [@arigaud_ca](https://twitter.com/arigaud_ca) |
| Ashley Bischoff | [@handcoding](https://twitter.com/handcoding) |
| Becky Gibson | [@becka11y](https://twitter.com/becka11y) |
| Billy Gregory | [@thebillygregory](https://twitter.com/thebillygregory) |
| Bruno Pulis | [@obrunopulis](https://twitter.com/obrunopulis) |
| Cameron Cundiff | [@ckundo](https://twitter.com/ckundo) |
| Carie Fisher | [@cariefisher](https://twitter.com/cariefisher) |
| Charlie Turrell | [@AccessibilityC3](https://twitter.com/AccessibilityC3) |
| Claudia Nascimento | [@claumartin](https://twitter.com/claumartin)
| Claudio Luís Vera | [@modulist](https://twitter.com/modulist)
| Cordelia McGee-Tubb | [@cordeliadillon](https://twitter.com/cordeliadillon) |
| Cynthia Shelly | [@cyns](https://twitter.com/cyns) |
| Daniel Göransson | [@DanielGoransson](https://twitter.com/DanielGoransson) |
| Darek Kay | [@darek_kay](https://twitter.com/darek_kay) |
| Dave Rupert | [@davatron5000](https://twitter.com/davatron5000) |
| David A. Kennedy | [@davidakennedy](https://twitter.com/davidakennedy) |
| Deborah Edwards-Oñoro | [@redcrew](https://twitter.com/redcrew) |
| Debra Ruh | [@debraruh](https://twitter.com/debraruh) |
| Denis Boudreau | [@dboudreau](https://twitter.com/dboudreau) |
| Dennis Gaebel | [@gryghostvisuals](https://twitter.com/gryghostvisuals) |
| Dennis Lembrée | [@dennisl](https://twitter.com/dennisl) |
| Derek Featherstone | [@feather](https://twitter.com/feather) |
| Devon Persing | [@devonpersing](https://twitter.com/devonpersing) |
| Doug Schepers | [@shepazu](https://twitter.com/shepazu) |
| Dylan Barrell | [@dylanbarrell](https://twitter.com/dylanbarrell) |
| Eliza Greenwood | [@E_lizaG](https://twitter.com/E_lizaG) |
| Eric Bailey | [@ericwbailey](https://twitter.com/ericwbailey) |
| Eric Eggert | [@yatil](https://twitter.com/yatil) |
| Eric Wright | [@ewaccess](https://twitter.com/ewaccess) |
| Glenda Sims | [@goodwitch](https://twitter.com/goodwitch) |
| Graham Armfield | [@coolfields](https://twitter.com/coolfields) |
| Greg Tarnoff | [@gregtarnoff](https://twitter.com/gregtarnoff) |
| Harcourt Hamsa | [@freescrpt](https://twitter.com/freescrpt) |
| Hector Minto | [@hminto](https://twitter.com/hminto) |
| Helena McCabe | [@misshelenasue](https://twitter.com/misshelenasue) |
| Henny Swan | [@iheni](https://twitter.com/iheni) |
| Heydon Pickering | [@heydonworks](http://twitter.com/heydonworks) |
| Hidde de Vries | [@hdv](http://twitter.com/hdv) |
| Ida Franceen | [@kolombiken](http://twitter.com/kolombiken) |
| Ire Aderinokun | [@ireaderinokun](http://twitter.com/ireaderinokun) |
| Jamie Knight | [@JamieKnight](https://twitter.com/JamieKnight) |
| Jared Smith | [@jared_w_smith](https://twitter.com/jared_w_smith) |
| Jeffrey Zeldman | [@zeldman](https://twitter.com/zeldman) |
| Jen Simmons | [@jensimmons](https://twitter.com/jensimmons) |
| Jennison Asuncion | [@Jennison](https://twitter.com/Jennison) |
| JoAnna Hunt | [@johunt0311](https://twitter.com/johunt0311) |
| Joe Dolson | [@joedolson](https://twitter.com/joedolson) |
| Joe Watkins | [@\_josephwatkins](https://twitter.com/_josephwatkins) |
| John Foliot | [@johnfoliot](https://twitter.com/johnfoliot) |
| John McNabb | [@JohnKMcNabb](https://twitter.com/JohnKMcNabb) |
| Jonathan Hassell | [@jonhassell](https://twitter.com/jonhassell) |
| Jonny James | [@heresjonnyjames](https://twitter.com/heresjonnyjames) |
| Joseph Karr O'Connor | [@AccessibleJoe](https://twitter.com/AccessibleJoe) |
| Jules Ernst | [@JulezRulez](https://twitter.com/JulezRulez) |
| Julianna Rowsell | [@JuliannaRowsell](https://twitter.com/JuliannaRowsell) |
| Karl Groves | [@karlgroves](https://twitter.com/karlgroves) |
| Lainey Feingold | [@LFLegal](https://twitter.com/LFLegal) |
| Laura Carlson | [@laura_carlson](https://twitter.com/laura_carlson) |
| Laura Kalbag | [@laurakalbag](https://twitter.com/laurakalbag) |
| Léonie Watson | [@LeonieWatson](http://twitter.com/LeonieWatson) |
| Luis Garcia | [@garcialo](https://twitter.com/garcialo) |
| Lucy Greco | [@accessaces](https://twitter.com/accessaces) |
| Luke McGrath | [@lukejmcgrath](https://twitter.com/lukejmcgrath) |
| Manjula Dube | [@manjula_dube](https://twitter.com/mmatuzomanjula_dube) |
| Manuel Matuzović | [@mmatuzo](https://twitter.com/mmatuzo) |
| Marcelo Sales | [@msales](https://twitter.com/msales) |
| Marco Zehe | [@MarcoZehe](https://twitter.com/MarcoZehe) |
| Marcy Sutton | [@marcysutton](http://twitter.com/marcysutton) |
| Melanie Sumner | [@melaniersumner](https://twitter.com/melaniersumner) |
| Michael Spellacy | [@spellacy](https://twitter.com/spellacy) |
| Michiel Bijl | [@MichielBijl](https://twitter.com/MichielBijl) |
| Mike Gifford | [@mgifford](https://twitter.com/mgifford) |
| Mike Paciello | [@mpaciello](https://twitter.com/mpaciello) |
| Molly Watt | [@MollyWattTalks](https://twitter.com/MollyWattTalks) |
| Monika Piotrowicz | [@monsika](https://twitter.com/monsika) |
| Neil Milliken | [@NeilMilliken](https://twitter.com/NeilMilliken) |
| Nicolas Steenhout | [@vavroom](https://twitter.com/vavroom) |
| Patrick Fox | [@patrickfox](https://twitter.com/patrickfox) |
| Patrick H. Lauke | [@patrick_h_lauke](https://twitter.com/patrick_h_lauke) |
| Paul Adam | [@pauljadam](https://twitter.com/pauljadam) |
| Reinaldo Ferraz | [@reinaldoferraz](https://twitter.com/reinaldoferraz) |
| Rachel Carden | [@bamadesigner](https://twitter.com/bamadesigner) |
| Rachel R. Vasquez | [@RachelRVasquez](https://twitter.com/RachelRVasquez) |
| Rian Rietveld | [@RianRietveld](https://twitter.com/RianRietveld) |
| Rob Dodson | [@rob_dodson](https://twitter.com/rob_dodson) |
| Russ Weakley | [@russmaxdesign](https://twitter.com/russmaxdesign) |
| Sarah Horton | [@gradualclearing](https://twitter.com/gradualclearing) |
| Sarah Pulis | [@sarahtp](https://twitter.com/sarahtp) |
| Scott O'Hara | [@scottohara](https://twitter.com/scottohara) |
| Scott Vinkle | [@svinkle](https://twitter.com/svinkle) |
| Shawn Lauriat | [@slauriat](https://twitter.com/slauriat) |
| Shawn Lawton Henry | [@shawn_slh](https://twitter.com/shawn_slh) |
| Sina Bahram | [@SinaBahram](https://twitter.com/SinaBahram) |
| Sommer Panage | [@Sommer](https://twitter.com/Sommer) |
| Stefan Judis | [@stefanjudis](https://twitter.com/stefanjudis) |
| Steph Slattery | [@sublimemarch](https://twitter.com/sublimemarch) |
| Steve Faulkner | [@stevefaulkner](https://twitter.com/stevefaulkner) |
| Suz Hinton | [@noopkat](https://twitter.com/noopkat) |
| Svetlana Kouznetsova | [@svknyc](https://twitter.com/svknyc) |
| Ted Drake | [@ted_drake](https://twitter.com/ted_drake) |

## Other notes and incomplete thoughts

**[`^  back to top  ^`](#accessibility-resources)**

- Accessibility on Instagram - how does Instagram incorporate accessibility?
- The Roboto font - apparently this font is accessibility friendly, was it designed with this in mind?
- Other fonts that are dyslexia friendly
- [Person sues Coles for poor accessibility](https://www.business-humanrights.org/en/latest-news/australia-customer-sues-coles-supermarkets-over-alleged-disability-discrimination-re-accessibility-of-website/)
- [Helping blind people learn to code](https://www.freecodecamp.org/news/helping-blind-people-learn-to-code-c47c68d4a237/)
- Accessibility workshops?
- An accessibility-first website project would be a great portfolio piece (e.g. for someone looking for an internship)
