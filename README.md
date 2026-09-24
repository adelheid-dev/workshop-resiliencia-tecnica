# Workshop: Resiliência Técnica e Postura em Engenharia de Software

Repositório oficial dedicado à análise de Mindset Fixo *versus* Crescimento, gestão de Sprints com Trello e aplicação de práticas ágeis para melhoria contínua no desenvolvimento de software.

---

## 1. Diagnóstico de Vulnerabilidade (Post-Mortems de Incidentes Reais)

Esta secção mapeia situações reais onde respostas defensivas (Mindset Fixo) geraram prejuízos sistêmicos, aplicando a reescrita estratégica com a regra do "Ainda Não".

### Incidente 1: A instabilidade do AVA por sobrecarga de acessos em cima do prazo
* **Contexto Real:** Durante a entrega de atividades estipulado (ex: vencimento às 23:00), ocorre uma sobrecarga massiva no portal devido ao grande volume de alunos a tentar enviar os arquivos simultaneamente perto da hora limite (ex: às 21:40), resultando em indisponibilidade do sistema e impedindo o envio. Como vários estudantes foram afetados pelo mesmo problema, a professora acabou por reabrir o prazo.
* **Resposta Defensiva (Mindset Fixo):** *"O AVA cai o tempo todo e o sistema é péssimo. Como a plataforma sempre falha quando todo mundo tenta entrar junto, nem vou me preocupar em enviar antes; se eu perder o prazo por culpa da lentidão, a responsabilidade é inteiramente da faculdade."*
* **Impacto Sistêmico:** Dependência de prazos limite extremos, risco desnecessário de perder a nota por questões técnicas previsíveis e transferência total da responsabilidade de organização para fatores externos.
* **Reescrita com a Regra do "Ainda Não":** *"O portal *ainda* sofre com picos de lentidão e quedas quando há acessos simultâneos em massa perto do prazo final, mas nós podemos evitar esse risco organizando o nosso cronograma para submeter as atividades com antecedência, garantindo a entrega mesmo diante de imprevistos de infraestrutura."*

### Incidente 2: A barreira didática no ensino técnico
* **Contexto Real:** Disciplinas avançadas onde o docente possui forte domínio técnico mas encontra barreiras na transmissão didática dos conteúdos.
* **Resposta Defensiva (Mindset Fixo):** *"O professor sabe muito mas não sabe dar aula. Como a explicação é confusa, não adianta estudar por fora; se eu tirar nota baixa, a culpa é exclusivamente da didática dele."*
* **Impacto Sistêmico:** Postura passiva de desistência e acumulação de lacunas técnicas graves na formação.
* **Reescrita com a Regra do "Ainda Não":** *"O professor *ainda* não encontrou a didática ideal para transmitir o conteúdo de forma fluida, mas nós podemos assumir o protagonismo usando documentações, videoaulas e apoio de monitores."*

---

## 2. Diretrizes de Code Review sem Ego

Para combater o Mindset Fixo em revisões de código e promover um ambiente de segurança psicológica, o time adota as seguintes diretrizes:

* **Foco no Código, Nunca na Identidade:** As críticas e sugestões devem ser direcionadas estritamente à lógica implementada, legibilidade ou desempenho, evitando qualquer julgamento pessoal sobre o desenvolvedor.
* **Cultura de Aprendizado Mútuo:** O Code Review não deve ser visto como um "tribunal de erros", mas sim como uma oportunidade de mentoria cruzada e partilha de conhecimento entre a equipa.
* **Clareza e Empatia:** Comentários construtivos em *Pull Requests* explicando o porquê da sugestão, abrindo espaço para o diálogo técnico.

---

## 3. Plano de Ação em 3 Sprints

A execução do projeto e a refatoração das posturas técnicas e de código são geridas através de um quadro Kanban (Trello) dividido nas seguintes Sprints:

* **Sprint 1: Post-Mortems e Segurança Psicológica**
  * *Objetivo:* Mapear incidentes reais de falhas e respostas defensivas.
  * *Entregas:* Documentação dos casos do AVA e da barreira didática no README e alinhamento da postura do grupo.
* **Sprint 2: Refatoração Ativa de Código Legado**
  * *Objetivo:* Aplicar boas práticas de engenharia em códigos complexos ou mal estruturados.
  * *Entregas:* Criação de branches dedicadas à otimização e aplicação das diretrizes de Code Review sem ego.
* **Sprint 3: Uso Estratégico de Copilotos e Ferramentas de IA**
  * *Objetivo:* Integrar inteligência artificial no fluxo de desenvolvimento para testes e tarefas repetitivas.
  * *Entregas:* Otimização do fluxo de trabalho humano, focando o esforço em arquitetura e resolução de problemas complexos de negócio.

---

## 🔗 Links do Projeto
* **Quadro Trello do Projeto:** [Aceder ao Trello do Workshop] (https://trello.com/invite/b/6ab591016ab989f2b36140d6/ATTIeb66809feea1a43046d4cdb2ded9fa2fA0143016/n1-at4)
