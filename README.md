# Awesome Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools for dev, design, and life.

Inspired by [awesome-python](https://github.com/vinta/awesome-python).

<!-- TOC -->
* [Awesome Tools ![Awesome](https://awesome.re/badge.svg)](#awesome-tools-)
  * [Design](#design)
    * [Figma](#figma)
  * [Branding](#branding)
  * [Machine Learning](#machine-learning)
    * [Open Training Data](#open-training-data)
    * [Llama](#llama)
    * [Awesome Papers on Natural Language Processing (NLP)](#awesome-papers-on-natural-language-processing-nlp)
  * [Knowledge Graph](#knowledge-graph)
  * [LaTeX](#latex)
  * [Software Architecture](#software-architecture)
  * [Frontend Dev](#frontend-dev)
    * [UI Performance](#ui-performance)
    * [Mock Backend](#mock-backend)
  * [Backend Dev](#backend-dev)
    * [IntelliJ](#intellij)
    * [Java](#java)
    * [GraphQL](#graphql)
    * [Database](#database)
      * [Database Management](#database-management)
  * [DevOps](#devops)
    * [OpenStack](#openstack)
  * [Miscellaneous](#miscellaneous)
* [Contributing](#contributing)
* [License](#license)
<!-- TOC -->

---

## Design

- [Vectorian ornaments](https://www.vectorian.net/free-vintage-vectors.html)
- SVG/LOGO
    - [SVG Repo](https://www.svgrepo.com/)
    - [Worldvectorlogo](https://worldvectorlogo.com/logo/google-lighthouse)
    - [Brandfetch](https://brandfetch.com/cypress.io)
- [API Stylebook Design Guidelines](https://apistylebook.com/design/guidelines/)
- [Implement an AWS Client VPN](https://youtube.com/playlist?list=PLTk5ZYSbd9Mg6i1ud6F9KIFQR7zppcQXc&si=pMMqPv-KZVaH3v3t)
- [Ubuntu Design](https://design.ubuntu.com/)

### Figma

- [Select Similar](https://www.figma.com/community/plugin/792767780551514994/select-similar) - Completely screwed on a file after duplicating 300 objects? Instead of going one by one this plugin single handedly came in clutch.

## Branding

- [HashiCorp](https://www.hashicorp.com/brand)
- [Elastic Brand Guide](https://brand.elastic.co/)
- [TypeScript](https://qubitpi.github.io/TypeScript-Website/branding/)
- [Golang](https://go.dev/blog/go-brand)
- [Docker](https://www.docker.com/company/newsroom/media-resources/)
- [GraphQL](https://graphql.org/brand/)
- [Jupyter](https://github.com/jupyter/design/tree/main)

## Machine Learning

- [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html) by Sutton and Barto - is the introductory book on RL. It covers very basics and build up from there. Does not cover deep RL.
- [Deep Learning Tutorial](http://ufldl.stanford.edu/tutorial/)

### Open Training Data

When we are learning about Machine Learning it is best to actually experiment with real-world data, not just artificial
datasets. Fortunately, there are thousands of open datasets to choose from, ranging across all sorts of domains. Here
are a few places we can look to get data:

- [Project Gutenberg](https://www.gutenberg.org/) - Free books for read and data analytics
- [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/)
- [Wikipedia's list of Machine Learning datasets](https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research)
- [WikiSQL](https://github.com/QubitPi/WikiSQL) - NL to SQL
- [Knowledge Graph entities](https://www.ownthink.com/docs/kg/)
- [University of Oregon RouteViews Project](https://www.routeviews.org/routeviews/)
- [Datasets subreddit](https://www.reddit.com/r/datasets/)
- [Kaggle datasets](https://www.kaggle.com/datasets)
- [Amazon's AWS datasets](https://registry.opendata.aws/)
- [AWS Data Exchange](https://docs.aws.amazon.com/data-exchange/)
- [Data Portals](https://dataportals.org/) - A Comprehensive List of [Open Data](https://opendefinition.org/) Portals from Around the World
- [Nasdaq Data Link](https://data.nasdaq.com/institutional-investors)
- [University of Oregon RouteViews Project](https://www.routeviews.org/routeviews/)
- [OpenConcepts](https://github.com/QubitPi/OpenConcepts) - Entity [API](http://openconcepts.zjukg.cn/api_page)

### Llama

- [Downloading converted and quantized Llama models](https://huggingface.co/TheBloke)
    - [LLaMA 2 7B base](https://huggingface.co/TheBloke/Llama-2-7B-GGUF)
    - [LLaMA 2 13B base](https://huggingface.co/TheBloke/Llama-2-13B-GGUF)
    - [LLaMA 2 70B base](https://huggingface.co/TheBloke/Llama-2-70B-GGUF)
    - [LLaMA 2 7B chat](https://huggingface.co/TheBloke/Llama-2-7B-chat-GGUF)
    - [LLaMA 2 13B chat](https://huggingface.co/TheBloke/Llama-2-13B-chat-GGUF)
    - [LLaMA 2 70B chat](https://huggingface.co/TheBloke/Llama-2-70B-chat-GGUF)
- [Downloading Llama models](https://llama-2.ai/download/)
- [A comprehensive guide to running Llama 2 locally](https://replicate.com/blog/run-llama-locally)
- [Ollama](https://ollama.ai/)
- [llama-2-7b-hf](https://huggingface.co/daryl149/llama-2-7b-hf) - Converted model weights for Llama-2-7B in Huggingface format

### Awesome Papers on Natural Language Processing (NLP)

- [Attention is All you Need](./nlp-papers/attention-is-all-you-need/ms.pdf)

## Knowledge Graph

- [arrows.app](https://github.com/QubitPi/arrows.app)
- [Neo4j Desktop Graph Apps Gallery](https://install.graphapp.io/) - Plugin apps for Neo4j Desktop that provide new capabilities, like Monitoring, Import, Analysis, Running Graph Algorithms, Visualization and much more

## LaTeX

- [LaTeX math equation online editor](https://latexeditor.lagrida.com/)
- [QuickLaTeX.com](https://quicklatex.com/) - Instant math equation syntax checker and sharing via image online
- [MacTeX](https://www.tug.org/mactex/) - LaTeX comes with various installation packges, some are minimized versions. The comprehensive package is MacTeX
- [CTAN](https://www.ctan.org/) - The "Maven Central" for LaTeX
- [texlive package manager](https://tug.org/texlive/doc/tlmgr.html) - Installing a LaTeX package. e.g. `sudo tlmgr update --self && sudo tlmgr install pgfornament`
- [LaTeX showcase](https://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends)
- [Cool Text Highlighting in LaTeX](https://tex.stackexchange.com/a/6029)

## Software Architecture

- [Software architecture tools](https://softwarearchitecture.tools/)
- [UML Boundary Object v.s. Control Object](https://stackoverflow.com/a/17028825/14312712)

## Frontend Dev

- [Nodesource](https://deb.nodesource.com/) - Universal node & npm installer
- [npm trends](https://npmtrends.com/)
- [Defensive CSS](https://defensivecss.dev/)
- [The Modern JavaScript Tutorial](https://javascript.info/)

### UI Performance

- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)
- [Lighthouse CI](https://github.com/GoogleChrome/lighthouse-ci) - Maintained by Google, GitHub App install required, UI report hosting requires dedicated server
- [Lighthouse CI Action](https://github.com/treosh/lighthouse-ci-action) - Maintained by third party, no GitHub App install required, no dedicated UI report hosting server required
- [PageSpeed Insights](https://pagespeed.web.dev/)
- [Performance Budget Calculator](https://perf-budget-calculator.firebaseapp.com/)
- [Request Map Generator](https://requestmap.webperf.tools/)
- [Third Party Web](https://www.thirdpartyweb.today/)

### Mock Backend

- [json-server](https://github.com/typicode/json-server) - Quick back-end for prototyping and mocking
- [lowdb](https://github.com/typicode/lowdb) - Simple to use type-safe local **JSON database**
- [json-graphql-server](https://github.com/marmelab/json-graphql-server)

## Backend Dev

- [get.docker.com](https://github.com/docker/docker-install) - Installing Docker on Linux with an automated script
- [JSON to JSON Schema converter online](https://transform.tools/json-to-json-schema)
- [API Platform](https://api-platform.com/) (also checkout this [interesting startup](https://les-tilleuls.coop/en))
- [Generate SQL DB Schema Diagram](https://dbdiagram.io/)
- [Cloudcraft](https://www.cloudcraft.co/) - Visualize cloud architecture like a Pro by creating smart AWS diagrams

### IntelliJ

- [String Manipulation plugin](https://plugins.jetbrains.com/plugin/2162-string-manipulation) - With a simple `Alt`/`Option` + `M` you get case switching, sorting, filtering, incrementing, aligning to columns, grepping, escaping, encoding, and more
- [Intellij Ubuntu Light Theme](https://github.com/QubitPi/intellij-theme-ubuntu) - an Idea theme plugin whose color scheme follows the famous [Ubuntu Color Palette](https://design.ubuntu.com/brand/colour-palette)

### Java

- [Java Generics FAQs](http://www.angelikalanger.com/GenericsFAQ/JavaGenericsFAQ.html)
- [Defensive Copy](http://www.javapractices.com/topic/TopicAction.do?Id=15)
- [Learning Java via Jenkov](https://jenkov.com/)
- [VisualVM](https://visualvm.github.io/)
- [jConsole](https://openjdk.java.net/tools/svc/jconsole/)
- [Java Decompiler](http://java-decompiler.github.io/)
- Diagnostic Tools
    - [The jps Utility](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr015.html)
    - [The jstat Utility](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr017.html)
    - [The jinfo Utility](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr013.html)
    - [The jmap Utility](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr014.html)
    - [The jhat Utility](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr012.html)
    - [The jstack Utility](https://docs.oracle.com/javase/8/docs/technotes/guides/troubleshoot/tooldescr016.html)

### GraphQL

- [GraphiQL online](https://graphiql-online.com)
- [gqt](https://github.com/eerimoq/gqt) - Build and execute GraphQL queries in the terminal

### Database

- [MySQL Tutorial](https://www.mysqltutorial.org/)
- [Oracle Tutorial](https://www.oracletutorial.com/)
- [Postgres.app](https://postgresapp.com/) - The easiest way to get started with PostgreSQL on Mac

#### Database Management

- [DBeaver](https://dbeaver.io/)
- [pgAdmin](https://github.com/pgadmin-org/pgadmin4) (PostgreSQL)
- [pgweb](https://github.com/sosedoff/pgweb) (PostgreSQL)

## DevOps

- [Go Playground](https://go.dev/play/)
- [Docker Registry UI](https://github.com/QubitPi/docker-registry-ui)

### OpenStack

- [Swift Docker](https://github.com/FNNDSC/docker-swift-onlyone)

## Miscellaneous

- [local-jwks-server](https://github.com/murar8/local-jwks-server) - [a tool for mocking JWT authentication with JWKS](https://www.reddit.com/r/webdev/comments/15crsg3/i_made_a_tool_for_mocking_jwt_authentication_with/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
- [OpenID Connect explained](https://connect2id.com/learn/openid-connect)
- [Refactoring.Guru](https://refactoring.guru/)
- [Discourse](https://github.com/discourse/discourse) - A platform for community discussion. Free, open, simple.
- [git-crypt](https://github.com/AGWA/git-crypt)
- [whatismyip.com](https://www.whatismyip.com/)
- [Online JSON formatter](https://jsonformatter.curiousconcept.com/#)
- [command-not-found.com](https://command-not-found.com/) - Dealing with "command not found" Error
- [Convert curl command to programming language code](https://curlconverter.com/)
- [Convert JSON to YAML](https://www.json2yaml.com/)
- [smee.io](https://smee.io/) - Receives payloads then sends them to your locally running application
- [Escape/Unescape Tool](https://www.freeformatter.com/json-escape.html)
- [Unix Time Stamp - Epoch Converter](https://www.unixtimestamp.com/)
- [URL Decoder/Encoder](https://meyerweb.com/eric/tools/dencoder/)
- [Greasy Fork](https://greasyfork.org/en) - A nice browser per-website customization such as [de-流氓 script](https://greasyfork.org/en/scripts/393995-bilibili-干净链接/code) by Bilibili
- [Random String Generator](https://www.random.org/strings/)
- [Online Self-Signed SSL Certificate Generator Tool for Website](https://regery.com/en/security/ssl-tools/self-signed-certificate-generator)
- [martinfowler.com](https://martinfowler.com/)
- [Tree](https://tree.nathanfriend.io/): An online tree-like utility for generating ASCII folder structure diagrams. Written in TypeScript and React.

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](./CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/QubitPi/awesome-tools/pulls) by adding :+1: to them. Pull requests will be merged when their votes reach **20**.

# License

The use and distribution terms for [awesome-tools](https://qubitpi.github.io/awesome-tools/) are covered by the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

<div align="center">
    <a href="https://opensource.org/licenses">
        <img align="center" width="50%" alt="License Illustration" src="https://github.com/QubitPi/QubitPi/blob/master/img/apache-2.png?raw=true">
    </a>
</div>

- - -

If you have any question about this opinionated list, do not hesitate to contact me [![Gmail Badge](https://img.shields.io/badge/jack20220723@gmail.com-ea4435?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:jack20220723@gmail.com)](mailto:jack20220723@gmail.com) or open an issue on GitHub.
