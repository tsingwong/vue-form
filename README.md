
## Vue实现表单提交

### 具体功能实现

1. 移动端页面与PC端页面一致；
2. 页面初始化时，使用ajax发送get请求，获取数据；
3. 为各个字段创建检验规则，按照需要加载验证规则；
4. 表单提交时，验证有错误时，弹窗显示错误，并保持原状；验证没有错误的时候，使用ajax发送POST请求，参数为用户填写的内容组成的对象。

### 未完成工作及不足

1. 选择 `行业类型` 时，并未使用弹层；
2. 对于 `是否打折` 字段，其规则是必填，这里写的规则是 `是否获取过焦点`；
3. 由于之前没有接触过Vue.js及移动端页面，故代码臃肿，且对Vue的理解不够。
4. 开发的时候使用是Chrome浏览器，其他浏览器的兼容性并未测试；
5. 页面背景颜色部分与UI设计有所差异。
