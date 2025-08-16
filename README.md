# HairDay

Projeto desenvolvido para treinar JavaScript na trilha FullStack da Rocketseat.

## 1. Visão Geral

HairDay é uma aplicação web para auxiliar salões de beleza a gerenciar seus agendamentos de corte de cabelo. Permite aos administradores criar e editar compromissos, visualizar horários disponíveis e gerenciar a agenda de forma simples e eficiente.

## 2. Layout

O layout do projeto foi inspirado por um design da Rocketseat (possivelmente um protótipo no Figma). Ele oferece uma interface clara, com navegação intuitiva e foco na experiência do usuário.

## 3. Funcionalidades

- Criar e editar agendamentos
- Visualizar compromissos agendados
- Mostrar horários disponíveis ("time slots")
- Filtrar por dia selecionado
- Interface amigável voltada para administradores de salão

## 4. Estrutura do Projeto

```
hairday/
├── dist/                 # Arquivos compilados e prontos para produção
├── src/                  # Código-fonte principal
│   ├── assets/           # Imagens e ícones
│   ├── libs/             # Bibliotecas de utilitários como dayjs
│   ├── modules/
│   │   ├── form/
│   │   └── schedules/
│   ├── services/         # Chamadas API e lógica de negócio
│   ├── styles/           # Arquivos CSS (formulário, global etc.)
│   ├── utils/            # Funções utilitárias (por exemplo, 'opening-hours')
│   └── main.js           # Inicialização da aplicação
├── index.html            # Entrada da aplicação
├── package.json          # Metadados, dependências, scripts
├── package-lock.json     # Versões fixas das dependências
├── server.json           # Configurações do servidor (p. ex., json-server)
└── webpack.config.js     # Configurações do Webpack
```

## 5. Como Executar Localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/dieegomarcelo/hairday.git
   cd hairday
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o servidor (ex: json-server ou similar):

   ```bash
   npm run server
   ```

4. Em outro terminal, inicie a aplicação no modo de desenvolvimento:

   ```bash
   npm run dev
   ```

Abra o navegador e acesse `http://localhost:3000` (ou outra porta configurada).

## 6. Tecnologias

- JavaScript (ES6+)
- HTML5 e CSS3
- Webpack
- json-server (ou similar para API fake)
- Bibliotecas auxiliares (ex: dayjs)

## 7. Contribuições

Contribuições são bem-vindas! Você pode ajudar com:

- Correções de bugs
- Novas funcionalidades (como persistência via backend real)
- Melhorias na interface e experiência do usuário
- Refatoração ou otimização

Abra uma issue ou envie um pull request. Qualquer feedback será muito bem-vindo!

## 8. Licença

Este projeto está aberto para uso pessoal e educacional. Sinta-se à vontade para adaptar conforme suas necessidades.
