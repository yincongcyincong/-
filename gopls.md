### 后台执行
./gopls serve -listen :8080

### vscdoe 交互配置
```
"go.languageServerFlags": [
  "-remote=localhost:8080"
],
```
 Ctrl+Shift+P (or Cmd+Shift+P on macOS) 快捷键 找"Go: Restart Language Server"进行vscode重启

