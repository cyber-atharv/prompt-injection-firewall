# Changelog

All notable changes to prompt-injection-firewall are documented here.

### [2025-12-13]
- feat: implement verbose output mode for troubleshooting

### [2025-12-14]
- fix: resolve memory leak in idle connection reaper

### [2026-01-03]
- perf: minimize redundant heap allocations in hot loop

### [2026-01-29]
- fix: resolve race condition during concurrent worker initialization

### [2026-01-29]
- test: verify backward compatibility with legacy message format

### [2026-02-02]
- fix: correct endianness conversion in raw packet parser

### [2026-02-04]
- chore: update internal constants and clean up legacy comments

### [2026-02-12]
- docs: update license headers and author metadata

### [2026-03-05]
- fix: resolve memory leak in idle connection reaper

### [2026-03-10]
- style: format code according to style conventions

### [2026-03-14]
- fix: prevent duplicate event emission during rapid retry bursts

### [2026-03-28]
- test: implement mock service for end-to-end integration tests

### [2026-04-02]
- feat: add graceful shutdown signal handler (SIGINT/SIGTERM)

### [2026-04-18]
- feat: add graceful shutdown signal handler (SIGINT/SIGTERM)

### [2026-04-24]
- style: clean up trailing whitespace and fix alignment

### [2026-04-24]
- test: add fuzzing harness for packet decoding routine

### [2026-04-27]
- perf: optimize memory allocation in buffer pool

### [2026-05-12]
- refactor: extract validation logic into dedicated helper module

### [2026-06-05]
- feat: implement verbose output mode for troubleshooting

### [2026-07-20]
- refactor: decouple configuration loader from runtime engine

### [2026-07-24]
- docs: add example configuration commands to quickstart guide

### [2026-07-28]
- fix: correct endianness conversion in raw packet parser

### [2026-09-05]
- fix: patch edge-case buffer truncation in stream reader

