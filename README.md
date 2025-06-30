# CRUD-JavaScript-LocalStorage
Este projeto é uma aplicação web simples que implementa operações CRUD (Create, Read, Update, Delete) para gerenciamento de usuários, utilizando **JavaScript puro** e **LocalStorage** para persistência de dados no navegador.

## 📋 Funcionalidades

- ✅ Criar um novo usuário
- 📄 Listar todos os usuários
- ✏️ Editar usuários existentes (atualização completa ou parcial)
- ❌ Excluir usuários
- 💾 Armazenamento persistente com `localStorage`

## 🧠 Tecnologias Utilizadas

- HTML
- CSS (pode ser incluído à parte)
- JavaScript (vanilla)
- Armazenamento local (`localStorage`)

## 💡 Como Funciona

### Estrutura do Objeto `usuario`

```js
{
  id: Number,       // Gerado automaticamente com base no timestamp
  nome: String,
  email: String,
  idade: String
}
Principais Funções
createUsuario(usuario): Cria um novo usuário e o salva no localStorage.

listarUsuarios(): Lista todos os usuários na tela.

updateUsuario(id, novoUsuario): Atualiza completamente os dados de um usuário.

patchUsuario(id, campo, valor): Atualiza apenas um campo específico de um usuário.

deleteUsuario(id): Remove um usuário pelo ID.

editarUsuario(id): Carrega os dados do usuário selecionado no formulário para edição.

🧪 Como Usar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/gerenciador-usuarios.git
Abra o arquivo HTML no seu navegador.

Preencha o formulário com os dados do usuário e envie.

Use os botões "Editar" e "Excluir" para manipular os dados da lista.

🗂 Estrutura Esperada do HTML
Certifique-se de que o HTML tenha os seguintes elementos com os respectivos ids:

Um formulário com campos:

#usuarioId (input hidden)

#nome

#email

#idade

Um elemento <ul id="listaUsuarios"></ul> para exibir os usuários
