# Eclipse Plugin相关限制

1.在使用销售易开发者平台Eclipse Plugin进行操作之前，要先进行登录操作。

2.一个Eclipse workspace下的所有project享有同一套登陆信息，并且修改任一project credentials都会影响相同workspace下的其他proejct。

3.如果在多租户并行开发时，需要给每个租户单独创建一个Eclipse workspace，做到一个租户享有一个workspace。

4.研发人员可以下载线上业务逻辑代码到本地，如果线上代码与本地代码不一致，会提示用户是否用线上代码覆盖本地代码。

5.部署代码到线上业务逻辑代码功能，自动校验线上与本地代码差异。





