# Glossary

## Lecture 1: Security Controls

| Term | Definition |
|------|------------|
| Information Security | The practice of protecting data and systems from unauthorized access, use, disclosure, disruption, modification, or destruction through the application of various controls and measures. |
| Confidentiality | Ensuring that sensitive data is accessible only to authorized individuals, entities, or processes, and preventing disclosure to unauthorized parties. |
| Integrity | Maintaining and assuring the accuracy, consistency, and trustworthiness of data throughout its entire lifecycle, preventing unauthorized modification. |
| Availability | Ensuring that authorized users have reliable and timely access to resources, services, and information when needed. |
| Threat | Any potential danger that could exploit a vulnerability to breach security and cause harm to information assets or systems. |
| Vulnerability | A weakness or flaw in system security procedures, design, implementation, or internal controls that could be exploited to compromise security. |
| Exploit | A defined way to breach the security of an information system through a vulnerability, whether intentionally crafted malware or an inadvertent coding error. |
| Risk | The potential for loss, damage, or destruction of assets or data as a result of a threat exploiting a vulnerability. |
| Security Control | A safeguard or countermeasure prescribed to protect the confidentiality, integrity, and availability of an information system. |
| Technical Control | Hardware and software mechanisms used to protect assets and control access, such as authentication systems, encryption, and intrusion detection systems. |
| Encryption | The process of converting data into a coded form to prevent unauthorized access, using mathematical algorithms and keys. |
| Firewalls | Network security systems that monitor and control incoming and outgoing network traffic based on predetermined security rules. |
| Antivirus | Software designed to detect, prevent, and remove malicious software, including viruses, worms, trojans, and other types of malware. |
| Managerial Control | Administrative measures to manage security risks and protect assets, including policies, procedures, and guidelines. |
| Security Policy | A formal document that defines acceptable use, protection responsibilities, and security expectations for an organization's information technology resources. |
| Risk Assessment | A systematic process of evaluating potential risks and their likelihood of occurrence, analyzing vulnerabilities, and determining appropriate protective measures. |
| Compliance | Adhering to established rules, regulations, laws, and standards that are mandated by external authorities or internal policies. |
| Operational Control | Day-to-day security procedures and mechanisms implemented to protect assets and maintain secure operations. |
| Security Awareness | Educational programs and activities designed to ensure that personnel understand security risks and their responsibilities in protecting organizational assets. |
| Incident Response | A structured approach to handling and managing the aftermath of security breaches or cyberattacks, including detection, analysis, containment, and recovery. |
| Physical Control | Tangible measures implemented to prevent unauthorized physical access to resources, including barriers, locks, security guards, and surveillance systems. |
| Access Control System | A collection of mechanisms that work together to create a security architecture for controlling resource access based on authority levels and need. |
| Preventive Control | Measures designed to stop unwanted or unauthorized activities from occurring in the first place. |
| Deterrent Control | Mechanisms intended to discourage potential attackers by making the target appear less attractive or increasing the perceived risk of detection. |
| Psychological Deterrence | Methods that create fear of consequences or negative outcomes to discourage potential security violations. |
| Detective Control | Systems and procedures that identify and record significant events, security breaches, or attempted breaches after they have occurred. |
| Alert Threshold | A predetermined level or condition that, when reached, triggers a notification or response action in a security monitoring system. |
| Corrective Control | Measures designed to react to and reduce the impact of an incident that has already occurred, helping restore systems to normal operations. |
| Compensating Control | Alternative security measures implemented when primary controls cannot be employed due to legitimate business or technical constraints. |
| Patch | A piece of software designed to update a computer program or system to fix security vulnerabilities and other bugs. |
| Directive Control | Measures that direct, confine, or control actions by specifying proper procedures and behaviors to achieve security objectives. |

## Lecture 2: Fundamental Concepts

| Term | Definition |
|------|------------|
| CIA Triad | The three fundamental principles of information security: Confidentiality (protecting data from unauthorized access), Integrity (ensuring data accuracy and reliability), and Availability (ensuring systems and data are accessible when needed) |
| Non-repudiation | A security property that prevents a user or entity from denying that they performed a specific action, typically achieved through digital signatures and audit trails |
| AAA Framework | A security framework encompassing Authentication, Authorization, and Accounting to manage digital resource access and maintain system security |
| Authentication | The process of verifying the identity of a user, system, or entity, typically through credentials like passwords or biometrics |
| Authorization | The process of determining what resources or actions a verified identity can access or perform within a system |
| Accounting | The tracking and logging of user activities, system events, and resource usage for security auditing and compliance purposes |
| Multi-Factor Authentication (MFA) | A security system requiring two or more independent verification methods from different categories: something you know, something you have, or something you are |
| Role-based Access Control (RBAC) | A security model where access permissions are assigned to roles, and users are granted access by being assigned to appropriate roles |
| Discretionary Access Control (DAC) | An access control method where the owner of a resource determines who can access it and what privileges they have |
| Access Control Lists (ACL) | A set of rules specifying which users or system processes are granted access to specific objects, along with the level of access permitted |
| Least Privilege | A security principle requiring users and processes to have only the minimum permissions necessary to perform their authorized tasks |
| Log | A record of events, transactions, or activities that occur within a system or network, used for monitoring and analysis |
| Gap Analysis | A method of assessing the difference between current security measures and desired security posture, identifying areas needing improvement |
| Zero Trust Architecture (ZTA) | A security framework that assumes no user or system should be trusted by default, requiring continuous verification regardless of location or network connection |
| Control Plane (ZTA) | The component in Zero Trust Architecture responsible for making and enforcing access decisions based on policy, managing authentication, and orchestrating security controls |
| Data Plane (ZTA) | The network component that forwards data between systems after access decisions are made, implementing the control plane's security policies |
| Adaptive Identity | A dynamic approach to identity verification that adjusts authentication requirements based on contextual factors like location, device, and behavior patterns |
| Policy Engine | The decision-making component that evaluates access requests against security policies, considering factors like user identity, device status, and risk level |
| Implicit Trust Zone | A network segment where devices are automatically trusted without continuous verification, often considered a security weakness in modern architectures |
| Policy Enforcement Point | The security component that implements and enforces access decisions made by the policy engine, controlling data flow between resources |
| Bollards | Physical security barriers, typically posts or columns, designed to prevent vehicle access while allowing pedestrian traffic |
| Access Control Vestibules | Enclosed spaces with two or more doors where only one door can be opened at a time, creating a secure buffer zone for controlled entry |
| Fences | Physical barriers used to define property boundaries, deter unauthorized access, and channel traffic through designated entry points |
| Infrared Sensor | A detection device that monitors changes in infrared radiation patterns to detect movement or presence of objects and people |
| Pressure Sensor | A device that detects and measures force or weight changes, often used in security systems to monitor footsteps or vehicle presence |
| Microwave Sensor | A motion detection device that emits microwave radiation and monitors changes in the reflected patterns to detect movement |
| Ultrasonic Sensor | A device that uses high-frequency sound waves to detect presence and movement by measuring the time taken for sound to reflect off objects |
| Honeypot | A security resource that appears valuable but is isolated and monitored, designed to attract and detect potential attackers |
| Honeynet | A network of honeypots working together to simulate a larger network infrastructure, providing more comprehensive threat intelligence |
| Honeyfile | A fake document or file designed to appear valuable, planted to detect unauthorized access or data theft attempts |
| Honey Token | A unique, trackable piece of data (like a database entry or email address) planted to detect and trace unauthorized access or data breaches |

## Lecture 3: Change Management

Term | Definition
-----|------------
Change Management | A systematic approach to handling transitions and transformations in organizational processes, tools, and objectives while minimizing disruption and ensuring successful implementation
System Ownership | The assignment of overall responsibility and accountability for a system's operation, maintenance, and governance throughout its lifecycle
Technical Owner | An individual or team responsible for the technical aspects, maintenance, configuration, and performance of a system or application
Business Owner | The person or entity accountable for defining system requirements, ensuring business value, and making strategic decisions about a system's development and usage
Total Cost of Ownership | The comprehensive assessment of all direct and indirect costs associated with acquiring, implementing, maintaining, and eventually decommissioning a system or asset
Stakeholder | Any individual, group, or organization that can affect, be affected by, or perceive themselves to be affected by a decision, activity, or outcome of a project
Impact Analysis | The evaluation of potential consequences and ripple effects that a proposed change might have on various systems, processes, and business operations
Backout Plan | A predetermined strategy to restore systems to their previous stable state if implemented changes cause unexpected issues or failures
Maintenance Window | A scheduled period when systems can be taken offline or operated with limited functionality to perform updates, patches, or repairs
Standard Operating Procedure | A documented set of step-by-step instructions that describe how to perform routine operational tasks consistently and effectively
Restart Procedure | A defined sequence of steps for safely stopping and restarting a system or application while maintaining data integrity and proper functionality
Allow List | A security mechanism that explicitly permits specified entities (IP addresses, applications, users) to access resources while blocking all others by default
Deny List | A security control that explicitly blocks specified entities from accessing resources while allowing all others that aren't listed
Downtime | The period during which a system is unavailable or non-operational, whether planned for maintenance or caused by failures
Legacy Application | An outdated or obsolete system that continues to be used due to its critical role, despite potential compatibility or maintenance challenges
Direct Dependency | A component, service, or resource that a system immediately requires to function properly
Indirect Dependency | A secondary or tertiary requirement that, while not immediately connected, can still affect system functionality through its relationship with direct dependencies
Version Control | A system for tracking and managing changes to software code, documents, or other collections of information, enabling collaboration and maintaining history