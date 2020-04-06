# design-system-storybook-workflow

Example of storybook and Figma working together to keep consistent components with design system.

Figma link --> [PLEASE FILL ME]

## What do we want to do?

Present a component library in Storybook and the integration with a prototype in Figma.

## Integration ideas

### Sync stories with Design name

Check for all the pages inside Figma, inside each page there is several frames.

Figma:

- **Pages**
  - **Frames**
    - Symbols

Storybook:

- **Story**
  - **Variation**
    - Component

1. Check how many stories don't have a design linked.
2. Add new stories with the name of new pages and frames.

### Sync stories with Screenshots

Add the figma frame to the story (screenshot).

### Visual test

Automatic test that check the diffing between the rendered component and the screenshot.

## License

Mit.
