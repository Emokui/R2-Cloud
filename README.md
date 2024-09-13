**利用 CloudFlare R2+pages 建造网盘/图床服务**

1.Fock本项目


2.创建R2存储桶,设置 "R2.dev 子域" 允许访问


3.pages链接此项目并添加以下变量


PUBURL           复制的公共存储桶URL


GUEST            public/


admin:123123      *


4.函数-R2绑定-变量名填写 BUCKET
