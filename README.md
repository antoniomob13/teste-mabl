# teste-mabl

Projeto web estático simples para demonstrar um fluxo básico de login e cadastro. O repositório não usa backend, banco de dados ou autenticação real: toda a lógica está no front-end e serve como exemplo de interface e navegação entre páginas.

## Sobre o projeto

O aplicativo possui três telas principais:

- `index.html`: página de login.
- `register.html`: página de cadastro simulado.
- `dashboard.html`: área acessada após um login bem-sucedido.

O comportamento das telas é controlado por `script.js`, que valida apenas um usuário fixo e redireciona entre as páginas. O estilo visual básico está em `style.css`.

## Funcionalidades

- Login com validação simulada.
- Cadastro simulado com redirecionamento para a tela de login.
- Redirecionamento para uma dashboard após login correto.
- Layout simples para testes e demonstrações.

## Estrutura dos arquivos

- `index.html` - formulário de login.
- `register.html` - formulário de cadastro.
- `dashboard.html` - página pós-login.
- `script.js` - lógica de login e cadastro simulados.
- `style.css` - estilos globais das páginas.

## Como executar

Como o projeto é estático, não há necessidade de instalar dependências.

### Opção 1: abrir diretamente no navegador

1. Abra o arquivo `index.html` no navegador.
2. Use os dados de teste informados abaixo.

### Opção 2: usar o Live Server no VS Code

1. Abra a pasta do projeto no VS Code.
2. Instale a extensão Live Server, se quiser servir as páginas localmente.
3. Clique com o botão direito em `index.html` e escolha `Open with Live Server`.

## Credenciais de teste

Use os seguintes dados para entrar com sucesso:

- E-mail: `teste@teste.com`
- Senha: `123456`

## Fluxo esperado

1. Acesse a página de login.
2. Informe as credenciais corretas.
3. O sistema exibe um alerta de sucesso e direciona para a dashboard.
4. Se o cadastro for usado, o sistema apenas simula o registro e retorna para o login.

## Observação

Este repositório foi feito para fins didáticos e de teste. Ele não armazena usuários reais nem processa autenticação segura.