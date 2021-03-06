### 说明
WordPress是一个注重美学、易用性和网络标准的个人信息发布平台。WordPress虽为免费的开源软件，但其价值无法用金钱来衡量。

WordPress的图形设计在性能上易于操作、易于浏览；在外观上优雅大方、风格清新、色彩诱人。

### 详细步骤

1.确保您有可用集群，创建集群详情见：[集群基本教程](https://www.qcloud.com/doc/product/457/6779)

2.这里使用了tutum/wordpress Docker镜像来创建一个公开访问的Wordpress网站

3.创建单实例版的wordpress仅供测试使用，该镜像中包含了wordpress所有的运行环境，直接拉取创建服务即可，但使用单实例版的wordpress不能保证数据的持久化存储，建议您使用自建的mysql或使用腾讯云数据库CDB来保存您的数据，可见使用[CDB版的wordpress搭建](https://www.qcloud.com/document/product/457/7447)

#### 创建wordpress服务

1.输入服务名称，选择运行集群

2.填写镜像tutum/wordpress，选择latest版本

3.填写端口映射

![Alt text](https://mc.qcloudimg.com/static/img/3b40d7cd09c0850569fa7967b7aaa362/Image+024.png)
![Alt text](https://mc.qcloudimg.com/static/img/27a0a00a151c5f5ebacffca5fc8f832a/Image+025.png)
### 访问wordpress服务
点击服务，查看服务外网ip，在浏览器输入ip地址即可访问
![Alt text](https://mc.qcloudimg.com/static/img/c0132b35996db099c02af7f2cf747137/Image+023.png)