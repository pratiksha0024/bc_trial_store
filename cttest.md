# bc_trial_store

# Store URL
https://ustar.mybigcommerce.com 

#Preview Code
 pqi7bkh2jl
 
# Approach 
I implemented product color swatches on the category page using the Stencil util API. The product attributes were fetched dynamically and rendered as clickable swatches.

# Template Files Modified
templates/components/products/card.html
assets/js/theme/global/card-swatches.js
assets/js/theme/global/index.js
assets/scss/components/_cards.scss

# What each file does 
card.html → Added HTML for displaying color swatches on product cards in category pages.
card-swatches.js → Handles swatch rendering logic and interaction.
index.js → Imports and initializes the swatch functionality globally.
_cards.scss → Adds styling for the swatch UI on product cards.
