## Comparison between uv and pip
what they are, how they differ, and why you might use one over the other 👇
# ---- pip ----
→ pip is Python’s standard package manager used to install, uninstall, and manage Python packages from PyPI.
→ It comes bundled with Python by default.
→ It installs packages into the currently active environment (e.g., a virtualenv).

💡 But pip does not manage environments itself — you need separate tools like venv or virtualenv for that.

# ---- uv ----
✔ uv is a modern, Rust-based Python package & project manager that aims to replace not just pip, but also related tooling (like environment managers and dependency locking).
✔ Automatically handles virtual environments (uv venv)
✔ Uses a lock-file for reproducible environments
✔ Can manage Python versions, envs, and dependencies in one tool

# Main differences explained
📌 Scope of functionality
→ pip focuses on just package installation and removal.
→ uv does package installation + environment management + dependency locking under one tool.

# Summary
→ pip is the traditional, default way to install Python packages.
→ uv is a new all-in-one package & environment manager that replaces pip and adds features like faster installs, env management, and dependency locking — making workflow simpler and often faster.