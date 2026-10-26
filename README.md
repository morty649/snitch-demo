# Demo target for [Snitch](https://github.com/morty649/snitch).

Green test suite, 100% function coverage — yet it misses boundary bugs on purpose.
Open a PR changing `shopcalc/pricing.py` and watch Snitch comment with the bugs your tests would let through.

## Run tests

```bash
pip install -e .
python -m pytest -q
```
