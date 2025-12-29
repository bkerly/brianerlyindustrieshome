# Brian Erly Industries

A minimalist and quirky landing page showcasing my projects.

## Overview

This is a simple, clean portfolio site that features clickable cards linking to my main projects:
- **Newspaperize** - A tool for creating newspaper-style layouts
- **AdventureLLM** - An LLM-powered adventure game

## Design

The site uses a minimal design approach with:
- Space Grotesk and Inter font pairing for a quirky yet professional look
- Hand-drawn PNG images for each project card
- Smooth hover animations
- Responsive layout that works on all screen sizes

## Setup

1. Clone this repository
2. Add your hand-drawn PNG images:
   - `newspaper.png` for the Newspaperize card
   - `adventurellm.png` for the AdventureLLM card
3. Open `index.html` in a browser

## Customization

To add or modify project cards, edit the `.cards-container` section in `index.html`. Each card follows this structure:

```html
<a href="YOUR_PROJECT_URL" class="card">
    <div class="card-content">
        <img src="your-image.png" alt="Project Name">
    </div>
    <div class="card-label">Project Name</div>
</a>
```

## License

© Brian Erly

## Links

- [Main Site](https://bkerly.github.io/)
- [Newspaperize](https://brianerly.shinyapps.io/newspaperize/)
- [AdventureLLM](https://brianerly.shinyapps.io/Escape_21/)
