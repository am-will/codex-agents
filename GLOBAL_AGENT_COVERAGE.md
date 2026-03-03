# Global Agent Coverage Check

Comparison date: 2026-03-03

Method:
- Compared role names from `~/.codex/agents/*.toml` against this repo's `agents/**/*.toml`.
- Normalization used: lowercase, `_` -> `-`, and removal of known source suffixes (`-wshobson`, `-davepoon`, `-vijaythecoder`, `-hesreallyhim`, `-0xfurai`).

## Summary
- Global roles scanned: 27
- Covered in repo by normalized name: 1
- Not covered by normalized name: 26

## Covered
- `debugger.toml`

## Not Covered
- `accessibility-wcag-auditor.toml`
- `api_designer.toml`
- `architect.toml`
- `backend.toml`
- `content_writer.toml`
- `data_pipeline.toml`
- `devops.toml`
- `documenter.toml`
- `frontend.toml`
- `migrator.toml`
- `mobile.toml`
- `performance.toml`
- `plan-checker.toml`
- `refactorer.toml`
- `reviewer.toml`
- `scout.toml`
- `security.toml`
- `smart_contract.toml`
- `sparky.toml`
- `tdd_test_writer.toml`
- `worker_high.toml`
- `worker_medium.toml`
- `worker_mini.toml`
- `worker_spark_high.toml`
- `worker_spark_xhigh.toml`
- `worker_xhigh.toml`

## Worker Copies Added
Copied from `~/.codex/agents` into `agents/workers/` (copy-only, originals retained):
- `worker_high.toml`
- `worker_medium.toml`
- `worker_mini.toml`
- `worker_spark_high.toml`
- `worker_spark_xhigh.toml`
- `worker_xhigh.toml`
