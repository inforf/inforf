# Ronaldo Ferreira — QA Portfolio

## O que é este repositório

Este projeto representa como atuo como QA em um sistema real.

Não é um projeto de programação, e sim de validação de comportamento de software.

Aqui os testes automatizados são utilizados para:
- reproduzir problemas
- validar correções
- evitar regressões após atualizações

Os cenários simulam ações reais de usuários (login, navegação, validações de interface e regras de negócio).

A automação é apenas uma ferramenta.  
O objetivo principal é garantir que o sistema continue funcionando após mudanças.

---

## Sobre

QA focado em comportamento real de sistemas e prevenção de incidentes em produção.

Este portfólio demonstra como estruturo testes de software observando primeiro o usuário e depois o código.

A pergunta central aqui não é:

> "o sistema funciona?"

Mas sim:

> "o usuário consegue continuar trabalhando sem interrupções?"

---

## Estrutura do portfólio

O conteúdo representa o fluxo completo de qualidade em um produto:

1. observar comportamento do usuário
2. reproduzir o problema
3. investigar a causa
4. apoiar decisão de release

Cada repositório possui uma finalidade dentro desse fluxo.

---

## 1 — Observação de comportamento (ambiente real)

### QA Playground — ambiente com falhas intencionais
https://inforf.github.io/

Simula situações comuns de produção:

- formulário com validação incorreta
- navegação inconsistente
- mensagens confusas ao usuário
- problemas de interface
- erros de fluxo

Objetivo: identificar problemas antes que o usuário precise reportar.

### Coleta de sessão

Utilização de análise de navegação (ex: session replay) para observar:

- cliques repetidos
- retorno para telas anteriores
- hesitação
- dificuldade de navegação

Isso fornece evidência comportamental do problema.

---

## 2 — Reprodução e análise (automação + relatório)

### Automação do QA Playground
https://github.com/inforf/qa-playground-automation

Os comportamentos observados são reproduzidos em testes automatizados utilizando Playwright.

O foco não é testar o código, e sim validar o comportamento esperado do sistema.

Cobertura:

- fluxo principal
- validações de formulário
- estados inválidos
- mensagens ao usuário
- consistência de interface

Após cada execução é possível identificar:

- impacto no usuário
- severidade
- frequência
- necessidade de bloqueio de release

---

## 3 — Validação contínua (pipeline e decisão de release)

### QA Automation Portfolio
https://github.com/inforf/qa-automation-portfolio

Demonstra validação contínua após alterações no sistema.

Fluxos validados:

- login
- navegação
- carrinho
- checkout
- validação de API

Pipeline executa automaticamente:

1. commit
2. execução E2E
3. coleta de resultados
4. decisão de liberação

Objetivo: impedir regressões após deploy.

---

## O que este portfólio demonstra

Mais do que automação, demonstra qualidade de produto:

- análise de comportamento do usuário
- investigação de incidentes
- reprodução de defeitos
- validação funcional
- prevenção de regressão
- apoio à decisão de release
- integração com desenvolvimento

---

## Tecnologias

- Playwright
- TypeScript
- Node.js
- GitHub Actions
- REST API
- JSON
- análise de logs

---

## Conceito

Qualidade não é a última etapa.

É antecipação de incidente.

Um sistema pode:
- não apresentar erro técnico
- não cair
- passar em testes funcionais

E ainda assim impedir o usuário de concluir a tarefa.

Qualidade começa quando o impacto no usuário passa a fazer parte da decisão técnica.

---

## Contato

LinkedIn: https://www.linkedin.com/in/ronaldo-ferreira-qa  
Email: inforf@hotmail.com
