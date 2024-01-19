# vue2-json-editor-formatter

> 一个用vue2.0写的json编辑器，包含格式校验、错误提示和格式化功能。改写自[react-json-editor-ajrm](https://github.com/AndrewRedican/react-json-editor-ajrm#readme)

### Usage

``` bash
# install deps
npm install vue2-json-editor-formatter -S
```

##### html部分

```html
<json-editor v-model="jsonData"></json-editor>
```
##### js部分

```js
import JsonEditor from 'vue2-json-editor-formatter';
    export default {
        name: "JsonEditorDemo",
        components: {
            JsonEditor
        },
        data() {
            return {
                jsonData: [3,4]
            }
        }
    }
```

##### v-model双向数据绑定
v-model是一个json字符串。JsonEditor接受一个json字符串，并输出一个json字符串。

### Features
* 支持v-model双向绑定
* 支持只读模式viewOnly

## License

[MIT](http://opensource.org/licenses/MIT)



