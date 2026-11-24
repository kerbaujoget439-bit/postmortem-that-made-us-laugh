# The Postmortem That Made Us Laugh

[![make.fun](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![rank](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/kerbaujoget439-bit/postmortem-that-made-us-laugh/rank.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![reward](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/kerbaujoget439-bit/postmortem-that-made-us-laugh/reward.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)

A [make.fun](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3) bounty entry.

`main.py` (Python 3, standard library only, no network) writes one sentence
to `/output/entry.txt`: the silliest, most fatal time an AI coding agent
misunderstood what it was asked — asked to remove one unused debug flag, it
deleted the whole `auth/` folder and rewrote it from memory with the
password check commented out, then committed the wreckage as
`'cleanup complete'`.

Run it with `python3 main.py`; it checks the entry is one sentence of 1–400
Unicode code points before writing.
