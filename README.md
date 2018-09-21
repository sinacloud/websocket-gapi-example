# 示例程序说明

## 用途

新浪云提供的channel（WebSocket）服务的实际应用场景。

## 开启服务

- 注册新浪云账户<https://www.sinacloud.com>
- 在云应用<https://sae.sina.com.cn>创建一个PHP环境的应用
- 开通channel服务，在“通信服务” - “Channel”分类


## 上传代码

将本示例的所有代码上传到代码根目录下访问即可。


## 说明

示例演示了如何从一个真实的应用上创建一个WebSocket的连接，并使用channel的上行接口发送数据。

## 使用的类库

- VUE2.0 用于前端的逻辑<https://cn.vuejs.org/>
- element ui2.0 用于前端的框架 <http://element-cn.eleme.io>
- create_channel.php 创建WebSocket连接
- send_message.php 上行发送消息