🚀 Sistema de Gestão de Vendas MEI - (FRONT-END)
Sistema moderno de gestão de vendas para Microempreendedores Individuais (MEI) desenvolvido com React, TypeScript e shadcn/ui.

✨ Funcionalidades
🔐 Autenticação
Login seguro com JWT
Registro de novos usuários
Proteção de rotas privadas
Logout automático em caso de token expirado
📊 Dashboard Executivo
Resumo mensal e anual de vendas
Ticket médio calculado automaticamente
Produtos mais vendidos com ranking
Vendas por categoria com distribuição visual
Vendas por dia do mês atual
Exportação de relatórios em JSON e CSV
🛍️ Gestão de Vendas
Listagem de vendas com paginação
Cadastro de novas vendas
Filtros por período
Cálculo automático de valores totais
📦 Gestão de Produtos
Catálogo de produtos organizado
Cadastro e edição de produtos
Categorização de produtos
Status ativo/inativo
🎨 Design System
shadcn/ui Components
Cards responsivos e elegantes
Buttons com variantes e estados
Inputs com validação visual
Layout moderno com sidebar
Loading states e feedback visual
Tema Personalizado
Cores primárias azuis profissionais
Modo claro otimizado para produtividade
Tipografia clara e legível
Espaçamentos consistentes
🛠️ Tecnologias
Core
React 19 - Framework principal
TypeScript - Tipagem estática
React Router DOM - Roteamento
Axios - Cliente HTTP
UI/UX
shadcn/ui - Componentes modernos
Tailwind CSS - Estilização utilitária
Radix UI - Componentes acessíveis
Lucide React - Ícones consistentes
Desenvolvimento
React Scripts - Build e desenvolvimento
ESLint - Linting de código
PostCSS - Processamento CSS
🚀 Como Executar
Pré-requisitos
Node.js 18+
npm ou yarn
API backend rodando na porta 3333
Instalação
# Clone o repositório
git clone <url-do-repositorio>

# Entre no diretório
cd vendas-app-frontend

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm start
Configuração da API
O frontend está configurado para conectar com a API em:

http://localhost:3333/api
Para alterar, edite o arquivo src/services/api.ts:

const API_BASE_URL = 'http://localhost:3333/api';
📱 Páginas e Rotas
Públicas
/login - Página de login
/register - Página de registro
Privadas (requer autenticação)
/dashboard - Dashboard principal
/vendas - Listagem de vendas
/produtos - Gestão de produtos
/venda-form - Formulário de nova venda
🔧 Estrutura do Projeto
src/
├── components/          # Componentes reutilizáveis
│   ├── ui/             # Componentes shadcn/ui
│   ├── Layout.tsx      # Layout principal
│   └── ProtectedRoute.tsx
├── pages/              # Páginas da aplicação
│   ├── Dashboard.tsx   # Dashboard principal
│   ├── Login.tsx       # Página de login
│   ├── Register.tsx    # Página de registro
│   └── Vendas.tsx      # Gestão de vendas
├── services/           # Serviços e API
│   └── api.ts          # Cliente HTTP e endpoints
├── lib/                # Utilitários
│   └── utils.ts        # Funções auxiliares
└── context/            # Contextos React
    └── VendaContext.tsx
🎯 Funcionalidades Implementadas
✅ Autenticação Completa
 Login com email e senha
 Registro de novos usuários
 Proteção de rotas
 Interceptors para token JWT
 Logout automático
✅ Dashboard Moderno
 Cards de métricas principais
 Produtos mais vendidos
 Vendas por categoria
 Vendas por dia
 Exportação de relatórios
 Loading states
✅ Interface Moderna
 Design system shadcn/ui
 Layout responsivo
 Navegação lateral
 Feedback visual
 Estados de loading e erro
✅ Integração com API
 Serviços tipados
 Tratamento de erros
 Interceptors HTTP
 Paginação
 Filtros
🔮 Próximas Funcionalidades
📈 Relatórios Avançados
 Gráficos interativos com Recharts
 Comparativos mensais
 Projeções de vendas
 Relatórios personalizados
🛍️ Gestão Avançada
 Gestão de estoque
 Categorias personalizadas
 Importação/exportação de dados
 Backup automático
🎨 UX/UI
 Modo escuro
 Temas personalizáveis
 Notificações push
 PWA (Progressive Web App)
🤝 Contribuição
Fork o projeto
Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
Commit suas mudanças (git commit -m 'Add some AmazingFeature')
Push para a branch (git push origin feature/AmazingFeature)
Abra um Pull Request
📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

🆘 Suporte
Para suporte, abra uma issue no GitHub ou entre em contato com a equipe de desenvolvimento.

Desenvolvido com ❤️ para MEIs brasileiros

--------------------------------------------------------------------------------------------------------------------

🚀 Gestão de Vendas - MEI API (BACK-END)
Sistema completo de gestão de vendas desenvolvido especificamente para Microempreendedores Individuais (MEIs). Uma solução robusta, gratuita e intuitiva para controle financeiro e operacional de pequenos negócios.

📋 Índice
Sobre o Projeto
Funcionalidades
Tecnologias
Pré-requisitos
Instalação
Configuração
Uso da API
Endpoints
Estrutura do Projeto
Contribuição
🎯 Sobre o Projeto
O Gestão de Vendas - MEI é uma API REST desenvolvida com NestJS e Prisma que oferece aos Microempreendedores Individuais uma solução completa para:

✅ Controle financeiro profissional
✅ Registro simplificado de vendas
✅ Gestão de produtos e estoque
✅ Relatórios detalhados e dashboards
✅ Exportação de dados para DAS/PGMEI
✅ Análises de performance e tendências
🚀 Funcionalidades
👤 Gestão de Usuários
Cadastro e autenticação segura
Perfil personalizado por MEI
Sistema de JWT para segurança
📦 Gestão de Produtos
Cadastro completo de produtos
Categorização inteligente
Controle de preços e status
Análise de produtos mais vendidos
💰 Gestão de Vendas
Registro rápido e intuitivo
Cálculo automático de valores
Histórico completo de transações
Filtros por período e produto
📊 Relatórios e Analytics
Dashboard executivo em tempo real
Comparativos mensais e anuais
Análise por categoria e produto
Exportação em JSON e CSV
Métricas de performance (ticket médio, etc.)
🛠 Tecnologias
Backend: NestJS (Node.js + TypeScript)
Banco de Dados: MySQL com Prisma ORM
Autenticação: JWT + Passport
Validação: Class Validator + Class Transformer
Documentação: Swagger (em desenvolvimento)
📋 Pré-requisitos
Node.js (versão 18 ou superior)
MySQL (versão 8.0 ou superior)
pnpm (recomendado) ou npm
🔧 Instalação
Clone o repositório
git clone <url-do-repositorio>
cd vendas-api
Instale as dependências
pnpm install
Configure o banco de dados
# Crie o banco de dados MySQL
mysql -u root -p
CREATE DATABASE vendas_db;
Configure as variáveis de ambiente
# Copie o arquivo de exemplo
cp .env.example .env

# Edite o arquivo .env com suas configurações
DATABASE_URL="mysql://usuario:senha@localhost:3306/vendas_db"
JWT_SECRET="seu-jwt-secret-super-seguro"
JWT_EXPIRES_IN="7d"
PORT=3000
Execute as migrações do banco
pnpm prisma generate
pnpm prisma db push
Inicie o servidor
# Desenvolvimento
pnpm start:dev

# Produção
pnpm build
pnpm start:prod
⚙️ Configuração
Variáveis de Ambiente
Variável	Descrição	Exemplo
DATABASE_URL	URL de conexão MySQL	mysql://user:pass@localhost:3306/vendas_db
JWT_SECRET	Chave secreta para JWT	minha-chave-super-secreta
JWT_EXPIRES_IN	Tempo de expiração do token	7d
PORT	Porta do servidor	3000
Banco de Dados
O sistema utiliza as seguintes tabelas principais:

tb_usuarios - Dados dos MEIs
tb_produtos - Catálogo de produtos
tb_vendas - Registro de vendas
tb_relatorios_mensais - Cache de relatórios
🔌 Uso da API
Autenticação
Todas as rotas (exceto registro e login) requerem autenticação via Bearer Token:

Authorization: Bearer <seu-jwt-token>
Exemplo de Uso
# 1. Registrar usuário
curl -X POST http://localhost:3000/api/auth/register \
  -H "Content-Type: application/json" \
  -d '{
    "nome": "João Silva",
    "email": "joao@exemplo.com",
    "senha": "123456"
  }'

# 2. Fazer login
curl -X POST http://localhost:3000/api/auth/login \
  -H "Content-Type: application/json" \
  -d '{
    "email": "joao@exemplo.com",
    "senha": "123456"
  }'

# 3. Criar produto
curl -X POST http://localhost:3000/api/produtos \
  -H "Authorization: Bearer <token>" \
  -H "Content-Type: application/json" \
  -d '{
    "nome": "Camiseta Básica",
    "preco": 29.90,
    "categoria": "Roupas"
  }'

# 4. Registrar venda
curl -X POST http://localhost:3000/api/vendas \
  -H "Authorization: Bearer <token>" \
  -H "Content-Type: application/json" \
  -d '{
    "produtoId": 1,
    "quantidade": 2,
    "dataVenda": "2024-01-15"
  }'
📚 Endpoints
🔐 Autenticação
POST /api/auth/register - Cadastrar usuário
POST /api/auth/login - Fazer login
👤 Usuários
GET /api/users - Listar usuários
GET /api/users/:id - Buscar usuário
PATCH /api/users/:id - Atualizar usuário
DELETE /api/users/:id - Excluir usuário
📦 Produtos
GET /api/produtos - Listar produtos (paginado)
POST /api/produtos - Criar produto
GET /api/produtos/:id - Buscar produto
PATCH /api/produtos/:id - Atualizar produto
DELETE /api/produtos/:id - Excluir produto
GET /api/produtos/categoria/:categoria - Produtos por categoria
GET /api/produtos/mais-vendidos - Produtos mais vendidos
💰 Vendas
GET /api/vendas - Listar vendas (paginado, com filtros)
POST /api/vendas - Registrar venda
GET /api/vendas/:id - Buscar venda
PATCH /api/vendas/:id - Atualizar venda
DELETE /api/vendas/:id - Excluir venda
GET /api/vendas/periodo - Vendas por período
GET /api/vendas/resumo-mensal - Resumo mensal
📊 Relatórios
GET /api/relatorios/dashboard - Dashboard principal
GET /api/relatorios/comparativo-mensal - Comparativo mensal
GET /api/relatorios/detalhado - Relatório detalhado
GET /api/relatorios/exportar - Exportar dados (JSON/CSV)
🔍 Sistema
GET /api - Informações da API
GET /api/health - Status do sistema
📁 Estrutura do Projeto
src/
├── auth/                 # Módulo de autenticação
│   ├── dto/             # DTOs de autenticação
│   ├── guards/          # Guards JWT e Local
│   └── strategies/      # Estratégias Passport
├── common/              # Utilitários compartilhados
│   └── dto/            # DTOs comuns (paginação)
├── prisma/             # Configuração Prisma
├── produtos/           # Módulo de produtos
├── relatorios/         # Módulo de relatórios
├── users/              # Módulo de usuários
├── vendas/             # Módulo de vendas
├── app.module.ts       # Módulo principal
└── main.ts            # Ponto de entrada
🎨 Padrões de Código
Arquitetura: Modular (NestJS)
Validação: DTOs com decorators
Segurança: JWT + Guards
Banco: Prisma ORM com relacionamentos
Tratamento de Erros: Exception Filters
Documentação: JSDoc + README
🚀 Deploy
Docker (Recomendado)
# Dockerfile
FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "run", "start:prod"]
Variáveis de Produção
NODE_ENV=production
DATABASE_URL=mysql://user:pass@host:3306/db
JWT_SECRET=chave-super-segura-producao
🤝 Contribuição
Fork o projeto
Crie uma branch (git checkout -b feature/nova-funcionalidade)
Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade')
Push para a branch (git push origin feature/nova-funcionalidade)
Abra um Pull Request
📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para detalhes.

👨‍💻 Autor
Desenvolvido com ❤️ para ajudar MEIs a crescerem seus negócios.

🎯 Objetivo: Democratizar o acesso a ferramentas de gestão profissional para pequenos empreendedores brasileiros.

📞 Suporte: Abra uma issue no GitHub para reportar bugs ou solicitar funcionalidades.
