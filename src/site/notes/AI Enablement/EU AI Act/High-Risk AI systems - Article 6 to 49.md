---
{"dg-publish":true,"permalink":"/ai-enablement/eu-ai-act/high-risk-ai-systems-article-6-to-49/","title":["High-Risk AI systems - Article 6 to 49"]}
---


# **Section 1: Classification of AI systems as high-risk (Art. 6 to 7)** 

#### **Article 6 – Classification of High-Risk AI Systems**

**What qualifies an AI system as “high-risk”?**  
An AI system is considered high-risk if it is either a safety component of a product or the product itself, and that product is subject to EU safety regulations listed in Annex I. Additionally, the product must require a third-party conformity assessment before it can be placed on the market or used. This means that if an AI system is part of something like a medical device, vehicle, or industrial machine that already needs safety certification, the AI system is automatically treated as high-risk under the AI Act.

**Annex III use cases and exceptions**  
Even if an AI system isn’t part of a regulated product, it can still be classified as high-risk if it falls under one of the sensitive use cases listed in Annex III, such as biometric identification, education, employment, law enforcement, or access to essential services. However, there are exceptions. If the AI system only performs a narrow or supporting task (like flagging patterns or preparing data for a human decision), and it doesn’t significantly influence outcomes or pose a real risk to health, safety, or fundamental rights, it may not be considered high-risk. But if the system involves profiling individuals, it is always classified as high-risk, regardless of its function.

**Provider responsibilities and future updates**  
If a provider believes their Annex III AI system is not high-risk, they must document their reasoning before launching the system and register it under Article 49(2). They must also be ready to share this documentation with national authorities if asked. The European Commission will issue practical guidelines by February 2026 to help clarify how this article should be applied, including examples of what is and isn’t high-risk. The Commission also has the power to update the classification rules through delegated acts, but any changes must maintain or improve the level of protection for health, safety, and fundamental rights.

##### **Article 7 – Updating the List of High-Risk Use Cases**

**How the list of high-risk AI use cases can change**  
Article 7 gives the European Commission the authority to update the list of high-risk AI systems found in Annex III of the regulation. This means the Commission can add new use cases or modify existing ones through delegated acts. However, this power is limited to situations where two conditions are met: (a) the AI system is used in one of the sectors already listed in Annex III (like education, employment, law enforcement, etc.), and (b) the system poses a risk to health, safety, or fundamental rights that is equal to or greater than the risks posed by systems already classified as high-risk.

**Criteria for assessing whether a system should be added**  
To decide whether a new AI use case should be added to Annex III, the Commission must consider a range of factors. These include how the system is used, how much data it processes (especially sensitive data), how autonomous it is, and whether people can override its decisions. The Commission also looks at whether the system has already caused harm or raised serious concerns, how widespread or intense the potential harm could be, and whether the people affected are in a vulnerable position or unable to opt out. It also considers whether the system’s outcomes are reversible and whether existing EU laws already provide effective protections.

**3. Removing systems from the high-risk list**  
The Commission can also remove AI systems from Annex III, but only if two conditions are met: (a) the system no longer poses a significant risk to health, safety, or fundamental rights, and (b) removing it won’t reduce the overall level of protection provided by the regulation. Any changes must be consistent with other updates made under Article 7 and must reflect technological and market developments. The Commission is also required to publish **practical guidelines and examples** by February 2026 to help clarify how these decisions are made.

------ 
# **Section 2: Requirements for high-risk AI systems (Art. 8 to 15)**

##### **Article 8 – Compliance with the Requirements**

**High-risk AI systems must meet strict standards.**  
Any AI system classified as high-risk must follow the rules set out in this section of the regulation. These rules are based on the system’s intended use and the current best practices in AI technology. Developers and providers must ensure their systems are safe, reliable, and respectful of people’s rights.

**Risk management is central to compliance.**  
To meet these requirements, providers must use a proper risk management system (as described in Article 9). This system helps identify and reduce potential risks to health, safety, and fundamental rights throughout the AI system’s lifecycle.

**Integration with existing product safety laws.**  
If the AI system is part of a product already regulated under EU safety laws (like medical devices or vehicles), the provider must ensure the entire product complies with both the AI Act and those existing laws. To avoid duplication and extra work, providers can reuse testing, documentation, and reporting they already do under those laws, so long as it covers the AI-specific requirements too.

**Goal: consistency and reduced burden.**  
The regulation encourages providers to streamline their compliance efforts by combining AI-related checks with existing product safety procedures. This helps maintain consistency across regulations and reduces unnecessary administrative burden.

##### **Article 9 – Risk Management System**

**A continuous, lifecycle-wide process**  
All high-risk AI systems must have a risk management system in place. This isn’t a one-time task, it’s a continuous and iterative process that must be planned, implemented, and updated throughout the entire lifecycle of the AI system. The goal is to identify, assess, and reduce risks to health, safety, and fundamental rights, both during development and after the system is deployed.

**Key steps in the process**  
The risk management system must include:
- Identifying and analysing foreseeable risks when the system is used as intended
- Estimating risks from both intended use and reasonably foreseeable misuse
- Evaluating new risks based on real-world data collected after deployment (post-market monitoring)
- Applying targeted measures to eliminate or reduce those risks

These risks must be ones that can reasonably be addressed through design, development, or technical documentation. The system must also ensure that any residual risks (risks that remain after mitigation) are acceptable.

**How to manage and test risks**  
Risk management should prioritise design-based solutions to eliminate risks where possible. If risks can’t be eliminated, appropriate mitigation and control measures must be put in place. Providers must also ensure that users (deployers) receive clear information and training to use the system safely. Testing is required to confirm that the AI system performs reliably and meets the regulation’s requirements. This testing should be done throughout development and before the system is released, using predefined metrics and thresholds. Real-world testing may also be used where appropriate.

**Special considerations and integration with other laws**  
When designing risk management measures, providers must consider the skills, knowledge, and context of the people who will use the system, especially if the system could affect children or vulnerable groups. If the provider is already subject to other EU laws that require internal risk management (e.g. medical device regulations), the AI risk management process can be integrated with those existing procedures, as long as all AI-specific requirements are still met.

##### **Article 10 – Data and Data Governance**

**Data quality is essential for high-risk AI systems**  
High-risk AI systems that rely on training, validation, or testing data must use high-quality datasets. These datasets must be carefully managed and appropriate for the system’s intended purpose. The regulation requires that data be relevant, representative, as complete and error-free as possible, and statistically sound, especially when the AI system is used to make decisions about people or groups.

**Strong data governance practices are required**  
Providers must follow robust data governance and management practices. This includes documenting how data is collected, processed, and prepared (e.g. labelling, cleaning, updating), and assessing whether the data is suitable for the system’s purpose. Providers must also check for biases that could harm people’s health, safety, or rights, and take steps to detect, prevent, and reduce those biases. If there are gaps or weaknesses in the data, providers must identify them and explain how they will be addressed.

**Special rules for sensitive personal data**  
In rare cases, providers may need to use special categories of personal data (like data about race, health, or religion) to detect and correct bias. This is only allowed if it’s strictly necessary and no other data (including anonymised or synthetic data) can achieve the same result. If used, this data must be protected with state-of-the-art security and privacy measures, such as pseudonymisation, strict access controls, and deletion once it’s no longer needed. Providers must also document why this sensitive data was necessary and how it was handled.

**Context matters**  
The data used must reflect the real-world context in which the AI system will operate. This includes geographical, behavioural, and functional factors. For AI systems that don’t involve training models (e.g. rule-based systems), these data quality and governance requirements apply only to the testing phase.

##### **Article 11 – Technical Documentation**

**Documentation is mandatory before launch**  
Before a high-risk AI system can be placed on the market or used, the provider must create technical documentation that proves the system complies with the AI Act’s requirements. This documentation must be kept up to date throughout the system’s lifecycle and must be clear and complete enough for regulators or notified bodies to assess compliance.

**What the documentation must include**  
The documentation must contain all the elements listed in Annex IV of the regulation. These include details about the system’s design, development, intended purpose, risk management, testing, and performance. For small and medium-sized enterprises (SMEs), including start-ups, the Commission will provide a simplified documentation template. SMEs can use this form to meet their obligations, and notified bodies must accept it during conformity assessments.

**Integration with existing product regulations**  
If the AI system is part of a product already regulated under EU safety laws (like medical devices or vehicles), the provider can create one combined set of documentation that meets both the AI Act and the other applicable laws. This helps reduce duplication and administrative burden.

**Future updates to documentation requirements**  
The European Commission has the power to update Annex IV through delegated acts. This ensures that the documentation requirements can evolve with technical progress and continue to provide all the necessary information for compliance assessments.

##### **Article 12 – Record-Keeping**

**Logging is required throughout the system’s life**  
High-risk AI systems must be technically capable of automatically recording events (logs) during their entire operational lifetime. This ensures that the system’s functioning can be traced and reviewed when necessary.

**Logs must support safety and monitoring**  
The logging features must be designed to help identify situations where the system could pose a risk or undergo a significant change. They must also support post-market monitoring and help track the system’s operation, as required by other parts of the AI Act.

**Special logging rules for biometric identification systems**  
For high-risk AI systems used for real-time or post-remote biometric identification (as listed in Annex III, point 1(a)), the logs must include specific details. These include the start and end times of each use, the reference database used, the input data that triggered a match, and the identity of the people who verified the results.
##### **Article 13 – Transparency and Provision of Information to Deployers**

**AI systems must be understandable to users**  
High-risk AI systems must be designed and developed in a way that makes their outputs clear and interpretable. This ensures that users (deployers) can understand how to use the system properly and responsibly. The level of transparency must be appropriate to meet the legal obligations of both the provider and the deployer.

**Clear instructions must be provided**  
Each high-risk AI system must come with instructions for use, either in digital or physical form. These instructions must be concise, complete, accurate, and easy to understand. They should provide all the information a deployer needs to use the system safely and effectively.

**What the instructions must include**  
The instructions must include the provider’s identity and contact details, the system’s intended purpose, and its performance characteristics, such as accuracy, robustness, and cybersecurity. They must also explain any known risks, including those from foreseeable misuse, and describe how the system performs for specific groups of people if relevant. Where applicable, the instructions should include information about the data used to train and test the system, how to interpret its outputs, and any planned changes to its performance. Human oversight measures, technical requirements, expected system lifetime, and maintenance needs must also be included. If the system logs data, the instructions must explain how deployers can access and understand those logs.

##### **Article 14 – Human Oversight**

**AI systems must allow for human control**  
High-risk AI systems must be designed so that people can effectively oversee them while they are in use. This includes using appropriate tools and interfaces that make it possible for humans to monitor and intervene when needed.

**Oversight helps reduce risks**  
The goal of human oversight is to prevent or reduce risks to health, safety, or fundamental rights, especially in cases where other safety measures might not be enough. This includes risks that could arise from misuse that is reasonably foreseeable.

**Oversight measures must match the risk**  
The type of human oversight required depends on how risky the system is, how autonomous it is, and the context in which it is used. Oversight can be built into the system by the provider or set up as procedures for the deployer to follow. These measures must be identified before the system is placed on the market or put into use.

**Deployers must be able to monitor and intervene**  
The system must be provided in a way that allows the people responsible for oversight to:
- Understand what the system can and cannot do
- Monitor its performance and spot problems or unexpected behaviour
- Be aware of the risk of over-relying on the system’s output (known as automation bias)
- Interpret the system’s results correctly
- Choose not to use the system or override its output when necessary
- Stop the system safely using a “stop” button or similar method

**Extra rules for biometric identification systems**  
For high-risk AI systems used for biometric identification (as listed in Annex III, point 1(a)), no action or decision can be taken based on the system’s identification unless it has been verified and confirmed by at least two qualified people. However, this requirement does not apply in areas like law enforcement, migration, border control, or asylum if EU or national law considers it disproportionate.

##### **Article 15 – Accuracy, Robustness and Cybersecurity**

**AI systems must perform reliably and securely**  
High-risk AI systems must be designed and developed to achieve a suitable level of accuracy, robustness, and cybersecurity. These qualities must be maintained consistently throughout the system’s entire lifecycle.

**Accuracy must be measurable and declared**  
The system’s level of accuracy and the metrics used to measure it must be clearly stated in the instructions for use. The European Commission will work with experts and organisations to develop standard benchmarks and methods for measuring accuracy and robustness.

**Systems must handle errors and unexpected situations**  
High-risk AI systems must be resilient to errors, faults, or inconsistencies, whether they come from within the system or from its environment. This includes interactions with people or other systems. Providers must implement technical and organisational measures to ensure this resilience.

**Redundancy can help ensure robustness**  
To improve robustness, systems may include technical redundancy features such as backup systems or fail-safe mechanisms that allow the system to continue operating safely if something goes wrong.

**Learning systems must avoid harmful feedback loops**  
If a high-risk AI system continues to learn after being deployed, it must be designed to avoid feedback loops, where biased outputs influence future inputs. Providers must include safeguards to detect and reduce these risks.

**Protection against tampering is essential**  
High-risk AI systems must be secure against attempts by unauthorised individuals to manipulate their use, outputs, or performance. This includes protecting against exploitation of system vulnerabilities.

**Cybersecurity measures must address AI-specific threats**  
Cybersecurity protections must be appropriate to the risks and context in which the system is used. These protections should include defences against attacks like:

- Data poisoning (manipulating training data)
- Model poisoning (tampering with pre-trained components)
- Adversarial attacks (inputs designed to trick the system)
- Confidentiality breaches and model flaws

---- 
# **Section 3: Obligations of providers and deployers of high-risk AI systems and other parties (Art. 16 to 27)**

##### **Article 16 – Obligations of Providers of High-Risk AI Systems**

**Providers must ensure compliance**  
Before placing a high-risk AI system on the market or putting it into use, providers must make sure it fully complies with all the requirements listed in Section 2 of the AI Act.

**Provider identification must be clear**  
The provider’s name, registered trade name or trademark, and contact address must be clearly shown on the system itself. If that’s not possible, this information must be included on the packaging or in the accompanying documentation.

**A quality management system is required**  
Providers must have a quality management system in place that meets the standards set out in Article 17. This system helps ensure the AI system is developed and maintained properly.

**Documentation must be maintained**  
Providers must keep the technical documentation required under Article 18. This documentation proves the system meets the AI Act’s requirements and must be kept up to date.

**Logs must be preserved**  
If the provider controls the system, they must keep the logs that are automatically generated by the AI system, as required by Article 19.

**Conformity assessment is mandatory**  
Before the system is launched, it must go through a conformity assessment process as described in Article 43. This process checks whether the system meets all legal requirements.

**Declaration and CE marking**  
Providers must issue an EU declaration of conformity (Article 47) and affix the CE marking to the system, or to its packaging or documentation, to show that it complies with the regulation (Article 48).

**Registration obligations**  
Providers must register the high-risk AI system in the EU database as required under Article 49(1).

**Corrective actions and cooperation**  
If problems arise, providers must take corrective actions and share relevant information as required by Article 20. They must also be ready to demonstrate compliance with the law if requested by national authorities.

**Accessibility compliance**  
High-risk AI systems must also meet accessibility requirements under EU Directives 2016/2102 and 2019/882, ensuring they are usable by people with disabilities.

##### **Article 17 – Quality Management System**

**Providers must have a documented quality system**  
Providers of high-risk AI systems must set up a quality management system that ensures the system complies with the AI Act. This system must be clearly documented through written policies, procedures, and instructions.

**What the quality system must include**  
The system must cover several key areas:

- A strategy for meeting legal requirements, including how changes to the AI system will be managed.
- Methods for designing, controlling, and verifying the system’s design.
- Procedures for development, quality control, and quality assurance.
- Testing and validation steps before, during, and after development, including how often they are done.
- Technical standards used, and alternative methods if harmonised standards are not fully applied.
- Data management processes, including how data is collected, labelled, stored, filtered, and retained.
- A risk management system as required by Article 9.
- A post-market monitoring system, as outlined in Article 72.
- Procedures for reporting serious incidents, in line with Article 73.
- Communication processes with authorities, customers, and other stakeholders.
- Record-keeping systems for all relevant documents and information.
- Resource management, including measures to ensure supply chain security.
- An accountability framework that defines who is responsible for each part of the system.

**Proportionality based on provider size**  
The complexity of the quality management system should match the size of the provider’s organisation. However, all providers must still meet the required level of rigour to ensure their AI systems comply with the law.

**Integration with other sector-specific systems**  
If a provider already follows quality management rules under other EU laws (such as in healthcare or automotive sectors), they can include the AI-specific requirements within those existing systems.

**Special rules for financial institutions**  
Financial institutions that already follow internal governance rules under EU financial services law are considered to have met most of the quality management system requirements. However, they must still comply with the rules on risk management, post-market monitoring, and incident reporting.

##### **Article 18 – Documentation Keeping**

**Providers must store key documents for 10 years**  
Providers of high-risk AI systems must keep important documentation available for national authorities for at least 10 years after the system is placed on the market or put into service. This includes:

- The technical documentation required under Article 11
- The quality management system documentation from Article 17
- Any approved changes by notified bodies
- Decisions and documents issued by notified bodies
- The EU declaration of conformity from Article 47

**Rules for when a provider goes out of business**  
Each EU country must set rules to ensure that this documentation remains available to authorities even if the provider or their authorised representative goes bankrupt or shuts down before the 10-year period ends.

**Special rule for financial institutions**  
If the provider is a financial institution already subject to EU financial services law, they can keep the required technical documentation as part of their existing legal documentation obligations under that law.

##### **Article 19 – Automatically Generated Logs**

**Providers must keep system logs**  
Providers of high-risk AI systems must retain the logs that are automatically generated by their systems, as described in Article 12(1), as long as those logs are under their control.

**Logs must be kept for at least six months**  
Unless other EU or national laws say otherwise, especially laws related to data protection, these logs must be stored for a period that fits the system’s intended purpose, and for no less than six months.

**Special rule for financial institutions**  
If the provider is a financial institution already subject to EU financial services law, they can store these logs as part of their existing documentation obligations under that law.

##### **Article 20 – Corrective Actions and Duty of Information**

**Providers must act if their AI system is non-compliant**  
If a provider believes, or has reason to believe, that a high-risk AI system they’ve placed on the market or put into use does not comply with the AI Act, they must take immediate corrective action. This could include fixing the issue, withdrawing the system, disabling it, or recalling it. They must also inform distributors, and if relevant, deployers, authorised representatives, and importers.

**Immediate action required if the system poses a risk**  
If the provider becomes aware that the AI system presents a risk (as defined in Article 79(1)), they must investigate the cause right away. If a deployer reported the issue, the provider must work with them to understand what went wrong. The provider must then inform the relevant market surveillance authorities and, if applicable, the notified body that certified the system. They must explain the nature of the problem and what corrective steps have been taken.

##### **Article 21 – Cooperation with Competent Authorities**

**Providers must share information when asked**  
If a national authority makes a justified request, providers of high-risk AI systems must give them all the necessary documents and information to prove that the system complies with the AI Act. This information must be provided in a language that the authority can easily understand, chosen from the official languages of the EU.

**Access to system logs**  
If requested, providers must also give the authority access to the system’s automatically generated logs (as described in Article 12), as long as those logs are under the provider’s control.

**Confidentiality must be respected**  
Any information that authorities receive under this article must be handled according to the confidentiality rules set out in Article 78.

##### **Article 22 – Authorised Representatives of Providers of High-Risk AI Systems**

**Non-EU providers must appoint a representative in the EU**  
If a provider of a high-risk AI system is based outside the EU, they must appoint an authorised representative within the EU before making the system available on the EU market. This must be done through a written agreement.

**Representatives must be empowered to act**  
The provider must give the authorised representative the authority to carry out specific tasks listed in the mandate. The representative must also provide a copy of this mandate to national authorities if requested, in an official EU language chosen by the relevant Member State.

**Responsibilities of the authorised representative**  
The representative must:

- Check that the provider has completed the EU declaration of conformity and technical documentation, and that the system has passed the required conformity assessment.
- Keep key documents (including the provider’s contact details, declaration of conformity, technical documentation, and any certificates) for 10 years after the system is placed on the market.
- Provide authorities with all necessary information to prove the system complies with the AI Act, including access to system logs if the provider controls them.
- Cooperate with authorities in any actions taken to reduce or manage risks related to the AI system.
- Ensure registration requirements are met, or verify that the provider has correctly registered the system.

**Authorities can contact the representative directly**  
The authorised representative can be contacted by authorities instead of the provider for any matters related to compliance with the AI Act.

**Ending the mandate if the provider breaks the rules**  
If the representative believes the provider is not following the AI Act, they must end the mandate and immediately inform the relevant market surveillance authority and, if applicable, the notified body, explaining why the mandate was terminated.

##### **Article 23 – Obligations of Importers**

**Importers must check compliance before placing AI systems on the market**  
Before selling a high-risk AI system in the EU, importers must make sure it meets all legal requirements. This includes checking that:

- The provider has completed the required conformity assessment (Article 43),
- The technical documentation is in place (Article 11 and Annex IV),
- The system has a CE marking, an EU declaration of conformity (Article 47), and instructions for use,
- The provider has appointed an authorised representative in the EU (Article 22).

**Action required if the system is non-compliant or falsified**  
If the importer suspects that the system doesn’t comply with the law, is fake, or has fake documentation, they must not place it on the market until the issue is resolved. If the system poses a risk (as defined in Article 79(1)), the importer must inform the provider, the authorised representative, and the relevant market surveillance authorities.

**Importer identification must be clear**  
Importers must include their name, registered trade name or trademark, and contact address on the system, its packaging, or its documentation.

**Safe storage and transport**  
While the system is under the importer’s responsibility, they must ensure that storage and transport conditions do not compromise its compliance with the AI Act.

**Documentation must be kept for 10 years**  
Importers must keep a copy of the notified body’s certificate (if applicable), the instructions for use, and the EU declaration of conformity for 10 years after the system is placed on the market or put into service.

**Cooperation with authorities**  
Importers must provide authorities with all necessary information and documentation to show the system complies with the law. This must be in a language the authority can understand. They must also ensure that the technical documentation can be made available.

**Support risk mitigation efforts**  
Importers must cooperate with authorities in any actions taken to reduce or manage risks related to the AI system they placed on the market.

##### **Article 24 – Obligations of Distributors**

**Distributors must check compliance before selling**  
Before making a high-risk AI system available on the market, distributors must check that:

- The system has the CE marking,
- It comes with the EU declaration of conformity (Article 47),
- It includes instructions for use,
- The provider and importer have met their obligations under Articles 16(b) and (c), and 23(3).

**Distributors must not sell non-compliant or risky systems**  
If a distributor believes, based on the information they have, that the system doesn’t meet the legal requirements or poses a risk (as defined in Article 79(1)), they must not sell it until the issue is resolved. If the system is risky, they must inform the provider or importer.

**Safe handling is required**  
Distributors must ensure that storage and transport conditions do not compromise the system’s compliance with the AI Act while it is under their responsibility.

**Corrective action if problems are found**  
If a distributor finds out that a system they’ve already sold is non-compliant, they must take corrective action. This could mean fixing the issue, withdrawing the product, or recalling it. If the system poses a risk, they must also inform the provider or importer and notify the relevant authorities, explaining the issue and what actions were taken.

**Provide information to authorities when asked**  
If requested by a competent authority, distributors must provide all relevant information and documentation about their actions to show that the system complies with the law.

**Cooperate with authorities**  
Distributors must work with authorities on any actions taken to reduce or manage risks related to the AI systems they’ve placed on the market.

##### **Article 25 – Responsibilities Along the AI Value Chain**

**When others become providers**  
Distributors, importers, deployers, or any third party will be treated as the provider of a high-risk AI system, and must follow all provider obligations under Article 16, if they:

- Put their own name or brand on a high-risk AI system already on the market,
- Make a substantial modification to a high-risk AI system that keeps it classified as high-risk,
- Change the intended purpose of an AI system (including general-purpose AI) so that it becomes high-risk under Article 6.

**Original providers are no longer responsible in these cases**  
If one of the above changes happens, the original provider is no longer considered responsible for that specific system. However, they must still cooperate with the new provider by sharing necessary information, technical access, and support, unless they had clearly stated that their system must not be modified into a high-risk AI system.

**Product manufacturers as providers**  
If a high-risk AI system is a safety component of a product covered by EU product safety laws (listed in Annex I), the product manufacturer becomes the provider if:

- The AI system is sold with the product under the manufacturer’s name or brand,
- The AI system is activated under the manufacturer’s name after the product is sold.

**Agreements between providers and third-party suppliers**  
Providers and third parties who supply tools, services, components, or processes for high-risk AI systems must sign a written agreement. This agreement must clearly define what information, access, and support the third party must provide to help the provider meet their legal obligations. This rule does **not** apply to open-source tools or components (except general-purpose AI models).

**Voluntary contract templates**  
The AI Office may create and publish **voluntary model contract terms** to help providers and third-party suppliers agree on responsibilities. These templates will be free to use and available in a user-friendly digital format. They will also consider sector-specific needs.

**Protection of confidential information**  
All cooperation and information sharing must respect intellectual property rights, business confidentiality, and trade secrets, in line with EU and national laws.

##### **Article 26 – Obligations of Deployers of High-Risk AI Systems**

**Use in Line with Instructions**  
Deployers must use high-risk AI systems strictly according to the provider’s instructions. They must assign human oversight to individuals with the necessary competence, training, and authority. These obligations do not interfere with the deployer’s freedom to organise internal resources.  

**Data Control and Monitoring**  
If deployers control the input data, they must ensure it is relevant and representative for the system’s intended purpose. They must monitor the system’s operation and, if risks or serious incidents arise, inform the provider, distributor, and relevant authorities without delay. Use must be suspended if the system presents a risk under Article 79(1).  

**Logging Requirements**  
Deployers must retain logs automatically generated by the high-risk AI system for at least six months, unless otherwise required by law. Financial institutions may fulfil this obligation through existing governance documentation under EU financial services law.  

**Worker Notification**  
Before deploying a high-risk AI system in the workplace, employers must inform affected workers and their representatives. This must be done in accordance with applicable Union and national laws and practices.  

**Public Sector Registration**  
Public authorities and EU institutions must ensure the system is registered in the EU database before use. If it is not registered, they must not use it and must inform the provider or distributor.  

**Biometric Identification in Law Enforcement**  
Deployers using post-remote biometric identification systems must obtain prior authorisation from a judicial or administrative authority, unless used for initial suspect identification based on objective facts. Use must be targeted and proportionate. Untargeted use is prohibited, and no adverse legal decisions may be based solely on system output.  

**Documentation and Reporting**  
Each use of post-remote biometric identification must be documented in the relevant police file and made available to authorities upon request. Annual reports must be submitted to market surveillance and data protection authorities, excluding sensitive operational data. Member States may adopt stricter national rules.  

**Transparency and Cooperation**  
Deployers must inform individuals when decisions affecting them are made using high-risk AI systems. They must also cooperate with competent authorities in any actions taken to enforce the AI Act.

##### **Article 27 – Fundamental Rights Impact Assessment for High-Risk AI Systems**

**Who must conduct the assessment**  
Before deploying a high-risk AI system under Article 6(2) (excluding those used in Annex III, point 2), public sector bodies, private entities providing public services, and deployers using systems under Annex III, points 5(b) and 5(c), must carry out a fundamental rights impact assessment.

**What the assessment must include**  
The assessment must describe:
- how the AI system will be used in the deployer’s processes,
- the timeframe and frequency of its use,
- the categories of people likely to be affected,
- the specific risks of harm to those people, based on provider information,
- the human oversight measures in place,
- and the actions to be taken if those risks materialise, including governance and complaint mechanisms.

**When and how to update the assessment**  
The obligation applies to the first use of the system. Deployers may reuse previous assessments or rely on the provider’s assessment in similar cases. If any relevant element changes or becomes outdated, the deployer must update the assessment.

**Notification to authorities**  
Once completed, the deployer must notify the market surveillance authority by submitting the filled-out assessment template. An exemption applies in cases covered by Article 46(1).

**Relation to data protection assessments**  
If a data protection impact assessment has already been conducted under GDPR Article 35 or Directive 2016/680 Article 27, the fundamental rights impact assessment must complement it.

**Support from the AI Office**  
The AI Office will provide a standardised questionnaire template, including an automated tool, to help deployers complete the assessment more easily.

---
# **Section 4: Notifying authorities and notified bodies**

##### **Article 28 – Notifying Authorities**

**Designation and Cooperation**  
Each Member State must designate or establish at least one notifying authority responsible for setting up, carrying out, and monitoring the procedures for assessing, designating, and notifying conformity assessment bodies. These procedures must be developed in cooperation with notifying authorities from other Member States.

**Role of National Accreditation Bodies**
Member States may assign the tasks of assessment and monitoring to a national accreditation body, in line with Regulation (EC) No 765/2008.

**Independence and Impartiality**  
Notifying authorities must be structured to avoid conflicts of interest with conformity assessment bodies. They must ensure objectivity and impartiality in their operations.

**Separation of Functions**  
Decisions on the notification of conformity assessment bodies must be made by individuals who were not involved in the assessment of those bodies.

**Prohibition on Commercial Services**
Notifying authorities must not offer or provide any services that conformity assessment bodies perform, nor any consultancy services on a commercial or competitive basis.

**Confidentiality**  
All information obtained by notifying authorities must be kept confidential, in accordance with Article 78.

**Competence and Staffing**  
Notifying authorities must have a sufficient number of competent personnel with expertise relevant to their tasks, including in information technology, AI, law, and fundamental rights supervision.

##### **Article 29 – Application of a Conformity Assessment Body for Notification**

**Submission of Application**  
Conformity assessment bodies must apply for notification to the notifying authority in the Member State where they are established.

**Required Documentation**  
The application must include:
- a description of the conformity assessment activities,
- the modules and types of AI systems the body is competent to assess,
- and an accreditation certificate (if available) issued by a national accreditation body confirming compliance with Article 31.

**Supporting Documents from Other Designations**  
Any valid documents related to existing designations under other Union harmonisation legislation must be included in the application.

**Alternative to Accreditation Certificate**  
If no accreditation certificate is available, the body must provide all necessary documentation to allow the notifying authority to verify, recognise, and monitor compliance with Article 31.

**Use of Existing Designation Documents**  
Documents and certificates from other Union designations may support the application under this Regulation. The notified body must update its documentation whenever relevant changes occur to ensure ongoing compliance with Article 31.

##### **Article 30 – Notification Procedure**

**Eligibility for Notification**  
Only conformity assessment bodies that meet the requirements of Article 31 may be notified by notifying authorities.

**Notification Process**  
Notifying authorities must notify the European Commission and other Member States using the Commission’s electronic notification tool.

**Notification Content**  
The notification must include full details of the conformity assessment activities, the modules involved, the types of AI systems covered, and proof of competence. If no accreditation certificate is provided (as per Article 29(2)), the notifying authority must submit documentary evidence of the body’s competence and monitoring arrangements.

**Objection Periods**  
The conformity assessment body may begin operating as a notified body if no objections are raised:
- within two weeks if the notification includes an accreditation certificate,
- or within two months if it includes only documentary evidence.

**Handling Objections**  
If objections are raised, the Commission must consult with the relevant Member States and the conformity assessment body. It will then decide whether the notification is justified and communicate its decision to the Member State and the body concerned.

##### **Article 31 – Requirements Relating to Notified Bodies**

**Legal Status**  
A notified body must be legally established in an EU Member State and have its own legal identity.

**Organisational and Technical Standards**  
It must meet strict standards for organisation, quality management, resources, and cybersecurity to carry out its tasks properly.

**Structure and Trust**  
Its internal structure and operations must inspire trust in its assessments and results.

**Independence**  
The body must be independent from the AI provider it assesses, from any business with a financial interest in the system, and from competitors. However, it may use AI systems it has assessed if needed for its own operations or personal use.

**No Conflicts of Interest**  
Staff and management must not be involved in designing, developing, marketing, or using high-risk AI systems. They must avoid any activity that could compromise their impartiality, especially consultancy services.

**Impartiality**  
The body must have clear procedures and a structure that ensures impartiality in all its work and promotes this principle throughout the organisation.

**Confidentiality**  
It must keep all information obtained during assessments confidential, unless disclosure is legally required. Staff are bound by professional secrecy, except when reporting to the national notifying authority.

**Proportional Approach**  
Its procedures must consider the size, sector, and complexity of the provider and the AI system being assessed.

**Liability Insurance**  
It must have suitable liability insurance unless the Member State takes on this responsibility directly.

**Competence and Integrity**  
The body must be capable of performing all its tasks with high professional standards and expertise, whether done internally or by others under its responsibility.

**Internal Expertise**  
It must have enough qualified staff in areas like AI, data, law, and computing to evaluate both its own work and that of any external partners.

**Participation in Standards and Coordination**  
It must take part in EU coordination activities and stay up to date with relevant standards, either directly or through representation.

##### **Article 32 – Presumption of Conformity with Requirements Relating to Notified Bodies**

**1. Use of Harmonised Standards**  
If a conformity assessment body complies with relevant harmonised standards published in the Official Journal of the European Union, it is presumed to meet the requirements set out in Article 31—provided those standards cover the applicable requirements.

##### **Article 33 – Subsidiaries of Notified Bodies and Subcontracting**

**Compliance of Subcontractors and Subsidiaries**  
If a notified body subcontracts tasks or uses a subsidiary for conformity assessments, it must ensure they meet the same requirements as set out in Article 31 and must inform the notifying authority.

**Full Responsibility**  
The notified body remains fully responsible for all tasks carried out by its subcontractors or subsidiaries.

**Provider Agreement and Transparency**  
Subcontracting or delegation to a subsidiary is only allowed with the provider’s agreement. Notified bodies must publish a list of their subsidiaries.

**Record-Keeping**  
Documents related to the qualifications of subcontractors or subsidiaries and the work they perform must be kept available for the notifying authority for five years after the subcontracting ends.

##### **Article 34 – Operational Obligations of Notified Bodies**

**Conformity Assessments**  
Notified bodies must verify that high-risk AI systems comply with the requirements of the AI Act using the conformity assessment procedures outlined in Article 43.

**Minimising Burden on Providers**  
When carrying out their tasks, notified bodies must avoid placing unnecessary burdens on providers. They must consider the provider’s size, sector, structure, and the complexity of the AI system—especially to reduce administrative and compliance costs for micro and small enterprises. However, they must still apply the necessary level of scrutiny to ensure full compliance with the Regulation.

**Documentation and Cooperation**  
Notified bodies must make all relevant documentation, including that provided by the AI system provider, available to the notifying authority upon request. This is to support the authority’s assessment, designation, notification, and monitoring responsibilities.

##### **Article 35 – Identification Numbers and Lists of Notified Bodies**

**Unique Identification Numbers**  
The European Commission assigns a single identification number to each notified body, even if that body is notified under multiple EU laws.

**Public List of Notified Bodies**  
The Commission publishes a list of all notified bodies under this Regulation, including their identification numbers and the specific activities they are authorised to perform. This list is kept up to date to ensure transparency and accuracy.

##### **Article 36 – Changes to Notifications**

**Notification of Changes**  
Any changes to a notified body’s status must be communicated by the notifying authority to the Commission and other Member States using the electronic tool mentioned in Article 30(2). Extensions of scope follow the same procedures as in Articles 29 and 30.

**Other Changes**  
For changes other than scope extensions, specific procedures apply. If a notified body plans to stop its activities, it must inform the notifying authority and affected providers as early as possible, at least one year in advance if planned. Certificates may remain valid for up to nine months if another notified body agrees in writing to take over responsibility and completes a full assessment within that time.

**Loss of Compliance**  
If a notifying authority suspects that a notified body no longer meets the requirements of Article 31 or is failing its duties, it must investigate immediately. The body must be informed of the concerns and given a chance to respond. If non-compliance is confirmed, the authority must restrict, suspend, or withdraw the designation and inform the Commission and Member States.

**Provider Notification and File Handling**  
If a designation is restricted, suspended, or withdrawn, the notified body must inform affected providers within 10 days. The notifying authority must ensure that the body’s files are preserved and made available to other authorities upon request.

**Impact on Certificates**  
The notifying authority must assess how the change affects issued certificates, report its findings to the Commission and Member States within three months, and require the withdrawal of any improperly issued certificates. It must also inform relevant national authorities and ensure appropriate action is taken to protect health, safety, or fundamental rights.

**Validity of Certificates During Suspension or Restriction**  
Certificates remain valid if the notifying authority confirms there is no risk and outlines a plan to resolve the issue, or if no new certificates will be issued and the body can still monitor existing ones. If not, the provider must confirm within three months that another notified body will temporarily take over monitoring responsibilities.

**Validity of Certificates After Withdrawal**  
If a designation is withdrawn, certificates may remain valid for nine months if the national authority confirms no risk and another notified body agrees to take over and completes its assessment within 12 months. The national authority may extend certificate validity in three-month increments, up to a total of 12 months.

**Communication of Changes**  
Any authority or notified body taking over responsibilities must immediately inform the Commission, other Member States, and other notified bodies.






Section 5: Standards, conformity assessment, certificates, registration