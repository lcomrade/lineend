**LineEnd** - is a very simple library that allows you to control the end of lines.


## Installing
Add the following to your `go.mod` file:
```go.mod
require git.lcomrade.su/root/lineend v1
```


## Using
The library is very easy to use. Here is the documentation:

| Function                               | Description                                                                                                |
| -------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `GetLineEnd      (text string) string` | Allows you to get the end of a line used in the text. It can return `\r\n`, `\r`, `\n` or an empty string. |
| `DosToOldMac     (text string) string` | Converts end of line from CRLF to CR.                                                                      |
| `DosToUnix       (text string) string` | Converts end of line from CRLF to LF.                                                                      |
| `OldMacToDos     (text string) string` | Converts end of line from CR to CRLF.                                                                      |
| `OldMacToUnix    (text string) string` | Converts end of line from CR to LF.                                                                        |
| `UnixToDos       (text string) string` | Converts end of line from LF to CRLF.                                                                      |
| `UnixToOldMac    (text string) string` | Converts end of line from LF to CR.                                                                        |
| `UnknownToDos    (text string) string` | Converts unknown line end to CRLF.                                                                         |
| `UnknownToOldMac (text string) string` | Converts unknown line end to CR.                                                                           |
| `UnknownToUnix   (text string) string` | Converts unknown line end to LF.                                                                           |
