# Preface

This plugin solves a series of user experience problems in vim's preview window and provide a handy way to preview tags, files and function signatures.

`vim-preview` introduces several commands:


| Command | Arguments | Description |
|---------|-----------|-------------|
| PreviewTag | `[tagname]` | Display the tag in the preview window circularly |
| PreviewFile | `[+cmd]` `filename` | Display the file in the preview window |
| PreviewClose | `N/A` | Close the preview window |
| PreviewScroll | `offset` | Scroll preview window without leaving current window or inser mode |
| PreviewSignature | `[function name]` | Preview the function signature circularly in the command line |


## PreviewTag
 
This command can display tag definition in the preview window circularly:

```VimL
PreviewTag [tagname]
```





Every body uses a 16:9 wide display today, but the default preview window can still only be opened in a new split above or below current window.



