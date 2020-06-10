---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: be2f2b5ad468ad63bfcb2fdd67d063203ac08654
workflow-type: tm+mt
source-wordcount: '5030'
ht-degree: 79%

---


# Notas de versão da Adobe Experience Cloud - Maio de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Esta página fornece novos recursos, correções e avisos importantes na [!DNL Adobe Experience Cloud]. As datas de lançamento da solução podem variar. Verifique com frequência para obter as atualizações mais recentes.

>[!NOTE]
>
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras.

**Data de lançamento: maio de 2020**

Última atualização: **4 de junho de 2020**

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Atualizado em 4 de junho de 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html) (links para a página de ajuda do Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/br/primetime/user-guide.html) (links para a página de ajuda do Primetime)

Precisa de ajuda? Visite [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) para encontrar cursos com curadoria da Adobe, documentação técnica, respostas rápidas, insight da comunidade e treinamento com instrutor.

## ![Ícone](/assets/adobe.png) Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

Data de lançamento: **21 de maio de 2020**

**Novidades**

* Usando a Adobe ID, é possível assinar notificações de eventos com mais granularidade até a oferta de produtos e complementos. Para ajudar você a configurar a assinatura mais rápido, o processo de assinatura automática agora recomenda uma seleção de produtos e ofertas de acordo com os direitos do seu produto. Isso deve reduzir o número de emails recebidos e fornecer notificações mais relevantes na sua caixa de entrada. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Experiência do usuário de assinatura e notificação aprimorada | <ul><li>[!DNL Marketo Engage] as localizações regionais agora são filtradas de acordo com a lista de ofertas de produtos selecionadas.</li><li>[!DNL Marketo Engage] as notificações por email são relevantes para as preferências de região, local e ambiente do usuário.</li></ul> |
| Confirmação de assinatura do evento | <ul><li>Agora você pode obter uma confirmação por email ao assinar atualizações de evento único em andamento.</li></ul> |
| Melhorias na utilização da navegação global | <ul><li>Experiência do usuário consistente com o `Adobe.com` no menu de navegação de nível superior.</li></ul> |

## ![Ícone](/assets/ec_appicon_24.png) Interface da Experience Cloud {#ecloud}

Atualizações gerais na interface da Experience Cloud.

**Domínio de produto unificado**

A Adobe está atualizando o domínio e o cabeçalho da interface para unificar e melhorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar a experiência de maneiras pequenas, mas importantes. Eles não alterarão seus fluxos de trabalho atuais.

As atualizações incluem:

* Novos URLs de aplicativo: `experience.adobe.com/<application name>`:
   * Todos os produtos acabarão por adotar esse padrão de URL. Procure novos URLs para se tornarem efetivos durante o mês.
   * Compatibilidade de navegador: os navegadores compatíveis incluem [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versões mais recentes). **Observação:** embora a interface da Experience Cloud seja compatível com esses navegadores, os aplicativos individuais podem não ser compatíveis com todos os navegadores. (Por exemplo, o [Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/admin/sys-reqs.html) não é compatível com o [!DNL Opera] e o [Target](https://docs.adobe.com/help/pt-BR/target/using/implement-target/before-implement/supported-browsers.html) não é compatível com o [!DNL Safari].)
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
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Painel de controle do Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Serviço Places | `experience.adobe.com/places` |
| Distribuição de software | `experience.adobe.com/downloads` |
| Ferramenta de administração (beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Quadro e coleções]**, um filtro legado no seletor de [!UICONTROL Ativos da Experience Cloud], será descontinuado.

## ![Ícone](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notas de versão para [!DNL Experience Platform,] incluir [!DNL Experience Platform Launch,] [!UICONTROL Orquestração de jornada], [!UICONTROL Ofertas], [!UICONTROL Pessoas], [!UICONTROL Places], [!UICONTROL Mobile Services] e boletins de segurança.

### Aprimoramentos na interface

Atualizado em: **15 de maio de 2020**

A [!DNL Adobe Experience Platform] está lançando atualizações no domínio e na barra de cabeçalho para melhorar a experiência e se unificar com outros aplicativos da Experience Cloud. As atualizações incluem:

* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do usuário aprimorada, incluindo artigos em destaque e documentação relevante para o contexto no menu Ajuda.
* Capacidade de fornecer feedback sobre a Experience Platform e os tíquetes de suporte a arquivos.

Consulte as [notas de versão da Experience Platform](https://docs.adobe.com/content/help/pt-BR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) para obter mais informações.

### Atributos do cliente - nova documentação

Atualizado em: **15 de maio de 2020**

* [Suporte a Atributos do cliente para CCPA](https://docs.adobe.com/content/help/pt-BR/core-services/interface/customer-attributes/ccpa.html) (Lei de Privacidade do Consumidor da Califórnia)
* [Suporte a Atributos do cliente para GDPR](https://docs.adobe.com/content/help/pt-BR/core-services/interface/customer-attributes/gdpr.html) (Regulamento Geral sobre a Proteção de Dados)

### Orquestração da jornada {#journey}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

* [Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html)
* [Notas de versão](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html)
* [Vídeos tutoriais](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Informações adicionais sobre a versão da Experience Platform

* [Notas de versão da Experience Platform Launch](https://docs.adobe.com/content/help/pt-BR/launch/using/intro/release-notes/current.html)
* [Notas de versão da Experience Platform](https://docs.adobe.com/content/help/pt-BR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/br/security.html) (Todos os produtos da Adobe)

## ![Ícone](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **June, 2020**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Novos recursos no Media Analytics](#media-aa)
* [Correções do Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)
* [Novos tutoriais do Analytics](#tutorials-analytics)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html)Geral - Data do Público alvo | Descrição |
| -----------| ---------- |-------|
| QI de atribuição: Atribuição algorítmica | 18 de junho de 2020 | O modelo de Atribuição  algorítmica na Área de trabalho da Análise usa técnicas estatísticas para determinar dinamicamente a alocação ideal de crédito para a métrica selecionada. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| QI de atribuição: Janelas de pesquisa personalizadas | 18 de junho de 2020 | Agora você pode configurar qualquer modelo de atribuição no IQ [!UICONTROL de] Atribuição para incluir pontos de contato de até 90 dias antes do período de tempo do relatórios. Isso normalmente aumentará a precisão da atribuição para eventos que ocorrem no início do período do relatórios, contabilizando as interações que ocorreram no(s) mês(es) anterior(es). [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Funções de projeto para projetos compartilhados da Workspace | 18 de junho de 2020 | Ao compartilhar um projeto da Workspace, você pode colocar recipient em uma das três funções do projeto, dependendo da experiência do projeto que deseja que eles tenham: Editar, Duplicado e Visualização. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projetos da área de trabalho somente para Visualização | 18 de junho de 2020 | Os projetos do Workspace podem ser compartilhados somente para usuários como &quot;Pode visualização&quot;. Quando um recipient Visualização abre o projeto compartilhado, ele recebe uma experiência mais restritiva do projeto, sem trilho restante e interações limitadas. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Capacidade de co-editar projetos do Workspace | 18 de junho de 2020 | Recipient adicionados à função &quot;Pode editar&quot; podem ser salvos em um projeto que foi compartilhado para eles. Isso se estende a administradores e não administradores. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Painel em branco atualizado no Workspace | 18 de junho de 2020 | O painel em branco no Workspace agora inclui painéis e visualizações, proporcionando uma maneira mais simples de escolher o fluxo de trabalho de análise que funciona melhor para você. |
| Domínios primários disponíveis na RDC da China | 18 de junho de 2020 | Permite que os clientes com um `.cn` domínio solicitem um domínio próprio para uso dentro da China Continental. (Documentação disponível com a compra do SKU &quot;Otimização do desempenho da China&quot;.) |
| Painel Quick Insights na Workspace | 25 de junho de 2020 | O Quick Insights fornece orientação para não analistas e novos usuários da área de trabalho da Análise para aprender a responder perguntas comerciais de forma rápida e fácil. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Analytics para o painel Públicos alvos na Workspace | 25 de junho de 2020 | O painel Análises para Públicos alvos (A4T) permite que você analise suas atividades e experiências do Público alvo da Adobe na área de trabalho da Análise. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html)Geral - Data do Público alvo | Descrição |
| -----------| ---------- |-----|
| Suporte para detecção de anomalias | 18 de junho de 2020 | A Detecção de anomalias fornece um método estatístico para determinar como uma determinada métrica foi alterada em relação aos dados anteriores. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Funções de projeto para projetos compartilhados da Workspace | 18 de junho de 2020 | Ao compartilhar um projeto da Workspace, você pode colocar recipient em uma das três funções do projeto, dependendo da experiência do projeto que deseja que eles tenham: Editar, Duplicado e Visualização. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projetos da área de trabalho somente para Visualização | 18 de junho de 2020 | Os projetos do Workspace podem ser compartilhados somente para usuários como &quot;Pode visualização&quot;. Quando um recipient Visualização abre o projeto compartilhado, ele recebe uma experiência mais restritiva do projeto, sem trilho restante e interações limitadas. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Capacidade de co-editar projetos do Workspace | 18 de junho de 2020 | Recipient adicionados à função &quot;Pode editar&quot; podem ser salvos em um projeto que foi compartilhado para eles. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |

### Novos recursos no [!UICONTROL Media Analytics] {#media-aa}

Data de atualização: **29 de maio de 2020**

**Rastreamento de estado do player:** os clientes do [!UICONTROL Media Analytics] podem capturar a interação do visualizador durante a reprodução usando um conjunto padrão de variáveis de solução para tela cheia, legendas ocultas, mudo, picture-in-picture e em foco. Você também tem flexibilidade para criar estados personalizados do player. As variáveis de Rastreamento de estado do player estão disponíveis para relatórios no [!UICONTROL Analysis Workspace]. Esse recurso exige um dos seguintes:

* Media [!DNL JavaScript] SDK 3.0 ou superior
* Para uso com o SDK [!DNL Adobe Experience Platform] (AEP):
   * [!UICONTROL Extensão do Media Analytics] (para Web): [!UICONTROL Adobe Media Analytics] (SDK 3.x) for Audio and Video v1.0 ou superior
   * [!UICONTROL Extensão do Media Analytics] (para dispositivos móveis): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 ou superior
* [!UICONTROL Coleção de mídia]

Consulte [Sobre o rastreamento do estado do player](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/player-state-tracking/player-state-overview.html).

### Adobe Analytics Fixes {#aa-fixes}

* Correção de um problema que fazia com que os segmentos com pesquisas multibyte para determinados conjuntos de relatórios não correspondessem a nada. Agora eles vão corresponder às cordas corretas. AN-220043
* Correção de um problema no qual o Filtro de item no Relatórios e análises não funcionava. AN-206132
* Corrigido o tempo de resposta lento na interface do usuário de projetos agendados. AN-214837
* Correção de um problema com a API de Relatórios do Analytics 2.0 que gerava um erro de intervalo de datas. AN-215087
* Correção de um caso em que a instância/visita/visitante não estava sendo contada no denominador das métricas de Tempo gasto. Isso ocorria quando uma ocorrência sem valor para a dimensão (por exemplo, Pagename) era seguida no mesmo segundo. AN-211074
* Correção de um problema em que os usuários não conseguiam acessar projetos do Workspace compartilhados com eles. AN-217561
* Corrigido o problema que fazia com que chaves não fossem classificadas pelo Construtor de regras de classificação. AN-221538
* Correção de um problema em que o Uso de chamadas do servidor não relatórios dados de uso. AN-210452
* Correção de problemas com segmentos publicados do Adobe Analytics que não tinham dados no AAM. AN-220208, AN-220659
* Correção de um problema que fazia com que relatórios mostrassem dados, mas os registros de Feeds de dados informassem &quot;Nenhum dado do Data Warehouse&quot;. AN-220784, AN-220858
* Correção de problemas que impedia a inicialização da Análise ad hoc do `experiencecloud.com` domínio. AN-219680, AN-221629
* Correção de problemas com o uso da tecla de atalho &quot;Ctrl (ou Command) + C&quot;. AN-221101, AN-221537
* Correção de um problema com a página de ativação do Mapa de Atividades. AN-222029, AN-221242
* Correção de um problema que impedia a adição de um ponto de contato no meio de uma visualização de Fallout. AN-221648

#### Outras correções do Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Migração para o domínio de produto unificado | Data efetiva: 28 de maio de 2020 | A migração para um domínio de produto unificado do Adobe Analytics, que começou em janeiro de 2020, terminou em 28 de maio de 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. Quando a migração da arquitetura for concluída (em breve), você será notificado por meio das notas de versão e essa etapa da lista de permissões não será mais necessária. [Esta](https://helpx.adobe.com/br/analytics/kb/adobe-ip-addresses.html) é uma lista completa de domínios e endereços IP recomendados que você deve permitir.<br>Se sua organização bloquear cookies de terceiros, entre em contato com o Atendimento ao cliente para recuperar o acesso ao Adobe Analytics. |
Se sua organização bloquear cookies de terceiros, entre em contato com o Atendimento ao cliente para recuperar o acesso ao Adobe Analytics.
|Nova landing page padrão do Adobe Analytics|Data de efetivação: 18 de junho de 2020|Em 18 de junho de 2020, a landing page padrão do Adobe Analytics mudará de Relatórios para Espaço de trabalho. Essa alteração ocorrerá para qualquer usuário que não tenha definido uma landing page personalizada anteriormente.|
|Lista de permissões de tecnologia de terceiros|12 de março de 2020 (data de efetivação)|O Adobe Analytics começou a utilizar tecnologias de terceiros para o gerenciamento de implantação de recursos e suporte no produto. Os URLs a seguir devem ser adicionados a qualquer firewall de rede que permita o acesso completo aos recursos:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul>|
|Redundância aprimorada para disponibilidade da área de trabalho de Análise|21 de maio de 2020|Para garantir a disponibilidade da área de trabalho de Análise, estamos adicionando uma CDN secundária (Rede de Delivery de Conteúdo) para obter redundância aprimorada. Os seguintes URLs devem ser adicionados a qualquer lista de permissões de firewall de rede necessária:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul>|
|Alteração na forma como [!UICONTROL Entradas/Saídas] são calculadas no [!UICONTROL Workspace]|7 de abril de 2020|Na [!UICONTROL Análise Workspace], a partir de março de 2020, alteramos a forma como o valor _Nenhum_ interage com [!UICONTROL Entradas/Saídas]. Como agora é possível ativar ou desativar o valor _Nenhum_ no [!UICONTROL Analysis Workspace], aplicamos o valor _Nenhum_ após a entrada ou saída, enquanto que (para eVars) costumava ser aplicado antes da entrada ou saída. Por exemplo, suponha que a primeira ocorrência de uma visita não tenha valor para eVars, mas a segunda ocorrência tem. No [!UICONTROL Reports &amp; Analytics], a primeira ocorrência será exibida como _Não especificado_ para a Entrada, mas no [!UICONTROL Analysis Workspace] será exibida como o valor na segunda ocorrência.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports &amp; Analytics] will no longer be available as of October, 2020.|
|Fim da vida útil - APIs herdadas do Analytics|9 de janeiro de 2020|Em novembro de 2020, os seguintes serviços de API herdada do Analytics atingirão seu fim de vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0.|
|San Jose FTP Broker Finding for London and Singapore|Julho 2020|Para clientes em Londres e Cingapura, deixaremos de oferecer suporte à intermediação de dados entre Londres ou Cingapura e o data center San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL da Análise ad hoc|6 de agosto de 2018|A Adobe anunciou a intenção de encerrar a Análise ad hoc. Uma data para o fim da vida útil será compartilhada assim que estiver disponível. Para obter mais informações, visite [Descubra a Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/appmeasurement-updates.html). A versão 2.20.0 foi lançada em 5 de março de 2020.

### Novos tutoriais do Analytics {#tutorials-analytics}

| Conteúdo | Descrição |
| -----------| ---------- |
| [Modelo do tutorial de treinamento no Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | O tutorial de treinamento do [!UICONTROL Analysis Workspace] orienta você pela terminologia e etapas comuns para criar seu primeiro projeto no [!UICONTROL Workspace]. |
| [Adição de comparações anteriores de mês e ano às tendências](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Saiba como aplicar intervalos de datas personalizados para criar comparações de tendências mensais e anuais para qualquer métrica no [!UICONTROL Analysis Workspace]. |
| [Extensão Dark Mode para o Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Ative a extensão Dark Reader Chrome para tornar o Analysis Workspace escuro. |
| [Extensão Color Eyedropper para Definição de paletas personalizadas](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Saiba como usar a extensão ColorPick EyeDropper Chrome para localizar facilmente os valores hexadecimais necessários para usar uma paleta de cores personalizada em seus projetos do [!UICONTROL Workspace]. |

#### Recursos de ajuda do Analytics

* [Tutoriais do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentação de produto do Adobe Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/landing/home.html)

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Novos recursos, correções, documentação e tutoriais no Audience Manager.

### Atualizações da interface do usuário

O Audience Manager está lançando atualizações no domínio e na barra de cabeçalho para melhorar sua experiência e se unificar com outros aplicativos da Experience Cloud.

* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do usuário aprimorada, incluindo artigos em destaque e vídeos relevantes pára o contexto no menu Ajuda.
* Capacidade de fornecer feedback sobre a Experience Platform e os tíquetes de suporte a arquivos.
* Um novo padrão de URL mais simples. Atualize seus marcadores para o novo url: `experience.adobe.com/audience-manager`.

Essas atualizações estão disponíveis somente para usuários que fazem logon com a Adobe ID. Para alternar para um logon com a Adobe ID, consulte [Gerenciar usuários e produtos da Experience Cloud](https://docs.adobe.com/content/help/pt-BR/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Novos recursos e correções no Adobe Audience Manager

| Recurso | Descrição |
| -----------| ---------- |  
| [Ferramentas de gerenciamento em massa (BAAAM)](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Fizemos o upload de uma nova planilha de ferramentas de gerenciamento em massa que: <br><br><ul><li>Permite listar as subpastas na sua hierarquia de características (AAM-51528)</li><li>Recupera métricas quando solicitado para características associadas a IDs de CRM (IDs entre dispositivos) (AAM-52135)</li><li>Corrige um problema de codificação de idioma para caracteres coreanos (AAM-AAM-54006)</li></ul> |

**Correções**

* Correção de um problema em que os relatórios de tendências expiravam em pastas com um grande número de características. (AAM-54457)
* Correção de um problema em que os clientes não conseguiam ver o [!UICONTROL Construtor de expressões] no fluxo de trabalho de criação/edição de características. (AAM-54255)
* Correção de um problema em que as mensagens de erro na interface do usuário eram exibidas por pouco tempo, desaparecendo antes que os clientes tivessem a chance de lê-las. Isso ocorreu, por exemplo, ao tentar excluir um segmento que estava mapeado para um destino. (AAM-54031)
* Correção de um problema em que os clientes que não estão mais usando o [!UICONTROL Audience Marketplace] recebiam emails de faturamento mensais. (AAM-54602)
* Correção de um problema em que os clientes que clicavam em certas características de outros locais na interface do usuário viam links com falha em vez das características. (AAM-54768)
* Correção de um problema em que, no modo de edição de expressão de característica, pressionar ENTER atualizava a página e a expressão de característica era perdida. (AAM-54210)
* Várias melhorias de acessibilidade na interface. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Novos tutoriais do Audience Manager {#tutorials-aam}

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Noções básicas sobre termos e conceitos básicos no Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | Este vídeo aborda alguns dos termos e conceitos básicos que orientam você no Audience Manager, incluindo sinais, características, segmentos etc. |
| [Como entender o fluxo de dados no Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Este vídeo ajuda você a entender o Adobe Audience Manager descrevendo o fluxo de dados para dentro, através e para fora do aplicativo. |
| [Audience Manager - Visão geral de um DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Entenda os principais desafios com a personalização entre canais e como o Adobe Audience Manager promove a jornada do cliente. Saiba também quais tipos de dados podem ser integrados no Audience Manager e identifique os parceiros de ecossistema ad-tech integrados ao Audience Manager. |
| [Casos de uso do Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | Neste vídeo, identificamos quatro casos de uso comuns do Audience Manager e descrevemos as práticas recomendadas associadas a eles. |
| [Como entender as métricas entre dispositivos no Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | Neste vídeo, discutimos a diferença entre perfis de dispositivos e perfis entre dispositivos e mostramos onde os números na interface do usuário correspondem a esses diferentes tipos de perfis. |
| [Como entender públicos-alvo preditivos no Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | Neste vídeo, discutimos o que são públicos-alvo preditivos do Audience Manager, apresentamos detalhes sobre como funcionam e indicamos casos de uso. |
| [Configurar e relatar públicos-alvo preditivos no Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | Neste vídeo, abordamos a configuração de públicos-alvo preditivos na interface do Audience Manager. Também vemos os relatórios que mostram os resultados do modelo. |

## ![Ícone](/assets/aem.png) Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Atualizações do produto

* **AEM como um Cloud Service**

   * Melhorias e correções no processamento de ativos. A caixa de diálogo de reprocessamento de ativos dá ao usuário mais controle, permite selecionar um perfil de processamento específico e diz se o fluxo de trabalho de pós-processamento deve ser acionado.
   * Aprimoramentos no desempenho de assimilação de ativos do Dynamic Media.

### Autoajuda

* **Serviço de conversão automatizada de formulários - versão AFC-2020.03.1**

   Uma nova opção está disponível ao instalar o conector mais recente:

   **[!UICONTROL Detecção automática de seções lógicas]**: você pode usar a opção [!UICONTROL Detecção automática de seções lógicas] para soltar painéis em nível de página (painéis baseados em números de página) e criar apenas painéis lógicos. Ele também agrupa os campos que não pertencem a nenhuma seção com seções lógicas anteriores e agrupa os campos de uma seção lógica espalhados por duas páginas adjacentes em uma única seção lógica. Por exemplo, se alguns campos de uma seção lógica estiverem no final da página um e alguns estiverem no início da página dois, todos esses campos serão agrupados em uma única seção lógica.

* **Formatos de imagem não aceitos no Dynamic Media**

   Informações sobre os subtipos de formatos de arquivo de imagem rasterizada que não são aceitos no [!UICONTROL Dynamic Media].

   Consulte [Formatos de imagem rasterizada não aceitos no Dynamic Media](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Fragmentos de conteúdo**

   Informações sobre o [Suporte a fragmentos de conteúdo na API HTTP do AEM Assets](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html), juntamente com [Personalização e extensão de fragmentos de conteúdo](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html) e [Fragmentos de conteúdo configurando componentes para renderização](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **Comunidade da AEM Experience League**

   Conecte-se com a [Comunidade da AEM Experience League](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): Faça perguntas aos colegas e especialistas do AEM, navegue por processos e compartilhe suas dicas e seu conhecimento!

* **Informativos do AEM**

   O informativo do AEM disponibilizado pela [!UICONTROL Experience League] foi projetado para ajudar você a usar o AEM e obter vantagens desde o início. Este é o informativo mais recente:

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): o Experience Manager agora está disponível como um serviço na nuvem.
   * [Assine](https://adobeeventsonline.com/AEM/2017/NL/Optin/) o informativo Experience Insider.
   * Visualize arquivos do informativo na seção [Recursos do AEM](https://helpx.adobe.com/br/support/experience-manager/6-5.html) na página Aprendizagem e suporte do Adobe Experience Manager 6.5.

### Novos tutoriais da Experience Manager

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Configurar o AEM Runtime local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | O Adobe Experience Manager (AEM) pode ser executado localmente usando o [!UICONTROL AEM como um] [!UICONTROL Quickstart] Jar do SDK do Cloud Service. Isso permite que os desenvolvedores implantem e testem código, configuração e conteúdo personalizados antes de confirmá-los no controle de origem e implantá-los em um [!UICONTROL AEM como um ambiente de serviço na nuvem]. |
| [Introdução aos AEM Assets](https://video.tv.adobe.com/v/33624?captions=por_br) | Um vídeo de introdução sobre como começar a usar AEM Assets para usuários comerciais. |
| [Esquemas de pastas de metadados](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Os esquemas de pastas de metadados permitem que os usuários gerenciem e revisem metadados associados às próprias pastas de ativos, em vez de diretamente nos ativos. |
| [Marcação com tags](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | As tags são uma ferramenta integral para gerenciar ativos na hierarquia de pastas dos ativos. Estabelecer uma taxonomia de marcação é essencial para permitir que os usuários descubram e organizem ativos no AEM. |
| [Perfis de metadados](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Os perfis de metadados permitem a aplicação automática de metadados padrão em ativos nas pastas de ativos. Isso ajuda a reduzir a carga do gerenciamento de metadados sobre os usuários do AEM e aumenta a consistência dos metadados. |
| [Esquemas de metadados](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Os esquemas de metadados definem a interface que expõe os metadados do ativo no AEM. Este vídeo explora a combinação de abordagens usadas para aplicar ativos. |

### Recursos adicionais

* [Notas de versão do AEM como um serviço na nuvem](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM como uma documentação de serviços na nuvem](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
* [Página inicial de aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Página inicial de aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Página inicial de aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página inicial de aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Notas de versão do AEM Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/home.html)
* [Notas de versão do Dynamic Media](https://docs.adobe.com/content/help/pt-BR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

## ![Ícone](/assets/campaign.png) [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Campaign Standard

* [Lançamento do Adobe Campaign Standard 20.3](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Painel de controle do Campaign

| Recurso | Descrição |
| -----------| ---------- |  
| Gerenciamento de chaves GPG | Instale e/ou gere chaves GPG em uma instância de marketing para criptografar dados enviados do Campaign e descriptografar dados recebidos. |
| Gerenciamento de certificados para subdomínios CNAME | O Painel de controle agora permite que você renove os certificados SSL de seus subdomínios que foram delegados com o método CNAME. |

### Novos tutoriais do Campaign

* Tutoriais do Novo Campaign Standard

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Painel de controle - Gerenciamento de registros do Google TXT](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Saiba como adicionar registros de verificação de site do Google TXT a todos os subdomínios usados para enviar emails para endereços GMAIL com o Painel de controle do Campaign. |
| [Configurar e executar um fluxo de trabalho com a atividade de API externa](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Saiba como chamar um endpoint da REST API externa usando a atividade de API externa. |
| [Introdução às notificações por push para tutorial do Android](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | Este tutorial explica as etapas necessárias para configurar notificações por push com aplicativos do Campaign Standard e Android. |

* Novos tutoriais do Campaign Classic

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Gerenciamento de big data no Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Saiba como usar o conector Snowflake no Adobe Campaign Classic. |
| [Painel de controle - Gerenciamento de registros do Google TXT](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Saiba como adicionar registros de verificação de site do Google TXT a todos os subdomínios usados para enviar emails para endereços GMAIL com o Painel de controle do Campaign. |

### Recursos de ajuda do Campaign

* Adobe Campaign Standard: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/campaign-standard-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/overview.html) - [Planejamento de lançamento](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-planning.html) - [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/campaign-classic-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/documentation-updates.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Novos recursos na Advertising Cloud DSP](#adcloud-dsp)
* [Novos recursos na Advertising Cloud Search](#adcloud-search)

### Novos recursos na Advertising Cloud DSP {#adcloud-dsp}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campaign Classic] e [!UICONTROL Campaign Beta] | As configurações de mensuração do IAS para fraude e segurança de marca, que você pode configurar opcionalmente para cada campanha, agora incluem opções para medir no inventário VAST e VPAID. |
| [!UICONTROL Campaign Beta] | As visualizações de dados e os tempos de carregamento de página foram aprimorados. |
|  | Em todas as páginas, agora é possível baixar relatórios do Excel com base nos filtros e nas visualizações atuais. |
|  | (Na versão de 22 de maio) As novas métricas incluem as métricas All-time, Current Interval Delivery, Date Specific OTS. |
| [!UICONTROL Listas negras] | O sistema de previsão agora usa automaticamente a lista negra do anunciante ou da conta. Os usuários não precisam mais colar a lista negra nas configurações de posicionamento. |
| [!UICONTROL Contratos de inventário] | (Beta fechado) Um novo formulário simplificado permite que você configure, edite e solucione rapidamente as ofertas da plataforma do lado do suprimento (SSPs) que não estão disponíveis na Caixa de entrada da ID do contrato. |
|  | Quando você aceita um pacote de ofertas programáticas garantidas na Caixa de entrada da ID do contrato, agora você é alertado de que precisa criar uma disposição padrão para cada uma das IDs do contrato. |

### Novos recursos na [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanhas] | (Contas do Google Ads; serviço beta) A partir do final de maio, a Advertising Cloud Search poderá sincronizar os dados das campanhas de exibição do Google Gmail e das campanhas do Google Smart Shopping com as conversões do Google para rastreamento e relatórios. O serviço também permitirá que você edite as configurações de campanha e as configurações de grupo de publicidade para suas campanhas existentes nas visualizações de Campanhas e grupos de anúncios. O serviço será opcional. Quando o serviço estiver disponível, será aplicada uma taxa adicional.<br>Para obter mais informações sobre o serviço, incluindo o programa beta e o escopo futuro, entre em contato com seu gerente de conta da Adobe. |

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Para ver as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ícone](/assets/marketo.png) [!DNL Marketo] {#marketo}

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
