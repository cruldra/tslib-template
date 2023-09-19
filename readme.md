这是一个``typescript``库项目,用``semantic-release``自动发布到``npm``.

## 使用

1. 先准备好你的``github``和``npm``令牌
2. 点击``Use this template``复制这个项目
3. 添加两个``secrets``,``NPM_TOKEN``和``GH_TOKEN``,如图:![img.png](img.png)
4. 把``.github/workflows/publish-to-npm.yml1``重命名为``.github/workflows/publish-to-npm.yml``
5. 在``package.json``中修改``name``和``repository``

## 注意事项

- 不要在``publish-to-npm.yml1``中直接使用``npm_token``,npm会检测是否泄漏,如果直接使用会导致npm撤销令牌
