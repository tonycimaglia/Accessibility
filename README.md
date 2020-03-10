# Accessibilty

## What is Accessibility

#### What is it at its core?

Making sure that all users have equal access to the information and functionality of your site.

The users that we're mainly referring to when we discuss a11y (just an abbrevation) are those with physical impairments. It can also refer to users on mobile devices or people using slow internet connections.

Accessible sites are designed designed and developed so that people with disabilities can use them

perceive, understand, navigate, and interact with the Web

how many people are disabled in the world

- Numbers are variable, but it's about 1.15 billion people according to WHO. 
  vision alone
  physical impairments

How do they navigate the web differently?
reduced dexterity
mouthsticks
screen readers
captions for videos
What are the concerns to consider

## Why should you care?

- access to the web is a human basic human right
- improve peoples lives
- bottom lines (more users, great optics)
- legal implications (ADA)

## Writing Accessible Code

#### good layouts

Don't be Ling's Cars...

https://www.lingscars.com/

#### html easiest most important

    headings - (defined hierarchy)
    labels for inputs - (screen readers willgrasp at straws for text to read)
    alternate tags - does it affect the way the page works without it?
      -reads description / also helps search engines

    css
    color contrast
    focus colors (people love removing this!)
    js
    skip links (github) (webAim)

## Conducting a Manual Accessibility Check

- tab through your site's experience
  are there off screen elements that are in the tab order?
  - menu hidden on certain width, etc.
  - remove / disable offscrren content from the tab order
    run through it with a screen reader
    run throught the contrast of the site

## Automating Accessibility Checks

Tools to check how accessible your pages are:
WAVE - been around 20 years
Lighthouse -

W3C - WCAG
perceivable - people can see or hear the content
operable - use by typing or by voice
understandable - clear and simple language
Robust - people can use different assistive technologies
ATAG - CMS / code editors, etc
UAAG - web browsers / media players

# Resources

- https://www.w3.org/WAI/WCAG21/quickref/

- aXe

- https://developers.google.com/web/fundamentals/accessibility/how-to-review?utm_source=lighthouse&utm_medium=devtools
