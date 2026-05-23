# onboard-client 指令

## 目的
啟動新客戶審查流程（階段 1）。

## 動作
1. 讀取 `shared-memory/client/current/brief.md`。
2. 調用 `coo` agent 進行「門檻防禦」審查。
3. 若通過，則建立專案目錄並指派 `chaos-surveyor`。
4. 若不通過，生成拒絕信。
