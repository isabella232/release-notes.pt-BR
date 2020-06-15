---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 3dd0f7e9f8712786acc31a01dc0fdece9f4004b9
workflow-type: tm+mt
source-wordcount: '6484'
ht-degree: 37%

---


# Acesso antecipado - Notas de versão da Adobe Experience Cloud - junho de 2020

![Banner](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. Ele também destaca a nova documentação, cursos de treinamento e tutoriais em vídeo para ajudá-lo a aproveitar ao máximo o Experience Cloud.

>[!IMPORTANT]
>
>Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.

>[!NOTE]
>
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras.

**Data de lançamento: 18 de junho de 2020**

As datas de lançamento do produto podem variar. Verifique novamente com frequência se há atualizações.

Última atualização: **15 de junho de 2020**

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Orquestração da jornada](#journey-orch)
* [Analytics](#analytics) (e [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/br/primetime/user-guide.html) (links para a página de ajuda do Primetime)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insight da comunidade e treinamento conduzido por instrutores.

## ![Ícone](/assets/adobe.png) Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

Lançado: **21 de maio de 2020**

**Novidades**

* Usando a Adobe ID, é possível assinar notificações de eventos com mais granularidade até a oferta de produtos e complementos. Para ajudar você a configurar a assinatura mais rápido, o processo de assinatura automática agora recomenda uma seleção de produtos e ofertas de acordo com os direitos do seu produto. Isso deve reduzir o número de emails recebidos e fornecer notificações mais relevantes na sua caixa de entrada. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Experiência do usuário de assinatura e notificação aprimorada | <ul><li>[!DNL Marketo Engage] as localizações regionais agora são filtradas de acordo com a lista de ofertas de produtos selecionadas.</li><li>[!DNL Marketo Engage] as notificações por email são relevantes para as preferências de região, local e ambiente do usuário.</li></ul> |
| Confirmação de assinatura do evento | <ul><li>Agora você pode obter uma confirmação por email ao assinar atualizações de evento único em andamento.</li></ul> |
| Melhorias na utilização da navegação global | <ul><li>Experiência do usuário consistente com o `Adobe.com` no menu de navegação de nível superior.</li></ul> |

## ![Ícone](/assets/ec_appicon_24.png) Interface da Experience Cloud {#ecloud}

Atualizações gerais na interface do Experience Cloud.

**Domínio de produto unificado**

A Adobe está atualizando o domínio e o cabeçalho da interface para unificar e melhorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar a experiência de maneiras pequenas, mas importantes. Eles não alterarão seus fluxos de trabalho atuais.

As atualizações incluem:

* Novos URLs de aplicativo: `experience.adobe.com/<application name>`:
   * Todos os produtos acabarão por adotar esse padrão de URL. Procure novos URLs para se tornarem efetivos durante o mês.
   * Compatibilidade de navegador: os navegadores compatíveis incluem [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versões mais recentes). **Observação:** Embora a interface de Experience Cloud seja compatível com esses navegadores, os aplicativos individuais podem não suportar todos os navegadores. (Por exemplo, o [Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/admin/sys-reqs.html) não é compatível com o [!DNL Opera] e o [Target](https://docs.adobe.com/help/pt-BR/target/using/implement-target/before-implement/supported-browsers.html) não é compatível com o [!DNL Safari].)
   * (Somente para o [!DNL Safari]) A alteração de domínio pode causar problemas de cookie no [!DNL Safari]. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do [!DNL Safari], os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Experience Cloud poderá funcionar nesse novo domínio.
* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do produto aprimorada: a [!UICONTROL Experience League] está integrada ao produto para que a pesquisa de ajuda também inclua resultados de fóruns da comunidade e conteúdo em vídeo. Essa alteração simplifica o acesso a mais conteúdo e ajuda a aproveitar ao máximo a Experience Cloud. Além disso, clique em **[!UICONTROL Ajuda]** > **[!UICONTROL Feedback]** para relatar problemas ou compartilhar suas ideias com a Adobe.

Os aplicativos a seguir usam o novo domínio experience.adobe.com:

| Aplicativo ou serviço | Domínio |
| -----------| ---------- |
| Página inicial da Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Gerenciamento de jornada | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Painel de controle do Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribuição de software | `experience.adobe.com/downloads` |
| Ferramenta de administração (beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Quadro e coleções]**, um filtro legado no seletor de [!UICONTROL Ativos da Experience Cloud], será descontinuado.

## ![Ícone](/assets/experience_platform_appicon_24.png) da Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

Data de lançamento: **10 de junho de 2020**

[!DNL Adobe Experience Platform] inclui os seguintes novos recursos:

* **Área de trabalho da ciência de dados:** O [!DNL JupyterLab Launcher] agora inclui um [!DNL Python] notebook para aprendizado de máquina em tempo real (Alpha).
* **Segmentação:** Um campo de data de aniversário para funções de data foi adicionado, permitindo que os usuários avaliem datas sem o ano.
* **Fontes:** Novos conectores de origem para [!DNL Apache HDFS] e [!DNL Couchbase].

Para obter mais informações sobre esses recursos, consulte as notas [de versão do](https://docs.adobe.com/content/help/pt-BR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)Experience Platform.

### Informações adicionais sobre a versão da Experience Platform

* [Notas de versão da Experience Platform Launch](https://docs.adobe.com/content/help/pt-BR/launch/using/intro/release-notes/current.html)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/br/security.html) (Todos os produtos da Adobe)

### Novos cursos e tutoriais de Experience Platform {#tutorials-plat}

| Conteúdo | Tipo de conteúdo | Descrição |
| -----------| ---------- | ---------- |
| [Introdução ao Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | Curso | Saiba como o Adobe Experience Platform ajuda a fornecer a experiência certa, transformando seus dados em perfis robustos de clientes em tempo real e insights orientados por AI que você pode ativar em cada canal. Este curso de introdução oferece uma visão geral dos recursos do Experience Platform, casos de uso, relacionamento com a Adobe Experience Cloud, arquitetura básica, interface e funções do projeto. |
| [Introdução ao SDK da Web e à Rede de Borda](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | Tutorial em vídeo | Uma visão geral do SDK do Adobe Experience Platform e da Edge Network. O Experience Platform Web SDK é uma biblioteca JavaScript do lado do cliente que permite que os clientes usem uma biblioteca JavaScript, um tipo de beacon, um fluxo de dados, um e um destino do lado do servidor para enviar dados para todos os aplicativos Adobe e para destinos de terceiros. |
| [Demonstração do SDK da Web e da rede Edge](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | Tutorial em vídeo | Assista ao SDK da Web Adobe Experience Platform e à Rede Edge em ação, com uma única chamada para a Adobe enviar dados para Experience Platform, Analytics, Audience Manager e Público alvo. |
| [Demonstração da Platform de dados do cliente em tempo real](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | Tutorial em vídeo | Saiba como a CDP em tempo real é usada para coletar dados de várias fontes. Você pode unir esses dados em um único perfil de cliente em tempo real e ativá-los para criar experiências personalizadas de clientes. |

## ![Ícone](/assets/experience_platform_appicon_24.png) do Journey Orchestration {#journey-orch}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

### Última versão

A versão do segundo trimestre foi publicada. [Saiba mais](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html)

### Novos cursos e tutoriais de Journey Orchestration {#jo-tutorials}

| Conteúdo | Tipo de conteúdo | Descrição |
| -----------| ---------- | ---------- |
| [Introdução ao Journey Orchestration para administradores](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | Curso | Saiba como configurar e usar o Journey Orchestration. Este curso aborda os principais conceitos e as etapas de configuração necessárias para permitir a orquestração de uma jornada. Saiba como criar, publicar e como relatar e analisar suas jornadas orquestradas. |
| [Introdução ao Journey Orchestration para usuários empresariais](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | Curso | Saiba como configurar e usar o Journey Orchestration. Este curso aborda os principais conceitos. Você aprenderá a criar, publicar, relatar e analisar suas Jornadas orquestradas. |

### Recursos adicionais para a Orquestração de jornadas

[Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Updated **June 10, 2020**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Novos recursos no Media Analytics](#media-aa)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [Novos cursos e tutoriais do Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- |-------|
| QI de atribuição: Atribuição algorítmica | 18 de junho de 2020 | O modelo de Atribuição  algorítmica no Analysis Workspace usa técnicas estatísticas para determinar dinamicamente a alocação ideal de crédito para a métrica selecionada. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| QI de atribuição: Janelas de pesquisa personalizadas | 18 de junho de 2020 | Agora você pode configurar qualquer modelo de atribuição no IQ [!UICONTROL de] Atribuição para incluir pontos de contato de até 90 dias antes do período de tempo do relatórios. Isso normalmente aumentará a precisão da atribuição para eventos que ocorrem no início do período do relatórios, contabilizando as interações que ocorreram no(s) mês(es) anterior(es). [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Funções de projeto para projetos compartilhados da Workspace | 18 de junho de 2020 | Ao compartilhar um projeto da Workspace, você pode colocar recipient em uma das três funções do projeto, dependendo da experiência do projeto que deseja que eles tenham: Editar, Duplicado e Visualização. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projetos da área de trabalho somente para Visualização | 18 de junho de 2020 | Os projetos do Workspace podem ser compartilhados somente para usuários como &quot;Pode visualização&quot;. Quando um recipient Visualização abre o projeto compartilhado, ele recebe uma experiência mais restritiva do projeto, sem trilho restante e interações limitadas. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Capacidade de co-editar projetos do Workspace | 18 de junho de 2020 | Recipient adicionados à função &quot;Pode editar&quot; podem ser salvos em um projeto que foi compartilhado para eles. Isso se estende a administradores e não administradores. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Painel em branco atualizado no Workspace | 18 de junho de 2020 | O painel em branco no Workspace agora inclui painéis e visualizações, proporcionando uma maneira mais simples de escolher o fluxo de trabalho de análise que funciona melhor para você. |
| Domínios primários disponíveis na RDC da China | 18 de junho de 2020 | Permite que os clientes com um `.cn` domínio solicitem um domínio próprio para uso dentro da China Continental. (Documentação disponível com a compra do SKU &quot;Otimização do desempenho da China&quot;.) |
| Painel Quick Insights no Espaço de trabalho | 25 de junho de 2020 | O painel Quick Insights fornece orientação para não analistas e novos usuários do Analysis Workspace para saber como responder a perguntas comerciais de forma rápida e fácil. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Painel Analytics for Target no Espaço de trabalho | 25 de junho de 2020 | O painel Analytics for Target (A4T) permite que você analise suas atividades e experiências Adobe Target, com incentivo e confiança, no Analysis Workspace. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- |-----|
| QI de atribuição: [!UICONTROL Atribuição algorítmica] | 18 de junho de 2020 | O modelo de Atribuição  algorítmica no [!UICONTROL Analysis Workspace] usa técnicas estatísticas para determinar dinamicamente a alocação ideal de crédito para a métrica selecionada. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| QI de atribuição: Janelas de pesquisa personalizadas | 18 de junho de 2020 | Agora você pode configurar qualquer modelo de atribuição no QI [!UICONTROL de] Atribuição para incluir pontos de contato de até 90 dias antes do período de tempo do relatórios. Isso normalmente aumentará a precisão da atribuição para eventos que ocorrem no início do período do relatórios, contabilizando as interações que ocorreram no(s) mês(es) anterior(es). [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Suporte para detecção de [!UICONTROL anomalias] | 18 de junho de 2020 | [!UICONTROL A Detecção] de anomalias fornece um método estatístico para determinar como uma determinada métrica foi alterada em relação aos dados anteriores. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Funções de projeto para projetos compartilhados da [!UICONTROL Workspace] | 18 de junho de 2020 | Ao compartilhar um projeto da [!UICONTROL Workspace] , você pode colocar recipient em uma das três funções do projeto, dependendo da experiência do projeto que você deseja que eles tenham: Editar, Duplicado e Visualização. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projetos somente para Visualização do [!UICONTROL Workspace] | 18 de junho de 2020 | [!UICONTROL Os projetos do Workspace] podem ser compartilhados com os usuários como _[!UICONTROL Pode Visualização]_somente. Quando um recipient Visualização abre o projeto compartilhado, ele recebe uma experiência de projeto mais restritiva, sem trilho restante e interações limitadas.[Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Capacidade de co-editar projetos do [!UICONTROL Workspace] | 18 de junho de 2020 | Recipient adicionados à função _[!UICONTROL Pode editar]_podem ser salvos em um projeto que foi compartilhado para eles.[Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Painel Quick Insights no [!UICONTROL Espaço de trabalho] | 25 de junho de 2020 | O painel Quick Insights fornece orientação para não analistas e novos usuários do [!UICONTROL Analysis Workspace] para saber como responder a perguntas comerciais de forma rápida e fácil. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/panels/quickinsight.html) |

### Novos recursos no [!UICONTROL Media Analytics] {#media-aa}

Data de atualização: **29 de maio de 2020**

**Rastreamento de estado do player:** os clientes do [!UICONTROL Media Analytics] podem capturar a interação do visualizador durante a reprodução usando um conjunto padrão de variáveis de solução para tela cheia, legendas ocultas, mudo, picture-in-picture e em foco. Você também tem flexibilidade para criar estados personalizados do player. As variáveis de Rastreamento de estado do player estão disponíveis para relatórios no [!UICONTROL Analysis Workspace]. Esse recurso exige um dos seguintes:

* Media [!DNL JavaScript] SDK 3.0 ou superior
* Para uso com o SDK [!DNL Adobe Experience Platform] (AEP):
   * [!UICONTROL Extensão do Media Analytics] (para Web): [!UICONTROL Adobe Media Analytics] (SDK 3.x) for Audio and Video v1.0 ou superior
   * [!UICONTROL Extensão do Media Analytics] (para dispositivos móveis): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 ou superior
* [!UICONTROL Coleção de mídia]

Consulte [Sobre o rastreamento do estado do player](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/player-state-tracking/player-state-overview.html).

### Correções no Adobe Analytics {#aa-fixes}

* Correção de um problema que fazia com que os segmentos com pesquisas multibyte para determinados conjuntos de relatórios não correspondessem a nada. Agora eles vão corresponder às cordas corretas. (AN-220043)
* Correção de um problema no qual o Filtro [!UICONTROL de] item em [!UICONTROL Relatórios e Analytics] não funcionava. (AN-206132)
* Corrigido o tempo de resposta lento na interface de Projetos  agendados. (AN-214837)
* Correção de um problema com a API de Relatórios do Analytics 2.0 que gerava um erro de intervalo de datas. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. Isso ocorria quando uma ocorrência sem valor para a dimensão (por exemplo, Pagename) era seguida no mesmo segundo. (AN-211074)
* Correção de um problema em que os usuários não conseguiam acessar projetos [!UICONTROL do Workspace] compartilhados com eles. (AN-217561)
* Corrigido o problema que fazia com que chaves não fossem classificadas pelo Construtor [!UICONTROL de regras de]classificação. (AN-221538)
* Correção de um problema no qual o Uso [!UICONTROL de chamada do] servidor não relatórios dados de uso. (AN-210452)
* Correção de problemas com segmentos publicados do Adobe Analytics sem dados no Audience Manager. (AN-220208, AN-220659)
* Correção de um problema que fazia com que os relatórios mostrassem dados, mas os registros [!UICONTROL de Feeds] de dados informassem &quot;Nenhum dado de Data warehouse&quot;. (AN-220784, AN-220858)
* Correção de problemas que impedia a inicialização do [!UICONTROL Ad hoc analysis] a partir do `experiencecloud.com` domínio. (AN-219680, AN-221629)
* Correção de problemas com o uso da tecla de atalho &quot;Ctrl (ou Command) + C&quot;. (AN-221101, AN-221537)
* Correção de um problema com a página de ativação do [!UICONTROL Activity Map] . (AN-222029, AN-221242)
* Correção de um problema que impedia a adição de um ponto de toque no meio de uma visualização de [!UICONTROL Fallout] . (AN-221648)

#### Outras correções do Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Migração para o domínio de produto unificado | Data efetiva: 28 de maio de 2020 | A migração para um domínio de produto unificado do Adobe Analytics, que começou em janeiro de 2020, terminou em 28 de maio de 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist (formerly, allowlist) `omniture.com` as a third-party cookie. Quando a migração completa da arquitetura for concluída (em breve), você será notificado por meio das notas de versão e essa etapa permitida não será mais necessária. [Esta](https://helpx.adobe.com/br/analytics/kb/adobe-ip-addresses.html) é uma lista completa de domínios e endereços IP recomendados que você deve permitir.<br>Se sua organização bloquear cookies de terceiros, entre em contato com o Atendimento ao cliente para recuperar o acesso ao Adobe Analytics. |
| Nova página de aterrissagem padrão do Adobe Analytics | Data efetiva: 18 de junho de 2020 | Em 18 de junho de 2020, a landing page padrão do Adobe Analytics será alterada de [!UICONTROL Relatórios] para [!UICONTROL Espaço de trabalho]. Essa alteração ocorrerá para qualquer usuário que não tenha definido uma landing page personalizada anteriormente. |
| Tecnologia de terceiros permitida | 12 de março de 2020 (data de efetivação) | O Adobe Analytics começou a utilizar tecnologias de terceiros para o gerenciamento da implantação de recursos e suporte no produto. Os URLs a seguir devem ser adicionados a qualquer firewall de rede que permita o acesso completo aos recursos:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 21 de maio de 2020 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. Os URLs a seguir devem ser adicionados a qualquer lista permitida de firewall de rede necessária:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Alteração na forma como [!UICONTROL Entradas/Saídas] são calculadas no [!UICONTROL Espaço de trabalho] | 7 de abril de 2020 | A partir de março de 2020, mudamos no [!UICONTROL Analysis Workspace] a forma como o valor _Nenhum_ interage com [!UICONTROL Entradas/Saídas]. Como agora é possível ativar ou desativar o valor _Nenhum_ no [!UICONTROL Analysis Workspace], aplicamos o valor _Nenhum_ após a entrada ou saída, enquanto que (para eVars) costumava ser aplicado antes da entrada ou saída. Por exemplo, suponha que a primeira ocorrência de uma visita não tenha valor para eVars, mas a segunda ocorrência tem. No [!UICONTROL Reports &amp; Analytics], a primeira ocorrência será exibida como _Não especificado_ para a Entrada, mas no [!UICONTROL Analysis Workspace] será exibida como o valor na segunda ocorrência. |
| EOL do **[!UICONTROL Arquivo do painel]** | 27 de março de 2020 | A configuração **[!UICONTROL Exibir arquivo]** em **[!UICONTROL Gerenciar painéis]** no [!UICONTROL Reports &amp; Analytics] não estará mais disponível a partir de março de 2020. |
| Fim da vida útil - APIs antigas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Cingapura, não apoiaremos mais a intermediação de dados entre Londres ou Cingapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fim da vida útil do Ad Hoc Analysis | 6 de agosto de 2018 | A Adobe anunciou a intenção de encerrar a vida útil do Ad Hoc Analysis. Uma data para o fim da vida útil será compartilhada assim que estiver disponível. Para obter mais informações, visite [Descubra a Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### Novos cursos e tutoriais da Analytics {#tutorials-analytics}

Novos cursos, vídeos de tutoriais e artigos no Analytics e Customer Journey Analytics.

| Conteúdo | Tipo de conteúdo | Descrição |
| -----------| ---------- | ---------- | 
| [Introdução ao Customer Journey Analytics para usuários](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | Curso | Neste curso, você aprenderá a usar o Customer Journey Analytics (CJA) para analisar dados de várias fontes de dados diferentes. Você aprenderá sobre as diferenças entre o Adobe Analytics e o Customer Journey Analytics e como os dados são tratados no CJA. Depois de realizar esse curso, você deve ser capaz de criar e personalizar visualizações entre canais para uma melhor compreensão de seus clientes. |
| [Introdução ao Customer Journey Analytics para administradores](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Curso | Saiba como configurar e usar o [!UICONTROL Journey Orchestration]. Este curso aborda os principais conceitos e as etapas de configuração necessárias para habilitar a orquestração de uma jornada. Você aprenderá a criar, publicar e a relatar e analisar suas Jornadas orquestradas. |
| [Introdução à Customer Journey Analytics para engenheiros de dados](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | Curso | Neste curso, você aprenderá sobre os dados que entram no Customer Journey Analytics e como eles afetam os relatórios do analista. Este curso baseia-se no seu conhecimento geral sobre o Adobe Experience Platform. |
| [Introdução ao Customer Journey Analytics para administradores](https://video.tv.adobe.com/v/34349?captions=por_br) | Tutorial em vídeo | Um vídeo de introdução ao Customer Journey Analytics para administradores. |
| [Implementação da Analytics guiada](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | Curso | Neste curso, você aprenderá a implementar o Adobe Analytics, a entender os conceitos da Analytics, a criar um plano e a implementar o Adobe Analytics usando o Experience Platform Launch. |
| [Fundamentos da Adobe Analytics para líderes](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | Curso | Neste curso, saiba mais sobre os fundamentos da Analytics e como a Analysis Workspace pode mudar sua empresa. Saiba como descobrir insights com o Adobe Sensei, ouvir depoimentos de clientes e assistir aos destaques de especialistas do setor no Summit 2019. |
| [Introdução ao Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | Curso | Saiba como começar a usar o Analysis Workspace. Crie seu primeiro projeto, aprenda a definir intervalos de datas, aplicar segmentos e compartilhar e colaborar em projetos. |
| [Adobe Analytics painel Scorecard Builder](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | Tutorial em vídeo | Neste vídeo, saiba como criar e compartilhar [!UICONTROL Scorecards] no [!UICONTROL Analysis Workspace] para ser exibido nos painéis da Adobe Analytics (aplicativo móvel). |
| [Experiência no aplicativo dos painéis Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | Tutorial em vídeo | Neste vídeo, saiba como usar painéis da Adobe Analytics (aplicativo móvel) para acessar e visualização [!UICONTROL Scorecards] criados por você ou compartilhados com você. |

#### Recursos de ajuda do Analytics

* [Tutoriais do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentação de produto do Adobe Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/landing/home.html)

## ![Ícone](/assets/audience-manager.png) do Adobe Audience Manager {#aam}

Novos recursos, correções, documentação e tutoriais no Audience Manager.

Updated **June 10, 2020**

### Atualizações da interface do usuário

O Audience Manager está lançando atualizações no domínio e na barra de cabeçalho para melhorar sua experiência e se unificar com outros aplicativos da Experience Cloud.

* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do usuário aprimorada, incluindo artigos em destaque e vídeos relevantes pára o contexto no menu Ajuda.
* Capacidade de fornecer feedback sobre tíquetes de suporte a Experience Platform e arquivos.
* Um novo padrão de URL mais simples. Atualize seus marcadores para o novo url: `experience.adobe.com/audience-manager`.

Essas atualizações estão disponíveis somente para usuários que fazem logon com a Adobe ID. Para alternar para um logon com a Adobe ID, consulte [Gerenciar usuários e produtos da Experience Cloud](https://docs.adobe.com/content/help/pt-BR/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Novos recursos e correções no Adobe Audience Manager

| Recurso | Descrição |
| -----------| ---------- |  
| [Plug-in de Audience Manager para IAB TCF v2.0 ](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.translate.html) | Continuando com o foco da Adobe na privacidade por design, estamos atualizando o Plug-in do Audience Manager para o TCF da IAB para a versão 2.0 da Estrutura de Transparência e Consentimento (TCF) do IAB, a partir de 10 de junho de 2020. Os clientes que implementaram o Plug-in Audience Manager para IAB TCF devem atualizar para a versão 2.0 até 15 de agosto de 2020, para continuar usando o recurso. Após 15 de agosto de 2020, a versão 1.1 será substituída e não será mais suportada. |

**Correções**

* Atualização dos Termos e condições [!UICONTROL do] Audience Marketplace para refletir os requisitos legais em regiões geográficas específicas. (AAM-54518)
* Corrigido um problema no qual acessar a página [!UICONTROL Características] a partir de marcadores resultava em um erro 404. (AAM-54768)
* Correção de um problema em que a API de Atualização de destino expirava ao recuperar modelos [!UICONTROL algorítmicos]. (AAM-54342)
* Os usuários agora podem ver um indicador de precisão de classificação de modelo para [!UICONTROL Smart Personas]. (AAM-54847)
* Correção de um problema em que pressionar Enter após adicionar uma expressão característica removeria a expressão em vez de salvá-la. (AAM-54210)
* Correção de um problema em que as chamadas para o método GET da API [!UICONTROL Características] falhavam para usuários que não tinham a permissão VISUALIZAÇÃO_MODELS. (AAM-53104)
* Correção de um problema em que os usuários não podiam excluir Modelos [!UICONTROL algorítmicos] que contivessem Características [!UICONTROL da pasta]. (AAM-50192)
* expressões de traços longos agora envolvem várias linhas. (AAM-54972)
* Correção de um problema em que os usuários com permissões somente leitura podiam visualizar o botão [!UICONTROL Criar novo] nas páginas de modelos algorítmicos. (AAM-54889)
* Correção de um problema que fazia com que o indicador de carregamento dos relatórios [!UICONTROL Geral] e [!UICONTROL Tendência] continuasse girando após a conclusão do download CSV. (AAM-54571)
* Correção de um problema em que os usuários não podiam adicionar traços em massa a segmentos no Construtor [!UICONTROL de segmentos]. (AAM-55033)
* Várias melhorias de acessibilidade na interface. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### Novos cursos e tutoriais de Audience Manager {#tutorials-aam}

| Conteúdo | Tipo de conteúdo | Descrição |
| -----------| ---------- | ---------- |  
| [Introdução ao Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | Curso | Este curso ensina o básico do Audience Manager e os problemas que você pode resolver usando-o. Saiba mais sobre casos de uso comuns e termos e conceitos-chave do Audience Manager. |
| [Introdução à identidade no Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | Tutorial em vídeo | Saiba como o Adobe Audience Manager gerencia a identidade, incluindo perfis internos e união de perfis, bem como sincronização de ID com parceiros. |
| [Como entender e configurar o destino baseado em pessoas do LinkedIn](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | Curso | Este vídeo o orienta pelos conceitos e etapas para criar um Destino baseado em pessoas para o LinkedIn. Ele se baseia nos vídeos e na documentação adicionais relacionados aos Destinos baseados em pessoas. |
| [Criando características baseadas em regras](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | Tutorial em vídeo | Saiba como usar o Construtor de [!UICONTROL características] na interface do Audience Manager para criar uma característica baseada em regras, permitindo capturar atividades em tempo real em perfil. |
| [Ativação do plug-in Audience Manager para IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | Tutorial em vídeo | Saiba como habilitar o Plug-in Audience Manager para IAB TCF. Habilitar este plug-in é fácil se você estiver usando o Adobe Experience Platform Launch. |
| [Demonstração do plugin Audience Manager para IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | Tutorial em vídeo | Neste vídeo, veja como os cookies e os beacons do Serviço de ID da Experience Cloud e as soluções são afetados pelas seleções de opções do usuário IAB. |

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Atualizações do produto

* **AEM 6.5.5.0**

   AEM 6.5, Service Pack 5 (6.5.5.0, lançado em 04 de junho de 2020) é uma atualização importante que inclui novos recursos, melhorias essenciais solicitadas pelo cliente e desempenho, estabilidade, melhorias de segurança, lançadas desde a disponibilização geral do AEM 6.5 em abril de 2019.

   * [Notas de versão](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [Resultados da versão do AEM Forms](https://helpx.adobe.com/br/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack (6.4.8.1 lançado em 4 de junho de 2020) é uma atualização importante que inclui várias correções internas e de clientes desde a disponibilização geral do AEM 6.4, Service Pack 8 (6.4.8.0) em março de 2020.

   * [Notas de versão](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Resultados da versão do AEM Forms](https://helpx.adobe.com/br/aem-forms/kb/aem-forms-releases.html)

### Autoajuda

* **AEM como um Cloud Service**

   Novidades do AEM como Cloud Service?

   Os destaques incluem:

   * Estrutura de integração de comércio do AEM Sites.
   * Tags inteligentes aprimoradas e novidades na experiência de treinamento orientada pela interface do usuário.
   * Suporte do Adobe Asset Link para o Adobe Xd.
   * AEM Assets suporte a Dynamic Media 3D.
   * As novas melhorias de autoatendimento reduzem as dependências da Adobe para operações de caixa de proteção.
      * O suporte aprimorado à caixa de proteção de autoatendimento no Cloud Manager permite que os usuários autorizados excluam todos os ambientes em uma caixa de proteção e recebam créditos.
      * Os ambientes da caixa de proteção de hibernação automática &quot;hibernam&quot; automaticamente as caixas de proteção após um período de inatividade. Os clientes podem acionar ativamente a &quot;deshibernação&quot;.
   * Ferramentas de Transição para suportar a aceleração da nuvem
   Com o objetivo de reduzir o tempo e o custo para a transição, de um local para outro, duas ferramentas de transição foram lançadas este mês. Essas ferramentas são projetadas para automatizar algumas das principais tarefas durante o processo de transição e, portanto, reduzir o esforço geral. .

   1. [O uso da Ferramenta](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) de transferência de conteúdo (disponível no SD) simplifica a atividade de transferência de conteúdo e a torna escalável. Com uma interface de usuário fácil de usar, a ferramenta é autoatendimento para clientes e parceiros existentes (no local/AMS) que estão fazendo a transição para o AEM como Cloud Service.
   1. [Ferramenta AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) (Open-source) para automatizar a conversão de configurações AMS Dispatcher em configurações Cloud Service Dispatcher.
   [Notas de versão do AEM como Cloud Service 2020.6.0](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   Ferramentas de Transição:

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Componentes principais**

   A versão 2.9.0 dos Componentes principais apresenta integração com a [Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) e um novo Componente de barra de progresso, e agora está disponível junto com a documentação [de](https://docs.adobe.com/content/help/pt-BR/experience-manager-core-components/using/introduction.html) criação e os detalhes do [desenvolvedor e o download do projeto disponível no GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Mudar para o AEM como um Cloud Service**

   [Mover para o AEM como um Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/home.html) descreve a jornada de transição recomendada para um cliente AEM que está mudando para o Cloud Service. O objetivo desta documentação é fornecer aos clientes informações, orientação e práticas recomendadas para ajudá-los a se preparar para essa transição e tornar essa jornada estruturada e previsível.

   Uma das ferramentas de Transição da nuvem - Ferramenta de transferência de conteúdo foi lançada. [A Ferramenta](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) de transferência de conteúdo é desenvolvida pela Adobe e pode ser usada para mover o conteúdo existente de uma instância de AEM de origem (local ou AMS) para a instância de Cloud Service de AEM de público alvo de .

   Uma das Ferramentas de refatoração de código - AEM Dispatcher Converter foi lançada. [O AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) é uma ferramenta para converter as configurações existentes do AEM Dispatcher para o AEM como configurações do Cloud Service Dispatcher e está disponível.

* **Acessibilidade e diretrizes do WCAG 2.1**

   Atualizações em relação às Diretrizes do WCAG 2.1:

   * [Adobe Experience Manager as a Cloud Service e as diretrizes de acessibilidade na Web](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [Um guia rápido para a WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [Criação de conteúdo acessível (Conformidade com o WCAG 2.1)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **Informativos do AEM**

   O informativo do AEM disponibilizado pela Experience League foi projetado para ajudar você a usar o AEM e obter vantagens desde o início. Este é o informativo mais recente:

   * [Volume 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): o Experience Manager agora está disponível como um serviço na nuvem.
   * [Assine](https://adobeeventsonline.com/AEM/2017/NL/Optin/) o informativo Experience Insider.
   * Visualize arquivos do informativo na seção [Recursos do AEM](https://helpx.adobe.com/br/support/experience-manager/6-5.html) na página Aprendizagem e suporte do Adobe Experience Manager 6.5.

### **Comunidade**

* **Discussão da comunidade do AEM**

   Agora você pode ver todos os anúncios do AEM e referências interessantes a blogueiros internos e externos em um único lugar. Consulte a seção [Discussão da comunidade do AEM.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Novos cursos e tutoriais de Experience Manager

| Conteúdo | Tipo de conteúdo | Descrição |
| -----------| ---------- | ---------- |
| [Introdução ao Adobe Asset Link para usuários comerciais](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | Curso | Neste curso, aprenda a usar os recursos e os recursos do Adobe Asset Link para alimentar seu design criativo com conteúdo armazenado nos ativos Adobe Experience Manager. O curso aborda tudo, desde como iniciar o link de ativos da adobe, operações básicas de ativos, opções de pesquisa e navegação e como colaborar com outros usuários de forma eficiente. |
| [Introdução aos AEM Assets para usuários comerciais](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | Curso | Saiba como começar a usar AEM Assets para usuários empresariais. Explore as noções básicas de AEM Assets, recursos de colaboração, pesquisa, organização de ativos e download de ativos e suas execuções. |
| [Introdução aos AEM Sites para usuários empresariais](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | Curso | Saiba como usar os principais recursos e recursos do AEM Sites para gerenciar as páginas da Web de sua organização. O curso aborda tudo, desde uma introdução a AEM Sites, conceitos básicos de criação, recursos de criação avançados e recursos de gerenciamento de página. |
| [Estrutura de projetos do AEM](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Artigo | Descreve as alterações necessárias aos projetos do Adobe Experience Manager Maven para que sejam compatíveis com o AEM Cloud Service. |
| [Modelos Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | Tutorial em vídeo | Saiba mais sobre como depurar o AEM como uma inicialização rápida local do SDK do Cloud Service usando o console da Web Sling Models. |
| [Componentes do console da Web do AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | Tutorial em vídeo | Saiba mais sobre como depurar o AEM como uma inicialização rápida local do SDK do Cloud Service usando o console da Web Componentes. |
| [Depuração do Início rápido local do SDK do AEM usando registros](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Tutorial em vídeo | Saiba mais sobre como depurar o AEM como uma inicialização rápida local do SDK do Cloud Service usando o console da Web Pacotes. |
| [Depuração remota do AEM como uma inicialização rápida local do SDK do Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | Tutorial em vídeo | Saiba mais sobre a depuração remota do Java no seu IDE, permitindo que você passe pela execução do código ativo no AEM para entender o fluxo de execução exato. |
| [Configuração de tags inteligentes](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | Tutorial em vídeo | Instruções passo a passo para integrar o Adobe Experience Manager (AEM) ao Serviço de conteúdo inteligente usando a E/S da Adobe. |
| [Geração em lote de documentos](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | Artigo | Saiba mais sobre como usar a API de lote para produzir várias comunicações interativas a partir de um modelo. |
| [Criando documento de canal de impressão em AEM Forms](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | Artigo | Aprenda as etapas necessárias para criar uma comunicação interativa para o canal de impressão. |
| [Acessar o Adobe Asset Link](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | Tutorial em vídeo | Saiba mais sobre como acessar o conteúdo armazenado nos ativos Adobe Experience Manager (AEM Assets), sem sair dos aplicativos de desktop da Creative Cloud mais conhecidos. |
| [Visão geral do painel Link de ativos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | Tutorial em vídeo | O Adobe Asset Link fornece aos usuários criativos a capacidade de navegar, pesquisar, sair e fazer check-in de ativos armazenados no AEM Assets usando o painel no aplicativo no InDesign, no Photoshop e no Illustrator. Seja apresentado à interface do usuário do painel Link de ativos da Adobe e seus recursos. |
| [Pesquisa de ativos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | Tutorial em vídeo | Os usuários criativos podem pesquisar ativos armazenados em AEM Assets usando palavras-chave ou realizar uma pesquisa em um local específico. |
| [Controle de versão e comentários do arquivo](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | Tutorial em vídeo | Usando o painel Adobe Asset Link, você pode acessar detalhes do arquivo para ativos em AEM Assets, como miniatura, metadados básicos e versões no painel. |
| [Check-in Check-out](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | Tutorial em vídeo | O Adobe Asset permite que você faça check-out de AEM Assets diretamente do aplicativo criativo no qual você está trabalhando e pode começar a fazer edições imediatamente. |
| [Renderização Somente para Posicionamento para AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | Tutorial em vídeo | Explore como criar e usar uma representação Somente disposição para ativos AEM (FPO). |
| [Inserir cópia](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | Tutorial em vídeo | Saiba como usar ativos de AEM Assets usando a operação Inserir cópia. |
| [Baixar e carregar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | Tutorial em vídeo | Saiba como baixar e fazer upload de arquivos de ativos de e para AEM Assets usando o painel Link de ativos. |
| [Arquivos e coleções](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | Tutorial em vídeo | Saiba como acessar arquivos e coleções do AEM Assets de forma rápida e fácil no painel Link do ativo. |
| [Baixar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | Tutorial em vídeo | Saiba como baixar ativos e suas execuções no computador local para uso e compartilhamento. |

### Recursos adicionais

* [AEM como um Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
* [Página inicial de aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Página inicial de aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Página inicial de aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página inicial de aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/home.html)
* [Notas de versão do Dynamic Media](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Novas versões de produtos

[A versão](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html) Adobe Campaign Classic 20.2 inclui:

* _Suporte da Emoticon_ - _Azure Synapse FDA Connector_ - _Novas regras de privacidade_
* Painel de controle da Campanha: [Monitoramento ativo de perfis](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### Cursos e tutoriais da nova campanha

| Conteúdo | Tipo de conteúdo | Descrição |
| -----------| ---------- | ---------- |  
| [Introdução ao Adobe Campaign Standard para usuários comerciais](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Curso | Saiba como navegar na interface, trabalhar com delivery e criar e gerenciar dados de recipient. |
| [Instale e configure o cliente Adobe Campaign](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Vídeo | Saiba como baixar e instalar o console do Adobe Campaign Client, criar e gerenciar suas conexões com vários ambientes e verificar o acesso ao console do Adobe Campaign Client |

### Recursos de ajuda
* Adobe Campaign Standard: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/campaign-standard-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/overview.html) - [Planejamento de lançamento](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-planning.html) - [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/campaign-classic-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/documentation-updates.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html) - Como fazer vídeos para [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Novos recursos na Advertising Cloud DSP](#adcloud-dsp)
* [Novos recursos na Advertising Cloud Search](#adcloud-search)

### Novos recursos na Advertising Cloud DSP {#adcloud-dsp}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanha] Home | (Lançamento de 3 de junho) Novas métricas de posicionamento no nível da campanha com base no orçamento da campanha fornecido e no tempo decorrido estão disponíveis. |
| Previsão de posicionamento | (Lançamento de 3 de junho) Para disposições de CTV e vídeo com otimização de nível de posicionamento, as configurações de posicionamento agora incluem previsão para várias extensões de anúncio (15 s e 30 segundos). Eles também incluem previsões para o inventário VAST e VPAID. |
| Otimização de CPA/ROAS | (lançamento de 20 de maio) Os gerentes de Campanhas não precisam mais limitar novas colocações dentro dos pacotes para evitar a atribuição excessiva de orçamento. As disposições agora recebem uma alocação de orçamento dinâmica com base no desempenho do CPM ou CPA/ROAS. |

### Novos recursos na [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanhas] | A Microsoft Advertising (antigo Bing Ads) está substituindo as métricas de posição média após 30 de setembro de 2020. Em preparação, a partir de 11 de julho, as restrições baseadas na posição serão ignoradas e as condições baseadas na posição em qualquer tipo de restrição também serão ignoradas. |
| [!UICONTROL Insights de publicidade] | (Versão de 13 de junho) As seguintes informações foram removidas:<br/><br/><ul><li>Desempenho do Público alvo da Audiência (a versão mais recente)</li><li>Desempenho histórico (a versão mais recente)</li><li>Tipo de correspondência (a versão mais recente)</li><li>Auditoria de configurações (a versão mais recente)</li><li>Pré-publicação do portfólio (herdado)</li></ul><br/>Os insights restantes são versões herdadas e o rótulo _Herdado_ foi removido dos nomes. Além disso, os modos Live/Edit foram removidos. |

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Para ver as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ícone](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes ao se envolverem em todas as jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte as [!DNL Marketo] [notas de versão](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) para obter as informações mais recentes.

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
