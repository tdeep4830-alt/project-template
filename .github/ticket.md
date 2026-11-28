---
name: Ticket
about: 一張由 Architect 拆出嚟、可以獨立完成同驗收嘅工作
title: "T-XXX: "
labels: []
---

## 目標
<!-- 一句講清楚完成之後會有乜唔同 -->

## 範圍
- 可以改嘅檔案／目錄：
- 唔准改嘅檔案／目錄：

## 驗收條件
<!-- 每條都要可以客觀驗證，寫明點樣驗 -->
- [ ] 條件 1 —— 驗證方法：
- [ ] 條件 2 —— 驗證方法：

## 測試指令
```bash
pytest -q
```

## 依賴
- 要等邊張 ticket 先做得：
- 參考：PRD 第 _ 節、ARCHITECTURE 第 _ 節

## 負責
- Build：coder
- Audit：qa
