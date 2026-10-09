### Slimane Chanchoul: AI and automation engineer

I automate the work that eats a team's week and repair AI systems that give answers nobody trusts: Excel VBA and Google Sheets automation, Python data pipelines, Claude MCP servers and agent skills, RAG and LLM fixes, machine-learning models. Every result below comes from a run you can replay.

**Proof**

| Project | Result | Where |
|---|---|---|
| Agent skill for NextBrowser (open-source AI browser) | Merged upstream in [PR #306](https://github.com/nextbrowser-oss/nextbrowser-app/pull/306) after recorded acceptance runs on Microsoft, GitHub and Google | [nextbrowser-app fork](https://github.com/slimaneoptic/nextbrowser-app) |
| RAG chatbot fix (case study, synthetic documents) | 20/30 -> 29/30 correct answers on the same documents, questions and model; outdated facts given as valid 3 -> 0; each version run twice | [rag-fix-case-study](https://github.com/slimaneoptic/rag-fix-case-study) · [case study](https://slimanechanchoul.com/rag-fix/) |
| Excel MCP server for Claude (demo, read-only, sandboxed) | A business question on a 2,000-row synthetic workbook answered in 30.5 s with 8 tool calls; 25 of 26 claims correct; 81 tests | [excel-mcp-server](https://github.com/slimaneoptic/excel-mcp-server) · [demo](https://slimanechanchoul.com/mcp-excel/) |
| Google Sheets one-click weekly report (Apps Script, demo on synthetic orders) | 500 raw orders -> 464 clean, 34 flagged with reasons, live FX, chart, email; 31 tests | [sheets-weekly-report](https://github.com/slimaneoptic/sheets-weekly-report) · [demo](https://slimanechanchoul.com/sheets-report/) |
| Agent workflow runner (demo) | Retries with backoff, crash recovery from checkpoints, code-checked answers, human review, cost per run; screenshots from real runs | [agent-workflow-runner](https://github.com/slimaneoptic/agent-workflow-runner) · [demo](https://slimanechanchoul.com/agent-workflow-demo/) |
| Demand forecast and reorder planner (demo) | 4 models backtested per product, reorder plan, CP-SAT budget optimizer over 300 scenarios per product | [demand-planner](https://github.com/slimaneoptic/demand-planner) · [live app](https://slimanechanchoul.com/planner/) |
| Route optimizer and AI shift scheduler (demos) | 11-32% lower daily cost than a manual plan on the sample cities; a roster that explains every gap | [route-optimizer](https://github.com/slimaneoptic/route-optimizer) · [shift-scheduler](https://github.com/slimaneoptic/shift-scheduler) |

Also: a website chatbot that answers only from a site or PDFs with citations ([site-chatbot](https://github.com/slimaneoptic/site-chatbot)), and a 29-fps road-perception prototype ([video](https://slimanechanchoul.com/vision/)).

Each repo has a README to reproduce the numbers; most have a `tests/` folder.

Website: https://slimanechanchoul.com · [Hire me on Upwork](https://www.upwork.com/freelancers/~01d6ae0f1a06a43ac0)
