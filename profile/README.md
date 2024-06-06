<img src="https://github.com/Ilhasoft/weni-platform/raw/main/images/logos/png/weni-396x129-color.png" data-canonical-src="https://github.com/Ilhasoft/weni-platform/raw/main/images/logos/png/weni-396x129-color.png" width="396"/>

## About

[Weni Platform](https://weni.ai) is an open-source product that contemplates a set of tools, including state-of-the-art of AI models, that enable and potentialize individuals and organizations to solve communication problems and generate impact at scale by building their own automation in a visual and low-code web platform.

As a company we're running as a SaaS product with plans based on the communication traffic necessary for the organization that's accessible in this [address](https://dash.weni.ai).

- [Product documentation](https://docs.weni.ai)

<img src="https://github.com/Ilhasoft/weni-platform/raw/main/images/product/home.png" data-canonical-src="https://github.com/Ilhasoft/weni-platform/raw/main/images/product/home.png"/>

## Open-Source Governance

The Weni Platform open source projects are governed by [@weni-ai](https://github.com/weni-ai/). Weni opens all its software parts under terms of an open-source license to reach potential users and partners mainly. Secondly, Weni wants to reach developers by building a community for some pieces that are more reusable in other businesses or software projects, such as NLP models or tools. Besides that, the openness of our software is also related to building trust by enabling our external stakeholders to audit the security of our software.

## Community

- Join our [community chat](https://community-chat.weni.ai) to discuss with our internal team
- Join [#dev](https://community-chat.weni.ai/channel/dev) for help from the community to development issues

## Modules

Weni Platform contemplates a set of modules with its own micro-services and micro front-ends applications to enable its whole functionalities, each one has a specific repository with its own instructions in how-to-deploy, the table below details them by using the symbol 🖥️  for front-end components, ⚙️ for back-end components that contain businesses rules and 🧩 for micro-services that are used internally for a specific task.

| Modules                                                       |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Dash**                                                     | **Skeleton and connection between modules**                  |
| 🖥️ [webapp](https://github.com/weni-ai/weni-webapp)          | Front-end component that enables organization management and connection of other micro front-end apps |
| ⚙️ [engine](https://github.com/weni-ai/weni-engine)          | Back-end component that manages the organization business rules and the connection of other micro-services that are part of the architecture |
| **Academy**                                                  | **Video-based learning module of the platform**              |
| 🖥️ [webapp](https://github.com/weni-ai/weni-academy)         | Front-end component of the academy module                    |
| ⚙️ [engine](https://github.com/weni-ai/weni-academy-engine)  | Back-end component of the academy module                     |
| **Artificial Intelligence**                                  | **Natural Language Understanding tools as intent classification, named entity recognition and QnA extraction** |
| 🖥️ [ia-platform-frontend](https://github.com/weni-ai/ia-platform-frontend) | Front-end component of the AI module                         |
| ⚙️ [bothub-engine](https://github.com/weni-ai/bothub-engine) | Back-end component with the business rules of AI model that holds the end-to-end job of creating, training, and testing NLU datasets |
| 🧩 [bothub-nlp-api](https://github.com/weni-ai/bothub-nlp-api) | Service responsible for handling API requests related to NLU tasks |
| 🧩 [bothub-nlp](https://github.com/weni-ai/bothub-nlp)      | Service responsible for parallel processing of NLU tasks both for training and prediction |
| **Integrations**                                             | **Integrations module of the platform**                      |
| 🖥️ [weni-integrations-webapp](https://github.com/weni-ai/weni-integrations-webapp) | Front-end component of Integrations module                   |
| ⚙️ [weni-integrations-engine](https://github.com/weni-ai/weni-integrations-engine) | Back-end componente that provides so API endpoints and business rules of Integrations module |
| **Flows/Studio**                                             | **Messaging data workflow**                                  |
| ⚙️ [flows-engine](https://github.com/weni-ai/flows)                  | Back-end component to support the whole message workflow     |
| 🧩 [courier](https://github.com/weni-ai/courier)             | Message gateway for communication channels (e.g. WhatsApp, Telegram, Instagram, etc.) |
| 🧩 [mailroom](https://github.com/weni-ai/mailroom)           | Service responsible for heavy lifting jobs on behalf of flows |
| 🧩 [indexer](https://github.com/weni-ai/rp-archiver)         | Service responsible for indexing flows contacts into ElasticSearch |
| 🧩 [archiver](https://github.com/weni-ai/rp-indexer)         | Service responsible of archiving messages and flow runs to optimize database |
| **Chats**                                             | **Messaging data workflow**                                  |
| 🖥️ [webapp](https://github.com/weni-ai/chats-webapp)         | Front-end component of the Chats module                    |
| ⚙️ [engine](https://github.com/weni-ai/chats-engine)  | Back-end component of the Chats module                     |


## Contributing

**We are looking for collaboration from the Open Source community!** There's so much we want to do, 
including but not limited to: enhancing existing applications with new features, 
optimizing the NLP tasks and algorithms involved that boost accuracy, new communication channels and integrations.

* Please read our [contribution guidelines](https://github.com/ilhasoft/weni-platform/blob/main/.github/CONTRIBUTING.md) 
for details on what and how you can contribute.

* Report a bug by using [this guideline](https://github.com/ilhasoft/weni-platform/blob/main/.github/CONTRIBUTING.md#report-a-bug) 
for details on what and how you can contribute.

## Public roadmap

The roadmap of solutions we're working on at the moment is publicly available [on this page]([https://bit.ly/weni-roadmap](https://github.com/orgs/weni-ai/projects/6/views/1?filterQuery=)) and we're willing to get your contributions to it.

## Using the issue tracker

The issues created here will be analysed and validated. They can be submitted to [this repository](https://github.com/ilhasoft/weni-platform) or in the respective module exposed in the [modules table](https://github.com/Ilhasoft/weni-platform/tree/main#modules).

The issue tracker is the preferred channel for [bug reports](https://github.com/ilhasoft/weni-platform/blob/main/.github/CONTRIBUTING.md#report-a-bug) and [features requests](#features), but please respect the following restrictions:

- Please **do not** use the issue tracker for personal support requests (send an email to [support@weni.ai](mailto:support@weni.ai)).

- Please **do not** derail or troll issues. Keep the discussion on topic and respect the opinions of others.

<a name="features"></a>

## Get the Latest News

- [Instagram](https://instagram.com/weni.ai)
- [Blog](https://weni.ai/blog/)
- [LinkedIn](https://www.linkedin.com/company/weniai)
- [Youtube](https://www.youtube.com/c/WeniPlatform)

Any other questions, reach out to us at [our website](https://weni.ai) or you can email us directly at [support@weni.ai](mailto:support@weni.ai).
