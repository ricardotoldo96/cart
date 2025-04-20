# Balanceador de Carteira de Investimentos

Uma aplicação web completa para balanceamento de carteira de investimentos, desenvolvida com Next.js.

## Funcionalidades

- Sistema de login com credenciais seguras
- Dashboard para visualização da carteira atual
- Ajuste de percentuais para cada categoria de ativo:
  - Ações brasileiras
  - Fundos imobiliários
  - Renda fixa
  - Ações internacionais
  - Criptomoedas
- Adição de novos ativos à carteira
- Cálculo de quanto investir em cada categoria com base no valor total desejado

## Tecnologias Utilizadas

- Next.js 15.1.4
- React 18
- Tailwind CSS
- TypeScript

## Implantação na Vercel

Este repositório está configurado para ser facilmente implantado na Vercel:

1. Faça um fork deste repositório
2. Acesse [vercel.com](https://vercel.com)
3. Clique em "Add New..." e selecione "Project"
4. Importe o repositório que você acabou de forkar
5. Mantenha as configurações padrão e clique em "Deploy"

## Desenvolvimento Local

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Construir para produção
npm run build

# Iniciar servidor de produção
npm run start
```

## Estrutura do Projeto

- `/src/app` - Páginas da aplicação
- `/src/components` - Componentes reutilizáveis
- `/src/lib` - Funções utilitárias e acesso ao banco de dados
- `/migrations` - Scripts SQL para inicialização do banco de dados

## Credenciais de Acesso

Para acessar o sistema, utilize as seguintes credenciais:
- Usuário: RicardoToldo
- Senha: (configurada nas variáveis de ambiente)
