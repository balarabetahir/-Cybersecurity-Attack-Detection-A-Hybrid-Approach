# -Cybersecurity-Attack-Detection-A-Hybrid-Approach
The project employs a rule-based system as the first line of defense. This involves using a set of pre-defined rules, which are based on known attack patterns, to analyze network data.

## The primary objective is to understand how cyberattacks occur and identify the key indicators that signal an attack. 
By analyzing network data and identifying correlations between various variables, we can develop and implement more effective monitoring systems for attack detection using a hybrid approach of both rule-based systems and machine learning. This knowledge enables us to apply learnings to real-world scenarios and contribute to the broader effort of securing the cyber landscape.

The project employs a rule-based system as the first line of defense. This involves using a set of pre-defined rules, which are based on known attack patterns, to analyze network data. For instance, a rule might flag an attack if the ‘source to destination time to live’ (sttl) is low while the ‘count of states time to live’ (ct_state_ttl) value is high. These rules are easy to understand and fast to implement, allowing for quick identification of common attack patterns. Though effective, such a system may produce false positives, requiring further validation. The rules can be visualized using a decision tree.
