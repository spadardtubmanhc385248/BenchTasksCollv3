# Final pool

Consolidated copy of every task marked **implemented** in the Notion **Task Tracker** (`Task Status Table`).

## Admission check

Requirement source: `tasks/examples/example-task` (readme.txt and the per-file requirements).
- `docs/task.md` and `docs/agent_system_prompt.md` exist, are non-empty and written entirely in English.
- `docs/user_system_prompt.md`, when present and non-empty, must be written entirely in English.
- `evaluation/main.py` must exist; `preprocess/main.py`, `initial_workspace/` and `groundtruth_workspace/`
  are optional and are copied whenever the developer supplied them.
- If a `task_config.json` is present, `needed_mcp_servers` must be non-empty and `needed_local_tools`
  must be non-empty and contain `claim_done`.
- Apart from those content requirements, only file existence is checked.

77 tasks are included; each directory is a verbatim copy of the task on its developer branch.

## Tasks by developer

- **fan-dev** (4): coupon-manager, discount-calculator, loyalty-program, price-tracker
- **gyy** (6): blog-engine, cms-builder, content-scheduler, robots-handler, social-publisher, tag-manager
- **haoze** (4): media-organizer, streaming-service, subtitle-generator, video-trimmer
- **jl_dev** (5): canvas-grade-automation, customer-feedback-processor, email-classification-system, inventory-management, pdf-report-generator
- **junteng_dev** (8): booking-system, calendar-sync, contact-manager, help-desk, order-processor, product-catalog, reminder-service, shipment-tracker
- **junxian_dev** (3): qr-generator, social-connector, translation-api
- **lueyang-dev** (8): activity-logger, client-portal, crm-system, deal-manager, email-campaign, follow-up-reminder, sales-pipeline, territory-manager
- **lv** (7): analytics-dashboard, chat-bot, feedback-collector, personalization-service, sentiment-analyzer, survey-builder, voice-processor
- **ruige** (6): canvas-automation, data-analytics, expense-tracker, file-manager, log-analyzer, web-crawler
- **wenshuo-dev** (4): cache-optimizer, image-processor, scheduler, search-engine
- **xiaochen_dev** (7): backup-utility, deployment-tool, error-tracker, health-monitor, monitoring-agent, security-scanner, status-checker
- **yuxuan-dev** (5): asset-optimizer, content-manager, network-analyzer, sync-service, task-scheduler
- **yuzhen-dev** (6): alert-system, data-validator, form-builder, invoice-generator, payment-processor, permission-manager
- **zhaochen** (4): certificate-manager, load-balancer, storage-manager, template-engine

## Source branch heads

| Developer branch | Commit |
| --- | --- |
| `fan-dev` | `8b90f34538e4e106eba103265efaa9a456be498c` |
| `gyy` | `9612ffff37072726292c77df0f4c6db2f8df1bbb` |
| `haoze` | `e0072cf979548c56984072cd76f529c7beea59b2` |
| `jl_dev` | `4e2b63f5dafce88b60886ed6e6af7bd9a8966296` |
| `junteng_dev` | `4ab0c5415824d799c3457a26482f9b794c7e9e93` |
| `junxian_dev` | `96bbc11b6fc701d07d961aaf070c434fccd1794f` |
| `lueyang-dev` | `bf8b9a1d25edd81b158db0bb7f49d8624348e74d` |
| `lv` | `0be3288e0fd4ae1f241d3ce9cc1c864ae2606d37` |
| `ruige` | `a6f3fba387f68acaf6517803e88b40a4a3c52658` |
| `wenshuo-dev` | `d11080ed8d65fb72eb32d9353cb20844b593f9e8` |
| `xiaochen_dev` | `20bfc73490dcf4029b92123b6055e076b7eb5dfa` |
| `yuxuan-dev` | `e82c8295f9506ced6862ab7f39048a731b48beb4` |
| `yuzhen-dev` | `c68265dafe0a0eccc6e183ff96d1a3e5591a3d8b` |
| `zhaochen` | `b5f9cc4f79bb9218e40c0293ab9ec4e90352a626` |
