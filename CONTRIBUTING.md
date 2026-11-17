# Guia de Contribuição — Rede de Repositórios do CGTIC

Que bom ter você colaborando com o ecossistema de software das Instituições Federais de Ensino Superior (IFES)! Este documento estabelece as diretrizes gerais de colaboração da organização **`cgtic-ifes`**.

---

## 🏛️ 1. Autonomia das Instituições Mantenedoras

Cada repositório hospedado nesta organização é mantido por uma IFES específica, que detém **autonomia** sobre suas regras de versionamento, aceitação de contribuições e ciclo de releases.

* **Verifique sempre o repositório local primeiro:** Caso um projeto possua seu próprio arquivo `CONTRIBUTING.md` ou instruções específicas no `README.md`, **as regras locais daquele repositório prevalecem** sobre este guia geral.

---

## 🚀 2. Fluxo Recomendado de Contribuição

1. **Alinhe antes de grandes mudanças:** Antes de desenvolver uma funcionalidade complexa ou alteração estrutural, abra uma *Issue* (ou verifique as já existentes) para confirmar se a proposta está alinhada ao roadmap da instituição mantenedora.
2. **Crie um Fork e uma Branch:**
   * Faça um *fork* do repositório para sua conta (ou conta da sua equipe/IFES).
   * Crie uma *branch* descritiva a partir da branch principal (`main` ou `develop`, conforme o projeto):
     * `feat/nome-da-funcionalidade`
     * `fix/descricao-da-correcao`
     * `docs/ajuste-documentacao`
3. **Desenvolva com foco em qualidade e segurança:**
   * Escreva código limpo, modular e bem documentado.
   * Inclua ou atualize testes automatizados sempre que possível.
   * **Nunca faça commit de segredos** (senhas, chaves de API, certificados, arquivos `.env` reais ou dados pessoais/institucionais).
4. **Abra um Pull Request (PR):**
   * Preencha o formulário padrão de *Pull Request* explicando o contexto, o impacto da mudança e como testá-la.
   * Acompanhe a execução das esteiras automatizadas (*GitHub Actions / CI*) e interaja com os revisores da instituição mantenedora.

---

## 🏷️ 3. Versionamento Semântico (SemVer)

Incentivamos que todos os projetos e contribuições sigam o padrão **[Semantic Versioning (SemVer)](https://semver.org/)** no formato `MAJOR.MINOR.PATCH`:

* **`MAJOR` (`X.0.0`):** Mudanças incompatíveis na API, banco de dados ou comportamento que exigem adaptação de quem já utiliza o sistema.
* **`MINOR` (`0.X.0`):** Novas funcionalidades adicionadas mantendo compatibilidade com versões anteriores.
* **`PATCH` (`0.0.X`):** Correções de bugs e ajustes de segurança retrocompatíveis.

---

## ⚖️ 4. Licenciamento e Responsabilidade

* Ao enviar uma contribuição para qualquer repositório público desta organização, você concorda que seu código será disponibilizado sob a mesma licença definida no arquivo **`LICENSE`** do respectivo repositório.
* Lembre-se de que cada universidade é responsável por auditar e validar tecnicamente o código antes de implantá-lo em produção, isentando o CGTIC e as instituições cedentes de responsabilidade por eventuais danos decorrentes do uso.
