# anaconda基本使用
- anaconda主要是一个虚拟环境管理器
- 还是一个安装包管理器
- conda list ： 显示anaconda安装的包
- conda env list : 显示anaconda的虚拟环境列表
- conda create -n xxx python=3.6: 创建python版本为3.6的虚拟环境，名称为xxx
- 



# 类的基本实现 
- 可以用过默认内置变量检查类和对象的所有成员
    - 对象所有成员检查
        
        # dict前后各两个下划线
        obj.__dict__
        
    - 类所有的成员
    
        # dict前后各两个下划线
        class_name.__dict__