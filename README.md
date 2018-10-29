# clo.DT
hand-writable programming notation, part of clo.core

example:  # `/#`表示REPL

```
/# hello world/= log

hello world

/# f/= log 你好{time/str/1} =/ # time/str/1-> yy-mm-dd hh:mm:ss
你好 2018-10-29 17:32

```

运算符| 定义 | 效果 | 常规等价 
------|-----|------|--------
/  | 斜杠 | 分隔符 | [:] [，]
名/1 | 斜杠/2 | 定义、引用 |

