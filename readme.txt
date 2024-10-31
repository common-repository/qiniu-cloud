=== Qiniu Cloud For Wordpress ===
Contributors: Cuelog
Donate link: http://cuelog.com
Tags: 七牛, 云储存, qiniu, qiniu cloud, autosave, remote
Requires at least: 3.5
Tested up to: 3.6
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Auto save the attachments to Upyun Cloud Storage

== Description ==

1，请先申请七牛账户并开通镜像加速
2，不需要修改程序任何代码，通过传统的上传方式上传附件后自动使用七牛的镜像加速，
   当用户请求资源（图片，文件）时，七牛会自动从你服务器上拉取资源并加载，以后用户
   访问的时候，自动从七牛空间上获取资源，从而降低服务器带宽压力，提高访问速度

== Installation ==

1，申请七牛云云储存：http://portal.qiniu.com/signup?code=3l7qkmf1ct2kx
2，创建一个云空间，并上传一个名字为 quniu_test.jpg 文件（任意格式）到七牛云空间
3，根据插件选项的说明，填写七牛云储存开发者后台中的相关参数
4，上传本地的附件并将URL转换为七牛的URL

= 1.0.0 =
# released the first version.