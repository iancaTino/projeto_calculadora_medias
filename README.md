# Calculadora de Médias 📊
Este projeto consiste em uma calculadora de médias que permite ao usuário adicionar atividades e suas respectivas notas. A aplicação calcula a média das notas inseridas e verifica automaticamente se o aluno foi aprovado ou reprovado em cada atividade, com base em uma nota mínima que pode ser definida pelo usuário.

## Objetivo do Projeto:
Permitir que o usuário adicione o nome da atividade e a nota de cada atividade.

Exibir se o aluno foi aprovado ou reprovado em cada atividade, de acordo com a nota mínima.

Calcular a média final das atividades e indicar se o aluno foi aprovado ou reprovado com base na média.

## Como Funciona:
O usuário insere o nome da atividade e a nota no formulário.

Ao clicar em "Adicionar +", a atividade é registrada e exibida em uma tabela.

O sistema verifica se a nota da atividade é maior ou igual à nota mínima definida pelo usuário. Caso contrário, a atividade é marcada como reprovada.

A média final é calculada automaticamente com base nas notas inseridas, e o status de aprovado ou reprovado é exibido.

## Componentes e Funcionalidades:
HTML: Estrutura do formulário, tabela para exibição das atividades e nota, e a área onde a média final é exibida.

CSS: Estilo para o layout da página, incluindo a formatação dos campos de entrada, tabela e botões.

JavaScript: Lógica para adicionar atividades, calcular a média das notas e determinar a aprovação ou reprovação, atualizando a interface conforme o usuário interage.

## Tecnologias Utilizadas:
HTML: Estrutura básica da página e dos formulários.

CSS: Estilo visual, tornando a interface mais agradável e fácil de usar.

JavaScript: Lógica para adicionar, calcular e exibir as notas, além da interação com o usuário.

## Exemplo de Interação:
O usuário insere uma atividade com a nota 8. Se a nota mínima for 6, a atividade será marcada como aprovada.

Se o usuário inserir uma atividade com a nota 4 e a nota mínima for 6, a atividade será marcada como reprovada.

A média das notas será calculada, e o status de aprovação será exibido na parte inferior da tabela.

Resultado Esperado:
Cada linha da tabela mostrará o nome da atividade, a nota da atividade e o status (Aprovado ou Reprovado) com emojis de celebração ou tristeza.

A média final será atualizada automaticamente conforme novas atividades forem adicionadas, e o status final de aprovação será exibido.

