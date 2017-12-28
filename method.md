pwd   --查看当前路径
cd e:   --进入E盘
mkdir test  --在在E盘下创建test空文件夹
git init   -- 初始化，编程git可以管理的仓库  会生成 .git文件，他就是用来跟踪管理版本库的

git add .添加所有文件
git add test.txt  添加文件名是  test.txt 的文件到缓存区    
git commit -m"add test.txt" 将缓存区里的文件上传
git status 查看文件状态


git rm test.txt  删除文件
git commit -m"remove test.txt"确认删除文档

git remote add origin git @github.com:XIEHONGDAO/learngit.git
git push -u orgin master   第一次push
git push orgin master



git init  初始化


git clone git@github.com:XIEHONGDAO/gitskills.git

ls 查看文件