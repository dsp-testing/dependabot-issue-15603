# Dependabot Core issue 15603 reproduction

This repository reproduces a grouped uv update that becomes unresolvable when
Dependabot attempts to update mypy beyond the version supported by the latest
type-stub packages.

Issue: https://github.com/dependabot/dependabot-core/issues/15603
