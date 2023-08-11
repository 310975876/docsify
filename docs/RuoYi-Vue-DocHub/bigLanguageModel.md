## ChatGPT

| 组件 | 源码 | 版本 | license |
| ------ | ------ | ------ | ------ |
| openai | [地址](https://github.com/openai/openai-node)  | 3.2.1 | MIT |
| markdown-it-vue | [地址](https://github.com/ravenq/markdown-it-vue)  | 1.1.7 | MIT |


设置`OpenAI-Key`：修改`.env.development`和`.env.production`文件中 `VUE_APP_OPENAI_API_KEY="你的openai api key"`
>警告
>
>使用 `OpenAI-Key` 时，如果网络不通，那是`被墙了`，你需要自建代理，绝对不要使用别人的公开代理，那是危险的。

### 项目进度（对标OpenAI官方接口文档）
|  接口   | 描述  | 
|  ----  | ----  |
| List Models  | 获取模型列表 | 
| Completion  | text-davinci-003, text-davinci-002, text-curie-001, text-babbage-001, text-ada-001, davinci, curie, babbage, ada模型 |
| Chat Completion  | gpt-4, gpt-4-0314, gpt-4-32k, gpt-4-32k-0314, gpt-3.5-turbo, gpt-3.5-turbo-0301模型 |
| Create edit  | 创建编辑(待..) |
| Create Image  | 根据描述生成图片 |
| Create image edit  | 根据上传的图片结合输入的描述生成图片 |
| Create Image Variation  | 根据上传的图片生成变体图片 |
| Create embeddings    | 创建向量查询(可以实现PDF对话)(待..) |
| Create transcription  | 语音转换为文字 |
| Create translation    | 一个或多个来源语言的语音或音频文件翻译成目标语言 |
| List files    | 文件列表 |
| Upload file    | 上传文件 |
| Delete file    | 删除文件 |
| Retrieve file    | 检索文件信息 |
| Retrieve file content    | 检索文件内容(OpenAI为了防止滥用,只要plus用户才可以使用) |
| Create fine-tune    | 创建微调 |
| List fine-tunes    | 微调列表 |
| Retrieve fine-tune    | 检索微调信息 |
| Cancel fine-tune    | 取消微调 |
| List fine-tune events | 微调事件列表(待..) |
| Delete fine-tune model    | 删除微调模型 |
| Create moderation    | 创建审核 |
| List engines | 引擎列表(已弃用) |
| Retrieve engine | 检索引擎信息(已弃用) |
| 多会话储存和上下文逻辑    | GPT3.5模型支持上下文逻辑,多窗口上下文对话 |
| 导出导入数据   | 支持导出当前会话，导出全部会话，导入当前会话，导出当前会话，清除当前会话，清除全部会话 |
| 聊天截图到本地图片    | 截图功能，有缺陷只能截图当前窗口的图片，建议QQ长截图（暂时取消） |
| 更换聊天窗口背景    | 支持输入背景图片URL，暂时取消并保留此功能，没太大意义（暂时取消） |
| 角色扮演    | 内置多角色prompt |
| 界面多语言    | 支持中英文语言 |
