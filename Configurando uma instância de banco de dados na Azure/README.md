# Criando um banco de dados em SQL

Este projeto consiste na criação de um banco de dados em SQL na Azure com configurações básicas, visando testar e demonstrar o processo de provisionamento de recursos na plataforma. Para realizar este procedimento, é imprescindível que o usuário tenha uma conta ativa no Azure.

## Acessando recurso na AZURE

Para criar um banco de dados em SQL na Azure, comece realizando o login no portal do Azure. No menu à esquerda, clique em Banco de dados SQL. Um painel com todos os bancos de dados existentes será exibido. Conforme imagem.

- Painel de Banco de Dados da AZURE

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Configurando%20uma%20inst%C3%A2ncia%20de%20banco%20de%20dados%20na%20Azure/imagens/Banco%20de%20Dados%20SQL.png">
</div>

Em seguida, selecione a opção criar, para ser direcionado ao painel de criação de banco de dados.

- Painel de criação de Banco de Dados SQL na Azure

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Configurando%20uma%20inst%C3%A2ncia%20de%20banco%20de%20dados%20na%20Azure/imagens/Configura%C3%A7%C3%A3o%20do%20Banco%20de%20Dados.png">
</div>

No painel de criação de Banco de dados SQL, o usuário deverá configurar a seu Banco de Dados para atender aos requisitos do projeto. Para este laboratório será criado um Banco de Dados para efeitos de demostração. 

# Configurações do banco de Dados

    Detalhes do projeto
   
    - Assinatura: Assinatura do Azure 1
    - Grupo de recursos: lab-01

    Detalhes do banco de dados

    - Nome do banco de dados: Teste
    - Servidor: teste01 (East US)
    - Deseja usar o pool elástico SQL: Não
    - Ambiente de carga de trabalho: Desenvolvimento
    - Computação + Armazenamento: Uso Geral - Sem servidor Série Standard (Gen5), 1 vCore, 32 GB de armazenamento
    - Redundância do armazenamento de Backup: Armazenamento de backup com redundância local

- Configuração do Banco de Dados

<div aling="center">
 <img src="">
</div>


- Painel de criação do servidor

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Configurando%20uma%20inst%C3%A2ncia%20de%20banco%20de%20dados%20na%20Azure/imagens/Cria%C3%A7%C3%A3o%20de%20servidor.png">
</div>

Após as configurações terem sido preenchidas deve se ir na aba **Revisar + criar**, para validar se as configurações definidas permitem a criação da maquina vitrual.

- Validação das configurações

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Configurando%20uma%20inst%C3%A2ncia%20de%20banco%20de%20dados%20na%20Azure/imagens/Validando%20configura%C3%A7%C3%B5es.png">
</div>

Após a aprovação das configurações, o próximo passo é a criação do banco de dados.

- Criação do banco de dados.

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Configurando%20uma%20inst%C3%A2ncia%20de%20banco%20de%20dados%20na%20Azure/imagens/Implanta%C3%A7%C3%A3o%20do%20banco%20de%20dados.png">
</div>

Após criação do banco de dados SQL, o mesmo estará disponível no painel todos recursos, que permitirá o acesso a banco de dados e a eventual utilização para finalidade a que se destina.

- Acesso ao banco de dados SQL.

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Configurando%20uma%20inst%C3%A2ncia%20de%20banco%20de%20dados%20na%20Azure/imagens/Banco%20de%20dados%20Teste.png">
</div>

Após a confirmação da criação do banco de dados banco de dados SQL para fins didáticos, o mesmo foi excluído de forma a evitar cobraças futuras por sua utilização.

## Autor

- [Frederico S N Cota](https://github.com/FredericoSander)
