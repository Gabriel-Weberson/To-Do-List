# **To-Do List com Gerenciamento de Projetos**

## **Descrição**
Este é um projeto completo de gerenciamento de tarefas no formato **To-Do List**, desenvolvido com **Node.js (Express)** no backend e **Vue.js** no frontend. Ele permite criar e gerenciar **projetos**, adicionar **tarefas** organizadas por status (`To Do`, `In Progress` e `Complete`), além de registrar automaticamente a data de criação e finalização de cada tarefa.

---

## **Funcionalidades**
- **Gerenciamento de Projetos**:
  - Criar, visualizar e deletar projetos.
- **Gerenciamento de Tarefas**:
  - Adicionar tarefas com título e status.
  - Editar e excluir tarefas.
  - Alterar o status das tarefas entre `To Do`, `In Progress` e `Complete`.
  - Exibir datas de criação e finalização para tarefas concluídas.
- **Interface Intuitiva**:
  - Colunas coloridas para organizar tarefas:
    - 🔵 Azul: `To Do`
    - 🟠 Laranja: `In Progress`
    - 🟢 Verde: `Complete`

---

## **Tecnologias Utilizadas**
### **Backend**:
- Node.js com Express.js para criação da API.
- CORS para comunicação entre frontend e backend.

### **Frontend**:
- Vue.js para interface dinâmica.
- CSS para design responsivo e estilização.
- Axios para consumo da API.

### **Outras Ferramentas**:
- JSON para armazenamento de dados temporários.

---

## **Como Executar**

1. Execute o terminal dentro da pasta do Backend e envie o seguinte comando: node index.js
2. Execute o terminal dentro da pasta do Frontend e envie o seguinte comando: npm run serve
