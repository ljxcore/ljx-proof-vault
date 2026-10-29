# The Honest Engine: Why We Publish Our Failures

Most AI companies only show you their wins. We don't. Our engine is built with a pre-registered acceptance gate. It is mathematically required to reject its own results if they don't hold up to holdout testing, permutation nulls, or known-physics audits.

Here are three times the engine told us "No." We consider this our strongest proof of all.

1. **X010 Feynman Blind Test:** The engine attempted a harder Feynman equation and failed the blind test (error > 1.0). The pipeline correctly labeled it `FAILED_BLIND_TEST`.
2. **SRSD Benchmark:** The engine achieved a median R2 gain of exactly 0.0. It refused to overfit.
3. **Adversarial Stress V9:** The engine was subjected to adversarial noise and accepted exactly 0 solutions. It knew the data was garbage.

You can verify the math in the JSON files inside this folder.
