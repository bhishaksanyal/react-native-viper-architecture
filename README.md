[![GitHub issues](https://img.shields.io/github/issues/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/network)
[![GitHub stars](https://img.shields.io/github/stars/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/bhishaksanyal/react-native-typescript-template)](https://github.com/bhishaksanyal/react-native-typescript-template/blob/main/LICENSE)
[![codecov](https://codecov.io/gh/bhishaksanyal/react-native-typescript-template/branch/main/graph/badge.svg?token=0SEFICI138)](https://codecov.io/gh/bhishaksanyal/react-native-typescript-template)

# React Native Typescript Starter Template

A react-native typescript starter template with inbuilt ready to use Eslint, Prettier, Jest and Typescript setup. Following are the list of setups which are already done for you to start working on a new project immediately.

### Getting Started
#
1. Clone and install
```
# Clone the repo
git clone https://github.com/bhishaksanyal/react-native-typescript-template.git

# Navigate to clonned folder and Install dependencies
cd react-native-typescript-template && yarn install

# Install Pods
cd ios && pod install
```

2. Rename the project
```
yarn rename <PROJECT_NAME>
```
3. Migrate to AndroidX to support [React Native 0.60](https://reactnative.dev/blog/2019/07/03/version-60#androidx-support)
```
yarn jetify
```
4. Remove .git
```
rm -rf .git
```
5. Run in iOS simulator
```
yarn ios
```
6. Run in Android simulator
```
yarn android
```


### Typescript (https://www.typescriptlang.org/)
#
TypeScript is a strongly typed programming language which builds on JavaScript giving you better tooling at any scale.

## What is TypeScript?
1. JavaScript and More

`
    TypeScript adds additional syntax to JavaScript to support a tighter integration with your editor. Catch errors early in your editor.
`

2. A Result You Can Trust

`
    TypeScript code converts to JavaScript which runs anywhere JavaScript runs: In a browser, on Node.js or Deno and in your apps.
`

3. Safety at Scale

`
    TypeScript understands JavaScript and uses type inference to give you great tooling without additional code.
`

Run the following command for typescript compilation check
```
yarn tsc
```
### Eslint

I have used ESlint instead of TSlint because - 

TSLint has been deprecated in favor of ESLint. Please see https://github.com/palantir/tslint/issues/4534 for more information.

Run the following command for lint check
```
yarn lint
```

### Prettier

Prettier for code formatting is already configured and if you are using VSCode as an editor then project is set to fix all indentation problems on "Save". 

You can also run the following command to fix prettier problems for the entire project manually 

```
yarn prettier:write
```

### Jest

Jest comes along with react-native but with very basic configuration. I have already setup this template such that test results can be seen right away with some amazingly helpful scripts.

```
#run this command to see file wise coverage (This will open an html page)

yarn coverage
```

```
#run this command to run tests in watch mode

yarn test:watch
```

```
#run this command for snapshot testing

yarn test:update
```

```
#running this command will run all tests for the entire project

yarn test
```


### Suggestions
#

### Code coverage check

Apart from these I have added [codecov](https://about.codecov.io/) plugin to check code coverage. It supports most languages so its highly recommended.

### Navigation

[React Navigation](https://reactnavigation.org/docs/typescript/) is the best choice till date for react-native app navigation.

### CI/CD

[AppCenter](https://appcenter.ms/) This microsoft product takes away all CI/CD problems. Uses fastlane internally and also free to upto certain features.

### Firebase

There are various options in firebase suit which can be used to solve multiple business problems. For instance - Crashlytics can be used for error and crash reporting, Performance for app performance monitoring, Distribution for adhoc distribution and much more.


Leave a star for motivation :)

HAPPY CODING !