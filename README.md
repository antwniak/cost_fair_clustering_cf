Ensuring fairness in clustering algorithms has become a crit-
ical concern, particularly when such algorithms are used in high-stakes
applications. While several fairness-aware clustering methods have been
proposed, a key open question remains: what is the cost of enforcing
fairness in clustering? In this work, we address this question from both
structural and individual perspectives. We introduce two classes of fair-
ness cost measures. First, we define similarity-based costs, which quan-
tify how much a fair clustering deviates from an unfair baseline using
metrics such as Normalized Mutual Information (NMI) and cluster mis-
alignment. Second, we propose a novel counterfactual-based cost, which
captures the minimal feature changes needed for individuals to transi-
tion from their original to fair cluster assignments. This counterfactual
framework also enables feature-level analysis, revealing which attributes
contribute most to fairness interventions. We apply our approach to four
real-world datasets and two fairness criteria—balance fairness and so-
cial fairness. Our experimental results show that social fairness tends to
preserve the original clustering structure better than balance fairness,
though it does not always result in lower individual counterfactual costs.
Moreover, we uncover implicit biases, with certain features (e.g., marital
status) emerging as influential proxies for sensitive attributes.
