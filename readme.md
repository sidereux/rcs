# 整体规划
服务端、桌面端、移动端、web，最好都要有，但我精力有限，所以决定优先实现桌面端和服务端，移动端次之，web目前看优先级最低。

桌面端比较重，主要业务逻辑和计算都在桌面端实现。

服务端比较轻，主要做同步和一些简单的计算。

# 服务分类

center 主服务，使用端口50001

# 功能设计

## 输入网页，自动获取标题等信息
这个在桌面端和移动端都有需求，可以考虑用c++实现，然后给两端调用。
