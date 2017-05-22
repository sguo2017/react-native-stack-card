# react-native-stack-card
infinite card style carousel for react-native project 
<br>Demo
------
<br>![](https://github.com/yjy5264/react-native-card-carousel/raw/master/image/card.gif)
<br>Install
------
```javascript
npm install react-native-stack-card --save
```
<br>Usage
------
```javascript
<StackCard
    data = {itemArr}
    onPress = {item => {}}
    contentRender = {item => {
        return <CustomView item = {item} />;
    }} 
/>
```
