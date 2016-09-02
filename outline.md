Course Outline
===============

## What is accessibility?

* wikipedia definition for some lols/wtfs'
* break that down a bit more
* what is web/digital accessibility?
  * It's not just 'can a blind person use it'

### Interactive Activity

What things impair peoples use of the internet?

#### Answers to look for:

* sight
  * lack of (full and partial)
  * colour blindness
* motor skills
  * arthritis
  * temporary loss (broken bones, only able to use one hand)
  * RSI
* mental cognitivity
  * English not first language
  * not technology savy
* technology
  * slow/limited bandwidth
  * no laptop/PC (no access to a mouse or keyboard)

## Why Accessibility?

* It's the 'right' thing to do
  * "inclusive design"
  * an accessible website is one that more people can (and hopefully will) use
  * we're working hard on making stuff so surely it's good to have our hard work be used?!
* It's fun
  * puts you into the mind of the users of the site
  * makes you stop thinking quite so much as a developer
* Legal obligation
  * digitial accessibility now part of the UK Equality Act 2010
  * target web accessibility case - settled for $6m dollars
* Profit
  * By making a site accessible you increase it's audience to more people. More audience, more money

### Interactive Activity

How does it fit within our four I's?

* Integrity
  * admit that we can be better where we so far haven't been and push through to be that
* In-touch
  * our audience will all have some form of impediment, buy building something they're able to use we give them something they want 
* Inspire
  * retail websites are pretty average when it comes to accessibility - we can lead the way not only externally to our users but also internally to our teams
* Innovate
  * looking at what we have and what we will in the future build and making it accessibile is a massive innovation for M&S

## How accessibility?

### How do people with a disability use the internet?

Follow on from the examples above.

* browser/OS extensions
* custom stylesheets
* using the web without a mouse

Introduce the notion of AT (Assitive Technology)

* sits on-top of a browser and provides additional functionality

### Interactive Activity(ies)

#### How people with disabilities use the web 

* How a screen reader uses the web
  * semantic heading structures
  * anchor text makes sense on it's own
  * all content is availiable to hear
  * where you are on the site makes sense (focusing on content, page markers)
* How to use a website without a keyboard
  * ability to see visually where your cursor currently is
  * able to hit all required page landmarks
  * understandable HTML content structure
  * ability to interact with stuff (can't trigger rollovers for example)
* Site contrast - run the website through a low contrast display (or maybe colour blindness?)
  * 100% reliance on colours that may not be visible
  * easy to see inline errors when they occur?
* Using the website on the go - can you use it easily on a mobile device while holding something in one arm
  * are hit areas large enough to tap
  * are pages responsive enough to work on the devices they're used on
  * are things quick enough - does it look like things are working for someone who is likely a bit stressed out
  * many other things from the first couple of activities
* Viewing the site in a slow bandwidth environment - is it possible to do?
  * time to first usage
  * responders to input
  * downloading of assets
  * is it easy to read things (custom font lols)

## Doing accessibility

### How can I make the web accessible?

* use simple and native HTML where-ever possible
* stick to existing behaviour and usage standards
  * links all being the same colour
  * form elements acting like form elements
  * browser functionality
* CSS
  * :focus styles
  * accesible hiding techniques
* focusing on content (CSS and JS)
* wai-aria
  * but remember the first rule of aria is see if you can't just use HTML

### Testing accessibility

What is the best way to discover if a website is inaccessible or not?

* WCAG 2.0
  * Princibles on Web Accessibility that remain constant:
        * Perceivable
        * Operable
        * Understandable
        * Robust
  * explain the evolution of 2.0 from 1.0
* testing tools
  * tenon
  * browser extensions
  * OS screen readers
* web accessibility !== a tick box exercise
* user sessions with real users
* audits from accessibility experts

## Who accessibility?

* This is not just a problem for developers
* Tie back into the findings of the practical activities above:
  * if a design relies too much on colours and graphics then it's not an accessible design
  * if a website is only possible to be controlled via a mouse then it's not an accessible UX
  * if a website uses complex or ambigious words then it's not accessible copy
* It is therefore the responsibility of the entire team to fix this when problems are highlighted
