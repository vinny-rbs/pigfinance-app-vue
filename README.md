# PigFinance - Interface Web para Controle Financeiro

Sistema de controle financeiro pessoal desenvolvido para organizar receitas e despesas de forma estruturada, com categorização de movimentações financeiras. A aplicação apresenta design moderno, responsivo e acessível, proporcionando maior controle, visibilidade e gestão eficiente dos fluxos financeiros, auxiliando o usuário na tomada de decisões financeiras.

---

## Tecnologias

* Html, Css, JavaScript / Vue.js
* Figma / Design System
* Typescript
  

---

## Estrutura do Projeto

````
financontrol-ui/
├── public/ # Arquivos estáticos
├── src/
│ ├── assets/ # Imagens, ícones e Css base
│ ├── components/ # Componentes reutilizáveis da UI
│ ├── router/ # Rotas da aplicação (Vue Router)
│ ├── view/ # Páginas principais da aplicação
│ ├── diretivas/ # diretivas vue, comportamentos que um elemento deve ter.
│ ├── App.vue # Componente raiz
│ └── main.ts # Ponto de entrada da aplicação
├── .gitignore # Arquivos ignorados pelo Git
├── package.json # Metadados e dependências do projeto
└── README.md # Documentação do projeto
````

---

## Integração com a API

A interface consome os dados da API [Finance API (Go)](https://github.com/mth-ribeiro-dev/finance-api-go/tree/master), que fornece os endpoints REST para:

- Listar transações
- Adicionar e excluir receitas/despesas
- Calcular saldo total
- (Futuramente) autenticação de usuários

A base da API está configurada em:  
`src/cmd/server/main.go`

---

## Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/vinny-rbs/MyFinance_Gerencia-de-Financas.git

# Acesse a pasta do projeto
cd Gerencia-de-Finan-as---MyFinance

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
A aplicação estará disponível em http://localhost:5173.
```
## Funcionalidades

* Cadastro de receitas e despesas

* Visualização de saldo e lista de transações

* Filtros por data e tipo de transação

* Layout responsivo (mobile e desktop)

* Gráficos interativos com Chart.js (em breve)

* Exportação de relatórios em PDF (em breve)

## Boas Práticas Adotadas

Componentização com foco em reutilização e manutenção

Organização modular em pastas claras e separadas

Consumo de API externas

Responsividade e acessibilidade básica aplicada

## Autor

Desenvolvido por:

Vinicius Ribeiro – [vinny-rbs](https://github.com/vinny-rbs)

Contato: viniciusjunioribeiro05@gmail.com


## Contribuição

Contribuições são bem-vindas!
Sinta-se à vontade para abrir uma issue ou enviar um pull request.
