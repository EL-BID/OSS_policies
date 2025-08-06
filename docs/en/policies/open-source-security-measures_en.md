# Open Source Security Measures

!!! abstract "About this policy"
      These policies aim to ensure that open-source software used or produced by the public sector meets robust security standards. They establish requirements and guidelines for vulnerability management, secure development practices, and supply chain integrity, recognizing the strategic importance of OSS in national cybersecurity frameworks.
  
!!! note "What we include"
      This section includes laws, strategies, and operational guidelines that address the security of OSS in government systems. These may include mandatory vulnerability disclosure rules, security-by-design requirements, guidance on using or contributing to secure OSS, and protocols for secure software development lifecycles and supply chain assurance.
      
### 🌍  Policies

### 🇨🇦 Canada

* 🔗 [Address Security and Privacy Risks Guideline](https://www.canada.ca/en/government/system/digital-government/government-canada-digital-standards/address-security-privacy-risks.html)  
* 📄 Overview:  
> The Address Security and Privacy Risks guideline provides a comprehensive framework for securing software, including OSS used in government systems. It outlines security measures across the full lifecycle, including threat modeling, automated and penetration testing, privacy impact assessments, encryption, and patch management. While not exclusive to OSS, the guidance supports open-source adoption by emphasizing transparency, modular security features, and continuous monitoring, helping ensure that open systems meet rigorous privacy and cybersecurity standards.

* 🔗 [Open First Whitepaper: Open Source Software Use](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/open-source-software/open-first-whitepaper/open-first-whitepaper-use.html)  
* 📄 Overview:  
> The Open First Whitepaper emphasizes security as a key advantage of open-source software, citing its transparency, auditability, and wide peer review. In the "Security" section, the document explains that public access to source code allows for early identification and remediation of vulnerabilities, aligning with NIST recommendations against relying on obscurity. OSS is favored by national security agencies due to its inspectability, and its security model based on hardening through open testing, is presented as more robust when projects are actively maintained and reviewed.



### 🇪🇨 Ecuador

* 🔗 [Executive Decree No. 1014](https://web.gestiondocumental.gob.ec/wp-content/uploads/2020/08/Decreto-Ejecutivo-N-1014.pdf)
* 📄 Overview:
  > Executive Decree No. 1014 requires Ecuador’s central government entities to ensure technical capacity before deploying open-source software, as stated in Article 3. This provision aims to safeguard the secure and effective implementation of OSS by mandating adequate support infrastructure, indirectly addressing OSS security through operational readiness and oversight by the Subsecretariat of Informatics.
  
### 🇬🇧 England

* 🔗 [Open Source, Open Standards and Re‑Use: Government Action Plan)](https://assets.publishing.service.gov.uk/media/5a789aade5274a277e68e04d/open_source.pdf)
* 📄 Overview:
  > The Action Plan addresses open source security through Action 4, which establishes regular assessments by the CIO Council to ensure that open-source products used in government meet defined standards of maturity, codebase security, and project sustainability. This measure aims to mitigate risks associated with deploying open-source solutions in critical public services by verifying the reliability and stability of the tools before widespread adoption.

* 🔗 [The Digital, Data and Technology Playbook](https://www.gov.uk/government/publications/the-digital-data-and-technology-playbook/the-digital-data-and-technology-playbook)
* 📄 Overview:
  > The playbook defines security protocols for all procured technology, which inherently covers open source software. The "Cyber security assessment" key policy requires that all projects apply a robust level of security assessment to safeguard public data. As expanded upon in Chapters 8 and 9, this includes mandating standards such as the Cyber Essentials Scheme for contracts handling personal information or providing certain ICT services, ensuring that any OSS utilized in public systems is subject to the same rigorous security risk evaluation and management.

### 🇫🇷 France

* 🔗 [Interministerial Support and Expertise Contracts for Free Software](https://code.gouv.fr/fr/utiliser/marches-interministeriels-support-expertise-logiciels-libres/)
* 📄 Overview:
  > The interministerial support contracts for open-source software include mandatory upstream contributions of all fixes, including security patches, developed during maintenance. This policy ensures that vulnerabilities addressed within public systems are resolved at the source, enhancing security for both government and broader OSS users.

* 🔗 [Selecting Open Source Software – ANSSI Guide](https://cyber.gouv.fr/publications/selection-dun-logiciel-libre)
* 📄 Overview:
  > ANSSI’s guide “Sélection d’un logiciel libre” outlines cybersecurity criteria for evaluating and selecting open-source software used in public systems. While not binding, it promotes secure OSS adoption by recommending assessment of code transparency, maintenance practices, and community responsiveness, reinforcing France’s broader open-source security posture.

* 🔗 [Reporting Significant Vulnerabilities](https://cert.ssi.gouv.fr/signalement-vulnerabilite-incident-2321-4-1)
* 📄 Overview:
  > Under Article L. 2321‑4‑1 of the French Code de la Défense, all software publishers—including open-source developers—are required to report significant vulnerabilities or incidents affecting their products to ANSSI. This regulation ensures security issues in OSS are disclosed and addressed promptly, reinforcing national cybersecurity standards across both proprietary and open systems.


### 🇩🇪 Germany

* 🔗 [BSI FLOSS Policy (2020)](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Freie-Software/freie-software_node.html#:~:text=The%20role%20of%20the%20Federal,leads%20to%20greater%20manufacturer%20independence)
* 📄 Overview:
> The Federal Office for Information Security (BSI) promotes using free/open-source software (FOSS) to increase software diversity and security. It notes that open source allows code auditing and independent fixes, reducing monocultures.


### 🇰🇷 South Korea

* 🔗 [Software Supply Chain Security Guidelines (2023)](https://www.msit.go.kr/bbs/view.do?sCode=user&mId=113&mPid=238&bbsSeqNo=94&nttSeqNo=3184474)
* 📄 Overview:
> A government guideline jointly released by MSIT, the National Intelligence Service, and other agencies to bolster software supply-chain security. It promotes SBOM usage and developer practices to manage OSS-related vulnerabilities.

### 🇨🇭 Switzerland

* 🔗 [Nationale Cyberstrategie 2024 – Pilot Project](https://www.ncsc.admin.ch/dam/ncsc/de/dokumente/strategie/cyberstrategie-ncs/Bericht-zur-Umsetzung-der-NCS_2024-DE.pdf.download.pdf/Bericht-zur-Umsetzung-der-NCS_2024-DE.pdf)
* 📄 Overview:
> In 2024, the BACS, in collaboration with the NTC, launched a pilot project to evaluate two widely used OSS products.

### 🇺🇸 United States

* 🔗 [GSA OSS Implementation Guide](https://open.gsa.gov/oss-implementation/#how-to-open-source)
* 📄 Overview:
> The U.S. General Services Administration (GSA) promotes integrating security and review processes into the software development lifecycle to enable safe open-sourcing of government code. Project teams are encouraged to conduct ongoing code reviews in collaboration with contractors and to coordinate closely with IT security offices for regular application and source code scans. The CTO team provides custom scanning scripts specifically designed to detect sensitive content in code prior to public release—distinct from standard security scans. Rather than postponing these activities until the end of development cycles, GSA recommends incorporating them continuously throughout the project, supporting a gradual, project-by-project transition to open source, aligned with updates or vendor changes.

* 🔗 [CISA, OpenSSF, OSSF Roadmap & Package Security Principles](https://repos.openssf.org/principles-for-package-repository-security)
* 📄 Overview:
> Open source security is increasingly recognized as critical to digital infrastructure, and recent initiatives provide a structured response to its challenges. The OpenSSF’s Principles of Package Repository Security define a maturity model (Levels 0–3) across four domains—authentication, authorization, general capabilities, and CLI tooling—to guide repositories in strengthening protections. Measures include mandatory MFA, role-based access controls, vulnerability disclosure policies, malware detection, and secure dependency management, with advanced repositories supporting SBOM generation and static analysis.
> Complementing this, the Securing Open Source Software Act of 2023 expands the role of CISA, mandating it to hire OSS experts, create a Software Security Advisory Subcommittee, and launch pilot OSPOs in federal agencies. CISA’s FY24–26 Open Source Security Roadmap sets four strategic goals: establishing CISA as a leader in OSS security, increasing visibility into OSS risk, securing federal OSS use, and hardening the broader OSS ecosystem through tools like SBOMs, best practices, and coordinated vulnerability response.


### 🇪🇺 European Commission

* 🔗 [Open Source Software Strategy 2020–2023](https://commission.europa.eu/document/download/97e59978-42c0-4b4a-9406-8f1a86837530_en?filename=en_ec_open_source_strategy_2020-2023.pdf)
* 📄 Overview:
> We make sure the code we use and the code we share is free from vulnerabilities by applying continuous security testing.


* 🔗 [European Commission Digital Strategy 2022](https://commission.europa.eu/document/download/d699a990-59c2-4ca2-8613-0abbed0962b5_fr?filename=C_2022_4388_1_FR_ACT&prefLang=en)
* 📄 Overview:
> Open-source balances immediate technological needs and future flexibility, increases IT security through multiple independent quality controls, and takes into account technological sovereignty, openness and long-term collective digital interests.


* 🔗 [REGULATION (EU) 2024/1173 – Cyber Resilience Act](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847)
* 📄 Overview:
> In order to foster the uptake of secure products with digital elements, and to enable manufacturers to provide products that are secure by design and default, it is important to ensure that open-source software components are developed in a secure manner and that vulnerability management is carried out effectively by the developers of those components. The secure development of a product with digital elements and its components, including open-source components, should be subject to due diligence.


## 🤝 How to contribute
  
!!! tip "Want to add a policy?"
      See something missing? [Open a policy suggestion](https://github.com/EL-BID/OSS_policies/issues/new?template=policy-suggestion.yml)