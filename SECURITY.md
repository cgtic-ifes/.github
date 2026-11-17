# Política de Segurança — Rede de Repositórios do CGTIC

A segurança dos sistemas utilizados pelas Instituições Federais de Ensino Superior (IFES) é uma prioridade para a comunidade do **CGTIC**.

---

## 🛡️ Reportando uma Vulnerabilidade de Segurança

Se você identificar uma falha de segurança, exposição de dados ou vulnerabilidade em qualquer repositório desta organização:

1. **NÃO abra uma Issue pública nem mencione a falha em Pull Requests abertos**, evitando expor as universidades que utilizam a solução antes que uma correção esteja disponível.
2. **Utilize o canal privado do GitHub (Private Vulnerability Reporting):**
   * Acesse a aba **Security** do repositório afetado;
   * Clique em **Advisories** → **Report a vulnerability** para enviar os detalhes de forma confidencial diretamente aos mantenedores da instituição responsável.
3. **Contato alternativo:** Caso o reporte privado não esteja habilitado no repositório específico, entre em contato diretamente com a equipe de TIC da instituição mantenedora indicada no `README.md` do projeto.

### O que incluir no reporte
* Descrição clara da vulnerabilidade e do impacto potencial;
* Versão ou *commit* afetado;
* Passo a passo ou prova de conceito (PoC) para reproduzir o problema de forma controlada.

---

## ⚙️ Boas Práticas de Segurança para Mantenedores (IFES)

Incentivamos que os gestores e equipes técnicas de cada repositório ativem os recursos nativos de proteção do GitHub:

* **Dependabot Alerts & Security Updates:** Para monitoramento contínuo e atualização automatizada de dependências vulneráveis.
* **Secret Scanning & Push Protection:** Para bloquear acidentalmente o envio de tokens, senhas e chaves privadas ao histórico do Git.
* **GitHub Actions (SAST / Testes de Segurança):** Inclusão de análises estáticas e verificação de imagens Docker nas esteiras de CI antes do *merge* de contribuições externas.

---

## ⚖️ Avaliação Técnica e Isenção de Responsabilidade

Conforme estabelecido nas diretrizes gerais da organização, **compete exclusivamente a cada universidade ou usuário interessado auditar, testar e validar tecnicamente o código-fonte compartilhado** antes de sua implantação em ambiente institucional. Nem o CGTIC nem a instituição cedente se responsabilizam por incidentes ou danos decorrentes do uso das soluções aqui hospedadas.
