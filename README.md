Projeto base de React: 

{
  "name": "react-landing-page",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
    "@testing-library/jest-dom": "^5.11.4",
    "@testing-library/react": "^11.1.0",
    "@testing-library/user-event": "^12.1.10",
    "react": "^17.0.2",
    "react-dom": "^17.0.2",
    "react-scripts": "4.0.3",
    "styled-components": "^5.2.3",
    "web-vitals": "^1.0.1"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "storybook": "start-storybook -p 6006 -s public",
    "build-storybook": "build-storybook -s public"
  },
  "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
    ],
    "overrides": [
      {
        "files": [
          "**/*.stories.*"
        ],
        "rules": {
          "import/no-anonymous-default-export": "off"
        }
      }
    ]
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "devDependencies": {
    "@storybook/addon-actions": "^6.2.9",
    "@storybook/addon-essentials": "^6.2.9",
    "@storybook/addon-links": "^6.2.9",
    "@storybook/node-logger": "^6.2.9",
    "@storybook/preset-create-react-app": "^3.1.7",
    "@storybook/react": "^6.2.9",
    "eslint-config-prettier": "^7.2.0",
    "eslint-plugin-prettier": "^3.3.1",
    "jest-styled-components": "^7.0.4",
    "prettier": "^2.2.1"
  }
}
