在git上先从主分支clone一个自己的分支master1  
将master1拉到本地  
如果master中的文件1有内容修改，本地的master1没有修改，则可以直接merge，不会报错  
如果master中的文件1有内容修改，本地的master1也有修改，则会存在冲突，需要手动解决  
  
解决完冲突后可以直接推送  