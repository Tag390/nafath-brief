Version: NAFATH-V3
Track: Cybersecurity 

## Overview
NAFATH is a public-service AI assistant designed to help people access information clearly, safely, and reliably. A trustworthy assistant must provide accurate answers, protect personal information, and communicate uncertainty when information cannot be verified. Secure software development helps prevent vulnerabilities, while responsible AI practices support transparency and accountability. Mobile security protects users accessing services through smartphones, and secure networking helps maintain reliable communication between systems. Cybersecurity controls reduce unauthorized access, detect suspicious activity, and support incident response. Effective data governance ensures that information is accurate, appropriately accessed, and handled according to privacy requirements. These six areas are interconnected: weaknesses in one area can affect the entire service. Together, they help improve service availability, protect sensitive information, and strengthen public trust in digital services.
## Software
Secure software development helps reduce vulnerabilities before an application is released. Developers should follow secure coding practices, review code, test for weaknesses, and fix identified security issues. For a public-service AI assistant, software security also includes access control, safe error handling, and regular updates. These practices help protect service availability and user information throughout the software lifecycle.

Resource: https://csrc.nist.gov/Projects/ssdf
## AI 
Trustworthy AI should be reliable, transparent, secure, and accountable. An AI assistant serving the public should provide clear answers, protect sensitive information, and communicate uncertainty when it cannot verify a claim. Human oversight and ongoing evaluation can help identify inaccurate outputs and security risks. Responsible AI practices build public trust while reducing the risk of harmful or misleading information.

Resource: https://www.nist.gov/itl/ai-risk-management-framework
## Mobile
Mobile security is important when people access public services through smartphones. Applications should use secure communication, protect locally stored information, request only necessary permissions, and authenticate users appropriately. Developers should keep dependencies updated and test applications for common vulnerabilities. Strong mobile security helps prevent unauthorized access and protects personal information when users interact with digital government services.

Resource: https://mas.owasp.org/
## Networking
Secure networking ensures that systems communicate safely and reliably. Important measures include network segmentation, firewalls, secure protocols, traffic monitoring, and timely patching of network devices. For a public-service AI assistant, network controls can reduce unauthorized access and limit the spread of attacks. Network monitoring also helps security teams detect unusual activity and maintain service availability.

Resource: https://www.nist.gov/cyberframework
## Cybersecurity
Cybersecurity protects systems, networks, and information against unauthorized access, disruption, and misuse. A trustworthy public-service AI assistant should use least-privilege access, multifactor authentication where appropriate, vulnerability management, security logging, and incident response procedures. Regular security assessments can reveal weaknesses before attackers exploit them. These controls support confidentiality, integrity, and availability while helping maintain public confidence in digital services.

Resource: https://www.cisa.gov/topics/cybersecurity-best-practices
## Data 
Data governance helps ensure that information is accurate, protected, and used appropriately. A public-service AI assistant should collect only the data it needs, restrict access to authorized users, protect sensitive information, and define retention periods. Data quality checks and reliable sources can improve answer accuracy. Clear privacy practices also help users understand how their information is handled and reduce unnecessary exposure of personal data.

Resource: https://www.nist.gov/privacy-framework
## Misconception in My Track
A common misconception in cybersecurity is that prompt injection can always be prevented by blocking suspicious words in a user's message. In reality, prompt injection may use indirect instructions hidden in documents or other content processed by an AI system. Keyword filtering alone is not a reliable defense. Systems should treat external content as untrusted, limit the assistant's permissions, validate actions, and test defenses regularly. These measures reduce risk but cannot guarantee complete prevention.

Resource: OWASP Top 10 for LLM Applications — LLM01: Prompt Injection
## Open Question
How can we evaluate whether an AI assistant's defenses against direct and indirect prompt injection remain effective when new attack techniques emerge?
