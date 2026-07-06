# ruguo-plan-guide — 如菓員工手冊（單站雙分頁：施工計畫＋工地日報）

## Zeabur Deployment（主要載體，2026-07-06 起）
- Project ID: 6a41173bd525b066f2475268（building-tracker）
- Service ID: 6a4b875b7e05aa801c1a6c19（ruguo-manual）
- 更新流程：改 index.html → `npx zeabur@latest deploy --project-id 6a41173bd525b066f2475268 --service-id 6a4b875b7e05aa801c1a6c19 --json`（NEVER 省略 service-id，會建重複服務）

## GitHub Pages（備援，歷史網址）
- repo FennixChou/ruguo-plan-guide；2026-07-06 GP legacy builder repo 級卡死 40+ 分鐘（重觸發/空 commit/build_type 切換皆無效）故遷 Zeabur。GP 恢復後 index.html 改轉址頁指向 Zeabur 網址。
- 同日 ruguo-daily-log-manual（日報手冊舊站）已 revert 轉址恢復原內容，等主站穩定後再改轉址。
