# Ronaldo Ferreira — QA Portfolio

Qualidade de software não é encontrar defeitos depois da entrega.  
É impedir que o usuário seja impactado.

Meu foco é antecipar falhas antes do release, reduzir risco funcional e dar segurança para a equipe liberar versões com confiança.

Este portfólio demonstra como analiso comportamento de sistemas, identifico riscos, automatizo validações críticas e apoio a decisão de publicação de uma versão.

---

## Sobre

Atuo com análise de comportamento de sistemas web, investigação de incidentes, validação funcional e acompanhamento de releases.

Minha experiência vem principalmente de ambientes reais de produção, onde aprendi algo importante:

Um sistema pode **funcionar tecnicamente** e ainda assim estar errado para o usuário.

Por isso minha atuação não é baseada apenas em executar casos de teste, mas em entender:

- regras de negócio
- fluxo do usuário
- impacto de mudanças
- risco de publicação

O objetivo não é apenas encontrar erros.  
É evitar que eles cheguem ao cliente.

---

## Filosofia de trabalho

Busco atuar antes do problema chegar ao usuário final.

O papel do QA não é somente reportar defeitos.  
É criar mecanismos para que eles não aconteçam.

Quando um erro chega em produção, o trabalho não falhou —  
mas a oportunidade de prevenção existia.

Por isso minha atuação prioriza:

- validação de regras de negócio antes do deploy
- análise de impacto de mudanças
- testes em fluxos críticos do usuário
- automação para evitar regressão
- evidências para decisão de release

Produção deve ser exceção, não rotina.

---

## Estrutura do portfólio

O conteúdo está organizado para representar o ciclo completo de qualidade dentro de um produto:

1. Observar o comportamento real do sistema
2. Reproduzir e analisar riscos
3. Automatizar validações
4. Apoiar a decisão de release

Cada repositório representa uma etapa desse processo.

---

## 1 — Observação de comportamento (ambiente real)

### QA Playground — ambiente com falhas intencionais  
https://inforf.github.io/qa-playground  
https://inforf.github.io

Este projeto simula situações reais que podem ocorrer em aplicações web.

O objetivo não é demonstrar falhas, mas demonstrar prevenção.

O ambiente foi construído com defeitos intencionais para mostrar como identificar riscos **antes que uma versão seja publicada**.

Exemplos de cenários presentes:

- validação incorreta de formulário
- mudança de contexto sem revalidação
- inconsistência de navegação
- falhas de fluxo do usuário
- comportamentos inesperados de interface

Aqui o foco não é apenas executar testes, mas observar:

- como o usuário interage
- onde ocorre fricção
- onde existe risco de erro humano
- qual impacto de negócio o problema causa

---

## 2 — Reprodução e análise (automação + relatório)

### Automação do QA Playground
https://github.com/inforf/qa-playground-automation

Os comportamentos observados são reproduzidos automaticamente usando **Playwright**.

A automação executa:

- fluxos críticos
- validações funcionais
- verificação de comportamento
- coleta de evidências

Após a execução:

1. Os testes geram relatórios estruturados
2. O relatório é enviado para uma IA rodando localmente (Ollama)
3. A IA analisa o resultado
4. É gerado um relatório interpretado

A automação não serve apenas para executar testes.

Ela funciona como uma validação automatizada de release:  
o relatório gerado permite avaliar rapidamente se a versão pode ser entregue com segurança.

A IA local interpreta os resultados para transformar evidência técnica em informação compreensível para decisão.

Ou seja, não é apenas "teste passou ou falhou".  
É **apoio à decisão de publicação**.

---

## 3 — Validação contínua (pipeline e regressão)

### QA Automation Portfolio
https://github.com/inforf/qa-automation-portfolio

Este projeto é independente do Playground.

Ele demonstra automação aplicada em diferentes aplicações de teste públicas para demonstrar conhecimento em:

- automação E2E
- testes de API
- regressão automatizada
- CI/CD

Fluxos automatizados incluem:

- login
- navegação
- carrinho
- checkout
- validação de API

Pipeline executado via GitHub Actions:

1. execução automática
2. testes E2E
3. geração de relatório
4. evidências anexadas
5. bloqueio em caso de falha

O objetivo é demonstrar como a automação protege o sistema contra regressões após alterações.

---

## O que este portfólio demonstra

Mais do que ferramentas, o foco é qualidade de produto.

Capacidades apresentadas:

- análise de comportamento do usuário
- identificação de risco funcional
- reprodução estruturada de defeitos
- documentação clara
- automação E2E
- testes de API
- validação de regressão
- integração contínua
- apoio à decisão de release

---

## Tecnologias

- Playwright
- TypeScript / JavaScript
- Node.js
- GitHub Actions
- REST API
- HTML / CSS
- Análise de logs
- Relatórios automatizados
- IA local (Ollama)

---

## Conceito

Software de qualidade não é aquele sem bugs.
É aquele em que o usuário não sofre o impacto das falhas.

O objetivo do QA não é bloquear deploy.
É evitar que a equipe descubra problemas através do cliente.

Quanto mais cedo o risco é identificado, menor o custo, menor o impacto e maior a confiança na entrega.

Qualidade não é uma etapa do projeto.  
É um sistema de prevenção.

Atuar junto ao time, de forma colaborativa e integrada, fortalece as entregas, melhora a comunicação entre áreas e facilita a prevenção de problemas antes da publicação.

---

## Contato

LinkedIn: https://www.linkedin.com/in/ronaldo-ferreira-qa  
Email: inforf@hotmail.com
