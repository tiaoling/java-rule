### 必须遵守
1. 如无特殊要求，api 必须遵守 REST 风格


```
HTTP 方法 路径  控制器#动作 作用
GET /photos photos#index  显示所有图片
GET /photos/new photos#new  显示新建图片的表单
POST  /photos photos#create 新建图片
GET /photos/:id photos#show 显示指定的图片
GET /photos/:id/edit  photos#edit 显示编辑图片的表单
PATCH/PUT /photos/:id photos#update 更新指定的图片
DELETE  /photos/:id photos#destroy  删除指定的图片
```

