# React-Native-Action-Button
Button Floating in React Native
[react-native-action-button](https://github.com/mastermoo/react-native-action-button)

![buttonfloating](https://camo.githubusercontent.com/0d71fda546fc0aabd5b9e6fa0ea0934dace2c085/687474703a2f2f692e67697068792e636f6d2f3236426b4d69723949634168716534454d2e676966)

# Install
```
npm i react-native-action-button --save
```
and for react native <= version 60
```
react-native link react-native-vector-icons
```
and for react native >= version 59
```
react-native link
```
# Import
```
import ActionButton from 'react-native-action-button';
import Icon from 'react-native-vector-icons/Ionicons';
```
# Use 
```
<ActionButton buttonColor="rgba(231,76,60,1)">
          <ActionButton.Item buttonColor='#9b59b6' title="New Task" onPress={() => console.log("notes tapped!")}>
            <Icon name="md-create" style={styles.actionButtonIcon} />
          </ActionButton.Item>
          <ActionButton.Item buttonColor='#3498db' title="Notifications" onPress={() => {}}>
            <Icon name="md-notifications-off" style={styles.actionButtonIcon} />
          </ActionButton.Item>
          <ActionButton.Item buttonColor='#1abc9c' title="All Tasks" onPress={() => {}}>
            <Icon name="md-done-all" style={styles.actionButtonIcon} />
          </ActionButton.Item>
        </ActionButton>
```

```
const styles = StyleSheet.create({
  actionButtonIcon: {
    fontSize: 20,
    height: 22,
    color: 'white',
  },
});
```
