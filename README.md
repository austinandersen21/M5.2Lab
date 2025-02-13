# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

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
I tested the background/foreground color contrast using a contrast checker at https://webaim.org/resources/contrastchecker/. The contrast ratio for green and black was 4.08:1, which failed most tests aside from one of the larger-text tests, and the graphical interface test. However for general text, it failed. As a result, I chose to simply go with the color white.
A white background and black text had a 21:1 contrast ratio, which passed all the tests.

Using the keyboard to explore the website did not function as expected. You could use the arrows to scroll the page, and tab to explore the different elements, some of the buttons weren't reachable via the tab button such as the "comments" button at the bottom of the page. 

Two additional ideas for improvement on this webpage would be to add the aria-live tag to comments so as new comments pop up, they are read out loud to the user. I also think that having alert messages that read aloud any errors would also be useful, in case submitting a comment couldn't be done, or searching something doesn't yield any results.