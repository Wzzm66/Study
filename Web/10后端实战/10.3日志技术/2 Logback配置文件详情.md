
![[Pasted image 20261012081456.png]]


完整的配置文件
![[Pasted image 20261012081600.png]]

![[Pasted image 20261012081701.png]]


管理了开关和上面定义的输出位置
![[Pasted image 20261012081742.png]]


日志输出的格式
{%thread}：表示输出的线程名字
%level：表示输出的日志级别   
-5%level：表示输出的日志级别，并且输出五个字符，不足的话会自动补全
%logger{50}：表示日志记录器的名字，最多50个字符，超过会自动简化
%msg：表示日志对象的传递信息     %n：换行
![[Pasted image 20261012081928.png]]


![[Pasted image 20261012082744.png]]







Logback的日志级别
![[Pasted image 20261012083441.png]]