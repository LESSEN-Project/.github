## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# Welcome to the LESSEN Project

LESSEN project has fully funded 14 research positions to work on algorithmic solutions to challenges in conversational intelligence. We are a diverse team of researchers based at multiple universities in the Netherlands, with expertise in information retrieval, natural language processing, machine learning, and customer psychology. As part of the LESSEN project, which is funded by the Dutch Research Council (NWO), we work together with industrial stakeholders Achmea, Ahold Delhaize, Albert Heijn, Bol.com, KPN, and Rasa to develop chat-based conversational agents.
LESSEN project description

The LESSEN project aims to develop, implement, and test advanced chat-based conversational AI agents that are safe, transparent, and tailored for lesser-resourced tasks and domains. LESSEN concentrates on tasks, domains, and scenarios with fewer resources. By combining theoretical and experimental methodologies, LESSEN aims to tackle issues including computational efficiency, limited data availability, and privacy considerations. The project also aims to democratize conversational AI technology and promote its responsible use. Key research questions include:

    How to build and adapt conversational agents efficiently?
    How to generate engaging conversations across low-resource domains?
    How to ensure safety, privacy, and transparency in conversational AI?

Therefore LESSEN is organized along three research lines, each of which constitutes two work packages to address scientific challenges of the project which are (i)  the development of neural architectures that are compute and resource efficient; (ii) domain adaptation and data augmentation; and (iii) safety, privacy, and transparency. By tackling urgent research topics, LESSEN aims to democratize conversational AI technology for the Dutch language. With strong connections to academic and industrial partners, LESSEN achieves to have a significant scientific impact by establishing new benchmarks, developing innovative methods, and enhancing collaboration within the research community.

    PhD 1: Parsimonious architectures
    PhD 2: Parsimonious architectures
    PhD 3: Efficient data use and re-use
    PhD 4: Efficient data use and re-use
    PhD 5: Domain adaptation
    PhD 6: Domain adaptation
    PhD 7: Data augmentation
    PhD 8: Data augmentation
    PhD 9: Safety and privacy protection
    PhD 10: Safety and privacy protection
    PhD 11: Transparency and explainability
    PhD 12: Transparency and explainability
    Postdoc: Evaluation
    Scientific Programmer: Knowledge utilization

We provide further descriptions below.
Descriptions of the research positions

## Xinyi Chen : Parsimonious architectures. 
This PhD project is aimed at making neural networks for conversational agents more efficient. How can we reduce their data and compute footprint, both at training time and at inference time? Knowledge distillation has emerged as a potential solution, allowing small student models to learn from, and emulate the performance of, large teacher models. In this project you will develop neural architecture search methods to effectively emulate large conversational models subject to limited memory and parameter budgets.

    Supervisor: Maarten de Rijke (m.derijke@uva.nl, http://staff.fnwi.uva.nl/m.derijke)
    Co-supervisor: Jan N. van Rijn, Leiden University
    Home base: University of Amsterdam, Informatics Institute

## Andreas Paraskeva : Parsimonious architectures. 
This PhD project is aimed at making neural networks for conversational agents more efficient. How can we reduce their data and compute footprint, both at training time and at inference time? Knowledge distillation has emerged as a potential solution, allowing small student models to learn from, and emulate the performance of, large teacher models. In this project you will develop methods that utilize data beyond the particular dataset (i.e., meta-learning techniques) to improve the efficiency of neural architecture search methods.

    Supervisor: Jan N. van Rijn (jvrijn@liacs.nl, https://www.universiteitleiden.nl/en/staffmembers/jan-van-rijn)
    Co-supervisor: Maarten de Rijke, University of Amsterdam
    Home base: Leiden University

## Mohanna Hoveyda : Efficient data use and re-use. 
The aim of this PhD project is to make efficient use of existing knowledge for developing conversational agents under data scarcity conditions. Conversational agents require large amount of training data to handle complex user requests about objects or abstract concepts. Structured information that is stored in knowledge graphs can be used to enrich data-hungry conversational models. In this project, you will inject information from knowledge graphs into transformer-based models and  generate knowledge-enriched conversational agents, without requiring large amount of unstructured training data.

    Supervisor: Faegheh Hasibi (f.hasibi@cs.ru.nl,  https://www.ru.nl/en/people/hasibi-f) 
    Co-supervisor: Maarten de Rijke, University of Amsterdam
    Home base: Radboud University Nijmegen

## Jirui Qi : Efficient data use and re-use. 
This PhD project focuses on multilinguality-related challenges and opportunities, with the goal of enabling the development of conversational agents under data scarcity conditions. Besides enabling knowledge sharing among high- and low-resource languages and language variants, the project aims at empowering chatbots to handle code-switching utterances, which are common in many communities. Possible approaches to achieve this include, among others: (i) applying advanced cross-lingual transfer techniques to different components of a low-resource conversational agent, and (ii) building and evaluating large multilingual language models specialized on conversational data.

    Supervisor: Arianna Bisazza (a.bisazza@rug.nl, https://www.cs.rug.nl/~bisazza)
    Co-supervisor: Raquel Fernández, University of Amsterdam
    Home base: University of Groningen, Center for Language and Cognition

## I-Fan Lin : Domain adaptation. 
The objective of this PhD project is to solve domain-specific challenges of developing conversational agents. Smaller retailers lack the amount of data needed to train conversational agents for their domain. Large retailers face the challenge of a large variety of user intents. In this project you will develop (i) transfer learning methods to allow knowledge transfer from high-resource to low-resource domains using limited training data; (ii) conversational agent technology adaptive to domain- and task-specific user requirements, learned from user interactions.

    Supervisor: Suzan Verberne (s.verberne@liacs.leidenuniv.nl, https://liacs.leidenuniv.nl/~verbernes/)
    Co-supervisor: Faegheh Hasibi, Radboud University
    Home base: Leiden University, Leiden Institute of Advanced Computer Science

## Mert Yazan : Domain adaptation. 
This PhD track takes a unique interdisciplinary approach combining insights from consumer psychology and user studies with state-of-the-art AI methodology. In this project you will analyze user needs in diverse domains, make a systematic investigation of user interactions and requirements, and implement new methods for (i) few-shot learning to allow knowledge transfer from high resource to low-resource retail domains using very limited training data; (ii) flexible adaptation of conversational agent technology to domain- and task-specific user requirements, learned from user interactions.

    Supervisor: Frederik Situmeang (f.b.i.situmeang@hva.nl, https://www.hva.nl/profiel/s/i/f.b.i.situmeang/f.b.i.situmeang.html)
    Co-supervisor: Suzan Verberne, Leiden University
    Home base: Amsterdam University of Applied Sciences

## Roxana Petcu : Data augmentation. 
The aim of this PhD project is to generate synthetic data for training conversational agents. One of the limitations of developing models for conversational agents is the availability and cost of labeled training data. A common approach to alleviate this need is to increase the amount of training data by data augmentation. In this project we will use controllable text generation techniques to develop alternative and unbiased dialogue trajectories to train conversational systems on. 

    Supervisor: Evangelos Kanoulas (e.kanoulas@uva.nl,  https://staff.fnwi.uva.nl/e.kanoulas/)
    Co-supervisor: Faegheh Hasibi, Radboud University
    Location: University of Amsterdam, Informatics Institute

## Heydar Soudani : Data augmentation. 
The aim of this PhD project is to generate synthetic data for training conversational agents. One of the limitations of developing models for conversational agents is the availability and cost of labeled training data. A common approach to alleviate this need is to increase the amount of training data by data augmentation. In this project, you will use knowledge graphs (e.g., Wikipedia) to develop methods that generate question-answer pairs that form coherent conversations.

    Supervisor: Faegheh Hasibi (f.hasibi@cs.ru.nl,  https://www.ru.nl/en/people/hasibi-f) 
    Co-supervisor: Evangelos Kanoulas, University of Amsterdam
    Home base: Radboud University Nijmegen

## Vera Neplenbroek : Safety and privacy protection. 
This PhD project aims to develop new methods for preventing the generation of unsafe utterances by conversational agents, with the goal of ensuring that the system’s behavior does not result in the reinforcement of negative stereotypes or in users feeling excluded. More concretely,  we will approach the problem from three related angles: (i) detection: creation of a typology of safety issues relevant to particular stakeholders and detection of potentially unsafe content; (ii) interpretability: developing and applying explainability techniques to identify the causes that led to generating problematic utterances; and (ii) controlled text generation: developing and applying methods to steer utterance generation away from unsafe content. 

    Supervisor: Raquel Fernández (raquel.fernandez@uva.nl, http://www.illc.uva.nl/~raquel)
    Co-supervisor: Arianna Bisazza, University of Groningen
    Home base: University of Amsterdam, Institute for Logic, Language and Computation

## Ali Satvaty : Safety and privacy protection. 
This PhD project aims to develop auditing techniques for privacy protection in conversational agents and develop measures to make the agents more resilient against malicious attacks. More specifically, we will: (i) look at the security/safety characteristics of machine learning systems commonly used in conversational agents; (ii) study the applicability/impact of various families of machine learning attacks (e.g., membership/property inference, model reconstruction, backdoors) (iii) develop novel cryptographic methods or adapt existing ones (e.g., multi-party computing, differential privacy, homomorphic encryption) for the preservation of privacy in the context of chat-based conversational assistants. 

    Supervisor: Fatih Turkmen (f.turkmen@rug.nl, https://www.cs.rug.nl/~turkmen/)
    Co-supervisor: Suzan Verberne, Leiden University
    Home base: University of Groningen

## Yumeng Wang : Transparency and explainability. 
This PhD project aims to achieve transparency of conversational agents. In the project you will develop and evaluate algorithms to generate conversational explanations of (i) actions taken by a chat-based conversational assistant and (ii) the data used for predictions. The aim will be model and data transparency for the user of the conversational agent.

    Supervisor: Suzan Verberne (s.verberne@liacs.leidenuniv.nl, https://liacs.leidenuniv.nl/~verbernes/)
    Co-supervisor: Frederik Situmeang, Amsterdam University of Applied Sciences
    Home base: Leiden University

## Kudzai Sauka : Transparency and explainability. 
This PhD project aims to distinguish the psychological process, preferences, and values of different stakeholders to craft explanations and achieve model transparency in an effective way. In order to do so: (i) you will develop post-hoc and model-agnostic interpretation methods for black-box and complex neural network models in the context of textual data; (ii) identify and develop techniques that will ensure safe counterfactual explanations that can be made actionable by various stakeholders; and (iii) adopt an interdisciplinary qualitative and quantitative approach to translate explanations provided by the methods in (i) and (ii) into suitable actions for various audiences: engineers, business stakeholders and end users.

    Supervisor: Frederik Situmeang (f.b.i.situmeang@hva.nl, https://www.hva.nl/profiel/s/i/f.b.i.situmeang/f.b.i.situmeang.html)
    Co-supervisor: Fatih Turkmen, University of Groningen
    Home base: Amsterdam University of Applied Sciences

## Panagiotis Eustratiadis : Evaluation. 
This Postdoc project aims to (i) supervise and coordinate the evaluation process in the entire LESSEN project; (ii) aid in developing benchmark datasets within and across different research projects within LESSEN; (iii) develop a metrics for a holistic, fair, accessible, reproducible, and continuous evaluation.

    Supervisor: Evangelos Kanoulas (e.kanoulas@uva.nl,  https://staff.fnwi.uva.nl/e.kanoulas/)
    Home base: University of Amsterdam, Informatics Institute

## Jurian Baas: Knowledge utilization. 
The main objective of this position is to integrate and disseminate knowledge and research output generated from the research lines across members of the consortium and to interested parties outside of the consortium. You will be forefront in the consortium efforts to 
  1. Organize knowledge transfer activities through regular meetups and tutorials within the consortium that build on the knowledge being developed by the PhD students within the consortium
  2. Integrate primary academic outputs that consist of algorithms and models as described in (open access) papers published in top level conferences and journals into prototypes. 
  3. Realize joint development of an annual demonstrator for pilots validated in a relevant environment with partners. 
  4. Organize bi-annual consortium-wide stakeholder sessions aimed at translating LESSEN’s advances to LESSEN’s stakeholders and the broader Dutch community interested in deploying chat-based conversational agents.

    Supervisor: Frederik Situmeang (f.b.i.situmeang@hva.nl, https://www.hva.nl/profiel/s/i/f.b.i.situmeang/f.b.i.situmeang.html)
    Home base: Amsterdam University of Applied Sciences
