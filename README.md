﻿```mermaid
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    Alice-)John: See you later!
```


暂时：
被控制端								控制端
		-----连接对方的8888端口----->
				（socket）
				
发送屏幕信息------------------------>
			<-----------------------接收并信息,发送按键信息
模拟按键信息

重复这个过程
