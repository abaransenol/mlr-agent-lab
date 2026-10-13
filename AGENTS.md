# Agent Guidelines & Working Rules

All AI agents working in this repository must strictly adhere to the following rules:

1. **Context & Orientation**:
   - Always read `README.md` and `PLAN.md` before taking action or planning tasks.
   - Keep `PLAN.md` updated with completed progress and immediate next steps.

2. **Isolated Environment**:
   - Always use a dedicated Python virtual environment (`.venv`) managed via `uv`.
   - Never install packages into the system/global Python environment.
   - Execute commands using `uv run <command>` or within the activated virtual environment.

3. **Verification Before Completion**:
   - Always run and verify all checks, scripts, and tests before reporting a task as completed.
   - Never assume code works without executing and validating the output.

4. **Run Logging**:
   - Document significant runs and experiments in `RUNS.md`, noting the model (from `/status`), what was requested, and verification results.
