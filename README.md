# rn-visible-view
一个React Native的控制空间的显示与消失的控件

## Example & Useage

### 可见

```javascript
export default class demo extends Component {
  render() {
    return (
      <View style={styles.container}>
        <Text style={styles.welcome}>
          Welcome to React Native!
        </Text>

        <VisibleView visible={true}>
          <Text style={styles.instructions}>
            To get started, edit index.ios.js
          </Text>
          <Text style={styles.instructions}>
            Press Cmd+R to reload,{'\n'}
            Cmd+D or shake for dev menu
          </Text>
        </VisibleView>
      </View>
    );
  }
}
```

![可见](https://github.com/React-IO/rn-visible-view/blob/master/screenshot/v.png?raw=true)

### 不可见
```javascript
export default class demo extends Component {
  render() {
    return (
      <View style={styles.container}>
        <Text style={styles.welcome}>
          Welcome to React Native!
        </Text>

        <VisibleView visible={false}>
          <Text style={styles.instructions}>
            To get started, edit index.ios.js
          </Text>
          <Text style={styles.instructions}>
            Press Cmd+R to reload,{'\n'}
            Cmd+D or shake for dev menu
          </Text>
        </VisibleView>
      </View>
    );
  }
}
```

![不可见](https://github.com/React-IO/rn-visible-view/blob/master/screenshot/n.png?raw=true)




## 安装
`npm install rn-visible-view --save`

