# wildlife

Making website for accessible. To start it up head over to index.html and start a live server.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```
## Accessibility Lab Answers
Color: the color scheme wasn't the best. The contrast ratio between the text and background is insufficient for accessibility compliance. I changed it.
Semantic HTML: I was able to navigate quite well with tab and my arrow keys, but the menus and links weren't highlighted well. Article lacks proper semantic structure so I fixed it. The navigation menu is now wrapped with nav
Images: added descriptive alt text.
Audio Player: added alternative for users and used audio tag with a fallback message for older browsers that don't support html audio
Forms: By adding a visually hidden label. Use for attribute to explicitly associate labels with inputs.
Show/Hide Comment Control: Made it focusable using tabindex="0". 
Table: added th for headers, and caption tag for table summary
