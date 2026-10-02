
## 🤖 Automação Web CodeceptJS - Playwright - Node.js + JavaScript (FasTix)

<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/d824a189-1a3d-43a3-a951-29b8a8d5152b" />

<img width="1908" height="1020" alt="image" src="https://github.com/user-attachments/assets/c4a8dd60-10fc-4ad0-b3af-0026098aa6c5" />

<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/c23cd596-ee67-4ba2-a957-e3e0e85f0ed5" />

<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/5f897dc5-d6be-4261-beff-70c8222ec644" />


A **FasTix** é uma plataforma de comercialização, distribuição e intermediação de ingressos, além de produtos e serviços associados ao mercado de entretenimento no Brasil. 

O projeto consiste na documentação **Gherkin (linguagem para descrever o comportamento do software)** e **BDD (Behavior-Driven Development)**, em uma suíte de testes automatizados para o site FasTix (https://fastix.com.br), **baseada na versão de produção ativa publicada em julho de 2026.**

A suíte automatizada do FasTix **reúne 586 testes distribuídos em 6 Features**, cobrindo toda a jornada do usuário na plataforma do primeiro acesso à compra de ingressos **sob 17 dimensões de qualidade diferentes, não apenas validação funcional.**

O site foi desenvolvido pela **empresa americana Web Solutions FL** (https://www.websolutionsfl.com/).

Todos os testes e a estrutura deste repositório foram desenvolvidos por **Diogo Amancio.**

---

  ## 📑 Índice

- [📱 Sobre o app](#-sobre-o-app)
- [🤖 Codecept](#-codeceptjs)
- [🏷️ Tecnologias utilizadas](#️-tecnologias-utilizadas)
- [⚙️ Estrutura da Suíte de Testes FasTix](#️-estrutura-da-suíte-de-testes-fastix)
- [📋 Tipos de teste realizados na suíte](#-tipos-de-teste-realizados-na-suíte)
- [▶️ Como executar este projeto](#%EF%B8%8F-como-executar-este-projeto)
- [🧰 Ambiente e rotina diária](#-ambiente-e-rotina-diária)
- [✅ Uso](#-uso)
- [📁 Estrutura do repositório](#-estrutura-do-repositório)
- [🧭 A Jornada do usuário](#-a-jornada-do-usuário)
- [🧠 Estratégia e cobertura de Testes ](#-estratégia-e-cobertura-de-testes)
- [🎯 Distribuição da cobertura ](#-distribuição-da-cobertura)
- [📲 Abordagem técnica ](#-abordagem-técnica)
- [⌨️ Suíte de Testes Automatizados ](#%EF%B8%8F-suíte-de-testes-automatizados)
- [🔭 Feature Explorar Eventos ](#-feature-explorar-eventos)
- [🙋 Feature Suporte e Ajuda ](#-feature-suporte-e-ajuda)
- [🏠 Feature Tela Inicial ](#-feature-tela-inicial)
- [📢 Feature Publicar Eventos ](#-feature-publicar-eventos)
- [🎟️ Feature Comprar Ingressos ](#%EF%B8%8F-feature-comprar-ingressos)
- [👤 Feature Criar Conta ](#-feature-criar-conta)
- [🐞 Bugs Encontrados](#-bugs-encontrados)
- [🔗 Bug × Feature × Causa Raiz](#-bug--feature--causa-raiz)
- [📊 Análise da Suíte de Testes](#-análise-da-suíte-de-testes)
- [🕵🏻‍♂️ Root Cause Analysis (RCA)](#%E2%80%8D%EF%B8%8F-root-cause-analysis-rca)
- [🧪 Metodologia de teste](#-metodologia-de-teste)
- [🚧 Limitações e escopo](#-limitações-e-escopo)
- [🚀 Próximos passos (CI/CD)](#-próximos-passos-cicd)
- [💡 Aprendizados técnicos](#-aprendizados-técnicos)
- [📬 Contato](#-contato)


- ---

## 📱 Sobre o app

A FasTix é uma plataforma voltada à venda, distribuição e intermediação de ingressos, além de oferecer produtos e serviços relacionados ao setor de entretenimento no Brasil.

Atuando como uma ticketeira, a FasTix conecta o público aos organizadores de eventos, realiza a intermediação de ingressos e facilita a venda online de entradas para shows de música, festivais, cursos, palestras, exposições e eventos esportivos, independentemente do porte dos produtores de evento (pequeno, médio ou grande).

Também oferece tecnologia para produtores, com controle total para os organizadores realizarem a gestão de vendas e o controle de acesso do público no dia do evento (check-in).


---

## 🤖 CodeceptJS

O **CodeceptJS** utiliza recursos do ecossistema **Node.js e JavaScript**, dessa forma ele integra recursos do ecossistema **Node.js e JavaScript**, integrando o **Playwright** para a execução de testes automatizados em aplicações Web.

### Pré-requisitos para utilização no Windows
* **Node.js**
* **JavaScript**
* **CodeceptJS**
* **Playwright: Para a execução de testes automatizados da aplicação Web da FasTix.**

---

## 🏷️ Tecnologias utilizadas

![Web Testing](https://img.shields.io/badge/Web%20Testing-Automation-1E88E5?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Test%20Automation-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CodeceptJS](https://img.shields.io/badge/CodeceptJS-Test%20Automation-6C63FF?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-Web%20Testing-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Testes Automatizados](https://img.shields.io/badge/Automated%20Testing-QA-1E88E5?style=for-the-badge)
![Test Scripts](https://img.shields.io/badge/Test%20Scripts-Automation-CB171E?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)
![Gherkin](https://img.shields.io/badge/Gherkin-BDD-5B5B5B?style=for-the-badge)

---

## ⚙️ Estrutura da Suíte de Testes FasTix

A suíte de testes da FasTix é **organizada em 6 Features composto por 586 testes.**

Dessa maneira, seguindo a jornada do usuário no site, desde o login, passando pela exploração de eventos, pelo acesso ao suporte e à ajuda, pela tela inicial, pela publicação de eventos, pela compra de ingressos e pela criação de uma conta.

| Feature                   |  Testes Automatizados |
| ------------------------- | ------: |
| Feature_Explorar Eventos            |      70 |
| Feature_Suporte e Ajuda            |      75 |
| Feature_Tela Inicial          |      164 |
| Feature_Publicar Eventos|      98 |
| Feature_Comprar Ingressos           |      127 |
| Feature_Criar Conta           |      52 |
| **Total**                 | **586** |


---

## 📝 Tipos de teste realizados na suíte

| Tipos de Testes |
| ------------------------- |
| Testes End-to-End (E2E) |
| Testes Funcionais |
| Testes de Regressão |
| Testes de Navegação |
| Testes de Interface (UI) |
| Testes de Responsividade |
| Testes de Acessibilidade |
| Testes de Performance |
| Testes de Estabilidade |
| Testes de Estresse |
| Testes de Robustez |
| Testes de Validação de Dados |
| Testes de Integridade |
| Testes de Compatibilidade de Navegação |
| Testes de Monitoramento de Erros |
| Testes de Integridade Visual |
| Testes de Persistência de Estado |
| **Total: 17 tipos de testes** |


---

## ▶️ Como executar este projeto 

Um resumo rápido para quem está clonando este repositório pela primeira vez. Para ver o passo a passo completo, consulte a seção **🧰 Ambiente e rotina diária** mais abaixo.

## 📌 Pré-requisitos

Configuração do ambiente com a instalação das seguintes tecnologias:

- **Node.js**  ([guia oficial de instalação](https://nodejs.org/learn/getting-started/an-introduction-to-the-npm-package-manager))
- **npm**
- **CodeceptJS**  ([guia oficial de instalação](https://codecept.io/installation/))
- **Playwright** ([guia oficial de instalação](https://playwright.dev/docs/intro))

## 📌 Passos

1. **Realizar o Download ZIP do projeto:**


<img width="565" height="495" alt="image" src="https://github.com/user-attachments/assets/2f573976-f5fc-4681-9681-cfe38c46cbe6" />

---

2. **Acessar a pasta Arquivos JavaScript (Testes Automatizados):**

<img width="512" height="75" alt="image" src="https://github.com/user-attachments/assets/381c1dfa-930c-487b-a173-1e1a1d6d8540" />


## 📌 Plano de Testes

Para garantir uma cobertura abrangente das funcionalidades da plataforma, o projeto foi dividido em seis Features, cada uma responsável por validar um conjunto específico de comportamentos do sistema.

Todos os cenários foram documentados utilizando a linguagem Gherkin, (por meio das palavras-chave Dado, Quando, Então e E) pensando na facilidade de comunicação para as equipes de desenvolvimento, qualidade (QA), produto e demais áreas envolvidas da FasTix.


1. **Acessar a pasta Plano de Testes:**

<img width="507" height="72" alt="image" src="https://github.com/user-attachments/assets/acc7b565-33c0-404d-92ba-4a62872f65c4" />

---

2. **Acessar o arquivo FasTix - Plano de Testes.docx:**

<img width="596" height="55" alt="image" src="https://github.com/user-attachments/assets/41cc0bbf-1210-4ab5-8918-bf120793e16a" />

---

3. **Consultar o Plano de Testes:**

<img width="1817" height="915" alt="image" src="https://github.com/user-attachments/assets/0623268e-849b-4e04-9a19-1e5cca74de99" />

---

## 📌 Bugs e Issues

Durante a execução dos testes automatizados foram identificados alguns comportamentos inesperados na plataforma.

Para documentar essas ocorrências foi elaborado um arquivo específico de Bugs e Issues, contendo as seguintes evidências de testes:

|Evidências                 |  
| ------------------------- | 
| Descrição detalhada de cada problema;            |     
| Passos para reprodução;         |     
| Resultado obtido;       |    
| Resultado esperado; |    
| Capturas de tela (screenshots);           |     
|Link para acesso de vídeos demonstrando os comportamentos encontrados          |     
|Propostas de melhoria para a plataforma         |     


Esse material auxilia na análise, priorização e correção das falhas identificadas, contribuindo para a evolução contínua da qualidade da plataforma.

1. **Acessar a pasta Bugs e Issues:**

<img width="507" height="57" alt="image" src="https://github.com/user-attachments/assets/28eaf619-5e42-423f-bbfb-18e625c82d78" />

---

2. **Acessar o arquivo FasTix - Bugs e Issues.docx:**

<img width="520" height="52" alt="image" src="https://github.com/user-attachments/assets/2f109dba-4ac1-4402-94d7-57959eacbab6" />

---

3. **Consultar o Bugs e Issues:**

<img width="1801" height="910" alt="image" src="https://github.com/user-attachments/assets/a4fc4703-d22f-4169-b7f4-5639a2eca8bb" />


---

## 🧰 Ambiente e rotina diária

O ambiente de testes combina:

### Pré-requisitos para utilização no Windows
* **Node.js**
* **JavaScript**
* **CodeceptJS**
* **Playwright:Para a execução de testes automatizados da aplicação Web da FasTix.**

## ⚙️ Configuração do Ambiente (Windows)

### Instalação do CodeceptJS com Playwright

### 📍 1. Instalar o Node.js

O CodeceptJS depende do Node.js para funcionar.

1. Acesse: https://nodejs.org/
2. Execute o instalador utilizando as configurações padrão.

### 📍 2. Verificar a instalação

```bash
node -v
```

Em seguida:

```bash
npm -v
```

> ⚠️ **Importante:** Se ambos os comandos retornarem uma versão, a instalação foi concluída com sucesso.

### 📍 3. Criar o projeto

```bash
mkdir MeuProjeto
cd MeuProjeto
```

### 📍 4. Inicializar o projeto Node.js

```bash
npm init -y
```

Esse comando cria automaticamente o arquivo:

```text
package.json
```

### 📍 5. Instalar o CodeceptJS

```bash
npm install codeceptjs --save-dev
```

### 📍 6. Instalar o Playwright

Instale a biblioteca:

```bash
npm install playwright --save-dev
```

Depois instale os navegadores utilizados pelo Playwright:

```bash
npx playwright install
```

### 📍 7. Inicializar o CodeceptJS

```bash
npx codeceptjs init
```

### 📍 8. Configurar o assistente

| Pergunta | Resposta |
|----------|----------|
| **Where are your tests located?** | `./tests` |
| **What helpers do you want to use?** | `Playwright` |
| **Where is your application running?** | `https://fastix.com.br` *(ou a URL da aplicação)* |
| **Browser in which testing will be performed** | `chromium` |
| **Do you want to generate example tests?** | `Yes` |
| **Do you want to use TypeScript?** | `No` *(caso utilize JavaScript)* |

---

> ⚠️ **Importante:** A pasta `output/` armazena screenshots, vídeos e relatórios de falhas gerados automaticamente durante a execução dos testes não deve ser versionada no repositório (adicione ao `.gitignore`).

### 📍 9. Criar um teste de exemplo

Crie o arquivo:

```text
tests/teste_inicial_test.js
```

```javascript
Feature("Teste Inicial");

Scenario("Abrir o Google", ({ I }) => {
  I.amOnPage("https://www.google.com");
  I.see("Google");
});
```

### 📍 10. Verificação final

Execute:

```bash
npx codeceptjs run
```

> ⚠️ **Importante:** se o teste for executado sem erros, o ambiente foi configurado corretamente.

---

## ✅ Uso

Após configurar o ambiente e instalar todas as dependências, utilize os comandos abaixo para executar os testes automatizados.

### 📍 Executar todos os testes automatizados

Executa todas as Features e todos os cenários de teste do projeto FasTix.

```bash
npx codeceptjs run
```

### 📍 Executar uma Feature específica

Executa todos os cenários pertencentes a uma Feature específica.

```bash
npx codeceptjs run --grep "nome_da_feature"
```

Exemplo:

```bash
npx codeceptjs run --grep "suporteeajuda"
```

Abaixo, segue a lista dos comandos para a execução de cada uma das seis Features específicas do projeto:

```bash
# 1 - Feature Explorar Eventos
npx codeceptjs run --grep "explorareventos"

# 2 - Feature Suporte e Ajuda
npx codeceptjs run --grep "suporteeajuda"

# 3 - Feature Tela Inicial
npx codeceptjs run --grep "telainicial"

# 4 - Feature Publicar Eventos
npx codeceptjs run --grep "publicareventos"

# 5 - Feature Comprar Ingressos
npx codeceptjs run --grep "compraringressos"

# 6 - Feature Criar Conta
npx codeceptjs run --grep "criarconta"
```

### 📍 Executar um cenário específico de uma Feature

Executa apenas um cenário de teste.

```bash
npx codeceptjs run --grep "nome_da_feature + número_do_cenário"
```

Exemplo:

```bash
npx codeceptjs run --grep "suporteeajuda33"
```

### 📍 Exibir cada passo da execução

```bash
npx codeceptjs run --steps
```

### 📍 Executar em modo detalhado

```bash
npx codeceptjs run --verbose
```

### 📍 Executar em modo detalhado exibindo todos os passos

```bash
npx codeceptjs run --steps --verbose
```

---

## 📁 Estrutura do repositório

```text
MeuProjeto/
├── tests/
│   └── example_test.js
├── output/
├── steps_file.js
├── codecept.conf.js
├── package.json
└── node_modules/
```


---

## 🧭 A Jornada do usuário

A suíte tem como objetivo automatizar e validar a jornada completa do usuário dentro da FasTix. 

Diferente de um fluxo estritamente linear, a plataforma atende dois perfis de usuário com caminhos próprios o comprador de ingressos e o produtor de eventos além de uma camada de suporte acessível a qualquer momento:

```text
Fluxo do Comprador:
Tela Inicial → Explorar Eventos → Criar Conta / Login → Comprar Ingressos → Pagamento e Confirmação
```

```text
Fluxo do Produtor:
Tela Inicial → Publicar Eventos → Login (Google / Apple / E-mail) → Gerenciamento de Eventos e Equipes
```

```text
Suporte e Ajuda: acessível a qualquer momento da jornada, funcionando como camada transversal de apoio ao usuário.
```

Os testes não validam apenas funcionalidades isoladas, mas também simulam comportamentos e situações próximas da utilização real de uma plataforma de venda de ingressos desde a descoberta de um evento na página inicial, passando pela pesquisa e seleção do evento certo, a criação de conta ou autenticação, a escolha e o pagamento dos ingressos, até a possibilidade de o mesmo usuário se tornar um produtor e publicar seus próprios eventos.

As informações a seguir apresentam a estrutura completa da suíte de testes da FasTix, organizada em seis Features que representam, em conjunto, a jornada do usuário na plataforma.

Cada **Feature** possui um conjunto de cenários que cobre desde o caminho feliz até casos de borda, testes de estresse, acessibilidade, performance e segurança, permitindo visualizar de forma clara o que é validado em cada etapa desde a descoberta do evento na Tela Inicial até a confirmação do pagamento na etapa de Comprar Ingressos, passando pelo suporte ao usuário e pela publicação de novos eventos por produtores.

---

## 🧠 Estratégia e cobertura de Testes 


**A suíte automatizada do FasTix reúne 586 testes distribuídos em 6 Features**, cobrindo toda a jornada do usuário na plataforma do primeiro acesso à compra de ingressos sob 17 dimensões de qualidade diferentes, não apenas validação funcional. 

A cobertura foi dimensionada por risco de negócio: as áreas com maior impacto em receita e alcance de usuários (Tela Inicial e Comprar Ingressos) concentram o maior volume de testes.

A FasTix é uma plataforma de venda, distribuição e intermediação de ingressos, atuando como ticketeira para produtores de eventos de todos os portes como shows, festivais, cursos, palestras, exposições e eventos esportivos. Além da venda ao público, oferece aos organizadores ferramentas de gestão de vendas e controle de acesso (check-in) no dia do evento. 

Esse escopo combina e-commerce, gestão de conteúdo publicado por terceiros e operação em tempo real, o que torna qualquer falha silenciosa potencialmente cara seja em receita, confiança do produtor ou experiência do público na entrada do evento.

## 🎯 Distribuição da cobertura

| Feature                     | Testes Automatizados | Papel na jornada |
| ---------------------------- | --------------------: | --- |
| Feature_Tela Inicial         |                   164 | Ponto de entrada, maior raio de impacto de qualquer instabilidade |
| Feature_Comprar Ingressos    |                   127 | Fluxo que gera receita diretamente |
| Feature_Publicar Eventos     |                    98 | Ferramenta de gestão para produtores |
| Feature_Suporte e Ajuda      |                    75 | Canal de contato, SEO e institucional |
| Feature_Explorar Eventos     |                    70 | Busca e navegação por carrossel de eventos divulgados na page|
| Feature_Criar Conta          |                    52 | Onboarding de novos usuários |
| **Total**                    |               **586** | — |

> ⚠️ **Importante:** A distribuição não é uniforme por decisão, não por lacuna: Tela Inicial e Comprar Ingressos concentram o maior volume porque representam, respectivamente, o ponto de contato de praticamente todo usuário e o fluxo com impacto financeiro direto — qualquer regressão ali tem o maior raio de dano possível ao negócio.

## 📲 Abordagem técnica

Cada Feature é testada sob um subconjunto relevante de 17 dimensões de qualidade:


| Tipos de Testes                            |
| ------------------------------------------ |
| Testes Funcionais                          |
| Testes End-to-End (E2E)                    |
| Testes de Navegação                        |
| Testes de Interface (UI)                   |
| Testes de Responsividade                   |
| Testes de Acessibilidade                   |
| Testes de Performance                      |
| Testes de Estabilidade                     |
| Testes de Estresse                         |
| Testes de Robustez                         |
| Testes de Validação de Dados               |
| Testes de Integridade                      |
| Testes de Compatibilidade de Navegação     |
| Testes de Monitoramento de Erros           |
| Testes de Contrato de Eventos de Analytics |
| Testes de SEO e Metadados                  |
| Testes de Segurança                        |
| **Total: 17 tipos de testes**              |


Todos os testes foram aplicados conforme o que cada parte da aplicação efetivamente arrisca quebrar, não como um checklist genérico repetido igualmente em toda a plataforma. 

Um fluxo de checkout demanda rigor em cálculo de valores e estabilidade sob múltiplas interações; uma página institucional de suporte demanda mais atenção a acessibilidade, SEO e integridade de links externos. 

Essa adaptação por contexto é o que diferencia uma suíte estruturada por risco de uma simples réplica de casos de teste entre páginas.

O conjunto completo funciona como base de regressão contínua: qualquer alteração na plataforma pode ser validada contra os 586 cenários existentes antes de chegar ao usuário final, ao produtor de evento ou à operação de check-in.

---

## ⌨️ Suíte de Testes Automatizados 

> ⚠️ **Importante:** Este documento aplica as correções de coerência e padronização identificadas na revisão geral da suíte, tabelas de cenários corrigidas para coluna única, nomes de dimensão unificados entre título de seção e matriz, nível de heading padronizado (H2 para todas as seções de "Regressão" e "Matriz de cobertura") e legendas padronizadas em formato de tabela.

## 🔭 Feature Explorar Eventos

| Feature |
| --- |
| Feature_Explorar Eventos |
| 0001 - Acessar a página de eventos (Botão: Explorar eventos) |
| 0002 - Acessar a página de eventos (segunda opção de acesso via ícone fast-forward) |
| 0003 - Acessar a página de eventos (Botão: Explorar eventos) e verificar a navegação por scroll |
| 0004 - Acessar a página de eventos (segunda opção de acesso via ícone fast-forward) e verificar a navegação por scroll |
| 0005 - Buscar uma cidade (São Paulo) no campo de pesquisa por evento (Botão: Explorar eventos) |
| 0006 - Buscar uma cidade (São Paulo) no campo de pesquisa por evento (segunda opção de acesso via ícone fast-forward) |
| 0007 - Buscar um evento (Buffalo Tom em São Paulo) no campo de pesquisa (Botão: Explorar eventos) |
| 0008 - Buscar um evento (Buffalo Tom em São Paulo) no campo de pesquisa (segunda opção de acesso via ícone fast-forward) |
| 0009 - Buscar um local (Fabrique Club) no campo de pesquisa (Botão: Explorar eventos) |
| 0010 - Buscar um local (Cine Joia) no campo de pesquisa (segunda opção de acesso via ícone fast-forward) |
| 0011 - Buscar um evento (Buffalo Tom em São Paulo) e visualizar suas informações no campo de pesquisa (Botão: Explorar eventos) |
| 0012 - Buscar um evento (Buffalo Tom em São Paulo) no campo de pesquisa (segunda opção de acesso via ícone fast-forward) |
| 0013 - Visualizar os campos 'Sobre o evento', clicar em 'Leia mais' e 'Mostrar menos' |
| 0014 - Acessar o campo 'Localização' e abrir o endereço clicando em 'Abrir no Google Maps' |
| 0015 - Acessar o endereço no Google Maps e retornar para a página do evento (Buffalo Tom em São Paulo) |
| 0016 - Acessar o campo 'Localização', clicar em 'Ver mais' e acessar a página |
| 0017 - Acessar a página 'Ver mais' e clicar no ícone abaixo do evento para retornar à página do evento |
| 0018 - Acessar a página do evento (Buffalo Tom em São Paulo) e clicar no ícone do Google Maps ao lado do título 'Cine Joia' |
| 0019 - Acessar a página do Google Maps, depois, retornar para a página do evento (Buffalo Tom em São Paulo) |
| 0020 - Acessar a página de Política de Compra (via acesso superior da página) e verificar a navegação por scroll |
| 0021 - Acessar a página de Termos de Uso (via acesso superior da página) e verificar a navegação por scroll |
| 0022 - Acessar a página de Política de Compra (via acesso inferior da página) e verificar a navegação por scroll |
| 0023 - Acessar a página de Termos de Uso (via acesso inferior da página) e verificar a navegação por scroll |
| 0024 - Acessar a página de Meia-Entrada e verificar a navegação por scroll |
| 0025 - Acessar a página de Guia Check-in e verificar a navegação por scroll |
| 0026 - Acessar as opções 'App Fastix (Recomendado)' e 'Web' do 'Guia Check-in' |
| 0027 - Acesso simultâneo entre os campos 'Meia Entrada', 'Política de Compra', 'Termos de Uso' |
| 0028 - No campo 'Termos de Uso', acessar o tópico '2. Aceite dos Termos' e acessar o link 'Política de Compra' |
| 0029 - No campo 'Termos de Uso', acessar o tópico '2. Aceite dos Termos' e acessar o link 'Política de Meia-entrada e ingressos Acessíveis' |
| 0030 - No campo 'Termos de Uso', acessar o tópico '9. Operação, Isenções e Limitação de Responsabilidade' e acessar o link 'Política de Compra' |
| 0031 - No campo 'Termos de Uso', acessar o tópico '13. Comunicações Eletrônicas' e acessar o link 'Política de Compra' |
| 0032 - No campo 'Política de Compra', acessar o tópico '1. INTRODUÇÃO' e acessar o link 'Termos de Uso' |
| 0033 - No campo 'Política de Compra', acessar o tópico '1. INTRODUÇÃO' e acessar o link 'Política de Meia-Entrada e Ingressos Acessíveis' |
| 0034 - No campo 'Política de Compra', acessar o tópico '2. SUA CONTA E REGISTRO' e acessar o link 'Termos de Uso' |
| 0035 - Validar campo de pesquisa por evento, local e cidade utilizando termo inexistente: 'Testando Fastix' |
| 0036 - Validar campo de pesquisa por evento, local e cidade utilizando caracteres especiais |
| 0037 - Validar o campo de pesquisa por evento, local e cidade utilizando 10 vezes cada caractere especial |
| 0038 - Validar o campo de pesquisa por evento, local e cidade utilizando números |
| 0039 - Validar o campo de pesquisa por evento, local e cidade com variações de caracteres especiais |
| 0040 - Validar o campo de pesquisa por evento, local e cidade com combinação de números e caracteres especiais |
| 0041 - Navegação entre eventos no carrossel utilizando o botão de controle por ícone (Botão voltar) |
| 0042 - Navegação entre eventos no carrossel utilizando o botão de controle por ícone (Botão avançar) |
| 0043 - Navegação entre eventos no carrossel utilizando os botões de voltar e avançar (10x voltar + 10x avançar) |
| 0044 - Navegação de Stress no carrossel + acesso ao evento 'Buffalo Tom em São Paulo' |
| 0045 - Navegação de stress no carrossel, acesso ao evento e retorno à home page |
| 0046 - Validar estabilidade da busca sob stress |
| 0047 - Validar comportamento do sistema sob duplo clique e múltiplos cliques consecutivos |
| 0048 - Validar navegação utilizando back e forward do navegador |
| 0049 - Validar recuperação da aplicação após refresh durante interação |
| 0050 - Stress de refresh durante interação contínua |
| 0051 - Validar responsividade da aplicação em dispositivos mobile, tablet e desktop ultrawide |
| 0052 - Validar navegação utilizando apenas teclado |
| 0053 - Validar atualização correta dos conteúdos do carrossel |
| 0054 - Validar comportamento visual, navegação, estabilidade, integridade e stress do carrossel de eventos |
| 0055 - Validar acessos simultâneos dos links institucionais, aplicativos e redes sociais no rodapé do evento |
| 0056 - Validar abertura e navegação entre múltiplas abas externas e internas |
| 0057 - Validar a recuperação do sistema após uma busca inválida e sem resultados |
| 0058 - Input extremo: validar comportamento da busca com entradas extremas |
| 0059 - Validar tempo de resposta da aplicação |
| 0060 - Validar estabilidade da aplicação durante scroll agressivo |
| 0061 - Validar integridade do conteúdo dinâmico dos cards de eventos |
| 0062 - Validar a integridade das imagens da plataforma na página 'Explorar Eventos' |
| 0063 - Validar ausência de erros críticos no console da aplicação |
| 0064 - Validar estabilidade da aplicação durante sessão longa |
| 0065 - Validar estabilidade da aplicação após múltiplos reloads consecutivos |
| 0066 - Validar comportamento da página de explorar eventos após interrupções inesperadas |
| 0067 - Validar gerenciamento correto de foco da aplicação na página de 'Explorar eventos' |
| 0068 - Validar navegação utilizando apenas TAB na página 'Explorar Eventos' |
| 0069 - Validar filtros e navegação da página 'Explorar Eventos' |
| 0070 - Validar integridade do footer após múltiplas interações |
| **Total: 70 cenários** |

Todos os testes foram classificados considerando diferentes dimensões de teste. Essa abordagem evita tratar conceitos distintos como E2E, Regressão, Acessibilidade e Stress como se fossem categorias equivalentes.

### 📌 Dimensões de cobertura

| Dimensão | Categorias | Objetivo |
| --- | --- | --- |
| **Escopo** | E2E | Validar jornadas completas atravessando diferentes páginas e componentes |
| **Objetivo funcional** | Funcionais, Validação de Dados, Integridade | Verificar comportamentos esperados, dados apresentados e consistência das informações |
| **Qualidade da aplicação** | UI, Responsividade, Acessibilidade, Performance, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais |
| **Condição / técnica de teste** | Estresse, Compatibilidade de Navegação | Exercitar a aplicação sob condições repetitivas, intensivas ou diferentes formas de navegação |
| **Resiliência** | Monitoramento de Erros, Recuperação de Estado | Avaliar comportamento diante de erros, reloads, interrupções e operações inesperadas |
| **Finalidade de execução** | Regressão | Reexecutar cenários existentes para identificar possíveis impactos causados por alterações no sistema |

### 🧪 Cobertura funcional e E2E

#### Testes Funcionais

Validam se as funcionalidades disponíveis na aplicação apresentam o comportamento esperado.

**Exemplos:**

* **0001–0004:** acesso à página de eventos através de diferentes pontos da Home;
* **0005–0012:** pesquisa por eventos, cidades e locais;
* **0013:** expansão e recolhimento de conteúdo através de "Leia mais/Mostrar menos";
* **0014–0019:** navegação entre evento, localização e Google Maps;
* **0020–0034:** acesso e navegação pelas páginas institucionais;
* **0041–0043:** interação com os controles do carrossel;
* **0069:** filtragem e navegação.

#### Testes End-to-End (E2E)

Validam jornadas completas envolvendo múltiplos componentes ou páginas da aplicação.

**Exemplos:**

* **0001:** Home → Explorar Eventos;
* **0011:** pesquisa → identificação do evento → acesso à página do evento;
* **0015:** página do evento → Google Maps → retorno ao fluxo do evento;
* **0045:** stress do carrossel → acesso ao evento → retorno à Home → nova interação;
* **0057:** pesquisa inválida → recuperação → pesquisa válida.

> **Observação:** E2E representa o **escopo da jornada**, e não uma categoria funcional isolada. Um mesmo cenário E2E também pode ser funcional, de navegação, de robustez ou de recuperação.

### 🗺️ Testes de Navegação

Validam a movimentação do usuário entre páginas, componentes, links, histórico do navegador e diferentes pontos de acesso.

**Exemplos:**

* **0001–0004:** diferentes formas de acesso à página de eventos;
* **0014–0019:** navegação entre evento, localização e Google Maps;
* **0020–0034:** navegação entre páginas institucionais;
* **0041–0045:** navegação pelo carrossel;
* **0048:** utilização dos comandos Back e Forward do navegador;
* **0055–0056:** navegação através de links e múltiplas abas;
* **0067–0068:** navegação utilizando foco e teclado.

### 🖥️ Testes de Interface (UI)

Avaliam a presença, interação e comportamento dos principais componentes da interface.

**Exemplos:**

* **0013:** expansão/recolhimento de conteúdo;
* **0026:** validação das opções "Web" e "App FasTix";
* **0041–0043:** botões de navegação do carrossel;
* **0051:** componentes da interface em diferentes resoluções;
* **0061:** cards de eventos;
* **0062:** imagens;
* **0070:** integridade dos elementos do footer.

### 📐 Testes de Responsividade

Avaliam o comportamento da aplicação em diferentes dimensões de viewport.

O cenário **0051** realiza uma validação específica utilizando:

* **390 × 844 — Mobile**
* **768 × 1024 — Tablet**
* **2560 × 1440 — Desktop Ultrawide**

Durante a execução são avaliados elementos como: visibilidade de eventos, carrossel, navegação, overflow, componentes da interface, footer, acesso à página do evento, refresh, e ausência de mensagens de erro.

### ♿ Testes de Acessibilidade

Avaliam a capacidade de interação com a aplicação utilizando mecanismos alternativos ao mouse.

**Exemplos:**

* **0052:** navegação utilizando teclado;
* **0067:** gerenciamento e comportamento do foco;
* **0068:** navegação utilizando exclusivamente TAB.

Os cenários verificam elementos como foco, sequência de navegação, utilização de TAB, Shift+TAB, Enter, Space, e interação com elementos da interface sem depender exclusivamente do mouse.

### ⚡ Testes de Performance

Avaliam o comportamento da aplicação em relação ao tempo de resposta durante operações específicas.

**Exemplo:**

* **0059:** validação relacionada ao tempo de resposta da aplicação.

> A suíte possui uma cobertura de performance **pontual**, não caracterizando uma estratégia completa de performance/load testing. Para um projeto futuro, poderiam ser adicionados testes específicos de carga, volume e throughput.

### 🔄 Testes de Estabilidade

Avaliam se a aplicação permanece funcional após repetição de operações, múltiplas interações, reloads ou períodos prolongados de utilização.

**Exemplos:**

* **0046:** estabilidade durante operações repetitivas;
* **0049:** recuperação após refresh;
* **0050:** múltiplos refreshes;
* **0054:** estabilidade do carrossel;
* **0060:** scroll agressivo;
* **0064:** sessão prolongada;
* **0065:** múltiplos reloads;
* **0066:** recuperação após interrupção inesperada.

### 🔥 Testes de Estresse (Stress Testing)

Submetem determinados componentes a operações repetitivas ou intensivas para verificar seu comportamento sob condições mais agressivas.

**Exemplos:**

* **0044:** múltiplos avanços e retornos do carrossel;
* **0045:** stress do carrossel associado a uma jornada E2E;
* **0046:** operações repetitivas;
* **0047:** múltiplas interações/cliques;
* **0050:** múltiplos refreshes;
* **0054:** operações repetitivas sobre o carrossel;
* **0058:** entradas extremas.

> ⚠️ **Importante:**  Esses cenários caracterizam stress/robustez de componentes da aplicação. Eles não devem ser apresentados como um teste formal de **load/performance**, pois não simulam múltiplos usuários ou carga concorrente de infraestrutura.

### 🛡️ Testes de Robustez

Avaliam a capacidade da aplicação de lidar com entradas inesperadas, inválidas, extremas ou sequências incomuns de interação.

**Exemplos:**

* **0035:** pesquisa por termo inexistente;
* **0036:** caracteres especiais;
* **0037:** caracteres especiais repetidos;
* **0038:** entradas numéricas;
* **0039–0040:** combinações de entradas para validação de comportamento;
* **0046–0047:** operações repetitivas;
* **0057:** recuperação após pesquisa inválida;
* **0058:** entrada extrema;
* **0066:** interrupção inesperada.

### 🔎 Testes de Validação de Dados

Verificam se os dados inseridos, pesquisados, retornados ou apresentados pela aplicação são tratados corretamente.

**Exemplos:**

* **0005–0012:** pesquisa por cidade, evento e local;
* **0035:** pesquisa sem resultado;
* **0036–0040:** caracteres especiais, números e combinações;
* **0057:** recuperação entre pesquisa inválida e válida;
* **0058:** entrada extrema;
* **0061:** validação dos dados exibidos nos cards;
* **0069:** filtros e resultados.

### 🔑 Testes de Integridade

Avaliam se os dados e componentes permanecem consistentes após diferentes operações.

**Exemplos:**

* **0053:** validação da alteração de estado do carrossel;
* **0054:** integridade do carrossel após múltiplas operações;
* **0061:** consistência dos dados dos cards;
* **0062:** integridade das imagens;
* **0070:** integridade do footer após múltiplas interações.

### 🌐 Testes de Compatibilidade de Navegação

Verificam se diferentes mecanismos de navegação continuam funcionando corretamente em diferentes contextos de interação.

**Exemplos:**

* **0048:** Back/Forward do navegador;
* **0051:** navegação em diferentes resoluções;
* **0052:** navegação por teclado;
* **0055:** links institucionais, aplicativos e redes sociais;
* **0056:** utilização de múltiplas abas;
* **0067–0068:** navegação por foco e teclado.

> ⚠️ **Importante:** Essa categoria representa **compatibilidade entre diferentes mecanismos de navegação**, e não compatibilidade entre diferentes browsers. A suíte atual não demonstra, pelos cenários analisados, uma estratégia completa de cross-browser testing.

### 🚨 Testes de Monitoramento de Erros

Monitoram sinais de falhas durante a execução e verificam a ausência de mensagens de erro conhecidas.

**Exemplos:**

* **0039:** ausência de `500` e `Error`;
* **0040:** ausência de `500`, `Error` e `Exception`;
* **0053–0054:** ausência de mensagens como `Application error`, `Internal Server Error` e `Unexpected error`;
* **0063:** monitoramento de erros no console.

### 🎨 Testes de Integridade Visual

Avaliam se elementos visuais permanecem íntegros após diferentes interações.

**Exemplos:**

* **0051:** elementos visuais em diferentes resoluções;
* **0054:** comportamento visual do carrossel após múltiplas operações;
* **0062:** validação da integridade das imagens;
* **0070:** integridade visual do footer.

### 🔃 Recuperação e Estado da Aplicação

Nos cenários analisados, existem testes relacionados à manutenção e recuperação do estado da aplicação após determinadas operações.

**Exemplos:**

* **0049:** recuperação após refresh;
* **0050:** comportamento após múltiplos refreshes;
* **0057:** recuperação após uma pesquisa inválida;
* **0065:** comportamento após múltiplos reloads;
* **0066:** recuperação após interrupção inesperada.

> **Precisão técnica:** esses cenários são melhor descritos como **testes de recuperação/resiliência e gerenciamento de estado**. Eles não comprovam, isoladamente, persistência de dados de negócio em banco, sessão ou armazenamento local.

### 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os 70 cenários podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após: novas funcionalidades; alterações de UI; alterações de navegação; correções de bugs; alterações no carrossel; alterações de responsividade; alterações de componentes; mudanças estruturais nas páginas.

A ideia é verificar se uma alteração introduzida no sistema provocou efeitos colaterais em comportamentos que anteriormente funcionavam.

**Exemplo de estratégia:**

```text
Alteração no sistema
        ↓
Execução dos testes relacionados
        ↓
Execução da suíte de regressão
        ↓
Comparação dos resultados
        ↓
Identificação de regressões
        ↓
RCA / Bug Report
```

### 📊 Matriz de cobertura da suíte

| Dimensão | Cenários principais | Cobertura |
| --- | --- | --- |
| **E2E** | 0001, 0011, 0015, 0045, 0057 | 🟢 |
| **Funcional** | 0001–0045, 0069 | 🟢 |
| **Regressão** | 0001–0070 | 🟢 |
| **Navegação** | 0001–0004, 0014–0034, 0041–0048, 0055–0056 | 🟢 |
| **UI** | 0013, 0026, 0041–0043, 0051, 0061–0062, 0070 | 🟢 |
| **Responsividade** | 0051 | 🟢 |
| **Acessibilidade** | 0052, 0067–0068 | 🟢 |
| **Performance** | 0059 | 🟡 |
| **Estabilidade** | 0046, 0049–0050, 0054, 0060, 0064–0066 | 🟢 |
| **Estresse** | 0044–0047, 0050, 0054, 0058 | 🟢 |
| **Robustez** | 0035–0040, 0046–0050, 0057–0058, 0060, 0064–0066 | 🟢 |
| **Validação de Dados** | 0005–0012, 0035–0040, 0057–0058, 0061, 0069 | 🟢 |
| **Integridade** | 0053–0054, 0061–0062, 0070 | 🟢 |
| **Compatibilidade de Navegação** | 0048, 0051–0052, 0055–0056, 0067–0068 | 🟢 |
| **Monitoramento de Erros** | 0039–0040, 0053–0054, 0063 | 🟢 |
| **Integridade Visual** | 0051, 0054, 0062, 0070 | 🟢 |
| **Recuperação/Estado** | 0049–0050, 0057, 0065–0066 | 🟢 |

**Legenda:**

| Indicador | Classificação |
| --- | --- |
| 🟢 | Cobertura claramente demonstrada pelos cenários analisados |
| 🟡 | Cobertura presente, porém pontual e passível de expansão |

---

## 🙋 Feature Suporte e Ajuda

| Feature |
| --- |
| Feature_Suporte e Ajuda |
| 0001 - Acessar a página de Suporte e Ajuda pela página principal |
| 0002 - Acessar a página de Suporte e Ajuda e navegar até o footer |
| 0003 - Acessar o contato da Fastix via Instagram |
| 0004 - Acessar o contato da Fastix via Email (5 cliques consecutivos) |
| 0005 - Acessar o contato da Fastix via WhatsApp |
| 0006 - Preencher o formulário completo de contato |
| 0007 - Impedir envio da mensagem quando o campo "NOME" não é preenchido |
| 0008 - Impedir envio da mensagem quando o campo "EMAIL" não é preenchido |
| 0009 - Impedir envio da mensagem quando o campo "MENSAGEM" não é preenchido |
| 0010 - Impedir envio da mensagem quando nenhum campo é preenchido |
| 0011 - E-mail sem o @ — bloqueio do envio |
| 0012 - Aceitar e-mail com @, mas manter envio bloqueado sem validação humana |
| 0013 - Validar preenchimento de todos os campos com caracteres especiais |
| 0014 - Validar preenchimento individual dos campos com 10x cada caractere especial |
| 0015 - Clicar no card "Como solicitar reembolso?" |
| 0016 - Clicar nos cards "Como solicitar reembolso?" e "O que preciso levar no dia do evento?" |
| 0017 - Clicar nos cards reembolso, evento e "Como vender ingressos pela FasTix?" |
| 0018 - Clicar nos cards reembolso, evento, venda e "Onde compro ingresso sem taxa?" |
| 0019 - Clicar e acessar o botão iOS |
| 0020 - Clicar e acessar o botão Android |
| 0021 - Clicar e acessar o Guia Check-in |
| 0022 - Clicar e acessar os Termos e Condições de Uso |
| 0023 - Clicar e acessar a Política de Compra |
| 0024 - Clicar e acessar a Meia Entrada |
| 0025 - Clicar no ícone do LinkedIn na Central de Ajuda |
| 0026 - Clicar no ícone do Instagram na Central de Ajuda |
| 0027 - Clicar no ícone do X na Central de Ajuda |
| 0028 - Clicar no ícone de Email (Contato) na Central de Ajuda |
| 0029 - Clicar no link WebSolutionsFL na Central de Ajuda |
| 0030 - Navegação por teclado até o botão Suporte e Ajuda |
| 0031 - Validar acessibilidade e navegação via TAB em todos os campos do formulário |
| 0032 - Validação visual do foco na página de Suporte e Ajuda |
| 0033 - Garantir acesso e funcionalidade dos elementos do footer via navegação por TAB |
| 0034 - Persistência do formulário após scroll (stress test 10x) |
| 0035 - Validação de campos obrigatórios com espaços vazios |
| 0036 - Validação do limite máximo do campo Nome |
| 0037 - Validação do limite máximo do campo Mensagem (estabilidade) |
| 0038 - Validar limite máximo do campo Código do Pedido |
| 0039 - Validação do limite máximo do campo Email (estabilidade) |
| 0040 - Colagem de conteúdo no campo Mensagem do formulário |
| 0041 - Atualização (reload) da página durante preenchimento do formulário |
| 0042 - Validar estabilidade da aplicação durante navegação repetitiva (3x) |
| 0043 - Validar estabilidade sob navegação repetitiva com liberação de memória (20x) |
| 0044 - Validar estabilidade durante navegações repetitivas com monitoramento de console/rede (20x) |
| 0045 - Detecção de memory leak visual no fluxo de suporte (20x) |
| 0046 - Validar performance e estabilidade da navegação para a página de suporte (10 ciclos) |
| 0047 - Responsividade da página de suporte (Desktop, Laptop, Tablet, Mobile) |
| 0048 - Clique múltiplo nos botões de contato Instagram, Email e WhatsApp (10x) |
| 0049 - Estabilidade visual durante scroll contínuo (20x) |
| 0050 - Validar acessibilidade e integridade de todos os links da página |
| 0051 - Navegação para páginas externas com verificação de status HTTP |
| 0052 - Validar retorno correto ao utilizar o botão voltar do navegador (múltiplas páginas) |
| 0053 - Validar navegação e retorno correto das páginas do menu superior |
| 0054 - Validar navegação e retorno via botões Entrar, Criar Conta e Voltar |
| 0055 - Fluxo completo de navegação e retorno (navegador + menu + Entrar/Criar Conta) |
| 0056 - Validação de estabilidade após múltiplos acessos (5x) |
| 0057 - Validação de estabilidade após múltiplos acessos ao footer (5x, com liberação de memória) |
| 0058 - Validar stress de clique nos cards da página (5 loops × 4 cards) |
| 0059 - Validação visual do footer da página |
| 0060 - Validação visual do footer com responsividade (Desktop e Mobile) |
| 0061 - Observabilidade do console e falhas de rede |
| 0062 - Observabilidade realista de console, rede e UI |
| 0063 - Validar performance da página via Navigation Timing API |
| 0064 - Validação de Lazy loading do footer |
| 0065 - Validar estabilidade do formulário por execuções repetidas (Anti-Flaky, 3x) |
| 0066 - Teste anti-flaky do formulário com métricas de estabilidade e retries (5x) |
| 0067 - Validação de fallback sem imagens na página |
| 0068 - Validação de eventos no DataLayer |
| 0069 - Validação de contrato de eventos no dataLayer (schema e sequência) |
| 0070 - Validação de SEO title e meta description |
| 0071 - Validar SEO da página com keywords obrigatórias e opcionais |
| 0072 - Validação de OG tags |
| 0073 - Validar consistência das OG tags entre browser e crawler headless |
| 0074 - Garantir acessibilidade básica dos campos do formulário (label ou ARIA) |
| 0075 - Validar exposição de scripts e possíveis leaks de dados sensíveis no HTML |
| **Total: 75 cenários** |

Assim como na Feature Explorar Eventos, todos os testes foram classificados considerando diferentes dimensões de teste, evitando tratar conceitos distintos (E2E, Regressão, Acessibilidade, Stress, SEO, Segurança) como categorias equivalentes.

### 📌 Dimensões de cobertura

| Dimensão | Categorias | Objetivo |
| --- | --- | --- |
| **Escopo** | E2E | Validar jornadas completas atravessando múltiplas páginas |
| **Objetivo funcional** | Funcionais, Validação de Dados, Integridade | Verificar comportamentos esperados, dados apresentados e consistência das informações |
| **Qualidade da aplicação** | UI, Responsividade, Acessibilidade, Performance, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais |
| **Condição / técnica de teste** | Estresse, Compatibilidade de Navegação | Exercitar a aplicação sob condições repetitivas, intensivas ou diferentes formas de navegação |
| **Resiliência** | Monitoramento de Erros, Recuperação de Estado | Avaliar comportamento diante de erros, reloads e interrupções |
| **Observabilidade e Analytics (dataLayer)** | Contrato de eventos | Verificar se dados de rastreamento seguem um schema esperado — dimensão específica desta feature, ausente na Explorar Eventos |
| **SEO e Metadados** | Title, meta description, keywords, OG tags | Verificar se os metadados da página seguem o esperado — dimensão específica desta feature |
| **Segurança** | Exposição de dados sensíveis | Verificar ausência de vazamento de credenciais, tokens ou chaves no HTML/scripts renderizados — dimensão específica desta feature |
| **Finalidade de execução** | Regressão | Reexecutar cenários existentes para identificar impactos causados por alterações no sistema |

### 🧪 Cobertura funcional e E2E

#### Testes Funcionais

Validam se as funcionalidades disponíveis na página apresentam o comportamento esperado.

**Exemplos:**

* **0001–0006:** acesso à página e aos canais de contato (Instagram, Email, WhatsApp), preenchimento completo do formulário;
* **0015–0018:** interação com os cards de ajuda ("Como solicitar reembolso?", "O que levar no dia do evento?", etc.);
* **0019–0024:** acesso a páginas institucionais (iOS, Android, Guia Check-in, Termos, Política de Compra, Meia Entrada);
* **0025–0029:** ícones e links do footer (LinkedIn, Instagram, X, Email, WebSolutionsFL);
* **0040:** colagem de conteúdo no campo Mensagem.

#### Testes End-to-End (E2E)

Validam jornadas completas envolvendo múltiplos componentes ou páginas.

**Exemplos:**

* **0021–0024:** Suporte → página institucional específica;
* **0052–0055:** navegação para páginas externas/internas → retorno à página de Suporte, incluindo fluxos de Entrar e Criar Conta;
* **0073:** comparação entre a renderização vista pelo browser e a servida a um crawler headless — atravessa camada de frontend e de servidor.

> ⚠️ **Importante observação:** Assim como na Feature Explorar Eventos, E2E representa o **Escopo da jornada**, não uma categoria funcional isolada.

### 🗺️ Testes de Navegação

**Exemplos:**

* **0001–0005:** diferentes formas de acesso à página e aos canais de contato;
* **0015–0029:** navegação por cards de ajuda, páginas institucionais e ícones do footer;
* **0052–0055:** botão voltar do navegador, menu superior, e botões Entrar/Criar Conta.

### 🖥️ Testes de Interface (UI)

**Exemplos:**

* **0015–0018:** overlays dos cards de ajuda;
* **0025–0029:** ícones de redes sociais e contato no footer;
* **0032:** indicação visual de foco;
* **0059–0060:** integridade visual do footer.

### 📐 Testes de Responsividade

**Exemplos:**

* **0047:** validação em 4 resoluções — Desktop (1920×1080), Laptop (1366×768), Tablet (768×1024), Mobile (375×667);
* **0060:** footer especificamente validado em Desktop (1280×720) e Mobile (375×812).

### ♿ Testes de Acessibilidade

**Exemplos:**

* **0030:** navegação via TAB até o link "Suporte e Ajuda";
* **0031:** navegação via TAB por todos os campos do formulário (fluxo único de até 80 tabs);
* **0032:** validação visual do indicador de foco (outline, box-shadow, ring);
* **0033:** acesso ao footer via TAB (até 120 tabs), validando que links possuem `href` funcional;
* **0074:** presença de `label`/`aria-label` nos campos do formulário.

### ⚡ Testes de Performance

**Exemplos:**

* **0046:** tempo de navegação por 10 ciclos, com limite de 3000ms por ciclo;
* **0063:** métricas via Navigation Timing API (`domContentLoaded`, `TTFB`, `responseTime`), com thresholds definidos;
* **0064:** comportamento de lazy loading do footer.

> ⚠️ **Importante:** Assim como na feature de referência, a cobertura de performance é **pontual**, focada em tempo de navegação e carregamento — não caracteriza uma estratégia completa de load/stress de infraestrutura.

### 🔄 Testes de Estabilidade

**Exemplos:**

* **0034:** persistência do formulário após 10 ciclos de scroll;
* **0041:** recuperação após reload duplo durante preenchimento;
* **0042–0043:** navegação repetitiva (3x e 20x);
* **0049:** scroll contínuo (20 ciclos);
* **0056–0057:** múltiplos acessos consecutivos (5x), incluindo variante com footer e liberação forçada de memória;
* **0065–0066:** testes anti-flaky do formulário, incluindo cálculo de taxa de flakiness (`flakinessRate`) com limite de 10%.

### 🔥 Testes de Estresse (Stress Testing)

**Exemplos:**

* **0004:** 5 cliques consecutivos no link de e-mail;
* **0014:** preenchimento com 10 repetições de cada caractere especial, em loop;
* **0034:** 10 ciclos de scroll com validação de persistência;
* **0043–0045:** 20 ciclos de navegação, com monitoramento de erros e detecção de memory leak visual;
* **0048:** 10 ciclos de clique simulado nos botões de contato (com neutralização de `href` para evitar navegação real);
* **0058:** 5 loops × 4 cards = 20 interações de clique.

> ⚠️ **Importante:** Assim como na Explorar Eventos, esses cenários caracterizam stress/robustez de componentes da página — não simulam carga concorrente de múltiplos usuários nem substituem uma ferramenta dedicada de load testing.

### 🛡️ Testes de Robustez

**Exemplos:**

* **0007–0010:** bloqueio de envio com campos individualmente ou totalmente vazios;
* **0011–0012:** e-mail malformado (sem `@`) e e-mail válido sem validação humana (captcha);
* **0013–0014:** conjunto amplo de caracteres especiais (incluindo símbolos matemáticos, moedas, acentuação) em todos os campos;
* **0035:** campos preenchidos apenas com espaços em branco;
* **0036–0039:** limites máximos de caracteres por campo (Nome, Mensagem, Código do Pedido, Email), validando truncamento real via manipulação do `value` nativo do input;
* **0040:** colagem de conteúdo extenso;
* **0067:** comportamento da página com todas as imagens bloqueadas (fallback).

### 🔎 Testes de Validação de Dados

**Exemplos:**

* **0007–0014:** validação de campos obrigatórios e formato de e-mail;
* **0035–0039:** limites de caracteres e valor real armazenado em cada campo;
* **0050:** integridade dos `href` de 10 links distintos (Instagram, Email, WhatsApp, iOS, Android, LinkedIn, X/Twitter, WebSolutionsFL);
* **0069–0070:** schema de eventos do dataLayer e presença de metadados de SEO.

### 🔑 Testes de Integridade

**Exemplos:**

* **0045:** ausência de crescimento anormal do DOM entre ciclos (indício de memory leak);
* **0049:** variação controlada de elementos de UI durante scroll contínuo;
* **0050:** ausência de links vazios ou quebrados;
* **0059–0060:** integridade estrutural do footer (altura, largura, itens renderizados);
* **0064:** presença de links no footer após o carregamento progressivo (lazy loading).

### 🌐 Testes de Compatibilidade de Navegação

**Exemplos:**

* **0052:** botão voltar do navegador, testado contra 4 páginas institucionais distintas;
* **0053–0054:** navegação e retorno via menu superior e via botões Entrar/Criar Conta;
* **0055:** combinação de todos os mecanismos de navegação (voltar do navegador + menu + Entrar/Criar Conta) em um único fluxo.

> ⚠️ **Importante:** Assim como na feature de referência, essa categoria trata de **diferentes mecanismos de navegação** dentro do mesmo navegador não caracteriza uma estratégia de teste cross-browser.

### 🚨 Testes de Monitoramento de Erros

**Exemplos:**

* **0044:** captura de erros de console, `pageerror` e falhas de rede durante 20 ciclos, com filtros para ruído conhecido (Cloudflare challenge, erro pré-existente de SSR `React #418`) e limite de 5 erros críticos;
* **0056–0057:** ausência de textos como "404", "500", "Application error" após múltiplos acessos;
* **0061–0062:** monitoramento dedicado de console e falhas de rede (`requestfailed`) em um fluxo único.

### 🎨 Testes de Integridade Visual

**Exemplos:**

* **0032:** indicador visual de foco;
* **0045:** estabilidade do número de elementos de UI entre ciclos;
* **0049:** variação de botões/inputs durante scroll contínuo;
* **0059–0060:** estrutura visual do footer, incluindo responsividade.

### 🔃 Recuperação e Estado da Aplicação

**Exemplos:**

* **0041:** recuperação do formulário após dois reloads consecutivos;
* **0065–0066:** testes anti-flaky com retry automático (até 2 tentativas por execução) e cálculo formal de taxa de flakiness.

> ⚠️ **Importante:** **Precisão técnica:** assim como destacado na feature de referência, esses cenários validam **recuperação/resiliência da interface**, não persistência de dados de negócio em backend o formulário nunca é de fato submetido com sucesso em nenhum cenário desta suíte (o botão permanece desabilitado sem validação humana, cenário 0012).

### 📡 Observabilidade e Analytics (dataLayer)

Avaliam se eventos de rastreamento e metadados da página seguem um contrato/schema esperado — categoria não presente na Feature Explorar Eventos.

**Exemplos:**

* **0068:** presença de eventos no `dataLayer` relacionados a "Suporte"/"contact" após o clique;
* **0069:** validação de **schema completo** do evento `gtm.linkClick` (campos obrigatórios `gtm.elementText`, `gtm.elementUrl`, `gtm.triggers`), sequência esperada de eventos (`gtm.js` → `gtm.dom` → `gtm.load` → `gtm.linkClick` → `gtm.historyChange`), e ausência de eventos duplicados.

### 🏷️ Testes de SEO e Metadados

**Exemplos:**

* **0070:** presença e tamanho de `title` e `meta description` (limite de 160 caracteres);
* **0071:** presença de keywords obrigatórias (`fastix`) e opcionais (`ingressos`, `suporte`, `ajuda`), com cálculo de score percentual;
* **0072:** presença e tamanho mínimo de tags Open Graph (`og:title`, `og:description`, `og:url`);
* **0073:** **consistência entre o HTML servido ao navegador e o HTML servido a um crawler** (simulado com User-Agent do Googlebot) — verifica se a aplicação faz pré-renderização correta de metadados para SEO.

### 🔒 Testes de Segurança

**Exemplo:**

* **0075:** varredura do HTML renderizado (na Home e na página de Suporte) em busca de padrões sensíveis (`api_key`, `secret`, `token`, `password`, `bearer`, `jwt`, entre outros) e de scripts inline suspeitos.

### 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os 75 cenários podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após: alterações no formulário de contato ou em suas validações; alterações nos cards da Central de Ajuda; alterações no footer ou em seus links; alterações de navegação entre Suporte e outras páginas do site; mudanças em tags de SEO/Open Graph; mudanças na configuração de eventos de Analytics (dataLayer); alterações estruturais na página que possam impactar acessibilidade.

**Exemplo de estratégia:**

```text
Alteração no sistema
        ↓
Execução dos testes relacionados
        ↓
Execução da suíte de regressão
        ↓
Comparação dos resultados
        ↓
Identificação de regressões
        ↓
RCA / Bug Report
```

### 📊 Matriz de cobertura da suíte

| Dimensão | Cenários principais | Cobertura |
| --- | --- | --- |
| **E2E** | 0021–0024, 0052–0055, 0073 | 🟢 |
| **Funcional** | 0001–0029, 0040 | 🟢 |
| **Regressão** | 0001–0075 | 🟢 |
| **Navegação** | 0001–0029, 0052–0055 | 🟢 |
| **UI** | 0015–0018, 0025–0029, 0032, 0059–0060 | 🟢 |
| **Responsividade** | 0047, 0060 | 🟢 |
| **Acessibilidade** | 0030–0033, 0074 | 🟢 |
| **Performance** | 0046, 0063, 0064 | 🟡 |
| **Estabilidade** | 0034, 0037, 0041–0045, 0049, 0056–0057, 0065–0066 | 🟢 |
| **Estresse** | 0004, 0014, 0034, 0043–0045, 0048, 0058 | 🟢 |
| **Robustez** | 0007–0014, 0035–0040, 0067 | 🟢 |
| **Validação de Dados** | 0007–0014, 0035–0039, 0050, 0069–0070 | 🟢 |
| **Integridade** | 0045, 0049–0050, 0059–0060, 0064 | 🟢 |
| **Compatibilidade de Navegação** | 0052–0055 | 🟢 |
| **Monitoramento de Erros** | 0044, 0056–0057, 0061–0062 | 🟢 |
| **Integridade Visual** | 0032, 0045, 0049, 0059–0060 | 🟢 |
| **Recuperação/Estado** | 0041, 0065–0066 | 🟢 |
| **Observabilidade e Analytics (dataLayer)** | 0068–0069 | 🟢 |
| **SEO e Metadados** | 0070–0073 | 🟢 |
| **Segurança** | 0075 | 🟡 |

**Legenda:**

| Indicador | Classificação |
| --- | --- |
| 🟢 | Cobertura claramente demonstrada pelos cenários analisados |
| 🟡 | Cobertura presente, porém pontual e passível de expansão |

---

# 🏠 Feature Tela Inicial

| Feature                                                                                          |
| ------------------------------------------------------------------------------------------------ |
| Feature_Tela Inicial                                                                             |
| 0001 - Acessar "Explorar Eventos"                                                                |
| 0002 - Acessar "Publicar Eventos"                                                                |
| 0003 - Acessar "Suporte e Ajuda"                                                                 |
| 0004 - Acessar o botão de idioma                                                                 |
| 0005 - Acessar o botão de idioma e clicar na opção Português                                     |
| 0006 - Acessar o botão de idioma e clicar na opção Español                                       |
| 0007 - Acessar o botão de idioma e clicar na opção English                                       |
| 0008 - Acessar o botão de "Entrar"                                                               |
| 0009 - Acessar o botão de "Criar Conta"                                                          |
| 0010 - Acessar o botão de busca (Search / Command Palette ⌘K)                                    |
| 0011 - Acessar o botão "Explorar Eventos"                                                        |
| 0012 - Acessar o botão "Pesquisar evento, local..."                                              |
| 0013 - Navegação no carrossel utilizando o botão de controle por ícone                           |
| 0014 - Navegação sequencial no carrossel com múltiplos cliques (10x)                             |
| 0015 - Navegação no carrossel com seleção de evento (THE WHITE BUFFALO em SÃO PAULO)             |
| 0016 - Navegação sequencial no carrossel (esquerda 10x + direita 10x)                            |
| 0017 - Clicar no botão "Criar Conta"                                                             |
| 0018 - Clicar no botão "Publicar evento"                                                         |
| 0019 - Clicar em "Criar Conta" próximo ao título "Vendendo tickets online? Nós podemos ajudar"   |
| 0020 - Clicar no botão iOS no footer                                                             |
| 0021 - Clicar no botão Android no footer                                                         |
| 0022 - Clicar no Guia Check-in no footer                                                         |
| 0023 - Clicar em Termos e Condições de Uso no footer                                             |
| 0024 - Clicar em Política de Compra no footer                                                    |
| 0025 - Clicar em Meia Entrada no footer                                                          |
| 0026 - Clicar no ícone do LinkedIn no footer                                                     |
| 0027 - Clicar no ícone do Instagram no footer                                                    |
| 0028 - Clicar no ícone do Twitter no footer (ícone desatualizado)                                |
| 0029 - Clicar no ícone de Email no footer                                                        |
| 0030 - Clicar no link WebSolutionsFL no footer                                                   |
| 0031 - Validar que todos os links principais retornam status 200 (Broken Links)                  |
| 0032 - Validar abertura correta de links externos sem navegação real (Instagram)                 |
| 0033 - Validar alteração completa de idioma para English                                         |
| 0034 - Validar alteração de idioma para English e comportamento após atualização da página       |
| 0035 - Validar alteração completa de idioma para Español                                         |
| 0036 - Validar acessibilidade e navegação via TAB nos elementos interativos e no footer          |
| 0037 - Validar estrutura visual, landmarks e atributos principais da Home                        |
| 0038 - Validar contraste visual mínimo dos componentes críticos                                  |
| 0039 - Validar foco visível ao navegar via teclado                                               |
| 0040 - Validar abertura do menu de idioma via ENTER                                              |
| 0041 - Diagnosticar comportamento do atalho CTRL + K                                             |
| 0042 - Validar comportamento funcional do atalho CTRL + K                                        |
| 0043 - Validar estrutura principal, navegação e responsividade da Home (Desktop/Tablet/Mobile)   |
| 0044 - Validar que o header não sofre quebra visual em diferentes resoluções                     |
| 0045 - Validar carregamento inicial da Home em menos de 3 segundos                               |
| 0046 - Validar estabilidade do carrossel após 100 navegações consecutivas (esquerda + direita)   |
| 0047 - Validar carregamento dinâmico de eventos durante scroll (Lazy Loading)                    |
| 0048 - Validar estabilidade do botão "Explorar Eventos" em execuções repetidas (10x, anti-flaky) |
| 0049 - Validar presença de título da página (SEO)                                                |
| 0050 - Validar presença de meta description (SEO)                                                |
| 0051 - Validar presença de atributo alt em imagens                                               |
| 0052 - Validar ausência de informações sensíveis no frontend                                     |
| 0053 - Validar ausência de informações sensíveis no frontend (variante com padrões nomeados)     |
| 0054 - Validar ausência de erro interno exposto e exibição de mensagem amigável                  |
| 0055 - Validar padronização visual dos botões CTA                                                |
| 0056 - Validar consistência dos links do footer                                                  |
| 0057 - Pesquisar evento existente                                                                |
| 0058 - Pesquisar evento inexistente                                                              |
| 0059 - Pesquisar utilizando caracteres especiais                                                 |
| 0060 - Validar debounce da busca                                                                 |
| 0061 - Validar ausência de erros no console durante navegação                                    |
| 0062 - Validar resposta da API de eventos                                                        |
| 0063 - Validar comportamento da interface sem carregamento de imagens                            |
| 0064 - Validar disparo de evento de Analytics ao clicar em "Explorar Eventos"                    |
| **Total: 64 cenários**                                                                           |

> ⚠️ **Importante:** Todos os testes foram classificados considerando diferentes dimensões de teste. Essa abordagem evita tratar conceitos distintos como E2E, Regressão, Acessibilidade, Estresse, Segurança e SEO como se fossem categorias equivalentes.

## 📌 Dimensões de cobertura

| Dimensão                        | Categorias                                                                                  | Objetivo                                                                                          |
| ------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Escopo**                      | E2E                                                                                         | Validar jornadas completas atravessando múltiplos componentes ou páginas a partir da Home         |
| **Objetivo funcional**          | Funcionais, Validação de Dados, Integridade                                                 | Verificar comportamentos esperados, dados apresentados e consistência das informações             |
| **Qualidade da aplicação**      | UI, Responsividade, Acessibilidade, Performance, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais                                   |
| **Condição / técnica de teste** | Estresse, Compatibilidade de Navegação                                                      | Exercitar a aplicação sob condições repetitivas, intensivas ou diferentes mecanismos de navegação |
| **Resiliência**                 | Monitoramento de Erros, Recuperação de Estado                                               | Avaliar o comportamento diante de erros, reloads, interrupções e mudanças de estado               |
| **Observabilidade e Contrato**  | Analytics (dataLayer), SEO / Metadados                                                      | Verificar eventos de rastreamento e metadados relevantes da página                                |
| **Segurança**                   | Exposição de dados sensíveis, mensagens de erro                                             | Verificar ausência de informações sensíveis e de mensagens técnicas indevidamente expostas        |
| **Finalidade de execução**      | Regressão                                                                                   | Reexecutar cenários existentes para identificar impactos causados por alterações no sistema       |

## 🧪 Cobertura funcional e E2E

### Testes Funcionais

Validam se as funcionalidades disponíveis na Home apresentam o comportamento esperado.

**Exemplos:**

* **0001–0012:** acesso aos principais pontos de entrada da Home;
* **0013–0016:** interação e navegação no carrossel;
* **0017–0030:** interação com CTAs, aplicativos, páginas institucionais, redes sociais e links do footer;
* **0033–0035:** alteração do idioma da aplicação;
* **0040–0042:** interação com o seletor de idioma e Command Palette;
* **0057–0058:** pesquisa de evento existente e inexistente;
* **0059:** pesquisa utilizando caracteres especiais;
* **0060:** comportamento de debounce da busca.

### Testes End-to-End (E2E)

Validam jornadas completas envolvendo diferentes componentes, páginas ou camadas da aplicação.

**Exemplos:**

* **0015:** carrossel → seleção do evento → navegação para a página correspondente;
* **0020–0025:** Home → acesso às páginas institucionais pelo footer;
* **0057:** Home → busca → identificação do evento → acesso ao evento;
* **0062:** Home → carregamento de eventos → comunicação com a API → disponibilização dos dados na interface;
* **0064:** clique em "Explorar Eventos" → navegação → registro do evento de Analytics.
* 
> ⚠️ **Importante observação:** E2E representa o **escopo da jornada**, e não uma categoria funcional isolada. Um mesmo cenário pode ser simultaneamente E2E, funcional, de navegação, de integridade ou de observabilidade.

## 🗺️ Testes de Navegação

Validam a movimentação do usuário entre páginas, componentes, links e diferentes pontos de acesso da aplicação.

**Exemplos:**

* **0001–0012:** diferentes pontos de acesso a partir da Home;
* **0013–0016:** navegação entre eventos no carrossel;
* **0017–0030:** navegação por CTAs e links do footer;
* **0033–0035:** navegação decorrente da alteração de idioma;
* **0057–0058:** navegação decorrente da pesquisa de eventos.

> **Observação:** os cenários desta Feature não contemplam explicitamente a utilização dos comandos Back/Forward, histórico do navegador ou retorno entre múltiplas páginas utilizando o histórico. Essa lacuna é tratada na dimensão Compatibilidade de Navegação.

## 🖥️ Testes de Interface (UI)

Avaliam a presença, interação e comportamento dos principais componentes visuais da interface.

**Exemplos:**

* **0013–0016:** interação com os controles do carrossel;
* **0020–0030:** botões, ícones e links do footer;
* **0033–0035:** componentes relacionados ao seletor de idioma;
* **0041–0042:** Command Palette;
* **0055:** padronização visual dos botões CTA;
* **0056:** consistência dos links do footer;
* **0063:** comportamento da interface quando as imagens não são carregadas.

## 📐 Testes de Responsividade

Avaliam o comportamento da Home em diferentes dimensões de viewport.

**Exemplos:**

* **0043:** validação da estrutura principal, navegação e comportamento responsivo da Home em Desktop, Tablet e Mobile;
* **0044:** validação específica da integridade visual do header em diferentes resoluções.

As resoluções utilizadas no cenário **0043** são:

* **1920 × 1080 — Desktop**
* **768 × 1024 — Tablet**
* **375 × 812 — Mobile**

A cobertura de responsividade está concentrada principalmente nos cenários **0043–0044**, sendo suficiente para demonstrar a dimensão, porém ainda passível de expansão para outros componentes e resoluções.

## ♿ Testes de Acessibilidade

Avaliam mecanismos de interação alternativos ao mouse e aspectos estruturais relacionados à acessibilidade.

**Exemplos:**

* **0036:** navegação via TAB pelos elementos interativos e footer;
* **0037:** validação de landmarks e atributos estruturais da página;
* **0038:** validação de contraste visual;
* **0039:** validação de foco visível;
* **0040:** abertura do menu de idioma utilizando ENTER;
* **0051:** validação da presença do atributo alt nas imagens.

A cobertura contempla navegação por teclado, foco, contraste, estrutura semântica e texto alternativo. Não representa, isoladamente, uma auditoria completa de conformidade WCAG.

## ⚡ Testes de Performance

Avaliam o comportamento da aplicação em relação ao tempo de resposta e à eficiência de determinadas operações.

**Exemplos:**

* **0045:** validação do carregamento inicial da Home com limite de 3 segundos;
* **0060:** validação do comportamento de debounce da busca e da quantidade de requisições disparadas durante a digitação.

A cobertura de Performance é pontual. Os cenários não caracterizam uma estratégia completa de load testing, stress de infraestrutura, throughput ou teste de múltiplos usuários concorrentes.

## ⚖️ Testes de Estabilidade

Avaliam se a aplicação permanece funcional após repetição de operações, múltiplas interações ou alterações de condições durante a execução.

**Exemplos:**

* **0034:** comportamento da aplicação após atualização da página com idioma alterado;
* **0046:** estabilidade do carrossel após múltiplas navegações consecutivas;
* **0047:** estabilidade durante carregamento dinâmico de eventos por scroll;
* **0048:** execução repetida do acesso a "Explorar Eventos";
* **0061:** monitoramento de console e rede durante um fluxo completo de navegação;
* **0063:** comportamento da interface sem carregamento das imagens.

## 🔥 Testes de Estresse (Stress Testing)

Submetem componentes ou funcionalidades a operações repetitivas ou intensivas para avaliar seu comportamento sob condições mais agressivas.

**Exemplos:**

* **0014:** múltiplos cliques consecutivos no controle do carrossel;
* **0016:** múltiplas navegações consecutivas para esquerda e direita;
* **0046:** múltiplas navegações consecutivas no carrossel.

> ⚠️ **Importante:**  Esses cenários representam estresse de componentes e interações da aplicação. Não devem ser apresentados como testes formais de carga ou performance de infraestrutura, pois não simulam múltiplos usuários ou carga concorrente.

## 🛡️ Testes de Robustez

Avaliam a capacidade da aplicação de lidar com entradas inesperadas, inválidas, repetitivas ou condições incomuns de execução.

**Exemplos:**

* **0058:** pesquisa por evento inexistente;
* **0059:** pesquisa utilizando caracteres especiais;
* **0063:** comportamento da interface sem carregamento das imagens;
* **0054:** tratamento de acesso a URL inexistente com apresentação de mensagem amigável;
* **0060:** comportamento da busca durante digitação contínua.

## 🔎 Testes de Validação de Dados

Verificam se dados inseridos, retornados, apresentados ou utilizados pelos componentes da aplicação são tratados corretamente.

**Exemplos:**

* **0031:** validação dos links principais e respectivos códigos de resposta;
* **0032:** validação do href e do comportamento esperado do link externo do Instagram;
* **0033–0035:** validação das alterações de idioma;
* **0049–0050:** validação de title e meta description;
* **0056:** validação dos links do footer;
* **0057–0059:** validação dos resultados da pesquisa;
* **0062:** validação da resposta da API de eventos.

## 🔑 Testes de Integridade

Avaliam se dados, componentes e estruturas permanecem consistentes após diferentes operações.

**Exemplos:**

* **0037:** integridade estrutural da Home, incluindo landmarks e atributos principais;
* **0044:** integridade do header em diferentes resoluções;
* **0056:** integridade dos links do footer;
* **0062:** consistência da resposta da API utilizada para disponibilizar os eventos;
* **0063:** integridade funcional da interface quando imagens não são carregadas.

## 🌐 Testes de Compatibilidade de Navegação

Verificam o comportamento da aplicação diante de diferentes mecanismos e contextos de navegação.

### GAP identificado

Não existem, nesta Feature, cenários específicos que demonstrem:

* utilização de Back e Forward do navegador;
* validação do histórico de navegação;
* retorno entre múltiplas páginas utilizando o histórico;
* navegação equivalente em diferentes browsers.

Portanto:

| Dimensão                         | Cobertura      |
| -------------------------------- | -------------- |
| **Compatibilidade de Navegação** | 🔴 Não coberta |
| **Cross-Browser**                | 🔴 Não coberta |

> ⚠️ **Importante precisão técnica:** Compatibilidade de Navegação e Cross-Browser são dimensões diferentes. A utilização de diferentes mecanismos de interação, como teclado, cliques, abas ou resoluções, não comprova compatibilidade entre Chrome, Edge, Firefox ou Safari.

## 🚨 Testes de Monitoramento de Erros

Monitoram sinais de falha durante a execução e verificam se erros técnicos não são indevidamente expostos ao usuário.

**Exemplos:**

* **0054:** validação da ausência de mensagens técnicas ao acessar uma URL inexistente;
* **0061:** monitoramento de erros do console e de respostas de rede com status HTTP ≥ 500.

> ⚠️ **Importante:** O cenário **0037** não deve ser classificado como Monitoramento de Erros, pois seu objetivo está relacionado à estrutura, landmarks e atributos da Home.

## 🎨 Testes de Integridade Visual

Avaliam se os elementos visuais permanecem consistentes após diferentes condições e interações.

**Exemplos:**

* **0038:** contraste visual dos componentes críticos;
* **0043–0044:** comportamento visual da Home e do header em diferentes resoluções;
* **0055:** padronização visual dos botões CTA;
* **0056:** consistência visual dos links do footer;
* **0063:** comportamento visual da interface sem carregamento das imagens.

## 🔃 Recuperação e Estado da Aplicação

Avaliam o comportamento da aplicação após atualização da página ou alteração de estado durante o fluxo.

**Exemplo principal:**

* **0034:** comportamento da aplicação após atualização da página com o idioma English selecionado.

O cenário verifica se a preferência de idioma permanece após o refresh ou se a aplicação retorna ao idioma padrão.

> ⚠️ **Importante precisão técnica:** Esse cenário demonstra comportamento de estado/preferência após reload, mas não comprova, isoladamente, persistência em banco de dados, sessão, cookie ou armazenamento local.

## 🔍 Observabilidade e Contrato — Analytics

Avaliam se ações relevantes do usuário geram eventos de rastreamento esperados.

**Exemplo:**

* **0064:** validação do disparo de evento de Analytics ao clicar em "Explorar Eventos", utilizando o `window.dataLayer`.

A cobertura é pontual. O cenário demonstra a existência do evento relacionado à interação, mas não caracteriza uma validação completa de contrato do Analytics contendo todos os campos, tipos, valores e schemas possíveis.

## 🏷️ Testes de SEO e Metadados

Avaliam a presença e a estrutura dos principais metadados da página.

**Exemplos:**

* **0049:** validação da presença e conteúdo da tag `<title>`;
* **0050:** validação da presença e conteúdo da meta description.

O cenário **0051**, relacionado ao atributo `alt`, permanece principalmente na dimensão de Acessibilidade. Embora o atributo também possua relevância para SEO, sua validação nesta Feature está diretamente associada à acessibilidade das imagens.

## 🔒 Testes de Segurança

Avaliam a ausência de informações sensíveis e de mensagens técnicas indevidamente expostas no frontend.

**Exemplos:**

* **0052–0053:** validação da ausência de padrões relacionados a informações sensíveis no HTML/frontend, incluindo termos como `api_key`, `secret`, `token`, `bearer`, `private_key`, `access_token` e `authorization`;
* **0054:** validação da ausência de informações técnicas sensíveis ou mensagens internas ao acessar uma URL inexistente.

Esses cenários representam verificações automatizadas de exposição no frontend. Não caracterizam, isoladamente, um teste completo de segurança da aplicação.

## 🔁 Regressão

A regressão não representa um conjunto separado de cenários.

Os **64 cenários** podem ser utilizados como uma suíte de regressão automatizada, especialmente após:

* alterações nos CTAs e botões da Home;
* alterações no seletor de idioma;
* alterações no carrossel de eventos;
* mudanças na funcionalidade de busca;
* alterações no footer;
* mudanças nos links institucionais e redes sociais;
* alterações de responsividade;
* alterações de acessibilidade;
* mudanças nas tags de SEO;
* alterações na instrumentação de Analytics;
* mudanças na estrutura ou carregamento dos eventos.

### Exemplo de estratégia

```text
Alteração no sistema
        ↓
Execução dos testes relacionados
        ↓
Execução da suíte de regressão
        ↓
Comparação dos resultados
        ↓
Identificação de regressões
        ↓
RCA / Bug Report
```

## 📊 Matriz de cobertura da suíte

| Dimensão                         | Cenários principais                              | Cobertura |
| -------------------------------- | ------------------------------------------------ | --------- |
| **E2E**                          | 0015, 0020–0025, 0057, 0062, 0064                | 🟢        |
| **Funcional**                    | 0001–0016, 0017–0030, 0033–0042, 0057–0060       | 🟢        |
| **Regressão**                    | 0001–0064                                        | 🟢        |
| **Navegação**                    | 0001–0030, 0033–0035, 0057–0058                  | 🟢        |
| **UI**                           | 0013–0016, 0020–0030, 0041–0042, 0055–0056, 0063 | 🟢        |
| **Responsividade**               | 0043–0044                                        | 🟡        |
| **Acessibilidade**               | 0036–0040, 0051                                  | 🟢        |
| **Performance**                  | 0045, 0060                                       | 🟡        |
| **Estabilidade**                 | 0034, 0046–0048, 0061, 0063                      | 🟢        |
| **Estresse**                     | 0014, 0016, 0046                                 | 🟢        |
| **Robustez**                     | 0054, 0058–0060, 0063                            | 🟢        |
| **Validação de Dados**           | 0031–0033, 0035, 0049–0050, 0056–0059, 0062      | 🟢        |
| **Integridade**                  | 0037, 0044, 0056, 0062–0063                      | 🟢        |
| **Compatibilidade de Navegação** | —                                                | 🔴        |
| **Monitoramento de Erros**       | 0054, 0061                                       | 🟢        |
| **Integridade Visual**           | 0038, 0043–0044, 0055–0056, 0063                 | 🟢        |
| **Recuperação/Estado**           | 0034                                             | 🟡        |
| **Observabilidade / Analytics**  | 0064                                             | 🟡        |
| **SEO / Metadados**              | 0049–0050                                        | 🟢        |
| **Segurança**                    | 0052–0054                                        | 🟢        |

### Legenda

| Indicador | Classificação                                              |
| --------- | ---------------------------------------------------------- |
| 🟢        | Cobertura claramente demonstrada pelos cenários analisados |
| 🟡        | Cobertura presente, porém pontual e passível de expansão   |
| 🔴        | Cobertura não observada nos cenários desta Feature         |

## ⚠️ Importante — GAP de Compatibilidade de Navegação

A ausência de cenários de Compatibilidade de Navegação na Feature **Tela Inicial** representa uma lacuna de cobertura decorrente do escopo e das condições de teste.

A suíte foi elaborada e executada exclusivamente em **ambiente de produção, utilizando o Google Chrome**. Não foram contemplados cenários específicos de histórico de navegação, como Back/Forward, retorno entre páginas utilizando o histórico e múltiplas navegações desse tipo.

Também não foram realizados testes **Cross-Browser** envolvendo Chrome, Edge, Firefox ou Safari.

Portanto, o GAP não caracteriza um defeito da aplicação, mas uma oportunidade de ampliação da cobertura da suíte, mantendo a distinção entre **Compatibilidade de Navegação** e **Compatibilidade entre Navegadores (Cross-Browser)**.


---

## 📢 Feature Publicar Eventos

| Feature |
| ------------------------- |
| Feature_Publicar Eventos |
| 0001 - Acessar a página de Publicar Eventos pela página principal |
| 0002 - Clicar na página Publicar Eventos via login do Gmail |
| 0003 - Inserir o e-mail de login por meio do login do Gmail |
| 0004 - Inserir o e-mail de login por meio do login da Apple |
| 0005 - Acessar a página de Publicar Eventos e realizar o Login |
| 0006 - Logado na página 'Producer', clicar nos botões 'Eventos', 'Equipes' e 'Dashboard' |
| 0007 - Clicar no filtro 'Período: Ano Atual' |
| 0008 - Clicar no filtro e selecionar a opção 'Eventos Futuros' |
| 0009 - Clicar no filtro e selecionar a opção 'Eventos Passados' |
| 0010 - Clicar no filtro e selecionar a opção 'Ano atual' |
| 0011 - Clicar no filtro e selecionar a opção 'Ano anterior' |
| 0012 - Clicar no filtro e selecionar a opção 'Mês atual' |
| 0013 - Clicar no filtro e selecionar a opção 'Mês anterior' |
| 0014 - Clicar no filtro e selecionar a opção 'Definir período' |
| 0015 - Acessar o filtro e clicar em todas as opções disponíveis |
| 0016 - Acessar o filtro e selecionar datas de início e fim no calendário via 'Definir período' |
| 0017 - Acessar o filtro e avançar o mês exibido no calendário |
| 0018 - Acessar o filtro e retornar o mês exibido no calendário |
| 0019 - Estresse: avançar e retroceder rapidamente vários meses no calendário do filtro |
| 0020 - Clicar no botão 'Novo Evento' e acessar a página de criação |
| 0021 - Clicar no botão 'Salvar configurações' no final da página |
| 0022 - Preencher 'Buscar endereço' com o nome da casa de eventos 'Carioca Club' |
| 0023 - Preencher endereço com nome e clicar na sugestão exibida pelo sistema |
| 0024 - Preencher endereço completo da casa de eventos 'Carioca Club' |
| 0025 - Preencher endereço completo e clicar na sugestão exibida e confirmada |
| 0026 - Preencher apenas o CEP da casa de eventos |
| 0027 - Preencher apenas o CEP e clicar na sugestão exibida e confirmada |
| 0028 - Preencher apenas o nome do estado 'Minas Gerais' |
| 0029 - Preencher nome do estado e clicar na confirmação exibida pelo sistema |
| 0030 - Preencher apenas o nome da cidade 'Belo Horizonte' |
| 0031 - Preencher nome da cidade e validar seleção/limpeza da sugestão |
| 0032 - Preencher CEP sem casa de eventos associada e confirmar |
| 0033 - Preencher número inexistente sem registro e confirmar a busca |
| 0034 - Preencher números e caracteres especiais sem registro e confirmar a busca |
| 0035 - Estresse: preencher números/caracteres especiais e confirmar a busca 5x seguidas |
| 0036 - Acessar o campo 'Detalhes do Local' após selecionar endereço válido |
| 0037 - Ativar e desativar a opção 'Mostrar Endereço' após selecionar endereço válido |
| 0038 - Visualizar o mapa em tela cheia após selecionar endereço válido |
| 0039 - Alternar a visualização do mapa entre Satélite e Mapa |
| 0040 - Validar a exibição dos controles Satélite, Mapa e Câmera |
| 0041 - Clicar no campo 'Limite de Ingressos' |
| 0042 - Validar campo 'Limite de Ingressos' sem preenchimento |
| 0043 - Validar campo 'Limite de Ingressos' com preenchimento |
| 0044 - Validar campo 'Limite de Ingressos' com preenchimento via stepper (setas) |
| 0045 - Estresse controlado no campo 'Limite de Ingressos' com valores positivos |
| 0046 - Estresse controlado no campo 'Limite de Ingressos' com valores negativos |
| 0047 - Validar limpeza do campo 'Limite de Ingressos' após atualização da página |
| 0048 - Preencher 'Limite de Ingressos' e validar persistência após atualização da página |
| 0049 - Exibir calendário ao acessar o campo 'Início do Evento' |
| 0050 - Exibir calendário ao acessar o campo 'Fim do Evento' |
| 0051 - Exibir calendário ao acessar o campo 'Encerrar Vendas' |
| 0052 - Selecionar data no calendário do campo 'Início do Evento' |
| 0053 - Selecionar data no calendário do campo 'Fim do Evento' |
| 0054 - Selecionar data no calendário do campo 'Encerrar Vendas' (valida dependência de datas anteriores) |
| 0055 - Navegar para meses posteriores no campo 'Início do Evento' |
| 0056 - Navegar para meses anteriores no campo 'Início do Evento' |
| 0057 - Navegar para meses posteriores no campo 'Fim do Evento' |
| 0058 - Navegar para meses anteriores no campo 'Fim do Evento' |
| 0059 - Navegar para meses posteriores no campo 'Encerrar Vendas' |
| 0060 - Navegar para meses anteriores no campo 'Encerrar Vendas' |
| 0061 - Alterar Horas, Minutos e Segundos no campo 'Início do Evento' |
| 0062 - Alterar Horas, Minutos e Segundos no campo 'Fim do Evento' |
| 0063 - Alterar Horas, Minutos e Segundos no campo 'Encerrar Vendas' |
| 0064 - Preencher data e horário nos três campos (Início, Fim, Encerrar Vendas) |
| 0065 - Estresse: acesso simultâneo preenchendo data/horário nos três campos, 5 iterações |
| 0066 - Fluxo completo: preencher data e horário nos três campos |
| 0067 - Fluxo completo com estresse de preenchimento de data/hora (15 execuções) |
| 0068 - Fluxo completo com estresse + reset de calendário (50 cliques de navegação) |
| 0069 - Fluxo completo com estresse de múltiplas aberturas de modal (20x) |
| 0070 - Fluxo completo com estresse de modal + estresse de input no campo de horas |
| 0071 - Fluxo completo com estresse E2E + modal (10 iterações) |
| 0072 - Estresse multiusuário: 3 sessões simultâneas preenchendo data/hora |
| 0073 - Validar obrigatoriedade dos campos ao salvar sem nenhum preenchimento |
| 0074 - Preencher apenas 'Nome do evento' e salvar configurações |
| 0075 - Preencher apenas 'Descrição Curta' e salvar configurações |
| 0076 - Preencher apenas 'Descrição do Evento' e salvar configurações |
| 0077 - Preencher apenas 'Início do Evento' e salvar configurações |
| 0078 - Edição da descrição do evento (negrito, itálico, títulos, listas, imagem, link) |
| 0079 - Inserir e manipular link no campo 'Descrição do Evento' |
| 0080 - Abrir modal de imagem e interagir com o botão 'Selecionar' |
| 0081 - Interagir com upload de Capa Vertical |
| 0082 - Interagir com upload de Capa Horizontal |
| 0083 - Visualizar e clicar na opção 'Gerenciar Equipes' |
| 0084 - Clicar em 'Pesquisar equipe' e realizar uma busca |
| 0085 - Acessar 'Pesquisar equipe' e criar via 'Nova Equipe' |
| 0086 - Clicar em 'Salvar' sem preencher campos obrigatórios da equipe |
| 0087 - Preencher 'Nome da Equipe' e tentar salvar sem membros |
| 0088 - Clicar no campo 'Adicionar' (membro à equipe) |
| 0089 - Tentar adicionar membro sem preencher campos obrigatórios |
| 0090 - Clicar e acessar o campo 'Controle de acesso' |
| 0091 - Acessar 'Controle de acesso' e clicar nos 'Templates' de perfil disponíveis |
| 0092 - Selecionar templates de perfil no controle de acesso (Agente, Marketing, Staff, Acesso Total) |
| 0093 - Selecionar nível de acesso na seção 'Visão Geral' |
| 0094 - Alterar nível de acesso na seção 'Visão Geral' entre múltiplas opções |
| 0095 - Alterar permissões de acesso para todas as seções do evento |
| 0096 - Estresse na alteração de permissões de acesso (5 ciclos completos) |
| 0097 - Estresse integrado: perfis + permissões por seção (2 ciclos) |
| 0098 - Alterar perfis e permissões por seção, validar estado final e fechar o modal |
| **Total** | **98** |

Assim como na Feature Explorar Eventos, todos os testes foram classificados por dimensão de teste, evitando tratar conceitos distintos como categorias equivalentes. Esta Feature introduz **quatro dimensões específicas** que não existiam na Explorar Eventos, refletindo a maior complexidade funcional da página (integrações externas, editor de conteúdo e um sistema de permissões).

### 📌 Dimensões de cobertura

| Dimensão | Categorias | Objetivo |
| --- | --- | --- |
| **Escopo** | E2E | Validar jornadas completas atravessando diferentes páginas e componentes |
| **Objetivo funcional** | Funcionais, Validação de Dados, Integridade | Verificar comportamentos esperados, dados apresentados e consistência das informações |
| **Qualidade da aplicação** | UI, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais |
| **Condição / técnica de teste** | Estresse | Exercitar a aplicação sob condições repetitivas ou intensivas |
| **Resiliência** | Recuperação de Estado | Avaliar comportamento diante de reloads |
| **Integração com Provedores Externos** | SSO (Google/Apple), Google Maps/Places | Validar integrações com serviços de terceiros — dimensão específica desta feature |
| **Editor de Conteúdo (WYSIWYG)** | Formatação de texto, links, mídia embutida | Validar o editor rico de descrição do evento — dimensão específica desta feature |
| **Controle de Acesso (RBAC)** | Perfis, permissões por seção, templates | Validar o sistema de papéis e permissões de equipe — dimensão específica desta feature |
| **Concorrência Multiusuário** | Sessões simultâneas | Validar comportamento sob uso concorrente real (múltiplas sessões de browser) — dimensão específica desta feature |
| **Finalidade de execução** | Regressão | Reexecutar cenários existentes para identificar impactos de alterações no sistema |

---

## 🧪 Cobertura funcional e E2E

### Testes Funcionais

**Exemplos:**

* **0001–0006:** acesso à página e autenticação;
* **0007–0019:** filtro de período no dashboard;
* **0020–0021:** criação de novo evento e salvamento;
* **0041–0048:** campo de limite de ingressos;
* **0049–0063:** campos de data/hora (Início, Fim, Encerrar Vendas);
* **0073–0082:** campos de configuração do evento (nome, descrições, capas);
* **0083–0090:** gestão de equipes.

### Testes End-to-End (E2E)

**Exemplos:**

* **0001, 0005:** Home → Publicar Eventos → Login;
* **0020:** login → dashboard → criação de novo evento;
* **0064, 0066:** preenchimento completo dos três campos de data/hora em sequência;
* **0083–0098:** criação de equipe → adicionar membro → configurar controle de acesso → validar estado final — a jornada mais longa da suíte, atravessando 4 sub-fluxos distintos.

> ⚠️ **Importante observação:** Assim como na Feature de referência, E2E representa o **escopo da jornada**, não uma categoria isolada.

---

## 🗺️ Testes de Navegação

**Exemplos:**

* **0001–0006:** diferentes pontos de acesso e autenticação;
* **0007–0019:** navegação pelo dropdown e calendário do filtro de período;
* **0020:** navegação até a criação de evento;
* **0049–0060:** abertura e navegação por mês nos três campos de data/hora;
* **0083:** navegação até "Gerenciar Equipes".

---

## 🖥️ Testes de Interface (UI)

**Exemplos:**

* **0038–0040:** controles do mapa (tela cheia, Satélite/Mapa, câmera);
* **0078:** toolbar de formatação do editor (negrito, itálico, H1/H2/H3, listas, imagem, link);
* **0080–0082:** modais de upload de imagem e capas;
* **0091–0094:** dropdowns de seleção de perfil e nível de acesso.

---

## ⚖️ Testes de Estabilidade

**Exemplos:**

* **0047–0048:** persistência/limpeza de campo após reload;
* **0068:** estabilidade após reset de calendário (50 cliques de navegação seguidos);
* **0072:** estabilidade sob 3 sessões simultâneas.

---

## 🔥 Testes de Estresse (Stress Testing)

Esta Feature tem a cobertura de estresse mais extensa da suíte, com uma escalada progressiva de complexidade:

**Exemplos:**

* **0015:** todas as opções do filtro de período em sequência;
* **0017–0019:** navegação rápida repetida no calendário do filtro;
* **0034–0035:** entrada extrema no campo de endereço, repetida 5x;
* **0045–0046:** interações repetidas no stepper do campo de limite (valores positivos e negativos);
* **0065, 0067:** preenchimento repetido de data/hora (5x e 15x);
* **0068–0071:** combinações crescentes de estresse — reset de calendário, múltiplas aberturas de modal, estresse de input, e E2E completo em 10 iterações;
* **0072:** estresse multiusuário com 3 sessões `Playwright` paralelas;
* **0096–0097:** estresse de alteração de permissões (5 e 2 ciclos completos, cobrindo múltiplas seções e perfis).

> ⚠️ **Importante:** Assim como na feature de referência, esses cenários caracterizam robustez de componentes sob uso intensivo não substituem uma ferramenta dedicada de load testing com carga real de múltiplos usuários de produção (com exceção do cenário 0072, que é o único desta suíte a usar sessões de browser genuinamente paralelas via `session()`).

---

## 🛡️ Testes de Robustez

**Exemplos:**

* **0026–0032:** buscas parciais de endereço (CEP isolado, estado isolado, cidade isolada) sem nome de estabelecimento;
* **0033:** número inexistente sem nenhum registro correspondente;
* **0034–0035:** string com mais de 90 caracteres combinando números e símbolos especiais;
* **0042:** campo obrigatório vazio (`aria-invalid`);
* **0046:** valor negativo no stepper de limite de ingressos.

---

## 🔎 Testes de Validação de Dados

**Exemplos:**

* **0022–0032:** diferentes formatos de entrada no campo de endereço (nome, endereço completo, CEP, estado, cidade) e a sugestão retornada pelo Google Places;
* **0042–0046:** validação de `aria-invalid` e mensagens de erro no campo de limite de ingressos;
* **0073–0077:** obrigatoriedade de campos ao salvar configurações do evento, testando um campo preenchido por vez;
* **0086–0087, 0089:** validação de campos obrigatórios na criação de equipe e adição de membros.

---

## 🔑 Testes de Integridade

**Exemplos:**

* **0036:** alternância dupla do painel "Detalhes do Local" sem quebra de estado;
* **0037:** consistência entre o switch "Mostrar Endereço" e os campos ocultos de latitude/longitude;
* **0047–0048:** integridade do campo de limite após reload;
* **0095, 0098:** validação do estado final de todas as seções de permissão após múltiplas alterações, confirmando que o valor exibido corresponde à última seleção feita.

---

## 🎨 Testes de Integridade Visual

**Exemplos:**

* **0038–0040:** carregamento visual do mapa e seus controles em diferentes configurações;
* **0078:** estado visual ativo dos botões da toolbar (classe `bg-secondary`) refletindo a formatação aplicada.

---

## 🔃 Recuperação e Estado da Aplicação

**Exemplos:**

* **0047:** campo de limite exibe erro de validação após ser esvaziado, mesmo após reload;
* **0048:** valor preenchido é reavaliado corretamente após atualização da página.

---

## 🔌 Testes de Integração com Provedores Externos (dimensão nova nesta feature)

Avaliam o comportamento da aplicação ao integrar com serviços de terceiros — autenticação social e geolocalização.

**Exemplos:**

* **0002–0004:** login social via Google e Apple, incluindo o tratamento de bloqueios esperados do próprio Google (`signin/rejected`, "Esse navegador ou app pode não ser seguro") como resultado **válido** de um ambiente de automação, não como falha do teste;
* **0022–0035:** integração com o autocomplete do Google Places, incluindo casos de entrada sem correspondência;
* **0038–0040:** iframe do Google Maps incorporado, com verificação condicional de controles (o teste se adapta caso um controle não esteja disponível na configuração atual do mapa).

> ⚠️ **Importante observação técnica** Os cenários 0003 e 0004 são particularmente sofisticados do ponto de vista de QA — eles reconhecem que a automação de login de terceiros (Google/Apple) é frequentemente **bloqueada intencionalmente** por essas plataformas como proteção antibot, e tratam esse bloqueio como confirmação de que a integração está funcionando (a aplicação redirecionou corretamente para o provedor), não como um erro do fluxo.

---

## 📝 Testes do Editor de Conteúdo — WYSIWYG (dimensão nova nesta feature)

**Exemplos:**

* **0078:** aplicação e remoção de formatação (negrito, itálico, cabeçalhos H1/H2/H3, listas ordenadas/não ordenadas), inserção de imagem e link, com verificação do estado visual ativo de cada botão;
* **0079:** inserção, edição e remoção de link via modal dedicado, incluindo o comportamento do campo após a remoção.

---

## 👥 Testes de Controle de Acesso — RBAC (dimensão nova nesta feature)

Avaliam o sistema de papéis e permissões granulares por seção do evento — a área de maior complexidade de regras de negócio da suíte.

**Exemplos:**

* **0090–0092:** acesso ao painel de controle e seleção de templates de perfil pré-definidos (Agente, Marketing, Staff, Acesso Total);
* **0093–0094:** alteração do nível de acesso na seção "Visão Geral" entre os quatro níveis (Somente Leitura, Acesso Total, Sem Acesso), incluindo múltiplas trocas em sequência;
* **0095:** aplicação do fluxo completo de 4 níveis de permissão a **todas** as seções disponíveis do evento, descobertas dinamicamente via DOM em vez de hardcoded;
* **0096–0098:** estresse e validação cruzada entre múltiplos perfis (Agente, Marketing, Staff, Acesso Total) e todas as seções, com verificação de estado final e fechamento correto do modal.

> ⚠️ **Importante:** Esta é a dimensão mais elaborada tecnicamente da suíte: os cenários usam retry automático (até 3 tentativas por seleção), descoberta dinâmica de seções via `grabTextFromAll`, e validação de estado final iterando sobre todas as combinações perfil × seção — um padrão de teste orientado a dados (data-driven), não apenas scripted.

---

## 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os 98 cenários podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após:

* alterações no fluxo de autenticação (própria ou social);
* alterações na integração com Google Maps/Places;
* alterações nos campos de configuração do evento;
* alterações no editor de descrição (WYSIWYG);
* alterações no sistema de permissões e papéis de equipe;
* mudanças nos componentes de calendário/date-picker.

### Exemplo de estratégia

```text
Alteração no sistema
        ↓
Execução dos testes relacionados
        ↓
Execução da suíte de regressão
        ↓
Comparação dos resultados
        ↓
Identificação de regressões
        ↓
RCA / Bug Report
```

---

## 📊 Matriz de cobertura da suíte

| Dimensão | Cenários principais | Cobertura |
| --- | --- | --- |
| **E2E** | 0001, 0005, 0020, 0064, 0066, 0083–0098 | 🟢 |
| **Funcional** | 0001–0021, 0041–0063, 0073–0090 | 🟢 |
| **Regressão** | 0001–0098 | 🟢 |
| **Navegação** | 0001–0019, 0049–0060, 0083 | 🟢 |
| **UI** | 0038–0040, 0078, 0080–0082, 0091–0094 | 🟢 |
| **Responsividade** | — | 🔴 não coberta nesta feature |
| **Acessibilidade** | — | 🔴 não coberta nesta feature |
| **Performance** | — | 🔴 não coberta nesta feature |
| **Estabilidade** | 0047–0048, 0068, 0072 | 🟢 |
| **Estresse** | 0015, 0017–0019, 0034–0035, 0045–0046, 0065, 0067–0072, 0096–0097 | 🟢 |
| **Robustez** | 0026–0035, 0042, 0046 | 🟢 |
| **Validação de Dados** | 0022–0032, 0042–0046, 0073–0077, 0086–0089 | 🟢 |
| **Integridade** | 0036–0037, 0047–0048, 0095, 0098 | 🟢 |
| **Compatibilidade de Navegação** | — | 🔴 não coberta nesta feature |
| **Monitoramento de Erros** | — | 🔴 não coberta nesta feature |
| **Integridade Visual** | 0038–0040, 0078 | 🟢 |
| **Recuperação/Estado** | 0047–0048 | 🟢 |
| **Integração com Provedores Externos** | 0002–0004, 0022–0035, 0038–0040 | 🟢 |
| **Editor WYSIWYG** | 0078–0079 | 🟢 |
| **Controle de Acesso (RBAC)** | 0090–0098 | 🟢 |
| **Concorrência Multiusuário** | 0072 | 🟡 |



### Legenda

| Indicador | Classificação |
| ------------------------- | ------------------------- |
| 🟢 | Cobertura claramente demonstrada pelos cenários analisados |
| 🟡 | Cobertura presente, porém pontual e passível de expansão |
| 🔴 | Não coberta pelos cenários desta feature (pode ser coberta em outra Feature, ex.: Acessibilidade/Responsividade já cobertas na Explorar Eventos e Suporte e Ajuda) |

---

> ⚠️ **Importante observações finais comparando com as outras Features:**

1. **Maior complexidade de regras de negócio da suíte**: Diferente das Features anteriores, esta lida com dependências entre campos (ex: cenário 0054 valida que "Encerrar Vendas" não pode ser anterior a datas já definidas) e com um sistema de permissões multidimensional (perfil × seção × nível de acesso).
2. **Uso extensivo de dados dinâmicos**: Vários cenários (0095, 0097, 0098) descobrem as seções disponíveis via DOM em tempo de execução em vez de usar uma lista fixa, isso torna os testes mais resilientes a mudanças de conteúdo, mas também significa que a suíte depende da estrutura do DOM permanecer semanticamente consistente (`label`/`for`).
3. **Tratamento maduro de bloqueios de terceiros**: Os cenários de login social (0003, 0004) são um exemplo de boa prática de QA, reconhecem que um bloqueio antibot do Google/Apple é um resultado esperado em ambiente automatizado, evitando falsos negativos.
4. **Lacunas em relação às outras Features**: Responsividade, Acessibilidade, Performance, Compatibilidade de Navegação e Monitoramento de Erros bem cobertas na Explorar Eventos e/ou Suporte e Ajuda não aparecem nesta Feature. Dado o alto número de campos de formulário e modais complexos aqui, a ausência de testes de acessibilidade (navegação por teclado, foco) é a lacuna mais relevante a considerar para expansão futura.

---

## 🎟️ Feature Comprar Ingressos

| Feature                                                                                                                                     |         |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Feature_Comprar Ingressos                                                                                                                   |         |
| 0001 - Acessar evento sem login e visualizar disponibilidade de ingressos                                                                   |         |
| 0002 - Tentar realizar a compra de ingresso sem selecionar nenhuma quantidade                                                               |         |
| 0003 - Redirecionamento para login ao tentar comprar ingressos sem autenticação                                                             |         |
| 0004 - Redirecionar para login ao tentar comprar ingressos sem autenticação, realizar o login para finalizar a compra                       |         |
| 0005 - Redirecionar para login ao tentar comprar quantidade máxima de ingressos sem autenticação, realizar o login para finalizar a compra  |         |
| 0006 - Funcionalidade, impedir seleção acima do limite máximo de 5 ingressos                                                                |         |
| 0007 - Impedir que a quantidade de ingressos fique abaixo de zero, mesmo com múltiplas tentativas de diminuição                             |         |
| 0008 - Comprar a primeira opção de ingresso disponível (Meia Estudante) sem autenticação                                                    |         |
| 0009 - Comprar a segunda opção de ingresso disponível (Meia Solidária) sem autenticação                                                     |         |
| 0010 - Comprar a terceira opção de ingresso disponível (Inteira) sem autenticação                                                           |         |
| 0011 - Comprar todos os tipos de ingressos validando limite mínimo                                                                          |         |
| 0012 - Comprar ingressos validando limite mínimo por tipo                                                                                   |         |
| 0013 - Comprar ingressos validando request e response                                                                                       |         |
| 0014 - Validar payload da compra de ingressos no endpoint de pedidos                                                                        |         |
| 0015 - Validar valor total da compra de ingressos no pedido                                                                                 |         |
| 0016 - Validar headers de autenticação na requisição de compra                                                                              |         |
| 0017 - Garantir que os dados exibidos na UI sejam idênticos ao payload enviado na criação do pedido                                         |         |
| 0018 - Validar que múltiplos cliques no botão Comprar ingressos não geram pedidos duplicados                                                |         |
| 0019 - Validar persistência dos ingressos selecionados após login                                                                           |         |
| 0020 - Impedir seleção acima do limite máximo de ingressos — Boundary Value (limite superior)                                               |         |
| 0021 - Validar precisão do cálculo do valor total com taxa de 15% de conveniência                                                           |         |
| 0022 - Resetar seleção de ingressos ao atualizar a página                                                                                   |         |
| 0023 - Consistência de comportamento em múltiplas abas independentes                                                                        |         |
| 0024 - Validação de segurança contra manipulação de valor no checkout                                                                       |         |
| 0025 - Reset do carrinho após falha de login                                                                                                |         |
| 0026 - Pagamento com cartão de crédito com dados completos (CPF)                                                                            |         |
| 0027 - Pagamento com cartão de crédito com dados completos (CNPJ)                                                                           |         |
| 0028 - Exibir mensagens de erro ao preencher dados inválidos no formulário de pagamento (CPF)                                               |         |
| 0029 - Exibir mensagens de erro ao preencher dados inválidos no formulário de pagamento (CNPJ)                                              |         |
| 0030 - Validar exibição de erros ao tentar pagar sem preencher os campos obrigatórios com cartão de crédito                                 |         |
| 0031 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Número do cartão                                                      |         |
| 0032 - Exibir mensagens de erro ao tentar pagar sem preencher o campo data de vencimento do cartão                                          |         |
| 0033 - Exibir mensagens de erro ao tentar pagar sem preencher o campo código de segurança (CVV) do cartão                                   |         |
| 0034 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Nome do Titular como aparece do cartão                                |         |
| 0035 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Documento do Titular (CPF)                                            |         |
| 0036 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Documento do Titular (CNPJ)                                           |         |
| 0037 - Exibir mensagens de erro ao tentar pagar sem preencher o campo E-mail                                                                |         |
| 0038 - Pagamento com cartão de Débito Virtual CAIXA com dados completos (CPF)                                                               |         |
| 0039 - Pagamento com cartão de Débito Virtual CAIXA com dados completos (CNPJ)                                                              |         |
| 0040 - Cartão de Débito Virtual CAIXA, exibir mensagens de erro ao preencher dados inválidos no formulário de pagamento (CPF)               |         |
| 0041 - Cartão de Débito Virtual CAIXA, exibir mensagens de erro ao preencher dados inválidos no formulário de pagamento (CNPJ)              |         |
| 0042 - Validar exibição de erros ao tentar pagar sem preencher os campos obrigatórios do Cartão de Débito Virtual CAIXA                     |         |
| 0043 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Número do Cartão de Débito Virtual CAIXA                              |         |
| 0044 - Exibir mensagens de erro ao tentar pagar sem preencher o campo data de vencimento do Cartão de Débito Virtual CAIXA                  |         |
| 0045 - Exibir mensagem 'Dado obrigatório' ao tentar pagar sem preencher o campo código de segurança (CVV) do Cartão de Débito Virtual CAIXA |         |
| 0046 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Nome do Titular como aparece do Cartão de Débito Virtual CAIXA        |         |
| 0047 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Documento do Titular (CPF) do Cartão de Débito Virtual CAIXA          |         |
| 0048 - Exibir mensagens de erro ao tentar pagar sem preencher o campo Documento do Titular (CNPJ) do Cartão de Débito Virtual CAIXA         |         |
| 0049 - Exibir mensagens de erro ao tentar pagar sem preencher o campo E-mail do Cartão de Débito Virtual CAIXA                              |         |
| 0050 - Cartão de Crédito, validação e exibição da bandeira “Mastercard” ao inserir um cartão válido                                         |         |
| 0051 - Cartão de Crédito, inserir número de cartão com número incompleto da bandeira Mastercard                                             |         |
| 0052 - Cartão de Crédito, validação e exibição da bandeira “Visa” ao inserir um cartão válido                                               |         |
| 0053 - Cartão de Crédito, inserir número de cartão com número incompleto da bandeira Visa                                                   |         |
| 0054 - Validação e exibição da bandeira “American Express” ao inserir um cartão válido                                                      |         |
| 0055 - Cartão de Crédito, inserir número de cartão com número incompleto da bandeira American Express                                       |         |
| 0056 - Inserir código de segurança válido da bandeira de cartão Mastercard                                                                  |         |
| 0057 - Inserir código de segurança inválido da bandeira de cartão Mastercard                                                                |         |
| 0058 - Inserir código de segurança válido da bandeira de cartão Visa                                                                        |         |
| 0059 - Inserir código de segurança inválido da bandeira de cartão Visa                                                                      |         |
| 0060 - Inserir código de segurança válido da bandeira de cartão American Express                                                            |         |
| 0061 - Inserir código de segurança inválido da bandeira de cartão American Express                                                          |         |
| 0062 - Inserir data de vencimento válida de cartão de crédito                                                                               |         |
| 0063 - Inserir cartão com data de vencimento expirada de cartão de crédito                                                                  |         |
| 0064 - Inserir cartão com data de vencimento incompleto de cartão de crédito                                                                |         |
| 0065 - Inserir no campo 'Nome do titular como aparece no cartão' um nome inválido (Com apenas um caractere)                                 |         |
| 0066 - Inserir no campo “Nome do titular como aparece no cartão” caracteres especiais                                                       |         |
| 0067 - Validar preenchimento do campo com vários tipos de caracteres especiais                                                              |         |
| 0068 - Validar preenchimento correto do campo CPF                                                                                           |         |
| 0069 - Validar preenchimento incorreto do campo CPF                                                                                         |         |
| 0070 - Validar preenchimento correto do campo CNPJ                                                                                          |         |
| 0071 - Validar preenchimento incorreto do campo CNPJ                                                                                        |         |
| 0072 - Validar preenchimento incorreto do campo E-mail                                                                                      |         |
| 0073 - Validar preenchimento correto do campo E-mail                                                                                        |         |
| 0074 - Cartão de Débito Virtual CAIXA, inserir no campo “Nome do titular como aparece no cartão” um nome inválido (Com apenas um caractere) |         |
| 0075 - Cartão de Débito Virtual CAIXA, inserir no campo “Nome do titular como aparece no cartão” caracteres especiais                       |         |
| 0076 - Cartão de Débito Virtual CAIXA, validar preenchimento do campo com vários tipos de caracteres especiais                              |         |
| 0077 - Cartão de Débito Virtual CAIXA, validar preenchimento correto do campo CPF                                                           |         |
| 0078 - Cartão de Débito Virtual CAIXA, validar preenchimento incorreto do campo CPF                                                         |         |
| 0079 - Cartão de Débito Virtual CAIXA, validar preenchimento correto do campo CNPJ                                                          |         |
| 0080 - Cartão de Débito Virtual CAIXA, validar preenchimento incorreto do campo CNPJ                                                        |         |
| 0081 - Cartão de Débito Virtual CAIXA, validar preenchimento incorreto do campo E-mail                                                      |         |
| 0082 - Cartão de Débito Virtual CAIXA, validar preenchimento correto do campo E-mail                                                        |         |
| 0083 - Pagamento via PIX preenchendo o campo e-mail                                                                                         |         |
| 0084 - Pagamento via PIX não preenchendo o campo e-mail                                                                                     |         |
| 0085 - Exibir erro ao tentar pagar via PIX com e-mails inválidos                                                                            |         |
| 0086 - Exibição de erros ao tentar pagar via PIX com e-mails inválidos (caracteres especiais + números)                                     |         |
| 0087 - Bloquear preenchimento do e-mail PIX apenas com espaços em branco                                                                    |         |
| 0088 - Validar remoção automática de espaços no e-mail PIX                                                                                  |         |
| 0089 - Validar limite máximo de caracteres no campo E-mail via forma de pagamento PIX                                                       |         |
| 0090 - Validar proteção contra scripts no campo e-mail PIX                                                                                  |         |
| 0091 - Validar proteção contra SQL Injection no campo e-mail PIX                                                                            |         |
| 0092 - Validar interação com métodos de pagamento na página de pedido                                                                       |         |
| 0093 - Pix, evitar múltiplas submissões ao clicar repetidamente no botão pagar                                                              |         |
| 0094 - Pix, evitar múltiplas submissões ao clicar repetidamente no botão pagar utilizando e-mails inválidos                                 |         |
| 0095 - Pix, evitar múltiplas submissões ao clicar repetidamente no botão pagar com e-mail válido                                            |         |
| 0096 - Desabilitar botão pagar durante o processamento do pagamento                                                                         |         |
| 0097 - Recarregar checkout durante pagamento PIX com e-mail válido                                                                          |         |
| 0098 - Recarregar checkout durante pagamento PIX com e-mail inválido                                                                        |         |
| 0099 - Exibir mensagem de sucesso ao clicar no botão Copiar chave PIX                                                                       |         |
| 0100 - Exibir mensagem de sucesso ao clicar no campo “Ou copie a chave”                                                                     |         |
| 0101 - Evitar múltiplos eventos ao clicar repetidamente em 'Copiar chave'                                                                   |         |
| 0102 - Validar renderização correta do QR Code após pagamento PIX                                                                           |         |
| 0103 - Expiração de pagamento PIX no checkout, exibir mensagem ao expirar pagamento PIX                                                     |         |
| 0104 - Validar que cada pagamento PIX gere um QR Code único                                                                                 |         |
| 0105 - Bloquear múltiplas cobranças PIX                                                                                                     |         |
| 0106 - Validar tempo de 5 segundos para exibição do QR Code PIX                                                                             |         |
| 0107 - Validar desaparecimento automático do toast 'Código copiado para a área de transferência!'                                           |         |
| 0108 - Realizar logout após selecionar ingressos                                                                                            |         |
| 0109 - Retornar para a página do evento e acessar novamente o checkout                                                                      |         |
| 0110 - Atualizar página na etapa de pagamento                                                                                               |         |
| 0111 - Validar persistência do pedido ao sair e retornar ao checkout                                                                        |         |
| 0112 - Checkout sessão expirada durante o fluxo de compra (10 minutos)                                                                      |         |
| 0113 - Refresh próximo da expiração do checkout                                                                                             |         |
| 0114 - Abrir checkout em nova aba do navegador                                                                                              |         |
| 0115 - Atualizar múltiplas vezes a página do checkout                                                                                       |         |
| 0116 - Logout em outra aba durante o checkout                                                                                               |         |
| 0117 - Validar sincronização do contador do checkout                                                                                        |         |
| 0118 - Validar persistência indevida do checkout após logout                                                                                |         |
| 0119 - Utilizar botão voltar durante pagamento                                                                                              |         |
| 0120 - Abrir o mesmo checkout em múltiplas abas                                                                                             |         |
| 0121 - Expiração do checkout em múltiplas abas simultaneamente                                                                              |         |
| 0122 - Validar persistência do subtotal após refresh                                                                                        |         |
| 0123 - Validar criação de novo pedido após carrinho expirado                                                                                |         |
| 0124 - Validar comportamento do checkout após hard refresh                                                                                  |         |
| 0125 - Validar bloqueio de checkout após múltiplas expirações consecutivas                                                                  |         |
| 0126 - Validar que o botão 'Pagar' não seja duplicado após alternar abas e retornar ao checkout                                             |         |
| 0127 - Garantir que elementos do checkout não sejam duplicados após alternar abas do navegador                                              |         |
| **Total**                                                                                                                                   | **127** |
                                                                                                                        

## 📌 Dimensões de cobertura

| Dimensão | Categorias | Objetivo |
| --- | --- | --- |
| **Escopo** | E2E | Validar jornadas completas de compra, checkout e pagamento, atravessando diferentes etapas e componentes |
| **Objetivo funcional** | Funcionais, Validação de Dados, Integridade | Verificar comportamentos esperados, validações, dados apresentados e consistência das informações durante a compra |
| **Qualidade da aplicação** | UI, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais |
| **Condição / técnica de teste** | Estresse | Exercitar a aplicação sob múltiplas interações, cliques, reloads, abas e tentativas consecutivas |
| **Resiliência** | Recuperação de Estado, Persistência de Estado | Avaliar o comportamento do checkout diante de refresh, logout, expiração de sessão, troca de abas e retorno ao fluxo |
| **Segurança** | Validação contra manipulação de valores, XSS e SQL Injection | Verificar mecanismos de proteção relacionados ao checkout e aos dados informados pelo usuário |
| **Concorrência / Multiaba** | Múltiplas abas e sessões de checkout | Validar o comportamento do fluxo de compra quando o mesmo checkout é manipulado em diferentes abas |
| **Finalidade de execução** | Regressão | Reexecutar os cenários existentes para identificar impactos de alterações no fluxo de compra e pagamento |

> ⚠️ **Importante:** A suíte apresenta ampla cobertura funcional, de validação, segurança, estabilidade e resiliência. Não foram considerados como cobertos, por ausência de cenários específicos, testes de **Cross-Browser**, **Responsividade**, **Acessibilidade**, **SEO/Metadados**, **Analytics** ou **Monitoramento de Erros/Console**.

---

## 🧪 Cobertura funcional e E2E

### Testes Funcionais

**Exemplos:**

- **0001–0012:** acesso ao evento, seleção de ingressos e validação das quantidades permitidas;
- **0013–0025:** validações da criação do pedido, cálculo de valores, autenticação, persistência da seleção e comportamento do carrinho;
- **0026–0049:** preenchimento, validação e processamento dos dados de pagamento por cartão de crédito e Cartão de Débito Virtual CAIXA;
- **0050–0082:** validação das bandeiras, código de segurança, vencimento, CPF, CNPJ, nome do titular e e-mail;
- **0083–0107:** fluxo de pagamento via PIX, validação do e-mail, geração do QR Code, cópia da chave, múltiplas submissões e expiração;
- **0108–0125:** comportamento do checkout diante de logout, retorno ao evento, refresh, expiração, múltiplas abas e recuperação da sessão;
- **0126–0127:** validação da integridade dos elementos do checkout após alternância entre abas.

### Testes End-to-End (E2E)

**Exemplos:**

- **0001–0005:** acesso ao evento → seleção de ingressos → tentativa de compra → autenticação → continuidade do fluxo;
- **0008–0017:** seleção dos diferentes tipos de ingresso → criação do pedido → validação de request, response, payload, valores e dados enviados;
- **0026–0037:** checkout → preenchimento dos dados do cartão → validações dos campos obrigatórios → tentativa de pagamento;
- **0038–0049:** checkout → seleção do Cartão de Débito Virtual CAIXA → preenchimento e validação dos dados → tentativa de pagamento;
- **0083–0107:** checkout → seleção de PIX → preenchimento do e-mail → processamento → geração do QR Code → cópia da chave → validação de expiração e submissões;
- **0108–0125:** alterações de estado durante o checkout → logout, refresh, expiração, retorno, múltiplas abas e criação de novo pedido.

> ⚠️ **Importante observação:** assim como na feature de referência, E2E representa o **escopo da jornada**, e não uma categoria isolada de teste.

---

## 🗺️ Testes de Navegação

**Exemplos:**

- **0001–0005:** navegação entre evento, seleção de ingressos e autenticação;
- **0008–0019:** navegação entre seleção de ingressos, login e criação do pedido;
- **0108–0111:** retorno à página do evento, acesso novamente ao checkout e navegação durante o processo de pagamento;
- **0114:** abertura do checkout em nova aba;
- **0116:** logout realizado em outra aba durante o checkout;
- **0119:** utilização do botão voltar durante o pagamento;
- **0120–0121:** abertura e expiração do mesmo checkout em múltiplas abas;
- **0126–0127:** alternância entre abas e retorno ao checkout para validar a integridade dos elementos.

> ⚠️ **Importante observação:** os cenários cobrem **compatibilidade de navegação**, especialmente histórico, retorno, refresh, novas abas e múltiplas abas. Isso não equivale a **Cross-Browser**, pois não há cenários específicos utilizando Chrome, Edge, Firefox e Safari.

---

## 🖥️ Testes de Interface (UI)

**Exemplos:**

- **0001–0012:** controles de quantidade, tipos de ingresso e limites de seleção;
- **0028–0037:** mensagens e estados de validação dos campos de pagamento com cartão;
- **0040–0049:** mensagens e estados de validação dos campos do Cartão de Débito Virtual CAIXA;
- **0050–0061:** exibição das bandeiras dos cartões e comportamento visual relacionado ao código de segurança;
- **0062–0082:** campos de vencimento, nome, CPF, CNPJ e e-mail;
- **0083–0107:** campo de e-mail PIX, botão de pagamento, QR Code, chave PIX e mensagens de sucesso/erro;
- **0126–0127:** integridade dos elementos do checkout após alternância entre abas.

---

## ⚖️ Testes de Estabilidade

**Exemplos:**

- **0018:** múltiplos cliques no botão de compra para verificar ausência de pedidos duplicados;
- **0047–0049:** repetição de preenchimentos e validações no fluxo do Cartão de Débito Virtual CAIXA;
- **0093–0098:** múltiplas submissões, processamento do pagamento e reload durante o fluxo PIX;
- **0101:** múltiplos cliques consecutivos em "Copiar chave";
- **0107:** controle do desaparecimento automático do toast;
- **0110–0115:** refresh, hard refresh, múltiplas atualizações e abertura do checkout em nova aba;
- **0117–0125:** sincronização, expiração, múltiplas abas e múltiplas expirações do checkout;
- **0126–0127:** estabilidade e integridade dos elementos após alternância entre abas.

---

## 🔥 Testes de Estresse (Stress Testing)

A Feature apresenta cobertura de estresse principalmente por meio de **interações repetitivas, múltiplos cliques, submissões consecutivas, reloads e utilização simultânea de abas**.

**Exemplos:**

- **0007:** múltiplas tentativas de diminuir a quantidade de ingressos abaixo de zero;
- **0018:** múltiplos cliques no botão de compra para verificar criação de pedidos duplicados;
- **0047–0049:** repetição de tentativas e preenchimentos nos campos de pagamento;
- **0093–0095:** múltiplos cliques e submissões consecutivas durante o pagamento PIX;
- **0101:** múltiplos cliques consecutivos em "Copiar chave PIX";
- **0110:** atualização da página durante a etapa de pagamento;
- **0115:** múltiplas atualizações do checkout;
- **0120–0121:** utilização e expiração do checkout em múltiplas abas;
- **0125:** múltiplas expirações consecutivas do checkout;
- **0126–0127:** alternância repetida entre abas e validação da não duplicação de componentes.

> ⚠️ **Importante:** Esses cenários caracterizam testes de robustez e estresse de interação da aplicação. Eles não substituem testes de carga ou performance com múltiplos usuários reais, realizados por ferramentas especializadas de performance/load testing.

---

## 🛡️ Testes de Robustez

**Exemplos:**

- **0006–0007:** valores nos limites superior e inferior da quantidade de ingressos;
- **0018:** múltiplos cliques no processo de compra;
- **0028–0037:** dados inválidos ou ausentes nos campos de pagamento por cartão;
- **0040–0049:** dados inválidos ou ausentes nos campos do Cartão de Débito Virtual CAIXA;
- **0051, 0053, 0055:** números incompletos de cartões de diferentes bandeiras;
- **0057, 0059, 0061:** códigos de segurança inválidos;
- **0063–0064:** cartão expirado ou data de vencimento incompleta;
- **0065–0067:** entradas inválidas e caracteres especiais no nome do titular;
- **0069, 0071–0072:** CPF, CNPJ e e-mail inválidos;
- **0084–0091:** entradas inválidas, espaços, limite de caracteres, scripts e SQL Injection no e-mail PIX;
- **0093–0098:** múltiplas submissões e reload durante pagamento;
- **0112–0125:** expiração, refresh, logout e manipulação do checkout em diferentes estados.

---

## 🔎 Testes de Validação de Dados

**Exemplos:**

- **0006–0012:** validação da quantidade mínima e máxima de ingressos;
- **0013–0017:** validação de request, response, payload, valor total e correspondência entre UI e dados enviados;
- **0028–0037:** validação dos dados obrigatórios e inválidos do cartão de crédito;
- **0040–0049:** validação dos dados obrigatórios e inválidos do Cartão de Débito Virtual CAIXA;
- **0050–0064:** validação de bandeiras, números de cartão, CVV e vencimento;
- **0065–0082:** validação de nome, caracteres especiais, CPF, CNPJ e e-mail;
- **0083–0091:** validação do e-mail utilizado no pagamento PIX;
- **0099–0107:** validação das respostas e estados relacionados à geração e utilização do QR Code PIX;
- **0117–0125:** validação do contador, expiração e estado do checkout.

---

## 🔐 Testes de Segurança

A Feature possui cenários específicos destinados à validação de comportamentos relacionados à segurança do processo de compra e pagamento.

**Exemplos:**

- **0016:** validação dos headers de autenticação na requisição de compra;
- **0024:** tentativa de manipulação do valor durante o checkout;
- **0090:** validação contra utilização de scripts no campo de e-mail PIX;
- **0091:** validação contra SQL Injection no campo de e-mail PIX;
- **0105:** validação contra múltiplas cobranças PIX;
- **0118:** validação da persistência indevida do checkout após logout;
- **0121:** validação da expiração do checkout em múltiplas abas.

> ⚠️ **Importante observação:** Esses cenários demonstram **validações de segurança específicas**. Eles não representam uma auditoria completa de segurança, pentest ou avaliação abrangente de vulnerabilidades.

---

## 🔑 Testes de Integridade

**Exemplos:**

- **0013–0017:** comparação entre request, response, payload, valores e dados exibidos na interface;
- **0018:** validação da integridade do pedido diante de múltiplos cliques;
- **0019:** persistência dos ingressos selecionados após autenticação;
- **0021:** consistência do cálculo do valor total com a taxa de conveniência;
- **0022:** validação do estado da seleção após atualização da página;
- **0050–0061:** consistência das informações relacionadas às bandeiras e códigos de segurança dos cartões;
- **0102:** validação da correta renderização do QR Code PIX;
- **0104:** validação de unicidade do QR Code gerado para cada pagamento;
- **0105:** validação contra geração de múltiplas cobranças;
- **0117–0125:** consistência do estado do checkout durante sincronização, expiração, refresh e múltiplas abas;
- **0126–0127:** validação contra duplicação de botões e elementos do checkout.

---

## 🎨 Testes de Integridade Visual

**Exemplos:**

- **0050, 0052, 0054:** exibição das bandeiras Mastercard, Visa e American Express após identificação do cartão;
- **0102:** renderização correta do QR Code PIX;
- **0106:** validação do tempo estabelecido para disponibilização do QR Code;
- **0107:** desaparecimento automático do toast de confirmação;
- **0126–0127:** validação da integridade visual/estrutural dos elementos do checkout após alternância entre abas.

> **Observação:** a cobertura está relacionada à integridade dos elementos visuais especificamente exercitados pelos cenários. Não há evidência, nesta Feature, de uma suíte completa de validação visual, como comparação pixel a pixel ou validação de layout em diferentes resoluções.

---

## 🔃 Recuperação e Estado da Aplicação

**Exemplos:**

- **0022:** reset da seleção de ingressos após atualização da página;
- **0025:** reset do carrinho após falha de login;
- **0097–0098:** recuperação do checkout após reload durante pagamento PIX;
- **0108:** comportamento do checkout após logout depois da seleção dos ingressos;
- **0109:** retorno ao evento e novo acesso ao checkout;
- **0110:** atualização da página durante a etapa de pagamento;
- **0111:** persistência do pedido ao sair e retornar ao checkout;
- **0112–0113:** expiração do checkout e refresh próximo da expiração;
- **0115:** múltiplos reloads da página;
- **0116:** logout em outra aba durante o checkout;
- **0118:** validação da persistência do checkout após logout;
- **0119:** utilização do botão voltar durante o pagamento;
- **0121:** expiração simultânea do checkout em múltiplas abas;
- **0122:** persistência do subtotal após refresh;
- **0123:** criação de novo pedido após expiração do carrinho;
- **0124:** comportamento após hard refresh;
- **0125:** comportamento após múltiplas expirações consecutivas.

---

## 💾 Testes de Persistência de Estado

**Exemplos:**

- **0019:** persistência dos ingressos selecionados após login;
- **0022:** comportamento da seleção após atualização da página;
- **0025:** estado do carrinho após falha de autenticação;
- **0108–0111:** comportamento do pedido e checkout após logout, retorno ao evento e nova entrada no fluxo;
- **0111:** persistência do pedido ao sair e retornar ao checkout;
- **0117:** sincronização do contador do checkout;
- **0118:** validação de persistência indevida após logout;
- **0122:** persistência do subtotal após refresh;
- **0123:** criação de novo pedido após expiração do carrinho;
- **0124:** comportamento do estado após hard refresh.

---

## ⏱️ Testes relacionados a Tempo de Resposta

A Feature possui uma cobertura **pontual** relacionada ao tempo de processamento, concentrada no fluxo de geração do QR Code PIX.

**Exemplo:**

- **0106:** validação do tempo de 5 segundos para exibição do QR Code PIX.

> ⚠️ **Importante observação:** Esse cenário representa uma validação temporal específica do fluxo PIX. Não caracteriza, isoladamente, uma suíte completa de **Testes de Performance**, pois não há cenários abrangentes de throughput, latência, carga, concorrência de usuários ou consumo de recursos.

---

## 🔄 Compatibilidade de Navegação

A Feature apresenta cobertura de compatibilidade relacionada ao comportamento do fluxo quando o usuário utiliza diferentes mecanismos de navegação do navegador.

**Exemplos:**

- **0114:** abertura do checkout em uma nova aba;
- **0116:** logout realizado em outra aba durante o checkout;
- **0119:** utilização do botão voltar durante o pagamento;
- **0120:** abertura do mesmo checkout em múltiplas abas;
- **0121:** expiração do checkout em múltiplas abas simultaneamente;
- **0126–0127:** alternância entre abas e retorno ao checkout.

> ⚠️ **Importante observação:** A cobertura acima trata de **navegação, histórico e múltiplas abas**. Não foram identificados cenários específicos de **Cross-Browser**, portanto não é possível considerar Chrome, Edge, Firefox e Safari como cobertos por esta Feature.

---

## 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os **127 cenários** podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após alterações relacionadas a:

- fluxo de seleção e quantidade de ingressos;
- autenticação durante a compra;
- criação e processamento de pedidos;
- cálculo de valores e taxa de conveniência;
- checkout;
- pagamentos com cartão de crédito;
- pagamentos com Cartão de Débito Virtual CAIXA;
- pagamento via PIX;
- geração e exibição do QR Code;
- expiração de checkout;
- gerenciamento de sessão;
- comportamento após refresh;
- navegação entre abas;
- prevenção de pedidos ou cobranças duplicadas;
- validações de segurança;
- alterações nos componentes da página de pagamento.

### Exemplo de estratégia

```text
Alteração no sistema
        ↓
Execução dos testes relacionados
        ↓
Execução da suíte de regressão
        ↓
Comparação dos resultados
        ↓
Identificação de possíveis regressões
        ↓
RCA / Bug Report
```


## 📊 Matriz de cobertura da suíte

| Dimensão | Cenários principais | Cobertura |
| --- | --- | --- |
| **E2E** | 0001–0005, 0008–0017, 0026–0037, 0038–0049, 0083–0107, 0108–0125 | 🟢 |
| **Funcional** | 0001–0025, 0026–0082, 0083–0107, 0108–0127 | 🟢 |
| **Regressão** | 0001–0127 | 🟢 |
| **Navegação** | 0001–0005, 0008–0019, 0108–0111, 0114, 0116, 0119–0121, 0126–0127 | 🟢 |
| **UI** | 0001–0012, 0028–0037, 0040–0049, 0050–0061, 0062–0082, 0083–0107, 0126–0127 | 🟢 |
| **Responsividade** | — | 🔴 não coberta nesta feature |
| **Acessibilidade** | — | 🔴 não coberta nesta feature |
| **Performance** | 0106 | 🟡 cobertura pontual |
| **Estabilidade** | 0018, 0047–0049, 0093–0098, 0101, 0107, 0110–0115, 0117–0125, 0126–0127 | 🟢 |
| **Estresse** | 0007, 0018, 0047–0049, 0093–0095, 0101, 0110, 0115, 0120–0121, 0125–0127 | 🟢 |
| **Robustez** | 0006–0007, 0018, 0028–0037, 0040–0049, 0051, 0053, 0055, 0057, 0059, 0061, 0063–0064, 0065–0067, 0069, 0071–0072, 0084–0091, 0093–0098, 0112–0125 | 🟢 |
| **Validação de Dados** | 0006–0017, 0028–0037, 0040–0049, 0050–0064, 0065–0082, 0083–0091, 0099–0107, 0117–0125 | 🟢 |
| **Segurança** | 0016, 0024, 0090–0091, 0105, 0118, 0121 | 🟢 |
| **Integridade** | 0013–0019, 0021–0022, 0050–0061, 0102, 0104–0105, 0117–0125, 0126–0127 | 🟢 |
| **Compatibilidade de Navegação** | 0114, 0116, 0119–0121, 0126–0127 | 🟢 |
| **Monitoramento de Erros** | — | 🔴 não coberta nesta feature |
| **Integridade Visual** | 0050, 0052, 0054, 0102, 0106–0107, 0126–0127 | 🟡 cobertura pontual |
| **Recuperação/Estado** | 0022, 0025, 0097–0098, 0108–0111, 0112–0113, 0115–0116, 0118–0119, 0121–0125 | 🟢 |
| **Persistência de Estado** | 0019, 0022, 0025, 0108–0111, 0117–0118, 0122–0124 | 🟢 |
| **Tempo de Resposta** | 0106 | 🟡 cobertura pontual |
| **Cross-Browser** | — | 🔴 não coberta nesta feature |
| **Analytics** | — | 🔴 não coberta nesta feature |
| **SEO / Metadados** | — | 🔴 não coberta nesta feature |

### Legenda

| Indicador | Classificação |
| --- | --- |
| 🟢 | Cobertura claramente demonstrada pelos cenários analisados |
| 🟡 | Cobertura presente, porém pontual e passível de expansão |
| 🔴 | Não coberta pelos cenários desta feature (pode ser coberta em outra Feature, ex.: Acessibilidade/Responsividade já cobertas em outras áreas da suíte) |



> ⚠️ **Importante:** **Lacunas e limitações de cobertura**

Com base nos **127 cenários analisados** da Feature **Comprar Ingressos**, foram identificadas algumas lacunas de cobertura. Como os testes foram realizados em **ambiente de produção** e não houve acesso ao fluxo end-to-end completo da compra, a validação foi realizada somente até a **etapa de seleção da forma de pagamento**. Dessa forma, não foi possível executar cenários pós-compra, como **confirmação do pagamento, validação de dados bancários, pagamento via QR Code/PIX, recebimento do recibo por e-mail e geração do ingresso virtual**.

Além dessa limitação de fluxo, os 127 cenários analisados não apresentam cobertura explícita para **Responsividade, Acessibilidade, Cross-Browser, Monitoramento de Erros/Console, Contrato de Eventos de Analytics, SEO e Metadados**. Essas ausências representam **GAPs de cobertura da Feature**, e não necessariamente defeitos da aplicação.

A cobertura de **Performance/Tempo de Resposta** é pontual, com um cenário específico para validação do tempo de exibição do QR Code PIX, não caracterizando uma estratégia ampla de testes de performance. Da mesma forma, **Cross-Browser** permanece sem cobertura explícita, pois os cenários de múltiplas abas, Back, Refresh e navegação não demonstram execução em diferentes navegadores. Isso é diferente de **Compatibilidade de Navegação**, que está contemplada pelos cenários **0114, 0116, 0119–0121 e 0126–0127**.

Portanto, os GAPs identificados nos **127 cenários analisados** devem ser interpretados considerando tanto as limitações impostas pelo ambiente de produção quanto a ausência de acesso às etapas posteriores da jornada de compra.

---

## 👤 Feature Criar Conta

| Feature |
| ------------------------- |
| Feature_Criar Conta |
| 0001 - Na tela principal, clicar no botão 'Criar Conta' |
| 0002 - Acessar a página e tentar criar conta sem preencher nenhum campo |
| 0003 - Preencher apenas 'Nome' e tentar criar conta |
| 0004 - Preencher 'Nome' e 'CPF/CNPJ' e tentar criar conta |
| 0005 - Preencher 'Nome', 'CPF/CNPJ' e 'Email' e tentar criar conta |
| 0006 - Preencher 'Nome', 'CPF/CNPJ', 'Email' e 'Celular' e tentar criar conta |
| 0007 - Preencher 'Nome', 'CPF/CNPJ', 'Email', 'Celular' e 'Senha' sem clicar em 'Criar Conta' |
| 0008 - Preencher apenas 'CPF/CNPJ' e clicar em 'Criar Conta' |
| 0009 - Preencher apenas 'Email' e clicar em 'Criar Conta' |
| 0010 - Preencher apenas 'Celular' e clicar em 'Criar Conta' |
| 0011 - Preencher apenas 'Senha' e clicar em 'Criar Conta' |
| 0012 - Clicar no botão 'Entrar com Apple' |
| 0013 - Clicar no botão 'Entrar com Google' |
| 0014 - Clicar no checkbox 'Sou estrangeiro' (marcar e desmarcar) |
| 0015 - Clicar no checkbox 'Receber emails' (marcar e desmarcar) |
| 0016 - Interagir múltiplas vezes com os checkboxes 'Sou estrangeiro' e 'Receber emails' |
| 0017 - Validar comportamento do combobox de DDD com três cliques consecutivos |
| 0018 - Validar todos os DDDs/códigos de país disponíveis no combobox (varredura completa) |
| 0019 - Clicar no seletor de idioma (abrir dropdown 'BR') |
| 0020 - Selecionar o idioma 'Español' |
| 0021 - Selecionar o idioma 'English' |
| 0022 - Alterar idioma para Español e clicar em 'Recibir correos electrónicos' |
| 0023 - Alterar idioma para Español e clicar em 'Soy extranjero' |
| 0024 - Alterar idioma para English e clicar em 'Receive emails' |
| 0025 - Alterar idioma para English e clicar em 'I'm a foreigner' |
| 0026 - Clicar no botão 'Voltar' |
| 0027 - Alterar idioma para Español e clicar em 'Volver' |
| 0028 - Alterar idioma para English e clicar em 'Back' |
| 0029 - Clicar em 'Entrar' e acessar a tela de login |
| 0030 - Clicar em 'Entrar', acessar login, e retornar via 'Criar Conta' |
| 0031 - Idioma Español: clicar em 'Iniciar sesión' |
| 0032 - Idioma Español: 'Iniciar sesión' e depois 'Crear cuenta' |
| 0033 - Idioma English: clicar em 'Sign in' |
| 0034 - Idioma English: 'Sign in' e depois 'Create an Account' |
| 0035 - Validar persistência dos dados do formulário após refresh |
| 0036 - Validar persistência do idioma (English, Português, Español) após refresh |
| 0037 - Validar bloqueio de múltiplos cliques no botão 'Criar Conta' |
| 0038 - Validar campo de e-mail com formato inválido |
| 0039 - Validar campo CPF com quantidade inválida de dígitos |
| 0040 - Validar campo celular com quantidade inválida de números |
| 0041 - Validar senha com quantidade insuficiente de caracteres (1 a 5, varredura) |
| 0042 - Validar navegação utilizando a tecla TAB |
| 0043 - Validar envio do formulário utilizando a tecla ENTER |
| 0044 - Validar consistência dos placeholders após troca de idioma (PT/EN/ES) |
| 0045 - Validar consistência das mensagens de erro após troca de idioma (PT/EN/ES) |
| 0046 - Validar acesso direto à URL '/signup' |
| 0047 - Validar comportamento ao retornar utilizando o botão Voltar do navegador |
| 0048 - Validar múltiplas abas simultâneas na tela de cadastro |
| 0049 - Validar comportamento após múltiplos hard refresh consecutivos |
| 0050 - Validar ausência de quebra visual após troca de idioma |
| 0051 - Validar retorno seguro após cancelamento do login via Google |
| 0052 - Validar retorno seguro após cancelamento do login via Apple |
| **Total** | **52** |

Assim como nas Features anteriores, todos os testes foram classificados por dimensão, evitando tratar conceitos distintos como categorias equivalentes. Esta Feature introduz **uma dimensão específica de grande profundidade**, uma internacionalização e reutiliza a dimensão de Integração com Provedores Externos já vista na Publicar Eventos, mas aplicada a um fluxo diferente (cadastro, não login social completo).

### 📌 Dimensões de cobertura

| Dimensão | Categorias | Objetivo |
| --- | --- | --- |
| **Escopo** | E2E | Validar jornadas completas atravessando diferentes páginas e componentes |
| **Objetivo funcional** | Funcionais, Validação de Dados, Integridade | Verificar comportamentos esperados, dados apresentados e consistência das informações |
| **Qualidade da aplicação** | UI, Acessibilidade, Estabilidade, Robustez, Integridade Visual | Avaliar características de qualidade além das regras funcionais |
| **Condição / técnica de teste** | Estresse, Compatibilidade de Navegação | Exercitar a aplicação sob condições repetitivas ou diferentes formas de navegação |
| **Resiliência** | Monitoramento de Erros, Recuperação de Estado | Avaliar comportamento diante de erros, reloads e cancelamentos de fluxo |
| **Internacionalização (i18n)** | Labels, placeholders, mensagens de erro, persistência de idioma | Validar a consistência da aplicação em Português, English e Español — dimensão de maior profundidade nesta feature |
| **Integração com Provedores Externos** | SSO (Google/Apple) | Validar o início e o cancelamento seguro de fluxos de autenticação social |
| **Finalidade de execução** | Regressão | Reexecutar cenários existentes para identificar impactos de alterações no sistema |

---

## 🧪 Cobertura funcional e E2E

### Testes Funcionais

**Exemplos:**

* **0001–0011:** acesso à página e preenchimento progressivo dos campos do formulário;
* **0014–0016:** checkboxes de "Sou estrangeiro" e "Receber emails";
* **0017–0018:** combobox de código de país/DDD;
* **0019–0025:** seletor de idioma e seus reflexos nos checkboxes.

### Testes End-to-End (E2E)

**Exemplos:**

* **0001:** Home → Criar Conta;
* **0029–0030:** Criar Conta → Login → Criar Conta (ida e volta entre as duas telas de autenticação);
* **0031–0034:** troca de idioma → navegação para login → validação do texto do botão no idioma selecionado;
* **0051–0052:** início de OAuth (Google/Apple) → cancelamento → retorno garantido a `/signup`.

> **Observação:** assim como nas features de referência, E2E representa o **escopo da jornada**, não uma categoria isolada.

---

## 🗺️ Testes de Navegação

**Exemplos:**

* **0001, 0026–0034:** acesso à página, botão Voltar, e alternância entre Criar Conta e Login (nos três idiomas);
* **0046:** acesso direto via URL, sem passar pela Home;
* **0047:** navegação via botão Voltar do navegador.

---

## 🖥️ Testes de Interface (UI)

**Exemplos:**

* **0014–0016:** estado visual dos checkboxes (`data-state="checked"/"unchecked"`);
* **0017–0018:** abertura/fechamento do combobox de DDD e validação do atributo `aria-expanded`;
* **0019–0021:** menu dropdown de seleção de idioma.

---

## ♿ Testes de Acessibilidade

**Exemplos:**

* **0042:** navegação completa pelo formulário usando exclusivamente a tecla TAB, validando a ordem lógica de foco entre Nome → CPF/CNPJ → checkboxes;
* **0043:** envio do formulário usando a tecla ENTER como alternativa ao clique no botão.

---

## ⚖️ Testes de Estabilidade

**Exemplos:**

* **0037:** disparo de 5 cliques rápidos no botão de submit, validando que o sistema não gera múltiplas requisições (limite de 5 `requests` capturadas via interceptação de rede);
* **0048:** duas abas abertas simultaneamente na mesma tela, cada uma preenchida com dados diferentes, validando que uma não interfere na outra;
* **0049:** 5 ciclos de hard refresh (incluindo limpeza de cache, `localStorage` e `sessionStorage`) sem perda de funcionalidade da página.

---

## 🔥 Testes de Estresse (Stress Testing)

**Exemplos:**

* **0016:** múltiplos cliques alternados nos dois checkboxes em sequência;
* **0018:** varredura de mais de 200 códigos de país no combobox de DDD, um teste orientado a dados que cobre virtually a lista inteira de países disponíveis;
* **0037:** 5 cliques quase simultâneos no botão de submit;
* **0041:** 5 variações de senha inválida (1 a 5 caracteres) em loop, cada uma reiniciando o formulário;
* **0049:** 5 ciclos de hard refresh consecutivos.

> ⚠️ **Importante:** O cenário 0018 é o teste de maior volume de dados desta suíte — mais de 200 iterações sobre uma lista real de códigos de país, incluindo tratamento de erro e reabertura do dropdown caso a busca não responda de primeira.

---

## 🛡️ Testes de Robustez

**Exemplos:**

* **0002–0011:** todas as combinações de preenchimento parcial do formulário (só nome, nome+CPF, apenas CPF, apenas email, apenas celular, apenas senha);
* **0038:** e-mail sem `@` nem domínio válido, validado via `checkValidity()` do HTML5;
* **0039:** CPF com 9 dígitos (quantidade inválida);
* **0040:** celular com apenas 5 dígitos.

---

## 🔎 Testes de Validação de Dados

**Exemplos:**

* **0038–0041:** formato de e-mail, quantidade de dígitos do CPF, quantidade de dígitos do celular, e tamanho mínimo de senha;
* **0044:** correspondência exata entre o texto dos placeholders e o idioma selecionado (ex: "Nome" em PT, "Full name" em EN, "Nombre completo" em ES);
* **0045:** presença das palavras-chave de erro esperadas em cada idioma (`obrigatório`/`required`/`obligatorio`).

---

## 🔑 Testes de Integridade

**Exemplos:**

* **0035:** o formulário preserva os dados digitados após um refresh, **ou** os limpa completamente — o teste aceita ambos os comportamentos como válidos, mas falha explicitamente se o resultado for um estado **parcial** (inconsistente);
* **0036:** o idioma selecionado permanece o mesmo após refresh, testado em cadeia para os três idiomas (PT → EN → ES, cada troca seguida de reload);
* **0044–0045:** consistência de texto entre idiomas, sem "vazamento" de mensagens do idioma anterior no DOM.

---

## 🌐 Testes de Compatibilidade de Navegação

**Exemplos:**

* **0047:** botão Voltar do navegador, validando se o formulário mantém ou perde os dados (o teste documenta o comportamento atual sem presumir um resultado específico como certo ou errado);
* **0048:** duas abas do navegador abertas na mesma URL simultaneamente.

---

## 🚨 Testes de Monitoramento de Erros

**Exemplos:**

* **0037:** ausência de mensagens como "Too many requests" ou "Erro interno" mesmo sob cliques rápidos repetidos;
* **0040:** verificação (não bloqueante) da presença de uma mensagem textual explícita de celular inválido, registrando um alerta caso a mensagem não apareça, sem falhar o teste por esse motivo isolado.

---

## 🎨 Testes de Integridade Visual

**Exemplo:**

* **0050:** verificação de que o `body` da página mantém dimensões válidas (`width`/`height` positivos) após cada troca de idioma, nos três idiomas testados em sequência.

---

## 🔃 Recuperação e Estado da Aplicação

**Exemplos:**

* **0035:** estado do formulário após refresh;
* **0047:** estado do formulário após navegação para outra página e retorno via botão Voltar;
* **0049:** estabilidade da página após múltiplos hard refreshes com limpeza agressiva de cache.

---

## 🔌 Testes de Integração com Provedores Externos

**Exemplos:**

* **0012–0013:** início do fluxo de login social (Google e Apple), validando o redirecionamento para o domínio correto do provedor (`accounts.google.com`, `appleid.apple.com`);
* **0051–0052:** cancelamento do fluxo OAuth e retorno seguro à página `/signup`, validando que o formulário permanece acessível e funcional mesmo após uma tentativa de login social interrompida.

> ⚠️ **Importante:** Assim como observado na Feature Publicar Eventos, esta suíte trata o redirecionamento correto para o provedor externo como critério de sucesso sem tentar completar a autenticação de fato, já que isso está fora do controle da aplicação sob teste.

---

## 🌍 Testes de Internacionalização — i18n (dimensão de maior profundidade nesta feature)

Avaliam a consistência da aplicação em três idiomas — Português, English e Español — através de múltiplas camadas: rótulos de botões, checkboxes, placeholders de campos, mensagens de erro, e persistência da escolha de idioma.

**Exemplos:**

* **0019–0021:** seleção de cada idioma via dropdown;
* **0022–0025:** verificação de que os checkboxes ("Receber emails"/"Recibir correos electrónicos"/"Receive emails", "Sou estrangeiro"/"Soy extranjero"/"I'm a foreigner") respondem corretamente após a troca de idioma;
* **0027–0028, 0031–0034:** botões de navegação (Voltar/Volver/Back, Entrar/Iniciar sesión/Sign in) traduzidos corretamente e funcionais em cada idioma;
* **0036:** persistência do idioma escolhido através de três refreshes consecutivos, validando que o idioma **não volta ao padrão** a cada reload;
* **0044:** os placeholders dos campos mudam corretamente entre os três idiomas, incluindo a observação de que o campo "CPF/CNPJ" (`document`) pode não ser exibido nos idiomas EN/ES — um comportamento de negócio documentado, não assumido como erro;
* **0045:** as mensagens de erro de validação também mudam de idioma corretamente, com verificação cruzada para garantir que mensagens do idioma anterior não permaneçam visíveis no DOM.

> ⚠️ **Importante:**  Esta é, de longe, a dimensão mais elaborada da suíte: nenhuma outra Feature testa 3 idiomas em paralelo através de 4 camadas diferentes (rótulos, placeholders, mensagens de erro, persistência). O nível de detalhe aqui como a observação sobre o campo `document` desaparecer em outros idiomas é o tipo de achado que só aparece quando o teste é desenhado para **descobrir** comportamento, não apenas confirmar uma expectativa fixa.

---

# 🔁 Regressão

A **regressão não representa um conjunto separado de cenários**.

Os 52 cenários podem ser utilizados como uma **suíte de regressão automatizada**, especialmente após:

* alterações no formulário de cadastro ou em suas validações;
* alterações no fluxo de autenticação social (Google/Apple);
* alterações nos textos, traduções ou no sistema de internacionalização;
* alterações no combobox de código de país;
* mudanças na navegação entre Criar Conta e Login.

### Exemplo de estratégia

```text
Alteração no sistema
        ↓
Execução dos testes relacionados
        ↓
Execução da suíte de regressão
        ↓
Comparação dos resultados
        ↓
Identificação de regressões
        ↓
RCA / Bug Report
```

---

# 📊 Matriz de cobertura da suíte

| Dimensão | Cenários principais | Cobertura |
| --- | --- | --- |
| **E2E** | 0001, 0029–0034, 0051–0052 | 🟢 |
| **Funcional** | 0001–0025 | 🟢 |
| **Regressão** | 0001–0052 | 🟢 |
| **Navegação** | 0001, 0026–0034, 0046–0047 | 🟢 |
| **UI** | 0014–0021 | 🟢 |
| **Responsividade** | — | 🔴 não coberta nesta feature |
| **Acessibilidade** | 0042–0043 | 🟢 |
| **Performance** | — | 🔴 não coberta nesta feature |
| **Estabilidade** | 0037, 0048–0049 | 🟢 |
| **Estresse** | 0016, 0018, 0037, 0041, 0049 | 🟢 |
| **Robustez** | 0002–0011, 0038–0040 | 🟢 |
| **Validação de Dados** | 0038–0041, 0044–0045 | 🟢 |
| **Integridade** | 0035–0036, 0044–0045 | 🟢 |
| **Compatibilidade de Navegação** | 0047–0048 | 🟢 |
| **Monitoramento de Erros** | 0037, 0040 | 🟢 |
| **Integridade Visual** | 0050 | 🟡 |
| **Recuperação/Estado** | 0035, 0047, 0049 | 🟢 |
| **Integração com Provedores Externos** | 0012–0013, 0051–0052 | 🟢 |
| **Internacionalização (i18n)** | 0019–0025, 0027–0028, 0031–0034, 0036, 0044–0045, 0050 | 🟢 |

### Legenda

| Indicador | Classificação |
| --- | --- |
| 🟢 | Cobertura claramente demonstrada pelos cenários analisados |
| 🟡 | Cobertura presente, porém pontual e passível de expansão |
| 🔴 | Não coberta pelos cenários desta feature (pode ser coberta em outra Feature, ex.: Acessibilidade/Responsividade já cobertas em outras áreas da suíte) |


## 💡 Observações finais comparando com as outras Features

1. **Dimensão de internacionalização sem precedente nas demais Features**: nenhuma outra Feature da suíte testa 3 idiomas em paralelo com esse nível de profundidade — rótulos, placeholders, mensagens de erro e persistência são todos verificados cruzadamente, incluindo a checagem ativa de que texto do idioma anterior não "vaza" para o DOM após a troca.
2. **Tratamento maduro de OAuth reaproveitado da Publicar Eventos**: os cenários 0012, 0013, 0051 e 0052 seguem o mesmo padrão de boa prática já visto na outra feature — validar o redirecionamento correto para o provedor, sem tentar completar a autenticação de fato.
3. **Testes que documentam comportamento em vez de assumir um resultado fixo**: os cenários 0035 (persistência após refresh) e 0047 (estado após botão Voltar) aceitam mais de um resultado como válido, desde que o sistema não fique em um estado **inconsistente** — essa é uma abordagem mais madura de QA do que apenas afirmar "o campo deve estar vazio" ou "o campo deve estar preenchido" sem confirmar qual é o comportamento de negócio pretendido.
4. **Lacunas em relação às outras Features**: assim como a Publicar Eventos, esta Feature não cobre Responsividade nem Performance de forma dedicada — ambas já demonstradas em outras Features da suíte (Explorar Eventos e Suporte e Ajuda). O cenário 0050 toca em integridade visual, mas de forma pontual (dimensões do `body`), não substituindo testes de responsividade em múltiplos viewports.


---

# 🐞 Bugs Encontrados


Durante a execução e análise da suíte de testes, além da validação funcional, foram identificados os seguintes comportamentos inesperados na plataforma FasTix. Cada ocorrência foi analisada a partir do cenário correspondente, reproduzida durante a execução dos testes e documentada com seu respectivo comportamento atual, resultado esperado e evidência.

## 🔭 Feature Explorar Eventos

<img width="1906" height="902" alt="image" src="https://github.com/user-attachments/assets/d1fe12c9-b025-4cc3-944c-cdddf1369f31" />


| ID | Descrição | Severidade | Passos para reproduzir | Evidência (teste) |
| :--- | :--- | :---: | :--- | :--- |
| **BUG-01** | **Cenário:** Buscar um local (Ex: Fabrique Club) no campo de pesquisa (Botão: Explorar eventos) <br><br> **Dado** que o usuário esteja na HomePage <br> **Quando** pesquisar pelo nome de um local específico **(Ex: Fabrique Club)** <br> **Então** os eventos associados ao local correspondente devem ser exibidos | 🔺 **Alta** | Acessar a Home → clicar em **"Explorar eventos"** → acessar o campo de pesquisa → pesquisar por `"Fabrique"` ou `"Fabrique Club"` → verificar os resultados apresentados. | `Cenário 09` — Feature **Explorar Eventos** |


## 🎬 **Vídeo:**

https://github.com/user-attachments/assets/879cdbc9-53fe-4cdd-8a92-98698e1bc2e7

## 📸 **Print:**


* **01 - Ao pesquisar por: Fabrique, é retornado a mensagem: Nenhum evento encontrado:**
<img width="1185" height="635" alt="image" src="https://github.com/user-attachments/assets/171a1f8d-c30f-4d5f-ab58-74acdde421ee" />

* **02 - Ao pesquisar por: Fabrique Club, é retornado a mensagem: Nenhum evento encontrado:**
<img width="1193" height="652" alt="image" src="https://github.com/user-attachments/assets/19b43547-95ad-4dea-8d8d-0a1cd872dce9" />

## ❗**Resultado Esperado:**

O campo de busca acessado pelo botão **"Explorar Eventos"** deverá retornar todos os eventos associados ao local pesquisado. 
Por exemplo, ao pesquisar por **"Fabrique" ou "Fabrique Club"**, ambas as buscas devem exibir todos os eventos associados ao local pesquisado.
Exemplo de eventos cadastrados para o local, Fabrique:

<img width="552" height="226" alt="image" src="https://github.com/user-attachments/assets/dddc7c2b-2720-4b1e-9c9c-8d70ded8481e" />


## 🙋 **Feature Suporte e Ajuda**

<img width="1867" height="955" alt="image" src="https://github.com/user-attachments/assets/903b8614-cb01-4c57-b793-5297723280f6" />



| ID | Descrição | Severidade | Passos para reproduzir | Evidência (teste) |
| :--- | :--- | :---: | :--- | :--- |
| **BUG-02** | **Cenário:** Validar o limite máximo do campo "Nome" <br><br> **Dado** que o usuário acesse a página inicial da plataforma <br> **E** navegue para a página "Suporte e Ajuda" <br> **Quando** preencher o campo "Nome" com um texto superior ao limite permitido <br> **Então** o sistema deve limitar a quantidade de caracteres aceitos no campo <br> **E** o campo não deve aceitar todo o conteúdo informado <br> **E** o campo não deve permanecer vazio após o preenchimento <br> **E** o valor armazenado no campo deve corresponder exatamente ao texto original truncado no limite permitido | 🔸 **Média** | Acessar **"Suporte e Ajuda"** → localizar o campo **"Nome"** → inserir um texto contendo **937 caracteres** → verificar o comportamento e a quantidade de caracteres aceita pelo campo. | `Cenário 0036` — Feature **Suporte e Ajuda** |

## 🎬 **Vídeo:**

https://github.com/user-attachments/assets/2624ed2e-d91e-4006-9de9-52857f05e001


## 📸 **Print:**


* **01 - Visualizar o campo “NOME” no formulário disponível:**
<img width="1190" height="701" alt="image" src="https://github.com/user-attachments/assets/a7638912-5ba4-4c0f-aaf4-9f72df8e905e" />

* **02 - Preencher o campo com 937 caracteres:**
<img width="1187" height="713" alt="image" src="https://github.com/user-attachments/assets/5b8252e8-2bb7-46e2-8fa3-948ddbe74d4e" />


## 🤖 Resultado do teste automatizado:

<img width="1140" height="818" alt="image" src="https://github.com/user-attachments/assets/d38dcd3e-53cb-48ba-b110-3a47e8fe8527" />


## ❗**Resultado Esperado:**

O campo **"Nome"** deve possuir um limite máximo de caracteres, informar esse limite ao usuário e aceitar apenas a quantidade permitida, armazenando exatamente o conteúdo truncado até o limite definido. 


## 🎟️ Feature Comprar Ingressos

| ID | Descrição | Severidade | Passos para reproduzir | Evidência (teste) |
| :--- | :--- | :---: | :--- | :--- |
| **BUG-03** | **Cenário:** Validar o limite máximo do campo "Nome" <br><br> **Dado** que o usuário acesse a página inicial da plataforma <br> **E** navegue para a página "Suporte e Ajuda" <br> **Quando** preencher o campo "Nome" com um texto superior ao limite permitido <br> **Então** o sistema deve limitar a quantidade de caracteres aceitos no campo <br> **E** o campo não deve aceitar todo o conteúdo informado <br> **E** o campo não deve permanecer vazio após o preenchimento <br> **E** o valor armazenado no campo deve corresponder exatamente ao texto original truncado no limite permitido | 🔸 **Média** | Acessar um evento → selecionar ingressos → clicar em **"Comprar ingressos"** → realizar login → selecionar **PIX** → informar um e-mail com mais de 255 caracteres → clicar em **"Pagar"**. | `Cenário 000000089` — Feature **Comprar Ingressos** |

🎬 **Vídeo:**

https://github.com/user-attachments/assets/4c152e77-1b72-43fa-a587-7742e58f17d3

## 📸 **Print:**

* **01 - Ao acessar a opção de pagamento via PIX e selecionar o campo E-mail, foi possível inserir até 510 caracteres, ultrapassando o limite de 255 caracteres normalmente adotado para esse tipo de campo e amplamente utilizado em estruturas de armazenamento de dados (Padrão de caminhos de arquivos no Windows Explorer, campos de texto em bancos de dados (como VARCHAR) e registros de rede como DNS TXT):**

<img width="1151" height="647" alt="image" src="https://github.com/user-attachments/assets/a87ae6aa-3d26-4871-b6f9-356477d46c77" />

* **02 - Ao clicar no botão pagar o sistema exibe uma mensagem de “Formato inválido” e “Preencha todos os dados para continuar”:**

<img width="1151" height="612" alt="image" src="https://github.com/user-attachments/assets/901ead3f-ee7f-4f79-b20c-7b6e6ba8b731" />

<img width="1156" height="626" alt="image" src="https://github.com/user-attachments/assets/a59d23be-65d0-4887-a79d-8e453ff83960" />



## 🤖 Resultado do teste automatizado:

<img width="1021" height="901" alt="image" src="https://github.com/user-attachments/assets/60c25954-e404-4fd3-9f4b-3c92a39618eb" />



## ❗**Resultado Esperado:**

O sistema deve limitar o campo **E-mail** a 255 caracteres ou exibir uma mensagem informando que o limite foi excedido, orientando o usuário a ajustar o valor informado.


## 🎟️ Feature Comprar Ingressos

<img width="1896" height="852" alt="image" src="https://github.com/user-attachments/assets/d4a6af57-395f-47de-8826-3d0766c9e402" />


| ID | Descrição | Severidade | Passos para reproduzir | Evidência (teste) |
| :--- | :--- | :---: | :--- | :--- |
| **BUG-04** | **Cenário:** Evitar múltiplos toasts de notificações ao clicar repetidamente no botão "Copiar chave" <br><br> **Dado** que o usuário seleciona a opção PIX como forma de pagamento <br> **Quando** preenche o campo de e-mail e clica no botão "Pagar" <br> **Então** o sistema deve exibir o QR Code do PIX e o botão "Copiar chave" <br> **E** ao clicar repetidamente em "Copiar chave", o usuário deve conseguir copiar a chave PIX para a área de transferência <br> **E** mesmo com cliques repetidos, o sistema deve exibir apenas um toast de notificação no topo da tela com a mensagem: "Código PIX - Código copiado para a área de transferência!" | 🔹 **Baixa** | Acessar o pagamento via PIX → preencher o e-mail → clicar em **"Pagar"** → clicar repetidamente em **"Copiar chave"** → observar os toasts exibidos no topo da página. | `Cenário 0000000101` — Feature **Comprar Ingressos** |


🎬 **Vídeo:**

https://github.com/user-attachments/assets/f8dc679c-3dca-4553-a6b4-eebf7521e95b

## 📸 **Print:**

* **01 - Seleção da opção PIX realizada e preenchimento do campo E-mail:**

<img width="1150" height="607" alt="image" src="https://github.com/user-attachments/assets/d9a19ac5-314a-43c9-bcd0-b47fedc7411d" />

* **02 - Após o preenchimento das opções acima, clicar no botão “Pagar”**:

<img width="1152" height="615" alt="image" src="https://github.com/user-attachments/assets/5aec6fd0-cee7-4140-8e02-f724e244c761" />


* **03 - Na sequência vai ser exibido o botão “Copiar chave”:**

<img width="1151" height="625" alt="image" src="https://github.com/user-attachments/assets/97f29716-ea93-4904-a558-bd52c123bc30" />


* **04 - Ao clicar repetidamente no botão “Copiar chave” na parte superior da tela vão ser exibido vários toasts de notificações:**

<img width="1157" height="612" alt="image" src="https://github.com/user-attachments/assets/aea4d3b9-64e3-4748-a103-5f543c4b2d8c" />

* **05 - Ao colocar o cursor do mouse em cima do toast de notificação exibido, outros toasts de notificações vão ser exibidos na página:**
<img width="1155" height="612" alt="image" src="https://github.com/user-attachments/assets/e33ba8c0-7802-45b1-9ff5-5df1d9088e31" />


## 🤖 Resultado do teste automatizado:

<img width="1107" height="736" alt="image" src="https://github.com/user-attachments/assets/16c9486f-6932-4aad-9901-9c809d93ae3b" />

<img width="1152" height="552" alt="image" src="https://github.com/user-attachments/assets/80ce6baa-218e-4112-81ef-01dc85b0d47d" />


## ❗**Resultado Esperado:**

Ao clicar repetidamente no **botão "Copiar chave"**, o sistema deve exibir apenas um toast de notificação, impedindo a geração de notificações duplicadas e garantindo que apenas uma mensagem de confirmação seja apresentada ao usuário.


## 🎟️ Feature Comprar Ingressos

<img width="1896" height="852" alt="image" src="https://github.com/user-attachments/assets/d4a6af57-395f-47de-8826-3d0766c9e402" />


| ID | Descrição | Severidade | Passos para reproduzir | Evidência (teste) |
| :--- | :--- | :---: | :--- | :--- |
| **BUG-05** | **Cenário:** Garantir que elementos do checkout não sejam duplicados após alternar abas do navegador <br><br> **Dado** que o usuário acessa a página do evento "Buffalo Tom em São Paulo" <br> **E** seleciona 2 ingressos do tipo "Meia Solidária" <br> **E** avança para a compra dos ingressos <br> **E** realiza login com credenciais válidas <br> **E** é redirecionado para a página de checkout do pedido <br> **E** o checkout é carregado completamente com o Payment Brick do Mercado Pago <br> **E** existe um botão "Pagar" visível <br> **Quando** o sistema captura um snapshot da estrutura do DOM e dos erros de console <br> **E** o usuário permanece 15 segundos na página de checkout <br> **E** abre uma nova aba do navegador <br> **E** acessa o Google <br> **E** permanece 15 segundos na nova aba <br> **E** retorna para a aba do checkout <br> **Então** o usuário deve permanecer na página do pedido <br> **E** o checkout deve continuar carregado corretamente <br> **E** a quantidade de botões "Pagar" deve permanecer inalterada <br> **E** a quantidade de opções de pagamento deve permanecer inalterada <br> **E** a quantidade de containers do Payment Brick deve permanecer inalterada <br> **E** a quantidade de labels "Cartão de crédito" deve permanecer inalterada <br> **E** a quantidade de labels "Pix" deve permanecer inalterada <br> **E** não devem existir elementos duplicados no checkout após o retorno à aba <br> **E** não devem ser gerados novos erros de hidratação React (#418) após a alternância de abas <br> **E** não devem ser gerados novos erros relacionados ao Meta Pixel <br> **E** não devem ser gerados novos erros relacionados ao Payment Brick do Mercado Pago <br> **E** deve ser possível registrar evidências do estado do DOM antes e depois da alternância <br> **E** deve ser possível registrar capturas de tela do checkout antes e depois da alternância <br> **E** deve ser possível gerar um relatório comparativo das diferenças encontradas entre os snapshots | 🔺 **Alta** | Acessar a compra de ingressos → avançar até a etapa de pagamento → permanecer na página → abrir uma nova aba → permanecer alguns segundos → retornar à aba da compra → verificar se o modal foi duplicado → interagir com o segundo modal. | `Cenário 0000000127` — Feature **Comprar Ingressos** |


🎬 **Vídeo:**

https://github.com/user-attachments/assets/0ee197fe-a999-40ac-b5de-a743f692885c


## 📸 **Print:**

* **01 - Ao acessar a página de formas de pagamento, é exibido um modal contendo as opções de pagamento:**

<img width="1155" height="611" alt="image" src="https://github.com/user-attachments/assets/7a587b34-1e1e-4ac5-8004-e6d94a83305d" />


* **02 - Após acessar a página mencionada acima, abra uma nova aba no navegador:**

<img width="1155" height="651" alt="image" src="https://github.com/user-attachments/assets/99e4dabb-d89a-424b-96bf-e7e299fa309d" />

* **03 - Em seguida, retorne à página do evento que estava aberta anteriormente. Ao retornar, é possível observar que o modal com as formas de pagamento foi duplicado:**

<img width="1152" height="655" alt="image" src="https://github.com/user-attachments/assets/db8ef1c7-e7c1-40e7-b0ad-f8cc56f205fd" />


* **04 - Selecione a opção "Cartão de Crédito" no segundo modal exibido e clique no segundo botão "Pagar":**

<img width="1155" height="612" alt="image" src="https://github.com/user-attachments/assets/f50e1406-9708-4df2-8827-2ca66db36639" />


* **05 - Após esse clique, o sistema exibirá o seguinte erro: "Ocorreu um erro. Por favor, tente novamente mais tarde.":**

<img width="1158" height="615" alt="image" src="https://github.com/user-attachments/assets/9251b666-b484-4f9b-9d29-94b301cc892a" />


* **06 - Console, antes de clicar no botão “Pagar”:**

<img width="1157" height="647" alt="image" src="https://github.com/user-attachments/assets/95da1505-4f17-4de5-abd4-8a53df239c03" />

<img width="1157" height="551" alt="image" src="https://github.com/user-attachments/assets/d3408a5b-e76d-4626-9765-a82272681ded" />



* **07 - Sourcers, antes de clicar no botão "Pagar":**

<img width="1155" height="656" alt="image" src="https://github.com/user-attachments/assets/b96cf4a4-2929-4b31-9b58-833eb414d1f6" />


<img width="1125" height="868" alt="image" src="https://github.com/user-attachments/assets/9e4a0e67-496c-4237-afc0-3b45265f17e8" />


* **08 - Após clicar no botão “Pagar”, aparecerá a seguinte mensagem de erro: "Ocorreu um erro. Por favor, tente novamente mais tarde.":**

<img width="1158" height="555" alt="image" src="https://github.com/user-attachments/assets/28245b2c-cb96-4983-8ebc-82a34f157f14" />


* **09 - Atualização do Console após clicar no botão “Pagar”:**
<img width="1156" height="660" alt="image" src="https://github.com/user-attachments/assets/8924c1d1-1b31-4da0-8d54-7082c6bf92c4" />

<img width="1126" height="881" alt="image" src="https://github.com/user-attachments/assets/205a97d2-65b9-4fe9-b0b6-0472f2c0fd4e" />



## ❗**Resultado Esperado:**

Ao abrir a página com as opções de pagamento da FasTix e acessar uma nova aba, ao retornar à página de compra de ingressos anteriormente acessada, o modal com as opções de pagamento não deve ser duplicado.


## 📢 Feature Publicar Eventos

<img width="1892" height="965" alt="image" src="https://github.com/user-attachments/assets/bbdd21bf-7342-4fe3-ab4e-70d8e005caa0" />


| ID | Descrição | Severidade | Passos para reproduzir | Evidência (teste) |
| :--- | :--- | :---: | :--- | :--- |
| **BUG-06** | **Cenário:** Stress integrado - Perfis + Permissões por seção <br><br> **Dado** que o usuário acesse a plataforma FasTix <br> **E** realize login com uma conta de produtor <br> **E** acesse a criação de um novo evento <br> **E** navegue até "Gerenciar Equipes" <br> **E** crie uma nova equipe <br> **E** acesse o modal "Permissões de Acesso" <br> **Quando** alternar os perfis de acesso: <br> **E** "Agente" <br> **E** "Marketing" <br> **E** "Staff" <br> **E** "Acesso Total" <br> **E** para cada perfil realizar a alteração de permissões para as seções: <br> **E** "Visão Geral" <br> **E** "Vendas" <br> **E** "Lotes" <br> **E** "Política de Privacidade" <br> **E** "Agenda" <br> **E** "Integrações" <br> **E** "Repasses" <br> **E** "Dados do Evento" <br> **E** "Formulário" <br> **E** "FAQ" <br> **E** "Cupons" <br> **E** "Entradas" <br> **E** para cada seção alternar as permissões na ordem: <br> **E** "Somente Leitura" <br> **E** "Acesso Total" <br> **E** "Sem Acesso" <br> **E** "Acesso Total" <br> **E** repetir todo o fluxo para todos os perfis durante 2 ciclos consecutivos <br> **Então** o sistema deve aplicar corretamente todas as alterações de permissões <br> **E** não deve apresentar falhas de carregamento, travamentos ou perda de estado <br> **E** deve manter o modal de permissões funcional durante toda a execução <br> **E** todas as seções devem permanecer configuradas com a permissão "Acesso Total" ao final do teste | 🔸 **Média** | Acessar **Publicar Eventos** → criar/acessar um evento → acessar **"Gerenciar Equipes"** → abrir **"Permissões de Acesso"** → selecionar um template, como **"Marketing"** → alterar uma permissão de seção → verificar o valor exibido no campo **"Template"**. | `Cenário 000097` — Feature **Publicar Eventos** |


🎬 **Vídeo:**

https://github.com/user-attachments/assets/6b41a139-32b0-4bff-8afb-43816bd69253


## 📸 **Print:**

*  **01 - Clicar no campo “Templates”:**

<img width="1158" height="653" alt="image" src="https://github.com/user-attachments/assets/3a31a2c1-c1b1-46cc-8f2c-05dea0bae640" />


*  **02 - Visualizar todas as opções disponíveis: Agente, Marketing, Staff e Acesso Total:**

<img width="1146" height="613" alt="image" src="https://github.com/user-attachments/assets/d60593bf-0e6f-45a8-ab7c-3b2ec1f320e5" />


*  **03 - Selecionar a opção “Marketing”:**

<img width="1153" height="647" alt="image" src="https://github.com/user-attachments/assets/afbc6e02-07cc-4971-8cd3-bc570ef8b62a" />

 
*  **04 - Acessar o painel "Permissões de Acesso", localizar a seção "Visão Geral" e selecionar a opção "Acesso Total", verificar que a opção "Marketing", exibida no lado direito do modal, permanece selecionada após a alteração da permissão:**

<img width="1151" height="647" alt="image" src="https://github.com/user-attachments/assets/33f32b6f-9faa-4587-a405-b73d5bdb6e35" />


* **05 - Ao alterar a permissão da seção "Visão Geral" para "Acesso Total", a opção "Marketing", previamente selecionada no campo "Template", foi substituída por "Templates", não preservando a seleção realizada:**

<img width="1153" height="647" alt="image" src="https://github.com/user-attachments/assets/40bf353e-de6c-408c-a43d-a1bd60091492" />


## ❗**Resultado Esperado:**

Ao selecionar o template "Marketing" no modal "Permissões de Acesso" e alterar a permissão da seção "Visão Geral" para "Acesso Total", o template previamente selecionado deve permanecer visível e selecionado no campo "Template", preservando a configuração definida pelo usuário durante toda a edição das permissões.
O valor do template selecionado deve ser mantido, sem que a seleção seja perdida após qualquer alteração nas permissões. Esse comportamento deve ocorrer independentemente do template escolhido.


## 🏠 Feature Tela Inicial

<img width="1152" height="683" alt="image" src="https://github.com/user-attachments/assets/4702da6d-3b9b-4ae4-b71f-d74ca34b3bd6" />


| ID | Descrição | Severidade | Passos para reproduzir | Evidência (teste) |
| :--- | :--- | :---: | :--- | :--- |
| **ISSUE-07** | **Cenário:** Clicar no ícone do Twitter no footer (Ícone desatualizado) <br><br> **Dado** que o usuário esteja na página inicial <br> **Quando** navegar até o footer da página <br> **E** clicar no ícone do Twitter (ícone desatualizado) situado no lado direito da página <br> **Então** o usuário deve ser redirecionado para a página oficial da FasTix no X | 🔹 **Baixa** | Acessar a página → rolar até o rodapé (*footer*) → localizar o ícone do Twitter na seção de redes sociais → verificar a imagem do ícone exibido. | `Cenário 00028` — Feature **Vídeo** |

🎬 **Vídeo:**

https://github.com/user-attachments/assets/72b551e7-ced7-49f5-9f4d-930eee71736e

## 📸 **Print:**

*  **01 - Ao acessar o footer e clicar no ícone do Twitter (ícone desatualizado):**
<img width="1151" height="612" alt="image" src="https://github.com/user-attachments/assets/5046973c-64fb-4341-8090-2fe783ce0e24" />


*  **02 - É realizado o redirecionamento automático para a página oficial da FasTix no X:**

<img width="1153" height="620" alt="image" src="https://github.com/user-attachments/assets/be1973f8-8b62-4bc8-9937-1e3926ea01b2" />

## ❗**Resultado Esperado:**

O ícone do Twitter exibido no footer encontra-se desatualizado e deve ser substituído pelo ícone oficial atual da plataforma X. 
---

### ⚠️ Observação

```text
Os bugs acima foram identificados a partir da execução e análise dos cenários de teste correspondentes. As severidades foram atribuídas considerando o impacto funcional observado em cada ocorrência.

BUG-01, BUG-03 e BUG-05 apresentam impacto diretamente relacionado à execução de jornadas importantes da plataforma, como pesquisa de eventos e checkout, enquanto os demais representam limitações de validação, inconsistências de interface ou perda de configuração.

O BUG-05 possui comportamento intermitente quanto ao momento exato de reprodução. Conforme observado no cenário, não existe um intervalo fixo para que o problema ocorra: em determinadas execuções o comportamento é reproduzido rapidamente, enquanto em outras pode ser necessário repetir o fluxo de alternância entre abas.

O BUG-06 também apresenta impacto sobre a configuração de permissões, uma vez que a alteração de uma permissão pode fazer com que o template previamente selecionado deixe de ser preservado.

As informações utilizadas neste documento foram mantidas de acordo com os cenários, resultados atuais e resultados esperados apresentados nos testes analisados.

A ISSUE-07, é relacionado ao link do rodapé que redireciona corretamente para o perfil no X, mas exibe a logo desatualizada do Twitter.

O comportamento esperado é de substituir o ícone antigo do Twitter pela nova logomarca do X no site da FasTix.

```
---

## 🔗 Bug × Feature × Causa Raiz

| Bug    | Feature           | Severidade | Causa Raiz                                                                     |
| ------ | ----------------- | ---------- | ------------------------------------------------------------------------------ |
| BUG-01 | Explorar Eventos  | Alta       | Falha na normalização e/ou filtragem da busca por local                        |
| BUG-02 | Suporte e Ajuda   | Média      | Ausência ou falha na validação do limite máximo de caracteres                  |
| BUG-03 | Comprar Ingressos | Média      | Ausência de validação do limite máximo do campo E-mail                         |
| BUG-04 | Comprar Ingressos | Baixa      | Falha no controle/deduplicação das notificações Toast                          |
| BUG-05 | Comprar Ingressos | Alta       | Falha na preservação do estado do checkout após alternância de abas            |
| BUG-06 | Publicar Eventos  | Média      | Falha na persistência do estado do template durante a alteração das permissões |

Essa visão consolidada evidencia que **a Feature Comprar Ingressos concentra três dos seis bugs identificados**, sendo também a única Feature com mais de uma ocorrência no conjunto analisado. Os demais bugs estão distribuídos entre **Explorar Eventos, Suporte e Ajuda e Publicar Eventos**.

Em relação às causas raiz, os problemas estão associados principalmente a **validação de dados, gerenciamento de estado e controle de componentes da interface**. O BUG-02 e o BUG-03 apresentam um padrão relacionado à ausência ou insuficiência de validação de limites de entrada, enquanto o BUG-05 e o BUG-06 envolvem problemas relacionados à preservação do estado da aplicação.

### 🛎️ Conclusão

A análise demonstra que os bugs não estão concentrados exclusivamente em problemas visuais. O conjunto apresenta diferentes padrões técnicos, envolvendo **processamento de dados de busca, validação de entradas, gerenciamento de notificações e persistência de estado**.

A Feature **Comprar Ingressos** merece atenção especial na análise de RCA por concentrar **três ocorrências distintas**, incluindo um problema relacionado ao estado do checkout após alternância de abas. Já os BUG-02 e BUG-03 indicam uma oportunidade de fortalecer as validações de limites de entrada em diferentes pontos da plataforma.

> **Nota de RCA:** As causas apresentadas neste board representam a **causa raiz provável/inferida a partir dos comportamentos observados nos cenários de teste**. A confirmação da causa raiz técnica exigiria análise do código, logs, arquitetura ou evidências adicionais de implementação.


---

## 📊 Análise da Suíte de Testes


### 📈 Distribuição de Bugs por Feature

<img width="1781" height="1060" alt="bugs_por_feature_fastix" src="https://github.com/user-attachments/assets/b4d8f1d7-b661-498f-b556-4a8ea2442196" />


### 📈 Análise Bugs por Feature

O gráfico apresenta **6 bugs encontrados**, distribuídos entre quatro Features da plataforma FasTix.

```text
A maior concentração está em Comprar Ingressos (3 bugs — 50,0%), enquanto Explorar Eventos,
Suporte e Ajuda e Publicar Eventos possuem 1 bug cada (16,7% cada).
```

A Feature **Comprar Ingressos** concentra metade dos bugs identificados no conjunto analisado. Os três problemas estão relacionados a diferentes comportamentos do checkout: limite de caracteres no campo E-mail durante o pagamento via PIX, geração duplicada de notificações ao copiar a chave PIX e duplicação do modal de pagamento após alternância de abas.

```text
Comprar Ingressos:  3 bugs — 50,0%
Explorar Eventos:   1 bug  — 16,7%
Suporte e Ajuda:    1 bug  — 16,7%
Publicar Eventos:   1 bug  — 16,7%
```

Essa distribuição demonstra que **Comprar Ingressos foi a Feature com maior concentração de problemas dentro do conjunto de bugs analisado.** Entretanto, esse dado não deve ser interpretado isoladamente como prova de que a Feature apresenta maior taxa de defeitos, pois não temos, neste conjunto, a quantidade total de testes executados em cada Feature.

**Do ponto de vista de Root Cause Analysis, a quantidade de bugs por Feature representa a concentração dos achados identificados dentro do escopo analisado, e não necessariamente a qualidade absoluta de cada Feature.**

A análise também mostra que os problemas encontrados possuem naturezas diferentes: falhas de validação de entrada, problemas de gerenciamento/preservação de estado, duplicação de componentes/notificações e comportamento incorreto de busca.

### 📈 Conclusão

A distribuição evidencia uma concentração de **50,0% dos bugs na Feature Comprar Ingressos**, enquanto os demais problemas estão distribuídos entre diferentes pontos da jornada da plataforma.

Para uma análise quantitativa mais completa, seria necessário relacionar **quantidade total de testes executados por Feature × bugs encontrados × severidade × causa raiz**, permitindo calcular, por exemplo, a concentração de bugs em relação ao esforço de teste.

---

### 📈 Bugs por Severidade

<img width="1522" height="902" alt="Bugs_por_Severidade_ATUALIZADO" src="https://github.com/user-attachments/assets/580a3af0-e3c8-4915-aabe-17a38c3fca22" />



### 📈 Análise Bugs Encontrados por Severidade

O gráfico apresenta **6 bugs encontrados**, distribuídos em três níveis de severidade:

```text
Média: 3 bugs — 50%
Alta: 2 bugs — 33,3%
Baixa: 1 bug — 16,7%
```

**A maior concentração está na categoria Média, responsável por metade dos bugs identificados. Outros 33,3% foram classificados como Alta e 16,7% como Baixa.**

Os dois bugs classificados como **Alta** estão relacionados a jornadas relevantes da plataforma:

```text
BUG-01 — Falha na busca de eventos por local — Explorar Eventos
BUG-05 — Duplicação do modal de pagamento após alternância de abas — Comprar Ingressos
```

O BUG-01 impede que uma busca por um local com eventos associados apresente os resultados esperados. O cenário registra que tanto "Fabrique" quanto "Fabrique Club" retornam **"Nenhum evento encontrado".**

O BUG-05 apresenta um comportamento mais complexo, relacionado à duplicação do modal de pagamento após a alternância entre abas do navegador. O cenário também registra evidências de DOM, Console e comportamento do Payment Brick, além da ocorrência da mensagem de erro após a interação com o segundo modal.

Os três bugs classificados como **Média** estão relacionados a:

```text
BUG-02 — Limitação/validação do campo Nome — Suporte e Ajuda
BUG-03 — Limite de caracteres do E-mail no PIX — Comprar Ingressos
BUG-06 — Perda da seleção do Template ao alterar permissões — Publicar Eventos
```

Já o **BUG-04**, classificado como Baixa, está relacionado à geração de múltiplos toasts ao clicar repetidamente em **"Copiar chave"** durante o pagamento via PIX.

Sob a perspectiva de Root Cause Analysis, os problemas não apresentam uma única origem aparente. Os cenários apontam para diferentes áreas de investigação:

```text
Validação de dados          → BUG-01, BUG-02 e BUG-03
Gerenciamento de estado     → BUG-05 e BUG-06
Controle de componentes     → BUG-04
```

> ⚠️ **Importante:** É importante destacar que essas classificações representam **causas raiz prováveis/inferidas a partir dos comportamentos observados**, e não causas técnicas definitivamente comprovadas. A confirmação exigiria análise de código, logs, arquitetura ou evidências adicionais de implementação.

### 📈 Conclusão

**Dos 6 bugs identificados, 5 estão nas categorias Alta ou Média (83,3%), enquanto 1 está classificado como Baixa (16,7%).**

O resultado demonstra que a suíte foi capaz de identificar problemas que ultrapassam inconsistências puramente visuais, abrangendo **busca, validação de dados, checkout, gerenciamento de estado, permissões e comportamento de componentes da interface.**

A distribuição de severidade deve, entretanto, ser interpretada em conjunto com **impacto, frequência, alcance, possibilidade de reprodução e criticidade da jornada afetada**, e não apenas pela quantidade de ocorrências.

---

### Análise Relação entre os dois gráficos

Os gráficos, analisados em conjunto, mostram duas dimensões diferentes dos achados:

```text
Gráfico Bugs por Feature    → Onde os bugs foram concentrados.
Gráfico Bugs por Severidade → Qual foi o perfil de severidade dos problemas encontrados.
```

A análise conjunta demonstra que **Comprar Ingressos concentra 50,0% dos bugs identificados**, e dois desses três problemas estão relacionados a comportamentos do fluxo de pagamento. Entretanto, não é possível concluir que essa Feature possua a maior taxa de defeitos da plataforma, pois não foi fornecida a quantidade total de testes executados em cada Feature para estabelecer uma relação entre **bugs encontrados e cobertura de testes.**

O conjunto analisado também demonstra que a severidade não está necessariamente relacionada à quantidade de bugs de uma Feature. Por exemplo, Comprar Ingressos possui três ocorrências distribuídas entre as três categorias de severidade: **1 Alta, 1 Média e 1 Baixa**, enquanto Explorar Eventos possui uma única ocorrência, classificada como **Alta**. Ou seja, a feature com mais bugs não é necessariamente a que concentra os problemas de maior impacto.

Dessa maneira, a quantidade de bugs deve ser analisada conjuntamente com a severidade e a causa raiz. O board **Bug × Feature × Causa Raiz** complementa essa visão ao demonstrar que os problemas estão associados principalmente a padrões relacionados a **validação de dados, gerenciamento de estado e controle de componentes da interface.**

Para uma análise de causa raiz mais completa, o próximo passo seria cruzar os dados em uma matriz:

```text
Feature × Testes Executados × Bugs × Severidade × Causa Raiz × Impacto
```

Esse cruzamento permitiria identificar não apenas onde os bugs foram encontrados, mas também **onde existe maior concentração de problemas em relação ao esforço de teste**, reduzindo o risco de conclusões baseadas exclusivamente na quantidade absoluta de bugs.


---


## 🕵🏻‍♂️ Root Cause Analysis (RCA)

Os **6 bugs documentados na suíte** apresentam diferentes padrões de comportamento e podem ser agrupados em **3 causas raiz prováveis**, cada uma indicando uma possível lacuna em validação de entrada, gerenciamento de estado ou controle de componentes da interface.

A análise abaixo foi construída a partir dos comportamentos observados nos cenários de teste. Como não houve acesso ao código-fonte, arquitetura ou logs completos da aplicação, as causas apresentadas devem ser tratadas como **hipóteses de causa raiz**, e não como causas técnicas definitivamente confirmadas.

### 🫆 Causa Raiz 1: Validação de entrada

<img width="1530" height="907" alt="Distribuicao_de_Bugs_por_Causa_Raiz_ATUALIZADO" src="https://github.com/user-attachments/assets/bf6fc9e8-a574-4978-b31f-85d41c96926c" />


* **Validação de entrada:** concentra o maior número de ocorrências (**3 bugs: BUG-01, BUG-02 e BUG-03**).

**Lógica de busca e matching:** concentra **1 bug (BUG-01)** — 16,7% dos achados. O **BUG-01** apresenta comportamento inconsistente na pesquisa de eventos por local: ao pesquisar por "Fabrique" ou "Fabrique Club", o sistema retorna **"Nenhum evento encontrado"**, apesar da existência de eventos associados ao local. A causa raiz inferida está no algoritmo de busca e matching, que não encontra correspondência entre o termo pesquisado e os registros existentes.

**Validação de entrada:** concentra **2 bugs (BUG-02 e BUG-03**) — 33,3% dos achados. **O BUG-02** está relacionado ao comportamento do campo **"Nome"** diante de uma entrada superior ao limite esperado de caracteres, indicando uma possível ausência ou insuficiência de validação do tamanho máximo permitido.

**O BUG-03** apresenta comportamento semelhante no campo E-mail do pagamento via PIX, permitindo a inserção de até **510 caracteres**, acima do limite esperado de 255 caracteres. Os dois problemas possuem em comum o tratamento inadequado ou insuficiente de entradas fornecidas pelo usuário. Entretanto, **não é possível afirmar, apenas pelos testes, se a falha está localizada no frontend, backend, camada de validação ou combinação dessas camadas.** Essa é a causa raiz provável com maior número de ocorrências dentro do conjunto analisado, empatada com **Gerenciamento de estado**, representando **33,3% dos bugs identificados** cada.

* Os três problemas possuem em comum o tratamento inadequado ou insuficiente de entradas fornecidas pelo usuário. Entretanto, **não é possível afirmar, apenas pelos testes, se a falha está localizada no frontend, backend, camada de validação ou combinação dessas camadas**.

**Gerenciamento de estado:** concentra **2 bugs (BUG-05 e BUG-06)** — 33,3% dos achados.
**Controle de componentes:** concentra **1 bug (BUG-04)** — 16,7% dos achados.

### 🫆 Causa Raiz 2: Gerenciamento e preservação de estado 

<img width="1550" height="889" alt="Gráfico_RCA_Relação_Causa_Raiz_Bugs_ATUALIZADO" src="https://github.com/user-attachments/assets/fd079ccb-4130-47cc-b488-04be8caf6d5b" />

****Gerenciamento de estado:** agrupa BUG-05 e BUG-06,** ambos relacionados à perda, duplicação ou alteração inesperada de informações previamente selecionadas pelo usuário.

No **BUG-05,** após a alternância entre abas do navegador, o sistema pode apresentar duplicação do modal de pagamento, incluindo opções e botões de pagamento. O cenário também registra a ocorrência de mensagem de erro após a interação com o segundo modal.

No **BUG-06,** a seleção realizada no campo "Template" não é preservada quando uma permissão de seção é alterada. O valor previamente selecionado pode ser substituído por "Templates".

Embora os dois comportamentos sejam diferentes, ambos apresentam indícios de problemas relacionados à manutenção do estado da interface durante mudanças de contexto ou interação.

No caso do BUG-05, existem evidências adicionais de comportamento relacionado ao DOM, console e componentes do fluxo de pagamento. Essas evidências ajudam a direcionar a investigação, mas não comprovam isoladamente qual componente ou camada é responsável pela causa raiz.

```text
⚠️ Causas inferidas a partir dos comportamentos observados. A confirmação técnica requer análise de código, logs ou arquitetura pelo time de desenvolvimento.
```

### 🫆 Causa Raiz 3: Controle de componentes e notificações (FAZENDO...)

* **Controle de componentes e notificações:** está associado ao **BUG-04**, relacionado à geração de múltiplos Toasts ao clicar repetidamente no botão **"Copiar chave"** durante o pagamento via PIX.

* O comportamento indica que cada interação dispara uma nova notificação sem que exista, aparentemente, um mecanismo adequado de controle, deduplicação ou bloqueio de chamadas repetidas.

* Diferentemente de uma simples inconsistência visual, o comportamento sugere uma possível oportunidade de melhoria no gerenciamento do ciclo de vida do componente de notificação ou no tratamento de interações repetitivas.

* Entretanto, novamente, o cenário de teste **não permite determinar se a origem está no componente Toast, no handler do botão, na camada de estado ou na lógica que dispara a notificação**.

Essa causa representa **1 dos 6 bugs identificados (16,7%)**.

### 📊 Distribuição das causas raiz

```text
Validação de entrada          → 3 bugs — 50%
Gerenciamento de estado       → 2 bugs — 33,3%
Controle de componentes       → 1 bug  — 16,7%
```

A distribuição demonstra que **a maior concentração de ocorrências está relacionada ao tratamento de entradas do usuário**, seguida por problemas associados ao gerenciamento de estado.

### 🫆 Conclusão

* Das três causas raiz prováveis identificadas, **a Validação de entrada** concentra a maior quantidade de ocorrências, reunindo BUG-01, BUG-02 e BUG-03. Os problemas apresentam comportamentos distintos, mas possuem em comum a necessidade de tratamento mais consistente das informações fornecidas pelo usuário.

* O **Gerenciamento e preservação de estado** aparece como o segundo agrupamento, reunindo BUG-05 e BUG-06. Ambos apresentam comportamentos de perda, duplicação ou substituição inesperada de informações durante mudanças de contexto ou interação.

* Já o **Controle de componentes e notificações** está associado exclusivamente ao BUG-04, relacionado à geração repetida de Toasts durante interações consecutivas.

* Diferentemente de uma RCA baseada exclusivamente em sintomas, essa análise permite identificar **padrões que podem atingir diferentes partes da aplicação**. Por exemplo, problemas de validação aparecem em Features distintas, enquanto problemas de estado também aparecem em contextos diferentes.

* **Nenhuma das três causas deve ser considerada tecnicamente confirmada apenas com base nos testes funcionais.** Para transformar essas hipóteses em uma RCA definitiva, seria necessário complementar a investigação com código-fonte, logs, arquitetura, traces, comportamento das APIs e análise do fluxo de estado da aplicação.

> ⚠️ **Importante:** Dessa maneira, a análise evita tratar cada bug como um caso isolado e direciona a investigação para **padrões sistêmicos de validação, gerenciamento de estado e controle de componentes**, mantendo a distinção entre **comportamento observado, hipótese de causa e causa raiz tecnicamente comprovada**.

---

## 🔗 Bug × Feature × Causa Raiz

| Bug | Feature | Severidade | Causa Raiz |
|---|---|---|---|
| BUG-01 | Explorar Eventos | Alta | Validação de entrada — falha na normalização e/ou filtragem da busca por local |
| BUG-02 | Suporte e Ajuda | Média | Validação de entrada — ausência ou falha na validação do limite máximo de caracteres |
| BUG-03 | Comprar Ingressos | Média | Validação de entrada — ausência de validação do limite máximo do campo E-mail |
| BUG-04 | Comprar Ingressos | Baixa | Controle de componentes — falha no controle/deduplicação das notificações Toast |
| BUG-05 | Comprar Ingressos | Alta | Gerenciamento de estado — falha na preservação do estado do checkout após alternância de abas |
| BUG-06 | Publicar Eventos | Média | Gerenciamento de estado — falha na persistência do estado do template durante a alteração das permissões |

Essa visão consolidada evidencia que **a Feature Comprar Ingressos concentra três dos seis bugs identificados (50%)**, sendo a única Feature com mais de uma ocorrência no conjunto analisado. Os demais bugs estão distribuídos individualmente entre **Explorar Eventos, Suporte e Ajuda e Publicar Eventos**.

Em relação às causas raiz, diferente do exemplo de referência (onde a mesma causa atravessava múltiplas Features), aqui **cada causa raiz está associada a um padrão técnico distinto**: validação de entrada, gerenciamento de estado e controle de componentes. Os BUG-02 e BUG-03 apresentam um padrão comum de ausência de validação de limites, enquanto BUG-05 e BUG-06 envolvem problemas de preservação de estado em contextos diferentes da aplicação.

> **Nota de RCA:** As causas raiz apresentadas representam a **hipótese provável inferida a partir dos comportamentos observados nos cenários de teste**. A confirmação técnica exigiria análise de código-fonte, logs, arquitetura e traces da aplicação.

---

## 📊 Análise da Suíte de Testes

### 📈 Distribuição de Bugs por Feature

O gráfico apresenta **6 bugs encontrados**, distribuídos entre quatro Features da plataforma FasTix:

```text
Explorar Eventos:   1 bug  — 17%
Suporte e Ajuda:    1 bug  — 17%
Comprar Ingressos:  3 bugs — 50%
Publicar Eventos:   1 bug  — 17%
```

A Feature **Comprar Ingressos** concentra metade dos bugs identificados. Os três problemas estão relacionados a comportamentos distintos do checkout: limite de caracteres no campo E-mail durante o pagamento via PIX, geração duplicada de notificações ao copiar a chave PIX e duplicação do modal de pagamento após alternância de abas.

**Do ponto de vista de Root Cause Analysis, a quantidade de bugs por Feature representa a concentração dos achados dentro do escopo analisado — não a qualidade absoluta de cada Feature.** A ausência de bugs nas demais Features (Tela Inicial, Criar Conta) indica o escopo dos cenários executados, não necessariamente a ausência de defeitos nessas áreas.

### 📈 Conclusão

A análise demonstra que os bugs não estão concentrados exclusivamente em problemas visuais nem em uma única camada da aplicação. O conjunto apresenta diferentes padrões técnicos envolvendo **processamento de dados de busca, validação de entradas, gerenciamento de notificações e preservação de estado**, confirmando o que a análise de causa raiz já havia sinalizado.

A Feature **Comprar Ingressos** merece atenção especial na evolução da cobertura de testes, por concentrar **três ocorrências distintas** incluindo um problema de alta severidade relacionado ao estado do checkout após alternância de abas (BUG-05). Já os BUG-02 e BUG-03 indicam uma oportunidade transversal de fortalecer as validações de limites de entrada em diferentes pontos da plataforma, independentemente da Feature onde se manifestam.

---

### 💭 Análise da Relação entre os Gráficos

Os gráficos, analisados em conjunto, expõem duas dimensões complementares da estratégia de testes:

```text
Gráfico Bugs por Feature   → Onde os problemas foram encontrados.
Análise de Causa Raiz      → Qual o padrão técnico subjacente a cada ocorrência.
```

Não é correto concluir que uma Feature é mais problemática apenas por concentrar mais bugs — especialmente sem conhecer o total de testes executados por Feature nem o contexto de produção real da plataforma. Para uma análise mais completa, o próximo passo seria construir uma **matriz Feature × quantidade de bugs × severidade × causa raiz**, cruzando também fatores como impacto ao usuário, frequência de reprodução e alcance. Esse cruzamento permitiria identificar onde há maior concentração de risco na aplicação, evitando conclusões baseadas exclusivamente na contagem de ocorrências.


---

## 🧪 Metodologia de teste

A construção da suíte seguiu um processo iterativo, combinando técnicas formais de design de testes com investigação exploratória sempre que o comportamento da plataforma não estava documentado previamente. A aplicação das técnicas não foi uniforme entre as Features: cada área recebeu o conjunto de abordagens mais relevante para o risco que representa — um formulário de checkout exige rigor diferente de uma página institucional de suporte.

**Particionamento de equivalência e análise de valor-limite** foram aplicados de forma sistemática em diferentes Features: campos testados com valores válidos, valores vazios, valores no limite de tamanho e valores fora do padrão esperado (caracteres especiais, texto muito longo, espaços em branco isolados ou combinados). Essa técnica foi especialmente relevante nos campos de Nome e E-mail da Feature Suporte e Ajuda, no campo E-mail do pagamento PIX e nos campos de quantidade de ingressos da Feature Comprar Ingressos — todos com comportamentos de limite identificados como bugs durante a execução.

- **Teste negativo:** utilizado para garantir que a plataforma rejeita corretamente entradas inválidas sem quebrar — credenciais incorretas, buscas sem resultado, campos com excesso de caracteres, tentativas de avançar etapas sem preencher dados obrigatórios e interações em estados inconsistentes da interface. Essa técnica foi central na cobertura de robustez das seis Features e está diretamente associada à identificação dos BUG-01, BUG-02 e BUG-03.

- **Teste exploratório:** técnica central para descobrir comportamentos não óbvios da plataforma. Bugs como a busca por local sem retorno de resultados (BUG-01) e a duplicação do modal de pagamento após alternância de abas (BUG-05) não foram encontrados por casos de teste pré-planejados, mas por investigação incremental: cada resultado inesperado gerava uma nova hipótese, testada isoladamente até isolar o padrão do problema. O teste exploratório também orientou a cobertura de cenários que não existiriam em um roteiro estritamente funcional, como testes anti-flaky com cálculo de taxa de flakiness e varredura de mais de 200 códigos de país no combobox de DDD.

- **Teste de regressão implícito:** ocorre a cada nova execução completa da suíte, servindo como rede de segurança para identificar quebras de comportamento após alterações na plataforma. Os 586 cenários funcionam coletivamente como base de regressão contínua — qualquer alteração em produção pode ser validada contra o conjunto existente antes de atingir o usuário final.

- **Teste de condição de corrida (concorrência):** aplicado em pontos críticos de interação repetida — como cliques consecutivos no botão "Copiar chave" do PIX e múltiplas submissões do formulário de Criar Conta — para verificar se a plataforma processa múltiplas ações quase simultâneas sem gerar duplicidade de notificações, pedidos ou requisições indevidas. O BUG-04 (toasts duplicados) é um achado direto dessa abordagem.

- **Teste de limite de caracteres e validação de entrada:** aplicado em campos de formulário em múltiplas Features (Nome e E-mail em Suporte e Ajuda, E-mail PIX em Comprar Ingressos, campos de criação de conta) para verificar se a plataforma impõe e comunica corretamente os limites máximos de caracteres aceitos. A técnica combinou inserção direta via interface e manipulação do `value` nativo do input para garantir que o truncamento real fosse testado, não apenas o comportamento visual.

- **Teste de persistência e gerenciamento de estado:** validou o comportamento da plataforma em situações de mudança de contexto — alternância entre abas do navegador, reload durante preenchimento, logout em aba paralela, alteração de permissões dentro de um modal e troca de idioma seguida de refresh. Essa abordagem foi responsável pela identificação dos BUG-05 e BUG-06, ambos relacionados à perda ou duplicação de estado após mudanças de contexto.

- **Teste orientado a dados (data-driven):** aplicado nos cenários de RBAC da Feature Publicar Eventos, onde as seções disponíveis são descobertas dinamicamente via DOM em tempo de execução em vez de uma lista fixa, e no cenário de varredura completa de DDDs na Feature Criar Conta, com mais de 200 iterações sobre dados reais. Essa abordagem torna os cenários mais resilientes a mudanças de conteúdo e mais representativos de uso real do que testes com valores hardcoded.

- **Teste de internacionalização (i18n):** aplicado na Feature Criar Conta com profundidade em três idiomas — Português, English e Español — verificando cruzadamente rótulos, placeholders, mensagens de erro e persistência da preferência de idioma após refresh. A técnica incluiu verificação ativa de que texto do idioma anterior não permanece no DOM após a troca, um tipo de validação que raramente aparece em roteiros funcionais convencionais.

Essa combinação de técnicas planejadas e exploratórias permitiu não apenas confirmar que as funcionalidades atendem ao comportamento esperado, mas também identificar seis bugs reais — cinco de severidade Média ou Alta — que não estariam cobertos por um roteiro de teste estritamente linear.

> ⚠️ **Observação:** todos os testes foram realizados diretamente em **ambiente de produção**, sem acesso a um ambiente de testes dedicado, logs internos, dados reais de usuários ou histórico de incidentes. Isso reforça o caráter exploratório e observacional da suíte — os comportamentos descritos representam o que foi possível observar e reproduzir a partir da interface pública da plataforma.

---

## 🚧 Limitações e escopo

Por se tratar de um projeto realizado integralmente em **ambiente de produção** — sem acesso a um ambiente de testes dedicado, dados internos, logs ou configurações administrativas —, o escopo foi definido exclusivamente a partir do que estava disponível e observável pela interface pública da plataforma FasTix.

Diferente de um ciclo completo de QA, onde o analista tem acesso a logs, dados reais de usuários, histórico de incidentes e variações de cenários trazidas por bugfixes e hotfixes recorrentes, este projeto foi construído com as informações que puderam ser confirmadas manualmente, tela a tela, ao longo da exploração da plataforma em produção. Essa condição moldou diretamente as decisões de escopo e deve ser considerada na leitura de qualquer métrica ou análise apresentada nesta suíte.

Alguns cenários ficaram intencionalmente fora do escopo por impossibilidade técnica ou falta de acesso:

- **Ciclo E2E completo de compra de ingressos:** não foi possível concluir o fluxo de compra em sua totalidade. As etapas de confirmação de pagamento (PIX e Cartão de Crédito), geração e validação real do QR Code, verificação de dados bancários, disponibilização dos ingressos para impressão e confirmações via e-mail e SMS estão fora do escopo desta suíte por ausência de acesso ao fluxo transacional completo. A cobertura da Feature Comprar Ingressos alcança até a etapa de seleção da forma de pagamento, com validações de formulário, segurança e estado do checkout — mas não inclui a confirmação efetiva da transação.

- **Ambiente de testes dedicado:** todos os cenários foram executados diretamente em produção, o que impossibilitou testes destrutivos, simulações de falha de infraestrutura, injeção de dados controlados ou qualquer interação com potencial de impactar usuários reais da plataforma. Cenários de estresse e robustez foram cuidadosamente construídos para permanecer dentro do que é seguro executar em produção — o que, por si só, limita a profundidade máxima de alguns testes de carga e concorrência.

- **Acesso administrativo e back-office:** funcionalidades de gestão interna de eventos, relatórios financeiros, controle de acesso (check-in no dia do evento) e configurações avançadas de produtores não foram testadas por exigirem credenciais administrativas não disponíveis neste escopo. A Feature Publicar Eventos cobre o fluxo do produtor até a configuração do evento e das equipes, mas não inclui a gestão operacional pós-publicação.

- **Confirmação de integrações externas de ponta a ponta:** o comportamento real das integrações com gateways de pagamento (processamento efetivo da transação), serviços de e-mail e SMS (entrega das confirmações) e sistemas de emissão de ingressos (geração do ingresso virtual) não pôde ser validado além da camada de interface. Os testes verificam o comportamento da UI e dos campos de formulário, não a resposta final dos sistemas integrados.

- **Testes de carga e performance em escala:** a ausência de ambiente dedicado impossibilitou simulações de múltiplos usuários simultâneos, testes de throughput, latência sob carga ou cenários de pico de acesso. Os cenários de estresse presentes na suíte simulam comportamento intensivo de um único usuário sobre componentes específicos — não substituem ferramentas de load testing como k6, Locust ou JMeter aplicadas contra um ambiente de homologação.

- **Cross-browser:** todos os testes foram executados exclusivamente no Google Chrome (Chromium via Playwright). Não há cobertura de Firefox, Edge ou Safari. A ausência é documentada explicitamente nas Features onde seria mais relevante e representa uma oportunidade de expansão, não uma falha da suíte.

Essas exclusões não representam falhas na cobertura, mas sim **decisões conscientes de escopo**, tomadas com base nas condições reais de acesso disponíveis. Documentar o que ficou fora é tão importante quanto documentar o que foi coberto: permite que qualquer analista que utilize esta suíte no futuro compreenda exatamente os seus limites e planeje a expansão da cobertura a partir deles.

---

## 🚀 Próximos passos (CI/CD)

Atualmente, a suíte é executada manualmente via terminal com o comando `npx codeceptjs run` na máquina local. A automação da execução via **GitHub Actions** foi avaliada como evolução natural do projeto, mas não foi implementada nesta fase por razões técnicas objetivas — não por falta de planejamento.

O CodeceptJS com Playwright oferece uma vantagem estrutural importante para CI/CD: os testes rodam em **modo headless** nativamente, sem necessidade de emulador físico ou ambiente gráfico. Isso torna a integração com GitHub Actions tecnicamente mais direta do que em stacks mobile (como o Maestro, que depende de emulador Android ativo e ponte ADB). A base técnica para o pipeline já existe — o que falta é a infraestrutura de suporte necessária para executá-lo com segurança.

Três fatores limitaram a implementação nesta fase:

- **Execução em produção:** automatizar a execução recorrente de 586 cenários diretamente em produção exigiria controle rigoroso sobre quais testes podem ser disparados sem gerar efeitos colaterais para usuários reais — especialmente fluxos que interagem com formulários públicos, buscas e navegação. Sem essa triagem, o risco de interferência é real.
- **Ausência de ambiente de staging:** sem um ambiente de homologação disponível, não há destino seguro para rodar a suíte completa de forma automatizada e recorrente. Essa é a dependência mais crítica para a implementação do pipeline.
- **Cobertura E2E parcial no checkout:** como o ciclo de compra de ingressos não foi concluído de ponta a ponta, incluir esses cenários em um pipeline automatizado exigiria definição clara de quais etapas são seguras para execução recorrente e quais precisam de ambiente controlado com dados de teste reais.

Uma implementação futura seguiria estas etapas:

```text
1. Provisionar ambiente de staging ou homologação para execução segura e recorrente dos testes.
2. Separar os cenários em dois grupos: "seguros para produção" (navegação, leitura, consultas)
   e "restritos a staging" (formulários, checkout, interações com dados).
3. Criar workflow no GitHub Actions com gatilho em pull requests e merges para a branch principal,
   executando inicialmente apenas o grupo seguro para produção como smoke test.
4. Expandir gradualmente para a suíte completa à medida que o ambiente de staging estiver estável.
5. Publicar automaticamente os relatórios de execução do CodeceptJS como artefato do workflow.
6. Configurar notificações de falhas via Slack ou e-mail para visibilidade imediata da equipe.
7. Avaliar serviços de nuvem (BrowserStack, Sauce Labs) para viabilizar testes transacionais reais
   em ambiente controlado, cobrindo as etapas de pagamento ainda fora do escopo atual.
```

O reconhecimento dessas dependências antes de iniciar a implementação é, em si, parte do planejamento de qualidade. Automatizar sem infraestrutura adequada criaria um pipeline instável e difícil de manter — o que prejudicaria a confiança da equipe nos resultados mais do que ajudaria.

---

## 💡 Aprendizados técnicos

A execução deste projeto gerou aprendizados técnicos concretos em quatro áreas:

**1. Automação em ambiente de produção exige disciplina de escopo**

Testar diretamente em produção sem staging força decisões que não aparecem em projetos com infraestrutura completa: quais cenários são seguros de executar repetidamente, quais podem gerar efeitos colaterais e onde o teste precisa parar antes de ultrapassar o limite do observável. Essa restrição, que inicialmente parece uma limitação, também treina uma habilidade importante: construir cenários precisos que validam o comportamento necessário sem depender de condições que só existem em ambientes controlados.

**2. Classificação por dimensões de qualidade evita análises enganosas**

Tratar E2E, Regressão, Stress e Funcional como categorias equivalentes é um erro comum em suítes grandes. Ao separar escopo da jornada (E2E) de objetivo funcional (Funcional) de condição de execução (Stress), ficou possível identificar com precisão o que cada cenário realmente valida — e comunicar isso sem ambiguidade para equipes de desenvolvimento, produto e operação. A distinção também evita que uma suíte pareça mais abrangente do que é: um teste de stress de carrossel não é um teste de performance de infraestrutura.

**3. Comportamento de terceiros precisa de tratamento explícito nos testes**

Os cenários de login social (Google/Apple) evidenciaram que, em automação, bloqueios antibot de provedores externos são resultados esperados, não falhas. Tratar o redirecionamento correto para o domínio do provedor como critério de sucesso — sem tentar completar a autenticação — é uma decisão de design de teste que evita falsos negativos e torna a suíte mais estável. O mesmo raciocínio se aplica à integração com Google Maps/Places: validar que a entrada retornou uma sugestão é diferente de validar que a sugestão é geográfica ou semanticamente correta.

**4. Testes que documentam comportamento em vez de assumir um resultado fixo são mais duráveis**

Alguns cenários desta suíte aceitam mais de um resultado como válido — o formulário de Criar Conta pode ou não preservar dados após refresh, e ambos os comportamentos são aceitáveis desde que o estado final seja consistente. Esse padrão, aplicado nos cenários 0035 e 0047 da Feature Criar Conta, representa uma abordagem mais madura do que afirmar "o campo deve estar vazio" sem confirmar qual é o comportamento de negócio pretendido. Testes que documentam o comportamento atual sem presumir uma única resposta correta tendem a ser mais estáveis ao longo do tempo e geram descobertas mais úteis do que testes que apenas confirmam o que já se sabe.

## 📬 Contato

 
| LinkedIn                   |  https://www.linkedin.com/in/diogoamanciosilva/ |
| ------------------------- | ------: |

| E-mail                   |  diogoamanciosilva@gmail.com/ |
| ------------------------- | ------: |



