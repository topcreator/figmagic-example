# Figmagic Example

The Figmagic template design system is available at [https://www.figma.com/file/b1ZabSdSz2z9mFctBOVIOy](https://www.figma.com/file/b1ZabSdSz2z9mFctBOVIOy). That's the file providing the tokens seen here.

## Installation

- Run `yarn` or `npm install` inside of the repository to install all dependencies
- Start the project by running `yarn start` or `npm start`
- To sync graphics, run `yarn figmagic:graphics` or `npm run figmagic:graphics`
- To sync elements, run `yarn figmagic:elements` or `npm run figmagic:elements`
- To sync all of it, run `yarn figmagic:sync` or `npm run figmagic:sync`
- Start Storybook with `yarn storybook` or `npm run storybook`

## Using Figmagic for your own files

- You will need to have a Figma file set up correctly (see above demo file)
- You will also need to have a Figma API key
- Set your URL and token in a file called `.env` in the root of your project (such as in this one, if you want to get started right away)
- Run the command `figmagic` in your project directory

Read more on the [Figma developer site](https://www.figma.com/developers/docs) if you need any further information.
