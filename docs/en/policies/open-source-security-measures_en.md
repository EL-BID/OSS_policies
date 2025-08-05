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
* 🔗 [Decreto Ejecutivo N° 1014 – Article 4](https://web.gestiondocumental.gob.ec/wp-content/uploads/2020/08/Decreto-Ejecutivo-N-1014.pdf)
* 📄 Overview:
> The use of proprietary (non-free) software is allowed only when:
>
> 1. There is no Free Software solution that meets the required needs
> 2. The national security is at risk
> 3. The IT project is at a point of no return

### 🇬🇧 England
* 🔗 [Government Action Plan (2010) – Action 4](https://assets.publishing.service.gov.uk/media/5a789aade5274a277e68e04d/open_source.pdf)
* 📄 Overview:
> Given the nature of Government work, a degree of confidence that a product is mature, that the code base is secure, that the project itself is sustainable is needed. The CIO Council will regularly assess products for maturity and recommend a list of products and implementations that meet agreed criteria.

### 🇫🇷 France

* 🔗 [Loi de Programmation Militaire – Article L. 2321‑4‑1](https://cert.ssi.gouv.fr/signalement-vulnerabilite-incident-2321-4-1/#:~:text=Vous%20%C3%AAtes%20potentiellement%20concern%C3%A9%20par,du%20code%20de%20la%20d%C3%A9fense)
* 📄 Overview:
> Obligates any software publisher (including OSS projects) to report significant vulnerabilities or security incidents in their products to ANSSI. This broad cybersecurity mandate applies equally to open-source and proprietary software, promoting prompt disclosure and patching.

* 🔗 [Sélection d’un logiciel libre – ANSSI Guidance](https://cyber.gouv.fr/publications/selection-dun-logiciel-libre)
* 📄 Overview:
> The French Cybersecurity Agency publishes best-practice guides (e.g. “Sélection d’un logiciel libre”) that list security criteria for open-source components. ANSSI also supports certification of critical OSS products (via CSPN) and provides audits and “SecNumCloud” accreditation for open-source cloud platforms.

* 🔗 [Marchés Interministériels de Support – Code.gouv.fr](https://code.gouv.fr/fr/utiliser/marches-interministeriels-support-expertise-logiciels-libres/#:~:text=Ces%20activit%C3%A9s%20sont%20men%C3%A9es%20en,communaut%C3%A9s%20et%20les%20administrations%20b%C3%A9n%C3%A9ficiaires)
* 📄 Overview:
> Interministerial OSS support contracts require that any security patches developed during support missions be returned upstream, ensuring vulnerabilities are fixed in the source project. This in turn benefits all users of that OSS.

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