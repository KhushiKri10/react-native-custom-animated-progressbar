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
import AnimatedProgressBar from 'react-native-custom-animated-progressbar';

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
## Screenshot
<img width="314" alt="image" src="https://github.com/KhushiKri10/react-native-custom-animated-progressbar/assets/53595245/6c2f1226-5366-4672-9571-824ce61f2f4b">

## Gif
![progress_bar_1](https://github.com/KhushiKri10/react-native-custom-animated-progressbar/assets/53595245/d5a90cd2-f79a-4e94-be9e-2424667c26f1)




## props

| name          | type            | default                     | description                                                               |
| ------------- | --------------- | --------------------------- | --------------------------------------------------------------------------|
| `size`      | number          | 4                        | progress bar height                                                      |
| `isRtl`       | boolean          | true                        | by this prop you can select progress bar style rtl or ltr                                                    |
| `bgColor`  | string         | '#c8e6c9'                       | progress bar background color                                     |
| `barColor`   | string | '#43a047'                        | progress bar color                                                      |
| `duration`     | number        | 500                        | animation duration in progress changing                                                         |
| `progress`      | number        | none                        | number between 0 - 1 |
| `barStyle`      | object or array        | none                        | if you want override progress bar style use this prop  |
| `rootStyle`      | object or array        | none                        | if you want override progress bar root style use this prop |
| `barWidth`      | number        | screen width                        | if you want change progress bar width use this prop |
