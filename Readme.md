**在mysql中创建一个数据库mall（名字自己随便取，后面改就是）：create database mall DEFAULT CHARASET utf8 COLLATE utf8_general_ci;**

项目根目录：

1、首先修改数据库信息，在 `/shoppingmall/settings.py` 中，修改数据库的名称和密码：

<img src="https://mmbiz.qpic.cn/mmbiz_png/ULibHgXIt3jzFVGN1TibEnUQiak7m280hJiaMxGl4qhya6TO2GRCTKXWkiasxRaBiaabLVTNxJNW79BqHMnp1omC1tjA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" alt="图片" style="zoom:30%;" />

2、生成迁移文件：`python manage.py makemigrations`

3、执行迁移脚本：`python manage.py migrate`。

<img src="https://mmbiz.qpic.cn/mmbiz_png/ULibHgXIt3jzFVGN1TibEnUQiak7m280hJiaiaf4iaiakyaE2UI8WAibxWiaPHE5iaqyuT7zJibGLc47cNxTWXeFAVa1Rbaag/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" alt="图片" style="zoom:30%;" />

