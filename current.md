---
title: Notas de versão mais recentes
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação dos produtos e serviços da Experience Cloud. Encontre ajuda e novos tutoriais da Experience Cloud, da Creative Cloud para corporações e da Document Cloud.
doc-type: release notes
last-update: March 2021
author: mfrei
translation-type: tm+mt
source-git-commit: d7c6508201971164b63a0d0d9490f66a2a87adf6
workflow-type: tm+mt
source-wordcount: '7026'
ht-degree: 32%

---


# Notas de versão da Adobe Experience Cloud - Março de 2021

![Banner](/assets/experience-cloud-banner-3.png)

As soluções e os serviços da Experience Cloud são atualizados mensalmente. Esta página é o local central para encontrar as atualizações, a documentação e os tutoriais da versão mais recente para produtos e serviços [!DNL Experience Cloud]. Você também pode encontrar nova documentação para a [!DNL Creative Cloud for Enterprise] e a [!DNL Document Cloud].

>[!NOTE]
>
>Assine a [Atualização mensal do produto de prioridade da Adobe](https://www.adobe.com/subscription/priority-product-update.html) para receber notificações por email sobre atualizações nesta página. Esta página é mantida durante todo o mês e pode conter conteúdo que está sujeito a alterações antes de uma data de lançamento. Verifique regularmente se há atualizações no produto Adobe enterprise e na documentação do Experience League.

Última atualização: **22 de março de 2021**

* [Status do sistema da Adobe](#status) (não atualizado)
* [Componentes, serviços e administração da interface do usuário do Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [Analytics](#analytics) e [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insight da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/adobe.png) Adobe da sistema de Status {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

As atualizações mais recentes para o Status do Sistema do Adobe são encontradas em [Status do Sistema do Adobe - 21 de maio de 2020](https://docs.adobe.com/content/help/pt-BR/release-notes/experience-cloud/previous/2020/05212020.html#status).

## ![](/assets/ec_appicon_24.png) ÍconeComponentes, serviços e administração da interface do usuário da Experience Cloud  {#ecloud}

**Pesquisa unificada:** a Pesquisa unificada, que está disponível no momento para o Experience Platform, agora oferece suporte à pesquisa em Fontes e Destinos para usuários do Experience Platform. Esse recurso permite pesquisar Segmentos, Conjuntos de dados, Esquemas, Fontes e Destinos.

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Inclui informações de atualização de versão da Experience Platform e do Experience Platform Launch.

* [Notas de versão da Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html). (Atualizado em 24 de fevereiro de 2021)
* [Notas de versão da Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=pt-BR). (Atualizado em 18 de fevereiro de 2021)

### Tutoriais e cursos da Experience Platform

Novos vídeos, tutoriais ou cursos publicados para a Experience Platform e serviços.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Março de 2021 | [Painel de monitoramento](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/monitoring-dashboard.html) | Vídeo | Saiba como monitorar e rastrear dados que são assimilados no Adobe Experience Platform usando o Painel de monitoramento. Esse painel de monitoramento fornece uma exibição de cima para baixo do processamento de dados de origem por meio de data lake para Perfil e Serviços de identidade nos níveis de execução de fonte, fluxo de dados e fluxo de dados, com recomendações acionáveis em tempo hábil. |
| Março de 2021 | [Assimilar dados usando conectores de transmissão do servidor do servidor](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-source-connector.html) | Vídeo | Este vídeo mostra como fazer stream de dados em tempo real de uma fonte de armazenamento em nuvem para a Platform e usar os dados em tempo real para o engajamento do cliente. |
| Março de 2021 | [Ingestão de dados para engenheiros de dados](https://video.tv.adobe.com/v/331971?quality=12&learn=on) | Vídeo | Visão geral do curso Ingestão de dados . |
| 5 de março de 2021 | [Ingestão de dados para engenheiros de dados](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1.dataingestion) | Curso | Como trazer dados de várias fontes para o Adobe Experience Platform e muito mais. |
| Março de 2021 | [Configurar o destino do Azure Blob](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=pt-BR#destinations) | Vídeo | Saiba como percorrer as etapas necessárias para configurar e configurar o destino de armazenamento do Azure Blob em [!UICONTROL Plataforma de dados do cliente em tempo real] (CDP em tempo real). |
| 5 de março de 2021 | [Introdução ao Offer Decisioning para profissionais de marketing](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | Curso | Saiba mais sobre o serviço de aplicativos [!UICONTROL Offer Decisioning] criado sobre o Adobe Experience Platform. Este curso foi projetado para profissionais de marketing que desejam gerar receita, experiência do cliente e fidelidade, fornecendo as melhores ofertas aos clientes. |
| 5 de março de 2021 | [Assimilação de dados de streaming por API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-http-api.html) | Vídeo | Este vídeo mostra como fazer o stream de dados para o Adobe Experience Platform em tempo real usando o endpoint da API HTTP. |
| 5 de março de 2021 | [Monitoramento da assimilação de dados usando a API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/data-monitoring.html?lang=pt-BR#data-ingestion) | Vídeo | Saiba como monitorar e rastrear dados que são assimilados na Adobe Experience Platform usando a interface e a API da plataforma. |
| 5 de março de 2021 | [Assimilar dados de bancos de dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-databases.html?lang=en#sources) | Vídeo | Este vídeo aborda como executar uma assimilação em lote de dados de uma fonte de banco de dados para o Real-time Customer Profile e Experience Data Lake da Adobe Experience Platform, de maneira contínua e escalável. |
| 5 de março de 2021 | [Assimilar dados do Amazon S3](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-amazon-s3.html) | Vídeo | Este vídeo mostra como assimilar facilmente dados de serviços de armazenamento em nuvem no Perfil do cliente em tempo real da Adobe Experience Platform e no lago de dados, de forma contínua e escalável. |
| 5 de março de 2021 | [Assimilar dados do Salesforce CRM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | Vídeo | Este vídeo mostra como assimilar facilmente dados de fontes de CRM no Perfil do cliente em tempo real da Adobe Experience Platform e no lago de dados, de forma contínua e escalável. |
| 5 de março de 2021 | [Assimilar dados da Adobe Analytics](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | Vídeo | O conector do Adobe Analytics Source permite fazer o stream fácil de dados do Adobe Analytics para o Real-time Customer Profile e Experience Data Lake da Adobe Experience Platform, de maneira contínua e escalável. |
| 5 de março de 2021 | [Noções básicas sobre conectores de origem](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/overview.html?lang=en#sources) | Vídeo | Este vídeo fornece uma visão geral de Fontes, ou conectores de origem, no Experience Platform. |
| 5 de março de 2021 | [Detalhes do postman de exportação do console do Adobe IO](https://experienceleague.adobe.com/docs/platform-learn/tutorials/apis/postman.html) | Vídeo | Saiba como autenticar e acessar APIs do Experience Platform. |
| 5 de março de 2021 | [Noções básicas sobre assimilação de dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/understanding-data-ingestion.html#data-ingestion) | Vídeo | Saiba mais sobre os recursos de assimilação de dados do Experience Platform que permitem unir seus dados em uma plataforma aberta e escalável para gerenciar perfis de clientes em tempo real. |

## ![Ícone](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use a Adobe Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Últimas versões de produtos

Versão de fevereiro de 2021 - Saiba mais sobre os recursos, as melhorias e as correções mais recentes nas [Notas de versão do Journey Orchestration](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html).

### Novos cursos e tutoriais do Journey Orchestration

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 16 de março de 2021 | [Atualizar ação do perfil](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=en#building-a-journey) | Vídeo | Saiba como atualizar um perfil de Experience Platform existente com informações provenientes de um evento, de uma fonte de dados ou usando um valor específico. |

### Recursos adicionais do Journey Orchestration

[Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![](/assets/experience_platform_appicon_24.png) IconOffer Decisioning  {#offer-decisioning}

[!UICONTROL O Offer ] Decisioning é um Serviço de aplicativos integrado ao Adobe Experience Platform. Use o [!UICONTROL Offer Decisioning] para oferecer a melhor oferta e experiência aos seus clientes em todos os pontos de contato na hora certa.

### Últimas versões de produtos

Versão de fevereiro de 2021 - Saiba mais sobre os recursos mais recentes nas [Notas de versão do Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new).

### Mais recursos para o Offer Decisioning

[Documentação](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en)  - Vídeos  [explicativos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **25 de março de 2021**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| ----------- | ---------- | ------- |
| Atualizações da API de reparo de dados | 25 de março de 2021 | A API de reparo de dados agora é compatível com variáveis padrão, incluindo [!UICONTROL Page] e [!UICONTROL Endereço IP], variáveis móveis e de vídeo, bem como props e eVars personalizados.  Os valores em variáveis podem ser excluídos ou novos valores podem ser definidos. A API agora também oferece filtragem de URLs, sequências de consulta, sinais e muito mais. |
| Analysis Workspace: [!UICONTROL Componentes] > [!UICONTROL Preferências do usuário] | 25 de março de 2021 | A página [!UICONTROL Componentes] > [!UICONTROL Preferências do usuário] permite gerenciar as configurações [!UICONTROL Analysis Workspace] e seus componentes relacionados para o usuário. [!UICONTROL As ] preferências do usuário se aplicam a todos os novos projetos e painéis. <br>**Observação:** as configurações a seguir foram movidas para o   User preferencespage:<ul><li>Configurações do relatório: Separador de milhares (agora chamado de _Number format_)</li><li>Configurações do relatório: Separador CSV</li><li>Projetos do Workspace: Ajuda > Ativar dicas</li><li>Projetos do Workspace: Painel em branco _Iniciar novos projetos com esta opção de painel_</li></ul> |
| Analysis Workspace: [!UICONTROL Previsão do bucket inteligente do histograma] | 25 de março de 2021 | [!UICONTROL O Histograma ] Predição de bucket inteligente ajuda com histogramas de métricas de alta cardinalidade, identificando automaticamente a largura e o número corretos de buckets para sua propagação de dados. Para métricas de baixa cardinalidade, a visualização se comporta da mesma forma que antes. |
| [!UICONTROL Usage ] LogAPI | 25 de março de 2021 | Esta é uma nova API v2.0 do Analytics que permite acesso programático aos mesmos dados de log de uso disponíveis em **[!UICONTROL Admin]** > **[!UICONTROL Log]** > **[!UICONTROL Log de uso e acesso]**. Detalhes adicionais sobre autenticação, esquema e resposta de amostra estão disponíveis [aqui](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md). |
| Suporte a painéis do Analytics para intervalos de datas personalizados | 25 de março de 2021 | Os criadores do Scorecard podem criar e aplicar intervalos de datas personalizados a projetos do scorecard móvel. Os criadores podem escolher entre predefinições de intervalo de datas familiar e móvel ou criar um intervalo de datas personalizado. |

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Data do Target | Descrição |
| ----------- | ---------- | ----- |
| Suporte para [!UICONTROL painéis do Adobe Analytics] | 25 de março de 2021 | [!UICONTROL O Customer Journey Analytics]  (CJA) agora é compatível com o  [!UICONTROL Adobe Analytics Dashboards Scorecard ] Builder e o aplicativo móvel. Isso permite que executivos e usuários empresariais vejam seus KPIs entre canais com base em dados de CJA, usando o mesmo aplicativo que já pode estar usando para o Adobe Analytics. |
| Analysis Workspace: **[!UICONTROL Componentes]** > **[!UICONTROL Preferências do usuário]** | 25 de março de 2021 | A página [!UICONTROL Componentes] > [!UICONTROL Preferências do usuário] permite gerenciar as configurações [!UICONTROL Analysis Workspace] e seus componentes relacionados para o usuário. [!UICONTROL As ] preferências do usuário se aplicam a todos os novos projetos e painéis. <br>**Observação:** as configurações a seguir foram movidas para o   User preferencespage:<ul><li>Projetos do Workspace: Ajuda > Ativar dicas</li><li>Projetos do Workspace: Painel em branco _Iniciar novos projetos com esta opção de painel_</li></ul> |
| Analysis Workspace: [!UICONTROL Previsão do bucket inteligente do histograma] | 25 de março de 2021 | [!UICONTROL O Histograma ] Predição de bucket inteligente ajuda com histogramas de métricas de alta cardinalidade, identificando automaticamente a largura e o número corretos de buckets para sua propagação de dados. Para métricas de baixa cardinalidade, a visualização se comporta da mesma forma que antes. |
| Suporte a painéis do Analytics para o Customer Journey Analytics | 25 de março de 2021 | O aplicativo de painéis do Analytics agora é compatível com o Customer Journey Analytics. Os usuários com o Customer Journey Analytics podem exibir KPIs de qualquer dado assimilado no Adobe Experience Platform no aplicativo de painéis do Analytics. O Customer Journey Analytics permite combinar várias fontes de dados para obter uma visualização verdadeira e de vários canais da experiência do cliente. Agora, com o aplicativo de painéis do Analytics, você pode obter uma visualização holística e atualizada de sua empresa, a qualquer hora e em qualquer lugar. |

### Correções no Adobe Analytics {#aa-fixes}

* Correção de um problema em que, após editar e salvar o novo proprietário de um segmento, esse novo proprietário não era refletido na interface do usuário do segmento. (AN-234502; AN-250970; (AN-250286)
* Correção de um problema que fazia com que um conjunto de relatórios do aplicativo consumisse chamadas do servidor primárias e chamadas do servidor primário móvel. (AN-244029)
* Correção de um problema com o tempo de resposta lento da interface do usuário ao abrir projetos do [!UICONTROL Workspace]. (AN-242553)
* Correção de um problema que impedia o logon no [!UICONTROL Report Builder] após a atualização para a versão mais recente. (AN-248825)
* Correção de um problema com permissões de usuário para usuários não administradores: Um usuário deve ter uma permissão, desde que seja adicionado a pelo menos um de seus perfis em [!UICONTROL Admin Console]. A adição de usuários a perfis deve ser adicionada apenas às permissões que têm e não deve remover nada que já tenham direito por meio de outros perfis de produto. (AN-242723)
* Correção de um problema de codificação de idioma com [!UICONTROL Feeds de dados]. (AN-249862)
* Correção de um problema em que os usuários não conseguiam acessar projetos compartilhados do [!UICONTROL Workspace]. (AN-247814)
* Correção de um problema em que [!UICONTROL Visualizações de Alerta] não correspondia ao número de [!UICONTROL Alertas] disparados. (AN-249392; (AN-250804)

#### Outras correções do Adobe Analytics

AN-206099; AN-237460; AN-241803; AN-243735; AN-244081; AN-244615; AN-244687; AN-246832; AN-247227; AN-248237; AN-248478; AN-248852; AN-249115; AN-249140; AN-249216; AN-249275; AN-249538; AN-249963; AN-250034; AN-250270; AN-250320; AN-250338; AN-250377; AN-250378; AN-250557; AN-250609; AN-250614; AN-250615; AN-250885; AN-251088; AN-251137; AN-251190; AN-251192; AN-251193; AN-251301; AN-251496; AN-251545; AN-251734; AN-251735; AN-251744; AN-251816; AN-251982; AN-251972; AN-252051; AN-252073; AN-252105; AN-252409; AN-252640

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| ----------- | ---------- | ---------- |
| [!UICONTROL Processamento VISTA do Same-as-SiteCatalyst]  = ON | 17 de março de 2021 | Em 17 de junho de 2021, todos os conjuntos de relatórios serão atualizados para terem o [!UICONTROL Processamento VISTA do mesmo SiteCatalyst] definido como ATIVADO. Essa alteração afeta os relatórios de [!UICONTROL Data Warehouse] processando os dados para corresponder às regras de processamento. Para dúvidas ou esclarecimentos, entre em contato com o Atendimento ao cliente do Adobe. |
| EOL de [!UICONTROL Processamento Completo] [!UICONTROL Fontes de Dados] | 10 de março de 2021 | O Adobe planeja descontinuar [!UICONTROL Processamento completo] [!UICONTROL Fontes de dados] no futuro. A partir de 25 de março de 2021, novas importações desse tipo não poderão mais ser criadas. Use [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) para importar esse tipo de dados. [Saiba mais](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html) |
| Opções de Reports &amp; Analytics da página de aterrissagem | 19 de fevereiro de 2021 | Em 25 de março de 2021, as opções para definir novos painéis de Reports &amp; Analytics ou outro conteúdo como sua página de aterrissagem do Adobe Analytics serão removidas. Se você tiver definido anteriormente uma página de Reports &amp; Analytics como sua página de aterrissagem personalizada, ela continuará a funcionar até que sua página de aterrissagem seja modificada em [!UICONTROL Preferências do usuário]. |
| Fim da vida útil do Ad Hoc Analysis | Janeiro de 2021 | [!UICONTROL A Ad Hoc Analysis] chegará ao fim da vida útil em 1º de março de 2021. Para obter mais informações, visite [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| Fim da vida útil para três serviços de API do Analytics | 6 de janeiro de 2021 | Em 30 de abril de 2021, os serviços de API herdados a seguir do Analytics estão programados para atingir sua data de fim de vida e serão encerrados. Quaisquer integrações atuais criadas com esses serviços deixarão de funcionar nesse dia.<ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre fim da vida útil da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder às suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Fim da vida útil do Data Connectors da Adobe | 13 de julho de 2020 | Os [!UICONTROL Data Connectors] da Adobe são alimentados por tecnologia herdada que não é mais viável ou compatível. Um novo padrão está disponível no [Programa de parceiro Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud). Você pode usar esse padrão para que qualquer integração continue a ser oferecida e suportada. A data de término oficial é 1º de agosto de 2021. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/import/dataconnectors/data-connectors-eol.html) |

### AppMeasurement {#appm}

Para obter as atualizações mais recentes das versões do AppMeasurement, consulte as [notas de versão do AppMeasurement para JavaScript](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/appmeasurement-updates.html).

### Recursos de ajuda do Analytics

* [Documentação e tutoriais do produto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR)

## ![Ícone](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Correções e aprimoramentos no Audience Manager.

### Correções e melhorias {#aam-fixes-and-improvements}

* Correção de um problema no [Relatório de status de integração](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html?lang=pt-BR). Nesse problema, havia uma discrepância entre os registros no relatório e os do arquivo carregado por um parceiro de integração. (AAM-57415)
* Correção de um problema que resultava na validação incorreta de mapeamento de segmento duplicado para **[!UICONTROL Destinos com base em pessoas]**. (AAM-56631)
* Correção de um problema que impedia alguns usuários de acessar **[!UICONTROL Relatórios de público-alvo]**. (AAM-57412)
* Correção de uma vulnerabilidade [!UICONTROL Remote Code Execution] que poderia ser usada por invasores para acessar dados confidenciais. (AAM-57495)

### Cursos e tutoriais do Audience Manager {#tutorials-aam}

Novos vídeos, tutoriais ou cursos publicados para o Audience Manager.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 19 de março de 2021 | [Compreensão da governança de dados na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-data-gov-for-aam-users.html) | Vídeo | Saiba mais sobre a funcionalidade de governança de dados em [!UICONTROL Plataforma de dados do cliente em tempo real]. |
| 19 de março de 2021 | [Uma tabela de duas permissões - marcas e consumidores](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/brands-vs-consumers.html) | Vídeo | Neste webinário, o Adobe descompacta o nível de compreensão e disponibilidade de anunciantes e editores para um futuro sem cookies, o impacto em seus casos de uso e a percepção que eles têm do ecossistema mais amplo. |
| 5 de março de 2021 | [10 considerações para o Gerenciamento responsável de dados do cliente](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/ten-considerations-for-responsible-customer-data-management.html) | Evento | Saiba mais sobre o Adobe e o Scotiabank Digital sobre as principais considerações para um gerenciamento responsável de dados. |
| 19 de março de 2021 | [O futuro do gerenciamento de dados e do ambiente de mudança](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/the-future-of-data-management-and-the-changing-environment.html) | Evento | Neste webinário, veja como o Adobe e a 451 Research estão pensando sobre o futuro da tecnologia e dos dados para lidar com o novo ambiente de marketing e começar a preparar sua empresa para o futuro do gerenciamento de dados. |
| 21 de março de 2021 | [Noções básicas sobre esquemas e XDM na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) | Vídeo | Ao migrar do Audience Manager para a Real-time Customer Data Platform (CDP em tempo real), você encontrará alguns novos conceitos e práticas. Os esquemas e o XDM se encaixam nessa categoria. Este vídeo explica esses conceitos. |
| 17 de março de 2021 | [Compreensão de sinais na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html) | Vídeo | Este vídeo destina-se aos usuários do Audience Manager que estão migrando para a Plataforma de dados do cliente em tempo real (CDP em tempo real) e discute como os sinais (pares de valores chave) usados no Audience Manager para criar características são usados na plataforma. |
| 12 de março de 2021 | [Noções básicas sobre esquemas e XDM na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html) | Vídeo | Ao migrar do Audience Manager para a Real-time Customer Data Platform (CDP em tempo real), você encontrará alguns novos conceitos e práticas. Os esquemas e o XDM se encaixam nessa categoria. Este vídeo explica esses conceitos. |
| 12 de março de 2021 | [Entendendo a assimilação de dados da Web na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-web-ingestion-for-aam-users.html) | Vídeo | Saiba mais sobre os conceitos de como trazer dados do site para a Real-time Customer Data Platform (CDP em tempo real) e inclui um toque de alto nível sobre onde o Audience Manager Data Connector se encaixa, bem como como como os dados podem se mover do site diretamente pelo SDK da Web para a CDP em tempo real. |
| 3 de março de 2021 | [Compreensão de segmentos na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=en#other-integrations) | Vídeo | Saiba mais sobre as diferenças nos segmentos e na criação de segmentos entre o Audience Manager e a CDP em tempo real. |
| 3 de março de 2021 | [Compreensão de características na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=en#other-integrations) | Vídeo | Aprenda as características no Audience Manager e o equivalente na CDP em tempo real. |
| 3 de março de 2021 | [Compreensão da assimilação de dados primários na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=en#other-integrations) | Vídeo | Saiba mais sobre a assimilação de dados offline próprios na Plataforma de dados do cliente em tempo real (CDP em tempo real). Saiba mais sobre algumas das principais diferenças entre os dois produtos em relação à assimilação de dados e mostra como o Audience Manager Data Connector pode ser usado como uma lacuna de interrupção até que os processos tenham sido transferidos para a CDP em tempo real. |
| 1 de março de 2021 | [Comercializar seus próprios públicos-alvo oferecendo no Audience Marketplace](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=en#audience-marketplace) | Vídeo | Saiba como configurar seus dados como um feed de dados privado ou público no Audience Marketplace, tornando-o um provedor de dados de terceiros ou segundo. |
| Março de 2021 | [Criação e gerenciamento da ativação de dados no Audience Manager](https://experienceleague.adobe.com/?lang=pt-BR&amp;recommended=AudienceManager-U-1-2020.4) | Curso | Neste curso, saiba mais sobre como ativar seus públicos-alvo, por exemplo, enviar dados de público-alvo para parceiros de destino para personalizar a experiência para seus usuários finais. Saiba mais sobre as noções básicas de destinos, como escolher o destino certo e como preparar e enviar dados de público-alvo para destinos de redes sociais com base em pessoas, não em cookies. |
| Março de 2021 | [Audience Manager Advanced Skilds](https://experienceleague.adobe.com/?lang=pt-BR&amp;recommended=AudienceManager-U-1-2020.5) | Curso | Depois de dominar as noções básicas do Audience Manager, faça este curso para saber mais sobre como elevar seu gerenciamento de público-alvo a um próximo nível. Saiba como usar a IA com modelos algorítmicos, como usar as Regras de mesclagem de perfis para entender seus clientes como pessoas em vez de dispositivos e outros tópicos excelentes para estender o uso do DMP. |

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

Novos recursos, correções e atualizações no Experience Manager. A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

>[!NOTE]
>
>A Adobe recomenda visitar a página de [Atualizações de versão e roteiro do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para se manter atualizado sobre as informações de lançamento.

### Versões do produto

* **AEM 6.5.8.0**
O AEM 6.5, Service Pack 8 (6.5.8.0 lançado em 11 de março de 2021), é uma atualização importante que inclui novos recursos, principais melhorias para o cliente, melhor desempenho, estabilidade e segurança, lançados desde a disponibilização geral do AEM 6.5, em abril de 2019.
   * [Notas de versão](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=pt-BR#service-pack)
   * [Resultados da versão do AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=pt-BR#forms-updates)

* **AEM 6.4.8.4**
AEM 6.4, Service Pack 8, Cumulative Fix Pack 4 (6.4.8.4 lançado em 25 de fevereiro de 2021) é uma atualização importante que inclui várias correções internas e de clientes desde a disponibilização geral do AEM 6.4, Service Pack 8 (6.4.8.0), em março de 2020.
   * [Notas de versão](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=pt-BR)
   * [Resultados da versão do AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager as a Cloud Service**

   Quais são as novidades do Experience Manager como Cloud Service?

   * **Experience Manager Sites como Cloud Service**

      * [O componente](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=en) RemotePage: Adição de suporte para visualização e edição de SPA externos no Experience Manager usando.
      * [Edição de um SPA externo no Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=en): Adição da capacidade de carregar um aplicativo de página única independente em uma instância do Experience Manager, adicionar seções editáveis de conteúdo e ativar a criação.
   * **Experience Manager Assets as a Cloud Service**

      * O Experience Manager Assets as a Cloud Service está qualificado para ter uma instância pré-configurada do Brand Portal. O usuário do Cloud Manager pode ativar o Brand Portal no Experience Manager Assets as a Cloud Service. Consulte [Ativar o Brand Portal usando o Brand Portal](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html).
      * Agora, as empresas podem adquirir ativos usando o Brand Portal. O recurso de fornecimento de ativos usa o Brand Portal para ajudar os clientes a se envolver com usuários de agências para obter ativos para novas campanhas de marketing, fotografias e projetos. Consulte [Visão geral da origem dos ativos](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=en) no Guia do Brand Portal.
      * O relatório de uso do Brand Portal agora exibe somente os usuários ativos. Os usuários inativos não são exibidos agora. Usuários ativos são aqueles cuja conta está atribuída a um perfil de produto no Admin Console. Consulte [Trabalhar com relatórios](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=en) no Guia do Brand Portal.
      * No Brand Portal, uma nova configuração de download é introduzida, que permite criar uma pasta separada para cada ativo ao baixar pastas, coleção e assim por diante. Consulte [Download de ativos](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=en) em **Baixar ativos do Brand Portal** no Guia do Brand Portal.
   * **Experience Manager Forms as a Cloud Service**

      A AEM Forms tem ajudado muitas organizações a oferecer excelentes experiências de integração e inscrição ao longo dos anos. Essas experiências têm ajudado organizações a converter leads em vendas, processar dados capturados do cliente, fornecer experiências responsivas com base no perfil do público-alvo e muito mais. Agora, o AEM Forms está disponível como um serviço em nuvem.

      Você pode usar o AEM Forms como um Cloud Service para criar formulários digitais, conectar formulários a fontes de dados existentes, integrar formulários com o Adobe Sign para adicionar assinaturas eletrônicas a formulários, gerar Documento de registro (DoR) para arquivar formulários enviados como arquivos PDF. O serviço também pode converter PDF forms existentes em formulários digitais. Além dos recursos padrão do AEM Forms, o serviço oferece vários recursos nativos em nuvem como dimensionamento automático, tempo de inatividade zero para atualizações e ambiente de desenvolvimento nativo em nuvem. Leia [esta publicação do blog](https://blog.adobe.com/en/publish/2021/03/11/experience-manager-forms-as-a-cloud-service.html) para saber mais sobre os recursos do AEM Forms as a Cloud Service.

      Entre em contato com o representante do Adobe para obter uma demonstração ou para se inscrever no serviço.


   * **Experience Manager Commerce as a Cloud Service**

      * Gerenciamento de experiência do produto: Enriqueça as páginas do catálogo de produtos individualmente com Fragmentos de experiência.
      * Propriedades do console do produto estendido para mostrar Ativos vinculados e Fragmentos de experiência, incluindo ações para navegar rapidamente para o conteúdo associado.
      * Lançamento do site de referência CIF Venia - 2021.02.24, que inclui os Componentes principais CIF versão 1.8.0. Consulte [Site de referência CIF Venia 2021.02.24](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24) para obter mais detalhes.
      * Lançamento da versão 1.8.0 dos Componentes principais da CIF. Consulte [Componentes principais da CIF 1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0) para obter mais detalhes.
   * **Cloud Manager**

      * Os clientes com ambientes que têm configurações pré-existentes de Nome de domínio personalizado para [Listas de permissões de IP](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=en#pre-existing-cdn), [Certificados SSL](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=en#pre-existing-cdn) e [Nomes de domínio personalizados](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=en#pre-existing-cdn) agora veem uma mensagem sobre suas configurações existentes anteriormente. Eles também podem se autoservir por meio da interface do usuário.
      * Os usuários com as permissões necessárias agora podem editar um Programa, permitindo que façam o seguinte de maneira automatizada:
         * Adicionar a solução Sites a um programa existente com Ativos ou vice-versa.
         * Remova Sites ou Ativos de um programa existente com Sites e Ativos.
         * Adicione o segundo direito de solução não utilizada a um programa existente ou como um novo programa.
      * **AEM Push** Updatelabel agora é exibido para  *Pipeline* Execution e  ** Activityscreens.
      * Se um ambiente estiver hibernado, mas também houver uma atualização de Experience Manager disponível, o status **Hibernado** terá prioridade sobre **Atualização disponível**.
      * Agora os usuários podem ver suas funções do Cloud Manager selecionando **Exibir funções do Cloud Manager** depois de navegar até o ícone Perfil do usuário (canto superior direito) do Unified Shell.
      * O rótulo **Application for Approval** foi renomeado para **Production Approval** para maior clareza.
      * O rótulo **Version** foi renomeado para **Git Tag** na tela de execução do pipeline de Produção.
      * Os rótulos que definem o comportamento quando métricas importantes não atingirem o limite definido foram renomeados para refletir seu comportamento verdadeiro: **Cancelar Imediatamente** e **Aprovar Imediatamente**.
      * As listas de desaprovação de classe e método foram atualizadas com base na versão `2021.3.4997.20210303T022849Z-210225` do SDK do Experience Manager Cloud Service.
      * O pipeline de Produção do Cloud Manager agora inclui o recurso [Teste de interface personalizada](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=en#custom-ui-testing).




### **Comunidade**

* **Desenvolvedores Adobe Live 2021 | Lista completa de sessões**

   [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875) Esta é uma lista agregada de todas as sessões do Experience Manager que ocorrem no  **Adobe Developers Live**.

* **Adobe Summit 2021 | Lista Experience Manager**

   [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344) Esta é uma lista agregada de todas as sessões do Experience Manager que ocorreram no  **Adobe Summit 2021**.

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Atualizações de versão e roteiro do Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-release-information/aem-release-updates/home.html)
* [Informações sobre a versão do Experience Manager as a Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/release-notes/home.html)
* [Notas de versão do Experience Manager Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://docs.adobe.com/content/help/pt-BR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Notas de versão do Cumulative Fix Pack do Experience Manager 6.4](https://docs.adobe.com/content/help/pt-BR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notas de versão do Experience ManagerAssets Dynamic Media](https://docs.adobe.com/content/help/pt-BR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de versão do Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Notas de versão do aplicativo para desktop Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-desktop-app/using/release-notes.html)
* [Notas de versão do Experience Manager Dispatcher](https://docs.adobe.com/content/help/pt-BR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

### Cursos e tutoriais do Experience Manager

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Março de 2021 | [Entrega de conteúdo no Experience Manager Cloud Service](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html#content) | Evento | O Adobe Experience Manager as a Cloud Service tem uma poderosa arquitetura de entrega de conteúdo pré-configurada. Demonstrar como tirar o melhor proveito das configurações otimizadas de entrega de conteúdo |
| Março de 2021 | [Migrar artigo do helpx sobre tipos de Forms e Documentos para ExL](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/pdf-forms-and-documents.html?lang=en#document-services) | Artigo | Um artigo explicando os diferentes tipos de PDF forms e documentos. |
| Março de 2021 | [Implantação de produção com um ambiente de publicação do AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html#graphql) | Tutorial | Configure um ambiente local para simular o conteúdo que está sendo distribuído de uma instância de Autor para uma instância de Publicação. Gere uma criação de produção de um aplicativo React configurado para consumir conteúdo do ambiente de publicação do AEM usando as APIs GraphQL. Ao longo do caminho, você aprenderá a usar variáveis de ambiente de maneira eficaz e a atualizar as configurações AEM CORS. |
| Março de 2021 | [Gerenciamento de conteúdo headless usando APIs GraphQL](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless) | Curso | Explore como as APIs GraphQL da AEM e os recursos sem periféricos podem ser usados para potencializar as experiências encontradas em um aplicativo externo. |
| Março de 2021 | [Lançamentos - Vídeo de recurso](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html) | Vídeo | As inicializações no AEM Sites fornecem uma maneira de criar, criar e revisar o conteúdo do site para uma versão futura. Durante a criação do lançamento, o site de produção pode continuar a evoluir e a mudar diariamente como normalmente aconteceria. |
| Março de 2021 | [Ativos relacionados e não relacionados - Videoktext de recurso](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html?lang=pt-BR) | Vídeo | Saiba como estabelecer e gerenciar relacionamentos entre ativos no AEM. |
| Março de 2021 | [Autenticação para o AEM as a Cloud Service de um aplicativo externo](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | Curso | Saiba como um aplicativo externo pode usar Tokens de acesso ao desenvolvimento local e Credenciais de serviço para autenticar programaticamente para AEM como um Cloud Service sobre HTTP. |
| Março de 2021 | [Preencha e assine vários formulários em um aplicativo de hipoteca](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms&amp;lang=pt-BR) | Curso | Assine um pacote de documentos perfeitamente usando a integração do AEM Forms e do Sign. Os dados inseridos no formulário podem ser usados para preencher previamente formulários subsequentes no pacote. |
| Março de 2021 | [Controle de versão / Timewarp no AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html) | Vídeo | O Timewarp é um recurso do Adobe Experience Manager Sites que fornece aos autores uma maneira rápida de revisar o estado de uma página em um momento específico no passado. |
| Março de 2021 | [Foundation - Gerenciamento de fluxo de trabalho](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=en#workflow) | Vídeo | Este vídeo usa Modelos de fluxo de trabalho para demonstrar esse conjunto de recursos, no entanto, eles também se aplicam a AEM Iniciadores. |
| Março de 2021 | [Blocos de fragmento de experiência](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html) | Vídeo | Os blocos de construção são um subrecurso dos Fragmentos de experiência. Os blocos de construção permitem que os autores de conteúdo reutilizem componentes em diferentes variações de Fragmentos de experiência. |
| Março de 2021 | [Editor de fluxo de trabalho](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=en#workflow) | Vídeo | O fluxo de trabalho permite o gerenciamento de processos de negócios no Experience Manager e é usado para o processamento automático de conteúdo, além de facilitar a governança e os processos que exigem tomada de decisão humana. |
| Março de 2021 | [Grupos de usuários fechados no AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html) | Vídeo | Grupos de usuários fechados (CUGs) é um recurso usado para restringir o acesso ao conteúdo a um grupo selecionado de usuários em um site publicado. Este vídeo mostra como Grupos de usuários fechados podem ser usados com os Ativos da Adobe Experience Manager para restringir o acesso a uma pasta específica de ativos. |
| Março de 2021 | [Relatórios ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html) | Vídeo | Saiba como a AEM Assets fornece uma estrutura de relatórios de nível empresarial que pode ser dimensionada para repositórios grandes por meio de uma experiência intuitiva do usuário. |
| Março de 2021 | [Tags inteligentes para imagens com o AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html) | Vídeo | As tags inteligentes de imagens aumentam AEM recursos de pesquisa adicionando tags de metadados de forma automática e inteligente a ativos de imagem com base no conteúdo da imagem. |
| Março de 2021 | [Em cascata de metadados, visibilidade](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html) | Vídeo | Saiba mais sobre as novas regras dinâmicas para requisitos de campo, visibilidade e opções contextuais. O vídeo também detalha as etapas necessárias para um administrador aplicar essas regras a um esquema de metadados personalizado. |
| Março de 2021 | [Mestres do projeto](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=en#delete-project-masters) | Vídeo | A exclusão de um projeto principal resulta em projetos derivados inutilizáveis. |
| Março de 2021 | [Personalização das propriedades da página](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html) | Vídeo | Crie um vídeo técnico sobre como estender e personalizar melhor as Propriedades da página. |
| Março de 2021 | [Tradução de fragmentos de conteúdo](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html) | Vídeo | Saiba como os Fragmentos de conteúdo podem ser localizados e traduzidos com o Adobe Experience Manager. Os ativos de mídia mista associados a um Fragmento de conteúdo também podem ser extraídos e traduzidos. |
| Março de 2021 | [Fragmentos de experiência](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html) | Vídeo | Saiba como os Fragmentos de experiência permitem que os autores de conteúdo reutilizem conteúdo em canais, incluindo páginas de Sites e sistemas de terceiros. |
| Março de 2021 | [Aumento da pesquisa de pesquisa aprimorada](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html) | Vídeo | Saiba mais sobre o Aumento de pesquisa. |

### Outros recursos de Ajuda do Experience Manager

* [Guias do Experience Manager as a Cloud Service ](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
* [Página de aprendizagem e suporte do Experience Manager 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Página de aprendizagem e suporte do Experience Manager 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Página de aprendizagem e suporte do Experience Manager 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página de aprendizagem e suporte do Experience Manager 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versões anteriores da documentação do Experience Manager](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/home.html)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produtos

Saiba mais sobre os recursos, melhorias e correções mais recentes lançados:

* [Notas de versão do Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html)
* [Notas de versão do Campaign Classic](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html).

>[!IMPORTANT]
>
>Saiba mais sobre [as atualizações de configuração necessárias](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/acc-config-updates.html?lang=en) para Adobe Campaign Classic.

### Novos cursos e tutoriais do Campaign

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Solução | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 23 de fevereiro de 2021 | [Deliverability - Métricas para deliverability](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html) | Campaign Classic/Padrão | Saiba mais sobre as principais métricas de capacidade de entrega para monitorar e como usá-las para identificar um problema de reputação. |
| 23 de fevereiro de 2021 | [Entregabilidade - Rejeições](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html) | Campaign Classic/Padrão | Saiba mais sobre os diferentes tipos de rejeições. |
| 23 de fevereiro de 2021 | [Deliverability - Reclamações](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html) | Campaign Classic/Padrão | Saiba mais sobre as reclamações que são registradas quando um usuário indica que um email é indesejado ou inesperado. |
| 23 de fevereiro de 2021 | [Entregabilidade - armadilhas de spam](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html) | Campaign Classic/Padrão | Saiba mais sobre os diferentes tipos de rejeições. |
| 23 de fevereiro de 2021 | [Entregabilidade - Marcação e bloqueio](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html) | Campaign Classic/Padrão | Saiba por que os ISPs colocam mensagens de email em pastas de spam ou as bloqueiam. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Processo de transição - Infraestrutura](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html) | Campaign Classic/Padrão | Saiba o que é necessário para construir corretamente uma infraestrutura de email. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Envolvimento](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html) | Campaign Classic/Padrão | Saiba mais sobre os diferentes tipos de envolvimento e por que o envolvimento é importante para a capacidade de entrega. |
| 23 de fevereiro de 2021 | [Deliverability - Processo de transição: Critérios de direcionamento](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html) | Campaign Classic/Padrão | Saiba como estabelecer uma reputação positiva a partir do get-go para criar confiança de maneira eficaz antes de acumulá-la em seus públicos menos envolvidos. |
| 23 de fevereiro de 2021 | [Entregabilidade - Processo de transição - Considerações específicas do ISP durante o aquecimento de IP](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html) | Campaign Classic/Padrão | Saiba mais sobre as diferentes regras e maneiras que os provedores de ISP têm de observar o tráfego |
| 24 de fevereiro de 2021 | [Deliverability - Primeiras impressões - introdução](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html) | Campaign Classic/Padrão | Saiba como configurar-se para executar um programa de email bem-sucedido fazendo uma boa primeira impressão nessas áreas. |
| 24 de fevereiro de 2021 | [Deliverability - Processo de transição: Volume](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html) | Campaign Classic/Padrão | Entenda como o volume de envio influencia a capacidade de delivery de suas campanhas de email. |
| 24 de fevereiro de 2021 | [Deliverability - Primeiras impressões - Coleta de endereços e crescimento de listas](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) | Campaign Classic/Padrão | Saiba quais são as melhores fontes para novos endereços de email, como garantir alta qualidade dos dados e alinhamento às diretrizes legais. |
| 25 de fevereiro de 2021 | [Deliverability - Primeiras impressões - Email de boas-vindas](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) | Campaign Classic/Padrão | Saiba quais devem ser os principais elementos da sua estratégia de boas-vindas. |
| 25 de fevereiro de 2021 | [Deliverability - Processo de transição: Troca de plataformas de email](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html) | Campaign Classic/Padrão | Saiba como fazer a transição sem problemas ao alternar plataformas de email. |
| 26 de fevereiro de 2021 | [Entregabilidade - Práticas recomendadas do conteúdo para oferecer a capacidade de entrega ideal](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html) | Campaign Classic/Padrão | Dicas para otimizar o conteúdo do seu email para entrega. |
| 26 de fevereiro de 2021 | [Entregabilidade - Permanência do remetente](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html) | Campaign Classic/Padrão | Saiba por que é importante estabelecer um volume de envio consistente. |
| 26 de fevereiro de 2021 | [Capacidade de entrega - Monitoramento contínuo](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html) | Campaign Classic/Padrão | Saiba quais problemas você precisa procurar ao monitorar seus deliveries. |
| 26 de fevereiro de 2021 | [Capacidade de entrega - colocá-la na prática](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html) | Campaign Classic/Padrão | Quatro pilares-chave para o sucesso. |
| 10 de março de 2021 | [Práticas recomendadas de capacidade de delivery para líderes, usuários empresariais e administradores](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability) | Campaign Classic | Conheça os principais termos, conceitos e abordagens de entrega para garantir o sucesso do seu programa de marketing. |

### Recursos de ajuda

* Adobe Campaign Standard: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/campaign-standard-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/overview.html) - [Planejamento de lançamento](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-planning.html) - [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/campaign-classic-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-classic-learn/tutorials/overview.html)- [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/documentation-updates.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html) - Vídeos explicativos do [Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/pt-BR/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notas de versão da Adobe Advertising Cloud.

* [Novos recursos na Advertising Cloud DSP](#adcloud-dsp)
* [Novos recursos na Advertising Cloud Search](#adcloud-search)

### Novos recursos no [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última atualização: **28 de outubro de 2020**

| Recurso | Descrição |
| -----------| ---------- |
| Novo Ajuda | (Versão de 28 de outubro) A ajuda herdada foi substituída por páginas atualizadas, que estão disponíveis no link Ajuda no menu principal do DSP e também estão sempre disponíveis em [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=pt-BR](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=pt-BR) |
| Campanhas | (Versão de 28 de outubro) As visualizações anteriores do Campaigns Beta agora são as visualizações padrão do Campaigns, para obter insights mais rápidos, fluxos de trabalho simplificados e visualizações personalizadas. |
| Inventário privado | (Versão de 15 de outubro) Todos os usuários agora podem configurar e editar informações da ID de negócios usando um novo formulário, que é uma versão simplificada do formulário antigo de [!UICONTROL Veiculação de anúncios inteligentes]. Para configurar as informações da nova ID de negócios, acesse **[!UICONTROL Inventário > Vendas]**, clique em **[!UICONTROL Criar]** e, em seguida, clique em **[!UICONTROL ID de acordo beta]**. |
| Previsão de posicionamento | (Versão de 15 de outubro) Para inserções com ritmo de nível de inserção, a seção [!UICONTROL Previsão] das configurações de inserção inclui uma nova seção [!UICONTROL Máximos estimados], que indica quanta capacidade está disponível com a configuração de direcionamento atual. |

### Novos recursos no [!DNL Advertising Cloud Search] {#adcloud-search}

Última atualização: **22 de janeiro de 2021, para lançamento em 23 de janeiro**

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanhas de pesquisa]<br> Relatórios | A Advertising Cloud Search não reporta mais novos dados de posição média para campanhas Microsoft® Advertising. A coluna Posição média mostra valores de zero (0) para datas a partir de 23 de janeiro. Esse processo é uma preparação para a descontinuação dos dados de posição média da Microsoft em janeiro de 2021.<br>Os dados de posição média coletados até 22 de janeiro ainda estão disponíveis nos relatórios. |

### Tutoriais e cursos da Ad Cloud

Atualizado: **2 de dezembro de 2020**

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Consulte as [notas de versão](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) do Magento Commerce e de Código aberto para obter as informações mais recentes.

## ![Ícone](/assets/target.png)[!DNL Target] {#target}

Consulte as [[!DNL Target] notas de versão](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html) para obter as informações mais recentes.

## ![Ícone](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

O [!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes envolvendo-se em cada estágio de jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte as [!DNL Marketo Engage] [notas de versão](https://docs.marketo.com/display/public/DOCS/Release+Notes) para obter as informações mais recentes.

### Recursos futuros

Os seguintes recursos serão lançados ao longo do trimestre:

| Recurso | Descrição |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nova segmentação baseada em conta</li><li>Salvar filtros específicos do painel</li><li>Exportar painéis Bizible como PDFs</li></ul> |
| Conexão de vendas | Compor atualizações/aprimoramentos da Janela e do Centro de comando |

### Desativações

* **Parâmetro &quot;_method&quot; da API de ativos:** a partir de setembro de 2020, os access points da API de ativos não aceitarão mais `_method` passar parâmetros de consulta em um corpo do POST para ignorar as limitações de comprimento do URI.
* **Desativação do suporte ao Internet Explorer:** a partir do lançamento realizado em 31 de julho de 2020, a interface do usuário do Marketo Engage não será mais compatível com o Internet Explorer.

## ![Ícone](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Para obter ajuda sobre a Document Cloud, consulte:

* [Hub de aprendizagem do Adobe Acrobat](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Hub de aprendizagem do Adobe Sign](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Aprendizagem e suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

Novos tutoriais para a Creative Cloud Enterprise.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Março de 2021 | [Como entender o licenciamento de usuário nomeado](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/nameduserlicensing.html) | Artigo | Saiba mais sobre a importância do Licenciamento de usuário nomeado. |
| 5 de março de 2021 | [Expiração do número de série](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/cceserial.html) | Vídeo | Saiba mais sobre as etapas necessárias para garantir que os usuários finais tenham acesso contínuo aos aplicativos e serviços do Adobe. |
| Março de 2021 | [Implantar e gerenciar aterrissagem - Ativo de suporte](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/overview-deploy.html) | Vídeo | Saiba como o Creative Cloud for Enterprise oferece suporte a implantações personalizadas e a atualizações flexíveis de licenças, além de funcionar com outras ofertas de Adobe para enterprise. |
| 5 de março de 2021 | [Personalizar as cores em uma ilustração do Vetor do Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html) | Vídeo | Adicione polidez a qualquer projeto com uma ilustração fantástica. Encontre o vetor perfeito no Adobe Stock e, em seguida, corresponda as cores à paleta do seu projeto usando o Adobe Illustrator. |
| 5 de março de 2021 | [Personalize um modelo de apresentação do Adobe Stock para parecer profissional, mas atraente](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html) | Vídeo | Crie uma bela apresentação estilizada em minutos com imagens e modelos do Adobe Stock e alguns efeitos especiais fáceis de fazer. |
| 5 de março de 2021 | [Personalizar uma animação da tela de carregamento com o Adobe Stock e o XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html) | Vídeo | Personalize arte vetorial do Adobe Stock para criar uma animação de tela de carregamento atraente para um aplicativo móvel. |
| 5 de março de 2021 | [Criar compostos de fotos realistas com imagens do Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html) | Vídeo | Reúna duas fotos excelentes do Adobe Stock para atrair pessoas para suas postagens sociais. |
| 5 de março de 2021 | [Crie quadros de humor inspiradores em breve com o Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html) | Vídeo | Crie um quadro de humor do projeto para retransmitir informações, ideias, visuais e paletas de cores para equipes/clientes. |
| 5 de março de 2021 | [Crie imagens de marca coesivas com lindos gradientes e ativos do Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html) | Vídeo | Traga animação para seus gráficos de informativo com vetores editáveis para o Adobe Stock. |
| 5 de março de 2021 | [Criar animações para email com o Adobe Stock e Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html) | Vídeo | Capacite seus emails com a animação de ação de interrupção com o Adobe Stock e o Photoshop. |
| 5 de março de 2021 | [Crie uma foto interativa de turismo com o Adobe Stock e o XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html) | Vídeo | Crie rapidamente uma foto interativa no protótipo do seu site com o Adobe Stock &amp; XD. |
