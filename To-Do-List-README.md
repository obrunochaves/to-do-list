
# To-Do List

## Sobre o Projeto

Essa é uma aplicação simples de lista de tarefas (“To-Do List”) desenvolvida com foco no aprendizado e implementação de funcionalidades em **JavaScript**. O objetivo principal é permitir ao usuário adicionar e remover tarefas de forma dinâmica, proporcionando uma interface limpa e funcional.

## Funcionalidades

### 1. **Adicionar Tarefas**
- O usuário pode digitar uma tarefa no campo de entrada e clicar no botão "Adicionar".
- A tarefa será adicionada à lista (é criada dinamicamente um elemento `<li>`).

### 2. **Remover Tarefas**
- Cada tarefa adicionada possui um botão de exclusão (“❌”).
- Ao clicar no botão de exclusão, a tarefa é removida da lista.

### 3. **Interface Responsiva e Estilizada**
- A aplicação utiliza a fonte **Poppins** e cores agradáveis para criar uma experiência visual moderna.

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página.
- **CSS3**: Estilização responsiva e customizada.
- **JavaScript**: Manipulação dinâmica do DOM para adicionar e remover tarefas.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/obrunochaves/to-do-list.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd to-do-list
   ```

3. Abra o arquivo **index.html** no navegador:
   - Basta clicar duas vezes no arquivo ou abrir via terminal com um comando como:
     ```bash
     start index.html
     ```

## Estrutura do Projeto

```
.
├── index.html      # Estrutura da aplicação.
├── styles.css      # Estilos para o layout.
├── script.js       # Funções JavaScript para manipulação da lista.
├── img/            # Pasta com o ícone utilizado como favicon.
```

## Funcionalidades em Destaque

- **Adicionar tarefa:** A função `adicionarTarefa()` captura o valor do campo de entrada e o insere como um novo item na lista.
- **Remover tarefa:** A função `deletarTarefa(element)` utiliza o `parentElement` para localizar e remover o item correspondente.

## Melhorias Futuras

- Adicionar persistência de dados usando **localStorage** para salvar as tarefas mesmo ao atualizar a página.
- Implementar um sistema de marcação para tarefas concluídas.
- Melhorar a responsividade para dispositivos menores.

## Autor

Desenvolvido por **Bruno Chaves**.

Acesse o repositório do projeto [aqui](https://github.com/obrunochaves/to-do-list) e sinta-se à vontade para contribuir! 😄
