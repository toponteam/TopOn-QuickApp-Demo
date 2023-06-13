# TopOn快应用广告SDK使用注意事项


## 配置信息说明

1、请将./src/app.ux 中的appId、appKey替换为您在topon开发者后台的相应的appId和appKey
2、请将./src/manifest.json 中的package换为您的包名
3、请将./src/pages/**/index.ux 对应appId下的对应广告位ID
4、请运行npm run install更新@topon/quick-app-sdk至最新版本

## 其他说明

1、若在测试过程中有更换appId的场景（appId: 'aaa' => appId: 'bbb'），请在在更换appId后先清除快应用localStorage中的缓存后刷新快应用IDE或者调试器