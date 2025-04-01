# tricky-button
Overview
This HTML/CSS/JavaScript code creates an animated button that cycles through different visual effects each time it's clicked. The button is perfectly centered on the page and features a ripple effect that originates from the click location.

#Structure Breakdown
HTML Structure:

Standard HTML5 document structure with <!DOCTYPE html>

Contains a single <button> element with ID animatedButton

#CSS Styling:

Body Styles: Uses flexbox to center content both horizontally and vertically (justify-content: center, align-items: center) with full viewport height (height: 100vh)

Button Base Style (cycle-button class):

Gradient background (pink to dark pink)

Rounded corners (border-radius: 50px)

White text with bold font

Shadow effect

Hidden overflow (for ripple effect)

Animation Classes (5 different effects):

pulse-effect: Button scales up slightly

color-rotate-effect: Cycles through color hues

bounce-effect: Button moves upward

shake-effect: Button wiggles side-to-side

flip-effect: 3D flip animation

Ripple Effect:

Circular wave that expands from click point

Uses absolute positioning and scale animation

#JavaScript Functionality:

Cycles through 5 different animation effects on each click

Creates a ripple effect at the click location

Maintains state of current effect using currentEffect counter

Cleans up animations after they complete

#The createRipple() function:

Dynamically creates a ripple element

Positions it at the click coordinates

Animates it to expand and fade out

Removes it after animation completes

#Key Features
Responsive Centering: Button stays centered regardless of screen size

Visual Feedback: Provides clear interactive feedback through animations

Variety: Cycles through 5 distinct animations

Polished Details: Includes smooth transitions, shadow effects, and the ripple effect

Self-cleaning: Removes animation classes after they complete

#Technical Highlights
Uses CSS Flexbox for perfect centering

Leverages CSS animations for smooth effects

Employs JavaScript classList API for animation management

Dynamically creates and destroys ripple elements

Uses modulo operator (%) for cycling through effects

This implementation provides an engaging, interactive button with professional visual effects that would work well in modern web applications.
