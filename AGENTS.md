# AGENTS.md

## Purpose

本 Wiki 用於建立、維護與擴充研究知識庫。

Agent 必須：

- 自主搜尋與整理資料
- 建立可追溯知識結構
- 評估來源品質
- 保存研究過程
- 維護研究缺口
- 產出附引用簡報
- 定期執行知識庫健檢

禁止：

- 虛構來源
- 虛構數字
- 虛構引文
- 虛構執行紀錄
- 將相關性描述為因果關係
- 宣稱完成未實際執行之操作

---

# Wiki Structure

```text
wiki/
├── index.md
├── overview.md
├── synthesis.md
├── research-gaps.md
├── contradictions.md
├── log.md
├── sources/
├── concepts/
├── topics/
├── comparisons/
├── methods/
├── presentations/
└── maintenance/
```

## Page Types

### Source Page
每個來源建立獨立頁面。
建議檔名：
sources/YYYY-Author-Title.md
包含：
- 標題
- 作者
- 發布單位
- 年份
- 來源類型
- 網址
- 查閱日期
- 全文取得狀態
- 摘要
- 研究方法
- 樣本資訊
- 主要發現
- 限制
- 證據等級
 
### Topic Page
每個研究主題建立獨立頁面。
建議內容：
- 研究問題
- 核心概念
- 支持證據
- 相反證據
- 研究限制
- 相關來源
- 研究缺口
 
### Comparison Page
比較不同研究結果。
包含：
- 比較對象
- 樣本差異
- 方法差異
- 共同發現
- 差異發現
- 可能原因
- 可支持結論
- 不可支持結論
 
### Presentation Page
保存簡報內容。
包含：
- 頁碼
- 標題
- 核心論點
- 重點
- 支持證據
- 引用
- 講稿
- 視覺建議
 
## YAML Frontmatter
---
title:
type:
status:
created:
updated:
evidence_level:
source_count:
tags:
---
type 可為：
- source
- topic
- concept
- comparison
- method
- presentation
- maintenance
 
## Internal Link Format
使用 Obsidian 標準格式：
[[頁面名稱]]
來源頁：
[[sources/2024-example-study]]
主題頁：
[[topics/戀愛態度]]
 
## Evidence Levels

### Level A
較強證據：
- 官方統計
- 大型代表性研究
- 多研究一致結果
- 適切研究設計

### Level B
中等證據：
- 正式學位論文
- 區域性研究
- 多個小型研究結果一致

### Level C
有限證據：
- 單校研究
- 小樣本研究
- 質性訪談
- 僅取得摘要

### Level D
議題線索：
- 媒體報導
- 專家評論
- 機構文章
- 未公開完整方法之調查
Level D 不得單獨支持核心研究結論。
 
## Source Import Workflow

### Step 1
搜尋來源：
1. 政府資料
2. 學術期刊
3. 博碩士論文
4. 研究機構報告
5. 調查報告
6. 媒體報導
7. 其他可追溯資料

### Step 2
評估來源：
- 身分
- 年份
- 樣本
- 地區
- 方法
- 研究限制

### Step 3
建立來源頁

### Step 4
更新主題頁

### Step 5
更新索引

### Step 6
更新日誌
 
## Research Workflow
收到任務後依序執行：
1. 搜尋資料
2. 評估來源
3. 匯入來源
4. 更新 Wiki
5. 交叉分析
6. 更新研究缺口
7. 產出成果
不得要求使用者指定流程。
 
## Cross-study Analysis Rules
分析：
- 共同發現
- 差異發現
- 定義是否一致
- 樣本是否可比較
- 方法是否可比較
- 多來源支持程度
- 研究缺口
結論必須分類：
- 直接證據
- 跨研究綜合
- 合理推論
- 尚無法判定
 
## Presentation Workflow
預設：
- 繁體中文
- 16:9
- 12頁
- 10~15分鐘
簡報結構：
1. 研究主題與核心問題
2. 研究背景與重要性
3. 資料來源與方法
4. 愛情定義
5. 戀愛動機
6. 伴侶選擇
7. 家庭與校園影響
8. 社群媒體影響
9. 國高中比較
10. 世代或群體差異
11. 研究限制與矛盾
12. 結論與參考資料
若證據不足：
改為：
- 證據缺口
- 研究不足
- 未來研究方向
不得虛構內容。
 
## Index Rules
index.md 必須包含：
- 頁面連結
- 一句摘要
- 類型
- 最後更新日期
- 來源數量
- 證據狀態
分類：
- Overview
- Sources
- Concepts
- Topics
- Comparisons
- Methods
- Presentations
- Research Gaps
- Maintenance
 
## Log Rules
log.md 採追加式紀錄。
格式：

```text=
## YYYY-MM-DD

### Action

內容說明

### Result

完成事項

### Next
```

### 後續工作
不得記錄未實際執行操作。
 
## Maintenance Workflow
定期檢查：
- 矛盾主張
- 過時內容
- 缺少引用
- 無法追溯數字
- 重複頁面
- 孤立頁面
- 遺漏連結
- 研究缺口
結果存放：
maintenance/
並更新：
log.md
 
## Citation Rules
所有重要主張必須引用來源。
格式：
（作者，年份）
（機構，年份）
完整書目盡可能包含：
- 作者
- 年份
- 標題
- 出版單位
- DOI
- URL
- 查閱日期
禁止：
- 研究顯示
- 有資料指出
- 根據調查
- 專家認為
除非立即附上具體來源。
 
## Error Handling

### 資料不足
明確標示：
未找到足夠且可核實的證據。

### 無法取得全文
標示：
僅取得摘要，未核對全文。

### 來源互相矛盾
建立：
contradictions.md
分析差異來源。

### 工具失敗
不得宣稱已完成。
應提供：
- 已完成項目
- 未完成項目
- 替代成果
 
# Final Operating Principles
1. 優先使用原始來源
2. 完整揭露限制
3. 保留研究矛盾
4. 不過度推論
5. 不虛構任何內容
6. 維護索引與日誌
7. 保持可追溯性
8. 發現研究缺口即記錄
9. 優先更新 Wiki
10. 全程自主執行