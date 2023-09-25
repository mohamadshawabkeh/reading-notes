
# React Native 

## getting started with react native

#### Name three Core Components of React Native and describe what they do.
- **Text**: The `Text` component is used for displaying text on the screen. It supports styling, such as fonts and text color.
- **View**: The `View` component is a fundamental building block for creating the user interface. It's like a container that can hold other components.
- **Image**: The `Image` component is used for displaying images in the app. It can load images from various sources and handle resizing.

#### What problem does React Native solve (why call it native)?
React Native allows developers to build mobile applications using JavaScript and React, while still providing a native-like user experience. It achieves this by translating the JavaScript code into native code, enabling the app to perform efficiently and smoothly.

#### What are the building blocks of a React Native app? How does that compare to a React app?
The building blocks of a React Native app include Core Components (such as `Text`, `View`, `Image`), Navigation, State Management, and Native Modules. These are similar to building blocks in a React app, but in React Native, they are designed to work with mobile-specific features and are compiled to native code, unlike a React app that runs in the browser.

## Expo

#### What solution does Expo provide?
Expo provides a set of tools and libraries that simplify the development of React Native apps. It offers features like a development server, over-the-air updates, and access to native modules without the need for native code.

#### Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
Expo is often referred to as the "Managed" workflow because it abstracts away many of the complex tasks involved in mobile app development, making it easier for developers to focus on building features.

#### What is the difference between React Native and Expo?
React Native is a framework for building mobile apps using JavaScript and React, while Expo is a set of tools and services that simplify the development of React Native apps. Expo provides a higher-level abstraction, but it may have some limitations compared to a custom React Native setup.

## Expo Snack

#### Checkout this tool. What does snack allow you to do?
Expo Snack is an online development environment that allows you to write and preview React Native code directly in your web browser. It's a great way to quickly prototype, test, and share React Native projects without needing to set up a development environment.

## Ejecting

#### What does “eject” mean within the context of Expo?
"Ejecting" in the context of Expo means transitioning your Expo project to a standard React Native project. This allows you to have more control over the native code and dependencies, which may be necessary for advanced customization.

#### When should you not eject?
You should avoid ejecting if you prefer the simplicity and convenience of the Expo Managed workflow, and your app's requirements can be met without extensive custom native code modifications.

#### Why might you choose to eject?
You might choose to eject when you need more flexibility and control over your project's native code, or when you want to integrate specific native modules that are not supported in the Expo Managed workflow. Ejecting also allows for more advanced configuration and optimizations.

### return to [Main Read Me File](./README.md)