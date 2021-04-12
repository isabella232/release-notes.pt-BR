---
title: Notas de versão mais recentes
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação dos produtos e serviços da Experience Cloud. Encontre ajuda e novos tutoriais da Experience Cloud, da Creative Cloud para corporações e da Document Cloud.
doc-type: release notes
last-update: March 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
translation-type: tm+mt
source-git-commit: 0739cde779fe6271e48cdba662eeadadf186944a
workflow-type: tm+mt
source-wordcount: '7942'
ht-degree: 87%

---

# Notas de versão da Adobe Experience Cloud - Março de 2021

![Banner](/assets/experience-cloud-banner-3.png)

As soluções e os serviços da Experience Cloud são atualizados mensalmente. Esta página é o local central para encontrar as últimas atualizações de lançamento, documentação e tutoriais para produtos e serviços da [!DNL Experience Cloud]. Você também pode encontrar nova documentação para a [!DNL Creative Cloud for Enterprise] e a [!DNL Document Cloud].

>[!NOTE]
>
>Assine a [Atualização mensal do produto de prioridade da Adobe](https://www.adobe.com/subscription/priority-product-update.html) para receber notificações por email sobre atualizações nesta página. Esta página é mantida durante todo o mês e pode ter conteúdo que esteja sujeito a alterações antes de uma data de lançamento. Verifique regularmente se há atualizações para o produto empresarial da Adobe e na documentação da Experience League.

Última atualização: **6 de abril de 2021**

* [Digital Experience Blueprints](#blueprints)  (nova documentação de implementação)
* [Status de sistema da Adobe](#status)
* [Componentes, serviços e administração da interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [Analytics](#analytics) **(atualizado em 6 de abril de 2021)** e  [Customer Journey Analytics](#cust-journey)
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

## ![](/assets/adobe.png) ÍconeDigital Experience Blueprints  {#blueprints}

Os Digital Experience Blueprints são implementações repetíveis para solucionar problemas de estratégia e de negócios estabelecidos. Os blueprints aceleram o tempo de implantação e fornecem um caminho rápido para o sucesso.

| Publicado | Descrição |
| -----------| ---------- |
| [Blueprints de experiência digital](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html) | Visão geral de [!UICONTROL Digital Blueprints]. Cada Blueprint oferece uma série de artefatos que explicam o problema comercial de alto valor, arquiteturas, etapas de implementação, considerações técnicas e links para a documentação relevante. |
| [Audience Activation Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/audience-activation/overview.html) | Essa ativação do primeiro público-alvo permite que as marcas conectem as interações do cliente em vários canais para fornecer um público centralizado que pode ser ativado para todos os canais. |
| [Blueprint do Activity Hub do cliente](https://experienceleague.adobe.com/docs/blueprints-learn/architecture//customer-activity-hub/overview.html) | Saiba como os aplicativos externos podem acessar o [!UICONTROL Perfil do cliente em tempo real] da Adobe Experience Platform. |
| [Customer Journey Analytics Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journey-analytics/overview.html) | Saiba como as marcas podem unificar os dados e o comportamento do cliente em vários canais e fontes de interação para criar uma visualização baseada em jornadas de todas as interações do cliente. |
| [Ciência de dados personalizados para o esquema de enriquecimento de perfil](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-science/overview.html) | Saiba como os dados no Adobe Experience Platform são usados pelo [!UICONTROL Data Science Workspace] para treinar, implantar e pontuar modelos para fornecer insights de aprendizado de máquina. |
| [Preparação de dados e plano de assimilação](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-ingestion/overview.html) | Saiba como mapear dados de origem para o esquema [!UICONTROL Experience Data Model] (XDM). Esse blueprint também inclui a execução de transformações nos dados, incluindo formatação de data, divisão de campo, concatenação e conversões, além de unir, mesclar e rechavear registros. |
| [Blueprint de exploração de dados e relatórios da empresa](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-exploration/overview.html) | O [!UICONTROL Serviço de Consulta] do Experience Platform permite que consultas SQL sejam executadas nos dados. Saiba como o [!UICONTROL Data Science Workspace] permite que a exploração de dados, a ciência de dados e as cargas de trabalho de aprendizado de máquina sejam executadas nos dados. |
| [Blueprint do Orquestração de Mensagens de Vários Canais](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/multi-channel-message-orchestration/overview.html) | Saiba como as marcas podem se envolver e se comunicar proativamente com seus clientes por meio de canais como email, SMS e alertas móveis. |
| [Esquema de coleta de dados da empresa do lado do servidor](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/server-side-enterprise-data-collection/overview.html) | Saiba como os dados coletados com os SDKs da Web e móvel do Adobe Experience Platform podem ser encaminhados do Experience Platform [!UICONTROL Edge Network] para um destino desejado. |
| [Blueprint de personalização da Web e móvel](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/web-personalization/overview.html) | Saiba como usar a segmentação de público-alvo em vários aplicativos para personalizar e otimizar as experiências do cliente. Você pode usar comportamentos de clientes, demografia, nível de fidelidade e transações anteriores para personalizar layouts, chamadas para ações e conteúdo. |

## ![Ícone](/assets/adobe.png) Adobe da sistema de Status {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

As atualizações mais recentes do Status do sistema da Adobe são encontradas em [Status do sistema da Adobe - 21 de maio de 2020](https://docs.adobe.com/content/help/pt-BR/release-notes/experience-cloud/previous/2020/05212020.html#status).

## ![Ícone](/assets/ec_appicon_24.png) Componentes, serviços e administração da interface da Experience Cloud {#ecloud}

| Recurso | Descrição |
| -----------| ---------- |
| Pesquisa unificada | A Pesquisa unificada, que está disponível no momento para o Experience Platform, agora oferece suporte à pesquisa em Fontes e Destinos para usuários do Experience Platform. Esse recurso permite pesquisar Segmentos, Conjuntos de dados, Esquemas, Fontes e Destinos. |

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Inclui informações de atualização de versão da Experience Platform e do Experience Platform Launch.

* [Notas de versão da Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR). (Atualizado em 24 de fevereiro de 2021)
* [Notas de versão da Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=pt-BR). (Atualizado em 18 de fevereiro de 2021)

### Tutoriais e cursos da Experience Platform

Novos vídeos, tutoriais ou cursos publicados para a Experience Platform e serviços.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Março de 2021 | [Painel de monitoramento](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/monitoring-dashboard.html?lang=pt-BR) | Vídeo | Saiba como monitorar e rastrear dados que são assimilados na Adobe Experience Platform usando o Painel de monitoramento. Esse painel de monitoramento fornece uma visualização de cima para baixo do processamento de dados de origem por meio de data lake para Perfil e Serviços de identidade nos níveis de execução de fonte e fluxo de dados, com recomendações acionáveis em tempo hábil. |
| Março de 2021 | [Dados de fluxo usando Conectores de origem](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-source-connector.html?lang=pt-BR) | Vídeo | Este vídeo mostra como transmitir dados em tempo real de uma fonte de armazenamento na nuvem para a Platform e usar os dados em tempo real para o envolvimento do cliente. |
| 5 de março de 2021 | [Assimilação de dados para engenheiros de dados](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1.dataingestion?lang=pt-BR) | Curso | Como trazer dados de várias fontes para a Adobe Experience Platform e muito mais. |
| Março de 2021 | [Configurar o destino do Azure Blob](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=pt-BR#destinations) | Vídeo | Saiba como percorrer as etapas necessárias para definir e configurar o destino do Armazenamento de Azure Blob na [!UICONTROL Plataforma de dados do cliente em tempo real] (CDP em tempo real). |
| 5 de março de 2021 | [Introdução ao Offer Decisioning para profissionais de marketing](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning?lang=pt-BR) | Curso | Saiba mais sobre o serviço de aplicativos [!UICONTROL Offer Decisioning] criado com base na Adobe Experience Platform. Este curso foi projetado para profissionais de marketing que desejam gerar receita, experiência do cliente e fidelidade fornecendo as melhores ofertas aos clientes. |
| 5 de março de 2021 | [Assimilação de dados de transmissão por API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-http-api.html?lang=pt-BR) | Vídeo | Este vídeo mostra como transmitir dados para a Adobe Experience Platform em tempo real usando o endpoint da API HTTP. |
| 5 de março de 2021 | [Monitoramento da assimilação de dados usando a API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/data-monitoring.html?lang=pt-BR#data-ingestion) | Vídeo | Saiba como monitorar e rastrear dados que são assimilados na Adobe Experience Platform usando a interface e a API da plataforma. |
| 5 de março de 2021 | [Assimilar dados de bancos de dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-databases.html?lang=pt-BR#sources) | Vídeo | Este vídeo mostra como assimilar dados em lote de uma fonte de banco de dados no Perfil do cliente em tempo real da Adobe Experience Platform e no Experience Data Lake, de maneira contínua e escalável. |
| 5 de março de 2021 | [Assimilar dados do Amazon S3](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-amazon-s3.html?lang=pt-BR) | Vídeo | Este vídeo mostra como assimilar facilmente dados em lote de serviços de armazenamento na nuvem no Perfil do cliente em tempo real da Adobe Experience Platform e no data lake, de forma contínua e escalável. |
| 5 de março de 2021 | [Assimilar dados do Salesforce CRM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html?lang=pt-BR) | Vídeo | Este vídeo mostra como assimilar facilmente dados em lote de fontes de CRM no Perfil do cliente em tempo real da Adobe Experience Platform e no data lake, de forma contínua e escalável. |
| 5 de março de 2021 | [Assimilar dados do Adobe Analytics](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html?lang=pt-BR) | Vídeo | O conector de origem do Adobe Analytics permite assimilar dados em lote facilmente do Adobe Analytics no Perfil do cliente em tempo real da Adobe Experience Platform e do Experience Data Lake, de forma contínua e escalável. |
| 5 de março de 2021 | [Noções básicas sobre conectores de origem](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/overview.html?lang=pt-BR#sources) | Vídeo | Este vídeo fornece uma visão geral de origens, ou conectores de origem, na Experience Platform. |
| 5 de março de 2021 | [Detalhes do postman de exportação do console do Adobe IO](https://experienceleague.adobe.com/docs/platform-learn/tutorials/apis/postman.html?lang=pt-BR) | Vídeo | Saiba como autenticar e acessar APIs da Experience Platform. |
| 5 de março de 2021 | [Noções básicas sobre assimilação de dados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/understanding-data-ingestion.html?lang=pt-BR#data-ingestion) | Vídeo | Saiba mais sobre os recursos de assimilação de dados da Experience Platform que permitem reunir os dados em uma plataforma aberta e escalável para gerenciar perfis de clientes em tempo real. |

## ![Ícone](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use a Adobe Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Últimas versões de produtos

Versões de fevereiro de 2021 - Saiba mais sobre os recursos, melhorias e correções mais recentes nas [Notas de versão do Journey Orchestration](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html).

### Novos cursos e tutoriais do Journey Orchestration

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 16 de março de 2021 | [Atualizar ação do perfil](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=pt-BR#building-a-journey) | Vídeo | Saiba como atualizar um perfil da Experience Platform existente com informações provenientes de um evento, de uma fonte de dados ou usando um valor específico. |

### Recursos adicionais do Journey Orchestration

[Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Ícone](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL O Offer Decisioning] é um serviço de aplicativos integrado à Adobe Experience Platform. Use o [!UICONTROL Offer Decisioning] para fornecer a melhor oferta e experiência aos seus clientes em todos os pontos de contato na hora certa.

### Últimas versões de produtos

Versão de fevereiro de 2021 - Saiba mais sobre os recursos mais recentes nas [Notas de versão do Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=pt-BR#new).

### Mais recursos para o Offer Decisioning

[Documentação](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=pt-BR) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=pt-BR)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **25 de março de 2021**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)  **(atualizado em 6 de abril de 2021)**
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| ----------- | ---------- | ------- |
| Atualizações da API de reparo de dados | 25 de março de 2021 | A API de reparo de dados agora suporta variáveis padrão, incluindo [!UICONTROL Page] e [!UICONTROL Endereço IP], variáveis móveis e de vídeo, bem como [!UICONTROL props] e [!UICONTROL eVars] personalizadas.  Os valores em variáveis podem ser excluídos ou novos valores podem ser definidos. A API agora também oferece filtragem de URLs, sequências de consulta, sinais e muito mais. |
| Analysis Workspace: [!UICONTROL Componentes] > [!UICONTROL Preferências do usuário] | 25 de março de 2021 | A página [!UICONTROL Componentes] > [!UICONTROL Preferências do usuário] permite gerenciar as configurações do [!UICONTROL Analysis Workspace] e seus componentes relacionados para o seu usuário. [!UICONTROL As preferências do usuário] se aplicam a todos os novos projetos e painéis. <br>**Observação:** as configurações a seguir foram movidas para a página [!UICONTROL Preferências do usuário]:<ul><li>Configurações do relatório: Separador de milhares (agora chamado de _Formato de número_)</li><li>Configurações do relatório: separador CSV</li><li>Projetos do Workspace: Ajuda > Ativar dicas</li><li>Projetos do Workspace: Painel em branco _Iniciar novos projetos com esta opção de painel_</li></ul> |
| Analysis Workspace: [!UICONTROL Previsão do bucket inteligente do histograma] | 25 de março de 2021 | [!UICONTROL A Previsão do bucket inteligente do histograma] ajuda com histogramas de métricas de alta cardinalidade, identificando automaticamente a largura e o número corretos de intervalos para a disseminação de seus dados. Para métricas de baixa cardinalidade, a visualização se comporta da mesma forma que antes. |
| [!UICONTROL Log de uso] API | 25 de março de 2021 | Esta é uma nova API v2.0 do Analytics que permite acesso programático aos mesmos dados de registro de uso disponíveis em **[!UICONTROL Admin]** > **[!UICONTROL Log]** > **[!UICONTROL Log de uso e acesso]**. Detalhes adicionais sobre autenticação, esquema e resposta de amostra estão disponíveis [aqui](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md). |
| Suporte a painéis do Analytics para intervalos de datas personalizados | 22 de abril de 2021 | Os criadores do cartão de pontuação podem criar e aplicar intervalos de datas personalizados a projetos do cartão de pontuação móvel. Os criadores podem escolher um espaço de trabalho familiar e predefinições de intervalo de datas para dispositivos móveis ou criar um intervalo de datas personalizado. [Saiba mais](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/curator.html#mobapp). |

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Data do Target | Descrição |
| ----------- | ---------- | ----- |
| Suporte para [!UICONTROL painéis do Adobe Analytics] | 25 de março de 2021 | [!UICONTROL O Customer Journey Analytics] (CJA) agora é compatível com o [!UICONTROL Construtor de cartão de pontuação de painéis do Adobe Analytics] e com o aplicativo móvel. Isso permite que executivos e usuários empresariais vejam seus KPIs entre canais com base em dados do CJA, usando o mesmo aplicativo que já podem estar usando para o Adobe Analytics. |
| Analysis Workspace: **[!UICONTROL Componentes]** > **[!UICONTROL Preferências do usuário]** | 25 de março de 2021 | A página [!UICONTROL Componentes] > [!UICONTROL Preferências do usuário] permite gerenciar as configurações do [!UICONTROL Analysis Workspace] e seus componentes relacionados para o seu usuário. [!UICONTROL As preferências do usuário] se aplicam a todos os novos projetos e painéis. <br>**Observação:** as configurações a seguir foram movidas para a página [!UICONTROL Preferências do usuário]:<ul><li>Projetos do Workspace: Ajuda > Ativar dicas</li><li>Projetos do Workspace: Painel em branco _Iniciar novos projetos com esta opção de painel_</li></ul> |
| Analysis Workspace: [!UICONTROL Previsão do bucket inteligente do histograma] | 25 de março de 2021 | [!UICONTROL A Previsão do bucket inteligente do histograma] ajuda com histogramas de métricas de alta cardinalidade, identificando automaticamente a largura e o número corretos de intervalos para a disseminação de seus dados. Para métricas de baixa cardinalidade, a visualização se comporta da mesma forma que antes. |
| Suporte a painéis do Analytics para o Customer Journey Analytics | 25 de março de 2021 | O aplicativo de painéis do Analytics agora é compatível com o Customer Journey Analytics. Os usuários com o Customer Journey Analytics podem exibir KPIs de qualquer dado assimilado na Adobe Experience Platform no aplicativo de painéis do Analytics. O Customer Journey Analytics permite combinar várias fontes de dados para obter uma visualização verdadeira e de vários canais da experiência do cliente. Agora, com o aplicativo de painéis do Analytics, você pode obter uma visualização integral e atualizada dos seus negócios, a qualquer hora e em qualquer lugar. [Saiba mais](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/curator.html?lang=en#cja-dashboards). |

### Correções no Adobe Analytics {#aa-fixes}

* Correção de um problema em que, após editar e salvar o novo proprietário de um segmento, esse novo proprietário não era refletido na interface do segmento. (AN-234502; AN-250970; AN-250286)
* Correção de um problema que fazia com que um conjunto de relatórios do aplicativo consumisse chamadas do servidor principal e chamadas do servidor principal móvel. (AN-244029)
* Correção de um problema com o tempo de resposta lento da interface do usuário ao abrir projetos do [!UICONTROL Workspace]. (AN-242553)
* Correção de um problema que impedia o logon no [!UICONTROL Report Builder] após a atualização para a versão mais recente. (AN-248825)
* Correção de um problema com permissões de usuário para usuários não administradores: o usuário deve ter uma permissão, desde que seja adicionado a pelo menos um de seus perfis no [!UICONTROL Admin Console]. A adição de usuários a perfis deve apenas aumentar as permissões que eles têm e não deve remover nada a que já tenham direito por meio de outros perfis de produto. (AN-242723)
* Correção de um problema de codificação de idioma com [!UICONTROL Feeds de dados]. (AN-249862)
* Correção de um problema em que os usuários não conseguiam acessar projetos compartilhados do [!UICONTROL Workspace]. (AN-247814)
* Correção de um problema em que as [!UICONTROL Visualizações de alerta] não correspondiam ao número de [!UICONTROL Alertas] disparados. (AN-249392; AN-250804)

#### Outras correções do Adobe Analytics

AN-206099; AN-237460; AN-241803; AN-243735; AN-244081; AN-244615; AN-244687; AN-246832; AN-247227; AN-248237; AN-248478; AN-248852; AN-249115; AN-249140; AN-249216; AN-249275; AN-249538; AN-249963; AN-250034; AN-250270; AN-250320; AN-250338; AN-250377; AN-250378; AN-250557; AN-250609; AN-250614; AN-250615; AN-250885; AN-251088; AN-251137; AN-251190; AN-251192; AN-251193; AN-251301; AN-251496; AN-251545; AN-251734; AN-251735; AN-251744; AN-251816; AN-251982; AN-251972; AN-252051; AN-252073; AN-252105; AN-252409; AN-252640

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| ----------- | ---------- | ---------- |
| Fim da vida útil das [!UICONTROL Fontes de dados de] [!UICONTROL Processamento completo] | 12 de abril de 2021, 2021 | O Adobe planeja descontinuar o [!UICONTROL Processamento completo] [!UICONTROL Fontes de dados] em 31 de julho de 2021. A partir de 25 de março de 2021, novas importações desse tipo não poderão mais ser criadas. Use a [API de inserção de dados em massa](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) para importar esse tipo de dados. [Saiba mais](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=pt-BR) |
| Atualização de logon para [!UICONTROL Report Builder] | 9 de abril de 2021 | Em 14 de janeiro de 2021, o logon [!UICONTROL Report Builder] removia as dependências das tecnologias herdadas e alinhava o processo de logon com o Experience Cloud. O Experience Cloud usa seu Enterprise ID (email e senha). Para garantir acesso ininterrupto a [!UICONTROL Report Builder], atualize o complemento [!UICONTROL Report Builder] para a versão 5.6.47 ou posterior até 22 de julho de 2021. O Report Builder versão 5.6.47 e posterior oferecerá suporte somente ao Experience Cloud sign-in e não oferecerá suporte ao logon único. |
| Feed de dados e Data Warehouse alterações de endereço IP | 6 de abril de 2021 | A partir de 17 de junho, os Feeds de dados e o sistema de entrega do Data Warehouse serão realocados em nossos data centers e, portanto, podem causar uma mudança de endereços IP externos visíveis a você.  Você deve confirmar que todos os blocos CIDR de IP para o data center em que seus relatórios e feeds são provenientes estão presentes em qualquer firewalls, para quaisquer sistemas de destino sob seu controle. [Esta é uma lista completa de intervalos de endereço IP a serem colocados nas listas de permissões](https://https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html#data-collection-and-ftp-ip-address-blocks) do firewall. |
| Aviso de alterações futuras no menu do Analytics | 24 de março de 2021 | Em 22 de abril de 2021, atualizaremos os menus suspensos **[!UICONTROL Components]**, **[!UICONTROL Tools]** e **[!UICONTROL Admin]** para obter alguns ganhos de desempenho. Todas essas páginas ainda estarão disponíveis nos links **[!UICONTROL Todos os componentes]**, **[!UICONTROL Todas as ferramentas]** e **[!UICONTROL Todos os administradores]** - simplesmente serão removidas do menu suspenso. Aqui estão os itens de menu que serão removidos do menu suspenso e colocados em sua respectiva página de link:<br><br> [!UICONTROL Componentes]<ul><li>[!UICONTROL Marcadores]</li><li>[!UICONTROL Painéis]</li><li>[!UICONTROL Metas]</li><li>[!UICONTROL Eventos de calendário]</li><li>[!UICONTROL Relatórios agendados]</li><li>[!UICONTROL Configurações do relatório]</li></ul>Ferramentas de <ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL Gerenciamento de usuários]</li><li>[!UICONTROL Classificação do importador]</li><li>[!UICONTROL Criador de regras de classificação]</li><li>[!UICONTROL Fontes de dados]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Configurações da empresa]</li><li>[!UICONTROL Logs]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Gerenciador de código]</li><li>[!UICONTROL Excluir por IP]</li><li>[!UICONTROL Gerenciamento de tráfego]</li></ul> |
| [!UICONTROL Processamento VISTA Same-as-SiteCatalyst] = ATIVADO | 17 de março de 2021 | Em 17 de junho de 2021, todos os conjuntos de relatórios serão atualizados para terem o [!UICONTROL Processamento VISTA Same-as-SiteCatalyst] definido como ATIVADO. Essa alteração afeta os relatórios do [!UICONTROL Data Warehouse] processando os dados para corresponder às regras de processamento. Para dúvidas ou esclarecimentos, entre em contato com o Atendimento ao cliente da Adobe. |
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
* Correção de um problema que impedia alguns usuários de acessar **[!UICONTROL Relatórios de público]**. (AAM-57412)
* Correção de uma vulnerabilidade na [!UICONTROL Execução de código remoto] que poderia ser usada por invasores para acessar dados confidenciais. (AAM-57495)

### Cursos e tutoriais do Audience Manager {#tutorials-aam}

Novos vídeos, tutoriais ou cursos publicados para o Audience Manager.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 19 de março de 2021 | [Compreensão da governança de dados na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-data-gov-for-aam-users.html?lang=pt-BR) | Vídeo | Saiba mais sobre a funcionalidade de governança de dados em [!UICONTROL Plataforma de dados do cliente em tempo real]. |
| 19 de março de 2021 | [Os dois lados da moeda - marcas e consumidores](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/brands-vs-consumers.html?lang=pt-BR) | Vídeo | Neste webinário, a Adobe revela o nível de compreensão e disponibilidade de anunciantes e editores para um futuro sem cookies, o impacto em seus casos de uso e a percepção que eles têm do ecossistema mais amplo. |
| 5 de março de 2021 | [10 considerações para o gerenciamento responsável de dados do cliente](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/ten-considerations-for-responsible-customer-data-management.html?lang=pt-BR) | Evento | Ouça o que a Adobe e o Scotiabank Digital têm a dizer sobre as principais considerações para um gerenciamento responsável de dados. |
| 19 de março de 2021 | [O futuro do gerenciamento de dados e do ambiente em mudança](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/the-future-of-data-management-and-the-changing-environment.html?lang=pt-BR) | Evento | Neste webinário, veja como a Adobe e a 451 Research estão pensando sobre o futuro da tecnologia e dos dados para abordar o novo ambiente de marketing e começar a preparar seus negócios para o futuro do gerenciamento de dados. |
| 21 de março de 2021 | [Noções básicas sobre esquemas e XDM na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=pt-BR#other-integrations) | Vídeo | Ao migrar do Audience Manager para a Plataforma de dados do cliente em tempo real (CDP em tempo real), você encontrará alguns novos conceitos e práticas. Os esquemas e o XDM se encaixam nessa categoria. Este vídeo explica esses conceitos. |
| 17 de março de 2021 | [Compreensão de sinais na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html?lang=pt-BR) | Vídeo | Este vídeo destina-se aos usuários do Audience Manager que estão migrando para a Plataforma de dados do cliente em tempo real (CDP em tempo real) e discute como os sinais (pares de valores chave) usados no Audience Manager para criar características são usados na plataforma. |
| 12 de março de 2021 | [Noções básicas sobre esquemas e XDM na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=pt-BR) | Vídeo | Ao migrar do Audience Manager para a Plataforma de dados do cliente em tempo real (CDP em tempo real), você encontrará alguns novos conceitos e práticas. Os esquemas e o XDM se encaixam nessa categoria. Este vídeo explica esses conceitos. |
| 12 de março de 2021 | [Noções básicas da assimilação de dados da Web na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-web-ingestion-for-aam-users.html?lang=pt-BR) | Vídeo | Saiba mais sobre os conceitos de como trazer dados do site para a Plataforma de dados do cliente em tempo real (CDP em tempo real), incluindo um comentário de alto nível sobre onde os Conectores de dados do Audience Manager se encaixam, além de como os dados podem se mover do site diretamente pelo SDK da Web para a CDP em tempo real. |
| 3 de março de 2021 | [Noções básicas de segmentos na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=pt-BR#other-integrations) | Vídeo | Saiba mais sobre as diferenças nos segmentos e na criação de segmentos entre o Audience Manager e a CDP em tempo real. |
| 3 de março de 2021 | [Noções básicas de características na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=pt-BR#other-integrations) | Vídeo | Conheça as características no Audience Manager e o equivalente na CDP em tempo real. |
| 3 de março de 2021 | [Noções básicas da assimilação de dados primários na CDP em tempo real para usuários do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=pt-BR#other-integrations) | Vídeo | Saiba mais sobre a assimilação de dados offline primários na Plataforma de dados do cliente em tempo real (CDP em tempo real). Conheça algumas das principais diferenças entre os dois produtos em relação à assimilação de dados e como o Conector de dados do Audience Manager pode ser usado como uma solução temporária até que os processos tenham sido transferidos para a CDP em tempo real. |
| 1 de março de 2021 | [Comercializar seus próprios públicos oferecendo no Audience Marketplace](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=pt-BR#audience-marketplace) | Vídeo | Saiba como configurar seus dados como um feed de dados privado ou público no Audience Marketplace, tornando-o um provedor de dados de terceiros. |
| Março de 2021 | [Criação e gerenciamento de ativação de dados no Audience Manager](https://experienceleague.adobe.com/?lang=pt-BR&amp;recommended=AudienceManager-U-1-2020.4) | Curso | Neste curso, aprenda como ativar seus públicos-alvo, por exemplo, enviar dados de público a parceiros de destino para personalizar a experiência dos usuários finais. Aprenda o básico sobre destinos, como escolher o destino certo e como preparar e enviar dados de público-alvo para destinos de redes sociais com base em pessoas, não em cookies. |
| Março de 2021 | [Habilidades avançadas no Audience Manager](https://experienceleague.adobe.com/?lang=pt-BR&amp;recommended=AudienceManager-U-1-2020.5) | Curso | Depois de dominar as noções básicas do Audience Manager, faça este curso para saber como elevar o nível do gerenciamento de público-alvo. Saiba como usar a IA com modelos algorítmicos, como usar as Regras de mesclagem de perfis para entender seus clientes como pessoas em vez de dispositivos e outros tópicos excelentes para estender o uso do DMP. |

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
O AEM 6.4, Service Pack 8, Cumulative Fix Pack 4 (6.4.8.4 lançado em 25 de fevereiro de 2021) é uma atualização importante que inclui várias correções internas e do cliente desde a disponibilidade geral do AEM 6.4, Service Pack 8 (6.4.8.0), em março de 2020.
   * [Notas de versão](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=pt-BR)
   * [Resultados da versão do AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager as a Cloud Service**

   Quais são as novidades do Experience Manager as a Cloud Service?

   * **Experience Manager Sites as Cloud Service**

      * [O componente RemotePage](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=pt-BR): adição de suporte para exibição e edição de SPAs externos no Experience Manager.
      * [Edição de um SPA externo no Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=pt-BR): adição da capacidade de fazer upload de um aplicativo independente de página única em uma instância do Experience Manager, adicionar seções editáveis de conteúdo e ativar a criação.
   * **Experience Manager Assets as a Cloud Service**

      * Assets do Experience Manager as a Cloud Service estão qualificados para ter uma instância pré-configurada do Brand Portal. O usuário do Cloud Manager pode ativar o Brand Portal em Assets do Experience Manager as a Cloud Service. Consulte [Ativar o Brand Portal usando o Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html?lang=pt-BR).
      * Agora, as empresas podem adquirir assets usando o Brand Portal. O recurso de fornecimento de ativo usa o Brand Portal para ajudar os clientes a se envolver com usuários de agências a fim de obter assets para novas campanhas de marketing, sessões de fotos e projetos. Consulte [Visão geral da origem do ativo](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=pt-BR) no Manual do AEM Brand Portal.
      * O relatório de uso do AEM Brand Portal agora exibe somente os usuários ativos. Os usuários inativos não são exibidos agora. Usuários ativos são aqueles cujas contas estão atribuídas a um perfil de produto no Admin Console. Consulte [Trabalhar com relatórios](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=pt-BR) no Manual do Brand Portal.
      * No AEM Brand Portal, é introduzida uma nova configuração de download que permite criar uma pasta separada para cada ativo ao baixar pastas, coleções e assim por diante. Consulte [Download de ativo](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=pt-BR) em **Baixar assets do AEM Brand Portal** no Manual do AEM Brand Portal.
   * **Experience Manager Forms as a Cloud Service**

      A AEM Forms tem ajudado muitas organizações a oferecer excelentes experiências de integração e inscrição ao longo dos anos. Essas experiências têm ajudado organizações a converter leads em vendas, processar dados capturados do cliente, fornecer experiências responsivas com base no perfil do público-alvo e muito mais. Agora, o AEM Forms está disponível como um serviço na nuvem.

      Você pode usar o AEM Forms como um serviço na nuvem para criar formulários digitais, conectar formulários a fontes de dados existentes, integrar formulários com o Adobe Sign para adicionar assinaturas eletrônicas a formulários e gerar Documento de registro (DoR) para arquivar formulários enviados como arquivos PDF. O serviço também pode converter PDF forms existentes em formulários digitais. Além dos recursos padrão do AEM Forms, o serviço oferece vários recursos nativos na nuvem, como dimensionamento automático, tempo de inatividade zero para atualizações e ambiente de desenvolvimento nativo na nuvem. Leia [esta publicação do blog do blog](https://blog.adobe.com/en/publish/2021/03/11/experience-manager-forms-as-a-cloud-service.html) para conhecer os recursos do AEM Forms como um serviço na nuvem.

      Entre em contato com o representante da Adobe para obter uma demonstração ou para cadastrar-se no serviço.


   * **Experience Manager Commerce as a Cloud Service**

      * Gerenciamento de experiência do produto: enriqueça as páginas do catálogo de produtos individualmente com Fragmentos de experiência.
      * Propriedades do console do produto estendido para mostrar Assets vinculados e Fragmentos de experiência, incluindo ações para navegar rapidamente até o conteúdo associado.
      * Lançamento do site de referência CIF Venia em 24/02/2021 que inclui a versão mais recente dos componentes principais CIF 1.8.0. Consulte o [Site de referência CIF Venia de 24/02/2021](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24) para obter mais detalhes.
      * Lançamento de componentes principais CIF versão 1.8.0. Consulte [Componentes principais CIF 1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0) para obter mais detalhes.
   * **Cloud Manager**

      * Os clientes com ambientes que têm configurações pré-existentes de Nome de domínio personalizado para [Listas de permissões de IP](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=pt-BR#pre-existing-cdn), [Certificados SSL](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=pt-BR#pre-existing-cdn) e [Nomes de domínio personalizados](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=pt-BR#pre-existing-cdn) agora veem uma mensagem sobre suas configurações existentes anteriormente. Eles também podem usar o autoatendimento na interface do usuário.
      * Os usuários com as permissões necessárias agora podem editar um programa, permitindo que façam o seguinte no autoatendimento:
         * Adicionar a solução Sites a um programa existente com Assets ou vice-versa.
         * Remover Sites ou Assets de um programa existente com Sites e Assets.
         * Adicionar o segundo direito de solução não utilizado a um programa existente ou como um novo programa.
      * **O rótulo Atualização por push do AEM** agora é exibido nas telas *Execução de pipeline* e *Atividade*.
      * Se um ambiente estiver hibernando, mas também houver uma atualização do Experience Manager disponível, o status **Hibernando** terá prioridade sobre **Atualização disponível**.
      * Agora os usuários podem ver suas funções do Cloud Manager selecionando **Exibir funções do Cloud Manager** depois de navegar até o ícone Perfil do usuário (canto superior direito) do Unified Shell.
      * O rótulo **Pedido de aprovação** foi renomeado para **Aprovação de produção** para oferecer mais clareza.
      * O rótulo **versão** foi renomeado para **Tag Git** na tela de execução do pipeline de Produção.
      * Os rótulos que definem o comportamento quando métricas importantes não atingirem o limite definido foram renomeados para refletir seu comportamento verdadeiro: **Cancelar Imediatamente** e **Aprovar Imediatamente**.
      * As listas de descontinuação de classe e método foram atualizadas com base na versão `2021.3.4997.20210303T022849Z-210225` do SDK do Experience Manager Cloud Service.
      * O pipeline de produção do Cloud Manager agora inclui o recurso [Teste de interface personalizada](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=pt-BR#custom-ui-testing).




### **Comunidade**

* **Desenvolvedores Adobe Live 2021 | Lista completa de sessões**

   [Aqui](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875) está uma lista agregada de todas as sessões do Experience Manager que ocorrem no **Adobe Developers Live**.

* **Adobe Summit 2021 | Lista completa de sessões do Experience Manager**

   [Aqui](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344) está uma lista agregada de todas as sessões do Experience Manager que ocorrerão no **Adobe Summit 2021**.

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Atualizações de versão e roteiro do Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-release-information/aem-release-updates/home.html)
* [Informações sobre a versão do Experience Manager as a Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/release-notes/home.html)
* [Notas de versão do Experience Manager Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://docs.adobe.com/content/help/pt-BR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Notas de versão do Cumulative Fix Pack do Experience Manager 6.4](https://docs.adobe.com/content/help/pt-BR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notas de versão do Experience ManagerAssets Dynamic Media](https://docs.adobe.com/content/help/pt-BR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de versão do Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=pt-BR)
* [Notas de versão do aplicativo para desktop Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-desktop-app/using/release-notes.html)
* [Notas de versão do Experience Manager Dispatcher](https://docs.adobe.com/content/help/pt-BR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

### Cursos e tutoriais do Experience Manager

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Março de 2021 | [Entrega de conteúdo no Experience Manager Cloud Service](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html?lang=pt-BR#content) | Evento | O Adobe Experience Manager as a Cloud Service tem uma eficiente arquitetura de entrega de conteúdo pré-configurada. Demonstrar como tirar o melhor proveito das configurações otimizadas de entrega de conteúdo |
| Março de 2021 | [Migrar artigo de ajuda sobre tipos de Formulários e Documentos para ExL](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/pdf-forms-and-documents.html?lang=pt-BR#document-services) | Artigo | Um artigo explicando os diferentes tipos de PDF forms e documentos. |
| Março de 2021 | [Implantação de produção com um ambiente de publicação do AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html?lang=pt-BR#graphql) | Tutorial | Configure um ambiente local para simular o conteúdo que está sendo distribuído de uma instância de Autor para uma instância de Publicação. Gere um build de produção de um aplicativo React configurado para consumir conteúdo do ambiente de publicação do AEM usando as APIs GraphQL. Ao longo do caminho, você aprenderá a usar variáveis de ambiente de maneira eficaz e a atualizar as configurações AEM CORS. |
| Março de 2021 | [Gerenciamento de conteúdo headless usando APIs GraphQL](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless?lang=pt-BR) | Curso | Explore como as APIs GraphQL do AEM e os recursos headless podem ser usados para potencializar as experiências encontradas em um aplicativo externo. |
| Março de 2021 | [Lançamentos - Vídeo de recurso](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html?lang=pt-BR) | Vídeo | Os lançamentos no AEM Sites fornecem uma maneira de criar e revisar o conteúdo do site para uma versão futura. Durante a criação do lançamento, o site de produção pode continuar evoluindo e mudando a cada dia, como aconteceria normalmente. |
| Março de 2021 | [Ativos relacionados e não relacionados - Videoktext de recurso](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html?lang=pt-BR) | Vídeo | Saiba como estabelecer e gerenciar relações entre assets no AEM. |
| Março de 2021 | [Autenticação para o AEM as a Cloud Service de um aplicativo externo](https://experienceleague.adobe.com/?lang=pt-BR&amp;recommended=ExperienceManager-D-1-2020.1.aemcs) | Curso | Saiba como um aplicativo externo pode usar Tokens de acesso de desenvolvimento local e Credenciais de serviço para realizar a autenticação programaticamente no AEM como serviço em nuvem por HTTP. |
| Março de 2021 | [Preencha e assine vários formulários em uma solicitação de hipoteca](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms&amp;lang=pt-BR) | Curso | Assine um pacote de documentos sem problemas usando a integração do AEM Forms e do Sign. Os dados inseridos no formulário podem ser usados para preencher previamente os próximos formulários no pacote. |
| Março de 2021 | [Controle de versão/Timewarp no AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html?lang=pt-BR) | Vídeo | O Timewarp é um recurso do Adobe Experience Manager Sites que fornece aos autores uma maneira rápida de consultar o estado de uma página em um momento específico no passado. |
| Março de 2021 | [Foundation - Gerenciamento de fluxo de trabalho](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=pt-BR#workflow) | Vídeo | Este vídeo usa Modelos de fluxo de trabalho para demonstrar esse conjunto de recursos. No entanto, eles também se aplicam a Iniciadores do AEM. |
| Março de 2021 | [Blocos de fragmento de experiência](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html?lang=pt-BR) | Vídeo | Os blocos são um sub-recurso dos Fragmentos de experiência. Os blocos permitem que os autores de conteúdo reutilizem componentes em diferentes variações de Fragmentos de experiência. |
| Março de 2021 | [Editor de fluxo de trabalho](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=pt-BR#workflow) | Vídeo | O fluxo de trabalho permite o gerenciamento de processo empresarial no Experience Manager e é usado para o processamento automático de conteúdo, além de facilitar a governança e os processos que exigem tomada de decisão humana. |
| Março de 2021 | [Grupos de usuários fechados no AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html?lang=pt-BR) | Vídeo | Grupos de usuários fechados (CUGs) é um recurso usado para restringir o acesso ao conteúdo a um grupo selecionado de usuários em um site publicado. Este vídeo mostra como Grupos de usuários fechados podem ser usados com o Adobe Experience Manager Assets para restringir o acesso a uma pasta específica de ativos. |
| Março de 2021 | [Relatórios ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html?lang=pt-BR) | Vídeo | Saiba como o AEM Assets fornece uma estrutura de relatórios de nível empresarial que pode ser dimensionada para repositórios grandes por meio de uma experiência do usuário intuitiva. |
| Março de 2021 | [Tags inteligentes para imagens com o AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html?lang=pt-BR) | Vídeo | As tags inteligentes para imagens aumentam os recursos de pesquisa do AEM adicionando marcas de metadados de forma automática e inteligente aos ativos de imagem com base no conteúdo da imagem. |
| Março de 2021 | [Metadados em cascata, visibilidade](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html?lang=pt-BR) | Vídeo | Saiba mais sobre as novas regras dinâmicas para requisitos de campo, visibilidade e opções contextuais. O vídeo também detalha as etapas necessárias para um administrador aplicar essas regras a um esquema de metadados personalizado. |
| Março de 2021 | [Projetos principais](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=pt-BR#delete-project-masters) | Vídeo | A exclusão de um projeto principal resulta em projetos derivados inutilizáveis. |
| Março de 2021 | [Personalização das propriedades da página](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html?lang=pt-BR) | Vídeo | Crie um vídeo técnico sobre como estender e personalizar melhor as Propriedades da página. |
| Março de 2021 | [Tradução de fragmentos de conteúdo](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html?lang=pt-BR) | Vídeo | Saiba como os Fragmentos de conteúdo podem ser localizados e traduzidos com o Adobe Experience Manager. Os ativos de mídia mista associados a um Fragmento de conteúdo também podem ser extraídos e traduzidos. |
| Março de 2021 | [Fragmentos de experiência](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html?lang=pt-BR) | Vídeo | Saiba como os Fragmentos de experiência permitem que os autores de conteúdo reutilizem conteúdo em canais, incluindo páginas de sites e sistemas de terceiros. |
| Março de 2021 | [Aumento de pesquisa aprimorada](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html?lang=pt-BR) | Vídeo | Saiba mais sobre o Aumento de pesquisa. |

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

Saiba mais sobre recursos, melhorias e correções mais recentes lançados:

* [Notas de versão do Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html)
* [Notas de versão do Campaign Classic](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html).

>[!IMPORTANT]
>
>Saiba mais sobre [as atualizações de configuração necessárias](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/acc-config-updates.html?lang=pt-BR) para o Adobe Campaign Classic.

### Novos cursos e tutoriais do Campaign

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Solução | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Métricas para capacidade de entrega](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html?lang=pt-BR) | Campaign Classic/Standard | Entenda quais métricas principais de entrega você deve monitorar e como usá-las para identificar um problema de reputação. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Rejeições](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba mais sobre os diferentes tipos de rejeições. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Reclamações](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba mais sobre as reclamações que são registradas quando um usuário indica que um email é indesejado ou inesperado. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Armadilhas de spam](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba mais sobre os diferentes tipos de rejeições. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Marcação e bloqueio](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba por que os ISPs colocam mensagens de email em pastas de spam ou as bloqueiam. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Processo de transição - Infraestrutura](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba o que é necessário para construir corretamente uma infraestrutura de email. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Envolvimento](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba mais sobre os diferentes tipos de envolvimento e por que o envolvimento é importante para a capacidade de entrega. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Processo de transição: Critérios de direcionamento](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba como estabelecer uma reputação positiva desde o início para criar confiança com eficiência antes de alcançar seus públicos menos envolvidos. |
| 23 de fevereiro de 2021 | [Capacidade de entrega - Processo de transição - Considerações específicas do ISP durante o aquecimento de IP](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba mais sobre as diferentes regras e maneiras pelas quais os provedores de ISP podm observar o tráfego |
| 24 de fevereiro de 2021 | [Capacidade de entrega - Primeiras impressões - introdução](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba como você pode se preparar para executar um programa de email de sucesso, causando uma boa primeira impressão nessas áreas. |
| 24 de fevereiro de 2021 | [Capacidade de entrega - Processo de transição: Volume](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html?lang=pt-BR) | Campaign Classic/Padrão | Entenda como o volume de envio influencia a capacidade de entrega de suas campanhas de email. |
| 24 de fevereiro de 2021 | [Capacidade de entrega - Primeiras impressões - Coleção de endereços e crescimento de listas](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba quais são as melhores fontes para novos endereços de email, como garantir alta qualidade dos dados e alinhamento às diretrizes legais. |
| 25 de fevereiro de 2021 | [Capacidade de entrega - Primeiras impressões - Email de boas-vindas](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba quais devem ser os principais elementos da sua estratégia de boas-vindas. |
| 25 de fevereiro de 2021 | [Capacidade de entrega - Processo de transição: Mudança de plataformas de email](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html?lang=pt-BR) | Campaign Classic/Padrão | Como fazer a transição descomplicada ao trocar de plataforma de email. |
| 26 de fevereiro de 2021 | [Capacidade de entrega - Práticas recomendadas de conteúdo para a entrega ideal](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html?lang=pt-BR) | Campaign Classic/Padrão | Dicas para otimizar o conteúdo do seu email para entrega. |
| 26 de fevereiro de 2021 | [Capacidade de entrega - Permanência do remetente](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba por que é importante estabelecer um volume de envio consistente. |
| 26 de fevereiro de 2021 | [Capacidade de entrega - Monitoramento contínuo](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html?lang=pt-BR) | Campaign Classic/Padrão | Saiba quais problemas você precisa procurar ao monitorar as entregas. |
| 26 de fevereiro de 2021 | [Capacidade de entrega - Colocando em prática](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html?lang=pt-BR) | Campaign Classic/Padrão | Quatro pilares-chave para o sucesso. |
| 10 de março de 2021 | [Práticas recomendadas de capacidade de entrega para líderes, usuários empresariais e administradores](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability?lang=pt-BR) | Campaign Classic | Conheça os principais termos, conceitos e abordagens de entrega para garantir o sucesso do seu programa de marketing. |

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

Última atualização: **29 de março de 2022, para a versão de 27 de março**

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanhas de pesquisa]<br> Relatórios | (Campanhas do Microsoft Ads) O suporte de lance está disponível para a estratégia de lance de custo por clique (eCPC) aprimorada da Microsoft, que é a estratégia de lance padrão para campanhas do Microsoft Advertising. Agora você pode especificar uma [!UICONTROL Estratégia de lance] no nível da campanha para suas campanhas. As opções incluem [!UICONTROL CPC Manual] e [!UICONTROL CPC Avançado]. Você pode usar [!UICONTROL CPC aprimorado] com campanhas de pesquisa, publicidade de pesquisa dinâmica existente e de compras.<br>Quando você adiciona uma campanha com eCPC a um portfólio otimizado do Advertising Cloud, o Advertising Cloud otimiza as ofertas básicas e, quando a opção &quot;Ajustar automaticamente os limites de orçamento da campanha&quot; está ativada, o orçamento da campanha. A Microsoft aplica todos os ajustes de lances e pode alterar os lances gerados pela Advertising Cloud no momento da consulta do usuário com base em dados e insights proprietários.<br>A coluna  [!UICONTROL Estratégias ] de lance personalizadas está disponível na exibição   Campanhas e em relatórios. |
| [!UICONTROL Campanhas de pesquisa]<br> [!UICONTROL Bulksheets] | (Campanhas Microsoft Advertising) Para anúncios de texto expandidos, o suporte agora está disponível para um terceiro título opcional ([!UICONTROL Título de anúncio 3]) e uma segunda descrição opcional ([!UICONTROL Descrição 2]). O suporte está disponível na visualização [!UICONTROL Anúncios] e em [!UICONTROL Bulksheets]. |
| [!UICONTROL Insights de publicidade] | Dois novos [!UICONTROL Insights de publicidade] estão disponíveis:<ul><li>[!UICONTROL Receita] atrasada: Mede o atraso de conversão (o tempo decorrido entre um clique de SEM e uma conversão subsequente) de um portfólio e mostra quaisquer diferenças na receita ponderada, no ROI e na precisão do modelo devido ao atraso.</li><li>[!UICONTROL Correspondência] cruzada de consultas: Encontra instâncias de consultas de pesquisa que o Google correspondeu a mais de uma palavra-chave e fornece sugestões para onde direcionar o tráfego.</li></ul> |

### Tutoriais e cursos da Advertising Cloud

Atualizado em: **23 de fevereiro de 2021**

| Tutorial | Descrição |
| -----------| ---------- |
| [Introdução ao Workspace e Relatórios](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-analysis-workspace-a4adc.html?lang=pt-BR) | Saiba como você pode usar seus dados do Advertising Cloud para criar relatórios visuais no Adobe Analytics Analysis Workspace. |

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

* [Hub de aprendizagem do Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Hub de aprendizagem do Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem e suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

Novos tutoriais para a Creative Cloud Enterprise.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Março de 2021 | [Como entender o licenciamento de usuário nomeado](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/nameduserlicensing.html?lang=pt-BR) | Artigo | Saiba mais sobre a importância do Licenciamento de usuário nomeado. |
| 5 de março de 2021 | [Expiração do número de série](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/cceserial.html?lang=pt-BR) | Vídeo | Saiba mais sobre as etapas necessárias para garantir que os usuários finais tenham acesso contínuo aos aplicativos e serviços da Adobe. |
| Março de 2021 | [Implantar e gerenciar aterrissagem - Ativo de suporte](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/overview-deploy.html?lang=pt-BR) | Vídeo | Saiba como a Creative Cloud para corporações oferece suporte a implantações personalizadas e a atualizações flexíveis de licenças, além de funcionar com outras ofertas da Adobe para corporações. |
| 5 de março de 2021 | [Personalizar as cores em uma ilustração do Vetor do Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html?lang=pt-BR) | Vídeo | Adicione sofisticação a qualquer projeto com uma ilustração de ótima aparência. Encontre o vetor perfeito no Adobe Stock e, em seguida, corresponda as cores à paleta do seu projeto usando o Adobe Illustrator. |
| 5 de março de 2021 | [Personalize um modelo de apresentação do Adobe Stock para ter aparência profissional, mas atraente](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html?lang=pt-BR) | Vídeo | Crie uma bela apresentação estilizada em minutos com imagens e modelos do Adobe Stock e alguns efeitos especiais fáceis de fazer. |
| 5 de março de 2021 | [Personalizar uma animação da tela de carregamento com o Adobe Stock e o XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html?lang=pt-BR) | Vídeo | Personalize arte vetorial do Adobe Stock e crie uma animação de tela de carregamento atraente para um aplicativo móvel. |
| 5 de março de 2021 | [Criar compostos de fotos realistas com imagens do Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html?lang=pt-BR) | Vídeo | Reúna duas fotos excelentes do Adobe Stock e atraia pessoas para suas postagens sociais. |
| 5 de março de 2021 | [Crie quadros de humor inspiradores rapidamente com o Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html?lang=pt-BR) | Vídeo | Crie um quadro de humor do projeto para retransmitir informações, ideias, visuais e paletas de cores para equipes/clientes. |
| 5 de março de 2021 | [Crie imagens de marca coesas com lindos gradientes e ativos do Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html?lang=pt-BR) | Vídeo | Traga animação para seus gráficos de informativo com vetores editáveis para o Adobe Stock. |
| 5 de março de 2021 | [Criar animações para email com o Adobe Stock e o Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html?lang=pt-BR) | Vídeo | Capacite seus emails com a animação de ação de interrupção com o Adobe Stock e o Photoshop. |
| 5 de março de 2021 | [Crie uma foto interativa de turismo com o Adobe Stock e o XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html?lang=pt-BR) | Vídeo | Crie rapidamente uma foto interativa no protótipo do seu site com o Adobe Stock e o XD. |
