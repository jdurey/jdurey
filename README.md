# Joshua Durey - AI Evaluation & Automated Learning Systems Architect

**M.A. Applied Linguistics | Founder, Human Creative**

I build plain-code gates, multi-model grading panels, and lesson compilers. I ran 52,167 multi-agent sessions on a prior US learning contract and shipped 16,000+ QTI 3.0 items alongside 1,000+ narrated lessons. Most AI pipelines look clean in logs until you test the output by hand. And to be fair, automation only covers the repeatable half of teaching and operations, so every tool here fails closed when models disagree and hands edge cases back to a human. I'm a US citizen working remotely in English.

## Talk to My AI Twin or Run a Live Workflow Audit

- [Talk to my 3-minute AI video twin](https://jdurey.github.io/interview/) on my cloned voice. Ask about my 88,000-call API audit while the side panel pulls up SHA-256 receipts.
- [Run a live 3-vendor workflow or JD diagnostic](https://jdurey.github.io/#diagnostic) to see where your team's queue actually waits before you spend a dollar on API tokens.
- [Book a 20-minute scope call](https://cal.com/joshua-durey-wqgvgp/20-min-scope-call) if you're hiring or scoping an eval build.

## New Print Book, 65-Min Video Masterclass & `$12.99` Practice Exams (Live Now)

- **Print Paperback (`$24.99` on Amazon)** - [*AI for Corporate Training & Instructional Design: The UbD Glass-Box Playbook*](https://www.amazon.com/dp/B0HRQFWFPR) covers SOP-to-SCORM 1.2 builds, blind-solver quiz checks, and LMS rollouts (ISBN `9798142559005`, ASIN `B0HRQFWFPR`).
- **65-Min Udemy Video & Code-Lab Masterclass (`$12.99` through Dec 15, 2026)** - [*AI Corporate Training: UbD SOP-to-SCORM & Video Factory*](https://www.udemy.com/course/ai-corporate-training-ubd-sop-to-scorm-video-factory/?couponCode=MASTER2026_SCORM) walks through 14 video and Python code-lab lessons (`81%` off list `$69.99`, coupon `MASTER2026_SCORM`) turning policy docs into blind-verified LMS packages, QTI banks, PDFs, and 1080p modules.
- **Udemy Scenario Exams (`$12.99` through Dec 15, 2026)** - [*Production LLM Evals & Multi-Agent Ops (40 Scenario Questions)*](https://www.udemy.com/course/production-llm-evals-multi-agent-ops-practice-exams/?couponCode=LAUNCH2026_EVALS) tests 6-rung cost routing, silent token cutoffs, and multi-vendor grading (`LAUNCH2026_EVALS`). [*AI Instructional Design & SOP-to-SCORM Practice Exams*](https://www.udemy.com/course/ai-instructional-design-sop-to-scorm-practice-exams/?couponCode=LAUNCH2026_SCORM) tests backwards design and answer-leak traps (`LAUNCH2026_SCORM`).
- **Self-Serve Code Kits on Whop** - Grab the [`$99` Corporate SOP-to-SCORM & Video Factory](https://whop.com/checkout/plan_y1ACgqNYGtul8/) to compile policy PDFs into SCORM 1.2 zips, QTI banks, and 1080p lessons, or the [`$79` Enterprise AI Eval & 6-Rung Cost Router Kit](https://whop.com/checkout/plan_lGsdWjQsePkvO/) for my 4-vendor judge harness and local-to-cloud token router.

## Selected Empirical Benchmarks (`56` Open Case Studies Across `88,000` API Calls at [jdurey.github.io](https://jdurey.github.io/))

No model ever touches the labels here. Each harness plants known bugs in code first, then checks if the grader catches them.

- [`telemetry-gates`](https://github.com/jdurey/jdurey.github.io/tree/main/harnesses/telemetry-gates) ([case study](https://jdurey.github.io/work/telemetry-gates/)) checked 88,000 real LLM API calls across 12 models. Only 7 threw HTTP errors, while 324 hit token caps and returned broken JSON under a 200 status.
- [`judge-trust`](https://github.com/jdurey/jdurey.github.io/tree/main/harnesses/judge-trust) ([case study](https://jdurey.github.io/work/judge-trust/)) tested Claude, GPT, Gemini, and Grok grading broken items blind, where single models passed 10% of broken work from their own vendor until a two-vendor panel drove false passes to 0%.
- [`feedback-integrity`](https://github.com/jdurey/jdurey.github.io/tree/main/harnesses/feedback-integrity) ([case study](https://jdurey.github.io/work/feedback-integrity/)) strips out question stems. A blind-solver then tests whether wrong-answer feedback leaks the key.
- [`qwen-lens`](https://github.com/jdurey/qwen-lens) runs an Apple Silicon MLX logit lens on Qwen3.6-35B-A3B to test Anthropic's workspace paper on a Mac. Two of five findings held up, and three came back null. Both halves stay in the repo.
- [`agent-boundary`](https://github.com/jdurey/jdurey.github.io/tree/main/harnesses/agent-boundary) ([case study](https://jdurey.github.io/work/agent-boundary/)) plants canary tokens to test path fences and caught symlink and prefix leaks (`CVE-2025-53109` and `CVE-2025-53110`) that passed code review.
- [`skills`](https://github.com/jdurey/skills) and [`human-creative-mcp`](https://github.com/jdurey/human-creative-mcp) share 12 Claude Code skills built from 5,150 logged agent mistakes (MIT), plus my HTTP MCP server and [M5 Ultra token router tests](https://jdurey.github.io/m5-tribunal/).
