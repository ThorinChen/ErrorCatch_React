# ErrorCatch_React
 Solution to the whole page crash caused by the exception of React sub component

## doc

[react-catchable](https://github.com/ThorinChen/Slider_Component_React/blob/main/src/Vertify/index.md)

## install

use npm
```shell
npm i react-catchable
```
use yarn
```shell
yarn add react-catchable
```
## setup

```jsx
import catchable from "react-catchable";
class XXXComponent extends React.Component{
    render(){
        return <div></div>
    }
}

export default catchable(XXXComponent);
```

#### Example
 **Demo source：[click](https://github.com/ThorinChen/Slider_Component_React/blob/main/src/Vertify/index.md)**
