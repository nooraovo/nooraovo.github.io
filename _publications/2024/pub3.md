---
title:          "When Errors Can Be Beneficial: A Categorization of Imperfect Rewards for Policy Gradient"
date:           2026-4-28 00:01:00 +0800
selected:       false
# pub:            "International Conference on Machine Learning (ICML)"
# pub_pre:        "Submitted to "
pub_post:       'Preprint.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# pub_date:       "2026"

abstract: >-
  Training language models via reinforcement learning often relies on imperfect proxy rewards, since ground truth rewards that precisely define the intended behavior are rarely available. Standard metrics for assessing the quality of proxy rewards, such as ranking accuracy, treat incorrect rewards as strictly harmful. In this work, however, we highlight that not all deviations from the ground truth are equal. By theoretically analyzing which outputs attract probability during policy gradient optimization, we categorize reward errors according to their effect on the increase in ground truth reward. The analysis establishes that reward errors, though conventionally viewed as harmful, can also be benign or even beneficial by preventing the policy from stalling around outputs with mediocre ground truth reward. We then present two practical implications of our theory. First, for reinforcement learning from human feedback (RLHF), we develop reward model evaluation metrics that account for the harmfulness of reward errors. Compared to standard ranking accuracy, these metrics typically correlate better with the performance of a language model after RLHF, yet gaps remain in robustly evaluating reward models. Second, we provide insights for reward design in settings with verifiable rewards. A key theme underlying our results is that the effectiveness of a proxy reward function depends heavily on its interaction with the initial policy and learning algorithm.
  cover:          /assets/images/covers/RMerrors.png
authors:
  - Shuning Shang*
  - Hubert Strauss*
  - Stanley Wei
  - Sanjeev Arora
  - Noam Razin
links:
  Paper: https://arxiv.org/abs/2604.25872
---
