# React Native simple Custom Animated Progress Bar

This is a simple animated progressbar component.


## Installation

 Supported version: react-native >= 0.59.0

  ```bash
  npm install react-native-custom-animated-progressbar
  ```
  
  or
  
  ```bash
  yarn add react-native-custom-animated-progressbar
  ```


  ## Example
```jsx
import CircularProgress from 'react-native-circular-progress-indicator';

....

 <AnimatedProgressBar progress={progress} />
        <AnimatedProgressBar
          size={20}
          progress={progress}
          rootStyle={{
            marginTop: 35,
          }}
        />
        <AnimatedProgressBar
          size={20}
          isRtl={false}
          progress={progress}
          rootStyle={{
            marginTop: 35,
          }}
        />
        ```

        ![](/image.png)
