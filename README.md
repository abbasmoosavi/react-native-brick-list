
# react-native-brick-list

## Getting started

`$ npm install react-native-brick-list --save`
Or
`$ yarn add react-native-brick-list`

## Usage

```javascript
import BrickList from 'react-native-brick-list';

<BrickList
    data={this.props.data}
    renderItem={(item) => (
        <View key={item.id} style={{ margin: wp('0.2%'), flex: 1, backgroundColor: Color.BACKGROUND_CARD, padding: wp('0.2%') }}>
            <FastImage resizeMode={FastImage.resizeMode.cover} style={{ height: '100%', width: '100%', resizeMode: 'cover' }} source={{ uri: item.url }} />
        </View>
    )}
    columns={3}
/>

  