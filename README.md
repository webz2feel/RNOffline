# RNOffline

A sample React Native app showing practical examples of how to make offline-friendly apps.

You can read the tutorial here:

-   [https://pusher.com/tutorials/offline-react-native-part-1](https://pusher.com/tutorials/offline-react-native-part-1)
-   [https://pusher.com/tutorials/offline-react-native-part-2](https://pusher.com/tutorials/offline-react-native-part-2)

### Prerequisites

-   React Native development environment or [Expo](https://expo.io/)
-   [Node.js](https://nodejs.org/en/)
-   [Yarn](https://yarnpkg.com/en/)

## Getting Started

1.  Clone the repo:

```
git clone https://github.com/anchetaWern/RNOffline.git
cd RNOffline
```

2.  Switch to your branch of choice:

-   `starter` - this is where you switch to if you're following part 1 of the series.
-   `redux-persist-sample` - contains the sample code for working with redux-persist.
-   `master` - contains the most recent version of the code.
-   `starter-chat` - contains the starter version of the chat app. This is the branch you switch to when following the second part of the series.
-   `offline-friendly-chat` - contains the final output for the whole series.

3.  Install the app dependencies:

```
yarn install
```

4.  Eject the project (re-creates the `ios` and `android` folders):

```
react-native eject
```

5.  Link the dependencies:

```
react-native link
```

6.  Run the app:

```
react-native run-android
```

## Built With

-   [React Native](http://facebook.github.io/react-native/)
