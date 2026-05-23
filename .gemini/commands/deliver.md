# deliver 指令

## 目的
整合最終產出並生成《品牌 AI 靈魂導航法典》。

## 動作
1. 讀取所有 `shared-memory/work-in-progress/` 下的產出。
2. 調用 `coo` 進行最終校對與整合。
3. 生成 `shared-memory/client/current/codex.md`。
4. 將資料移至 `shared-memory/client/archive/`。
