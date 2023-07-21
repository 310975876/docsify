## tinymce富文本编辑器（world文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| tinymce | [地址](https://github.com/tinymce/tinymce)  | 4.9.3 | MIT |

**1.添加tinymce静态文件至本地**

 [ruo-yi-vue-docHub / ruoyi-ui / public / Tinymce](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/public/Tinymce)

 **2.组件**
 
 [Tinymce](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/Tinymce)

 **3.使用**
 
```html
<Tinymce :height='400' v-model='form.content'></Tinymce>
```
```javaScript
import Tinymce from '@/components/Tinymce'
export default {
    components: {
        Tinymce,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## cherry-markdown编辑器（markdown文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| cherry-markdown | [地址](https://github.com/Tencent/cherry-markdown)  | 0.8.20 | Apache-2.0 |

**1.添加tinymce静态文件至本地**

[ruo-yi-vue-docHub / ruoyi-ui / public / CherryMarkdown](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/public/CherryMarkdown)

**2.组件**

[CherryMarkdown](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/CherryMarkdown)

**3.使用**
 
```html
<CherryMarkdown ref="CherryMarkdown" :height='400' v-model='form.contentMarkdown' ></CherryMarkdown>
```
```javaScript
import CherryMarkdown from '@/components/CherryMarkdown'
export default {
    components: {
        CherryMarkdown,
    },
    data() {
        return {
            form: {
                content: null,
                contentMarkdown: null,
            },
        }
    },
}
```

## bpmn流程图（流程图文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| bpmn-js | [地址](https://github.com/bpmn-io/bpmn-js)  | 7.3.1 | bpmn.io |
| bpmn-js-properties-panel | [地址](https://github.com/bpmn-io/bpmn-js-properties-panel)  | 0.37.2 | MIT |
| camunda-bpmn-moddle | [地址](https://github.com/camunda/camunda-bpmn-moddle)  | 4.5.0 | MIT |

**1.组件**

[Bpmn](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/Bpmn)

**2.使用**
 
```html
<Bpmn v-model='form.content'></Bpmn>
```
```javaScript
import Bpmn from '@/components/Bpmn'
export default {
    components: {
        Bpmn,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## tiny-whiteboard白板（画图文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| tiny-whiteboard | [地址](https://github.com/wanglin2/tiny_whiteboard)  | 0.1.12 | MIT |

**1.组件**

[TinyWhiteboard](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/TinyWhiteboard)

**2.使用**
 
```html
<TinyWhiteboard v-model='form.content'></TinyWhiteboard>
```
```javaScript
import TinyWhiteboard from '@/components/TinyWhiteboard'
export default {
    components: {
        TinyWhiteboard,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## simple-mind-map思维导图（思维导图文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| simple-mind-map | [地址](https://github.com/wanglin2/mind-map)  | 0.6.6 | MIT |
| @toast-ui/editor | [地址](https://github.com/nhn/tui.editor)  | 3.1.5 | MIT |
| v-viewer | [地址](https://github.com/mirari/v-viewer)  | 1.6.4 | MIT |
| xlsx | [地址](https://github.com/SheetJS/sheetjs)  | 0.18.5 | Apache-2.0 |
| vue-i18n | [地址](https://github.com/intlify/vue-i18n-next)  | 8.27.2 | MIT |

**1.组件**

[SimpleMindMap](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/SimpleMindMap)

**2.使用**
 
```html
<SimpleMindMap v-model='form.content'></SimpleMindMap>
```
```javaScript
import SimpleMindMap from '@/components/SimpleMindMap'
export default {
    components: {
        SimpleMindMap,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## luckysheet（excel文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| luckysheet | [地址](https://github.com/dream-num/Luckysheet)  | 2.1.13 | MIT |

**1.添加luckysheet静态文件至本地**

[ruoyi-ui/public/index.html](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/blob/master/ruoyi-ui/public/index.html)

**2.组件**

[Luckysheet](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/Luckysheet)

**3.使用**
 
```html
<Luckysheet v-model='form.content' :title="form.docsName"></Luckysheet>
```
```javaScript
import Luckysheet from '@/components/Luckysheet'
export default {
    components: {
        Luckysheet,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## vue-mark-display基于markdown的幻灯片（幻灯片文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| vue-mark-display | [地址](https://github.com/jinjiang/vue-mark-display)  | 0.2.2 | MIT |
| @toast-ui/editor | [地址](https://github.com/nhn/tui.editor)  | 3.1.5 | MIT |
| jshint | [地址](https://github.com/jshint/jshint)  | 2.13.6 | MIT |
| jsonlint | [地址](https://github.com/zaach/jsonlint)  | 1.6.3 | MIT |

**1.组件**

[TuiEditor](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/TuiEditor)

**2.使用**
 
```html
<TuiEditor v-model='form.content' :height="400"></TuiEditor>
```
```javaScript
import TuiEditor from '@/components/TuiEditor'
export default {
    components: {
        TuiEditor,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## monaco-editor文本编辑器（txt文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| monaco-editor | [地址](https://github.com/microsoft/monaco-editor)  | 0.20.0 | MIT |

**1.组件**

[MonacoEditor](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/MonacoEditor)

**2.使用**
 
```html
<MonacoEditor v-model='form.content' :options="{language: 'plaintext'}"></MonacoEditor>
```
```javaScript
import MonacoEditor from '@/components/MonacoEditor'
export default {
    components: {
        MonacoEditor,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## 代码编辑器（code文件）

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| vue-codemirror | [地址](https://github.com/surmon-china/vue-codemirror)  | 4.0.6 | MIT |
| script-loader | [地址](https://github.com/webpack-contrib/script-loader)  | 0.7.2 | MIT |

**1.组件**

[Codemirror](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/components/Codemirror)

**2.使用**
 
```html
<Codemirror v-model='form.content'></Codemirror>
```
```javaScript
import Codemirror from '@/components/Codemirror'
export default {
    components: {
        Codemirror,
    },
    data() {
        return {
            form: {
                content: null,
            },
        }
    },
}
```

## 地图搜索引擎

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| popmotion | [地址](https://github.com/popmotion/popmotion)  | 11.0.3 | MIT |
| konva | [地址](https://github.com/konvajs/konva)  | 8.3.2 | MIT |
| gcoord | [地址](https://github.com/hujiulong/gcoord)  | 0.3.2 | MIT |

**1.组件**

[map](https://gitee.com/Ning310975876/ruo-yi-vue-docHub/tree/master/ruoyi-ui/src/views/cms/map)


