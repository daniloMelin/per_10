# Atividade Prática Módulo 10 - Versionando o projeto template 

# Modificações no Código

## ListarTarefa.jsx

1. **Estados Adicionados**: Implementação dos estados **`historicoTarefas`** e **`mostrarHistorico`** para gerenciar e controlar a exibição do histórico de tarefas.
2. **Botão "Mostrar Histórico"**: Inclusão de um botão para alternar a visualização do histórico de tarefas.
3. **Bloco de Tabela Adicional**: Criação de um segundo bloco de tabela para exibir o histórico de tarefas quando **`mostrarHistorico`** estiver ativo.
4. **Lógica de Exclusão Modificada**: Ajuste na lógica de exclusão para mover tarefas concluídas para o histórico em vez de removê-las definitivamente.

## Criação do AlertDialog.jsx

1. **Novo Componente 'AlertDialog'**: Criação de um componente para exibir diálogos de confirmação.
2. **Propriedades Recebidas**: Configuração para receber as propriedades **`open`**, **`handleClose`**, **`handleConfirm`**, **`title`** e **`description`**.
3. **Utilização do Material-UI**: Uso do componente **`Dialog`** do Material-UI para a exibição do diálogo.
4. **Exibição de Título e Descrição**: Inclusão de título e descrição no corpo do diálogo.
5. **Botões de Ação**: Adição de botões para confirmar ou cancelar a operação.

## Adição do Componente AlertDialog no ListarTarefa.jsx

1. **Integração do 'AlertDialog'**: Inclusão do componente **`AlertDialog`** para exibir um diálogo de confirmação antes da exclusão de uma tarefa.
2. **Implementação de Diálogo de Confirmação**: Configuração do **`AlertDialog`** para aparecer ao tentar excluir uma tarefa.
3. **Lógica de Abertura e Fechamento**: Desenvolvimento da lógica para abrir e fechar o diálogo de confirmação conforme necessário.

# Modificações dos Estilos

## App.css

1. **Estilização Alternada de Linhas**: Adição das classes **`.table-row-even`** e **`.table-row-odd`** para aplicar estilos alternados às linhas da tabela, melhorando a legibilidade.
