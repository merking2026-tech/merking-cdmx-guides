# Merking Digital Technology — CDMX Living Series (GitHub Pages source)

静态站点源仓库，部署到 GitHub Pages 后，由 Whop 的 Website Embed 应用分别内嵌到对应付费商品页面。买家在 Whop 内解锁后浏览，到期收回 Whop 侧访问权限。

## 目录结构

| 目录 | 对应商品 | Whop 商品 ID | 方案 ID |
|---|---|---|---|
| `p1/` | CDMX Arrival Companion（$129） | `prod_GVmemoxyTMuji` | `plan_nFeFOzRHZvQ1e` |
| `p2/` | CDMX Relocation Blueprint（$449） | `prod_ZpgCNNUM3cXis` | `plan_AGcdBU4schS9c` |
| `p3/` | The Expat Living Vault: Mexico City（$999） | `prod_gzp9R8VrVATU2` | `plan_U0XPXiXN7o0Hm` |

每个目录下 `index.html` 为产品主页，`assets/` 内含配图、音频（MP3）和模板（CSV，EN + ZH）。

## Pages 地址（已发布）

- 仓库：`merking2026-tech/merking-cdmx-guides`（公开，Pages 由 `main` 分支根目录部署）
- P1：`https://merking2026-tech.github.io/merking-cdmx-guides/p1/`
- P2：`https://merking2026-tech.github.io/merking-cdmx-guides/p2/`
- P3：`https://merking2026-tech.github.io/merking-cdmx-guides/p3/`

## 说明

- 页面已加 `noindex, nofollow`，不希望被搜索引擎收录；Whop 付费墙之外仍应避免公开传播直链。
- 字体使用 Google Fonts（Playfair Display + Inter），系统字体为回退。
- 封面图与片头视频不属于站内页面素材，未纳入本仓库。
