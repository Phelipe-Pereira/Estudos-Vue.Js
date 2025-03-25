
# Curso de Vue.js 2 - Módulo 1

Este repositório contém o material de estudo e práticas desenvolvidas durante o **Módulo 1 do curso de Vue.js 2**, com foco nos principais fundamentos da biblioteca. O conteúdo abrange desde a instalação até a criação de componentes reutilizáveis, além de atividades práticas como a construção de um CRUD completo.

---

## 📚 Conteúdo das Aulas

### Aula 01 - Instalando Vue.js
- Conceito e características do Vue.js
- Instalação via CDN e npm
- Estrutura básica de um projeto
- Criação do primeiro app com Vue

### Aula 02 - Diretivas
- Introdução às diretivas Vue (`v-bind`, `v-model`, `v-if`, `v-else`, `v-else-if`, `v-show`, `v-for`)
- Manipulação de atributos e listas
- Condicionais na interface
- Aplicação prática com formulário de login

### Aula 03 - v-model: Interligando Formulários
- Ligação bidirecional entre dados e inputs
- Trabalhando com `input`, `radio`, `checkbox` e `select`
- Visualização em tempo real dos dados preenchidos

### Aula 04 - v-bind com Tags HTML
- Atribuição dinâmica de atributos como `src`, `alt` e `data-*`
- Interpolação com `{{ }}`

### Aula 05 - v-bind com `class` e `style`
- Manipulação de classes CSS e estilos inline de forma dinâmica
- Alternância de classes e efeitos visuais com `methods`
- Exemplos utilizando Bootstrap

### Aula 06 - v-on: Manipulando Eventos
- Uso da diretiva `v-on` e da forma abreviada `@`
- Eventos comuns: `click`, `mouseover`, `keyup`
- Modificadores `.prevent`, `.stop`, `.once`, `.self`
- Integração com formulários e tratamento de ações

### Aula 07 - Filters: Formatando Textos
- Uso de filtros para transformar dados em tempo de exibição
- Criação de filtros globais e locais
- Filtros com parâmetros e uso de pipes
- Observação: funcionalidade descontinuada no Vue 3

### Aula 08 - Computed & Watch
- Diferenças e aplicações de `computed` e `watch`
- Otimização com cache (computed)
- Execução de lógica personalizada (watch)
- Combinação dos dois em projetos práticos

### Aula 09 - Lifecycle Hooks
- Ciclo de vida de componentes Vue.js
- Hooks principais: `created`, `mounted`, `updated`, `destroyed` etc.
- Exemplos práticos com DOM e chamadas de API

### Aula 10 - Componentes Reutilizáveis
- Criação e registro de componentes Vue
- Comunicação entre componentes: `props` e `$emit`
- Componentes dinâmicos e uso de `slots`

---

## 🛠️ Projeto Prático: CRUD com Vue.js 2

### Primeira Versão
- Estruturação de um sistema de agenda simples
- Cadastro, listagem, edição e exclusão de contatos
- Uso de `v-model`, `v-for`, `v-on`, `computed`
- Lógica de alternância de modo de adição/edição

### Melhorias Adicionadas
- Mensagem de confirmação após adicionar/atualizar contatos
- Implementação de contador de contatos
- Estilização com CSS personalizada
- Feedback visual para melhor experiência do usuário

---

## 📌 Observações

- Todas as atividades foram desenvolvidas com base na versão **Vue.js 2.7.14**.
- Os projetos são simples e focam na didática do conteúdo.
- Filtros (`filters`) não são mais suportados no Vue 3, porém estão presentes aqui para fins de estudo do Vue 2.
- Para melhor depuração e visualização, recomenda-se o uso do [Vue Devtools](https://devtools.vuejs.org/).

---

## 📁 Organização

```
📂 aulas/
├── 01 - Instalando Vue.js
├── 02 - Diretivas
├── 03 - v-model com Formulários
├── 04 - v-bind com HTML
├── 05 - v-bind com Class e Style
├── 06 - v-on e Eventos
├── 07 - Filters
├── 08 - Computed e Watch
├── 09 - Lifecycle Hooks
├── 10 - Componentes Reutilizáveis

📂 pratica/
├── CRUD com Vue.js
├── CRUD com Melhorias
```

---

## ✍️ Autor

Este repositório foi criado por **Phelipe  Pereira** como parte do estudo e prática da biblioteca Vue.js 2.

---
