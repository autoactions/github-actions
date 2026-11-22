# GitHub Actions

Personal GitHub-hosted Tasks and temporary Sessions for Workflow MCP.

Runtime behavior is defined by the workflows and tests. Production execution and authorization are managed separately.

Ubuntu Session keeps the immutable Release Agent as its default. Its explicit
session_agent=rust-candidate choice is Linux-only acceptance mode, builds the
Rust Candidate from a reviewed commit pin, and starts it as the sole Session
Agent. Candidate mode requires its exact GitHub Action contract to be approved
in the published Workflow before it can run.
