# Criando-a-Primeira-VPC-e-M-quina-Virtual-pelo-Console-GCP

Vamos explorar como criar máquinas virtuais e redes VPC no **Google Cloud Platform (GCP)**. Aqui estão os passos para criar uma máquina virtual e uma rede VPC:

## Criando uma Rede VPC no GCP

1. Acesse o **Console do GCP** em [console.cloud.google.com](https://console.cloud.google.com/).
2. Na seção **Compute**, no sub-menu **Compute Engine**, clique em **VM Instances**.
3. Isso abrirá a página do serviço **Google Compute Engine**. No lado esquerdo, encontraremos outros produtos do serviço. Por enquanto, clique em **"Create"** para começar a criar sua rede VPC.

## Configurando a Rede VPC

1. Na tela de criação da rede VPC, dê um nome à sua nova rede. Por exemplo, você pode usar o nome "vpc-geral".
2. Podemos também adicionar descrições detalhadas sobre a rede e ativar o IPv6, se necessário.
3. Abaixo, podemos criar sub-redes. Essas sub-redes serão usadas pelas VMs, Google Kubernetes Engine (GKE) e outros recursos que precisam de uma VPC.
4. Configure o intervalo de endereços IPv4 usado pelas sub-redes.
5. Ative o acesso privado e os registros de fluxo da VPC, se necessário.
6. Finalize a criação da sua rede e sub-rede.

## Criando uma Máquina Virtual no Compute Engine

1. Acesse o **Console do GCP**.
2. Clique em **"Criar uma VM"** no dashboard ou vá até a opção **"Compute Engine"** no menu lateral esquerdo.
3. Na nova tela, dê um nome à sua VM e escolha a região e zona onde ela estará alocada.
4. Escolha o tipo de instância (por exemplo, T2 ou T3 micro) e configure outras opções conforme necessário.
5. Clique em **"Criar instância"** para criar sua máquina virtual.

Para conectar à sua máquina virtual (VM) no **Google Cloud Platform (GCP)**, siga os passos abaixo:

1. **Defina um usuário e senha** para acesso à VM:
    - No **Console do GCP**, acesse a lista de máquinas virtuais.
    - Clique na seta ao lado da VM desejada e selecione **"Configurar a senha do Windows"**.
    - Configure o usuário e uma senha será gerada automaticamente pela plataforma. Guarde esses dados.

2. **Conecte à máquina**:
    - Use uma ferramenta como o **Remote Desktop Connection (RDP)** para se conectar à VM.
    - Insira o **endereço IP externo** da VM e as credenciais de usuário e senha definidas anteriormente.

3. **Finalize**:
    - Agora estará conectado à sua máquina virtual no GCP!

Lembre-se de ajustar as configurações conforme suas necessidades específicas.
