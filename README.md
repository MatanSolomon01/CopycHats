# CopycHats: Evaluation of Question Sequencing using Artificial Agents

Schema Matching (SM), the task of finding correspondences among attributes of different target schemata, plays an 
important role in data integration. The task has been extensively researched over the recent years, leading to the
development of multiple algorithmic approaches, many of them incorporate human involvement to some extent,
either by performing the matching, verifying and validating provided algorithmic solutions, or by generating 
reliable ground truth for algorithms to be trained against. Human matching is a temporal process, in which previous 
decisions and ongoing cognitive processes influence future behavior. Therefore, planning a human matching task 
necessitates careful consideration, for example, the ordering of questions posed to the matcher. Various strategies 
exist for optimally choosing the sequence of matching questions and evaluating them may be limited by notable 
inherent human biases. In this work, we propose to leverage Large Language Models (LLMs) to create artificial agents 
that emulate human agents in order to evaluate question sequencing strategies. We offer an alternative to 
traditional human-based evaluations, which overcome those limitations. We test our suggested evaluation framework, 
and discuss the similarity and differences between artificial and the human agents in the context of schema matching 
evaluation.