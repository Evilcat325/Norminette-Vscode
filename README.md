## Norminette Vscode

Simple decorator for vscode user that use norminette command at 42/101 and inject errors of the current opened file in the vscode editor.

# Setting

## Default setting is

```
"norminette.command": "norminette -R CheckForbiddenSourceHeader",
"norminette.fileregex": "^ft.*\\.c$",
```

command will run as $command $filename
fileregex will default to only run on file start with "ft" end with ".c"
Regex is using typescript/javascript synatax;