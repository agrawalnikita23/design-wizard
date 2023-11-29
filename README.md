# Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Project Structure

```sh
.
├── cypress                # End-to-end tests
├── docs                   # Documentation files (markdown format, github flavour)
├── src                    # Source files
│    ├── components       # Components that are shared between pages/views
│    │    ├── component1  # Each page in its own folder. Anything related with component
│    │    └── component2  # (css, styled-components, unit tests) should be in the same folder
│    ├── graphql           # Common graphql queries/mutations
│    ├── lib               # Shared functions, utilities
│    └── pages             # Pages in the app, each page in its own folder
│         ├── page1        # Each page in its own folder. Anything related with page
│         └── page2        # (css, styled-components, unit tests) should be in the same folder
│                            # (except shared components/functions)
├── public                  # Public files (e.g. favicon, meta images)
└── README.md               # This file
```

We should not be using Redux in this project unless it is absolutely necessary. [Apollo can be used for state management](https://www.apollographql.com/blog/apollo-client/caching/dispatch-this-using-apollo-client-3-as-a-state-management-solution/)

## Main Libraries/Components Used

[FabricJS](http://fabricjs.com/)\
[Apollo Client](https://www.apollographql.com/docs/react/)\
[Styled Components](https://styled-components.com/)\
[React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)\
[Cypress Testing Library](https://testing-library.com/docs/cypress-testing-library/intro)

## Commit Messages

[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) should be used in this project.\
If commit is related to a ticket in Jira, ticket number should be included in the commit message

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
You can run `npm test -- --coverage (note extra -- in the middle) to include a coverage report`\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back! Before ejecting, please consult with Client. Please don't eject unless it is absolutely necessary. There are ways to change webpack configuration without ejecting (rewire, react-app-rewired, CRACO, ...)**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

NOTE: To open JSON debugger in canvas, press Ctrl + Shift + L key.


