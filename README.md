# wxMini_scanCode
小程序扫码控件，可以模拟二维码在测试环境的测试

## 使用
- 将scanCode文件复制到所需项目中
- 在Page页面中进行引用
 ```js
    config = {
      navigationBarTitleText: '测试扫码能力',
      usingComponents: {
        scanCode: '../components/scanCode/scanCode'
      }
    }
 ```
- 使用组件
```js
  <view class="container">
    <scanCode />
  </view>
```
- 能力预览</br>
<img src="./imgs/gif.gif" >

## 文章参考
- [dev环境测试动态小程序码
](https://juejin.im/post/5e82ff0bf265da47b27d7c57)
- [服务端小程序二维码生成](https://developers.weixin.qq.com/miniprogram/dev/api-backend/open-api/qr-code/wxacode.createQRCode.html)
- [wepy+weui+redux实现小程序脚手架](https://juejin.im/post/5e6087e2e51d4526f16e54ba)
- [玩转微信小程序的位置授权](https://juejin.im/post/5e55e641f265da57547792b0)
- [如何玩转小程序登录体系](https://juejin.im/post/5e4cabe96fb9a07c8914ffc7)

