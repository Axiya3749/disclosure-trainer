# 披露段落训练器 · Disclosure Segment Trainer

给中英口译员练固定套话用的小工具。银行、保险这类电话里，代表会用很快的语速念一整段标准声明，这些段落每次都一样，所以正确的练法不是现场翻，是提前练熟到脱口而出。

工作时不能使用任何工具，所以这个训练器只用在通话之前。

**在线使用：** https://axiya3749.github.io/disclosure-trainer/

## 功能

- **练习模式** — 中文默认盖住，自己先口译出来，再点开对照
- **跟读模式** — 浏览器朗读英文，语速 0.5x 到 1.6x 可调，从慢练到超过真实语速
- **已掌握归档** — 练熟的段落点一下就收起来，列表永远只剩还不熟的
- 按类别筛选、搜索、自己增删改、导出 JSON 备份

## 内容从哪来

只用公开来源，不用任何真实通话内容。

1. **CFPB 信用卡协议数据库** — https://www.consumerfinance.gov/credit-cards/agreements/
   收录 600 多家发卡机构的协议全文。CARD Act 强制要求公开，可自由取用。
   这是最好的来源。
2. **CFPB 示范表格（Know Before You Owe）** — 政府发布的标准披露模板。
3. **各银行官网公开的持卡人协议、隐私声明、费用表。**

建议去掉具体品牌名和产品名，改成通用说法。既降低风险，材料也更通用。

**不收录任何客户私人信息**，也不使用真实通话记录作为素材。

## 使用

单个 HTML 文件，无依赖。打开网页即可，或者下载 `index.html` 双击打开。数据存在浏览器 localStorage 里，建议定期点「导出」备份。

---

A small tool for Mandarin/English interpreters to drill the scripted
disclosure passages that come up in banking and insurance calls. These
passages are identical every time and are read at speed, so the right
way to handle them is to memorize a vetted rendering in advance rather
than translate them live.

Single HTML file, no dependencies, no build step.
