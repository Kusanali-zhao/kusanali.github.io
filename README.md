# kusanali.github.io

GitHub Pages 静态站点。

## 为什么 `https://kusanali-zhao.github.io/` 打不开？

GitHub 用户名是 **`Kusanali-zhao`**，当前仓库名是 **`kusanali.github.io`**（少了 `-zhao`）。

| 类型 | 仓库名要求 | 访问地址 |
|------|------------|----------|
| 用户站点 | 必须叫 `kusanali-zhao.github.io` | `https://kusanali-zhao.github.io/` |
| 项目站点（当前） | 任意名，如现在的 `kusanali.github.io` | `https://kusanali-zhao.github.io/kusanali.github.io/` |

所以根域名会 **404**；**能打开的地址**是：

**https://kusanali-zhao.github.io/kusanali.github.io/**

## 想用根域名怎么改？

1. 打开仓库 Settings → General → Repository name  
2. 改名为 **`kusanali-zhao.github.io`**（按 GitHub 规则用小写用户名）  
3. 等 Pages 重新部署后访问：https://kusanali-zhao.github.io/

## 本次修复

- 增加根目录 `index.html` 作为正式首页（以前只有内嵌 HTML 的 `README.md`）
- 增加 `.nojekyll`，按纯静态页发布，避免 Jekyll 改写
- 补全 charset / viewport / 移动端可读样式
