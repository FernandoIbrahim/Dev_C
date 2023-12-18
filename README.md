

# Party Hall Program Manager

Projeto desenvolvido no primeiro semestre do curso de Engenharia de Software entre as disciplinas de Algoritmos e Desenvolvimento Sistemas  I e Fundamentos de Engenharia de Software
## Descrição do Projeto

O sistema de controle e gestão para lidar com desafios operacionais de um salao de Festas, como conflitos de horários para festas e a falta de armazenamento eficiente de dados de clientes e fornecedores. O projeto visa solucionar esses problemas, proporcionando uma gestão eficaz das festas realizadas no salão.

## Funcionalidades do Sistema

1. **Cadastro de Cliente:**
   - Função para cadastrar um cliente com informações como código, nome, endereço, telefone, e data de nascimento. Garante unicidade de códigos.

2. **Cadastro de Fornecedor:**
   - Função para cadastrar um fornecedor, incluindo código, nome do buffet, e telefone. Garante unicidade de códigos.

3. **Cadastro de Festa:**
   - Função para cadastrar uma festa, exigindo código do cliente, quantidade de convidados, data, horário, tema e fornecedor. Garante a inexistência de festas em conflito de horários.

4. **Cálculo de Valor de Festa:**
   - Função para calcular o valor total e final da festa, baseado nas tabelas fornecidas, considerando a forma de pagamento. Atualiza o status do contrato como "a pagar".

5. **Atualização de Status do Contrato:**
   - Função para atualizar o status do contrato do cliente para "pago" ou "cancelado".

6. **Pesquisas no Sistema:**
   - a. Busca de informações do cliente por nome ou código.
   - b. Busca de informações de fornecedores por nome ou código.

7. **Relatório de Festas por Cliente:**
   - Função para exibir todas as festas de um cliente específico.

8. **Relatório Detalhado de Festa:**
   - Função para mostrar informações de uma festa a partir de uma data, incluindo detalhes do contrato, valor total e final.



## Como Executar o Sistema

1. Compile o código em C.
2. Execute o programa principal.
3. Siga o menu apresentado para cadastrar clientes, fornecedores, festas, realizar pesquisas, calcular valores e atualizar contratos.
4. O sistema persistirá as informações em arquivos de texto.

Divirta-se organizando festas no Salão Patati Patatá! 🎉
