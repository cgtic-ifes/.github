# CGTIC — Rede de Repositórios das IFES

Bem-vindo à organização oficial da comunidade do **Colégio de Gestores de Tecnologia da Informação e Comunicação (CGTIC)** das Instituições Federais de Ensino Superior (IFES).

Este espaço foi criado para ser um hub colaborativo onde cada universidade pode depositar, compartilhar e evoluir soluções tecnológicas com toda a rede, incentivando o desenvolvimento conjunto, o reuso de software e a troca de boas práticas entre as instituições.

---

## 💡 Por que utilizar este espaço no GitHub?

O GitHub foi adotado por ser uma plataforma amplamente consolidada na comunidade global de desenvolvimento, oferecendo infraestrutura gratuita, controle de versão distribuído, rastreabilidade de alterações e ferramentas nativas para revisão de código, gestão de tarefas e documentação. Naturalmente, **nada impede que as IFES utilizem outras plataformas, repositórios institucionais ou meios próprios para cooperar** — esta organização surge como **mais uma alternativa prática e acessível para fomentar a integração, dar visibilidade às soluções da rede e facilitar a colaboração** entre as equipes de TIC das universidades federais.

Além disso, manter um espaço aberto de código compartilhado é também um **convite para envolver nossos estudantes e toda a comunidade acadêmica**, aproximando o ensino, a pesquisa e a extensão da realidade tecnológica das universidades e permitindo que proponham melhorias que beneficiem todo o ecossistema das IFES.

---

## 🎯 Objetivos

* **Compartilhamento de soluções:** Disponibilizar sistemas, scripts, integrações, bibliotecas e ferramentas desenvolvidas pelas equipes de TIC das IFES.
* **Desenvolvimento em rede:** Fomentar a cooperação técnica para que melhorias feitas por uma universidade possam beneficiar toda a comunidade.
* **Engajamento acadêmico:** Estimular a participação ativa de estudantes, docentes, pesquisadores e técnicos na evolução das ferramentas utilizadas pelas instituições.
* **Transparência e padronização:** Facilitar a descoberta de projetos já existentes na rede antes de iniciar novos desenvolvimentos do zero.

---

## 🏛️ Governança e Autonomia das Instituições

Cada instituição que depositar projetos nesta organização **mantém total autonomia** sobre seus repositórios e é responsável por definir suas próprias regras de governança, incluindo:

* Política de atualizações e versionamento (com **forte incentivo à adoção do Versionamento Semântico — [SemVer](https://semver.org/)** para facilitar a rastreabilidade e a compatibilidade entre versões);
* Fluxo de análise e aprovação de *Pull Requests* / *Merge Requests*;
* Critérios para abertura, triagem e atendimento de *Issues*;
* Licenciamento e documentação do projeto.

> **🤝 Incentivo à Colaboração Aberta:** Embora cada instituição tenha autonomia para definir suas regras, **incentivamos fortemente que os gestores de cada repositório promovam um desenvolvimento realmente colaborativo**, mantendo seus projetos abertos para analisar e aceitar *Pull Requests* / *Merge Requests* enviados por outras universidades, estudantes e pela comunidade.

> **⚠️ Importante:** Antes de utilizar, abrir uma *issue* ou enviar contribuições para qualquer projeto, **leia atentamente o arquivo `README.md` (e eventuais arquivos `CONTRIBUTING.md`) de cada repositório** para conhecer as diretrizes específicas adotadas pela instituição mantenedora.

---

## ⚖️ Avaliação Técnica e Isenção de Responsabilidade

Os códigos-fonte, sistemas e artefatos disponibilizados nesta organização são compartilhados em caráter colaborativo. **Compete exclusivamente a cada universidade ou usuário interessado avaliar tecnicamente, auditar e validar o código-fonte compartilhado** antes de sua implantação ou uso em ambiente institucional.

**Nem o CGTIC, nem a instituição cedente ou os autores originais do código se responsabilizam pelo uso, adaptação, indisponibilidade ou por eventuais danos diretos ou indiretos** decorrentes da utilização dos projetos hospedados neste espaço, observados ainda os termos específicos da licença de cada repositório.

---

## 🔒 Visibilidade dos Repositórios (Públicos e Privados)

* **Incentivo ao Código Aberto:** Encorajamos fortemente que os projetos sejam hospedados como **repositórios públicos**, maximizando o alcance, o reuso e a colaboração aberta entre todas as IFES, estudantes e a sociedade.
* **Repositórios Privados:** Caso haja necessidade institucional, técnica ou de segurança, **não há impedimento para a criação de repositórios privados**. Nesses casos, cabe exclusivamente à **instituição mantenedora** gerenciar as permissões e conceder acesso a outras universidades ou colaboradores, em conformidade com suas próprias políticas internas.

---

## 🤝 Como Participar

1. **Explore os projetos:** Navegue pela aba [Repositories](https://github.com/orgs/cgtic-ifes/repositories) para conhecer as soluções já compartilhadas pela rede.
2. **Criação e depósito de projetos:** A criação e o depósito inicial de repositórios da instituição devem ser realizados pelo **Gestor de TIC da Universidade** (caso ainda não possua acesso, basta solicitar o vínculo à coordenação do CGTIC).
3. **Delegação às equipes:** Após criar o repositório, o próprio Gestor de TIC poderá delegar permissões especiais de administração, manutenção ou escrita aos membros de suas equipes técnicas para conduzirem o desenvolvimento no dia a dia.
4. **Documente, licencie e versione bem seu repositório:** Ao publicar e evoluir um projeto, observe as seguintes recomendações:
   * Inclua obrigatoriamente um arquivo **`README.md`** claro, informando a instituição responsável, o objetivo da solução, instruções de instalação e como outras universidades ou estudantes podem contribuir e solicitar acesso;
   * Inclua obrigatoriamente um arquivo **`LICENSE`**, descrevendo explicitamente a licença de uso, modificação e distribuição aplicável ao projeto;
   * Adote preferencialmente o padrão **[SemVer](https://semver.org/)** (`MAJOR.MINOR.PATCH`) na publicação de *releases* e *tags*, garantindo previsibilidade na evolução do software.

---

## 📦 Catálogo de Soluções Privadas da Rede

Como repositórios privados não ficam visíveis publicamente na vitrine da organização, listamos abaixo as ferramentas já desenvolvidas e disponibilizadas pelas instituições para consulta e eventual solicitação de acesso.

### Universidade Federal do Recôncavo da Bahia (UFRB)

* **[ProvaFácil (`cgtic-ifes/gabarito`)](https://github.com/cgtic-ifes/gabarito)** *(Repositório Privado)*
  * **O que faz:** Sistema web e API REST para correção automática de provas de múltipla escolha por meio de Leitura Óptica de Marcas (OMR) com visão computacional (OpenCV). Permite o cadastro de avaliações, turmas e gabaritos com pesos, geração de folhas de resposta personalizadas em PDF com QR Code individual e correção instantânea via foto (câmera do celular) ou digitalização (PDF/scanner), além de relatórios estatísticos e exportação em CSV.
  * **Tecnologias principais:** Python (FastAPI), OpenCV, ReportLab, SQLite/PostgreSQL e Docker.
  * **Como solicitar acesso:** Entrar em contato com a equipe de TIC da UFRB.

* **[Tela — Chromecast via Navegador (`cgtic-ifes/tela`)](https://github.com/cgtic-ifes/tela)** *(Repositório Privado)*
  * **O que faz:** Sistema de compartilhamento de tela e áudio com baixíssima latência para Smart TVs ou projetores de salas de aula, funcionando inteiramente na rede institucional local sem depender de hardware proprietário (como Chromecast). Conta com painel emissor para o professor e modo receptor (*Kiosk*) para a sala de aula via navegador.
  * **Tecnologias principais:** Node.js, WebRTC, PeerJS, HTML/JavaScript e Docker.
  * **Como solicitar acesso:** Entrar em contato com a equipe de TIC da UFRB.

* **[Importa XML Lattes (`cgtic-ifes/ImportaXMLLattes`)](https://github.com/cgtic-ifes/ImportaXMLLattes)** *(Repositório Privado)*
  * **O que faz:** Utilitário de linha de comando e contêiner para automação de consulta, download em lote e extração de currículos da Plataforma Lattes (CNPq) em formato XML estruturado (via ID Lattes ou CPF), com suporte nativo a proxy de saída institucional para atendimento à *whitelist* de IP do Web Service do CNPq.
  * **Tecnologias principais:** Shell Script (Bash), `curl`, `xmllint` e Docker (Alpine Linux).
  * **Como solicitar acesso:** Entrar em contato com a equipe de TIC da UFRB.
