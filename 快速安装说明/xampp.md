1. XAMPP 安装
直接到官方网下载最新的就行

1.  数据库创建
mysql -uroot
create database windb
grant all privileges on windb.* to w@localhost identified by "win"

1. 主题添加
**1)**  解压放到 ==wp-content/theme==
**2)**  web后台上传也行
**3)**  启用主题。 这一步必需要比下面的导入wordpress 先做，否则商品信息等无法被导入

1. 删除自动生成的文章，示例页面

1. 上传upload 图片到媒体库

1. xml 博客数据上传
**1)** xml上传前需要替换下里面的图片链接， 把其它月份的数据全部替换成本月的。







