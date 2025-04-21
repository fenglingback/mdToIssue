# mdToIssue

```
我想要利用GitHub API做一个在线md转GitHub issue的工具，满足以下要求：

1. 每次进入需要检测GitHub token：当检测到localStorage中存在"githubToken"键时，验证其有效性，若无效则清除该键值对并触发GitHub Token输入弹窗，待用户点击验证按钮通过API校验有效性后重新保存至localStorage。
2. 顶部是导航栏：包括导入、清空、保存、发布四个按钮。点击导入按钮，有两个选项：从本地导入md文件、从url导入md文件；本地导入就在中间编辑区域的title和content分别写入md文件的文件名和内容，url导入就只在中间编辑区域的content写入url的内容。点击清空按钮，清空中间编辑区域。点击保存按钮，将中间编辑区域的内容保存至localStorage。点击发布按钮，弹出repo选择框用来选择要发布到的GitHub仓库，选择后，将中间编辑区域的内容发布至该仓库的issue中。
3. 中间的左侧和右侧分别是编辑区域和预览区域：编辑区域包括title和content两个输入框，title输入框用于输入issue标题，content输入框用于输入issue内容，content可垂直滚动。预览区域使用marked.js和github css将编辑区域的content内容渲染，预览区域可垂直滚动。中间区域和整个页面都不可滚动。
4. 底部是footer区域：显示powered by fenglingback，"fenglingback"是可点击的链接，点击后跳转到`https://github.com/fenglingback`，链接样式美化突出。
5. 自动适配深色模式，css样式中不要使用hover属性。
6. 尽可能使用html5标签来创建更好的页面结构。
7. 注意内容不要超出屏幕范围。

请你用 HTML5、CSS3 和 JavaScript(ES6+) 来实现这个工具。
```
