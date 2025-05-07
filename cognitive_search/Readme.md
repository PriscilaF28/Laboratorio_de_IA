### Azure Cognitive Search
Rescurso de mineração de dados da Azure. As formas de uso podem ser pela própria interface ou ser integrado em uma aplicação.

### Recursos a serem criados  
***1. Azure AI Search***
* No portal da Azure selecionar o recurso Azure AI Search
* Selecionar o nivel Basic
* Indicar a assinatura, inserir o grupo de recursos e a localização

***2. Azure AI Service***
* No portal da Azure selecionar o recurso Azure AI Service 
* Indicar a assinatura, inserir o grupo de recursos e a localização
* Selecionar o nivel do preço para Standard


***3. Local Storage***
* No portal da Azure selecionar o recurso Local Storage 
* Indicar a assinatura, inserir o grupo de recursos e a localização
* Selecionar o nivel de performance Standard
* Para a redundancia de dados selecionar armazenamento local
* Criar o recurso
* Em seguida modificar nas configuração habilitar o acesso anônimo


***4. Fazer o upload dos arquivos***
* Dentro do Local Storage, criar um container para armazenar os arquivos
* Fazer upload dos arquivos no container, para alimentar a estrutura da IA


***5. Realizando a pesquisa de dados***
* Acessar a opção AI service >  
* Selecionar a função importar dados, indicar o local onde está os documentos e qual tipo de informação quer estrair desses documentos.
* Você deve especificar o indice e indicar o a palavra chave que está procurando
* Como resultado vai aparecer todos os arquivos que foram encontrados a palavra chave indicada 


link documentação: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
