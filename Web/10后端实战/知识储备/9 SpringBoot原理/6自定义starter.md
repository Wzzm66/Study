
![[Pasted image 20261028165807.png]]


![[Pasted image 20261028170536.png]]


![[Pasted image 20261028171626.png]]

![[Pasted image 20261028171915.png]]


在starter中引入autoconfigure依赖
![[Pasted image 20261028172249.png]]

在autoconfigure中引入阿里云依赖
![[Pasted image 20261028172610.png]]![[Pasted image 20261028172602.png]]


把之前做的阿里云工具类放进来
![[Pasted image 20261028172945.png]]

去除原来的@Component和@Autowrite注解，加上有参构造
![[Pasted image 20261028173024.png]]


![[Pasted image 20261028173220.png]]

去掉Component注解
![[Pasted image 20261028173759.png]]


定义一个自动配置类
![[Pasted image 20261028173727.png]]


定义自动配置文件将自动配置类的全类名放入
![[Pasted image 20261028174008.png]]





在测试的项目中引入刚刚写的起步依赖
![[Pasted image 20261028174241.png]]

配置阿里云的访问信息
![[Pasted image 20261028174455.png]]


测试
![[Pasted image 20261028174400.png]]