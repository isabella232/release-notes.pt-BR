---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 34940c585feab93f47f7915f4b45fa4a555cd235

---


# Acesso antecipado - Notas de versão da Adobe Experience Cloud - abril de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Novos recursos e correções na [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>
>Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.

>[!NOTE]
>
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: abril de 2020**

(As datas de lançamento da solução específica podem variar.)

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud e dos serviços principais](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (Alteração na data de **lançamento - consulte a atualização em 15** de abril)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html) (links para a página de ajuda da solução)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/br/primetime/user-guide.html) (links para a página de ajuda da solução)

Procurando a página principal da ajuda? Consulte [Documentação da Adobe Experience Cloud](https://docs.adobe.com/content/help/pt-BR/experience-cloud/user-guides/home.html).

## ![Ícone](/assets/adobe.png) Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

**Novidades**

* Usando a Adobe ID, é possível assinar notificações de eventos com mais granularidade até a oferta de produtos e complementos. Além disso, em nossa última versão, o processo de subscrição automática agora recomenda uma seleção de produtos e serviços com base em seus direitos ao produto. Isso deve simplificar o processo de subscrição, reduzindo o número de decisões ou cliques necessários para criar suas subscrições e, mais importante, fornecer notificações mais relevantes na sua caixa de entrada. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| subscrições personalizadas com base em direitos | <ul><li>Recomendações de subscrição pré-selecionadas com base nos direitos DX do usuário.</li><li>As subscrições recomendadas são destacadas na parte superior da lista do produto para uma visualização rápida.</li><li>As notificações por e-mail recebidas são relevantes para os direitos do usuário ao produto.</li></ul> |
| Gerenciamento mais fácil de Subscrições | <ul><li>**[!UICONTROL O Gerenciamento do Subscrição]** tem uma nova experiência de usuário para gerenciar subscrições de produtos e eventos.</li><li>Nova opção para visualização e edição de subscrições de produtos e eventos separadamente.</li><li>A opção **[!UICONTROL Excluir]** permite cancelar a inscrição de um produto ou subscrição.</li><li>A opção **[!UICONTROL Cancelar inscrição de todos]** com um clique está disponível para as subscrições do produto.</li><li>O suporte UX está disponível para superfícies Web/Mobile/Tablet e localização em 19 idiomas.</li></ul> |

## ![Ícone](/assets/ec_appicon_24.png) Interface da Experience Cloud e dos serviços principais{#ecloud}

Novos recursos e correções na interface da Experience Cloud, incluindo administração e principais serviços (atributos do cliente, audiências, acionadores, cookies etc.):

* A página do [!UICONTROL Feed] da Experience Cloud foi substituída. (EXC-8505)
* A página de logon da Experience Cloud foi atualizada para refletir os novos elementos de marca. (EXC-10747)

Para obter a documentação do produto, consulte a ajuda da [Experience Cloud](https://docs.adobe.com/content/help/pt-BR/core-services/interface/experience-cloud.html).

### Domínio de produto unificado

A Adobe está atualizando o domínio e o cabeçalho da interface para unificar e melhorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar a experiência de maneiras pequenas, mas importantes. Eles não alterarão seus fluxos de trabalho atuais.

As atualizações incluem:

* Novos URLs das soluções: `experience.adobe.com/<application name>`:
   * Todos os produtos acabarão por adotar esse padrão de URL. Procure novos URLs para se tornarem efetivos durante o mês.
   * Compatibilidade de navegador: os navegadores compatíveis incluem [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versões mais recentes). **Observação:** embora a interface da Experience Cloud seja compatível com esses navegadores, as soluções individuais podem não ser compatíveis com todos os navegadores. (Por exemplo, o [Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/admin/sys-reqs.html) não é compatível com o [!DNL Opera] e o [Target](https://docs.adobe.com/help/pt-BR/target/using/implement-target/before-implement/supported-browsers.html) não é compatível com o [!DNL Safari].)
   * (Somente para o [!DNL Safari]) A alteração de domínio pode causar problemas de cookie no [!DNL Safari]. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do [!DNL Safari], os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Experience Cloud poderá funcionar nesse novo domínio.
* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do produto aprimorada: a [!UICONTROL Experience League] está integrada ao produto para que a pesquisa de ajuda também inclua resultados de fóruns da comunidade e conteúdo em vídeo. Essa alteração simplifica o acesso a mais conteúdo e ajuda a aproveitar ao máximo a Experience Cloud. Além disso, clique em **[!UICONTROL Ajuda]** > **[!UICONTROL Feedback]** para relatar problemas ou compartilhar suas ideias com a Adobe.

## ![Ícone](/assets/experience_platform_appicon_24.png) Experience Platform{#platform}

Notas de versão para a [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Serviço de identidade,] Orquestração de jornadas, Mobile Services e informativos de segurança.

### Orquestração da jornada {#journey}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

* [Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html)
* [Notas de versão](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html)
* [Vídeos tutoriais](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services e SDKs móveis {#mobile}

Android 4.18.2 (3 de abril de 2020):

* Em mensagens do aplicativo: Por motivos de segurança, [!UICONTROL WebViews] criadas pelo SDK agora definem a propriedade `setAllowFileAccess` igual a _false_.

iOS 4.19.2 (24 de março de 2020):

* Geral: Correção de alguns vazamentos no [!DNL Target] código.

Unidade 4.19.0 (10 de março de 2020):

* Atualização do plug-in [!UICONTROL do] Unity para usar as versões 4.19.0 do iOS e 4.18.0 ou [!DNL Android].
* Novo método de aquisição exposto para [!DNL Android] permitir o processamento de um URL fornecido pelas APIs de [!DNL Google Play] Quem indicou.

### Informações adicionais sobre a versão da plataforma Experience Platform

* [Notas](https://docs.adobe.com/content/help/pt-BR/launch/using/intro/release-notes/current.html)de versão do Experience Platform Launch.
* [Notas de versão da plataforma Experience](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/br/security.html) (Todos os produtos da Adobe)

## ![Ícone](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>A versão de manutenção de abril do Adobe Analytics foi transferida para 21 de maio de 2020. Para obter as informações mais recentes da versão do Analytics, consulte as notas de versão de [março](c-legacy-releases/2020/03122020.md)

<!-- * [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices) (Updated April 7, 2020)
* [AppMeasurement](#appm) -->

* [Análise da jornada do cliente](#cust-journey)
* [Novos tutoriais do Analytics](#tutorials-analytics)

<!-- ### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
|[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace]|April 7, 2020|In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. For example, assume the first hit of a visit has no value for eVars, but the second hit does. In [!UICONTROL Reports & Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit.|
|EOL of **[!UICONTROL Conversion Level]** setting|March 3, 2020|The non-functioning [Conversion Level](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] will no longer be available as of October, 2020.|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics began moving to a new domain - `https://experience.adobe.com/analytics.`<br>**Note:** This change applies to all users accessing Analytics with their Adobe ID or Enterprise ID. <ul><li>The domain change may cause cookie issues when loading Analytics in Safari. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>The domain change may cause [!UICONTROL Activity Map] to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul>|
|End of Life - Analytics Legacy APIs|January 9, 2020|In November 2020, the following Analytics Legacy API services will reach their end-of-life and will be shutdown. Current integrations built using these services will stop working. <ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL of Ad Hoc Analysis|Aug 6, 2018|Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available. For more information, visit [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 was released on March 5, 2020. -->

### Customer Journey Analytics {#cust-journey}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Análise]de jornada do cliente: Preenchimento retroativo de conjunto de dados [!UICONTROL automatizado] | Esta nova opção permite importar todos os dados históricos de uma conexão no [!UICONTROL Customer Journey Analytics]. (Documentação a seguir) |

### Novos tutoriais do Analytics {#tutorials-analytics}

| Conteúdo | Descrição |
| -----------| ---------- |
| [Adobe Labs (Pré-visualizações de tecnologia) com o Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | O Adobe Labs (Pré-visualizações de tecnologia) permite que você se envolva com tecnologias emergentes, descubra insights valiosos e influencie o desenvolvimento e as prioridades futuras [!DNL Analytics] de recursos. |
| [Publicação de Audiências da Experience Cloud aprimorada](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Foram feitos aprimoramentos na [!UICONTROL Experience Cloud Audiência Publishing]. Agora você pode publicar audiências (segmentos) e disponibilizá-las seis vezes mais rápido. Isso reduz o tempo de latência atual de 48 horas para aproximadamente 8 horas, e possivelmente mais rápido, dependendo do tráfego e do tamanho do segmento. |
| [Vários conjuntos de relatórios na área de trabalho de Análise](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Vários conjuntos de relatórios podem ser analisados em um único projeto da [!UICONTROL Workspace] selecionando conjuntos de relatórios no nível do painel. Isso permite que você realize análises lado a lado no painel em diferentes conjuntos de dados. |

Consulte Página inicial [de ajuda do](https://docs.adobe.com/content/help/pt-BR/analytics/landing/home.html) Adobe Analytics para obter a documentação do produto.

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Novos recursos e correções no Adobe Audience Manager:

| Recurso | Descrição |
| -----------| ---------- |  
| [Principais problemas de suporte ao cliente](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | Adicionamos uma nova seção ao nosso portal de documentação, que inclui respostas às perguntas mais frequentes recebidas pela nossa equipe de suporte ao cliente. |

* Correção de um problema que resultava no relatórios impreciso de Audiências [](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) endereçáveis para segmentos que continham IDs de dispositivos móveis. Após esta atualização, você poderá ver um aumento em suas Audiências [endereçáveis](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html).
* Corrigido um problema que fazia com que os botões Teste [!UICONTROL de] Duplicado e Modelo [!UICONTROL de alocação de] Duplicados no Laboratório [!UICONTROL de] Audiências não funcionassem. (AAM-53388)
* Correção de um problema que fazia com que as Audiências [!UICONTROL de Taxa] de [!UICONTROL correspondência e de Endereçamento de] segmento fossem exibidas como 0 quando um destino era configurado para exportar UUIDs. As Audiências [!UICONTROL Taxa] de [!UICONTROL correspondência e Endereçamento] do segmento agora são exibidas como 100%. (AAM-51615)
* Corrigido um problema que fazia com que os nomes de características que contêm caracteres especiais fossem codificados duas vezes em HTML. (AAM-54001)
* Correção de um problema que impedia alguns usuários de alternarem para outras soluções da Adobe Experience Cloud na interface do [!DNL Audience Manager] usuário. (AAM-52917)
* Correção de um problema que impedia que alguns usuários criassem uma fonte de dados SHA256 para destinos baseados em Pessoas. (AAM-53525)
* Várias melhorias de acessibilidade na interface. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Ícone](/assets/aem.png) Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Autoajuda

* **Newsletter do AEM**

   Consulte a newsletter mais recente [do Adobe Experience Manager](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **AEM como um serviço em nuvem - Configuração do serviço da Dynamic Media Cloud**

   Uma nova opção está disponível quando você configura o Serviço da Dynamic Media Cloud:

   **Publicação** seletiva - ao selecionar essa opção, significa que os ativos são publicados automaticamente apenas para pré-visualização segura e podem ser publicados explicitamente no AEM sem publicação no DMS7 para delivery no domínio público.

   Consulte [Configuração do serviço](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)da Dynamic Media Cloud.

* **Dynamic Media - Imagem inteligente**

   Todo o tópico da Ajuda do Smart Imaging foi atualizado com novas informações, incluindo exemplos de ativos de imagem que representam a otimização adicionada do Smart Imaging.

   Consulte Imagem [inteligente](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Configuração do Dynamic Media - modo Scene7**

   Uma nova opção Sincronizar todo o conteúdo agora está disponível na página Configuração de Dynamic Media, localizada em **[!UICONTROL Ferramentas > Serviços]** em nuvem.

   Consulte [Criação de uma configuração](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)de mídia dinâmica.

* **O AEM Assets Brand Portal oferece suporte aos ativos AEM como um serviço em nuvem**

   Agora você pode publicar ativos do AEM Assets como um serviço em nuvem no AEM Assets Brand Portal.

   Consulte [Configurar ativos AEM com o Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) e [Publicar ativos no Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 lançado**

   O Adobe Asset Link 2.0 é compatível com o trabalho com vários ambientes AEM e oferece suporte ao AEM como um serviço em nuvem. O AEM oferece suporte às necessidades dos comerciantes para configurar a execução automática do fluxo de trabalho de processamento de ativos quando os ativos são carregados para uma pasta usando o Adobe Asset Link.

   See [Adobe Asset Link](https://helpx.adobe.com/br/enterprise/using/adobe-asset-link.html).

### Novos tutoriais do Experience Manager

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Configurar ferramentas locais do Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Saiba mais sobre como facilitar a configuração, validação e simulação do [!UICONTROL Dispatcher] localmente. |
| [Configurar ferramentas de desenvolvimento para projetos AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | O desenvolvimento do Adobe Experience Manager (AEM) exige que um conjunto mínimo de ferramentas de desenvolvimento seja instalado e configurado na máquina do desenvolvedor. Essas ferramentas suportam o desenvolvimento e a criação de projetos do AEM. |
| [Configurar o AEM Runtime local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | O Adobe Experience Manager (AEM) pode ser executado localmente usando o AEM como um [!UICONTROL QuickStart Jar]do SDK de serviço em nuvem. Isso permite que os desenvolvedores implantem e testem código, configuração e conteúdo personalizados antes de confirmá-los no controle de origem e implantá-los em um AEM como um ambiente de serviço em nuvem. |
| [Navegação](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Explore as noções básicas para navegação nos ativos AEM. |
| [Versões](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Explore como o AEM cria e mantém versões de ativos. |
| [AEM - Integração do [!DNL Magento] usando a Estrutura de Integração de [!UICONTROL Comércio]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Este vídeo o orienta pela configuração da integração entre o AEM e [!DNL Magento]. |
| [Introdução à pilha da arquitetura do AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | O arquétipo CIF do projeto cria um projeto CIF mínimo do Adobe Experience Manager (AEM) como ponto de partida para projetos de clientes que usam os componentes principais CIF. |
| [Introdução ao OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Uma introdução ao OSGi, uma arquitetura modular dinâmica para aplicativos Java que é a base do Adobe Experience Manager. |
| [Introdução ao Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Uma introdução ao [Java Content Repository (JCR)] usado pelo Adobe Experience Manager. |
| [Introdução ao Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Uma introdução ao [!DNL Sling], uma estrutura Web RESTful de código aberto que faz parte da pilha de tecnologia subjacente do Adobe Experience Manager. |
| [Introdução à camada Autor e Publicação](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Uma introdução aos níveis de [!UICONTROL Autor] e [!UICONTROL Publicação] como parte da arquitetura no Adobe Experience Manager. |
| [Introdução ao Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Uma introdução aos recursos do dispatcher como parte da arquitetura do AEM. |
| [Introdução ao desenvolvimento de componentes](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Uma visão geral do desenvolvimento de componentes com o Adobe Experience Manager Sites. Inclui uma introdução a [!UICONTROL Diálogos], Modelos Sling, Scripts HTL e Bibliotecas [!UICONTROL do lado do]cliente. |
| [Arquétipo de projeto AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | O projeto do AEM contém todos os códigos e configurações para uma implementação. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [Noções básicas sobre os componentes principais](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | Os componentes  principais do AEM são um conjunto padrão de componentes a ser usado com o Adobe Experience Manager. |
| [Usar o Jar de Início Rápido do AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Saiba como instalar e executar uma instância local do Adobe Experience Manager em apenas alguns minutos com o pod [!UICONTROL de início rápido do]AEM. |

### Recursos adicionais de ajuda

* [AEM como um Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
* [Página inicial de aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Página inicial de aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Página inicial de aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página inicial de aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/br/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/home.html)
* [Notas de versão do Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

## ![Ícone](/assets/campaign.png) [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html)

### Tutoriais do Novo Campaign Standard {#tutorials-acs}

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Substituição de Perfil - Testando mensagens de email usando perfis direcionados](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Teste suas mensagens de email usando o recurso Substituição de Perfil. |

### Recursos adicionais de ajuda da Campanha

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/br/support/campaign/standard.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planejamento de versão](https://helpx.adobe.com/br/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/br/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/pt-BR/RN.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Para ver as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ícone](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] é uma solução completa para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes ao se envolverem em todas as jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte as notas [!DNL Marketo] de [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) versão para obter mais informações.

### Recursos futuros

Os seguintes recursos serão lançados ao longo do trimestre:

| Recurso | Descrição |
|------|---------|
| [!DNL Bizible] | <ul><li>Nova segmentação baseada em conta</li><li>Salvar filtros específicos do painel</li><li>Exportar painéis Bizible como PDFs</li></ul> |
| Conexão de vendas | Compor atualizações/aprimoramentos da Janela e do Centro de comando |

### Anúncios

**Centro de Sucesso do Marketo Engage:** lançamento em fevereiro de 2020. O Centro de sucesso é um centro de ajuda no produto que permite pesquisar em Documentos de produto e na Comunidade, iniciar guias tutoriais, acessar conteúdo de adoção e muito mais. Observação: esse recurso será lançado como um beta na Austrália e Nova Zelândia e será implantado na América do norte posteriormente neste trimestre.

### Desativações

* **Parâmetro &quot;_method&quot; da API de ativo:** Depois de setembro de 2020, os Pontos finais da API de ativos não aceitarão mais passar os Parâmetros de Query em um corpo POST para ignorar as limitações de comprimento de URI. `_method`
* **Desativação do suporte ao Internet Explorer:** a partir do lançamento realizado em 31 de julho de 2020, a interface do usuário do Marketo Engage não será mais compatível com o Internet Explorer.

Para obter as notas de versão cumulativas e históricas, consulte [Notas de versão do Marketo](https://docs.marketo.com/x/CgA6Ag).
