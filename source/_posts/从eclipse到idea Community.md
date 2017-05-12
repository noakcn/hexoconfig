---
title:从eclipse到idea Community
tags: 	
 - idea
 - eclipse
 - jetBrain
---

### 调整设置

1. 将import * 调整为500

   `File`-> `Setting` -> `Code Style`->`Java`选择Imports 

   将`Class count to use import with '*'`修改为500(建议值)

   将`Names count to use static import with '*'` 修改为500(建议值)

   > Class count to use import with '*' 导入class达到500条时使用import \*代替

   ​

2. 调整import 顺序

   `File`-> `Setting` -> `Code Style`->`Java`选择Imports

   设置Import Layout

   ```
   static all other, 
   blank, 
   java.*, 
   blank, 
   javax.*, 
   blank, 
   org.*, 
   blank, 
   com.*, 
   blank, 
   all other imports
   ```

   如图所示

   ![layout1](http://om8bq99t5.bkt.clouddn.com/17-5-12/4131747-file_1494587266082_920d.png)
   ![layout2](http://om8bq99t5.bkt.clouddn.com/17-5-12/78262524-file_1494587507430_6d4d.png)

3. tab用四个空格键代替

   `File`->`Setting`->`Code Style`->`Groovy`选择Tabs and Indents 将 `Use tab character` 的勾去掉

   ![img](http://om8bq99t5.bkt.clouddn.com/17-5-12/87029098-file_1494586782026_6f78.png)

   ​





### 插件



### 快捷键







