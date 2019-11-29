# Changelog
## Unreleased

### v1.15 update
#### 新增

添加 单元测试  
添加 添加IP检查函数  
添加文件检测框架
  
#### 移除
>　PS: 将在 2.0版本移除以下函数.　　
 
RookieTools.PasswordCheckBase.pool 请使用 RookieTools.pool　　

RookieTools.common.host2ip　请使用　RookieTools.host2ip

RookieTools.common.is_open_port 请使用　RookieTools.is_open_port

#### 已知BUG
pool 传入 ProcessPoolExecutor 进程池卡死

#### 修复

修复日志多次输出BUG  

#### 重构

重构 downloader 函数  
重构 urllib3 hook 函数  
重构 ip 检查相关函数  
重构检查框架


### v1.11 update

修复 gzip boom BUG  
删除历史代码.  
downloader 重构  
TODO: deflate bomb 未进行修复
