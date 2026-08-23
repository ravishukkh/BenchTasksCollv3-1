# Final Pool

This directory collects all tasks that are implemented in the `BenchTasksCollv3` project,
tracked on our Notion page `Task Tracker`. Each subdirectory is a task whose
development status is `implemented`; see the Notion Task Tracker page for the
full list of tasks (implemented / implementing) with their implementors.

Rules for tasks under `tasks/finalpool`:
- `docs/task.md` must be non-empty and all English (no Chinese)
- `docs/agent_system_prompt.md` must be non-empty and all English (no Chinese)
- `docs/user_system_prompt.md` is optional, but if non-empty it must be all English
- `evaluation/main.py` and the other referenced files only need to exist

Implemented tasks in this pool (checked against the newest commit of every
developer branch that added new tasks):

- loyalty-program (implementor: fan-dev, branch fan-dev, commit 8b90f34)
- discount-calculator (implementor: fan-dev, branch fan-dev, commit 8b90f34)
- tag-manager (implementor: gyy, branch gyy, commit 9612fff)
- sitemap-generator (implementor: gyy, branch gyy, commit 9612fff)
- robots-handler (implementor: gyy, branch gyy, commit 9612fff)
- media-organizer (implementor: haoze, branch haoze, commit e0072cf)
- streaming-service (implementor: haoze, branch haoze, commit e0072cf)
- customer-feedback-processor (implementor: jl_dev, branch jl_dev, commit 4e2b63f)
- inventory-management (implementor: jl_dev, branch jl_dev, commit 4e2b63f)
- customer-portal (implementor: junteng_dev, branch junteng_dev, commit 4ab0c54)
- help-desk (implementor: junteng_dev, branch junteng_dev, commit 4ab0c54)
- social-connector (implementor: junxian_dev, branch junxian_dev, commit 96bbc11)
- territory-manager (implementor: lueyang-dev, branch lueyang-dev, commit bf8b9a1)
- client-portal (implementor: lueyang-dev, branch lueyang-dev, commit bf8b9a1)
- crm-system (implementor: lueyang-dev, branch lueyang-dev, commit c524b53)
- lead-tracker (implementor: lueyang-dev, branch lueyang-dev, commit c524b53)
- survey-builder (implementor: lv, branch lv, commit 0be3288)
- analytics-dashboard (implementor: lv, branch lv, commit 0be3288)
- web-crawler (implementor: ruige, branch ruige, commit a6f3fba)
- log-analyzer (implementor: ruige, branch ruige, commit a6f3fba)
- cache-optimizer (implementor: wenshuo-dev, branch wenshuo-dev, commit d11080e)
- scheduler (implementor: wenshuo-dev, branch wenshuo-dev, commit d11080e)
- status-checker (implementor: xiaochen_dev, branch xiaochen_dev, commit 20bfc73)
- health-monitor (implementor: xiaochen_dev, branch xiaochen_dev, commit 20bfc73)
- sync-service (implementor: yuxuan-dev, branch yuxuan-dev, commit e82c829)
- certificate-manager (implementor: zhaochen, branch zhaochen, commit b5f9cc4)
- storage-manager (implementor: zhaochen, branch zhaochen, commit b5f9cc4)

Tasks that are still `implementing` and were deliberately NOT copied into the
pool, because `docs/task.md` / `docs/agent_system_prompt.md` contain Chinese
text or required files are missing:

- currency-converter (junxian_dev) - docs/task.md contains a 中文描述 section
- insights-engine (lv) - docs/agent_system_prompt.md contains a 系统提示 section
- audit-logger (yuzhen-dev) - docs/agent_system_prompt.md contains a 系统提示 section
- resource-monitor (yuzhen-dev) - docs/agent_system_prompt.md contains a 系统提示 section
