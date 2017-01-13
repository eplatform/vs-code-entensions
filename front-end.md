#Visual Studio Code Recommended Extensions for a Front-End Developer
####Quick Guide
- Click extensions icon on the list(its white one bottom of the list)
- When menu opened click …(3 dots) right-top of the extensions menu
- Then Choose ‘Configure Recommended Extensions (Workspace)’

<img class="progressiveMedia-image js-progressiveMedia-image" data-src="https://cdn-images-1.medium.com/max/800/1*wf8ry089aLB2t_VqRk-8vg.png" src="https://cdn-images-1.medium.com/max/800/1*wf8ry089aLB2t_VqRk-8vg.png">

- Change content of extensions.json file with following snippet and save

```javascript
{
 // See http://go.microsoft.com/fwlink/?LinkId=827846
 // for the documentation about the extensions.json format
 "recommendations": [
  // Extension identifier format: ${publisher}.${name}. Example: vscode.csharp
  "formulahendry.auto-close-tag",
  "dzannotti.vscode-babel-coloring",
  "michelemelluso.code-beautifier",
  "dbaeumer.vscode-eslint",
  "donjayamanne.githistory",
  "ecmel.vscode-html-css",
  "abusaidm.html-snippets",
  "christian-kohler.path-intellisense",
  "xabikos.ReactSnippets",
  "shinnn.stylelint",
  "robertohuertasm.vscode-icons"
 ]
}
```

- Click again …(3 dots) right-top of the extensions menu
- And finally choose ‘Show WorkSpace Recommended Extensions’
<img class="progressiveMedia-image js-progressiveMedia-image" data-src="https://cdn-images-1.medium.com/max/800/1*9ZBdpY1COgTK-nqOgdhxVQ.png" src="https://cdn-images-1.medium.com/max/800/1*9ZBdpY1COgTK-nqOgdhxVQ.png">
7. Install packages from the list

Also you can add some keyboard shortcuts:

```json 
[
 {
 “key”: “cmd+alt+i”,
 “command”: “editor.action.formatDocument”
 },
 {
 “key”: “cmd+y”,
 “command”: “redo”
 }
]
```
😎 HAPPY HACKING 🙌🏼
