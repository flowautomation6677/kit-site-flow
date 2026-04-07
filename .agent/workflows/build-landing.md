---
description: /build-landing - Workflow de criação de sites agnóstico via Flow Kit Site.
---

# Workflow: Build Landing Page

Trata-se da linha de montagem universal que pavimenta o desenvolvimento de sucesso da Flow Automation e engaja o ecossistema do template de múltiplos clientes simultâneos.

**Gatilho do Workflow:** Enviar na conversa o comando `/build-landing`.

## Passo 1 (Leitura de Contexto)
- Ao ouvir o gatilho, você como modelo de código **DEVE**, obrigatoriamente e antes de codificar telas inteiras, ler de forma atenta e literal os 2 arquivos abaixo indicados na pasta do template atual:
  - `@docs/wireframe-aprovado.md`: Para entender e capturar o Copy literário e a Estrutura da Página principal que será levantada.
  - `@docs/idv-cliente.md`: Para recolher os mapeamentos das Cores HEX específicas e Tipografias nativas do cliente em pauta.
- Paralelo a isso, não esqueça de fazer a pergunta sobre as regras de deploy de infraestrutura (`output`).

## Passo 2 (Setup Dinâmico)
- Munido das definições primárias capturadas (no `.md` do cliente), construa ou edite o arquivo `tailwind.config.ts` do respectivo repositório injetando ativamente ali suas cores nomeadas e declarando seus arquivos vinculados a temas e fontes tipográficas oriundas do `idv-cliente.md`. 

## Passo 3 (Componentização)
- Produza arquivos dedicados de Componentes de base (`Button`, `Section`, `Card`) no seu local de interface nativo isolado. Implemente nestas peças base todas as orientações regidas via Skills ativas (os "Princípios"), utilizando agora a injeção via código dinâmico das características gráficas do cliente avaliado.

## Passo 4 (Montagem)
- Projete o "layout" contido e traduzido no wireframe aprovado transformando bloco por bloco a ordem exposta no documento.
- Como o template requer fidedignidade literária, a regra primária do tradutor de layouts deve se aplicar: Nenhuma vírgula do texto original (copy) deverá ser alterada da matriz original aprovada, sob pena grave perante o processo.

## Passo 5 (Revisão)
- Efetuar a revisão do projeto compilando dados analíticos visuais focados em atestar a correlação funcional mobile para assegurar Mobile-First responsivo. Concluindo através da constatação visual que ateste de maneira analítica, não há restrições ou barreiras de contraste para as cores do cliente recém inserida em campos texto-fundo da interface final.
