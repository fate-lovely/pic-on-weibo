#图床on微博



##功能

- 拖拽上传，复制上传
- 批量上传
- 浏览历史记录（存储在localStorage中）
- 导出历史记录



**注意： 图片一旦上传，无法删除（可能一直保留到微博倒闭那天），请不要上传任何隐私图片，同时，这个服务完全依赖微博，可能某一天就无法使用。**



##说明

- 图片上传具体实现？

  图片上传使用的是[http://picupload.service.weibo.com/interface](http://picupload.service.weibo.com/interface) 这个接口。上传之前需要登录微博，上传的图片不会显示在你的微博相册中，也不会和你的任何微博挂钩，完全的“野生图片”。

- 换一台电脑没有历史记录？

  历史记录存在浏览器本地存储中。目前没有可靠办法跨设备存储历史记录。

- chrome跨域

  http://stackoverflow.com/questions/9421933/cross-origin-xmlhttprequest-in-chrome-extensions/9422216#9422216

  ​