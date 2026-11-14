# Changelog

  heritage description) that falls outside this repo's scope (dining/ordering
  rules, not cultural description). Reverted; repo back at 39 entries. Net 0.
  Quality rule first, numbers never padded (same precedent as 2026-11-10).

## 2026-11-14 — incremental sync from published articles

- 1 entries added from official-source sentences in newly published articles; 0 candidates skipped (unreachable/non-official/duplicate source).

## 2026-11-14 — DB backfill

- 3 entries appended from the site's curated `verified_facts` (source URLs already re-checked against official pages at DB ingest). Append-only, deduped by claim+source.

## 2026-11-13 — incremental sync from published articles

- 1 entries added from official-source sentences in newly published articles; 0 candidates skipped (unreachable/non-official/duplicate source).

## 2026-11-11 — expanded with official-source facts

- 4 entries added directly from official Chinese government sources (rail: NRA/PSB Announcement No.1 items catalogue; food: Anti-Food-Waste Law; payment: Interim Regulation on Express Delivery; festival: holiday-decision amendment). Total now 43.

## 2026-11-10
- 建仓：从 food 主题 15 篇已发布英文文章的官方外链句 / FAQ 数字句 / 官方源直采中，逐条 curl 验证官方源后收录 39 条事实（点餐流程、买单与小费、过敏与食品标签、街头小吃、官方认定）。
- 口径：与铁路仓一致——可引用资产，不计外链成绩、不进三个数、不推广。
- 官方源变更时按月度维护任务（每月 10 日 09:30）重核 source_url，内容变化即按新官方值改 claim/figure 并记本文件一行。
