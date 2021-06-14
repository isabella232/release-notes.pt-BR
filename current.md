---
title: Notas de versão mais recentes
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação dos produtos e serviços da Experience Cloud. Encontre ajuda e novos tutoriais da Experience Cloud, da Creative Cloud para corporações e da Document Cloud.
doc-type: release notes
last-update: June 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: b0ad7a5c45760fba6a1a4e7e0f6dbbedbef93355
workflow-type: tm+mt
source-wordcount: '4913'
ht-degree: 52%

---

# Notas de versão da Adobe Experience Cloud - Junho de 2021

![Banner](assets/experience-cloud-banner-3.png)

Os aplicativos e os serviços da Experience Cloud são atualizados mensalmente. Esta página é o local central para encontrar as atualizações, a documentação e os tutoriais mais recentes para a [!DNL Experience Cloud] e a [!DNL Experience Platform]. Você também pode encontrar nova documentação para a [!DNL Creative Cloud for Enterprise] e a [!DNL Document Cloud].

>[!NOTE]
>
>Assine a [Atualização mensal do produto de prioridade da Adobe](https://www.adobe.com/subscription/priority-product-update.html) para receber notificações por email sobre atualizações nesta página. Esta página é mantida durante todo o mês. Portanto, verifique regularmente se há atualizações de produtos empresariais da Adobe e da documentação da Experience League.

Última atualização: **14 de junho de 2021**

* [Componentes da interface central da Experience Cloud](#ecloud)
* [Status de sistema da Adobe](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) e [Customer Journey Analytics](#cust-journey) 
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insight da comunidade e treinamento ministrado por instrutores.

## ![](/assets/ec_appicon_24.png) ÍconeComponentes da interface do usuário central da Experience Cloud {#ecloud}

Os Componentes da interface central do Experience Cloud incluem atualizações a serem acessadas no cabeçalho unificado do produto, como autoajuda, pesquisa e preferências da conta de usuário. As atualizações para Pessoas, Locais (Localização) e gerenciamento de produtos podem ser encontradas aqui.

| Recurso | Data | Descrição |
| ------- | ------- | ------- |
| Suporte para logon único para Adobe Federated IDs | 17 de junho de 2021 | Se você usa Federated IDs, é possível fazer logon no Experience Cloud sem precisar inserir um endereço de email ou senha. Para usar esse recurso, adicione **#/sso:@domain** ao URL do Experience Cloud. <br><br>Por exemplo, suponha que você seja o proprietário do domínio  **adobecustomer.** comand que deseja fazer logon no Adobe Analytics. O URL seria: **https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**. |
| Pesquisa Experience League | 1 de junho de 2021 | A pesquisa da documentação do Experience League foi aprimorada. Navegue até [Experience League](https://experienceleague.adobe.com/docs/?lang=en) e use o campo **[!UICONTROL Pesquisar]** para localizar tutoriais, documentação, cursos e muito mais. |

{style=&quot;table-layout:auto&quot;}

**Mais recursos de ajuda**

* Ajuda administrativa para [Componentes da interface central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) e gerenciamento de usuários
* Ajuda e notas de versão para [Places - Serviço de localização](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Ajuda em [Pessoas - Atributos do cliente e Biblioteca de público-alvo](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en).

## ![Ícone](/assets/adobe.png) Adobe da sistema de Status {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

As atualizações mais recentes do Status do sistema da Adobe são encontradas em [Status do sistema da Adobe - 21 de maio de 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=pt-BR) para obter as informações de lançamento mais recentes.

## ![Ícone](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Inclui informações de atualização de versão e nova documentação para Experience Platform e Experience Platform Launch.

* **26 de maio de 2021:** [Notas de versão do Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR)
* **17 de maio de 2021:** [Notas de versão da coleção de dados do Experience Platform](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=pt-BR)  (antigo Experience Platform Launch)

### Tutoriais e cursos da Experience Platform {#tutorials-platform}

Novos vídeos, tutoriais ou cursos publicados para a Experience Platform e serviços.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Junho de 2021 | [Preparar dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | Vídeo | Saiba como limpar, preparar e combinar dados de vários conjuntos de dados para criar um conjunto de dados usando as funções Criar tabela AS (CTAS) e Spark SQL para relatórios e painéis. |
| Junho de 2021 | [Copiar esquemas entre sandboxes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | Vídeo | Saiba como copiar um esquema de uma sandbox para outra no Adobe Experience Platform usando a [!UICONTROL Export/Import Schema API]. Crie e teste seus esquemas em sandboxes de desenvolvimento e, em seguida, copie-os para produção. |
| Junho de 2021 | [Atualizar schemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | Vídeo | Saiba mais sobre os aspectos básicos a serem observados ao atualizar esquemas existentes no Adobe Experience Platform. |
| Junho de 2021 | [Blocos de construção do schema](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | Vídeo | Saiba mais sobre os elementos fundamentais dos esquemas do Experience Data Model (XDM), incluindo campos, tipos de dados, grupos de campos de esquema, classes e comportamento. |
| Junho de 2021 | [Criar classes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | Vídeo | Saiba como criar classes no Adobe Experience Platform para usar em esquemas do Experience Data Model (XDM). |
| Junho de 2021 | [Configurar relações entre schemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | Vídeo | Saiba como configurar uma relação entre dois schemas no Adobe Experience Platform. Os relacionamentos permitem usar um conjunto de dados como uma tabela de pesquisa para outro. |
| Junho de 2021 | [Criar tipos de dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | Vídeo | Saiba como criar seus próprios tipos de dados no Adobe Experience Platform para usar em esquemas do Experience Data Model (XDM). |
| Junho de 2021 | [Converter seu modelo de dados em um modelo de dados de experiência](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | Vídeo | Saiba como os arquitetos de dados podem pegar seus modelos de dados transacionais existentes e convertê-los em um Experience Data Model. Este vídeo mostra a diferença nas abordagens de modelagem usando diagramas de relação de entidade. |
| Junho de 2021 | [Planejar o modelo de dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | Vídeo | Saiba o que fazer antes de começar a criar seus esquemas no Adobe Experience Platform. Documente seus casos de uso de negócios, entenda sua licença da Platform, conheça as medidas de proteção do produto e identifique quais dados devem ser assimilados antes de finalizar seu modelo de dados. |
| Junho de 2021 | [Tableau](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | Vídeo | Saiba como se conectar ao [!UICONTROL Serviço de consulta] de vários aplicativos de cliente de desktop que oferecem suporte ao protocolo `PostgreSQL` e como usar ferramentas e drivers `PostgreSQL` para conectar e gravar consultas. |
| Junho de 2021 | [Funções definidas pelo Adobe](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | Vídeo | Saiba como usar funções definidas pelo Adobe no Adobe Experience Platform [!UICONTROL Serviço de query] para executar tarefas comerciais comuns nos dados do evento de experiência. |
| Junho de 2021 | [Exploração de dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | Vídeo | Saiba como validar dados assimilados, visualizar dados e explorar propriedades estatísticas e analíticas de dados usando funções SQL. |
| Junho de 2021 | [Visão geral do serviço de query](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | Vídeo | Saiba mais sobre o Serviço de query no Adobe Experience Platform e como ele ajuda a entender o comportamento do cliente e gerar insights impactantes. |
| Junho de 2021 | [Visão geral da interface do usuário do serviço de query](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | Vídeo | Saiba como gravar e executar consultas, exibir consultas executadas anteriormente e acessar consultas salvas por outros usuários em sua Organização IMS no Adobe Experience Platform Query Service. |
| Junho de 2021 | [Consultar API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | Vídeo | Saiba como gravar e executar queries, criar consultas de agendamento e criar um modelo de consulta usando a API do Serviço de consulta do Adobe Experience Platform [!UICONTROL Query Service]. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use o Experience Platform para orquestrar a jornada de um cliente em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada indivíduo em tempo real.

* Atualizado em junho de 2021 - [Notas de versão do Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=pt-BR)

**Recursos adicionais do Journey Orchestration**

[Documentação](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL O Offer Decisioning] é um serviço de aplicativos integrado à Adobe Experience Platform. Use o [!UICONTROL Offer Decisioning] para fornecer a melhor oferta e experiência aos seus clientes em todos os pontos de contato na hora certa.

* Atualizado em abril de 2021 - [Notas de versão do Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=pt-BR#new)

**Mais recursos para o Offer Decisioning**

[Documentação](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=pt-BR)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **17 de junho de 2021**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [Cursos e tutoriais do Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade geral](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=pt-BR) - Data do Target | Descrição |
| ----------- | ---------- | ------- |
| N/D | N/D |

{style=&quot;table-layout:auto&quot;}

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade geral](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - Data do Target | Descrição |
| ----------- | ---------- | ----- |
| N/D | N/D |

{style=&quot;table-layout:auto&quot;}

### Correções no Adobe Analytics {#aa-fixes}

* Correção de um problema em que a moeda incorreta era exibida no relatório Receita em tempo real . (AN-254649)
* Atualização da documentação sobre [distinção entre maiúsculas e minúsculas de eVares no relatório](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html). (AN-246438)
* Atualização da documentação para explicar melhor a [Implementação do feed de dados](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html) e [aqui](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl). (AN-219485)
* Correção de problemas com alguns dados que não eram enviados no relatório de Data Warehouse (AN-259951; AN-259712; AN-260107; (AN-259953)

#### Correções adicionais no Adobe Analytics ou CJA

AN-246344; AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393; AN-259203; AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198; AN-260290; AN-260306 (CJA); AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| ----------- | ---------- | ---------- |
| Os agentes do usuário do navegador refletem versões incorretas do sistema operacional para macOS | 19 de maio de 2021 | Todos os principais navegadores atualmente relatam usuários do macOS X 11 e superior incorretamente como usando o macOS 10, conforme registrado na sequência de agente do usuário do navegador. Isso afeta os relatórios do Adobe Analytics, pois usa o agente do usuário para determinar as informações do dispositivo, como o sistema operacional. Essa imprecisão está aparentemente em vigor para evitar problemas de compatibilidade em alguns sites. Consulte este [tíquete Bugzilla](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454) como referência. Não está claro quando ou se esse problema será corrigido.<br>Alguns navegadores registraram inicialmente o macOS 11 corretamente, portanto, pode haver algum tráfego correspondendo a esse valor. No entanto, devido aos relatórios imprecisos, a filtragem para o sistema operacional macOS 11 não é útil.<br>Este problema é significativo porque, a partir do Safari no macOS 11, a Apple atualizou as limitações de expiração do cookie ITP para aplicar às implementações CNAME (consulte a publicação do blog [WebKit](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)).<br>Antes dessa atualização, essas limitações eram aplicadas apenas aos cookies do lado do cliente definidos pelo JavaScript. Essa imprecisão dificultará a avaliação de quanto tráfego está usando o macOS 11 e, portanto, é afetada pela alteração da ITP. Você pode saber mais sobre cookies e o Adobe Analytics [aqui](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html?lang=pt-BR#cookies). |
| Fim da vida útil para três serviços de API do Analytics | 19 de maio de 2021 | Em 18 de agosto de 2021, os seguintes serviços de API legados do Analytics atingiram sua data de término da vida útil e foram encerrados. Qualquer integração atual criada com esses serviços deixará de funcionar nesse dia.<ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>A Adobe forneceu uma seção de [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder às suas perguntas e fornecer orientações sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do Analytics [Adobe I/O](https://console.adobe.io/home?mv=email#), que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Atualizações da região ISO 2021 | 13 de maio de 2021 | A Adobe realizará as atualizações de 2021 da região ISO em 21 de maio de 2021. Você deve esperar pequenas atualizações após esta versão. |
| Fim da vida útil das fontes de dados de processamento completo | 12 de abril de 2021 | A Adobe planeja descontinuar o processamento completo de fontes de dados em 31 de julho de 2021. A partir de 25 de março de 2021, novas importações desse tipo não poderão mais ser criadas. Use a [API de inserção de dados em massa](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) para importar esse tipo de dados. |
| Fazer logon para atualizar para o [!UICONTROL Report Builder] | 9 de abril de 2021 | Em 14 de janeiro de 2021, as atualizações de logon do [!UICONTROL Report Builder] removeram as dependências das tecnologias herdadas e alinharam o processo de logon com a Experience Cloud. A Experience Cloud usa sua Enterprise ID (email e senha). Para garantir acesso ininterrupto ao [!UICONTROL Report Builder], atualize o suplemento [!UICONTROL Report Builder] para a versão 5.6.47 ou posterior até 22 de julho de 2021. O Report Builder versão 5.6.47 e posterior oferecerá suporte apenas ao logon da Experience Cloud e não oferecerá suporte ao logon único. |
| Mudanças de endereço IP de Feed de dados e Data Warehouse | 6 de abril de 2021 | A partir de 17 de junho, os Feeds de dados e o sistema de entrega do Data Warehouse serão realocados nos data centers da Adobe e, portanto, podem causar uma mudança de endereços IP externos visíveis a você. A Adobe recomenda confirmar se todos os blocos CIDR de IP do data center do qual seus relatórios e feeds são originados estão presentes em qualquer firewall, para qualquer sistema de destino sob seu controle. [Esta é uma lista completa de intervalos de endereço IP que devem ser incluídos nas listas de permissões do firewall](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=pt-BR#data-collection-and-ftp-ip-address-blocks). |
| Aviso de alterações futuras no menu do Analytics | 24 de março de 2021 | Em 22 de abril de 2021, a Adobe atualizou os menus suspensos **[!UICONTROL Componentes]**, **[!UICONTROL Ferramentas]** e **[!UICONTROL Administrador]** para obter ganhos de desempenho. Todas essas páginas ainda estarão disponíveis nos links **[!UICONTROL Todos os componentes]**, **[!UICONTROL Todas as ferramentas]** e **[!UICONTROL Todos os administradores]**: elas serão removidas do menu suspenso. Aqui estão os itens de menu que serão removidos do menu suspenso e colocados em sua respectiva página de link:<br><br> [!UICONTROL Componentes]<ul><li>[!UICONTROL Marcadores]</li><li>[!UICONTROL Painéis]</li><li>[!UICONTROL Metas]</li><li>[!UICONTROL Eventos de calendário]</li><li>[!UICONTROL Relatórios agendados]</li><li>[!UICONTROL Configurações do relatório]</li></ul>Ferramentas de <ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL Gerenciamento de usuários]</li><li>[!UICONTROL Classificação do importador]</li><li>[!UICONTROL Criador de regras de classificação]</li><li>[!UICONTROL Fontes de dados]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Configurações da empresa]</li><li>[!UICONTROL Logs]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Gerenciador de código]</li><li>[!UICONTROL Excluir por IP]</li><li>[!UICONTROL Gerenciamento de tráfego]</li></ul> |
| Processamento VISTA Same-as-SiteCatalyst ATIVADO | 17 de março de 2021 | Em 17 de junho de 2021, todos os conjuntos de relatórios serão atualizados para terem o [!UICONTROL Processamento VISTA Same-as-SiteCatalyst] definido como ATIVADO. Essa alteração afeta os relatórios do Data Warehouse processando os dados para corresponder às regras de processamento. Para dúvidas ou esclarecimentos, entre em contato com o Atendimento ao cliente. |
| Opções de Reports &amp; Analytics da página de aterrissagem | 19 de fevereiro de 2021 | Em 25 de março de 2021, as opções para definir novos painéis no Reports &amp; Analytics ou outro conteúdo como sua página de aterrissagem do Adobe Analytics serão removidas. Se você tiver definido anteriormente uma página do Reports &amp; Analytics como sua página de aterrissagem personalizada, ela continuará a funcionar até que sua página de aterrissagem seja modificada em [!UICONTROL Preferências do usuário]. |
| Fim da vida útil do Data Connectors da Adobe | 13 de julho de 2020 | Os [!UICONTROL Data Connectors] da Adobe são alimentados por tecnologia herdada que não é mais viável ou compatível. Um novo padrão está disponível no [Programa de parceiro Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud). Você pode usar esse padrão para que qualquer integração continue a ser oferecida e suportada. A data de término oficial é 1º de agosto de 2021. [Saiba mais...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=pt-BR) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Para obter as atualizações mais recentes das versões do AppMeasurement, consulte as [notas de versão do AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=pt-BR).

### Novos cursos e tutoriais do Analytics {#tutorials-analytics}

Novos cursos, tutoriais e artigos no [!DNL Analytics] e no [!UICONTROL Customer Journey Analytics].

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Junho de 2021 | [Introdução ao Customer Journey Analytics para administradores](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Curso | Saiba como configurar, configurar e administrar o Customer Journey Analytics. Saiba mais sobre alguns conceitos básicos para fornecer uma base e depois seguir para mais etapas de configuração. O curso é então limitado a algumas recomendações sobre como migrar métricas calculadas e segmentos do Adobe Analytics para o Customer Journey Analytics. |
| Junho de 2021 | [Configurar relatórios internos de pesquisa do site](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | Vídeo | Crie e configure tabelas de forma livre no Analysis Workspace para analisar a funcionalidade de pesquisa interna no site. |
| Junho de 2021 | [Mapear variáveis do SDK da Web no Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | Vídeo | Saiba como mapear variáveis de análise do SDK da Web para o Adobe Analytics usando Regras de processamento. |
| Junho de 2021 | [Implementar variáveis de pesquisa interna usando o SDK da Web](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | Vídeo | Saiba como usar o SDK da Web para implementar variáveis do Adobe Analytics em um caso de uso interno de rastreamento de termos de pesquisa. Consulte o fluxo de dados da página para a Experience Edge e, em seguida, para a Adobe Analytics. |
| Junho de 2021 | [Implementar variáveis de pesquisa interna usando o AppMeasurement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | Vídeo | Neste vídeo, aprenda as etapas de implementação de variáveis de pesquisa internas do site para o Adobe Analytics usando a Coleta de dados do Experience Platform/Launch, incluindo o termo de pesquisa, o número de resultados e outros. |
| Junho de 2021 | [Definição dos requisitos de negócios internos de pesquisa de site](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | Vídeo | Ao decidir rastrear a pesquisa interna em seu site, é importante primeiro decidir quais aspectos da pesquisa você deseja rastrear e quais ações podem ser tomadas com a análise dos resultados. Este vídeo documenta os requisitos comerciais. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ajuda do Analytics

* [Documentação e tutoriais do produto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR)

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Correções e aprimoramentos no Audience Manager.

### Correções e melhorias {#aam-fixes-and-improvements}

* Lançado um aprimoramento ao [Relatório de uso de atividade](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en) que agora permite revisar dados com mais de um ano. (AAM-58268)
* O Adobe fornece aos clientes do Audience Manager chaves de acesso do usuário para os buckets do Audience Manager Amazon S3. Por motivos de segurança, as chaves agora são automaticamente desativadas após 100 dias de inatividade. Para obter mais informações, consulte a pergunta na parte inferior da página nas [Perguntas frequentes sobre coleta de dados e integração de produto](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en).

## ![Ícone](/assets/aem.png) Experience Manager {#aem}

Novos recursos, correções e atualizações no Experience Manager (AEM). A Adobe recomenda que os clientes com implantações no local implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

>[!NOTE]
>
>A Adobe recomenda visitar a página de [Atualizações e roteiros de versão do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para se manter atualizado sobre as informações de lançamento.

### Atualizações de produto do Experience Manager

* **Experience Manager 6.5.9.0**

   O Experience Manager 6.5, Service Pack 9.0 (6.5.9.0 lançado em 27 de maio de 2021), é uma atualização importante que inclui novos recursos, principais melhorias solicitadas pelo cliente, melhor desempenho, estabilidade e segurança, lançados desde a disponibilização geral do AEM 6.5 em abril de 2019.

   * [Notas de versão](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=pt-BR)
   * [Resultados da versão do AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### Versões de produto Experience Manager

* **Experience Manager as a Cloud Service**

   Novos recursos no Experience Manager as a Cloud Service:

   * **Adobe Experience Manager as a Cloud Service Foundation**

      * [Canal](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en) de pré-lançamento: Visualize os recursos futuros um mês antes de eles entrarem em produção!
      * [Substituição](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en) da API: Uma lista das APIs obsoletas mais recentes.
      * [Plug-in](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en) Maven do Analisador de build do Experience Manager as a Cloud Service SDK: Atualize seus projetos maven para a versão mais recente, que inclui uma verificação da API Java™ obsoleta e outras melhorias.
   * **Experience Manager Sites as a Cloud Service**

      Agora você pode verificar o conteúdo em um novo [Camada de visualização](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en) para simular a aparência da experiência final e a experiência como faria no nível de Publicação. Essa nova funcionalidade é ativada pelo assistente de Publicação gerenciada dos sites do Experience Manager, que permite escolher um destino de publicação entre [!UICONTROL Publicar] ou [!UICONTROL Visualizar]. As experiências em [!UICONTROL Preview] podem ser acessadas por meio de um URL dedicado. Após a validação em [!UICONTROL Visualizar], você pode publicar o conteúdo de [!UICONTROL Autor] para [!UICONTROL Publicar] como de costume. Habilitar o Serviço de [!UICONTROL Visualização] no Experience Manager como um ambiente de Cloud Service está gradualmente saindo nas próximas semanas.

   * **Experience Manager Assets as a Cloud Service**

      Novos recursos no canal de pré-lançamento:

      * Os esquemas de metadados podem ser aplicados diretamente às propriedades da pasta.
      * A ferramenta [!UICONTROL Entrada em massa de ativos] permite adicionar metadados durante uma assimilação em massa.
      * Um aprimoramento da experiência do usuário exibe o número de ativos presentes em uma pasta. Para mais de 1000 ativos em uma pasta, o Experience Manager Assets exibe mais de 1000.

      Novos recursos em [!UICONTROL Dynamic Media]:

      * A Proporção de pixels do dispositivo de imagem inteligente (DPR) e a otimização da largura de banda da rede permitem que você forneça imagens de melhor qualidade com eficiência, em dispositivos com telas de alta resolução e largura de banda de rede restrita. Consulte as [perguntas frequentes sobre a geração inteligente de imagens](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en).



### **Comunidade Experience Manager**

* [One-Stop-Shop para todos os Experience Manager Blogs](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [Diretrizes para envio de uma nova Experience Manager Idea](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [Adobe Summit 2021 Sneaks com Dan Levy](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865): Uma vez por ano, todos os Adobe, desde engenheiros e cientistas de dados até designers de UX e gerentes de produtos, têm a chance de compartilhar ideias inovadoras para evoluir a forma como as marcas interagem com seus clientes. Junte-se a nós para o Adobe Sneaks, onde compartilhamos os sete principais projetos, tocando nas tecnologias mais recentes em áreas como IA e aplicativos de código baixo.

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Informações sobre a versão do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Notas de versão do Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=pt-BR)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Notas de versão do Cumulative Fix Pack do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=pt-BR)
* [Notas de versão do Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=pt-BR)
* [Notas de versão do Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=pt-BR)
* [Notas de versão do aplicativo para desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Notas de versão do Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=pt-BR)
* [Notas de versão do Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=pt-BR)

### Novos cursos e tutoriais do Experience Manager  {#tutorials-aem}

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Junho de 2021 | [Implementar os métodos da interface](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | Artigo | Saiba como implementar os métodos de interface para criar PDFs usando a API REST do Document Cloud. |
| Junho de 2021 | [Criar interface de serviço](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | Artigo | Defina os métodos na interface que deseja expor. |
| Junho de 2021 | [Criar configuração OSGi personalizada](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | Artigo | Saiba mais sobre a configuração OSGi personalizada para capturar detalhes do projeto do Adobe I/O. |
| Junho de 2021 | [Criar analisador de conteúdo](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | Artigo | Saiba como criar a parte JSON contendo as informações sobre os parâmetros de entrada para a chamada Criar PDF REST. |
| Junho de 2021 | [Criar etapa do processo personalizada](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | Artigo | Visualize o código completo da etapa do processo personalizado que converte e substitui os arquivos nativos pelos PDFs convertidos. Esta etapa personalizada pesquisa todos os anexos sob o nome da pasta, que é fornecido como um argumento de processo no fluxo de trabalho. Essa etapa do processo personalizado usa os métodos do `DocumentCloudSDKService` personalizado para criar PDFs. |
| Junho de 2021 | [Consultas Persistentes GraphQL](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | Vídeo | Saiba como habilitar, criar, atualizar e executar Consultas Persistidas no Experience Manager. |
| Junho de 2021 | [Criar seu primeiro servlet no AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | Artigo | Crie seu primeiro servlet sling para poder mesclar dados com um modelo de formulário. |
| Junho de 2021 | [Criação do seu primeiro serviço OSGi com formulários Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | Artigo | Crie seu primeiro serviço OSGi com o AEM Forms para que você possa gerar PDF ao mesclar dados com modelo. |

{style=&quot;table-layout:auto&quot;}

### Outros recursos de Ajuda do Experience Manager

* [Guias do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Página de aprendizagem e suporte do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página de aprendizagem e suporte do Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR#previous-updates)
* [Versões anteriores da documentação do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Guia do Usuário do Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=pt-BR)
* [Página inicial de ajuda do Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=pt-BR)
* [Documentação do Experience Manager: atualizações recentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=pt-BR#aem-as-a-cloud-service)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produtos

Saiba mais sobre recursos, melhorias e correções mais recentes lançados:

* **O novo Adobe Campaign v8** oferece infraestrutura, segurança, deliverability e melhorias significativas de monitoramento. O Adobe Campaign v8 melhora consideravelmente sua escala e velocidade, com a capacidade de gerenciar um número mais significativo de perfis de clientes, bem como taxas de delivery e transações por hora muito mais altas. Saiba mais na documentação do [Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html).

* **Versão 21.1.3 do Adobe Campaign Classic v7:** saiba mais nas Notas de versão do  [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=pt-BR).

* **Versão 21.2 do Adobe Campaign Standard:** saiba mais nas Notas de versão do  [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=pt-BR).

### Novos cursos e tutoriais do [!UICONTROL Campaign] {#tutorials-campaign}

| Publicado | Nome | Solução | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Junho de 2021 | [Integrar o Campaign Standard com o Analytics para otimizar o marketing por email](https://experienceleague.adobe.com/?lang=pt-BR#dashboard/learning) | Campaign Standard | (Curso) Saiba como integrar o Campaign Standard ao Adobe Analytics e otimizar suas estratégias de marketing por email usando dados em tempo real. Este curso mostra como criar um relatório do Campaign Standard no Adobe Analytics. Em seguida, saiba como usar Triggers da Experience Cloud e o Platform Launch para configurar mensagens de marketing e transacionais com base na atividade do cliente. |
| Junho de 2021 | [Tutoriais do Adobe Campaign V8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign V8 | Este guia do usuário contém vídeos e tutoriais sobre os vários recursos e funcionalidades do Adobe Campaign V8. |
| Junho de 2021 | [Criar e projetar entregas de email](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | Campanha V8 | (Vídeo) Entenda o processo de criação de um delivery de email e saiba como projetar e personalizar o conteúdo de email. |
| Junho de 2021 | [Projetar emails para entrega](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | Campanha V8 | (Vídeo) Saiba como aplicar as práticas recomendadas de capacidade de entrega aos seus deliveries de email. |
| Junho de 2021 | [Gerenciar fadiga usando regras de tipologia](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | Campanha V8 | (Vídeo) Saiba como implementar o gerenciamento de fadiga aplicando regras de tipologia. |
| Junho de 2021 | [Configurar o gerenciamento de fadiga usando filtros](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | (Vídeo) Saiba como implementar o gerenciamento de fadiga no Adobe Campaign usando filtros. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ajuda do Campaign

* Adobe Campaign Standard: [Centro de ajuda](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=pt-BR) - [Planejamento de lançamento](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=pt-BR)
* Adobe Campaign Classic: [Centro de ajuda](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=pt-BR)- [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=pt-BR)
* Painel de controle do Adobe Campaign: [Documentação](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [Notas de versão](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - Vídeos explicativos do [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=pt-BR)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=pt-BR)

## ![Ícone](/assets/advertising-cloud.png) Anúncio {#adcloud}

Notas de versão do [!DNL Adobe Advertising].

* [Novos recursos na Advertising DSP](#adcloud-dsp)
* [Novos recursos na Advertising Search](#adcloud-search)

### Novos recursos no [!DNL Advertising DSP] {#adcloud-dsp}

Última atualização: **Versão de 10 de junho de 2021 para 16 de junho**

| Recurso | Descrição |
| -----------| ---------- |
| Gerenciamento de campanhas | (Versão de 16 de junho) A previsão está disponível para disposições de exibição padrão com ritmo de posicionamento e orçamentos. |

{style=&quot;table-layout:auto&quot;}

### Novos recursos no [!DNL Advertising Search] {#adcloud-search}

Última atualização: **19 de maio de 2021, para a versão 18 de maio**

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Centro de notificações beta] | O [!UICONTROL Centro de notificações beta] está disponível para todos os usuários. Use-a para assinar notificações da Web e por email sobre erros de autenticação de conta, alertas personalizados acionados e a conclusão dos [!UICONTROL Insights de publicidade] gerados.<br>É possível exibir as notificações pelo:<ul><li>Painel [!UICONTROL Notificações], que é aberto no link Notificações no canto superior direito de qualquer página.</li><li>[!UICONTROL Centro de notificações] em [!UICONTROL Insights e Relatórios >Centro de notificação beta].</li></ul><br><b>Observação:</b> devido a aprimoramentos no modo como as notificações são armazenadas, todas as notificações existentes foram apadagas. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Consulte as [notas de versão](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) do Magento Commerce e de Código aberto para obter as informações mais recentes.

## ![Ícone](/assets/target.png)[!DNL Target] {#target}

Consulte as [[!DNL Target] notas de versão](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=pt-BR) para obter as informações mais recentes.

## ![Ícone](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

O [!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes envolvendo-se em cada estágio de jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte [!DNL Marketo Engage] [agendamento de versão](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) para obter as informações mais recentes sobre o agendamento de versão e as notas de versão.

## ![Ícone](/assets/workfront.png) [!DNL Workfront] {#workfront}

O Adobe [!DNL Workfront] é um aplicativo unificado de gerenciamento de trabalho para compartilhar ideias, criar conteúdo, gerenciar processos complexos e fazer o melhor trabalho.

Consulte a página [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) para obter um resumo das informações mais recentes para todos os produtos.

## ![Ícone](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Novos vídeos, tutoriais ou cursos publicados na Adobe Document Cloud.

### Cursos e tutoriais do Document Cloud {#tutorials-doc-cloud}

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Junho de 2021 | [Adobe Acrobat para Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | Vídeo | Obtenha acesso a ferramentas PDF que economizam tempo e a fluxos de trabalho de assinatura eletrônica diretamente no aplicativo do Google Drive. |

{style=&quot;table-layout:auto&quot;}

Para obter ajuda sobre a Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem e suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

| Publicado | Nome | Tipo | Descrição |
| ----------| --------- | --------- | --------- |
| Junho de 2021 | [Experimente o Fresco no iPad (e iPhone)](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | Vídeo | Explore um mundo totalmente novo de desenho digital e pintura com o Adobe Fresca nesta oficina prática de 15 minutos. Aprenda rapidamente a trabalhar com camadas e máscaras de recorte para adequar tinta e texturas a uma forma básica. |
| Junho de 2021 | [Decodificação da sopa alfabética de formatos gráficos](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | Vídeo | Arquivos PG, PNG, SVG, GIF e EPS são comumente usados em design, alguns para páginas da Web, outros para apresentações, publicações e projetos criativos. Mas... o que eles querem dizer, e o que você deve escolher? Descubra neste workshop prático de 15 minutos. |

{style=&quot;table-layout:auto&quot;}

Consulte [Tutoriais da Creative Cloud para corporações](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=pt-BR) para obter os tutoriais mais recentes.
