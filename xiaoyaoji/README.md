#### 制作小幺鸡接口文档镜像

## 谨记，能用就行，不影响主体功能就行，暂时知道有几个小问题
> 折腾了几天了，不想再折腾了
> 更换头像，右上角不会马上更新，要退出登录
> 通过邮箱找回密码时，后端接口没抛具体异常信息，直接返回一个response的请求体，说系统错误

**官方仓库地址  https://gitee.com/zhoujingjie/apiManager**  
**个人fork出来的地址  https://github.com/hegphegp/xiaoyaoji**

#### 使用方式
* 先导入sql文件夹的SQL脚本
* 启动docker-compose.yml脚本

## 谨记，如果用nginx做反向代理，必须是代理根路径到tomcat，不能代理其他路径到tomcat，因为有代码是这样子写的 return new ModelAndView("redirect:/plugin/config"); 没必要折腾了，能用就行了

