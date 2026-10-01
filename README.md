# 小公主乐园 🏰

一个挂在 GitHub Pages 上的可爱小网页，摩尔庄园风格的地图主页。

- 主页：<https://jack975645419.github.io/princess_home/>
- 进入密语：`dengdeng`（客户端简单口令，仅作趣味遮挡，不是真正的加密）

## 页面

- `index.html` — 密码门 + 乐园地图，点击「小苦瓜餐厅」进入餐厅
- `restaurant.html` — 小苦瓜餐厅，菜单里目前有「油焖大虾」的做法
- `css/style.css` — 所有样式

## 本地预览

直接双击 `index.html`，或在目录里起个静态服务：

```
python -m http.server 8000
```

## 加新建筑 / 新菜

- 新建筑：在 `index.html` 的 `.map-scene` 里复制一个 `.building` 卡片，并在 `style.css` 里给它一个 `left/top`。
- 新菜：在 `restaurant.html` 里复制一个 `.dish` 卡片（`data-dish="xxx"`），再复制一份 `<section class="recipe" id="recipe-xxx">`。
