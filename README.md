# TweetSpark Landing Page

## 🚀 部署到 Vercel（需要你操作）

### 方法 1：GitHub + Vercel（推荐）

1. **创建 GitHub 仓库**
   - 去 github.com/new
   - 仓库名：tweetspark-landing
   - 公开/私有都可以

2. **上传代码**
   ```bash
   cd tweetspark-landing
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/tweetspark-landing.git
   git push -u origin main
   ```

3. **连接 Vercel**
   - 去 vercel.com/new
   - 导入 GitHub 仓库
   - 点击 Deploy
   - 完成！获得 .vercel.app 域名

### 方法 2：Vercel CLI（如果你装了）

```bash
npm i -g vercel
cd tweetspark-landing
vercel
# 按提示登录并部署
```

### 方法 3：直接拖拽（最简单）

1. 安装 Vercel CLI：`npm i -g vercel`
2. 运行 `vercel` 命令
3. 或者把 `index.html` 直接拖到 vercel.com 的部署页面

---

## 📧 收集邮箱的后续

现在的代码只是把邮箱存到内存（刷新就没了）。你需要：

**方案 A：简单版（推荐先用）**
- 用 Google Forms 或 Tally.so 做收集表单
- 把表单嵌入到页面里

**方案 B：专业版**
- 接入 ConvertKit / Mailchimp / 邮件服务
- 或者用 Supabase 免费版存邮箱

---

## 🎯 推广策略（让链接被看到）

### 第一优先级（马上做）

1. **Twitter Build in Public**
   ```
   I'm building TweetSpark — turn ideas into tweets in 10s.
   
   Landing page is live. What do you think?
   
   👉 [你的链接]
   
   #buildinpublic
   ```

2. **Reddit r/indiehackers**
   - 标题："I built a landing page for my AI tweet tool. Roast me."
   - 内容：介绍你在解决的问题，附链接

3. **Telegram/Discord 群**
   - 独立开发者群
   - AI 产品群
   - 不要 spam，真诚分享

### 第二优先级（本周做）

4. **Product Hunt 预发布**
   - 去 producthunt.com/upcoming
   - 创建 Coming Soon 页面
   - 积累订阅者

5. **Indie Hackers 群组**
   - 加入相关讨论
   - 在合适的帖子下分享

6. **LinkedIn**
   - 如果你是开发者，LinkedIn 上分享"我做了什么"
   - 受众不同，可能有意想不到的效果

### 第三优先级（持续做）

7. **SEO 内容**
   - 写一篇博客："How I Validate a SaaS Idea in 3 Days"
   - 落地页加 /blog 路径

8. **合作互推**
   - 找其他独立开发者互相推广
   - 换 landing page 链接

---

## 📊 追踪数据

你需要设置：

1. **Vercel Analytics**（免费）
   - 看访问量

2. **Google Analytics**（免费）
   - 看用户行为

3. **Hotjar**（免费版）
   - 看用户点击热力图

---

## ✅ 检查清单

- [ ] 代码上传到 GitHub
- [ ] Vercel 部署成功
- [ ] 有自定义域名（可选，.vercel.app 也能用）
- [ ] 测试留邮箱功能
- [ ] 发了第一条推广 Twitter
- [ ] 设置了 Analytics

---

有问题随时问我！