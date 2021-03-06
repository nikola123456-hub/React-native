
React Native enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript and [React](http://facebook.github.io/react). The focus of React Native is on developer efficiency across all the platforms you care about - learn once, write anywhere. Facebook uses React Native in multiple production apps and will continue investing in React Native.

Supported operating systems are >= Android 4.1 (API 16) and >= iOS 7.0.

- [Getting Started](#getting-started)
- [Getting Help](#getting-help)
- [Documentation](#documentation)
- [Examples](#examples)
- [Extending React Native](#extending-react-native)
- [Upgrading](#upgrading)
- [Opening Issues](#opening-issues)
- [Contributing](#contributing)
- [License](#license)

## Introduction

See the official [React Native website](https://facebook.github.io/react-native/) for an introduction to React Native.

## Getting Started

- Follow the [Getting Started guide](http://facebook.github.io/react-native/docs/getting-started.html) to install React Native and its dependencies.
- [Open the UIExplorer example project](#examples) to see a list of components that ship with React Native.
- Install the React Developer Tools for [Chrome](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/react-devtools/) for better debugging [(read more)](http://facebook.github.io/react-native/docs/debugging.html).
- Try out apps from the [Showcase](https://facebook.github.io/react-native/showcase.html) to see what React Native is capable of!

## Getting Help

Please use these community resources for getting help. We use the GitHub issues for tracking bugs and feature requests and have limited bandwidth to address them.

- Ask a question on [StackOverflow](http://stackoverflow.com/) and tag it with `react-native`
- Articulate your feature request or upvote existing ones on [Product Pains](https://productpains.com/product/react-native/)
- Start a thread on the [React Discussion Board](https://discuss.reactjs.org/)
- Join #reactnative on IRC: chat.freenode.net
- If it turns out that you may have found a bug, please [open an issue](#opening-issues)

## Documentation

- Finally, React Native provides a small number of **Polyfills** that offer web-like APIs.

Another great way to learn more about the components and APIs included with React Native is to read their source. Look under the `Libraries` directory for components like `ScrollView` and `Navigator`, for example. The UIExplorer example is also here to demonstrate some of the ways to use these components. From the source you can get an accurate understanding of each component’s behavior and API.

The React Native documentation only discusses the components, APIs and topics specific to React Native (React on iOS and Android). For further documentation on the React API that is shared between React Native and React DOM, refer to the [React documentation](http://facebook.github.io/react/).

## Examples

- `git clone https://github.com/facebook/react-native.git`
- `cd react-native && npm install`

### Running the examples on iOS

Now open any example (the `.xcodeproj` file in each of the `Examples` subdirectories) and hit Run in Xcode.

### Running the examples on Android


```bash
./gradlew :Examples:Movies:android:app:installDebug
# Start the packager in a separate shell (make sure you ran npm install):
./packager/packager.sh
# Open the Movies app in your emulator
```

## Extending React Native

- Looking for a component? [react.parts](http://react.parts/)
- Fellow developers write and publish React Native modules to npm and open source them on GitHub.
- Making modules helps grow the React Native ecosystem and community. We recommend writing modules for your use cases and sharing them on npm.

## Upgrading


## Opening Issues


The GitHub issues are intended for bug reports and feature requests. For help and questions with using React Native please make use of the resources listed in the [Getting Help](#getting-help) section. [Product Pains](https://productpains.com/product/react-native/) in particular is a good way to signal your interest in a feature or issue. There are limited resources available for handling issues and by keeping the list of open issues lean we can respond in a timely manner.

## Contributing



## License

React is [BSD licensed](./LICENSE). We also provide an additional [patent grant](./PATENTS).

React documentation is [Creative Commons licensed](./LICENSE-docs).

Examples provided in this repository and in the documentation are [separately licensed](./LICENSE-examples), as are some of the [custom components](./LICENSE-CustomComponents).
