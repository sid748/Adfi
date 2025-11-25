# TODO - Hamburger and Menu Drawer Animation Enhancements

## Status
- [x] Plan approved by user.
- Current progress: Starting CSS edits.

## Detailed Steps (Updated)

### 1. Edit index.html [x DONE]
- [x] data-animation="over-right" already set on .navbar.w-nav.
- [x] Hamburger already CSS spans (.hamburger-icon > 3x .bar).

### 2. Edit CSS (AdFi - Performance Driven Marketing Financing_files/adfi-1ba2df.webflow.shared.bc6467f00.css) [ ]
- [ ] Add base .hamburger-icon & .bar styles (position, size, transition).
- [ ] Add .menu-button.w--open transforms: bars to cross (rotate45, opacity0, rotate-45).
- [ ] Enhance .nav-menu-2.w--open: smooth right slide if needed (Webflow base).
- [ ] Add .nav-menu-2.w--open .nav-menu-list-item: staggered slideInLeft anim (@keyframes translateX(-30px) scale + opacity, nth-child delay 0.1s).
- [ ] @media (max-width: 991px) scope.

### 3. Edit JS [x NOT NEEDED]
- [x] Existing jQuery toggle .w--open perfect, closes on links.

### 4. Testing [ ]
- [ ] Launch browser, mobile view, toggle hamburger: check cross anim.
- [ ] Check menu slides right.
- [ ] Check items slide left fancy/stagger.
- [ ] Close on link click.
- [ ] Tune if issues.

### Next
- Update this TODO after each step.
