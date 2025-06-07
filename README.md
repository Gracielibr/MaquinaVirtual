# Maquina Virtual
<img align="right" height="200" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTBqt_P4TlhuvChBf9ERGgpe1Qj5EJFdnuAXg&s">


Este trabalho é um desafio da DIO para praticar o processo de criação e configuração de uma máquina virtual na plataforma Microsoft Azure.


## O que é uma Máquina Virtual (VM)?
Uma máquina virtual (VM) é um ambiente virtual criado por meio de software para imitar um computador físico. Ela funciona dentro de um computador real, permitindo a execução de várias máquinas virtuais simultaneamente, como se um único hardware físico estivesse dividido em múltiplos sistemas virtuais. A VM comporta-se como uma máquina real, replicando todas as funcionalidades de um computador físico, incluindo processamento, armazenamento e rede, como se fosse um computador separado. Por isso, é comum descrevê-la como um 'computador dentro de outro computador'.
Entre suas principais aplicações, destacam-se: a execução de múltiplos sistemas operacionais em um mesmo hardware, o isolamento e segurança, os testes de desenvolvimento de software, a virtualização na nuvem, a preservação de sistemas legados, a consolidação de servidores, entre outras. Deste modo, as VMs não apenas economizam tempo, espaço e energia, mas também atendem a múltiplas finalidades computacionais.

## Crianddo uma VM na Microsoft Azure
<img align="right" height="200" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Microsoft_Azure.svg/1200px-Microsoft_Azure.svg.png">

###  Acesso à Plataforma
Para criar uma máquina virtual no Microsoft Azure, o primeiro passo é realizar o cadastro na plataforma. Após acessar a página inicial, basta posicionar o cursor do mouse sobre o ícone de máquina virtual para que seja exibida uma janela com um tutorial explicativo sobre o processo de criação, um recurso extremamente valioso para usuários que estão começando.
<div align="center">
  <p><strong>Tela do portal Azure mostrando o tutorial</strong></p>
  <img src="https://github.com/user-attachments/assets/b156eef2-b09b-4f7d-8cff-7a75bbd952e9" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>
Esse tutorial guia o usuário através das etapas necessárias, desde a configuração básica até a implantação final da máquina virtual, garantindo uma experiência mais intuitiva e acessível. A interface do Azure foi projetada para facilitar a navegação, com dicas e orientações que ajudam tanto iniciantes quanto usuários avançados a aproveitar ao máximo os recursos disponíveis.

###  Criando uma Maquina Virtual

Para criar uma máquina virtual na plataforma Microsoft Azure, localize e clique no ícone com o símbolo "+ Criar recurso" no painel de navegação. Ao selecionar essa opção, será exibida uma lista com os serviços mais populares disponíveis, onde você deverá escolher a alternativa "Máquina virtual" para iniciar o processo de configuração.
<div align="center">
  <p><strong>Tela do portal Azure Criar Recurso</strong></p>
  <img src="https://github.com/user-attachments/assets/479dbbca-d592-4745-80a7-a310e5cb88ca" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>
Essa ação direciona você para a página de configuração inicial, onde será possível definir os parâmetros básicos da sua máquina virtual antes de prosseguir com a implantação.
Ao acessar a tela de configuração inicial, você encontrará diversas opções para personalizar sua máquina virtual de acordo com as necessidades do seu projeto. Neste exemplo, optei por seguir as recomendações do tutorial oficial fornecido pela Microsoft Azure, que oferece um guia passo a passo para configuração adequada dos parâmetros.

<div align="center">
  <p><strong>Tela do portal Azure Criando uma maquina virtual</strong></p>
  <img src="https://github.com/user-attachments/assets/fc6523c1-f7e8-4d1d-947e-cb114de0d6ce" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>
Nesta etapa, é importante dedicar atenção especial às configurações básicas como sistema operacional, tamanho da instância e credenciais de acesso, garantindo que a máquina virtual seja criada com os recursos adequados para sua finalidade específica. 

Antes de finalizar a criação da máquina virtual, o Azure apresenta uma tela de revisão com todos os detalhes configurados anteriormente. Neste momento, o sistema mostra claramente os valores que serão cobrados pelo uso dos recursos selecionados, seguindo o modelo de pagamento conforme o uso que caracteriza os serviços em nuvem.
<div align="center">
  <p><strong>Tela do portal Azure Criando uma VM</strong></p>
  <img src="https://github.com/user-attachments/assets/f88c9e09-bc7d-48f4-87e7-6efe61770aaf" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>
Esta visualização permite conferir cuidadosamente todas as especificações técnicas e principalmente o custo estimado antes de confirmar a implantação. É a última oportunidade para ajustar qualquer configuração que não esteja adequada às necessidades do projeto ou ao orçamento disponível, garantindo que você só pague pelos recursos que realmente necessita utilizar.

Após a confirmação das configurações, inicia-se imediatamente o processo de implantação dos recursos para sua máquina virtual. A tela exibida apresenta uma visão detalhada do progresso, com uma barra de status que avança conforme cada etapa é concluída, permitindo acompanhar em tempo real a criação da sua VM.
<div align="center">
  <p><strong>Tela do portal Azure Criando uma VM</strong></p>
  <img src="https://github.com/user-attachments/assets/294f6dd0-f42d-41f1-a751-1c831282b0c0" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>
A interface apresenta de forma clara e organizada cada fase do processo. Esse procedimento normalmente leva alguns minutos para ser concluído, com mensagens precisas que indicam quando o sistema está configurando os componentes de rede, preparando o armazenamento ou alocando os recursos de computação. Durante todo esse período, o processo é totalmente automático, não requerendo nenhuma ação adicional por parte do usuário, que pode aguardar tranquilamente até que todos os recursos estejam completamente disponíveis para uso.

Quando a implantação for concluída com sucesso, será exibida uma mensagem de confirmação e sua máquina virtual estará pronta para uso. Neste momento, todos os recursos selecionados estão completamente configurados e disponíveis para acesso imediato.

<div align="center">
  <p><strong>Tela do portal Azure Criando uma VM</strong></p>
  <img src="https://github.com/user-attachments/assets/4dc3de56-6552-4159-a186-792ec88ac188" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>
Para começar a usar sua máquina virtual, clique no botão "Ir para o recurso". Você será levado diretamente ao painel de controle principal da VM, onde poderá acessar todas as funcionalidades e configurações imediatamente.

### Explorando a Máquina Virtual

Com a máquina virtual criada e em execução, o portal do Azure passa a oferecer um ambiente completo de controle e gerenciamento. A interface está dividida em duas áreas principais. À esquerda, encontra-se o menu de navegação da infraestrutura, que reúne todas as opções essenciais para administrar o ambiente, como Máquinas Virtuais, Discos, Instantâneos, Conjuntos de Criptografia de Disco, entre outros. Esse painel oferece acesso rápido e organizado aos principais recursos da infraestrutura em nuvem.
<div align="center">
  <p><strong>Tela do portal Azure VM Criada </strong></p>
  <img src="https://github.com/user-attachments/assets/7c0b00d4-f1e7-4c0a-89c3-bf303b80d1ac" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>
À direita, está o painel de detalhes da máquina virtual selecionada. Nele, são exibidas informações fundamentais da VM, como o nome (neste caso, "teste-vp-vm2"), o status atual (em execução), o sistema operacional (Windows Server 2022 Datacenter), o tamanho da instância (E2s v3 com 2 vCPUs e 16 GiB de RAM), o endereço IP público, o grupo de recursos ao qual a VM pertence e a região em que está hospedada (Brasil Sul – Zona 1). Também é possível visualizar dados sobre a rede associada, como sub-rede, IP privado e nome DNS, além de acessar controles importantes, como conectar, reiniciar, parar, capturar imagem da VM ou excluí-la.
Esse painel central oferece uma visão clara e detalhada da máquina virtual e permite que sejam feitas diversas configurações, como ajustar o sistema operacional, adicionar discos, configurar regras de rede, monitorar o desempenho, habilitar integrações e reforçar a segurança. Todos esses recursos estão organizados nas seções laterais de "Rede", "Configurações" e "Operações", proporcionando uma navegação intuitiva e eficiente para o gerenciamento completo da VM.

Dentre os recursos disponíveis, destaca-se a seção de tutoriais, especialmente útil para quem está começando. Esta funcionalidade está posicionada na parte inferior direita do painel principal, ao lado dos ícones de "Propriedades", "Monitoramento", "Funcionalidades" e "Recomendações", sendo facilmente reconhecível pelo ícone identificado como "Tutoriais". Esta seção oferece uma coleção abrangente de guias práticos e materiais de apoio.
<div align="center">

  <p><strong>Tela do portal Azure Tutorias para treinamento gratuito</strong></p>
  <img src="https://github.com/user-attachments/assets/93524c2e-da7a-4e9a-ab3e-2612c7a41681" 
       alt="Captura de tela do painel de VMs do Azure" 
       width="600" 
       height="450">
</div>

Esses materiais de aprendizado abrangem desde conceitos fundamentais para iniciantes até configurações avançadas para usuários experientes. O acesso é imediato e gratuito, integrado diretamente ao ambiente de gerenciamento da VM, o que permite aprender enquanto configura e opera sua máquina virtual. 


