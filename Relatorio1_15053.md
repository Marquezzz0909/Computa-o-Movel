# Tutorial 1 -- Hello Kotlin. Hello Mobile Android World!

## Course

Computação Móvel

## Student(s)

Guilherme Marques

## Date

2026

## Repository URL

https://github.com/dinis6045/Trabalho-1-todos

------------------------------------------------------------------------

# 1. Introduction

Este trabalho tem como objetivo introduzir o desenvolvimento de
aplicações móveis utilizando Kotlin e Android Studio.

A aplicação desenvolvida consiste numa aplicação simples Hello World,
cuja finalidade é demonstrar os conceitos básicos de:

-   Estrutura de um projeto Android
-   Utilização da linguagem Kotlin
-   Criação de interfaces gráficas com XML Views
-   Execução da aplicação num emulador Android

O objetivo principal é compreender o funcionamento base de uma aplicação
Android e o processo completo desde a criação do projeto até à execução.

------------------------------------------------------------------------

# 2. System Overview

A aplicação criada é uma aplicação Android simples que apresenta uma
interface básica com um texto no ecrã.

## Funcionalidades principais

-   Mostrar uma mensagem Hello World no ecrã
-   Executar a aplicação num dispositivo virtual Android
-   Utilizar Kotlin como linguagem principal
-   Utilizar XML para a construção da interface gráfica

## Componentes principais

O sistema é composto por:

-   MainActivity.kt -- Responsável pela lógica da aplicação
-   activity_main.xml -- Responsável pelo layout visual da aplicação
-   AndroidManifest.xml -- Define as configurações principais da
    aplicação

------------------------------------------------------------------------

# 3. Architecture and Design

A aplicação segue a arquitetura básica de aplicações Android baseada em
Activities.

## Estrutura principal

HelloWorld │ ├── app │ ├── java │ │ └── MainActivity.kt │ ├── res │ │
└── layout │ │ └── activity_main.xml │ └── AndroidManifest.xml

### Componentes da arquitetura

Activity\
Representa um ecrã da aplicação. A MainActivity é o ponto de entrada da
aplicação.

Layout XML\
Define a interface gráfica da aplicação incluindo TextView,
posicionamento dos elementos, cores e dimensões.

------------------------------------------------------------------------

# 4. Implementation

## Linguagem utilizada

Kotlin foi utilizada como linguagem principal para o desenvolvimento da
aplicação.

## MainActivity.kt

A classe principal da aplicação é responsável por iniciar a interface,
carregar o layout e gerir o ciclo de vida da Activity.

Exemplo simplificado:

class MainActivity : AppCompatActivity() { override fun
onCreate(savedInstanceState: Bundle?) {
super.onCreate(savedInstanceState)
setContentView(R.layout.activity_main) } }

## Layout da aplicação

O layout foi desenvolvido em XML utilizando um TextView para mostrar a
mensagem principal da aplicação.

------------------------------------------------------------------------

# 5. Testing and Validation

Os testes foram realizados utilizando o emulador Android integrado no
Android Studio.

## Testes realizados

-   Compilação da aplicação
-   Execução da aplicação
-   Verificação da interface gráfica
-   Confirmação da apresentação do texto no ecrã

Resultado: a aplicação executa corretamente e apresenta o texto esperado
no ecrã.

------------------------------------------------------------------------

# 6. Usage Instructions

## Requisitos

Para executar a aplicação é necessário:

-   Android Studio
-   SDK Android instalado
-   Emulador Android configurado

## Passos para executar

1.  Abrir o projeto no Android Studio
2.  Aguardar sincronização do Gradle
3.  Selecionar um dispositivo virtual Android
4.  Clicar em Run
5.  A aplicação será executada no emulador

------------------------------------------------------------------------

# 7. Prompting Strategy

Durante o desenvolvimento foram utilizados prompts com ferramentas de IA
para auxiliar na criação de código e resolução de problemas.

Os prompts foram refinados iterativamente até obter os resultados
desejados.

------------------------------------------------------------------------

# 8. Autonomous Agent Workflow

Fluxo de desenvolvimento:

1.  Planeamento da aplicação
2.  Criação do projeto Android
3.  Implementação do layout
4.  Implementação da lógica em Kotlin
5.  Testes no emulador
6.  Correção de erros

------------------------------------------------------------------------

# 9. Verification of AI‑Generated Artifacts

Os conteúdos gerados com apoio de ferramentas de IA foram verificados
através de:

-   compilação do código
-   execução da aplicação
-   revisão manual do código
-   testes funcionais

------------------------------------------------------------------------

# 10. Human vs AI Contribution

## Contribuição humana

-   criação do projeto
-   configuração no Android Studio
-   testes da aplicação
-   organização do repositório GitHub

## Contribuição da IA

-   apoio na geração de exemplos de código
-   explicação de conceitos
-   auxílio na resolução de erros

------------------------------------------------------------------------

# 11. Ethical and Responsible Use

As ferramentas de IA foram utilizadas apenas como suporte ao
desenvolvimento.

Todo o código foi revisto manualmente e o estudante mantém
responsabilidade total pelo trabalho apresentado.

------------------------------------------------------------------------

# 12. Version Control and Commit History

O projeto foi gerido utilizando Git e GitHub.

Etapas realizadas:

1.  criação de repositório
2.  adição dos ficheiros
3.  commits de alterações
4.  envio para GitHub

------------------------------------------------------------------------

# 13. Difficulties and Lessons Learned

Dificuldades encontradas:

-   configuração inicial do Android Studio
-   erros no AndroidManifest
-   configuração do emulador

Aprendizagens:

-   estrutura de aplicações Android
-   utilização de Kotlin
-   criação de layouts XML
-   execução de apps móveis

------------------------------------------------------------------------

# 14. Future Improvements

Possíveis melhorias:

-   adicionar botões interativos
-   melhorar o design da interface
-   adicionar navegação entre ecrãs
-   incluir novas funcionalidades

------------------------------------------------------------------------

# 15. AI Usage Disclosure

Ferramenta de IA utilizada:

-   ChatGPT

Utilização:

-   explicação de conceitos
-   geração de exemplos de código
-   apoio na estrutura do relatório

O estudante mantém responsabilidade total pelo conteúdo final.
