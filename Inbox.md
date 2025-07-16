```dataviewjs
const folder = "0 Inbox";
const file = app.vault.getAbstractFileByPath(`${folder}/Inbox.md`);
app.workspace.getLeaf().openFile(file);
```
