
<p align="center">
  <img width="60" src="https://gitee.com/hz8866/json-schema-editor-vue/raw/master/examples/assets/logo.png">
</p>
<h1 align="center">
  <a href="http://json-schema.sviip.com/" target="_blank">json-schema-editor-vue</a>
</h1>
<p align="center">A json-schema editor of high efficient and easy-to-use, base on Vue</p>
<p align="center">
  <img width="100%" src="https://gitee.com/hz8866/json-schema-editor-vue/raw/master/examples/assets/capture.png">
</p>


### Example
**Demo** [http://json-schema.sviip.com](http://json-schema.sviip.com) 

**[国内Demo](http://json-schema-editor.sviip.com)**
### Usage

```bash
npm install json-schema-editor-vue
```

```vue
import JsonSchemaEditor from '../packages/index'
Vue.use(JsonSchemaEditor)
```

```vue
<template>
  <div id="app">
    ...
    <json-schema-editor :value="tree"/>
    ...
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      tree:
      {
        root: {
          type: "object"
        }
      }
    }
  }
}
</script>
```

Don't forget to star if it helped!

如果对您有帮助，别忘记给个星哦

### Links

- [json-schema-editor-visual](https://github.com/YMFE/json-schema-editor-visual)