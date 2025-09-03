# Máquinas Virtuais no Azure: Guia de Criação #
Este guia detalhado irá te ajudar a criar e configurar máquinas virtuais (VMs) na nuvem do Microsoft Azure. O Azure oferece uma variedade de opções de VMs para atender às suas necessidades, desde pequenas instâncias de desenvolvimento até máquinas de alto desempenho para cargas de trabalho complexas.

## 1. Pré-requisitos ##
- Antes de começar, certifique-se de ter o seguinte:
- Uma conta ativa do Microsoft Azure. Se você não tiver uma, pode criar uma conta gratuita.
- Um grupo de recursos (resource group) onde a sua VM será hospedada. O grupo de recursos ajuda a organizar e gerenciar os recursos relacionados à sua aplicação.

## 2. Passo a passo para a criação da VM ##
- Após acessar o portal do Azure, você vai em "Criar um Recurso" e escolhe a opção "Máquina Virtual". A partir daí você deve escolher sua assinatura azure, escolher um grupo re recursos, e definir coisas como região, imagem, opções de disponibilidade e tipo de segurança;

## 3. Autenticações ##
- Você deve criar uma nome de usuário e uma senha forte para acessar a máquina virtual, no caso do linux pode gerar um par de chaves (pública e privada), você pode configurar o ip entre outras funcionalidades.

## 4. Discos e gerenciamento ##
As demais abas, como "Discos", "Gerenciamento", "Monitoramento" e "Avançado", oferecem opções para customizar o armazenamento, backup, monitoramento e outras configurações. Para um início rápido, você pode manter as configurações padrão.

## 5. Revisar e criar ##
Clique no botão "Revisar + criar". O Azure validará suas configurações. Após a validação, clique em "Criar" para iniciar o processo de implantação da sua VM. Isso pode levar alguns minutos.

## 6. Conectando-se à VM ##
-Use um cliente SSH (para Linux) ou o Conexão de Área de Trabalho Remota (RDP) para Windows, com o IP público e as credenciais que você definiu, para se conectar.
-Pronto! Sua máquina virtual no Azure está pronta para ser usada. Você pode começar a instalar aplicativos, hospedar sites ou realizar qualquer outra tarefa que precise.
