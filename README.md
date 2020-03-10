# Accessibilty

## What is it?

#### Accessibility at its core?

Making sure that all users have equal access to the information and functionality of your site.

The users that we're mainly referring to when we discuss a11y (just an abbrevation) are those with physical impairments. It can also refer to users on mobile devices or people using slow internet connections.

Accessible sites are designed designed and developed so that people with disabilities can use them

#### How many people are disabled in the world?

- Numbers are variable, but it's about 1.15 billion people according to WHO.
- vision alone - roughly 300 million

They have different ways that they perceive, understand, navigate, and interact with the Web.

How do people with disabilities navigate the web differently?

Keyboard only (reduced dexterity)

Screen readers (vision)

Captions for videos (hearing impaired)

## Why should you care?

- access to the web is a human basic human right
- improve peoples lives
- bottom lines (more users, great optics)
- legal implications (ADA)

## Writing Accessible Code

Lots of guides published in the 90s

Brought together in the Unified Web Site Accessibility Guidelines compiled at the University of Wisconsin–Madison

W3C (World Wide Web Consortium)

Version 8 becomes WCAG 1.0

WCAG 2.1

4 Principles

### Percievable

#### people can see or hear the content

    meaningful alt text (helps seo)
    making sure form elements are labeled (labels can be hidden, screen readers willgrasp at straws for text to read)
    good contrast
    removing titles from links

## Operable

####

    Page navigation and liks work using Only a keyborad
    Seizures are bad. <3 a second
    Obvious link text

#### Understandable

    keep nav in same order
    clearly identify form errors

#### Robust

    no errors
    usable in multiple formats

#### good layouts

Don't be Ling's Cars...

https://www.lingscars.com/

#### html easiest most important

    headings - (defined hierarchy)

    css
    focus colors (people love removing this!)
    js
    skip links (github) (webAim)

## Conducting a Manual Accessibility Check

- Tab through your site's experience.
  are there off screen elements that are in the tab order?
  - menu hidden on certain width, etc.
  - remove / disable offscrren content from the tab order
  - run through it with a screen reader
  - run through the contrast of the site

## Automating Accessibility Checks

Tools to check how accessible your pages are:
WAVE - been around 20 years
Lighthouse -

W3C - WCAG
perceivable -
operable - use by typing or by voice
understandable - clear and simple language
Robust - people can use different assistive technologies
ATAG - CMS / code editors, etc
UAAG - web browsers / media players

# Resources

- https://www.w3.org/WAI/WCAG21/quickref/

- aXe

- https://developers.google.com/web/fundamentals/accessibility/how-to-review?utm_source=lighthouse&utm_medium=devtools
