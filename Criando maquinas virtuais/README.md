# Criando uma Maquina Virtual 

Este projeto consiste na criação de uma Máquina Virtual no Azure com configurações básicas, visando testar e demonstrar o processo de provisionamento de recursos na plataforma.

Para realizar este procedimento, é imprescindível que o usuário tenha uma conta ativa no Azure.

## Acessando recurso no AZURE

Para criar uma máquina virtual no Azure, primeiro faça login no portal do Azure. No menu à esquerda, selecione Criar um Recurso. Isso abrirá um painel exibindo todos os recursos disponíveis para criação, como mostrado na imagem

- Painel de criação de recursos do Azure

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Criando%20maquinas%20virtuais/Imagens/Criar%20Recursos.png">
</div>

Em seguida, selecione a opção Máquina Virtual e clique em Criar.

- Painel de criação de maquina virtual

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Criando%20maquinas%20virtuais/Imagens/Cria%20maquina%20virtual.png">
</div>

No painel de criação de máquina virtual, o usuário deve configurar a máquina para atender aos requisitos específicos do projeto. Para este laboratório, será criada uma máquina virtual com configurações básicas, destinadas exclusivamente para fins de demonstração. 


# Configurações da Maquina Virtual

### Básico

    Detalhes de instâncias

    - Nome da Máquina: Teste
    - Região: (US) East US
    - Opções de disponibilidade: Zonas de disponibilidade
    - Opções de Zonas: Zona auto-selecionada
    - Zona de disponibilidade: Zona 1
    - Tipo de segurança: Computadores virtuais de inicialização confiável
    - Imagem: Ubuntu Server 2.044 LTS - x64 Gen2
    - Arquitetura de VM: x64
    - Tamanho: Standard_B1s - 1 vcpu, 1 GiB memória (US$ 7,59/mês) (serviços gratuitos qualificados)
       
    Conta Administrador

    - Tipo de autenticação: Chave Pública de SSH

### Rede 
Na aba Rede, foi necessário criar uma Rede Virtual para habilitar a conectividade das portas da máquina. A rede foi nomeada como teste_criacao.

    Interface de rede
  
    - Rede virtual: Teste_criação

- Criação da rede virtual

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Criando%20maquinas%20virtuais/Imagens/Cria%C3%A7%C3%A3o%20de%20rede%20virtual.png">
</div>

Após preencher todas as configurações, vá até a aba Revisar + criar para validar se as definições permitem a criação da máquina virtual.

- Validação das configurações

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Criando%20maquinas%20virtuais/Imagens/Valida%C3%A7%C3%A3o.png">
</div>

Após a aprovação das configurações, o próximo passo é a criação propriamente dita da maquina virtual.

- Criação da máquina virtual.

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Criando%20maquinas%20virtuais/Imagens/implanta%C3%A7%C3%A3o%20em%20andamento.png">
</div>

Após a criação, a máquina virtual estará disponível no painel Todos os recursos, onde será possível acessá-la e utilizá-la conforme o objetivo definido.

- Acesso a máquina virtual.

<div aling="center">
 <img src="https://github.com/FredericoSander/Azure_Essentials/blob/main/Criando%20maquinas%20virtuais/Imagens/Vis%C3%A3o%20do%20recurso.png">
</div>

Após a confirmação da criação da máquina virtual para fins didáticos, ela foi paralisada e, posteriormente, excluída para evitar cobranças futuras por seu uso.

## Autor

- [Frederico S N Cota](https://github.com/FredericoSander)