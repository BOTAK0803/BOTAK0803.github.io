---
title:          "CPNet: A Context based Personalized Deep Network for Nearby Flight Recommendation"
date:           03 August 2025
selected:       true
pub:            "KDD '25: Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V.2"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Poster</span>'
pub_date:       "2024"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  With the flourishing development of aviation and the convenience of booking flights online, nearby flight recommendation has become the core business of Online Travel Platforms (OTPs). Nearby flight addresses the issue of inadequate flight options for travelers by offering more cost-effective alternatives, such as recommending flights from nearby cities or on nearby departure dates. Currently, mainstream OTPs adopt rule-based or simple user preference-based strategies to recommend nearby flights. However, the insufficient emphasis on the user's historical behaviors and the ignorance of nearby flight's context make these existing strategies less effective in solving the nearby flight recommendation. To this end, a \textbf{C}ontext-based \textbf{P}ersonalized Deep \textbf{Net}work (CPNet) is proposed in this paper for nearby flight recommendation. In CPNet, a \textbf{P}ersonalized \textbf{P}references \textbf{L}earning (PPL) component is first proposed to encapsulate users' individual preferences, leveraging crucial feature correlations between historical behaviors and target nearby flight. Then, a \textbf{H}istorical \textbf{C}ost \textbf{L}earning (HCL) component is designed to learn the price sensitivity of users under the same query and the same nearby flight recommendation. Finally, we present a \textbf{C}ontext \textbf{P}otential \textbf{G}ain \textbf{L}earning (CPGL) component, where the important cost between target nearby flight and context flights are emphasized and learned. Offline experiments on a production dataset and a world-scale online A/B test at Fliggy\footnote{Fliggy:\url{https://www.fliggy.com/}} both demonstrate the superiority of the proposed CPNet over baselines. CPNet is now successfully deployed at Fliggy, one of the largest OTPs in China, serving millions of users every day for flight reservations.

cover:          /assets/images/covers/CPNet.jpg
authors:
  - Maolei Huang
  - Detao Lv
  - Yao Yu
  - Shuhan Song
  - Dong Li
  - Zhuoran Zhuang
links:
  pdf: https://dl.acm.org/doi/epdf/10.1145/3711896.3737183
---
