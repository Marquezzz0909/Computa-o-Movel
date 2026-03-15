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

O objetivo deste trabalho é introduzir os conceitos básicos do
desenvolvimento de aplicações móveis utilizando Kotlin e Android Studio.

A aplicação desenvolvida consiste numa aplicação simples do tipo Hello
World, cujo propósito é demonstrar como criar, compilar e executar uma
aplicação Android.

Este trabalho permite compreender: - Estrutura de um projeto Android -
Utilização da linguagem Kotlin - Criação de interfaces gráficas com XML
Views - Execução da aplicação num emulador Android

------------------------------------------------------------------------

# 2. System Overview

A aplicação apresenta uma interface simples onde é exibida uma mensagem
no ecrã.

Funcionalidades principais: - Mostrar uma mensagem de texto no ecrã -
Executar a aplicação num dispositivo virtual Android - Utilizar Kotlin
para a lógica da aplicação - Utilizar XML para a interface gráfica

Componentes principais: - MainActivity.kt --- lógica principal da
aplicação - activity_main.xml --- layout da interface -
AndroidManifest.xml --- configuração da aplicação

------------------------------------------------------------------------

# 3. Architecture and Design

Estrutura do projeto:

HelloWorld │ ├── app │ ├── java │ │ └── MainActivity.kt │ ├── res │ │
└── layout │ │ └── activity_main.xml │ └── AndroidManifest.xml

A aplicação segue a arquitetura básica Android baseada em Activities.

------------------------------------------------------------------------

# 4. Implementation

A aplicação foi implementada utilizando Kotlin para a lógica e XML para
o layout.

Exemplo simplificado da MainActivity:

class MainActivity : AppCompatActivity() { override fun
onCreate(savedInstanceState: Bundle?) {
super.onCreate(savedInstanceState)
setContentView(R.layout.activity_main) } }

O layout contém um TextView que apresenta a mensagem da aplicação.

------------------------------------------------------------------------

# 5. Testing and Validation

A aplicação foi testada utilizando o emulador Android do Android Studio.

Testes realizados: - Compilação da aplicação - Execução no emulador -
Verificação da interface gráfica - Confirmação da mensagem no ecrã

Resultado: a aplicação executa corretamente.

------------------------------------------------------------------------

# 6. Usage Instructions

Requisitos: - Android Studio - Android SDK - Emulador Android

Passos: 1. Abrir o projeto no Android Studio 2. Aguardar sincronização
do Gradle 3. Selecionar um dispositivo virtual 4. Clicar em Run 5. A
aplicação será executada

------------------------------------------------------------------------

# 7. Prompting Strategy

Durante o desenvolvimento foram utilizados prompts com ferramentas de IA
para apoio na geração de código e resolução de problemas.

------------------------------------------------------------------------

# 8. Autonomous Agent Workflow

Fluxo de desenvolvimento: 1. Planeamento da aplicação 2. Criação do
projeto Android 3. Implementação do layout 4. Implementação da lógica 5.
Testes no emulador 6. Correção de erros

------------------------------------------------------------------------

# 9. Verification of AI-Generated Artifacts

O código gerado com apoio de IA foi verificado através de: -
compilação - execução da aplicação - revisão manual do código

------------------------------------------------------------------------

# 10. Human vs AI Contribution

Contribuição humana: - criação do projeto - implementação - testes -
organização do GitHub

Contribuição da IA: - apoio na explicação de conceitos - geração de
exemplos de código - ajuda na estrutura do relatório

------------------------------------------------------------------------

# 11. Ethical and Responsible Use

As ferramentas de IA foram utilizadas apenas como apoio. O estudante
mantém responsabilidade total pelo trabalho.

------------------------------------------------------------------------

# 12. Version Control and Commit History

O projeto foi gerido com Git e GitHub: - criação de repositório -
commits - envio para GitHub

------------------------------------------------------------------------

# 13. Difficulties and Lessons Learned

Dificuldades: - configuração inicial do Android Studio - erros no
AndroidManifest - configuração do emulador

Aprendizagens: - estrutura de apps Android - utilização de Kotlin -
criação de layouts XML

------------------------------------------------------------------------

# 14. Future Improvements

Possíveis melhorias: - adicionar botões interativos - melhorar design da
interface - adicionar novas atividades

------------------------------------------------------------------------

# 15. AI Usage Disclosure

Ferramenta utilizada: - ChatGPT

Utilização: - explicação de conceitos - geração de exemplos de código -
apoio na organização do relatório

O estudante mantém responsabilidade pelo conteúdo final.
