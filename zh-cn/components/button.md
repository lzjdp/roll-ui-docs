<!--
 * @Author: your name
 * @Date: 2021-09-24 09:15:59
 * @LastEditTime: 2021-09-24 13:36:45
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /docs/zh-cn/components/button.md
-->
<font size=5 face="黑体">**Button 按钮**</font>

<font size=3 face="黑体">**按钮类型**</font>
```
import React from 'react' 
import { Button } from 'roll-ui'

class ButtonType extends React.Component {
    render () {
        return (
            <>
                <Button type="link"></Button>
            </>
        )
    }
}
```

<font size=3 face="黑体">**按钮大小**</font>
```
import React from 'react' 
import { Button } from 'roll-ui'

class ButtonSize exntends React.Component {
    render () {
        return (
            <>
                <Button size="large">Large</Button>
                <Button size="default">Default</Button>
                <Button size="small">Small</Button>
            </>
        )
    }
} 
```

<font size=3 face="黑体">**禁用**</font>
```
import React from 'react' 
import { Button } from 'roll-ui'

class ButtonSize exntends React.Component {
    render () {
        return (
            <>
                <Button type="primary" disabled>禁止使用</Button>
                <Button type="primary">正常使用</Button>
            </>
        )
    }
} 
```

<font size=5 face="黑体">**API**</font>

属性|说明|类型|默认值
:-:|:-:|:-:|:-:
type|按钮类型|<font color="red">primary &#124; default &#124; link</font>|default
size|按钮大小|<font color="red">large default small</font>|default
disabled|是否禁用|<font color="red">boolean</font>|false
onClick|点击按钮时的回调|<font color="red">event => void</font>|-