# SDGs DAO Contracts

一個台灣在地致力於 SDGs 發展的 DAO

## ??

- DAO 治理權合約
- ERC721
- 初期發行 1,000 份
- 持有此 NFT 即代表有權參與 DAO 治理，視為 DAO 治理權人

### 發行佔比

- 50% 業界專家
- 30% 公開發行
- 20% 項目方

### 治理權

- 參與表決募資提案通過與否，通過即表示能在募資池合約中創建募資池

### 未來計畫

- 參與 KYC 認證提案人

## SDGsDAO

- DAO 治理合約
- 使用 Openzeppelin Governance 合約庫合約
- DAO 提案、投票、取消、執行等操作合約

### 提案

- 任何人皆可為募資提案人，可於此發起募資提案

## Timelock

- DAO 代理執行合約
- 使用 Openzeppelin Governance 合約庫合約
- 治理合約提案通過後，由此合約代理執行

## ActionCenter

- 募資池合約
- 核心被治理合約，其操作僅能透過 DAO 執行合約操作
- 紀錄募資案、接收募資金額

## (收據合約)

- ERC721
- 參與募資案的贊助人獲得最終收據 NFT
