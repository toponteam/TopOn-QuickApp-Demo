# TopOn快应用广告SDK使用注意事项


## 配置信息说明

- 请将./src/app.ux 中的appId、appKey替换为您在topon开发者后台的相应的appId和appKey
- 请将./src/manifest.json 中的package换为您的包名
- 请将./src/pages/**/index.ux 中的placementId改为对应appId下的对应广告位ID
- 请运行npm run install安装依赖
- 由于demo中的SDK并不会同步更新，为确保使用最新版本的SDK，可先uninstall后再重新install

## 其他说明


- 若在测试过程中有更换appId的场景（appId: 'aaa' => appId: 'bbb'），请在在更换appId后先清除快应用localStorage中的缓存后刷新快应用IDE或者调试器