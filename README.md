# DataBaseInAzure
Resumo do processo de configuração de uma instância de Banco de Dados na Microsoft Azure.

✅ Passo a Passo da Configuração – Azure SQL Database
1. Acessar o Portal
Vá até: https://portal.azure.com

Faça login com sua conta Microsoft (ou corporativa).

2. Criar um recurso
No menu lateral esquerdo, clique em "Criar um recurso".

Procure por “SQL Database” e selecione a opção.

3. Configurar as Informações Básicas
Preencha os campos:

Assinatura e Grupo de Recursos: Escolha um grupo existente ou crie um novo.

Nome do banco de dados: Nome único para o SQL Database.

Servidor lógico: Selecione um existente ou clique em “Criar novo”.

Para novo: defina nome, usuário, senha e região.

Modo de compra: Em geral, "Uso vCore" ou "DTU-based" (modelo baseado em performance).

4. Configurar o Preço e o Desempenho
Você define:

Quantidade de vCores (poder de processamento)

Tamanho do armazenamento

Tipo de redundância (local, geográfica ou zoneada)

Dica: Para testes, escolha a camada gratuita ou básica.

5. Regras de Segurança
Configure firewall para permitir acesso ao banco (ex: IP local).

Pode habilitar Azure Defender para SQL (segurança extra).

Ative o controle de acesso com base em identidade se desejar usar o Azure AD.

6. Configurações adicionais (opcional)
Backup automático (gerenciado pelo Azure).

Alta disponibilidade automática.

Tags para organização e automação (úteis para projetos maiores).

7. Revisar e Criar
Revise todas as configurações.

Clique em “Criar”. O processo leva cerca de 1-3 minutos.

8. Acessar e Usar
Após a criação, vá até o recurso.

No painel, você verá:

String de conexão (para seu app)

Query Editor (para rodar SQL direto no navegador)

Monitoramento de desempenho e métricas.

