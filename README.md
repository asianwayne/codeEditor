# codeEditor

<!-- wp:list -->
<ul><li>双击打开列表，单击预览文件</li><li>按住alt+ 数字键盘， 可以打开已经打开的指定顺序的文件。</li><li>如果要跳到指定的文件而这些文件没被打开，就按ctrl + p 或者 mac的cmd + p 输入文件名字就好</li><li>按住ctrl + tab 切换已打开的文件</li><li>按住ctrl+shift+p 打开功能选项， 输入shortcuts json, 找到不是default的shortcode json. 可以更改shortcut</li><li>按住ctrl + 数字键盘，可以创建和切换不同的窗口，可以同时比对文件</li><li>如果要实现ctrl+数字键盘可以如同tab 一样切换文件， 可以修改shortcuts json文件：</li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>{&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+1","command":"workbench.action.openEditorAtIndex1"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+2","command":"workbench.action.openEditorAtIndex2"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+3","command":"workbench.action.openEditorAtIndex3"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+4","command":"workbench.action.openEditorAtIndex4"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+5","command":"workbench.action.openEditorAtIndex5"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+6","command":"workbench.action.openEditorAtIndex6"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+7","command":"workbench.action.openEditorAtIndex7"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+8","command":"workbench.action.openEditorAtIndex8"&nbsp; &nbsp; },&nbsp; &nbsp; {&nbsp; &nbsp; &nbsp; &nbsp; "key":"ctrl+9","command":"workbench.action.openEditorAtIndex9"&nbsp; &nbsp; },</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>ctrl + b 隐藏或显示sidebar. </li><li>如果想要sidebar出现在右侧，按住ctrl + , 可以打开settings 或者可以在file -> preference ->settings, 点击右上角的碎片，打开settings.json， 输入："workbench.sideBar.location": "right"。就可以把sidebar移到右边</li><li>Ctrl + J 打开或隐藏terminal </li><li>在settings.json里面修改终端的fontsize ： "terminal.integrated.fontSize":16</li><li>内置markdown live preview 功能： markdown 模块右侧上方的的预览功能即可</li><li>vs code可以搜索正则模式： https://www.youtube.com/watch?v=zwyHmFxeJtg&amp;t=249s</li><li>ctrl + k + w 关闭所有打开的文件 </li><li>在打开的css或者js文件中查找属性或者函数， 按ctrl+shift+o 就可以上下切换</li><li>alt+shift+down arrow 可以复制一行  up arrow是向上复制 </li><li>alt + up 或者down 可以向上或者向下移动 </li><li>多选几行的话 用down 或者up 然后按住shift 可以多选 ， 然后再按住alt+up 或者down 进行多行移动</li><li>Indent and format</li><li>ctrls+shift+p， 输入format， 可以选择格式化的种类进行代码格式化 </li><li>vscode可以设置每次保存的时候自动format: </li><li>按住ctrl+, 打开settings 点击右上角的碎片，打开settings.json  搜索输入format on save 就是在搜索, 设置为true 就好。 "editor.formatOnPaste": true, 就是设置每次粘贴的时候自动格式化</li><li>vs的prettier插件可以更好的进行代码的格式化 </li></ul>
<!-- /wp:list -->
