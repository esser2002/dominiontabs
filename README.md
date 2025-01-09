This fork allows for generation of Sumpfork-style tabs for storing cards for the X-Wing miniatures game.

The icons used are taken from the X-wing icons font, found here https://github.com/geordanr/xwing-miniatures-font

The X-Wing cards are wider than Dominion cardss, so getting the cards to fit inside a dominion game box, but still have the tabs visible, was a bit challenging.
We ended up not cutting precisely after the lines.

Generating the cards with this command should be a good baseline, and they fit well if a milimetre is cut from the top. If you are looking to make these yourself, I would recommend doing a test-print to see what fits.

`dominion_dividers --expansion x-wing --papersize A4 --size 8.82x6.15`

Alternatively, see the _x-wing_dividers.pdf_ file for cards generated with the settings above.
