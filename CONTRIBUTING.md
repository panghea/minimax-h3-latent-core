# Contributing

**This repository does not take pull requests.**

It is dual licensed - PolyForm Small Business 1.0.0 for everyone under that licence's threshold,
and a commercial licence above it. That only works while the copyright is held by one person: a
commercial licence can only be granted by someone who holds all of it, and a single merged
contribution from someone who later cannot be reached would end that permanently. It cannot be
undone after the fact.

So please open an issue instead. Especially useful:

- a case where a mask, a resize or a save/load round trip gives the wrong result, with the tensor
  shapes involved
- measurements - timings, PSNR, thresholds - that contradict or extend what the README claims
- a latent layout from a different MiniMax H3 build that this code fails to read

If you have already written the fix, describe it in the issue or paste a diff there and say it is
yours to give. It will be credited in the commit message.

The ComfyUI adapter is a separate repository under GPL-3.0 and takes pull requests normally.
