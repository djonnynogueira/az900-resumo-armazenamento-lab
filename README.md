# resumo-armazenamento-lab
Este repositório contém o resumo das lições aprendidas sobre armazenamento e gerenciamento de dados na nuvem Azure.

## Conceitos Abordados

### 1. Estratégias de Armazenamento (Storage Solutions)
O Azure oferece múltiplas opções de armazenamento para diferentes necessidades de negócio:

#### Azure Blob Storage
- Armazenamento de objetos em larga escala
- Idealmente para dados não estruturados (mídia, documentos, logs)
- Tiers: Hot, Cool, Archive
- Replicação automática para alta disponibilidade

#### Azure Files (Compartilhamento de Arquivos)
- Compartilhamentos SMB gerenciados na nuvem
- Compatibilidade com Windows, Linux e Mac
- Acesso via SMB 3.0 e NFS
- Snapshots para backup e recuperação

#### Azure Table Storage
- Banco de dados NoSQL para dados estruturados
- Alto desempenho e escalabilidade
- Bom para aplicações com muitas leituras e escritas

#### Azure Queue Storage
- Sistema de filas para desacoplamento de aplicações
- Armazenamento de mensagens de forma confiável
- Integração com Workers e Function Apps

- ### 2. Gerenciamento e Configuração de Dados

#### Tier de Armazenamento
- **Hot**: Acesso frequente, custo de armazenamento maior, acesso rápido
- **Cool**: Acesso menos frequente, custo menor, latência maior
- **Archive**: Retenção de longo prazo, menor custo, acesso mais lento

#### Replicação e Resiliência
- LRS (Locally Redundant Storage): Replicação dentro de um datacenter
- GRS (Geo-Redundant Storage): Replicação geográfica
- RAGRS (Read-Access Geo-Redundant): Leitura no DR
- GZRS (Geo-Zone-Redundant): Combina ZRS e GRS

#### Segurança e Criptografia
- Criptografia em repouso (Server-Side Encryption)
- Criptografia em trânsito (HTTPS/TLS)
- Controle de acesso com SAS (Shared Access Signatures)
- Firewall e Virtual Network endpoints

- ### 3. Gerenciamento de Ciclo de Vida
- Políticas de retenção automáticas
- Transição entre tiers
- Exclusão de dados antigos
- Redução de custos operacionais

## Competências Adquiridas

- Compreensão das diferentes opções de armazenamento no Azure
- Capacidade de escolher a solução de armazenamento apropriada para cada caso de uso
- Configuração de segurança e replicação de dados
- Otimização de custos de armazenamento
- Implementação de estratégias de backup e recuperação

## Conclusão

Este lab proporcionou uma visão abrangente sobre as estratégias de armazenamento e gerenciamento de dados no Azure. O conhecimento adquirido possibilita tomar decisões informadas sobre qual solução de armazenamento utilizar conforme a necessidade de cada projeto, considerando performance, custo e segurança.
