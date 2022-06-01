# Description

In this task we ask you to read an article, label it as fake or real, and give reasoning for your decision.

You will be given an external link that will direct you to the article. (WARNING: some URLs have a lot of advertisements popups, so it is advised to have an ad-blocker active in your browser). In your assessment of the article you are allowed to browse the web and search for external sources/proof, this is highly encouraged.

In the explaination for your reasoning you are asked to provide with phrases that make up your decision. In the event of finding external sources that contradict the assessed article you are encouraged to provide this proof in the reasoning.

# Messages

{
'Welcome to this fake news detection task. In this task we ask you to read an article, label it as fake or real, and give reasoning for your decision.',
'The title of the article is + TITLE',
'Here is the link to the article + LINK',
'Is the article real or fake?',
'Give reasoning for your answer (provide phrases and/or external source that back your decision')
}

# Quality control

# Data collection

To collect data for this task we used the fake news data repository FakeNewsNet (https://arxiv.org/abs/1809.01286). This dataset consits of two comprehensive datasets that includes news contents (political), and social context (gossip).

Articles were manually handpicked and checked whether URLs were still active. We manually constructed a dataset of 60 articles (30 political news, and 30 gossip news). Since the FakeNewsNet dataset consists of news with links to adult content sites and had articles with gory images we had to carefully hand pick the data to avoid these.
