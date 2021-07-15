# mini_payroll_app

O desafio : 
- Criar, vizualizar e remover fichas de funcionário;
- Processar salário com informação das fichas de funcionário previamente criadas;
- Bases de dados em SQL

            


![Image of Yaktocat](https://github.com/sergiomsgoncalvs/mini_payroll_app/blob/main/Menu%20principal.PNG)




O ecrã “Ficha de Funcionário” que é dividido por duas secções:

Na primeira secção é apresentado um formulário para inserção de dados do funcionário, após o seu preenchimento o utilizador pode adicionar ou atualizar um funcionário à base de dados através do botão “Gravar”. Caso pretenda o utilizador pode limpar as TextBoxs preenchidas ao clicar no botão “Limpar”.
É também possível eliminar fichas de funcionários à escolha do utilizador, devendo para isso selecionar o número interno do funcionário na NumericUpDown e após a sua escolha clicar no botão “Apagar”.


Na segunda secção é apresentada uma GridView que mostra os dados presentes na base de dados. A visualização dos dados pode ser filtrada por delegação ao escolher umas das delegações na ComboBox ou ao clicar no botão “Mostrar tudo” onde todas as fichas de funcionário serão exibidas. De mencionar que as alterações nas fichas de funcionário através dos botões “Gravar” e “Apagar” são alteradas em tempo real na GridView.

![Image of Yaktocat](https://github.com/sergiomsgoncalvs/mini_payroll_app/blob/main/Ficha%20funcionario.PNG)


O ecrã “Processamento”:

Após os dados obrigatórios serem inseridos pelo utilizador este deve de clicar no botão “Processar”, este botão vai recolher das TextBoxs os dados necessário para os cálculos para obter o salário líquido. Foram criadas variáveis na função do botão “Processar” para efetuar os cálculos de uma forma mais simplificada, devolvendo-os para outros campos presentes na GroupBox.


![Image of Yaktocat](https://github.com/sergiomsgoncalvs/mini_payroll_app/blob/main/Processamento.PNG)

Após os cálculos serem efetuados e apresentados o utilizador deve de clicar no botão “Gravar” para inserir os dados na Base de dados. De seguida deve de clicar no botão “Extrair Bin” para que os dados do processamento sejam exportados para um ficheiro binário que será criado com nome do mês e ano a que se refere o processamento. Caso já existe um ficheiro para esse mês e ano a informação é adicionada ao ficheiro já existente.
