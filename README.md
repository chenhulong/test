# test
test
git init          //git add . 和 git commit 也是必要的, 这样做会生成master主分支,否则
                  //后续push会有报错 error: src refspec master does not match any.
curl -u '用户名' https://api.github.com/user/repos -d '{"name":"仓库名"}'
git remote add origin https://github.com/用户名/仓库名.git
                 //或者使用ssh,避免输入密码 
                 //git remote add origin git@github.com:用户名/仓库名.git
git push origin master
--------------------- 
作者：chent86 
来源：CSDN 
原文：https://blog.csdn.net/chent86/article/details/78575998 
版权声明：本文为博主原创文章，转载请附上博文链接！
