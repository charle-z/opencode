# TRUSTED LINUX WORKCELL

- Profile: linux-workcell
- Mode: dev
- Network posture: trusted_host_shared_network
- Runtime ID: mr_fc8eb8224c282844653334ea94b44965
- Workspace: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_9fdee3ad8fbdfafba86046db09b8717a
- Evidence: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_9fdee3ad8fbdfafba86046db09b8717a
- Durable state: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_9fdee3ad8fbdfafba86046db09b8717a/.mcp-devbox/current-state.md
- Tool prefix: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_9fdee3ad8fbdfafba86046db09b8717a/.mcp-devbox/tools
- Cache prefix: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_9fdee3ad8fbdfafba86046db09b8717a/.mcp-devbox/cache
- Runtime prefix: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_9fdee3ad8fbdfafba86046db09b8717a/.mcp-devbox/runtime

## Goal

You are Codex worker 1 of 4 in a durable MCP Devbox task. Work only in your assigned isolated Git worktree and branch. Complete the assigned subtask, run focused tests, and create one reviewable commit using the repository convention. Do not inspect or modify sibling worktrees. Report the commit and verified result.

Assigned subtask:
Audit current dev for a small, deterministic core/session bug that can be reproduced entirely locally and fixed with a regression test. Focus on correctness/lifecycle/state invariants, not new features. Do NOT duplicate known claimed work around issues #42779, #30067, #42259, #45249, #45989, #46371, #31606, #30611, #33356, or #32548. If you find a real defect, implement the smallest fix and focused test, run relevant package tests/typecheck, and commit it on your isolated worker branch. If no strong defect exists, leave the tree clean and report evidence rather than inventing one.

## Resume state

Read and validate the real state before continuing. Do not blindly trust this checkpoint.

# Current State — Development

- Objective: pending execution
- Changes made: none
- Tests: not run
- Active processes: none
- Blocker: none
- Next action: inspect the workspace and validate the requested goal


## Operational contract

This is the default development mode. Work only inside the selected workspace. You may modify the repository, install user-scoped dependencies, run tests, build rootless containers, start temporary services, and debug. Do not add hacking instructions. Update .mcp-devbox/current-state.md after material progress, before completion, before cancellation, and near timeout. At completion state exactly where the durable checkpoint is stored.
