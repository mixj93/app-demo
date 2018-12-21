# app-demo

[如何创建应用市场V2的应用](https://appstorev2.netlify.com)

## 步骤

1. 制作chart
2. 上传chart（`anchor chart push super ./castro-1.0.0.tgz`）
3. 创建appspec（`anchor appspec create super/castro -d "Castro" -c super/castro:1.0.0 -f schema.json`）
4. 增加可见区域（`anchor appspec region add super/castro cxq`）
5. 更新appspec（`anchor appspec upgrade super/castro -d "Castro" -c super/castro:1.0.1 -f schema.json`）
