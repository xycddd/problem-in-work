#### 如何解决冲突

假设和master有冲突的分支是 test_conflict

1. git checkout master
2. git merge test_conflict
3. 在idea中找到冲突的代码进行解决

#### 提交了错的文件

1. git log找到上一次的提交，假设commit的名称为 asdfafdaf
2. git reset --soft asdfafdaf

#### 一个分支上的代码还没有通过评审，在另一个分支上修改了代码

解决方式一：将修改的代码直接提交上去，再次切换回原来分支的时候修改就会不见<br>
解决方式二：<br>
1. git add 修改的文件
2. git stash save "save messge" 修改的文件已经被保存，在版本控制中看不见了
3. 如果要应用的话，使用git stash apply
