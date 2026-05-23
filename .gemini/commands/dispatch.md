# dispatch 指令

## 目的
由 COO 拆解任務並分派給指定的 Specialist。

## 動作
1. COO 根據專案階段（診斷/施壓/轉譯）撰寫任務描述。
2. 將指令寫入 `shared-memory/arbitration-log/sessions/<timestamp>.md`。
3. 觸發對應的 Specialist 開始工作。
