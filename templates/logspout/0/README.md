# Logspout

### 声明：

<a href="http://www.youruncloud.com" target="_blank">深圳市云舒网络技术有限公司</a>对此模板、此模板相关镜像、及镜像内标识有我司版权声明的脚本和程序拥有版权，受法律保护。

未经本公司书面许可，任何单位及个人不得以任何方式或理由对上述产品、服务、信息、材料的任何部分进行使用、复制、修改、抄录、传播或与其它产品捆绑使用、销售。

凡侵犯本公司版权的，本公司必依法追究其法律责任。

对于其镜像内涉及的第三方软件、组件、库文件，相关版权属于第三方公司、组织或人员所拥有，本镜像仅提供试用功能。

### 概述：

此模板仅用于试用，如需在生产环境使用版本，请联系<a href="http://www.youruncloud.com" target="_blank">有容云</a>。

[该模板基于Glider Labs Logspout，是一个Docker容器日志路由器。它可以路由主机上所有容器的日志到你的日志管理系统(如AppSoar的ELK)]

### 配置：

默认配置如下，配置详细描述请点击<a href="http://www.youruncloud.com/help/68.html" target="_blank">此处</a>。

### 使用：

1.从catalog选择Logspout
2.输入配置项中必填信息(或使用默认配置)
3.点击运行，开始部署

通过AppSoar UI启动的任何服务，请确保禁用'-t'[tty]，否则无法路由该服务(容器)的日志。使用详细描述请点击<a href="http://www.youruncloud.com/help/68.html" target="_blank">此处</a>。
 
