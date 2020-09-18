原作者的github地址: https://github.com/BNDong/Cnblogs-Theme-SimpleMemory

博客园皮肤，基于原版进行一些定制化的修改。

1.更新了/src/script/base.js

使得在博客后台可以通过homeBannerTextAuthor设置副标语。
  
用法：

	window.cnblogsConfig = {
	    homeBannerText: [//标语
	        "我是标语一",
	        "我是标语二",
	        "我是标语三",
	        "我是标语四",
	    ],
	    homeBannerTextAuthor: [//副标语
	        "I'm slogan one",
	        "I'm slogan two",
	        "I'm slogan three",
	        "I'm slogan four",
	    ],
	}

2.更新了/src/script/articleStatement.js

修改了文章后缀中“关于作者”的默认文本。