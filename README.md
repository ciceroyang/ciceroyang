# Hi, I'm Cicero Yang.

I build reliable AI agents and the tools around them.

I build small, open-source tools for the parts of agent engineering that are easy
to ignore and expensive to get wrong: context, evaluation, safety, and developer
experience.

## Selected work

### [agent-context-lens](https://github.com/ciceroyang/agent-context-lens)

A local, zero-API-key audit for agent instructions, skills, and MCP
configuration, including a bounded model of the Codex instruction chain.

It estimates instruction-context cost, catches duplicated instructions, flags
risky configuration, and produces a scorecard that can run in CI.

## Earlier: DeepSeek Harness community work (2026)

I built a small set of independent, open-source tools for the
[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) ecosystem:

- [dsh-doctor](https://github.com/ciceroyang/dsh-doctor) — local environment,
  profile, and session-log diagnostics; it also helped align the shared
  `dsh-doctor/v1` community envelope.
- [dsh-trajectory](https://github.com/ciceroyang/dsh-trajectory) — portable,
  self-contained HTML trajectories from Harness session logs.
- [dsh-report-studio](https://github.com/ciceroyang/dsh-report-studio) —
  verifiable daily, weekly, handoff, and article reports from session evidence.
- [dsh-plugin-starter](https://github.com/ciceroyang/dsh-plugin-starter) — a
  zero-dependency scaffold that encodes common plugin-development pitfalls.

The public record includes a
[plugin field guide](https://github.com/deepseek-ai/deepseek-harness/discussions/961)
and the
[`dsh-doctor` interoperability discussion](https://github.com/deepseek-ai/deepseek-harness/discussions/1719),
a
[multi-frame session-log format proposal](https://github.com/deepseek-ai/deepseek-harness/discussions/2328),
and
[merged community-directory contributions](https://github.com/0xsline/awesome-deepseek-harness/pulls?q=is%3Apr+author%3Aciceroyang+is%3Amerged).
These are independent, unofficial community projects, not official DeepSeek
releases.

## How I work

- Ship runnable tools, not AI theater.
- Measure context before adding more context.
- Keep the default path local and inspectable.
- Treat evals and failure cases as product features.
- Support the agent stack people already use.

If you are working on agent infrastructure, open an issue or start a discussion.
