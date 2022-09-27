# Domain 1: Security and Risk Management

## Security Concepts

1. Ethics
    - (ISC)2 Code of Professional Ethics
      1. Protect society, the common good, neccessary public trust and confidence and the infrastructure
      2. Act honorably, honestly, justly, responsibly and legally
      3. Provide diligent and competent service to principle
      4. Advance and protect the professional
    - Organisational Code of Ethics
    - RFC 1087 - Ethics and the Internet - outline what should not do
      1. seeks to gain unauthorized access to resources of the internet
      2. disrupts the intended use of the internet
      3. wastes resources (people, capacity, computer) through such actions
      4. destroys the integrity of computer-based information
      5. comprimises the privacy of users
2. CIA Triad
    - Confidentiality: measure used to ensure the protection of the secrecy of data, objects or resources. The goal is to preveint or minimise unauthorized access to data.
      - Sensitivity: quality of informatio, which could hard or damage if disclosed.
      - Discretion: is an act of decision where an operator can influence or control disclosure in order to minimise hard or damage
      - Criticality: the level to which information is mission cirtical is its measure of criticality.
      - Concealment: is the act of hiding or preventing disclosure.
      - Secrecy: is the act of keeping something a secret.
      - Privacy: refer to keeping information confidential that is personally identifiable or that might cause harm if revealed.
      - Seclusion: involves storing something in an out-of-the-way localtion with strict access controls.
      - isolation: is the act of keeping something separate from others.
    - Integrity: is the concept of protecting the reliability and correctness of data.
    - Availability: means authorised subjects are granted timely and uninterrupted access to objects.
3. Authenticity: security concept that data is authentic and originates from its alleged source.
4. Nonrepudiation: ensure that subject of an activity or who caused an event cannot deny that the event occurred.
5. AAA: Authentication, authorisation, accounting
    - Identification: is claiming to be an identity when attempting to access a secured area or system.
    - Authentication: is proving that you are that claimed identity.
    - Authorisation: is defining the permission of a resource and object access for a speciric identity or subject.
    - Auditing: is recoding a log of the events and activities related to the system and subjects.
    - Accounting: is reviewing log files to check for compliance and violations in order to hold subjects accountable for their actions
6. Defense in Depth: layering, is the use of multiple controls in a series
7. Encryption: is the science of hiding the meaning or intent of a communication from unintended recipients

## Security Governance

1. Security Governance: is the collection of practices related to supporting, evaluating, defining and directing the security efforts of an organisation. Optimally, security governance is performed by a board of directors

[*] the best security plan is useless without one key factor: approval by senior management.

## Organisational Roles and Responsibility

1. Senior Manager: role is assigned to the person who is ultimately responsible for the security maintained by an organisation and who should be most concerned about the protection of its assets.
2. Security Professional: is responsible for following the directives mandated by senior management
3. Asset Owner: is responsible classifying information for placement and protection
4. Custodian: is reponsible for the tasks of implementing the prescribed protection defined by the security policy and senior management.
5. User: is assigned to any person who has access to the secured system
6. Auditor: is responsible for reviewing and verifying that the security policy is properly implemented and the derived security solutions are adequate
7. Security Leader: serves as the subject matter expert on issues of CIA
8. Business Leader: Understands the mission, goals, objectives of the broader organisation

## Due Deligence and Due Care

- Due diligence: security professional must take reasonable measures to investigate security risk - knowing what should be done and planning for it. due diligence is establishing a plan, policy and process to protect the interest of an organisation
- Due care: security professional must fulfilling legal responsibilities and professional best practices - doing right action at the right time. Due care is practicing the individual activities that maintain the due diligence

## Security Control Frameworks

1. COBIT - Control Objectives for IT - business focus control framework
2. ISO 27001 - cybersecurity control objectives
3. ISO 27002 - cybersecurity control implementation
4. ISO 27701 - privacy controls
5. ISO 31000 - risk management programs
6. NIST 800-53 - Security and Privacy Controls for Information Systems and Organisations - mandatory for federal agencies
7. NIST Cybersecurity Framework - identify protect detect response and recovery

PII - Personally Identifiable Information - any information that can be traced back to an individual
PHI - Protected Health Information - Individually identifiable health records governed under HIPAA

## GAPP - Generally Accepted Privacy Principles

1. Management
2. Notice
3. Choice and Consent
4. Collection
5. Use, Retention and Disposal
6. Access
7. Disclosure to third parties
8. Security
9. Quality
10. Monitoring and Enforcement

## Data breach Consequences

1. Reputation damange
2. Identify theft
3. Fines
4. Intellectual property theft

## Security Policy, Standards, Procedures and Guidelines

1. Security policy - top tier, document that defines the scope of security needed by the organisation and discusses the assets that require protection. Overview or generalisation of an organisation's security needs - mandatory

     - acceptable use policy - aup - define level of acceptable performance and expectation of behaviour and activity

2. Security standards - define compulsory requirements for the homogenous use of hardware, software, technology and security controls - mandatory
3. Security beseline - define minimum level of security that every system throughout the organisation must meet
    - CIS - contain baseline for software and system
4. Guideline - offer recommendations on how standards and baselines are implemented - optional
5. Security Procedures - is a detailed, step-by-step how-to document that describes the exact actions necessary to implement a specific security mechanism, control or solution. - mandatory or optional

## Business Impact Analyst - Identifies and prioritises risks

1. Annualised Loss Expectancy
2. Single Loss Expectancy

## Threat Modeling - is the security process where potential threats are identified, categorised and analysed

1. proactive - perform proactive during design and development
2. reactive - perform once a product has been deployed - also called threat hunting

STRIDE - microsoft threat categorisation scheme

1. Spoofing - gaining access to a target through the use of falsified identity
2. Tampering - any action resulting in unauthorised changes or manipulation of data
3. Repudiation - ability of a user or attacker to deny having performed action
4. Information disclosure - revelation or distribution of private, confidential information to external
5. Denial of service - an attack that attempts to prevent authorised use of a resource
6. Elevation of privilege - an attack where a limited user account is transformed into account with greater privileges

PASTA - Process for Attack Simulation and Threat Analysis - seven-stage threat modeling methodology - risk-centric approach that aims at selecting or developing countermeasure in relation to the value of the assets to be protected

1. Stage I definition of objective for the analysis of risks
2. Stage II definition of the technocal scope
3. Stage III Application decomposition and analysis
4. Stage IV Threat analysis
5. Stage V Weakness and vulnerability analysis
6. Stage VI Attack modeling and simulation
7. Stage VII Risk analysis and management

## Prioritization and Response

rate the risk

1. probability x damage potential
2. Disaster Repoducibility Exploitability Affected Users and Discoverability (DREAD)
   1. Damage Potential - how severe is the damage likely to be if the threat is realised
   2. Reproducibility - how complicated is it for atatcker to reproduce the exploit
   3. Exploitability - how hard is it to perform the attack
   4. Affected Users - how many user are likely to be affected by the attack
   5. Discoverability - how hard is it for an attacker to discover weakness

collusion - when several people work together to perpetrate a crime

## Risk Terminology and Concept

1. Asset - anything used in a business process or task such as person place or thing
2. Asset valuation - value assigned to an asset
3. Threat - any potential occurrence that may cause an undesirable or unwanted outcome for an organisation or  far a specific asset
4. Threat agent/actors - are usually people  or programs or hardware that exploit vulnerability to cause harm to targets
5. Threat events - are accidential occurrences or intentional exploitations of vulnerabilities
6. Threat vector - path or mean by which an attack or attacker can gain access to target in order to cause harm
7. Vulnerability - weakness in an asset or the weakness of a safeguard
8. Exposure - is being susceptible to asset loss because of a threat
9. Risk - is the possibility or likelihood that a threat will exploit a vulnerability to cause harm to an asset -- risk = threat * vulnerability
10. Safeguard - protection mechanism that removes or reduce vulnerability
11. Attack - intentional attempted exploitation of a vulnerability by threat agent to cause damage
12. Breach - is the occurrence of a security mechanism being bypassed by threat agent. A breach is a successful attack

Asset valuation - if asset has no value, there is no need to provide protection for it. A primary goal of risk analysis is to ensure that only cost-effective safeguards are deployed

## Risk Assessement Methodologies

1. Quantitative risk analysis - assign real dollar figures to the loss of an asset and is based on mathematical calculations
2. Qualitative risk analysis - assigns subjective and intangible values to the loass of an asset

The six major elements of quantitative risk analysis

1. Assign asset value (AV)
2. Calculate exposure factor (EF)
3. Calculate single loss expectancy (SLE)
4. Assess the annualised rate of occurrence (ARO)
5. Derive the annualised loss expectancy (ALE)
6. Perform cost/benefit analysis of countermeasures

SLE = AV x EF
ALE = SLE x ARO
ALE = AV x EF x ARO

## Risk Responses

1. Mitigation or reduction - implementation of safeguards, security controls to reduce or eliminate vulnerabilities or block threats
2. Assignment or transfer - is the placement of the responsibility of loss due to a risk onto another entity such as purchasing insurance and outsourcing are common form of assigning or transferring risk
3. Deterrence - process of implementing deterrents th would-be violators. the goal is to convince a threat agent not to attack. - seucrity camera, security guard, guard dog
4. Avoidance - process of selecting alternate options to have less associated risk - fly instead of drive
5. Acceptance - is the result after a cost/benefit analysis show countermeasure costs would outweigh the possible cost of loss due to a risk. In most case, accepting risk requires a clearly written statement that indicates why a safeguard was not implemented, who is responsible for the decision, who will be responsible for the loss if the risk is realised, usually signed by senior management
6. Reject or ignore - an unacceptable possible response to risk. denying that risk exists and hoping that it will never be realised are not valid prudent duecare/due diligence responses to risk

Total risk = threats x vulnerabilities x asset value

value of safeguard = (ALE before safegaurd) - (ALE after safeguard) - cost of safeguard

Risk appetite - is the total amount of risk that an organisation is willing to shoulder in aggregate across all assets

## Categories of security controls

1. administrative - management control, managerial control, procedural control
2. logical/technical - encryptions, firewall, etc
3. physical - real-world - guard, fences etc

## Type of controls

1. preventive - thwart or stop unwant or unauthorised activity from occurring
2. deterrent - discourage security policy violation
3. detective - deployed to discover or detect unwant or unauthorised activity
4. compensating - deployed to provide various options to other existing controls to aid in enforcement and support of security policies - if preventive control fails to stop deletion of a file, a backup can be a compensation conrol - if fire prevention fail, a compensation control is to have disaster recovery plan
5. corrective - modified environment to return systems to normal after an unwanted or unauthorised activity has occurred - terminating malicious activity or rebooting a system
6. recovery - an extension of corrective congtrol but have more advnaced or complex abilities.
7. directive - is deployed to direct, confine or control the actions of subjects to force or encourage compliance with security policies

## Risk Reporting and Documentation

1. Risk reporting - key task to perform at the conclusion of a risk analysis.
2. Risk register or risk log is a document that inventories all the identified risks to an organisation or system or within an individual project. it should include the following:
   1. Identifying risks
   2. evaluating the severity of and prioritizing those risks
   3. prescribe responses to reduce or eleminate the risks
   4. tracking the progress of risk mitigation
3. Risk Maturity Model (RMM)
   1. Ad hoc - a chaotic starting point from which all organisation initiate risk management
   2. Preliminary - loose attempts are made to follow risk management process, but each department may perform risk assessment uniquely
   3. Defined - a common or standardised risk framework is adopted organisation-wide
   4. Integrated - risk management operations are integrated into business process, metrics are used to gather effectiveness data and risk is considered an element in business strategy decisions
   5. Optimised - risk management focuses on achieving objectives rather than just reacting to external threats; increased strategic planning is geared toward business success rather than just avoiding incidents; and lessons learned are reintegrated into the risk management process
4. EOL - End of Life - is the point at which a manufacture no longer produces a product. service and support may continue for a period of time after EOL
5. EOS - End of Support or EOSL - End of Service Life - is when systems are no longer receiving update and support from the vendor

## Risk Frameworks

1. risk framwork is a guideline for how risk is to be assessed
2. NIST established the Risk Management Framework (RMF) - mandatory for federal agencies - 2010 - SP 800-37 Rev.2 consist of 6 cyclical phases
   1. prepare to execute the RMS
   2. categorise the system and information process
   3. select initial set of control for system to reduce risk to acceptable level
   4. implement the control and describe how the controls are employed within the system
   5. assess the control to determine if the control are implemented correctly
   6. authorise the system based on determination that risk is acceptable
   7. monitor the system and the associated controls on an ongoing basis
3. ISO/IEC 31000 - risk management - guidelines 
4. ISO/IEC 27005 - information technology 0 security techniques - information security risk management
5. Committee of Sponsoring Organisations (COSO) - of the Treadway Commission's Enterprise Risk Management - Integrated Framework
6. ISACA's Risk IT Framework
7. Operationally Critical Threat, Asset, and Vulnerability Evaluation (OCTAVE)
8. Threat Agent Risk Assessment (TARA)

## Social Engineering

1. whaling - a form of spear phishing that targets specific high-value individuals such as CEO or other C-level
2. smishing - short message service phishing - social engineering attack that occurs over SMS
3. vishing - voice based phishing or SpIT (spam over internet telephony) - is phishing done over any telephony or voice communication system
4. shoulder surfing - is often a physical world or in-person form of social engineering
5. invoice scams - social engineering attacks that often attempt to steal funds from an organisation through the presentation of a false invoice
6. Hoax - social engineering designed to convince targets to perform an action that will cause problems or reduce their IT security
7. Tailgating and Piggybacking - unauthoised entity gain access to facility under the authorisation of a valid worker but without their knowledge
8. Typo Squatting - a practice employed to capture and redirect traffic when a user mistype the domain name of intended resource.
9. URL hijecking - practice of displaying a link or advertisememnt that looks like that of a well-known product
10. Clickingjacking
