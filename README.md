# rn-visible-view
一个React Native的控制空间的显示与消失的控件

## Example

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



## 安装
`npm install rn-visible-view --save`

