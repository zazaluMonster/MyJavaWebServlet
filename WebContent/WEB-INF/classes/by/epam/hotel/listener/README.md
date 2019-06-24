# Listener

JavaWeb的架构内有是三个东西我们常常要去关心，

1. ServletContext

2. HttpSession

3. ServletRquest

所以JavaServlet-api给我们已经提供了监听器，当上面是三个对象创建销毁的时候，都会调用监听器的方法（也就是回调）