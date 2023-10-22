# Team Heroes API

## Descrição

Este repositório contém o código-fonte da API do Team Heroes, uma aplicação Ruby on Rails que permite gerenciar informações sobre equipes de super-heróis. A API foi desenvolvida utilizando Ruby 3.1.2 e Rails 7.0.8.

## Pré-requisitos

Antes de começar a usar a API do Team Heroes, certifique-se de ter as seguintes versões de software instaladas em sua máquina:

- Ruby 3.1.2
- Ruby on Rails 7.0.8
- Yarn 1.22.19
- Node.js v20.0.8
- Git version 2.34.1

## Configuração

1. Clone este repositório em sua máquina local:

```bash
git clone https://github.com/seu-usuario/team_heroes_api.git
```

2. A API utiliza chaves de credenciais para proteger informações sensíveis. No entanto, o repositório inclui um arquivo `config/credentials.yml.enc` que contém as credenciais do desenvolvedor. Para usar suas próprias credenciais, você deve apagar o arquivo existente e criar um novo. Execute o seguinte comando para editar as credenciais com seu editor preferido (neste exemplo, usamos o Visual Studio Code):

```bash
EDITOR="code --wait" bin/rails credentials:edit
```

Isso abrirá o editor configurado para você editar as credenciais. Siga as instruções fornecidas no arquivo `config/credentials.yml.enc` para configurar suas credenciais.

## Instalação

1. Instale as dependências do Ruby:

```bash
bundle install
```

2. Instale as dependências do JavaScript com Yarn:

```bash
yarn install
```

3. Execute as migrações do banco de dados para criar as tabelas necessárias:

```bash
bin/rails db:migrate
```

4. Inicialize o servidor:

```bash
bin/rails server
```

A API estará acessível em `http://localhost:3000`.

## Uso

A API do Team Heroes oferece endpoints para gerenciar equipes de super-heróis. Você pode encontrar informações detalhadas sobre como usar a API na [documentação](link-para-documentação).

## Contribuição

Se desejar contribuir para este projeto, sinta-se à vontade para abrir uma _pull request_. Lembre-se de seguir as diretrizes de contribuição do projeto.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

---

Divirta-se usando a API do Team Heroes! Se tiver alguma dúvida ou encontrar problemas, não hesite em entrar em contato conosco.