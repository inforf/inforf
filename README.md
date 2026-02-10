# Ronaldo Ferreira

QA focado em comportamento real do sistema e prevenção de incidentes em produção.

Este perfil não foi criado apenas para demonstrar automação de testes.
Ele demonstra como QA pode apoiar decisões de liberação analisando risco real ao usuário.

A pergunta central aqui não é:
> "o sistema funciona?"

É:
> "o usuário consegue concluir a tarefa com segurança?"

---

## Estrutura do portfólio

O portfólio representa o fluxo completo de qualidade em um produto:

1. observar o comportamento do usuário
2. reproduzir o problema
3. impedir regressão
4. apoiar decisão de release

Cada repositório cobre uma dessas etapas.

---

## 1 — Observação de comportamento (ambiente real)

🔎 **QA Playground — ambiente público com falhas intencionais**  
https://inforf.github.io/

O site simula problemas reais de produção:

- modal que não fecha
- carregamento infinito causado por API lenta
- formulário sem validação
- problema de acessibilidade (contraste insuficiente)

O objetivo não é derrubar o sistema.  
É demonstrar que um sistema pode funcionar tecnicamente e ainda impedir o usuário de concluir a tarefa.

### Coleta de sessões

O ambiente utiliza análise de sessão (Microsoft Clarity) para registrar interações reais dos visitantes.

Isso permite observar:

- cliques repetidos
- abandono de fluxo
- tentativa de ações sem resposta
- dificuldade de navegação

O Clarity fornece a evidência visual do comportamento.

---

## 2 — Reprodução e análise (automação + relatório)

🧪 **Automação do QA Playground + geração de relatório**  
https://github.com/inforf/qa-playground-automation

Os comportamentos observados são reproduzidos em testes automatizados com Playwright.

Cenários automatizados:

- usuário preso em modal
- requisição que nunca conclui
- envio de formulário inválido
- verificação de acessibilidade básica

Após a execução, um processo local analisa os resultados e gera um relatório estruturado contendo:

- resumo técnico
- impacto para o usuário
- severidade
- risco de negócio
- recomendação

Ou seja, o teste não termina em "passou ou falhou".  
Ele gera informação para tomada de decisão.

---

## 3 — Validação contínua (pipeline e decisão de release)

⚙️ **QA Automation Portfolio (E2E + API + CI)**  
https://github.com/inforf/qa-automation-portfolio

Este projeto demonstra automação aplicada a um sistema completo.

Fluxos cobertos:

- login
- navegação
- carrinho
- checkout
- confirmação de pedido
- validação de respostas de API

A suíte executa automaticamente em CI (GitHub Actions) a cada commit.

Pipeline:

1. ambiente preparado
2. aplicação iniciada
3. testes E2E executados
4. testes de API executados
5. falhas bloqueiam a liberação

Aqui o teste deixa de ser verificação manual e passa a apoiar decisão de deploy.

---

## O que este portfólio demonstra

Mais do que automação, o foco é qualidade de produto.

Capacidades demonstradas:

- análise de comportamento do usuário
- investigação de falhas
- reprodução de defeitos
- automação E2E
- testes de API
- prevenção de regressão
- geração de relatório técnico
- integração contínua
- apoio à decisão de release

---

## Tecnologias

Playwright • TypeScript • Node.js • GitHub Actions • REST API • HTTP • JSON • Session Replay Analysis

---

## Conceito

QA aqui não é tratado como etapa final.

É tratado como antecipação de incidente.

Um sistema pode:
- não apresentar erro
- não quebrar
- passar em testes funcionais

E ainda assim impedir o usuário de concluir a tarefa.

Qualidade começa quando o impacto ao usuário passa a fazer parte da decisão técnica.

---

## Contato

LinkedIn: https://www.linkedin.com/in/ronaldo-ferreira-qa  
Email: inforf@hotmail.com
