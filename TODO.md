# TODO - Add Entry Animations Using GSAP ScrollTrigger

## Objective
Add or enhance entry animations on page sections using GSAP ScrollTrigger, without using AOS library.

## Background
- The project already uses GSAP and ScrollTrigger plugin
- Existing animations target many sections and elements with fade, translate and delay effects
- We will use consistent styles and add animations for any missing or less animated sections

## Plan
- Modify index.html:
  - Locate the existing GSAP animation script block
  - Add ScrollTrigger animations for any main section or elements missing animations
  - Examples:
    - Use gsap.from() with opacity 0 and y or x translations (e.g. y: 50)
    - Trigger animations when elements come into viewport (start: 'top 80%')
    - Use stagger or delay between child elements for smooth effect
  - Ensure animations are smooth, performant and non-intrusive.

## Next Steps
- Edit index.html, add GSAP entry animations to designated sections
- Test animations on scroll in a browser to verify smooth entry effects
- Adjust duration, delay and easing as necessary
