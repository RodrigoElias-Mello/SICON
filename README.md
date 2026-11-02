# 🏢 SICON — Sistema Integrado de Gestão Condominial

<p align="center">
  <strong>Gestão inteligente, organização e controle em um só lugar.</strong>
  <br />
  Uma solução digital para simplificar a administração de condomínios.
</p>

<p align="center">
  <a href="https://sicon-sigc.vercel.app/">🌐 Acessar aplicação</a>
</p>

---

## 📌 Sobre o projeto

O **SICON (Sistema Integrado de Gestão Condominial)** é uma aplicação web full stack desenvolvida para centralizar e organizar os principais processos administrativos, financeiros e operacionais de condomínios.

A plataforma oferece um ambiente digital para cadastro e gerenciamento de informações, acompanhamento financeiro, organização de equipes, controle de reservas, administração de comunicados e acompanhamento de obrigações.

O objetivo é proporcionar uma ferramenta intuitiva, organizada e eficiente, permitindo que informações importantes da administração condominial sejam gerenciadas em um único ambiente.

## 🎯 Objetivos do projeto

- Centralizar informações administrativas do condomínio.
- Facilitar o gerenciamento de unidades e moradores.
- Organizar dados de funcionários e fornecedores.
- Controlar receitas, despesas e pagamentos.
- Gerenciar comunicados e avisos.
- Acompanhar reservas de espaços compartilhados.
- Organizar assembleias e registros de votação.
- Monitorar obrigações e respectivos prazos.
- Manter informações organizadas e associadas ao condomínio cadastrado.

## ✨ Módulos e funcionalidades

### 🏢 1. Unidades
- Cadastro de apartamentos, casas e unidades comerciais.
- Organização por bloco e número.
- Controle da situação das unidades.
- Associação de moradores às unidades cadastradas.

### 👥 2. Moradores
- Cadastro de moradores.
- Associação com unidades.
- Registro de informações de contato.
- Controle de situação cadastral.

### 👷 3. Funcionários
- Cadastro de funcionários.
- Registro de funções e contatos.
- Controle de datas de admissão.
- Acompanhamento da situação funcional.

### 🤝 4. Fornecedores
- Cadastro de empresas prestadoras de serviços.
- Organização por categoria de serviço.
- Registro de contatos.
- Controle de início e término de contratos.
- Campo para observações.

### 💰 5. Financeiro
- Registro de receitas e despesas.
- Organização por categorias.
- Controle de valores e vencimentos.
- Acompanhamento de pagamentos.
- Identificação de lançamentos pendentes, pagos ou cancelados.
- Resumo financeiro e histórico de movimentações.

### 📢 6. Comunicados
- Criação de comunicados.
- Definição do público destinatário.
- Organização por rascunhos, publicados e arquivados.
- Registro de informações e datas de publicação.

### 📅 7. Reservas
- Cadastro de solicitações de reserva.
- Identificação dos espaços compartilhados.
- Registro de solicitantes.
- Controle de datas e horários.
- Acompanhamento de solicitações pendentes, aprovadas, recusadas ou canceladas.

### 🗓️ 8. Assembleias
- Cadastro e agendamento de assembleias.
- Registro de data, horário e local.
- Organização de pautas.
- Registro de atas.
- Controle da situação das assembleias.

### ⚖️ 9. Obrigações legais
- Cadastro de obrigações.
- Organização por categoria.
- Controle de vencimentos.
- Registro de conclusão.
- Acompanhamento de pendências e prazos.

### 🚗 10. Veículos
- Cadastro de veículos vinculados aos moradores.
- Registro de placas, marcas, modelos e cores.
- Controle da situação cadastral.

### 🗳️ 11. Votações
- Registro de resultados de votação vinculados às assembleias.
- Controle de votos favoráveis.
- Registro de votos contrários.
- Registro de abstenções.
- Acompanhamento de votações pendentes ou encerradas.

## 📊 Painel administrativo

O dashboard reúne indicadores importantes para acompanhamento da administração condominial.

Entre os recursos disponíveis estão:

- Indicadores de unidades cadastradas.
- Quantidade de moradores ativos.
- Quantidade de funcionários ativos.
- Quantidade de fornecedores ativos.
- Resumo financeiro por período.
- Comparação de receitas e despesas pagas.
- Saldo financeiro.
- Histórico financeiro.
- Identificação de obrigações vencidas ou próximas do vencimento.
- Acompanhamento de solicitações de reservas pendentes.
- Acesso rápido aos principais módulos.

Os indicadores são calculados a partir dos registros armazenados na aplicação.

## 🔐 Autenticação e segurança

O SICON possui estrutura de autenticação e proteção das áreas administrativas.

Recursos implementados:

- Criação de conta.
- Login com e-mail e senha.
- Gerenciamento de sessões.
- Proteção de rotas administrativas.
- Redirecionamento de usuários não autenticados.
- Associação dos dados ao usuário responsável.
- Verificação de sessão nas operações do servidor.
- Validação dos dados enviados pelos formulários.

A autenticação utiliza Better Auth, enquanto as operações de dados são executadas no servidor.

## 🎨 Interface e experiência do usuário

A interface foi desenvolvida com foco em usabilidade, clareza e organização das informações.

Características:

- Identidade visual institucional.
- Layout administrativo moderno.
- Navegação lateral por módulos.
- Dashboard com indicadores.
- Componentes reutilizáveis.
- Formulários organizados.
- Tabelas para visualização de registros.
- Indicadores visuais de situação.
- Gráficos financeiros.
- Interface adaptável a diferentes tamanhos de tela.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Finalidade |
|---|---|
| Next.js 16 | Framework full stack e estrutura da aplicação |
| React 19 | Construção da interface |
| TypeScript 5.7 | Tipagem e segurança do código |
| Tailwind CSS 4 | Estilização da interface |
| PostgreSQL | Banco de dados relacional |
| Drizzle ORM | Comunicação e consultas ao banco de dados |
| Better Auth | Autenticação e gerenciamento de sessões |
| Zod 4 | Validação de dados |
| Recharts 3 | Construção de gráficos |
| Lucide React | Biblioteca de ícones |
| Base UI | Componentes de interface |
| Vercel Analytics | Análise de acesso em produção |
| pnpm | Gerenciamento de dependências |
| Vercel | Hospedagem e publicação da aplicação |

## 🏗️ Arquitetura e organização

O projeto utiliza a arquitetura do Next.js com App Router, separando páginas, componentes visuais, autenticação, operações de servidor e acesso aos dados.

### Estrutura de diretórios

```text
SICON/
│
├── app/
│   ├── (auth)/
│   │   ├── sign-in/
│   │   └── sign-up/
│   │
│   ├── (protected)/
│   │   ├── [module]/
│   │   ├── setup/
│   │   └── page.tsx
│   │
│   ├── api/
│   │   └── auth/
│   │
│   ├── globals.css
│   └── layout.tsx
│
├── components/
│   ├── ui/
│   ├── sicon/
│   ├── app-shell.tsx
│   ├── auth-form.tsx
│   ├── dashboard-overview.tsx
│   ├── module-workspace.tsx
│   └── setup-form.tsx
│
├── lib/
│   ├── actions/
│   ├── db/
│   ├── modules/
│   ├── auth.ts
│   ├── auth-client.ts
│   ├── auth-utils.ts
│   ├── dashboard-data.ts
│   ├── format.ts
│   └── utils.ts
│
├── public/
│
├── legacy/
│
├── package.json
├── pnpm-lock.yaml
├── next.config.mjs
├── postcss.config.mjs
├── tsconfig.json
├── proxy.ts
└── README.md
```

## 🗄️ Banco de dados

O projeto utiliza PostgreSQL como banco de dados relacional e Drizzle ORM para estruturar e executar operações de persistência.

O esquema contempla entidades como:

- Usuários.
- Sessões e contas de autenticação.
- Condomínios.
- Unidades.
- Moradores.
- Funcionários.
- Fornecedores.
- Lançamentos financeiros.
- Comunicados.
- Reservas.
- Assembleias.
- Obrigações legais.
- Veículos.
- Resultados de votações.

Os registros operacionais possuem associação com o usuário e o condomínio, permitindo organizar os dados conforme o contexto administrativo.

## 🚀 Executando o projeto localmente

### Pré-requisitos

- Node.js.
- pnpm.
- PostgreSQL.
- Git.

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acesse a pasta do projeto

```bash
cd SICON
```

### 3. Instale as dependências

```bash
pnpm install
```

### 4. Configure as variáveis de ambiente

Crie um arquivo `.env.local` na raiz do projeto:

```env
DATABASE_URL="postgresql://USUARIO:SENHA@HOST:5432/NOME_DO_BANCO"

BETTER_AUTH_SECRET="SUA_CHAVE_SECRETA"
BETTER_AUTH_URL="http://localhost:3000"
```

**Importante:** substitua os valores de exemplo pelas credenciais reais do seu banco de dados e por uma chave secreta segura. Nunca publique credenciais ou arquivos `.env.local` no GitHub.

### 5. Prepare o banco de dados

Configure o PostgreSQL e disponibilize as tabelas correspondentes ao esquema definido em `lib/db/schema.ts`.

O projeto não inclui, no pacote analisado, um script de migração configurado no `package.json`. Portanto, a criação e a atualização das tabelas precisam ser preparadas conforme a estratégia de migração adotada no ambiente.

### 6. Execute em desenvolvimento

```bash
pnpm dev
```

### 7. Acesse a aplicação

```text
http://localhost:3000
```

### 8. Gere a versão de produção

```bash
pnpm build
```

### 9. Inicie a aplicação em produção

```bash
pnpm start
```

## 🌐 Aplicação publicada

O SICON está disponível online:

**https://sicon-sigc.vercel.app/**

A aplicação utiliza autenticação e requer acesso por conta para entrar nas áreas administrativas.

## 👨‍💻 Desenvolvedor

**Rodrigo Elias Alfama de Mello**

Desenvolvedor Web | Front-End | Soluções Digitais

Formado em Análise e Desenvolvimento de Sistemas, com foco no desenvolvimento de aplicações web, interfaces modernas e soluções digitais.

<p align="center">
  <a href="https://portifolio-rodrigo-elias.vercel.app/">Portfólio</a> •
  <a href="https://www.linkedin.com/in/rodrigoelias1709">LinkedIn</a> •
  <a href="https://github.com/RodrigoElias-Mello">GitHub</a>
</p>

---

<p align="center">
  <strong>SICON — Gestão condominial integrada, organizada e inteligente.</strong>
</p>
