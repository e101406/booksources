## 阅读书源

### 书源来源
[http://ku.mumuceo.com](http://ku.mumuceo.com)   
感谢广大网络文学爱好网友的归纳整理

### 说明
每隔一段时间书源就大批量失效，为了方便阅读APP书源更新使用，特地整合了这个书源版本，后续会增加其它版本   

#### 目录约定
```$xslt
- 2.0（适用2.0版本书源）
- 3.0（适用3.0版本书源）
        // 以上每一个目录下都拥有（不存在就是没有源，默认书源前100条）
        --- total.json（全部书源）
        --- total_300.json（全部书源300条）
        --- is_audio.json（书源支持音频）
        --- is_search.json（书源支持发现）
        --- is_discover.json（书源支持搜索）
```  

#### 关于导入
```$xslt
导入地址：https://raw.githubusercontent.com/e101406/booksources/master/{书源版本文件夹}/{书源json文件名称}
例：假如我要导入2.0版本书源下的total.json（全部书源）
   则导入地址为：https://raw.githubusercontent.com/e101406/booksources/master/2.0/total.json
   其它书源同理，替换地址中文件夹和文件名即可

tips: 导入过程可能因网络问题（众所周知的原因）导致出现错误，可以多导入几次或者科学上网导入。
```  

#### 更新情况
```$xslt
1.0 增加书源站点健康度检测（ping方式）,按延迟选择前100个最优站点生成书源文件   
1.1 鸽了大半年，修复书源获取，现在能同步更新源仓库数据了
```  
