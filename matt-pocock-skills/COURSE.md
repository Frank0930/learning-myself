# Matt Pocock Skills 課程目錄

目標：先讀懂並使用 Matt Pocock 的既有技能，再比較它們的 `SKILL.md` 設計，最後仿作一個能交給團隊使用的技能。技能清單依 [官方 README 的 Reference](https://github.com/mattpocock/skills#reference)（2026-09-29 核對）；官方更新時應重新核對。

## 學習方式

每個技能都用同一組問題檢查：**解決什麼問題？何時使用？需要什麼輸入？會產出什麼？能與哪些技能接上？** 每組學完都有情境題，請你先選技能與說理由，我再給回饋。遇到設計細節時，先觀察原技能如何寫，不急著自己寫技能。

## 第一階段：向原作學習（25 個既有技能）

| 單元 | 技能 | 本單元要能做到 |
| --- | --- | --- |
| 0. 全貌與起步 | `ask-matt`、`setup-matt-pocock-skills` | 知道怎麼找適合的流程，以及新專案啟用技能前要設定什麼。 |
| 1. 釐清意圖與語言 | `grill-me`、`grilling`、`grill-with-docs`、`domain-modeling`、`to-questionnaire`、`wait-what` | 區分即時追問、記錄專案術語、向他人取得決策，以及重新解釋。 |
| 2. 探索與規劃 | `triage`、`research`、`prototype`、`to-spec`、`to-tickets`、`wayfinder` | 從未知問題走到可執行規格，並判斷何時需要原型或長期決策地圖。 |
| 3. 實作與驗證 | `implement`、`tdd`、`diagnosing-bugs`、`code-review`、`resolving-merge-conflicts` | 區分實作、測試、診斷、審查與衝突處理各自的回饋迴圈。 |
| 4. 架構與交接 | `codebase-design`、`improve-codebase-architecture`、`wizard`、`handoff`、`teach` | 判斷模組設計、定期架構盤點、人工操作指引與知識交接的時機。 |
| 5. 原作的寫作方法 | `writing-for-agents` | 把這個既有技能當作案例讀懂，為下一階段做準備。 |

所有技能的逐一用途、使用時機與官方文件連結，見[25 個技能速查表](reference/skill-map.html)。每個單元會挑真實案例深入讀官方 `SKILL.md`，並用相似情境比較容易混淆的技能。完成第一階段的標準是：看到一個陌生的團隊情境，能選出起始技能，說明不選相鄰技能的理由，並接出合理的後續流程。

## 第二階段：拆解原作怎麼設計

回頭比較多份官方 `SKILL.md`：frontmatter 與呼叫方式、`description` 的觸發條件、正文的步驟與完成標準、參考文件的分層、技能之間的組合。先前建立的[第 2 課](lessons/0002-read-a-skill-file.html)、[第 3 課](lessons/0003-description-as-trigger.html)、[第 4 課](lessons/0004-completion-criteria.html)會在這裡複習；目前暫停第 4 課練習。

## 第三階段：模仿與教團隊

選一個你們團隊反覆遇到的真實問題，先仿照最相近的官方技能寫出小型 `SKILL.md`；用幾個情境檢查它是否會在對的時候被使用、是否能照步驟完成，再整理成可供團隊演練的案例。這階段才開始自己設計技能。

## 目前位置

- 已完成：[第 1 課：先判斷問題，再選技能](lessons/0001-choose-the-right-skill.html)，並成功選出 `grill-with-docs → to-spec → to-tickets`。
- 已預習：第 2–3 課關於 `SKILL.md` 入口與觸發描述；它們會留到第二階段整合。
- 已完成：[原作實例：grill-with-docs](lessons/0005-grill-with-docs-case-study.html)，能辨識決策與領域語言需同步釐清的情境。
- 已完成：[原作實例：grilling 的提問順序](lessons/0006-grilling-decision-frontier.html)，能判斷前提已具備的問題可同輪詢問。
- **下一步：**[原作實例：domain-modeling 留下什麼](lessons/0007-domain-modeling-artifacts.html)。
