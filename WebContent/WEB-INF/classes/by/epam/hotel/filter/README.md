# Filter

Filter会在Server容器执行Servlet之前执行

常用于处理Session，Cache，Encode之类的问题等

# urlPatterns

代表Filter会拦截的请求URL

# dispatcherTypes

代表Filter会拦截的请求类型

REQUEST: 拦截直接请求（默认）
FORWARD: 拦截转发请求
INCLUDE: 拦截include模式来的请求
ASYNC: 拦截异步请求
ERROR: 拦截没有被声明的ERROR的请求

# doFilter

Filter的自定义处理方法

# chain.doFilter

传递request，response到下一个Filter
