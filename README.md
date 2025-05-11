Criando um Monitoramento de Custos no Data Factory


🚀 Visão Geral
Este projeto apresenta uma abordagem prática para explorar o ambiente Azure utilizando uma conta gratuita de estudante. O objetivo principal é configurar o Azure Data Factory e monitorar o uso e os custos dos recursos implantados. Durante a implementação, abordaremos os seguintes temas:

✔️ Estruturação de assinaturas e grupos de recursos.
✔️ Boas práticas de nomenclatura para facilitar a organização.
✔️ Personalização de dashboards para acompanhamento visual.
✔️ Utilização de métricas e alertas de custo para controle eficiente.
✔️ Automação com ARM Templates e Azure Cloud Shell.
✔️ Passo a passo completo para monitorar os gastos na plataforma.
✔️ Implementação de um script Python para automação do monitoramento de custos.
🛠️ Tecnologias Utilizadas
Azure Data Factory 🌐
Azure Monitor 📊
Azure Cost Management 💰
Azure Cloud Shell 🖥️
ARM Templates 📄
Python + Azure SDK 🐍
📌 Pré-requisitos
Antes de iniciar, certifique-se de ter:

🔹 Uma conta gratuita no Azure for Students ou Azure Free Tier.
🔹 Acesso ao Azure Portal.
🔹 Familiaridade com o Azure Resource Manager (ARM).
🔹 Conhecimentos básicos em PowerShell, CLI do Azure e Python.


🏗 Passo a Passo da Implementação de um projeto de monitoramento de custos



1️⃣ Criando o Ambiente no Azure
Acesse o portal Azure Portal.
Crie um Grupo de Recursos para organizar os ativos.
Configure uma Assinatura vinculada à conta gratuita.
Defina um Plano de Nomenclatura para manter a padronização.



2️⃣ Implantando o Azure Data Factory
No Azure Portal, vá até "Criar um recurso" e selecione Data Factory.
Escolha o grupo de recursos criado anteriormente.
Defina a região e nome do serviço seguindo as boas práticas.
Conclua a implantação e acesse o painel do Data Factory.
3️⃣ Monitorando os Custos
Acesse Azure Cost Management + Billing no portal.
Configure métricas de uso e custo para o Data Factory.
Defina alertas de custo para evitar gastos inesperados.
Crie um dashboard personalizado para visualização simplificada.




4️⃣ Automação com Azure Cloud Shell
Acesse o Azure Cloud Shell no portal.
Utilize PowerShell ou Azure CLI para gerenciar recursos.
Automatize tarefas recorrentes com scripts ARM Templates.
Teste a criação e remoção automatizada de recursos para otimização.
5️⃣ Implementação com Python 🚀
Podemos automatizar o monitoramento dos custos do Azure Data Factory utilizando Python e a Azure SDK. Siga os passos abaixo:

Instale as bibliotecas necessárias:
pip install azure-identity azure-mgmt-costmanagement

Código em Python para monitoramento de Custos:
Abra o arquivo monitoramento de custos.py 


Esse script autentica no Azure, consulta os custos do Data Factory e gera alertas caso os gastos ultrapassem o limite definido. 🚀

🎯 Resultados Esperados
✅ Melhor controle dos custos no Azure 💰.
✅ Configuração eficiente do Data Factory 🏗.
✅ Dashboards intuitivos para acompanhamento 📊.
✅ Automação e infraestrutura como código 📜.
✅ Monitoramento automatizado via Python 🤖.



Redundância de Arquivos no Azure com Data Factory
✨ Visão Geral
Este projeto tem como objetivo criar um processo completo de redundância de arquivos utilizando recursos do Microsoft Azure. Através do Azure Data Factory, você aprenderá a configurar toda a infraestrutura necessária para mover dados entre ambientes on-premises e a nuvem, garantindo backup seguro e acessível.

🔄 Fluxo do Processo
Conectar fontes de dados: SQL Server local e Azure SQL Database.
Criar Linked Services: Estabelecendo conexão entre o Data Factory e os repositórios de dados.
Criar Datasets: Definição das estruturas para entrada e saída dos dados.
Criar Pipelines: Construção dos fluxos de trabalho para movimentação dos dados.
Converter e armazenar: Transformar dados em arquivos .TXT, organizando-os em camadas (raw/bronze) dentro do Azure Data Lake.
Publicar e Executar: Validação e execução do pipeline.
Analisar performance: Aplicando boas práticas para otimizar o processo.
🛠️ Tecnologias Utilizadas
Microsoft Azure (🌍 Plataforma Cloud)
Azure Data Factory (🛠 Orquestração de Dados)
SQL Server (On-Premises e Azure SQL Database) (💾 Banco de Dados Relacional)
Azure Blob Storage (🏢 Armazenamento de Arquivos)
Integration Runtime (⚡ Conectividade Híbrida)
🗒️ Passo a Passo da Implementação
1. Criando o Azure Data Factory
Acesse o portal do Azure.
Crie um novo Data Factory.
Configure o Integration Runtime para conectar-se ao SQL Server local.
2. Configurando os Linked Services
Adicione um Linked Service para o SQL Server On-Premises.
Adicione um Linked Service para o Azure SQL Database.
Adicione um Linked Service para o Blob Storage.
3. Criando os Datasets
Crie um Dataset apontando para a tabela SQL de origem.
Crie um Dataset para os arquivos .TXT de destino no Blob Storage.
4. Criando o Pipeline
Adicione um Copy Activity para mover os dados do SQL Server para o Azure Data Lake.
Configure a transformação dos dados em arquivos .TXT organizados por camadas (raw/bronze).
Teste e valide as transferências.
5. Publicando e Executando
Publique as alterações e execute o pipeline.
Monitore os logs e valide a performance.
💡 Utilizando o SDK do Azure no Python
O SDK do Azure para Python permite interagir programaticamente com os serviços da nuvem, como o Azure Blob Storage. Com ele, você pode realizar operações como upload, download e gerenciamento de arquivos de forma eficiente.

Para instalar:

pip install azure-storage-blob

Exemplo de código para upload de arquivo no Azure Blob Storage abra o arquivo:
  projeto redundância de arquivos.py



Confira a documentação oficial:  (https://learn.microsoft.com/en-us/azure/storage/blobs/)
   para mais detalhes sobre suas funcionalidades.



Benefícios
🌐 Alta disponibilidade: Backup automático na nuvem.
⚖️ Segurança: Dados armazenados de forma redundante.
⏳ Eficiência: Pipelines otimizados para melhor desempenho.


Azure Databricks - Versionamento e Organização de Notebooks
Descrição
Este projeto demonstra como utilizar o Azure Databricks para versionamento e organização de notebooks em ambientes de dados. A proposta inclui:

Criação e configuração de clusters;
Importação e execução de notebooks com suporte de Inteligência Artificial;
Integração com Azure DevOps para controle de código e automação de pipelines de CI/CD;
Uso da IA integrada ao Databricks para geração de código Python e Spark;
Boas práticas para organização, exportação e reaproveitamento de notebooks;
Exploração de recursos do Microsoft Learn, com exercícios guiados e roteiros de aprendizado;
Trabalho colaborativo e seguro com versionamento estruturado em engenharia de dados e machine learning.
Arquitetura
A arquitetura deste projeto segue o fluxo abaixo:

Criação de um Cluster no Azure Databricks.
Importação de arquivos e notebooks para execução.
Execução de notebooks interativos com filtros, sumarizações e visualizações.
Geração de código com suporte de IA integrada ao Databricks.
Integração com Azure DevOps para versionamento e CI/CD.
Automação de pipelines para controle das execuções e governança.



Tecnologias Utilizadas
Azure Databricks
Python
Apache Spark
Azure DevOps
Microsoft Learn
CI/CD (Continuous Integration & Continuous Deployment)
MLflow (para versionamento de modelos em ML)
Passo a Passo - Configuração do Ambiente
1. Criar um Cluster no Databricks
Acesse Azure Databricks
Navegue até Clusters > Create Cluster
Escolha um nome e selecione a configuração de hardware necessária
Clique em Create Cluster
2. Importar e Executar um Notebook
No Databricks, acesse Workspace
Clique em Import e carregue um arquivo .ipynb ou .dbc
Abra o notebook para edição e execução
3. Configurar Azure DevOps para Versionamento
No Azure DevOps, crie um repositório Git
Conecte o Databricks ao Azure DevOps:
Vá para Repos > Git Integration
Configure a conexão ao seu repositório remoto
Habilite CI/CD Pipelines para automação
4. Criar um Pipeline CI/CD no Azure DevOps
No Azure DevOps, vá para Pipelines > New Pipeline
Escolha GitHub ou Azure Repos Git como origem do código
Selecione Starter Pipeline e edite o azure-pipelines.yml
Adicione o seguinte código para execução automatizada de notebooks:

trigger:
  branches:
    include:
      - main

pool:
  vmImage: 'ubuntu-latest'

steps:
- task: DatabricksRunNotebook@0
  inputs:
    databricksServiceConnection: 'AzureDatabricks'
    notebookPath: '/Workspace/MeuNotebook'
    workspaceUrl: 'https://adb-123456789.azuredatabricks.net'
    newCluster:
      clusterName: 'ci-cd-cluster'
      nodeTypeId: 'Standard_DS3_v2'
      sparkVersion: '7.3.x-scala2.12'


Salve e execute o pipeline para testar a automação

Código em Python e Spark

 código para leitura, transformação e exibição de dados em um notebook do Databricks: abra o arquivo: Projeto controle e versionamento de código pyspark


Benefícios do Projeto
✅ Melhor organização e versionamento de notebooks ✅ Automação de processos com CI/CD ✅ Colaboração eficiente em times de engenharia e ciência de dados ✅ Uso de Inteligência Artificial para facilitar o desenvolvimento ✅ Governança e segurança no controle de código


Integrando o Azure Data Factory ao Azure DevOps
Visão Geral
Este projeto demonstra como integrar o Azure Data Factory ao Azure DevOps, permitindo versionamento, controle de mudanças e backups automáticos de pipelines e artefatos de dados. Essa integração assegura maior governança e rastreabilidade no desenvolvimento de soluções de dados.

Benefícios da Integração
Versionamento de Pipelines: Manutenção de histórico de alterações.
Controle de Mudanças: Padronização e rastreamento de ajustes.
Backup Automático: Segurança contra perda de artefatos.
Preparação para CI/CD: Facilidade na automação de deploys futuros.
Passo a Passo da Integração
1. Criar uma Organização e um Projeto no Azure DevOps
Acesse o Azure DevOps.
Clique em Criar nova organização (caso não tenha uma).
Dentro da organização, clique em Novo projeto.
Defina um nome para o projeto e escolha a visibilidade (Privado ou Público).
Clique em Criar.
2. Configurar o Repositório Git
No projeto criado, vá para Repositórios.
Escolha Git como tipo de repositório.
Copie a URL do repositório remoto para uso posterior.
3. Criar o Azure Data Factory
Acesse o Portal do Azure.
Vá até Data Factory e clique em Criar.
Preencha as informações do recurso (Nome, Região, Grupo de Recursos).
Em Git Configuration, selecione Configure Git later se quiser configurar posteriormente.
Clique em Criar.
4. Configurar a Integração com o Git
Acesse o Azure Data Factory Studio.
No canto superior direito, clique em Manage.
Vá para a aba Git Configuration.
Clique em Configure e insira:
Provider: Azure DevOps Git
Account Name: Nome da organização no DevOps
Project Name: Nome do projeto criado
Repository Name: Nome do repositório
Branch: Defina a branch padrão (main ou develop)
Root Folder: /
Clique em Apply.
5. Gerenciando os Artefatos no Git
Todos os pipelines e datasets criados serão salvos no repositório.
Para visualizar no Azure DevOps:
Acesse Repositórios no DevOps e veja os arquivos versionados.
Cada alteração será armazenada com um commit.
Para realizar mudanças:
Faça edições no Data Factory e publique as alterações.
No DevOps, crie Pull Requests para revisar e aprovar mudanças antes do merge.
6. Boas Práticas de Governança
Utilizar branches dedicadas: feature/nova_funcionalidade, hotfix/correção.
Implementar revisões de código com Pull Requests.
Manter padrões de nomenclatura para pipelines e datasets.
Automatizar deploys futuros com CI/CD utilizando Azure Pipelines.
Conclusão
A integração do Azure Data Factory com o Azure DevOps proporciona maior governança, versionamento e controle sobre os pipelines de dados. Essa estrutura possibilita padronizar ambientes de desenvolvimento e criar uma esteira eficiente para automação futura de deploys no Azure.

