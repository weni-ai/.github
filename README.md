<img src="https://github.com/Ilhasoft/weni-platform/raw/main/images/logos/png/weni-396x129-color.png" data-canonical-src="https://github.com/Ilhasoft/weni-platform/raw/main/images/logos/png/weni-396x129-color.png" width="396"/>

[Weni Platform](https://weni.ai) is an open-source product that contemplates a set of tools, including state-of-the-art of AI models, that enable and potentialize individuals and organizations to solve communication problems and generate impact at scale by building their own automation in a visual and low-code web platform.

As a company we're running as a SaaS product with plans based on the communication traffic necessary for the organization that's accessible in this [address](https://dash.weni.ai).

- [Product documentation](https://docs.weni.ai)

<img src="https://github.com/Ilhasoft/weni-platform/raw/main/images/product/home.png" data-canonical-src="https://github.com/Ilhasoft/weni-platform/raw/main/images/product/home.png"/>

## Community

- Join our [community chat](https://community-chat.weni.ai) to discuss with our internal team
- Join [#dev](https://community-chat.weni.ai/channel/dev) for help from the community to development issues

## Modules

Weni Platform contemplates a set of modules with its own micro-services and micro front-ends applications to enable its whole functionalities, each one has a specific repository with its own instructions in how-to-deploy, the table below details them by using the symbol 🖥️  for front-end components, ⚙️ for back-end components that contain businesses rules and 🧩 for micro-services that are used internally for a specific task.

| Modules                                                       |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Dash**                                                     | **Skeleton and connection between modules**                  |
| 🖥️ [webapp](https://github.com/Ilhasoft/weni-webapp)          | Front-end component that enables organization management and connection of other micro front-end apps |
| ⚙️ [engine](https://github.com/Ilhasoft/weni-engine)          | Back-end component that manages the organization business rules and the connection of other micro-services that are part of the architecture |
| **Academy**                                                  | **Video-based learning module of the platform**              |
| 🖥️ [webapp](https://github.com/Ilhasoft/weni-academy)         | Front-end component of the academy module                    |
| ⚙️ [engine](https://github.com/Ilhasoft/weni-academy-engine)  | Back-end component of the academy module                     |
| **Artificial Intelligence**                                  | **Natural Language Understanding tools as intent classification, named entity recognition and QnA extraction** |
| 🖥️ [ia-platform-frontend](https://github.com/Ilhasoft/ia-platform-frontend) | Front-end component of the AI module                         |
| ⚙️ [bothub-engine](https://github.com/Ilhasoft/bothub-engine) | Back-end component with the business rules of AI model that holds the end-to-end job of creating, training, and testing NLU datasets |
| 🧩 [bothub-nlp-api](https://github.com/bothub-it/bothub-nlp-api) | Service responsible for handling API requests related to NLU tasks |
| 🧩 [bothub-nlp](https://github.com/bothub-it/bothub-nlp)      | Service responsible for parallel processing of NLU tasks both for training and prediction |
| **Integrations**                                             | **Integrations module of the platform**                      |
| 🖥️ [weni-integrations-webapp](https://github.com/Ilhasoft/weni-integrations-webapp) | Front-end component of Integrations module                   |
| ⚙️ [weni-integrations-engine](https://github.com/Ilhasoft/weni-integrations-engine) | Back-end componente that provides so API endpoints and business rules of Integrations module |
| **Flows/Studio**                                             | **Messaging data workflow**                                  |
| ⚙️ [rapidpro](https://github.com/ilhasoft/rapidpro)           | Back-end component to support the whole message workflow     |
| 🧩 [courier](https://github.com/ilhasoft/courier)             | Message gateway for communication channels (e.g. WhatsApp, Telegram, Instagram, etc.) |
| 🧩 [mailroom](https://github.com/ilhasoft/mailroom)           | Service responsible for heavy lifting jobs on behalf of rapidpro |
| 🧩 [indexer](https://github.com/ilhasoft/rp-archiver)         | Service responsible for indexing rapidpro contacts into ElasticSearch |
| 🧩 [archiver](https://github.com/ilhasoft/rp-indexer)         | Service responsible of archiving messages and flow runs to optimize database |

## Contributing

**We are looking for collaboration from the Open Source community!** There's so much we want to do, 
including but not limited to: enhancing existing applications with new features, 
optimizing the NLP tasks and algorithms involved that boost accuracy, new communication channels and integrations.

* Please read our [contribution guidelines](https://github.com/ilhasoft/weni-platform/blob/main/.github/CONTRIBUTING.md) 
for details on what and how you can contribute.

* Report a bug by using [this guideline](https://github.com/ilhasoft/weni-platform/blob/main/.github/CONTRIBUTING.md#report-a-bug) 
for details on what and how you can contribute.

## Using the issue tracker

The issues created here will be analysed and validated. They can be submitted to [this repository](https://github.com/ilhasoft/weni-platform) or in the respective module exposed in the above table.

The issue tracker is the preferred channel for [bug reports](https://github.com/ilhasoft/weni-platform/blob/main/.github/CONTRIBUTING.md#report-a-bug) and [features requests](#features), but please respect the following restrictions:

- Please **do not** use the issue tracker for personal support requests (send an email to bothub@ilhasoft.com.br).

- Please **do not** derail or troll issues. Keep the discussion on topic and respect the opinions of others.

<a name="features"></a>

## Get the Latest News

- [Instagram](https://instagram.com/weni.ai)
- [Blog](https://weni.ai/blog/)
- [LinkedIn](https://www.linkedin.com/company/weniai)
- [Youtube](https://www.youtube.com/c/WeniPlatform)

Any other questions, reach out to us at [our website](https://weni.ai) or you can email us directly at [support@weni.ai](mailto:support@weni.ai).
