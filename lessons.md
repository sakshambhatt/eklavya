# These are the things that I discovered in CSS while making the component library

## Overflow:
Works only on block elements which have height defined
## Perfectly round border radius:
eqauls dimensions (width = height), border-radius: 50%
## For text overlay and card with dismiss
[W3Schools overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp)
## When I click on buttons/ input tags, an outline appears which is not removed if I set :active/ :focus border: none;
1. [outline, a CSS property](https://stackoverflow.com/questions/1158515/difference-between-outline-and-border)
2. `outline: none` should not be used as it makes the element inaccessible by keyboard
## Did you know?
borders have sides. In my input field, I use `border: none` and `border-bottom: 2px solid var(--dark);
## floating buttons:
1. position sticky needs an offset relative to which it can stick. top, bottom, left or right.
2. Apart from that, its parent should have **height and overflow defined**.
## cursor pointer not working:
1. [stackoverflow answer](https://stackoverflow.com/questions/18434626/why-is-cursorpointer-effect-in-css-not-working/44510398)
2. The above solution did not help me
# All of the above are either my observations or answers found online. If you think one of these is incomplete/ incorrect, feel free to rectify me in a pull request.
