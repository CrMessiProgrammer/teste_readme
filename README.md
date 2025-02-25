# GestorPro - Sistema de RH 📝

<br />

<div align="center">
    <img src="https://ik.imagekit.io/a210gfzra/GestorPro/logo_rh.png?updatedAt=1740509915787" title="source: imgur.com" width="50%"/>
</div>

## 1. Descrição

*O projeto é um sistema de gestão de funcionários que facilita o cadastro e a consulta de dados essenciais, como nome, e-mail, cargo, salário e foto. Com uma interface intuitiva e responsiva, permite que os usuários realizem buscas e gerenciem informações de forma eficiente.*

------

## 2. Recursos

1. Cadastro de Funcionários – Interface intuitiva para adicionar novos colaboradores.
2. Consulta e Listagem – Exibição detalhada dos funcionários cadastrados.
3. Busca Inteligente – Filtragem rápida por nome, cargo ou e-mail.
4. Edição e Atualização – Possibilidade de modificar dados existentes.
5. Remoção Segura – Exclusão com confirmação para evitar erros acidentais.

# Features Especiais: #
1. Interface Responsiva – Adaptável para diferentes dispositivos.
2. Upload de Imagem – Inclusão de foto para melhor identificação dos funcionários.
3. Notificações e Feedback – Alertas para ações como cadastro, edição e remoção.
4. Melhorias de UX/UI – Design moderno e experiência do usuário otimizada.

------

## 3. Protótipo e Capturas de Tela



*Adicione print da tela inicial e/ou o link do protótipo no Figma (se houver)*

<div align="center">
    <img src="mudar" title="source: imgur.com" width="50%"/>
</div>

<br />

<a href="https://imgur.com/vK8ulM5"><img src="https://i.imgur.com/vK8ulM5.png" title="source: imgur.com" width="3%"/></a> [Protótipo desenvolvido no Figma](link para o Figma do Projeto)

------

## 4. Tecnologias

| Item                         | Descrição  |
| ---------------------------- | ---------- |
| **Servidor**                 | Node JS    |
| **Linguagem de programação** | TypeScript |
| **Biblioteca**               | React JS   |
| **Build**                    | Vite       |
| **Framework de Estilização** | Tailwind   |
| **Framework do Backend    ** | NestJS     |


---

## 5. Pré-requisitos

Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas:

- [Node.js](https://nodejs.org/) (v16+)
- [yarn](https://yarnpkg.com/)
- API NestJS API NestJS (https://docs.nestjs.com/openapi/introduction)

---

## 6. Configuração e Execução

1. Clone o repositório do Projeto
2. Instale as dependências: `yarn`
3. Clone o repositório do Projeto Backend: (https://github.com/Projeto-Integrador-Modelo-Gp01-Js06/rh-backend)
4. Siga as instruções de **Configuração e Execução** descritas no README do Projeto Backend
5. Adicione o endereço de execução do projeto na variável de ambiente **VITE_API_URL**, no projeto React
6. Execute o Projeto React: `yarn dev`
7. A aplicação React estará disponível no endereço: `http://localhost:5173`

---

## 7. Estrutura do Projeto

```plaintext
src/
│
├── components/       # Componentes reutilizáveis
├── contexts/         # Gerenciamento de estado global (ex: autenticação)
├── models/           # Estrutura de dados da aplicação-
├── pages/            # Páginas da aplicação
├── services/         # Integração com a API (requisições HTTP)
├── utils/            # Funções auxiliares (alerts)
└── App.tsx           # Componente principal da aplicação
```

---

## 8. Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch com a sua feature (`git checkout -b minha-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Faça um push para a branch (`git push origin minha-feature`)
5. Abra um Pull Request
