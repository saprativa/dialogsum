# DialSumm: A Real-life Scenario Dialogue Summarization Dataset

DialSumm is a large-scale dialogue summarization dataset, consisting of 13,460 dialogues with corresponding manually labeled summaries and topics.

This work is accepted by ACL findings 2021. You may find the paper here: <https://arxiv.org/pdf/2105.06762.pdf>.

If you want to use our dataset, please cite our paper. 

## Dialogue Data
We collect dialogue data for DialSumm from three public dialogue corpora, namely Dailydialog (Li et al., 2017), DREAM (Sun et al., 2019) and MuTual (Cui et al., 2019), as well as an English speaking practice website. 
These datasets contain face-to-face spoken dialogues that cover a wide range of daily-life topics, including schooling, work, medication, shopping, leisure, travel.
Most conversations take place between friends, colleagues, and between service providers and customers.

Compared with previous datasets, dialogues from DialSumm have distinct characteristics: 
* Under rich real-life scenarios, including more diverse task-oriented scenarios;
* Have clear communication patterns and intents, which is valuable to serve as summarization sources;
* Have a reasonable length, which comforts the purpose o automatic summarization.

## Summaries
We ask annotators to summarize each dialogue based on the following criteria:
* Convey the most salient information;
* Be brief;
* Preserve important named entities within the conversation;
* Be written from an observer perspective;
* Be written in formal language.

## Topics
In addition to summaries, we also ask annotators to write a short topic for each dialogue, which can be potentially useful for future work, e.g. generating summaries by leveraging topic information.




**Reference**

* Leyang Cui, Yu Wu, Shujie Liu, Yue Zhang, and Ming Zhou. 2020. MuTual: A dataset for multi-turn dialogue reasoning. In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, pages 1406–1416, Online. Association for Computational Linguistics.

* Yanran Li, Hui Su, Xiaoyu Shen, Wenjie Li, Ziqiang Cao, and Shuzi Niu. 2017. DailyDialog: A manually labelled multi-turn dialogue dataset. In Proceedings of the Eighth International Joint Conference on Natural Language Processing (Volume 1: Long Papers), pages 986–995, Taipei, Taiwan. Asian Federation of Natural Language Processing.

* Kai Sun, Dian Yu, Jianshu Chen, Dong Yu, Yejin Choi,and Claire Cardie. 2019. DREAM: A challenge dataset and models for dialogue-based reading comprehension. Transactions of the Association for Computational Linguistics, 7:217–231.

