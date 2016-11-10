footer: Jeff Juszczak, Vector Solutions, 2016
slidenumbers: true
![](/Users/jjuszczak/Desktop/react-logo-1000-transparent.png)
# React Native
**LEARN ONCE, WRITE ANYWHERE:
BUILD MOBILE APPS WITH REACT**

---

![right](/Users/jjuszczak/Desktop/react-logo-1000-transparent.png)

## What is React Native?

- Native mobile application development
  - iOS (App Store deployable)
  - Android (Google Play Store deployable)
  - Not quite bare metal, but compiles to native code
- Everything is JavaScript (ES6)
- Something that kind of looks like CSS[^1])

[^1]: If you love camelCase instead of kebab-case.

---

## Frequently Asked Questions

1. Is this really just a webview?
  - No.
1. Do I have to live in Xcode/Android Studio?
  - No, only to create deployable versions of the app.
1. Is this just a box of magic?
  - Yes and No.

---

## Getting Started

- MacOS (iOS and Android) or Windows (Android only)
- Xcode and/or Android Studio

MacOS with Xcode:

```bash
brew install node
brew install watchman
npm install -g react-native-cli

react-native init AwesomeProject
cd AwesomeProject
react-native run-ios
```

---

## Make it happen

![inline](/Users/jjuszczak/Desktop/2____dev_react-native__bash_.png)

---

## What's in the box?

Hey, we all (_mostly_) understand JavaScript
<br>

```objectivec
!["React" isEqualToString:@"Objective-C"]
```

```java
!"React".equals("Java")
```
<br>

```javascript
"React" === "JavaScript";
```

---

## What's in the box?

#### Tiny Library & API

  - 34 Component Types (like `<Text>`, `<Button>`, and `<Image>`)
  - 38 API methods (like `Alert`, `Clipboard`, and `Geolocation`)

---

## What's in the box?

#### Interwebs
- Designed from the ground up for pulling data from APIs
- Gracefully deal with asynchronous request/response cycle

<br>

```jsx
axios.get('https://rallycoding.herokuapp.com/api/music_albums')
      .then(response => this.setState({ albums: response.data }));
```

---

## What's in the box?

#### Flexbox

![inline](/Users/jjuszczak/Desktop/TXH5p.png)

---

## What's in the box?

#### Redux

...because Redux

![inline](/Users/jjuszczak/Desktop/redux_logo.png)

---

## Advantages?

<br>
### React Native vs. Native Native
  - "It's hard"
  - Good luck building two (iOS, Android) versions of everything
  - Just getting the boiler plate up is a PITA

---

## Advantages?

<br>
### React Native vs. Xamarin
  - C#
  - Steep learning curve
  - VisualStudio (yeah, I know)

---

## Advantages?

<br>
### React Native vs. Cordova (PhoneGap)
  - Not native (WebView all the things)
  - Not very performant (because of above)
  - No background processing

---

## Advantages?

<br>
### React Native vs. Ruby Motion
  - Proprietary (not open source)
  - Mostly just syntax wrappers, you still need to know what's going on under the hood
  - Not a yuge community; might be hard to get help

---

## Disadvantages?

  - Complex stuff is still hard, especially if there is no native React Native component[^2]
  - API is pretty stable, but new enough that something may break the ecosystem
  - Compiler is pretty black box; if something doesn't work, good luck finding out why

[^2]: You can still write native modules in Xcode or Android Studio if React Native can't do what you want. I wouldn't try writing any OpenGL games in React.

---

## Taylor [not] Swift

![inline](/Users/jjuszczak/Desktop/Glass_and_iPhone_6_–_iOS_10_2__14C5062c_.png)

---
![left](/Users/jjuszczak/Desktop/react-logo-1000-transparent.png)
## More please...

Where can I get more of this sweet, sweet React Native?

- [React Native website](https://facebook.github.io/react-native): Obviously
- [JS.coach](https://js.coach/react-native): Kind of like Ruby Toolbox for React and React Native components
- [The Complete React Native and Redux Course (from Udemy)](https://www.udemy.com/the-complete-react-native-and-redux-course/): Very good (if a bit overly detailed) course

---

# Thanks!
![fit](/Users/jjuszczak/Desktop/giphy.gif)
