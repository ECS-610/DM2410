# DM2410 ARM9嵌入式实验
##IAR 6.40.1安装
- 一 [IAR_Crack](http://pan.baidu.com/s/1i3kXLyP)为IAR破解程序,[CD_EWARM_6401_3812](http://pan.baidu.com/s/1gdIRNjH)为IAR安装程序   
 ![1](http://img5.douban.com/view/photo/photo/public/p2239693923.jpg)    
- 二 打开CD_EWARM_6401_3812文件夹，双击选中图标autorn.exe    
 ![2](http://img3.douban.com/view/photo/large/public/p2239697463.jpg)    
- 三 双击autorun.exe后出现如下图所示的界面，并单击红笔圈住的部分   
- ![3](http://img5.douban.com/view/photo/photo/public/p2239693928.jpg)   
- 四 点击Next   
 ![4](http://img5.douban.com/view/photo/photo/public/p2239693929.jpg)   
- 五 选择I accept the terms of the  license agreement后点击Next   
 ![5](http://img5.douban.com/view/photo/photo/public/p2239693930.jpg)    
- 六 打开IAR_Crack文件中的IAR破解程序    
 ![6](http://img5.douban.com/view/photo/photo/public/p2239693931.jpg)    
- 七 选择Embedded Workbench For ARM v5.40,点击Generate，将生成的license复制到下图点击NEXT(注意点击之后不要关闭)   
 ![7](http://img5.douban.com/view/photo/photo/public/p2239693932.jpg)   
- 八 出现下图将第八步生成的License key复制到下图中，并关闭第八步打开的IAR破解程序   
 ![8](http://img5.douban.com/view/photo/photo/public/p2239693933.jpg)    
- 九 点Next   
 ![9](http://img5.douban.com/view/photo/photo/public/p2239693934.jpg)    
- 十 出现如下界面后什么也不用操作，继续点击Next.   
 ![10](http://img5.douban.com/view/photo/photo/public/p2239693936.jpg)    
- 十一 选择Install.    
 ![11](http://img5.douban.com/view/photo/photo/public/p2239693937.jpg)    
- 十二 出现如下界面方框后打勾，然后点击Finsh.    
 ![12](http://img3.douban.com/view/photo/photo/public/p2239693940.jpg)    
- 十三 点击Exit退出   
 ![13](http://img3.douban.com/view/photo/large/public/p2239693941.jpg)    





#2 一个简例   
- 用IAR打开[miniGUI](http://pan.baidu.com/s/1dD3wN9f)工程项目:         
 ![菜单项](http://img3.douban.com/view/photo/large/public/p2239691074.jpg)       

 ![选择](http://img5.douban.com/view/photo/large/public/p2239691076.jpg)        
          
          
- 选中工程，右键展开菜单，点选**option**项       

 ![option](http://img5.douban.com/view/photo/large/public/p2239694336.jpg)       

- 选中左侧**Linker**项，勾选Override default,将文件替换成本工程.icf文件    
 ![icf](http://img3.douban.com/view/photo/large/public/p2239694340.jpg)   

- icf文件路径:  
  ![icf_path](http://img3.douban.com/view/photo/large/public/p2239694341.jpg)     

- 点击icf路径栏下的**Edit**项 选择第三个**Stack/Heap Size**选项卡 将最后**Heap**项参数改为0xf0000  
  ![stack](http://img3.douban.com/view/photo/large/public/p2239700030.jpg)

- 将开发板LCD右下侧的开关推至off   
  ![off](http://img5.douban.com/view/photo/photo/public/p2239702549.jpg)

- 点击IAR左侧菜单栏中**make** 和**Download and Debug**按钮编译和运行    
  ![make](http://img3.douban.com/view/photo/large/public/p2239702970.jpg)  
  ![b&b](http://img3.douban.com/view/photo/large/public/p2239702974.jpg)  


