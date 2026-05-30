# AGENTS.md — ccktaiwan
# Version: 1.0 | 2026-05-30
# Governance Reference: prospera-constitution-governance v3.0
# Pipeline Reference: prospera-infra-ci v3.5

## 1. REPO IDENTITY
Repo: ccktaiwan/ccktaiwan
Ring: Ring 0 — Profile
Role: GitHub 帳號 profile repo，Prospera 生態系公開門面，不可改名

## 2. AGENT RULES

### PERMIT
- 讀取 profile 內容
- 更新 README.md 展示資訊
- 維護 pinned repo 清單

### ESCALATE
- 修改對外聲明或品牌定位 → J2
- 變更帳號設定 → J3

### BLOCK
- 刪除或封存此 repo
- 儲存任何機密資訊或 API key

## 3. Decision Engine
Q1 Should / Q2 Can / Q3 Fit / Q4 Profit
任一 BLOCK → 整體 BLOCK
任一 ESCALATE → 觸發對應 J點

## 4. J 點
J1 技術確認 / J2 品質審閱 / J3 架構決策

# Version: 1.0 | 2026-05-30
# Human-Reviewed: pending
