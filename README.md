# DIO-Bradesco-Azure-VM
Criação e Configuração de Máquina Virtual no Azure
Visão Geral

Este repositório documenta meu processo de aprendizado e implementação de uma máquina virtual na plataforma Microsoft Azure, realizado como parte de um desafio da DIO (Digital Innovation One).

Conteúdo do Repositório

📂 Estrutura do Projeto

/
├── /images/                  # Capturas de tela do processo
├── README.md                 # Documentação principal (este arquivo)
├── azure-cheatsheet.md       # Comandos e dicas úteis para Azure
└── vm-setup-notes.md         # Anotações detalhadas sobre configuração
📝 Principais Tópicos Abordados

Criação de VM no Azure
Navegação no portal Azure
Seleção de configurações (tamanho, região, SO)
Configuração de rede e segurança
Gerenciamento de Recursos
Grupos de recursos
Monitoramento de custos
Configuração de alertas
Conectividade
Conexão RDP/SSH
Gerenciamento de chaves
Configuração de firewall
Boas Práticas
Otimização de custos
Políticas de segurança
Backup e recuperação
🛠️ Passo a Passo Básico

Acessar o Portal Azure (portal.azure.com)
Criar novo recurso > Máquina Virtual
Preencher configurações básicas:
Assinatura
Grupo de recursos
Nome da VM
Região
Imagem (OS)
Tamanho
Configurar conta administrativa
Definir regras de portas de entrada
Revisar e criar
📌 Dicas Importantes

Sempre desligue a VM quando não estiver em uso para evitar custos desnecessários
Utilize tags para organização dos recursos
Configure alertas de orçamento
Considere usar Azure Spot VMs para cargas de trabalho flexíveis
🔍 Recursos Adicionais

Documentação Oficial Azure VMs
Calculadora de Custos Azure
Melhores Práticas de Segurança
📸 Capturas de Tela

Verifique a pasta /images para visualizar o processo passo a passo.

📅 Próximos Passos

Explorar automação com Azure CLI
Implementar configuração como código com ARM templates
Integrar com outros serviços Azure (Storage, Networking)
