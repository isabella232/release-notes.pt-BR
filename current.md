---
title: Notas de versão da Adobe Experience Cloud
description: Notas de versão da Adobe Experience Cloud
doc-type: release notes
last-update: August 2020
author: mfrei
translation-type: tm+mt
source-git-commit: dab2c3fb8b9920f079195693a584f7c48b813e23
workflow-type: tm+mt
source-wordcount: '6207'
ht-degree: 43%

---


# Acesso antecipado - Notas de versão do Adobe Experience Cloud - agosto de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Esta página descreve novos recursos, correções e avisos importantes na [!DNL Adobe Experience Cloud]. Ela também destaca a nova documentação, cursos de treinamento e tutoriais em vídeo para ajudar você a aproveitar ao máximo a Experience Cloud.

>[!IMPORTANT]
>
>Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.

>[!NOTE]
>
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras.

**Data de lançamento: 13 de agosto de 2020**

As datas de lançamento do produto podem variar. Verifique frequentemente se há atualizações.

Última atualização: **7 de agosto de 2020**

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Orquestração da jornada](#journey-orch)
* [Analytics](#analytics) e [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://docs.adobe.com/content/help/pt-BR/primetime/release-notes/home.translate.html)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insight da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/adobe.png) Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

Consulte 21 [de maio de 2020](c-legacy-releases/2020/05212020.md#status) para obter as informações mais recentes.

## ![Ícone](/assets/ec_appicon_24.png) Interface da Experience Cloud {#ecloud}

Consulte as notas [de versão](c-legacy-releases/2020/07162020.md#ecloud) anteriores de julho para obter as informações mais recentes sobre a interface atualizada e o domínio unificado do produto.

## ![Ícone](/assets/experience_platform_appicon_24.png) da Adobe Experience Platform {#platform}

Notas de versão da [!DNL Experience Platform] e serviços de aplicativos, incluindo [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] e boletins de segurança.

Latest release date: **July 15, 2020**

Consulte as [notas de versão da Experience Platform](https://docs.adobe.com/content/help/pt-BR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) para obter as informações mais recentes da Experience Platform.

## ![Ícone](/assets/experience_platform_appicon_24.png) do Journey Orchestration {#journey-orch}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

### Novos cursos e tutoriais do Campaign

Novos vídeos, tutoriais ou cursos publicados no mês passado.

| Publicado | Nome | Descrição |
| ----------- | ---------- | ---------- |  
| 10 de julho de 2020 | [Eventos da etapa de viagem do relatórios para Adobe Experience Platform](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/reporting-step-events-to-adobe-experience-platform.html) | Saiba quais são os eventos de etapa de jornada e quais etapas de dados são criadas automaticamente no Experience Platform e como explorá-los. |

### Recursos adicionais do Journey Orchestration

[Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Novos recursos no Media Analytics](#media-aa)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- |-------|
| Melhorias na coleta de dados na China | 13 de ago de 2020 | As melhorias incluem: Suporte ao serviço de ID de Experience Cloud; suporte para SSL primário; e suporte para encaminhamento pelo lado do servidor. Para obter a documentação, entre em contato com o representante de vendas da Adobe. |
| [!UICONTROL Análises]entre dispositivos: Disponibilidade em EMEA e APAC | 31 de agosto de 2020 | [O Cross-Device Analytics](https://docs.adobe.com/content/help/en/analytics/components/cda/overview.html) e o gráfico privado estarão disponíveis para clientes na EMEA e na APAC. |
| Aprimoramento da correção em campo no [!UICONTROL Cross-Device Analytics] (disponível nas Américas e na EMEA) | 17 de agosto de 2020 | Essa implementação simplificada para novos clientes do [!UICONTROL Cross-Device Analytics] oferece a opção de suturar com base em uma ID de usuário armazenada em um campo do Analytics (prop ou eVar) em vez de usar um gráfico de dispositivo (cooperativo ou privado). O aprimoramento remove o requisito de implementar o ECID e remove o requisito de implementar a sincronização de ID para fins de CDA. (A sincronização de ECID e ID ainda é necessária para outros recursos.) |

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- |-----|
| [!UICONTROL Opção de Mapa de identidade para ID de pessoa] | 26 de junho de 2020 | [!UICONTROL O Mapa] de identidade é uma estrutura de dados de mapa que permite carregar pares de valores chave como parte da criação de uma conexão no [!UICONTROL Customer Journey Analytics]. As chaves são namespaces de identidade e o valor é uma estrutura que contém o valor de identidade. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics-platform/using/cja-connections/create-connection.html#use-identity-map-as-a-person-id) |

### Novos recursos no [!UICONTROL Media Analytics] {#media-aa}

Data de lançamento: **16 de julho de 2020**

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- | ---------- |
| [Dispositivos e plataformas compatíveis](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/supported-devices.html) | 18 de junho de 2020 | The [!UICONTROL Media Launch Extension] with AEP SDK now supports the following OTT devices:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Dispositivos e plataformas compatíveis](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/supported-devices.html) | 18 de junho de 2020 | A Extensão Media Launch com SDK AEP agora é compatível com os seguintes dispositivos OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Rastreamento do estado do player](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 de maio de 2020 | Os clientes do [!UICONTROL Media Analytics] podem capturar a interação do visualizador durante a reprodução usando um conjunto padrão de variáveis de solução para tela cheia, legendas ocultas, mudo, picture-in-picture e em foco. Você também tem flexibilidade para criar estados personalizados do player. As variáveis de Rastreamento de estado do player estão disponíveis para relatórios no [!UICONTROL Analysis Workspace]. Esse recurso exige um dos seguintes: <ul><li>Media [!DNL JavaScript] SDK 3.0 ou superior</li><li>Para uso com o SDK [!DNL Adobe Experience Platform] (AEP):</li><li>[!UICONTROL Extensão do Media Analytics] (para Web): [!UICONTROL Adobe Media Analytics] (SDK 3.x) for Audio and Video v1.0 ou superior</li><li>[!UICONTROL Extensão do Media Analytics] (para dispositivos móveis): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 ou superior</li><li>[!UICONTROL Coleção de mídia]</li></ul> |

### Correções no Adobe Analytics {#aa-fixes}

* Correção de um problema em que a API de relatórios não retornava valores de métricas atualizados. (AN-225617)
* Correção de um problema que impedia que Regras [!UICONTROL de] classificação classificassem dados para Detalhes [!UICONTROL do Canal de]marketing. (AN-224832)
* Correção de um problema que causava um erro de componentes __ ausentes ao criar novos projetos em um Conjunto [!UICONTROL de relatórios]virtuais.(AN-226808)
* Correção de um problema que causava um erro de componentes __ ausentes ao preparar um Conjunto de relatórios virtuais. (AN-228257)
* Correção de um problema que impedia a criação de novos públicos alvos do [!UICONTROL Relatórios e análises] e eventos do calendário. (AN-224872, AN-224890, AN-224914, AN-226661)
* Correção de um problema que causava atividades ausentes no painel A4T no [!UICONTROL Workspace]. (AN-224606)
* Correção de um problema com ocorrências de duplicado nos feeds [!UICONTROL de]dados. (AN-226308)
* Correção de um problema em que as métricas calculadas com atribuição de participação não retornavam os valores corretos. (AN-224642, AN-225190)
* Correção de um problema com dados de segmento compartilhados de [!DNL Analytics] a [!DNL Audience Manager] demora de mais de três dias para serem exibidos [!DNL Audience Manager].(AN-226649)
* Correção de um problema que impedia o uso do link [!UICONTROL Analisar mais] em emails de Alertas  inteligentes. (AN-226823)
* Correção de um problema que impedia a criação de segmentos em um conjunto [!UICONTROL de relatórios]virtual. (AN-227039)
* Correção de um problema que impedia a edição de alertas inteligentes. (AN-227162)

#### Outras correções do Adobe Analytics

AN-219351; AN-220960; AN-223788; AN-224630; AN-224948; AN-225618; AN-226261; AN-226828; AN-226845; AN-226937; AN-226961; AN-227070; AN-227079; AN-227521; AN-227610; AN-228203; AN-228451; AN-228466; AN-228538

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Fim da vida útil dos conectores de dados da Adobe | 13 de julho de 2020 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. Temos um novo padrão no [Programa de parceiros Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud) que deve ser adotado para todas as integrações que desejam continuar sendo oferecidas e tendo suporte. A data oficial do fim da vida útil ainda será determinada, mas prevemos que seja nos próximos 12 a 18 meses (meados de 2021 até o final de 2021). [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/import/dataconnectors/data-connectors-eol.html) |
| Mapeamento do conjunto de relatórios para organização IMS | Julho de 2020 | A ferramenta de mapeamento do conjunto de relatórios será descontinuada em novembro de 2020. Esse recurso capacita integrações como o Advertising Analytics e a publicação de segmentos da Experience Cloud no Adobe Analytics. Um conjunto de relatórios deve ser mapeado para uma organização IMS para ativar esses e outros serviços. Os conjuntos de relatórios mais recentes são mapeados automaticamente após a criação. No entanto, os conjuntos de relatórios mais antigos devem ser mapeados manualmente para uma organização IMS. See [Map report suites to an organization](https://docs.adobe.com/content/help/pt-BR/core-services/interface/about-core-services/report-suite-mapping.html) in the Experience Cloud interface (Core Services) user guide to make sure all report suites belong to an IMS org. |
| Migração para o domínio de produto unificado | Data efetiva: 28 de maio de 2020 | A migração para um domínio de produto unificado do Adobe Analytics, que começou em janeiro de 2020, terminou em 28 de maio de 2020. Embora o Adobe Analytics funcione para remover todas as referências de domínio `omniture.com` de sua arquitetura, é importante adicionar uma lista de permissões `omniture.com` como um cookie de terceiros. Quando a migração da arquitetura for concluída (em breve), você será notificado por meio das notas de versão e essa etapa da lista de permissões não será mais necessária. [Esta](https://helpx.adobe.com/br/analytics/kb/adobe-ip-addresses.html) é uma lista completa de domínios e endereços IP recomendados que você deve incluir na lista de permissões.<br>Se sua organização bloquear cookies de terceiros, entre em contato com o Atendimento ao cliente para recuperar o acesso ao Adobe Analytics. |
| Nova página de aterrissagem padrão do Adobe Analytics | Data efetiva: 18 de junho de 2020 | Em 18 de junho de 2020, a landing page padrão do Adobe Analytics será alterada de [!UICONTROL Relatórios] para [!UICONTROL Workspace]. Essa alteração ocorrerá para qualquer usuário que não tenha definido uma landing page personalizada anteriormente. |
| Tecnologia de terceiros permitida | 12 de março de 2020 (data de efetivação) | O Adobe Analytics começou a utilizar tecnologias de terceiros para o gerenciamento da implantação de recursos e suporte no produto. Os seguintes URLs devem ser adicionados a qualquer lista de permissões de firewall de rede necessária para garantir o acesso total aos recursos:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Redundância aprimorada para disponibilidade do [!UICONTROL Analysis Workspace] | 21 de maio de 2020 | Para garantir a disponibilidade do [!UICONTROL Analysis Workspace], estamos adicionando uma CDN (Content Delivery Network) secundária para melhorar a redundância. Os seguintes URLs devem ser adicionados a qualquer lista de permissões de firewall de rede necessária:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Alteração na forma como [!UICONTROL Entradas/Saídas] são calculadas no [!UICONTROL Workspace] | 7 de abril de 2020 | A partir de março de 2020, mudamos no [!UICONTROL Analysis Workspace] a forma como o valor _Nenhum_ interage com [!UICONTROL Entradas/Saídas]. Como agora é possível ativar ou desativar o valor _Nenhum_ no [!UICONTROL Analysis Workspace], aplicamos o valor _Nenhum_ após a entrada ou saída, enquanto que (para eVars) costumava ser aplicado antes da entrada ou saída. Por exemplo, suponha que a primeira ocorrência de uma visita não tenha valor para eVars, mas a segunda ocorrência tem. No [!UICONTROL Reports &amp; Analytics], a primeira ocorrência será exibida como _Não especificado_ para a Entrada, mas no [!UICONTROL Analysis Workspace] será exibida como o valor na segunda ocorrência. |
| EOL do **[!UICONTROL Arquivo do painel]** | 27 de março de 2020 | A configuração **[!UICONTROL Exibir arquivo]** em **[!UICONTROL Gerenciar painéis]** no [!UICONTROL Reports &amp; Analytics] não estará mais disponível a partir de março de 2020. |
| Fim da vida útil das APIs herdadas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Cingapura, não apoiaremos mais a intermediação de dados entre Londres ou Cingapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fim da vida útil do Ad Hoc Analysis | 6 de agosto de 2018 | A Adobe anunciou a intenção de encerrar a vida útil do Ad Hoc Analysis. Uma data para o fim da vida útil será compartilhada assim que estiver disponível. Para obter mais informações, visite [Descubra a Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Para obter as atualizações mais recentes das versões do AppMeasurement, consulte as [notas de versão do AppMeasurement para JavaScript](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/appmeasurement-updates.html).

#### Novos cursos e tutoriais do Analytics {#tutorials-analytics}

Novos cursos, vídeos de tutoriais e artigos no Analytics e Customer Journey Analytics.

| Publicado | Nome | Solução | Descrição |
| ----------- | ----------- | ---------- | ---------- |  
| 30 de julho de 2020 | [Limitar o acesso ao conjunto de relatórios no Admin Console](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/limit-report-suite-access-in-the-admin-console.html) | Tutorial | Saiba como usar o [!UICONTROL Admin Console] para garantir que os usuários possam acessar somente os conjuntos de relatórios necessários para sua função. |
| 24 de julho de 2020 | [Adicionar um administrador à Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/adding-an-administrator-to-adobe-analytics.html) | Tutorial | Saiba como adicionar um usuário como Administrador no Adobe [!UICONTROL Admin Console]. |
| 17 de julho de 2020 | [Painel Quick Insights no Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/quick-insights-panel-in-analysis-workspace.html) | Tutorial | O painel Quick Insights fornece orientação para não analistas e novos usuários do Analysis Workspace para saber como responder a perguntas comerciais de forma rápida e fácil. |
| 17 de julho de 2020 | [Painel Analytics para Públicos alvos (A4T) no Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/target/analytics-for-target-a4t-panel-in-analysis-workspace.html) | Tutorial | The [!UICONTROL Analytics for Target] (A4T) panel lets you analyze your Adobe Target activities and experiences, with lift and confidence, in Analysis Workspace. |
| 6 de julho de 2020 | [Criar Painéis Advertising Cloud com Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-advertising-cloud-dashboards-with-adobe-analytics.html?lang=en#tutorials) | Tutorial | Técnicas para criar um painel Advertising Cloud para monitoramento de campanha ao vivo. |
| 6 de julho de 2020 | [Criar métricas personalizadas do Analytics com dados da Advertising Cloud](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-custom-metrics-with-advertising-cloud-data.html?lang=en#tutorials) | Tutorial | Métricas personalizadas úteis para criar ao usar dados do Advertising Cloud no Adobe Analytics. |
| 6 de julho de 2020 | [Criar Perfis de jornada do site do Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-site-journey-profiles.html?lang=en#tutorials) | Tutorial | Como usar o Adobe Analytics para criar pools robustos de redefinição de metas do site para remarketing do Advertising Cloud. |
| 6 de julho de 2020 | [Criar segmentos do Analytics para Ativação e Relatórios](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-segments-for-activation-and-reporting.html?lang=en#tutorials) | Tutorial | Uso de dimensões Advertising Cloud para criar segmentos para relatórios e análise mais limpos. |
| 6 de julho de 2020 | [Criar uma Análise de Campanha de pré-lançamento com a Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/reporting-with-advertising-cloud-marketing-channels.html?lang=en#tutorials) | Tutorial | Como usar o Adobe Analytics para configurar a base para lançar uma campanha de mídia paga da Advertising Cloud. |
| 6 de julho de 2020 | [Compartilhamento de projetos no Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/project-sharing-in-analysis-workspace.html?lang=en#tutorials) | Tutorial | O compartilhamento de projetos é uma maneira de democratizar dados e insights da Analysis Workspace para usuários em sua organização. Você pode colocar recipient em uma das três funções do projeto, dependendo da experiência do projeto que deseja que eles tenham - Editar, Duplicado e Visualização. |
| 26 de junho de 2020 | [Janelas de reversão personalizadas no Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/custom-lookback-windows-in-attribution-iq.html?lang=en#tutorials) | Tutorial | As janelas de retrospectiva personalizadas permitem que você expanda a janela de atribuição além do intervalo de relatórios (até um máximo de 90 dias) e se aplica a cada conversão no intervalo de relatórios. |
| 26 de junho de 2020 | [Projetos somente visualização no Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/view-only-projects-in-analysis-workspace.html?lang=en#tutorials) | Tutorial | Workspace projects can be shared to users as _Can view_ only. When a _View_ recipient opens the shared project, they receive a more restrictive project experience, with no left rail and limited interactions. |
| 26 de junho de 2020 | [Modelo algorítmico em Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/algorithmic-model-in-attribution-iq.html?lang=en#tutorials) | Tutorial | O modelo [!UICONTROL Atribuição algorítmica] no Analysis Workspace usa técnicas estatísticas para determinar dinamicamente a alocação ideal de crédito para a métrica selecionada. |

#### Recursos de ajuda do Analytics

* [Tutoriais do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentação de produto do Adobe Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/landing/home.html)

## ![Ícone](/assets/audience-manager.png) do Adobe Audience Manager {#aam}

Novos recursos, correções, documentação e tutoriais no Audience Manager.

Data de lançamento: **13 de agosto de 2020**

### Novos recursos e correções no Adobe Audience Manager

* [As Audiências](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) preditivas agora suportam a seleção de uma Regra [!UICONTROL de mesclagem de] Perfis por modelo, durante a criação do modelo. (AAM-55178)
* As datas de start e término do mapeamento de destino agora estão visíveis na página de cada segmento. (AAM-40056)
* Correção de um problema em que o Tipo [!UICONTROL de] dispositivo de uma característica era automaticamente definido como [!UICONTROL Entre dispositivos] ao criar uma nova característica. (AAM-55368)
* Correção de um problema em que o [!UICONTROL Audience Marketplace] falhava ao carregar. (AAM-55549)
* Agora é possível desmapear segmentos de [!DNL Google] destinos quando o [!DNL Google UserList] parâmetro não é recuperável. (AAM-42655)
* Correção de um problema em que a adição de vários segmentos a um destino nem sempre funcionava corretamente. (AAM-55651)
* Correção de um problema em que os usuários cujo [!DNL Profile Merge Rules] limite era aumentado não visualizavam o botão [!UICONTROL Adicionar nova regra] . (AAM-55700)
* Correção de um problema em que o título Usuários [!UICONTROL únicos sobrepostos de] 30 dias ficava ausente das Métricas [!UICONTROL de relatório do feed de]dados. (AAM-55801)
* Agora, as métricas de duração são excluídas da visualização [!UICONTROL Destino] quando o destino está configurado para exportar [!DNL UUID]s. (AAM-54196)
* Correção de um problema em que os usuários não conseguiam visualização em [!DNL Tableau] relatórios. (AAM-55868)
* Correção de um problema em que os usuários recebiam um erro ao criar um novo modelo de Audiências  previsíveis. (AAM-55921)
* Várias melhorias de acessibilidade na interface. (AAM-49062, AAM-49063, AAM-49365).

### Novos tutoriais do Audience Manager {#tutorials-aam}

| Publicado | Nome | Solução | Descrição |
| ----------- | ----------- | ---------- | ---------- |
| 7 de agosto de 2020 | [Economize dinheiro e otimize a experiência do cliente ao suprimir anúncios em conversores](https://experienceleague.adobe.com/?recommended=AudienceManager-A-1-2020.1) | Tutorial | Neste curso, aprenda todos os conceitos para ir do start ao fim com o caso de uso de economia e otimização da experiência do cliente, removendo clientes existentes de suas campanhas de alcance. Isso inclui a criação de características e segmentos, a adição das regras de mesclagem de perfil certas, a adição de segmentos aos destinos e até mesmo o cálculo do ROI à medida que você usa esse caso de uso. |
| 7 de agosto de 2020 | [Escolhendo a regra de mesclagem de Perfil certa](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/choosing-the-right-profile-merge-rule.html) | Tutorial | Neste vídeo, descubra três dos casos de uso mais comuns para regras [!UICONTROL de mesclagem de]Perfis e como eles podem ajudar seus esforços de marketing. |
| 5 de agosto de 2020 | [Criação de uma Taxonomia de segmento](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-a-segment-taxonomy.html) | Tutorial | Ao criar um segmento no Audience Manager, você os armazena em uma estrutura baseada em pastas ou em uma _taxonomia_. Aprenda algumas dicas para criar e gerenciar a taxonomia do segmento. |
| 4 de agosto de 2020 | [Recuperar credenciais de API em E/S Adobe](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/api/retrieve-api-credentials-in-adobe-io.html) | Tutorial | Em vez de entrar em contato com a Adobe Consulting ou com o Atendimento ao cliente para obter credenciais para usar a REST API, você pode simplesmente acessar `Adobe.io` um navegador e recuperar ou registrar suas próprias credenciais. |
| 31 de julho de 2020 | [Uso de Idade e Frequência em Segmentos](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-recency-and-frequency-in-segments.html) | Tutorial | Use [!UICONTROL Idade] e [!UICONTROL Frequência] para fornecer aos seus parâmetros de segmento quantas vezes um visitante precisa se qualificar para uma característica dentro de um determinado período de tempo. Excelente para afinidade de conteúdo e casos de uso de limite de frequência, bem como outros. |
| 22 de julho de 2020 | [Noções básicas para a criação de segmentos](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/the-basics-of-creating-segments.html) | Tutorial | Percorra os campos na interface do usuário para criar um segmento no Audience Manager. |
| 22 de julho de 2020 | [Definição e criação de segmentos práticos](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/practical-segment-definition-and-creation.html) | Tutorial | Este vídeo o orienta por um processo de definição de seus segmentos, e depois os divide pelos traços e sinais que você precisa para criá-los. |
| 17 de julho de 2020 | [Suprimir publicidades para conversores](https://video.tv.adobe.com/v/36658?captions=por_br) | Tutorial | Economize dinheiro e otimize a experiência do cliente ao suprimir anúncios aos conversores. |
| 15 de julho de 2020 | [Avaliação do ROI em um caso de uso de supressão de clientes](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/value-realization/measuring-roi-in-a-customer-suppression-use-case.html) | Tutorial | Saiba como usar algumas fórmulas para determinar a economia de custos da campanha, suprimindo os anúncios aos clientes existentes. |
| 10 de julho de 2020 | [Criação de um segmento para suprimir anúncios aos clientes](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/building-a-segment-to-suppress-ads-to-customers.html) | Tutorial | Este vídeo discute as opções de criação de segmentos para excluir aqueles que já se converteram em status de cliente. |

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### **Versões do produto**

* **AEM como um Cloud Service**

   O que há de novo em AEM como Cloud Service? Os destaques em destaque incluem:

   * AEM Comércio está disponível no Cloud Service. Consulte [Introdução ao Comércio AEM como Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/getting-started.html)
   * Os conectores para Adobe Target e Adobe Analytics incluem melhorias na interface do usuário, substituição da interface clássica e integração com o Adobe Launch. Consulte [Integração do Adobe Analytics](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-analytics.html) e [integração do Adobe Target.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-target.html)
   * O Asset Compute Service é um serviço escalonável e extensível para processar ativos. Os administradores podem configurar o Experience Manager para chamar o trabalhador personalizado criado usando o Serviço de Computação de Ativos. Os desenvolvedores podem usar o serviço para criar funcionários personalizados especializados que atendam a casos de uso complexos. Esse serviço da Web pode gerar miniaturas para diferentes tipos de arquivos, renderizações de imagem de alta qualidade de formatos de arquivo Adobe, codificar vídeos (futuros), extrair metadados, extrair texto completo como precursor para indexação e executar um ativo por meio de todos os serviços do Sensei disponíveis. Consulte [Usar microserviços de ativos e perfis de processamento.](https://docs.adobe.com/content/help/br/experience-manager-cloud-service/assets/manage/asset-microservices-configure-and-use.html)
   * Várias melhorias para modelos de fluxo de trabalho e Dynamic Media em AEM como Cloud Service.
   * Release 2.11.0 of the [AEM Core Components](https://docs.adobe.com/content/help/pt-BR/experience-manager-core-components/using/introduction.html) is now available as part of AEM Sites including the following:
      * Introdução de um novo componente do visualizador de [PDF.](https://aemcomponents.dev/content/core-components-examples/library/page-authoring/pdf-viewer.html)
      * Suporte para Accelerated Mobile Pages (AMP) dos componentes principais. Ele ajuda a produzir experiências mais rápidas do cliente, tornando a página transição instantaneamente ao entrar no site a partir de um resultado de pesquisa móvel do Google, o que melhora a participação do usuário e a SEO. Consulte Suporte [AMP para os componentes principais.](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)
      * Compatibilidade com a versão 1.0.2 da Camada [de dados do cliente](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)Adobe.
   * Várias melhorias na interface do usuário no Cloud Manager.
   * Os pipelines do Cloud Manager agora oferecem suporte a variáveis e segredos definidos pelo cliente. Consulte Variáveis [Pipeline.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/getting-access/creating-aem-application-project.html#pipeline-variables)
   * [Os registros podem ser encaminhados para contas](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/logging.html#splunk-logs)de partes, o que permite que as organizações aproveitem seu [!DNL Splunk] investimento.
   * Você pode atribuir [um endereço](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/development-guidelines.html#dedicated-egress-ip-address) IP de saída estático e dedicado para o tráfego externo programado no código Java, que pode ser útil para algumas integrações.
   * O Cloud Readiness Analyzer v1.0.2 foi lançado. Consulte [Instalação do CRA no AEM 6.1.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/cloud-readiness-analyzer/using-cloud-readiness-analyzer.html#installing-on-aem61)
   * Consulte as notas de versão [completas para AEM como Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?mkt_tok=eyJpIjoiWm1SallqTmtOekF6WldZMCIsInQiOiJoTTZ3Qm9LNVRXc1lsbjExdlpNMGdQNFE2UGM5ejZob1EwZXlPZHp2MEZJa1BPTHhybHBYcUxFWTgwVjNFajlzYU1Fb1NoVXRwMTc3U2IrbHZKeTVSOG02MUErbWpIb1pjNU8zYkdTbW5MZHVIRUUyNk9vUU9SckdOeUJmbXlObSJ9)

### Autoajuda

* **AEM Forms**

   * Agora, os pacotes de adição AEM Forms estão disponíveis em [AEM Distribuição](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?2_group.propertyvalues.property=.%2Fjcr%3Acontent%2Fmetadata%2Fdc%3Asolution&amp;2_group.propertyvalues.operation=equals&amp;2_group.propertyvalues.0_values=público alvo-solution%3Aaem%2Fforms&amp;orderby=%40jcr%3Acontent%2Fjcr%3AlastModified&amp;orderby.sort=desc layout=lista&amp;p.offset=0&amp;p.limit=24)de software. Você pode encontrar links diretos para pacotes de cada versão compatível no artigo de versões [do](https://helpx.adobe.com/br/aem-forms/kb/aem-forms-releases.html) AEM Forms.
   * Use o site [de](https://docs.adobe.com/content/help/en/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) referência para saber o fluxo de trabalho completo do serviço de Conversão automatizada da Forms.
   * As versões Javadocs para AEM [6.5.5.0](https://helpx.adobe.com/experience-manager/6-5/forms/javadocs/index.html) e AEM [6.4.8.1](https://helpx.adobe.com/experience-manager/6-4/forms/javadocs/index.html) estão disponíveis.
   * [Importe certificados](https://docs.adobe.com/content/help/en/experience-manager-65/forms/manage-administer-aem-forms/hardening-aem-forms-environment/hardening-aem-forms-jee-environment.html#configuring-ssl) confiáveis para JVM enquanto endurece um AEM Forms no ambiente JEE.
   * Melhoria na documentação de configuração do [PDF Generator.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/install-configure-document-services.html)

* **Componentes principais**

   O Core Componentes versão 2.11.0 apresenta suporte para a AMP e agora está disponível, juntamente com a documentação [de](https://docs.adobe.com/content/help/pt-BR/experience-manager-core-components/using/introduction.html) criação e detalhes do [desenvolvedor e download do projeto, disponíveis no GitHub.](https://github.com/adobe/aem-core-wcm-components)

### **Comunidade**

* **O conteúdo AEM mais recente da Experience League**

   Essa é a fonte oficial do conteúdo técnico da Digital Experience produzido pela Adobe. Veja a lista completa [aqui.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/qaq-p/373396)

### Novos cursos e tutoriais do Experience Manager

Novos vídeos, tutoriais ou cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 7 de agosto de 2020 | [Introdução ao Gerenciamento de vários sites para usuários empresariais](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites.msm) | Curso | Saiba como estabelecer uma base sólida para sua implementação do AEM Assets configurando as principais preocupações, desde a configuração de uma arquitetura de conteúdo básico e taxonomia até a personalização de metadados e processamento de ativos. |
| 7 de agosto de 2020 | [Configuração da AEM Assets para administradores](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2020.1.assets) | Tutorial | Descrição |
| 19 de julho de 2020 | [Uso da ferramenta Transferência de conteúdo](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/migration/content-transfer-tool.html) | Tutorial | A Ferramenta de transferência [!UICONTROL de] conteúdo é a maneira recomendada para migrar o conteúdo de uma versão local ou hospedada pelo AMS do Experience Manager para um [!UICONTROL AEM como ambiente Cloud Service] . |
| 21 de julho de 2020 | [Criar uma Live Copy](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-live-copy.html) | Tutorial | Entenda como criar uma [!UICONTROL Live Copy] para seu site a partir de um [!UICONTROL Blueprint] usando o assistente [!UICONTROL Criar Live Copy] . |
| 21 de julho de 2020 | [Console de Live Copy](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-overview-console.html) | Tutorial | Saiba como visualização ou gerenciar herança em um site ou executar operações de implantação usando o console Visão geral da Live Copy. |
| 21 de julho de 2020 | [Projetos de tradução](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Tutorial | Saiba como criar, editar e gerenciar um projeto de tradução para sua Cópia [!UICONTROL de]idioma. |
| 21 de julho de 2020 | [Trabalhos de tradução](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Tutorial | Saiba como adicionar um trabalho de tradução a um projeto de tradução existente. |
| 21 de julho de 2020 | [Atualização da cópia de idioma com inicializações](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/updating-language-copy.html) | Tutorial | Saiba como atualizar, revisar e aprovar alterações em uma Cópia [!UICONTROL de] idioma com a ajuda de Inicializações. |
| 21 de julho de 2020 | [Visão geral do gerenciamento de vários sites](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/language-copy-overview.html) | Tutorial | Obtenha uma visão geral de como criar um site multilíngue usando o [!UICONTROL idioma Copiar] no [!UICONTROL AEM Sites]. |
| 21 de julho de 2020 | [Live Copy e Blueprint](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-and-blueprint.html) | Tutorial | Entenda a relação entre um [!UICONTROL Live Copy] e seu [!UICONTROL Blueprint] no [!UICONTROL AEM Sites]. |
| 21 de julho de 2020 | [Gerenciar herança de Live Copy em uma página](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-page-inheritance-live-copy.html) | Tutorial | Saiba como gerenciar a herança entre uma [!UICONTROL Live Copy] e seu [!UICONTROL Blueprint] em nível de página. |
| 21 de julho de 2020 | [Gerenciar herança do Live Copy em um componente](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Tutorial | Entenda como gerenciar a herança entre uma [!UICONTROL Live Copy] e seu [!UICONTROL Blueprint] no nível do componente. |
| 21 de julho de 2020 | [Criar uma cópia de idioma](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Tutorial | Descrição. |
| 21 de julho de 2020 | [Criar uma cópia de idioma](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-launguage-copy.html) | Tutorial | Explore como criar uma cópia [!UICONTROL de] idioma para o site AEM usando o assistente [!UICONTROL para]Criar cópia de idioma. |
| 21 de julho de 2020 | [Criar um projeto de tradução em vários idiomas](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-multinational-translational-project.html) | Tutorial | Saiba como criar, editar e gerenciar um projeto de tradução em vários idiomas para sua Cópia [!UICONTROL de] idioma AEM console Projeto. |
| 21 de julho de 2020 | [Criar um site de país](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-site.html) | Tutorial | Saiba como criar um site de país a partir de Cópias [!UICONTROL de] idiomas existentes usando o assistente para [!UICONTROL Criar site] . |
| 21 de julho de 2020 | [Criar uma página de cópia de idioma](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-page-language-copy.html) | Tutorial | Saiba como criar uma página em uma Cópia [!UICONTROL de]idioma existente e, em seguida, traduzir o conteúdo para outra Cópia [!UICONTROL de]idioma. |
| 21 de julho de 2020 | [Status do trabalho de tradução](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/translation-job-status.html) | Tutorial | Entenda os diferentes status associados a um trabalho de tradução ou a um item no trabalho. |
| 21 de julho de 2020 | [Introdução ao Gerenciamento de vários sites](https://video.tv.adobe.com/v/36686?captions=por_br) | Tutorial | Introdução ao curso Introdução ao Gerenciamento de vários sites para usuários corporativos. |
| 21 de julho de 2020 | [Criar fragmentos de formulário adaptáveis](https://video.tv.adobe.com/v/37325?captions=por_br) | Tutorial | Formulários adaptáveis fornecem um mecanismo conveniente para criar segmentos de formulários, como um painel ou um grupo de campos, somente uma vez e reutilizá-los em formulários adaptáveis. Esses segmentos reutilizáveis e independentes são chamados de fragmentos de formulário adaptáveis. |
| 21 de julho de 2020 | [Caixa de entrada AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/inbox-customization/introduction.html) | Tutorial | [!UICONTROL AEM Caixa de entrada] consolida notificações e tarefas de vários componentes AEM, incluindo workflows Forms. |
| 21 de julho de 2020 | [Depuração da inicialização rápida local do SDK do AEM usando registros](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Tutorial | Os registros atuam como linha de frente para depurar aplicativos AEM, mas dependem do logon adequado no aplicativo AEM implantado. |
| 21 de julho de 2020 | [Introdução ao editor do SPA](https://video.tv.adobe.com/v/37705?quality=12&learn=on&captions=por_br) | Tutorial | Uma introdução ao curso Introdução à Introdução AEM Editor SPA para desenvolvedores. |
| 2020 | [Permissões da linha de base](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/baseline-permissions.html) | Tutorial | O gerenciamento do acesso do usuário às pastas de ativos da linha de base é um aspecto essencial no controle e garante que os processos possam ser suportados corretamente. |
| 21 de julho de 2020 | [Workflows de start automático](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/auto-start-workflows.html) | Tutorial | Os workflows de start automático estendem o processamento de ativos em AEM como um Cloud Service, chamando automaticamente o fluxo de trabalho personalizado após o upload ou o reprocessamento. |
| 21 de julho de 2020 | [Depuração da inicialização rápida local do SDK do AEM usando registros](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Tutorial | Os registros atuam como linha de frente para depurar aplicativos AEM, mas dependem do logon adequado no aplicativo AEM implantado. |
| 21 de julho de 2020 | [Criar modelo de formulário adaptável](https://video.tv.adobe.com/v/37324?captions=por_br) | Tutorial | Quando os autores usam o modelo para criar um formulário adaptável, o novo formulário herda a estrutura e os componentes especificados no modelo. |
| 21 de julho de 2020 | [Criar fonte de dados agrupada da conexão Apache Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/prefill-fdm-db/create-form-data-model.html) | Tutorial | A primeira etapa na criação do modelo de dados de formulário RDBMS é configurar a Apache Sling Connection Pooling DataSource. |
| 21 de julho de 2020 | [Preenchimento prévio de formulários adaptáveis usando o modelo de dados de formulário](https://video.tv.adobe.com/v/36387?captions=por_br) | Tutorial | Introdução ao preenchimento prévio de formulários usando o modelo de dados de formulário. |
| 21 de julho de 2020 | [Criação do seu primeiro formulário adaptável](https://video.tv.adobe.com/v/37701?captions=por_br) | Tutorial | Neste vídeo, saiba como criar seu primeiro formulário adaptável. |

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Informações sobre a versão do AEM como serviço na nuvem](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/release-notes/home.html)
* [Notas de versão do AEM Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://docs.adobe.com/content/help/pt-BR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notas de versão do AEM 6.5 Service Pack](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Notas de versão do AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/pt-BR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notas de versão do AEM Assets Dynamic Media](https://docs.adobe.com/content/help/pt-BR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de versão do AEM Brand Portal](https://docs.adobe.com/content/help/pt-BR/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Notas de versão do aplicativo de desktop do AEM](https://docs.adobe.com/content/help/pt-BR/experience-manager-desktop-app/using/release-notes.html)
* [Notas de versão do AEM Dispatcher ](https://docs.adobe.com/content/help/pt-BR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notas de versão do Adobe Primetime](https://docs.adobe.com/content/help/pt-BR/primetime/release-notes/home.translate.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

### Recursos adicionais de ajuda para o AEM

* [Guias do usuário do AEM como serviço na nuvem](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
* [Página inicial de aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Página inicial de aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Página inicial de aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página inicial de aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/home.html)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Novas versões de produtos

Informações de versão do Campaign Classic, Campaign Standard e Painel de controle do Campaign.

#### Campaign Classic

* Versão 20.2.1 - [Leia mais](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Novos cursos e tutoriais do Campaign

Novos vídeos, tutoriais ou cursos publicados no mês passado.

| Publicado | Nome | Solução | Descrição |
| ----------- | ----------- | ---------- | ---------- |  
| 10 de julho de 2020 | [Painel de controle do Campaign - Gerenciamento de chaves GPG - Descriptografia de dados](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/decrypting-data.html) | Campaign Classic | Saiba como criar uma chave pública, importá-la e instalá-la em uma instância do Campaign para descriptografar dados de entrada. |
| 10 de julho de 2020 | [Painel de controle do Campaign - Gerenciamento de chave GPG - Uso de uma chave GPG para criptografar dados](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Classic | Saiba como exportar dados usando uma chave GPG instalada no Painel de controle do Campaign. |
| 10 de julho de 2020 | [Painel de controle do Campaign - Geração e instalação de chaves GPG para criptografia de dados](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Classic | Saiba como gerar um par de chaves GPG públicas/privadas e instalar a chave pública no Painel de controle do Campaign para poder criptografar dados antes de enviá-los da sua instância. |
| 21 de julho de 2020 | [Gerenciamento de Campanhas de marketing](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/managing-marketing-campaigns.html) | Campaign Classic | Entenda os principais conceitos da Adobe Campaign que ajudam a planejar, executar e avaliar com eficácia as campanhas de marketing entre canais. |
| 22 de julho de 2020 | [Criação de planos de marketing, programas e campanhas](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/creating-a-marketing-plan-programs-and-campaigns.html) | Campaign Classic | Saiba como criar um plano de marketing, programa e campanha, definir as propriedades de uma campanha e entender como usar o agendamento. O vídeo guia você por um exercício que você pode seguir. |
| 23 de julho de 2020 | [Criação e gerenciamento de perfis](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/profile-management/create-and-manage-profiles.html) | Campaign Classic | Entenda o conceito de perfis no Adobe Campaign Classic. Saiba como acessar os dados do perfil, classificar e filtrar perfis e criar e gerenciar perfis manualmente. |
| 28 de julho de 2020 | [Personalização de emails usando conteúdo condicional](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-create-a-multi-lingual-newsletter-using-conditional-content.html) | Campaign Classic | Saiba como adicionar conteúdo condicional a um delivery no exemplo de um boletim multilíngue. |
| 28 de julho de 2020 | [Personalização de emails usando campos de personalização](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-using-personalization-fields.html) | Campaign Classic | Saiba como adicionar um campo de personalização à linha de assunto e ao conteúdo de um delivery de email. |
| 28 de julho de 2020 | [Direcionamento de perfis em um fluxo de trabalho](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/targeting-profiles-in-a-workflow.html) | Campaign Classic | Entenda o uso de workflows da campanha e saiba como criar um fluxo de trabalho e perfis de público alvo em um fluxo de trabalho usando as condições de filtragem. |
| 31 de julho de 2020 | [Geração de um relatório de análise descritiva](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/reporting/generating-a-descriptive-analysis-report.html) | Campaign Classic | Saiba como gerar um relatório de análise descritivo. |
| 9 de julho de 2020 | [Painel de controle do Campaign - Gerenciamento de chave GPG - Uso de uma chave GPG para criptografar dados](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Standard | Saiba como exportar dados usando uma chave GPG instalada no Painel de controle do Campaign. |
| 9 de julho de 2020 | [Painel de controle do Campaign - Gerenciamento de chaves GPG - Descriptografia de dados](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/decrypting-data.html) | Campaign Standard | Saiba como criar uma chave pública, importá-la e instalá-la em uma instância do Campaign para descriptografar dados de entrada. |
| 9 de julho de 2020 | [Painel de controle do Campaign - Gerenciamento de chave GPG - Geração e instalação de chaves GPG para criptografia de dados](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Standard | Saiba como gerar e instalar um par de chaves públicas/privadas em uma instância do Campaign especificada para a criptografia de dados de saída. |

### Recursos de ajuda

* Adobe Campaign Standard: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/campaign-standard-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/overview.html) - [Planejamento de lançamento](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-planning.html) - [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/campaign-classic-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-classic-learn/tutorials/overview.html)- [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/documentation-updates.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html) - Vídeos explicativos do [Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/pt-BR/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notas de versão da Adobe Advertising Cloud.

### Novos recursos na [!UICONTROL Advertising Cloud Search] {#adcloud-search}

**Versão de 8** de agosto

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Portfólios] | Os limites de posição no nível de Portfolio não estão mais disponíveis nas configurações de portfólio. Quaisquer limites de posição criados anteriormente foram removidos. |
| [!UICONTROL Limitações] | Restrições baseadas em posição e condições de restrição não são mais suportadas:<br/><ul><li>As restrições de Posição e Posição máx. mín. não estão mais disponíveis e foram removidas de todas as restrições de Licitação e Posição criadas anteriormente e do Compartilhamento de Impressão.</li><li>Restrições existentes de lance e posição que incluíam restrições de posição, mas nenhuma restrição de lance era pausada. Eles ainda estão disponíveis na interface do usuário e nos relatórios.</li><li>As restrições de lance e posição foram renomeadas como restrições de lance.</li><li>Todas as condições baseadas na posição (usando as métricas Posição média, Posição média ponderada ou Última posição conhecida) em qualquer tipo de restrição foram removidas.</li></ul><br/>**Observação:**Os dados de posição continuarão a ser preenchidos enquanto estiverem disponíveis nos mecanismos de pesquisa. A Microsoft Ads será aposentada em setembro de 2020. |  |
| [!UICONTROL Campanhas] | (campanhas do Google Ads) A Advertising Cloud Search agora oferece suporte a anúncios personalizados em anúncios de pesquisa responsivos (RSAs). Anteriormente, eles eram suportados em todos os tipos de anúncios, exceto RSAs. |

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Para ver as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Ícone](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes ao se envolverem em todas as jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte as [!DNL Marketo] [notas de versão](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720) para obter as informações mais recentes.

### Recursos futuros

Os seguintes recursos serão lançados ao longo do trimestre:

| Recurso | Descrição |
|------|---------|
| [!DNL Bizible] | <ul><li>Nova segmentação baseada em conta</li><li>Salvar filtros específicos do painel</li><li>Exportar painéis Bizible como PDFs</li></ul> |
| Conexão de vendas | Compor atualizações/aprimoramentos da Janela e do Centro de comando |

### Anúncios

**Centro de Sucesso do Marketo Engage:** lançamento em fevereiro de 2020. O Centro de sucesso é um centro de ajuda no produto que permite pesquisar em Documentos de produto e na Comunidade, iniciar guias tutoriais, acessar conteúdo de adoção e muito mais. Observação: esse recurso será lançado como um beta na Austrália e Nova Zelândia e será implantado na América do norte posteriormente neste trimestre.

### Desativações

* **Parâmetro &quot;_method&quot; da API de ativos:** a partir de setembro de 2020, os access points da API de ativos não aceitarão mais `_method` passar parâmetros de consulta em um corpo do POST para ignorar as limitações de comprimento do URI.
* **Desativação do suporte ao Internet Explorer:** a partir do lançamento realizado em 31 de julho de 2020, a interface do usuário do Marketo Engage não será mais compatível com o Internet Explorer.

Para obter as notas de versão cumulativas e históricas, consulte [Notas de versão do Marketo](https://docs.marketo.com/x/CgA6Ag).
