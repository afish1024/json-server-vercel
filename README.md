
## 将 JSON Server 部署到 Vercel

将 [JSON Server](https://github.com/typicode/json-server) 部署到 [Vercel](https://vercel.com) 的模板，在线模拟 REST API

在线地址：
1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

![Powered by Vercel](https://images.ctfassets.net/e5382hct74si/78Olo8EZRdUlcDUFQvnzG7/fa4cdb6dc04c40fceac194134788a0e2/1618983297-powered-by-vercel.svg)

### 如何使用

1. 单极“使用此模板”或克隆此存储库。
2. 更新或使用存储库中的默认 [`db.json`](./db.json)。
3. 注册或登录 [Vercel](https://vercel.com)。
4. 在 Vercel 仪表板中，单击“**+新项目**”，然后“**导入**”您的存储库。
5. 在“**配置项目**”屏幕中，将所有内容都保留为默认状态，然后单击“**部署**”。
6. 等到部署完成，您自己的 JSON 服务器就可以提供服务了！

## 默认 `db.json`

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

json-server 的使用：
- https://www.cnblogs.com/Megasu/p/15782353.html
- https://cloud.tencent.com/developer/article/1688659
- https://juejin.cn/post/7043424909472563208#heading-46

## 参考

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
