# Olá, Mundo! em Python

Este é um exemplo simples de script em Python que imprime "Olá, mundo!" no console.

## Como usar

1. Clone este repositório ou copie o arquivo `hello_world.py`.
2. Execute o script usando o Python:

```bash
python hello_world.py
```

## Exemplo de código

```python
print("Olá, mundo!")
```

## Requisitos

- Python 3.x instalado

## Licença

Este projeto está licenciado sob a licença MIT.

# TaskManager

TaskManager é uma aplicação simples para gerenciamento de tarefas, construída com Node.js, Express e MongoDB. Ela permite criar, listar, atualizar e remover tarefas de forma rápida e eficiente.

## Recursos

- Cadastro de tarefas com título e descrição
- Listagem de todas as tarefas
- Marcar tarefas como concluídas
- Remover tarefas
- Interface de API RESTful

## Tecnologias Utilizadas

- Node.js
- Express
- MongoDB
- Mongoose

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/taskmanager.git
   cd taskmanager
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure as variáveis de ambiente (opcional):

   Crie um arquivo `.env` com o seguinte conteúdo:
   ```
   MONGODB_URI=mongodb://localhost:27017/taskmanager
   PORT=3000
   ```

4. Inicie o servidor:
   ```bash
   npm start
   ```

## Uso

A API estará disponível em `http://localhost:3000`.

### Endpoints principais

- `GET /tasks` — Lista todas as tarefas
- `POST /tasks` — Cria uma nova tarefa
- `PUT /tasks/:id` — Atualiza uma tarefa existente
- `DELETE /tasks/:id` — Remove uma tarefa

### Exemplo de requisição

```bash
curl -X POST http://localhost:3000/tasks \
  -H "Content-Type: application/json" \
  -d '{"title": "Comprar pão", "description": "Ir na padaria comprar pão"}'
```

## Contribuindo

Sinta-se à vontade para abrir issues ou enviar pull requests!

## Licença

Este projeto está licenciado sob a licença MIT.
