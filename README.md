> Original
> Stuff
·universal_css和universial_js里放着全网通用的css和js文件
·网站的树状结构放置在html_开头的文件夹中，html_###中包含着###页面的文件和子页面的html文件夹
·某个页面单独的css和js文件放置在###_css和###_js文件夹中
·某个页面的元素素材放置在###_material文件夹中
              网站
           ____||__________________________________
           ||           ||                       ||
(universal_css/js)(index_material)         (html_index)
                     ____________________________||________________________
                     ||             ||                   ||               
                (html_###1)     (html_###2)         (html_###3)    ........
                     ||      
     ________________||__________________________________________________________
     ||              ||               ||           ||             
 (###1_css/js) (###1_material)  (html_sub###1) (html_sub###2).......
                                       .
                                       .
                                       .
                                       .
          new
>

----
## Changelog
Aug. 25th

* Added "chgname.sh" to solve potential case-sensitive issue. (ON Linux)
* Known Issue: Improper behaviour on traversing: too many mv's
