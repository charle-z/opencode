# TRUSTED LINUX WORKCELL

- Profile: linux-workcell
- Mode: dev
- Network posture: trusted_host_shared_network
- Runtime ID: mr_014486fbe776c5c253a82f957882f2dc
- Workspace: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_71f48a414d4d512b4da886dd04a429c8
- Evidence: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_71f48a414d4d512b4da886dd04a429c8
- Durable state: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_71f48a414d4d512b4da886dd04a429c8/.mcp-devbox/current-state.md
- Tool prefix: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_71f48a414d4d512b4da886dd04a429c8/.mcp-devbox/tools
- Cache prefix: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_71f48a414d4d512b4da886dd04a429c8/.mcp-devbox/cache
- Runtime prefix: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_71f48a414d4d512b4da886dd04a429c8/.mcp-devbox/runtime

## Goal

Resume the registered workspace using its local trusted contract and persistent checkpoint. Perform only operations authorized by the local contract. Keep local-only values local. Return a bounded safe status.

## Resume state

Read and validate the real state before continuing. Do not blindly trust this checkpoint.

# Current State — Development

- Objective: pending execution
- Changes made: none
- Tests: not run
- Active processes: none
- Blocker: none
- Next action: inspect the workspace and validate the requested goal


## Runtime terminal checkpoint

- Runtime state: timeout
- Container cleanup: complete: runtime-labelled resources removed
- Active runtime process group: stopped
- Durable checkpoint: /home/charles/workspaces/.mcp-devbox-worktrees/opencode-oss/wt_71f48a414d4d512b4da886dd04a429c8/.mcp-devbox/current-state.md


## Operational contract

This is the default development mode. Work only inside the selected workspace. You may modify the repository, install user-scoped dependencies, run tests, build rootless containers, start temporary services, and debug. Do not add hacking instructions. Update .mcp-devbox/current-state.md after material progress, before completion, before cancellation, and near timeout. At completion state exactly where the durable checkpoint is stored.
