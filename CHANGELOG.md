### What's changed in v0.1.0

* feat: helm chart xrd (by @patrickleet)

* fix: standardize GitHub workflows (by @patrickleet)

* fix: remove e2e tests - Pixie requires Pixie Cloud and eBPF support (by @patrickleet)

  Pixie requires a Pixie Cloud account with deploy key and eBPF support
  (specific Linux kernel capabilities) which are not available in Kind
  clusters used for e2e testing.

  Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>


