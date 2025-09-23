# Medidas de Segurança para Código Aberto

!!! abstract "Sobre esta política"
      Estas políticas visam garantir que o software de código aberto (SCA) utilizado ou produzido pelo setor público atenda a padrões de segurança robustos. Elas estabelecem requisitos e diretrizes para o gerenciamento de vulnerabilidades, práticas de desenvolvimento seguro e integridade da cadeia de suprimentos (supply chain), reconhecendo a importância estratégica do OSS nos marcos nacionais de cibersegurança.
  
!!! note "O que incluímos"
      Esta seção inclui leis, estratégias e diretrizes operacionais que abordam a segurança do OSS em sistemas governamentais. Isso pode incluir regras obrigatórias de divulgação de vulnerabilidades, requisitos de segurança desde a concepção (security-by-design), orientações sobre o uso ou contribuição para SCA seguro, e protocolos para ciclos de vida de desenvolvimento de software seguro e garantia da cadeia de suprimentos.
      
### 🌍  Políticas

### 🇨🇦 Canadá

* 🔗 [Address Security and Privacy Risks Guideline](https://www.canada.ca/en/government/system/digital-government/government-canada-digital-standards/address-security-privacy-risks.html)
* 📄 Descripción:
> A diretriz "Address Security and Privacy Risks" (Abordar Riscos de
> Segurança e Privacidade) fornece um quadro abrangente para a
> segurança de software, incluindo o SCA utilizado em sistemas
> governamentais. Descreve medidas de segurança ao longo de todo o
> ciclo de vida, incluindo modelagem de ameaças, testes
> automatizados e de penetração, avaliações de impacto na
> privacidade, criptografia e gerenciamento de patches. Embora não
> seja exclusiva para SCA, a orientação apoia a adoção de código
> aberto ao enfatizar a transparência, recursos de segurança
> modulares e monitoramento contínuo, ajudando a garantir que os
> sistemas abertos atendam a rigorosos padrões de privacidade e
> cibersegurança.



* 🔗 [Open First Whitepaper: Open Source Software Use](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/open-source-software/open-first-whitepaper/open-first-whitepaper-use.html)
* 📄 Descripción:
> O "Open First Whitepaper" enfatiza a segurança como uma vantagem
> chave do software de código aberto, citando sua transparência,
> auditabilidade e ampla revisão por pares. Na seção "Segurança", o
> documento explica que o acesso público ao código-fonte permite a
> identificação e remediação precoces de vulnerabilidades,
> alinhando-se com as recomendações do NIST contra a dependência da
> obscuridade. O SCA é preferido por agências de segurança nacional
> devido à sua inspecionabilidade, e seu modelo de segurança,
> baseado no fortalecimento através de testes abertos, é apresentado
> como mais robusto quando os projetos são ativamente mantidos e
> revisados.


### 🇰🇷 Coreia do Sul

* 🔗 [Software Supply Chain Security Guidelines 1.0 (2023)](https://www.msit.go.kr/bbs/view.do?sCode=user&mId=113&mPid=238&bbsSeqNo=94&nttSeqNo=3184474)
* 📄 Descripción:
> Emitidas pelo Ministério da Ciência e TIC, juntamente com agências
> de segurança nacional e digitais, as Diretrizes de Segurança da
> Cadeia de Suprimentos de Software 1.0 estabelecem um quadro
> detalhado para a segurança do software de código aberto usado em
> sistemas governamentais. Central para a política é o uso de Listas
> de Materiais de Software (SBOM) para identificar, validar e
> gerenciar vulnerabilidades em componentes de código aberto ao
> longo do ciclo de vida do software. O documento descreve
> procedimentos técnicos, métodos de validação e estruturas de
> suporte — incluindo laboratórios de teste e ferramentas
> automatizadas de SBOM — para construir cadeias de suprimentos
> seguras, especialmente para instituições públicas e PMEs que
> adotam software de código aberto.


### 🇪🇨 Equador

* 🔗 [Executive Decree No. 1014](https://web.gestiondocumental.gob.ec/wp-content/uploads/2020/08/Decreto-Ejecutivo-N-1014.pdf)
* 📄 Descripción:
> O Decreto Executivo nº 1014 exige que as entidades do governo
> central do Equador garantam a capacidade técnica antes de
> implantar software de código aberto, conforme estabelecido no
> Artigo 3. Esta disposição visa salvaguardar a implementação segura
> e eficaz do SCA, exigindo uma infraestrutura de suporte adequada,
> abordando indiretamente a segurança do SCA através da prontidão
> operacional e da supervisão pela Subsecretaria de Informática.


### 🇺🇸 Estados Unidos

* 🔗 [GSA Open Source Software Implementation Guide](https://open.gsa.gov/oss-implementation/#how-to-open-source)
* 📄 Descripción:
> A política define protocolos de segurança para a liberação pública
> de código. As equipes de projeto são obrigadas a trabalhar com o
> escritório de segurança de TI para realizar varreduras regulares
> de código em busca de vulnerabilidades. Além disso, o guia observa
> que o escritório do CTO fornece scripts especializados projetados
> para ajudar as equipes a limpar o código-fonte de conteúdo
> sensível antes de ser publicado como código aberto.



* 🔗 [Securing Open Source Software Act of 2023](https://www.congress.gov/bill/118th-congress/house-bill/3286/text)
* 📄 Descripción:
> A Lei estabelece extensas obrigações de segurança para a CISA sob
> a Seção 2220F. Ela exige a criação de um quadro público para
> avaliar o risco de componentes de código aberto, considerando
> fatores como segurança de memória e práticas dos mantenedores. A
> CISA deve usar este quadro para avaliar o SCA em ativos federais
> de alto valor, aproveitando informações de Listas de Materiais de
> Software (SBOMs).



* 🔗 [CISA Open Source Software Security Roadmap](https://www.cisa.gov/sites/default/files/2024-02/CISA-Open-Source-Software-Security-Roadmap-508c.pdf)
* 📄 Descripción:
> Este roteiro é uma política de segurança abrangente para SCA. A
> Meta 2 descreve planos para criar um quadro público para a
> priorização de riscos de SCA com base no uso, manutenção e
> propriedades do código. A Meta 4 foca em fortalecer o ecossistema,
> avançando no uso de Listas de Materiais de Software (SBOM) nas
> cadeias de suprimentos de SCA (Objetivo 4.1) e fomentando melhores
> processos de divulgação de vulnerabilidades (Objetivo 4.4).


### 🇫🇷 França

* 🔗 [Selecting Open Source Software – ANSSI Guide](https://cyber.gouv.fr/publications/selection-dun-logiciel-libre)
* 📄 Descripción:
> O guia da ANSSI "Sélection d’un logiciel libre" descreve critérios
> de cibersegurança para avaliar e selecionar software de código
> aberto usado em sistemas públicos. Embora não seja vinculativo,
> promove a adoção segura de SCA ao recomendar a avaliação da
> transparência do código, práticas de manutenção e capacidade de
> resposta da comunidade, reforçando a postura de segurança de
> código aberto mais ampla da França.



* 🔗 [Reporting Significant Vulnerabilities](https://cert.ssi.gouv.fr/signalement-vulnerabilite-incident-2321-4-1)
* 📄 Descripción:
> O Artigo L. 2321-4-1 do Código de Defesa (Lei de Programação
> Militar de 2023): Obriga qualquer editor de software (incluindo
> projetos de SCA) a relatar vulnerabilidades significativas ou
> incidentes de segurança em seus produtos à ANSSI. Este amplo
> mandato de cibersegurança aplica-se igualmente a software de
> código aberto e proprietário, promovendo a divulgação e correção
> rápidas.



* 🔗 [Interministerial Support and Expertise Contracts for Free Software](https://code.gouv.fr/fr/utiliser/marches-interministeriels-support-expertise-logiciels-libres/)
* 📄 Descripción:
> Os contratos de suporte interministerial para software de código
> aberto incluem contribuições obrigatórias para o projeto original
> (upstream) de todas as correções, incluindo patches de segurança,
> desenvolvidas durante a manutenção. Esta política garante que as
> vulnerabilidades abordadas nos sistemas públicos sejam resolvidas
> na origem, aumentando a segurança tanto para o governo quanto para
> os usuários de SCA em geral.


### 🇬🇧 Reino Unido

* 🔗 [Open Source, Open Standards and Re‑Use: Government Action Plan](https://assets.publishing.service.gov.uk/media/5a789aade5274a277e68e04d/open_source.pdf)
* 📄 Descripción:
> O Plano de Ação aborda a segurança do código aberto através da
> Ação 4, que estabelece avaliações regulares pelo Conselho de CIOs
> para garantir que os produtos de código aberto usados no governo
> atendam a padrões definidos de maturidade, segurança do
> código-base e sustentabilidade do projeto. Esta medida visa
> mitigar os riscos associados à implantação de soluções de código
> aberto em serviços públicos críticos, verificando a confiabilidade
> e a estabilidade das ferramentas antes da adoção generalizada.



* 🔗 [The Digital, Data and Technology Playbook](https://www.gov.uk/government/publications/the-digital-data-and-technology-playbook/the-digital-data-and-technology-playbook)
* 📄 Descripción:
> O playbook define protocolos de segurança para toda a tecnologia
> adquirida, o que inerentemente cobre o software de código aberto.
> A política chave de "Avaliação de segurança cibernética" exige que
> todos os projetos apliquem um nível robusto de avaliação de
> segurança para proteger os dados públicos. Conforme expandido nos
> Capítulos 8 e 9, isso inclui a exigência de padrões como o Cyber
> Essentials Scheme para contratos que lidam com informações
> pessoais ou fornecem certos serviços de TIC, garantindo que
> qualquer SCA utilizado em sistemas públicos esteja sujeito à mesma
> rigorosa avaliação e gerenciamento de riscos de segurança.


### 🇨🇭 Suíça

* 🔗 [Report on the Implementation of the National Cyber Strategy (NCS) 2024](https://www.ncsc.admin.ch/dam/ncsc/de/dokumente/strategie/cyberstrategie-ncs/Bericht-zur-Umsetzung-der-NCS_2024-DE.pdf.download.pdf/Bericht-zur-Umsetzung-der-NCS_2024-DE.pdf)
* 📄 Descripción:
> A Seção 4.2.1 destaca a crescente importância de proteger o
> software de código aberto (SCA). Ela descreve um projeto piloto
> iniciado em 2024 pelo Escritório Federal de Cibersegurança (BACS)
> para testar produtos de SCA frequentemente utilizados. Esta
> iniciativa visa aumentar a transparência e a segurança do SCA,
> reduzir as superfícies de ataque e fortalecer a resiliência
> cibernética geral da Suíça.



* 🔗 [Instructions for Publishing Open Source Software](https://github.com/swiss/opensource-guidelines/blob/main/docs/en/em002-2.md)
* 📄 Descripción:
> A Seção 4.1, "Análise de código-fonte", define protocolos de
> segurança específicos a serem seguidos antes da publicação de
> qualquer software. Essas verificações obrigatórias incluem a
> varredura do código-fonte para garantir que não contenha segredos
> ou credenciais, a realização de testes de segurança direcionados e
> a criação de listas de todas as bibliotecas de terceiros
> utilizadas. Também recomenda o estabelecimento de um programa
> público de recompensas por bugs (bug bounty) após o lançamento.



* 🔗 [OSS Community Guidelines for the Federal Administration](https://github.com/swiss/opensource-guidelines/blob/main/docs/en/em002-4.md)
* 📄 Descripción:
> Um protocolo de segurança específico para projetos gerenciados
> pela comunidade é exigido na Seção 5.8. Esta política requer o
> estabelecimento de um canal confidencial para relatar erros
> relevantes para a segurança. Isso garante que potenciais
> vulnerabilidades possam ser divulgadas de forma responsável aos
> mantenedores do projeto sem serem tornadas públicas imediatamente,
> de forma semelhante ao processo usado em programas formais de
> recompensas por bugs.


### 🇪🇺 Comissão Europeia

* 🔗 [Regulation (EU) 2024/2847 (Cyber Resilience Act)](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847)
* 📄 Descripción:
> A lei impõe várias medidas de segurança para o SCA. O Artigo 13(5)
> exige a devida diligência ao integrar quaisquer componentes de
> terceiros, incluindo SCA. O Anexo I, Parte II, exige que os
> fabricantes produzam uma Lista de Materiais de Software (SBOM)
> para seus produtos. Além disso, o Artigo 24 cria obrigações
> específicas para os "administradores de software de código aberto"
> estabelecerem políticas de cibersegurança para os projetos que
> apoiam.



* 🔗 [European Commission digital strategy: Next generation digital Commission](https://commission.europa.eu/document/download/70703206-2592-4175-b10d-12f97382094a_en?filename=C_2022_4388_1_EN_ACT&prefLang=fr)
* 📄 Descripción:
> A estratégia aumenta a segurança em todo o cenário digital, o que
> inclui o software de código aberto. A página 14 descreve planos
> para a verificação sistemática de vulnerabilidades em todas as
> soluções digitais e verificações de segurança para software
> adquirido. O documento também reconhece que o SCA pode aumentar a
> segurança de TI através de múltiplos controles de qualidade
> independentes, integrando-o a uma abordagem de segurança desde a
> concepção (secure-by-design).



* 🔗 [Open Source Software Strategy 2020-2023: Think Open](https://commission.europa.eu/document/download/97e59978-42c0-4b4a-9406-8f1a86837530_en?filename=en_ec_open_source_strategy_2020-2023.pdf)
* 📄 Descripción:
> A segurança é um princípio de governança central, conforme
> delineado na Seção 5.5, intitulada "Seguro". A política exige
> testes de segurança contínuos e automatizados tanto para os
> componentes de código aberto que a Comissão utiliza em suas
> aplicações quanto para o código que pretende compartilhar
> publicamente. Isso garante que o software esteja livre de
> vulnerabilidades, aproveitando a experiência dos projetos
> EU-FOSSA.
  
## 🤝 Como contribuir
 
!!! tip "Quer adicionar uma política?"
    Viu que está faltando alguma informação? [Faça uma sugestão de política](https://github.com/EL-BID/OSS_policies/issues/new?assignees=&labels=contribution&template=policy-suggestion.yml&title=Sugestão%3A+%5BNome+da+Política%5D)
