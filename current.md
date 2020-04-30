---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: d3802d290f1d5192e5bc31f4003ee12fd0ad1ff4

---


# Notas de versão da Adobe Experience Cloud - Abril de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Novos recursos e correções na [!DNL Adobe Experience Cloud].

>[!NOTE]
>
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: abril de 2020**

Última atualização: 30 **de abril de 2020**

(As datas de lançamento específicas podem variar.)

* [Status de sistema da Adobe](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(Atualizado em 29 de abril)**
* [Gerenciador](#aam) de Audiências **(atualizado em 30 de abril)**
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html) (links para a página de ajuda do Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a página de ajuda do Primetime)

Procurando a página principal da ajuda? Consulte [Documentação da Adobe Experience Cloud](https://docs.adobe.com/content/help/pt-BR/experience-cloud/user-guides/home.html).

## ![Ícone](/assets/adobe.png) Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

**Novidades**

* Usando a Adobe ID, é possível assinar notificações de eventos com mais granularidade até a oferta de produtos e complementos. Além disso, em nossa versão mais recente, o processo de assinatura automática agora recomenda uma seleção de produtos e serviços com base nos direitos do seu produto. Isso deve otimizar o processo de assinatura, reduzindo o número de decisões ou cliques necessários para criar assinaturas e, o mais importante, entregar notificações mais relevantes em sua caixa de entrada. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Assinaturas personalizadas com base em direitos | <ul><li>Recomendações de assinatura pré-selecionadas com base nas autorizações de DX do usuário.</li><li>As assinaturas recomendadas estão destacadas no topo da lista de produtos para visualização rápida.</li><li>As notificações por email recebidas são relevantes para os direitos do produto do usuário.</li></ul> |
| Gerenciamento mais simples de assinaturas | <ul><li>**[!UICONTROL O Gerenciamento de assinaturas]** tem uma nova experiência de usuário para gerenciar assinaturas de produtos e eventos.</li><li>Nova opção para visualização e edição de assinaturas de produtos e eventos separadamente.</li><li>A opção **[!UICONTROL Excluir]** permite cancelar a assinatura de uma assinatura de produto ou evento.</li><li>A opção **[!UICONTROL Cancelar inscrição de todos]** com um clique está disponível para assinaturas de produto.</li><li>O suporte UX está disponível para superfícies Web/Mobile/Tablet e está traduzido em 19 idiomas.</li></ul> |

## ![Ícone](/assets/ec_appicon_24.png) Interface da Experience Cloud {#ecloud}

Novos recursos e correções na interface da Experience Cloud:

* A página do [!UICONTROL Feed] da Experience Cloud foi substituída. (EXC-8505)
* A página de logon da Experience Cloud foi atualizada para refletir os novos elementos de marca. (EXC-10747)

Para ver a documentação do produto, consulte a [ajuda da interface da Experience Cloud](https://docs.adobe.com/content/help/pt-BR/core-services/interface/experience-cloud.html).

### Domínio de produto unificado

A Adobe está atualizando o domínio e o cabeçalho da interface para unificar e melhorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar a experiência de maneiras pequenas, mas importantes. Eles não alterarão seus fluxos de trabalho atuais.

As atualizações incluem:

* Novos URLs de aplicativo: `experience.adobe.com/<application name>`:
   * Todos os produtos acabarão por adotar esse padrão de URL. Procure novos URLs para se tornarem efetivos durante o mês.
   * Compatibilidade de navegador: os navegadores compatíveis incluem [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versões mais recentes). **Observação:** embora a interface da Experience Cloud seja compatível com esses navegadores, os aplicativos individuais podem não ser compatíveis com todos os navegadores. (Por exemplo, o [Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/admin/sys-reqs.html) não é compatível com o [!DNL Opera] e o [Target](https://docs.adobe.com/help/pt-BR/target/using/implement-target/before-implement/supported-browsers.html) não é compatível com o [!DNL Safari].)
   * (Somente para o [!DNL Safari]) A alteração de domínio pode causar problemas de cookie no [!DNL Safari]. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do [!DNL Safari], os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Experience Cloud poderá funcionar nesse novo domínio.
* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do produto aprimorada: a [!UICONTROL Experience League] está integrada ao produto para que a pesquisa de ajuda também inclua resultados de fóruns da comunidade e conteúdo em vídeo. Essa alteração simplifica o acesso a mais conteúdo e ajuda a aproveitar ao máximo a Experience Cloud. Além disso, clique em **[!UICONTROL Ajuda]** > **[!UICONTROL Feedback]** para relatar problemas ou compartilhar suas ideias com a Adobe.

## ![Ícone](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notas de versão para [!DNL Experience Platform,] incluir [!DNL Experience Platform Launch,] [!UICONTROL Orquestração de jornada], [!UICONTROL Ofertas], [!UICONTROL Pessoas], [!UICONTROL Places], [!UICONTROL Mobile Services] e boletins de segurança.

### Orquestração da jornada {#journey}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

* [Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html)
* [Notas de versão](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html)
* [Vídeos tutoriais](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services e SDKs móveis {#mobile}

Android 4.18.2 (3 de abril de 2020):

* Em mensagens do aplicativo: Por motivos de segurança, [!UICONTROL WebViews] criadas pelo SDK agora definem a propriedade `setAllowFileAccess` igual a _false_.

iOS 4.19.2 (24 de março de 2020):

* Geral: Correção de alguns vazamentos no código [!DNL Target].

Unidade 4.19.0 (10 de março de 2020):

* Atualização do [!UICONTROL Unity Plugin] para usar as versões 4.19.0 do iOS e 4.18.0 ou [!DNL Android].
* Novo método de aquisição exposto para o [!DNL Android] para permitir o processamento de um URL fornecido pelas APIs do referenciador [!DNL Google Play].

### Informações adicionais sobre a versão da Experience Platform

* [Notas de versão da Experience Platform Launch](https://docs.adobe.com/content/help/pt-BR/launch/using/intro/release-notes/current.html)
* [Notas de versão da Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/br/security.html)  (Todos os produtos da Adobe)

## ![Ícone](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>A versão de manutenção de abril do Adobe Analytics foi transferida para 21 de maio de 2020. Para obter as informações mais recentes da versão do Analytics, consulte as [notas de versão de março](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Avisos importantes para administradores do Analytics](#aa-notices)  (Atualizado em 16 de abril de 2020)
* [AppMeasurement](#appm)
* [Novos tutoriais do Analytics](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Recurso | Descrição |
| -----------| ---------- |
| Data Workbench 6.74 (**Update 4/29/2020**) | Atualização da análise de certificado TLS do IMS (Identity Management Service) na implementação do servidor. Essa atualização expande a análise da correspondência de sequência para a expressão regular, incluindo a capacidade de lidar com certificados de nome alternativo do assunto (SAN). See [Data Workbench release notes](https://docs.adobe.com/content/help/en/data-workbench/using/release-notes/release-notes.html) for more information. |
| [!UICONTROL Customer Journey Analytics]: preenchimento retroativo automático de conjunto de dados | Esta nova opção permite importar todos os dados históricos de uma conexão no [!UICONTROL Customer Journey Analytics]. [Saiba mais](https://docs.adobe.com/content/help/pt-BR/analytics-platform/using/cja-connections/create-connection.translate.html) |

<!--### New features in Adobe Analytics {#aa-features}

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

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição  ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Remoção da verificação &quot;Segmento aplicado no Data Warehouse&quot; | 16 de abril de 2020 | A partir de 16 de abril de 2020, não verificamos mais se um segmento é aplicado em uma solicitação do Data Warehouse, no Segment Builder. Anteriormente, essa verificação procurava segmentos únicos aplicados às solicitações do Data Warehouse (excluía vários segmentos aplicados) e retornava uma notificação de aviso se fosse verdadeira. Essa alteração não afeta a verificação de compatibilidade de produtos do Data Warehouse para segmentos. |
| Alteração na forma como [!UICONTROL Entradas/Saídas] são calculadas no [!UICONTROL Workspace] | 7 de abril de 2020 | A partir de março de 2020, mudamos no [!UICONTROL Analysis Workspace] a forma como o valor _Nenhum_ interage com [!UICONTROL Entradas/Saídas]. Como agora é possível ativar ou desativar o valor _Nenhum_ no [!UICONTROL Analysis Workspace], aplicamos o valor _Nenhum_ após a entrada ou saída, enquanto que (para eVars) costumava ser aplicado antes. Por exemplo, suponha que a primeira ocorrência de uma visita não tenha valor para eVars, mas a segunda ocorrência tem. No [!UICONTROL Reports &amp; Analytics] será exibido como _Não especificado_ para a Entrada, mas no [!UICONTROL Analysis Workspace] será exibido como o valor na segunda ocorrência. |
| EOL da configuração **[!UICONTROL Nível de conversão]** | 3 de março de 2020 | A configuração inoperante [Nível de conversão](https://docs.adobe.com/content/help/pt-BR/analytics/admin/admin-tools/general-acct-settings-admin.html) em **[!UICONTROL Ferramentas de administração]** > **[!UICONTROL Conjuntos de relatórios]** > **[!UICONTROL Configurações gerais da conta]** serão removidas da interface em 12 de março de 2020. |
| EOL do **[!UICONTROL Arquivo do painel]** | 27 de março de 2020 | A configuração **[!UICONTROL Exibir arquivo]** em **[!UICONTROL Gerenciar painéis]** no [!UICONTROL Reports &amp; Analytics] não estará mais disponível a partir de março de 2020. |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Novo domínio do Adobe Analytics | 18 de dezembro de 2019 | Em 16 de janeiro de 2020, o Adobe Analytics começou a migrar para um novo domínio - `https://experience.adobe.com/analytics.`<br>**Observação:** essa alteração se aplica a todos os usuários que acessam o Analytics com sua Adobe ID ou Enterprise ID.<ul><li>O domínio pode causar problemas de cookie ao carregar o Analytics no Safari. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do [!DNL Safari], os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Analytics poderá funcionar nesse novo domínio da Adobe Experience Cloud. Você pode usar outros navegadores sem problemas, pois isso afeta somente os usuários do [!DNL Safari].</li><li>A alteração de domínio pode fazer com que o [!UICONTROL Activity Map] pare de funcionar para alguns clientes [em casos específicos](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fim da vida útil - APIs antigas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Cingapura, não apoiaremos mais a intermediação de dados entre Londres ou Cingapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fim da vida útil do Ad Hoc Analysis | 6 de agosto de 2018 | A Adobe anunciou a intenção de encerrar a vida útil do Ad Hoc Analysis. Uma data para o fim da vida útil será compartilhada assim que estiver disponível. Para obter mais informações, visite [Descubra a Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/appmeasurement-updates.html). A versão 2.20.0 foi lançada em 5 de março de 2020.

### Novos tutoriais do Analytics {#tutorials-analytics}

| Conteúdo | Descrição |
| -----------| ---------- |
| [Adobe Labs (Pré-visualizações de tecnologia) com o Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | O Adobe Labs (Pré-visualizações de tecnologia) permite que você interaja com novas tecnologias, descubra insights valiosos e influencie o desenvolvimento futuro de recursos [!DNL Analytics] e prioridades. |
| [Publicação avançada de público na Experience Cloud](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Foram feitos aprimoramentos na [!UICONTROL Publicação avançada de público na Experience Cloud]. Agora você pode publicar públicos (segmentos) e disponibilizá-los seis vezes mais rápido. Isso reduz o tempo de latência atual de 48 horas para aproximadamente 8 horas e, possivelmente, mais rápido, dependendo do tamanho do tráfego e do segmento. |
| [Vários conjuntos de relatórios no Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Vários conjuntos de relatórios podem ser analisados em um único projeto do [!UICONTROL Workspace] selecionando conjuntos de relatórios no painel. Isso permite que você faça análises lado a lado no painel em diferentes conjuntos de dados. |

Acesse a [Página de ajuda do Adobe Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/landing/home.html) para consultar a documentação do produto.

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Novos recursos e correções no Adobe Audience Manager:

**(Atualizado em 30 de abril)**

| Recurso | Descrição |
| -----------| ---------- |  
| [Audiências preditivas](../features/algorithmic-models/predictive-audiences.md) | [!UICONTROL Audiências] preditivas ajudam a classificar uma audiência desconhecida em personas distintas, em tempo real, usando técnicas avançadas de ciência de dados. <br><br> Em um contexto de marketing, uma pessoa é um segmento de audiência definido por visitantes, usuários ou compradores potenciais, que compartilham um conjunto específico de características, como demografia, hábitos de navegação, histórico de compras etc.<br><br>[!UICONTROL Os modelos preditivos de Audiências] levam esse conceito um passo além, permitindo que você use os recursos de aprendizado de máquina do Audiência Manager para classificar audiências desconhecidas em personas distintas. <br><br>O Gerenciador de Audiências ajuda você a fazer isso calculando a propensão de sua audiência primária desconhecida para um conjunto de audiências originais conhecidas. |
| Additional [!UICONTROL Profile Merge Rules] Enhancements | [!UICONTROL As Regras] de mesclagem de Perfis oferecem aos clientes do Audiência Manager a capacidade de definir, gerenciar e ativar segmentos de audiência com base na identidade em vez de dispositivos. <br><br> A partir de 29 de abril, os clientes do Audiência Manager poderão entender melhor o detalhamento das populações de IDs de dispositivos e dispositivos para características e segmentos na segmentação individual e relatórios em massa na interface do usuário do Audiência Manager. <br><br> Isso permitirá melhores insights de identidade no Gerenciador de Audiências, dando aos clientes uma visualização holística sobre a população total de segmentos por dispositivo, pessoa e residência. As exportações em massa de IDs de dispositivos e dispositivos também serão atualizadas para refletir esses aprimoramentos.<br><br>  As atualizações específicas incluem a capacidade de: <ul><li>Relatório sobre as IDs [](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/reference/ids-in-aam.html) entre dispositivos nos relatórios [Geral](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/general-reports.html) e [de Tendência](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/trend-reports.html) ;</li><li>Aprimorar o Seletor [!UICONTROL de] características no Construtor [de](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/features/segments/segment-builder.html) segmentos para incluir populações de características destacadas de IDs [de](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/reference/ids-in-aam.html)CRM;</li><li>Criar exportações de características exatas destacadas de IDs [de](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/reference/ids-in-aam.html)vários dispositivos;</li><li>Crie exportações de características exatas destacadas de IDs [de](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/reference/ids-in-aam.html) dispositivo (deve excluir características autenticadas);</li><li>Retorna as contagens corretas de características associadas às IDs [de](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/reference/ids-in-aam.html) CRM quando solicitado usando a ferramenta [BAAAM](https://docs.adobe.com/help/pt-BR/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) .</li></ul> |
| [Principais problemas do Suporte ao cliente](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | Adicionamos uma nova seção ao nosso portal de documentação, que inclui respostas às perguntas mais frequentes recebidas pela nossa equipe de suporte ao cliente. |

* Correção de um problema que resultava em relatórios impreciso de [públicos endereçáveis](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/features/addressable-audiences.html) para segmentos que continham IDs de dispositivos móveis. Após esta atualização, você poderá ver um aumento nos [Públicos endereçáveis](https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/features/addressable-audiences.html).
* Correção de um problema que fazia com que os botões [!UICONTROL Duplicar teste] e [!UICONTROL Duplicar modelo de alocação] no [!UICONTROL Audience Lab] não funcionassem. (AAM-53388)
* Correção de um problema que fazia com que [!UICONTROL Taxa de correspondência] e [!UICONTROL Segmentar públicos endereçáveis] fossem exibidos como 0 quando um destino estava configurado para exportar UUIDs. [!UICONTROL Taxa de correspondência] e [!UICONTROL Segmentar públicos endereçáveis] agora são exibidos como 100%. (AAM-51615)
* Correção de um problema que fazia com que nomes de características que continham caracteres especiais fossem codificados em HTML duas vezes. (AAM-54001)
* Correção de um problema que impedia alguns usuários de alternarem para outros aplicativos da Adobe Experience Cloud na [!DNL Audience Manager] interface do usuário. (AAM-52917)
* Correção de um problema que impedia que alguns usuários criassem uma fonte de dados SHA256 para destinos baseados em pessoas. (AAM-53525)
* Várias melhorias de acessibilidade na interface. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Ícone](/assets/aem.png) Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Autoajuda

* **Informativo do AEM**

   Consulte o informativo mais recente do [Adobe Experience Manager](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **AEM como serviço na nuvem - Configuração do Dynamic Media Cloud Service**

   Uma nova opção está disponível ao configurar o Dynamic Media Cloud Service:

   **Publicação seletiva** - ao selecionar essa opção, significa que os ativos são publicados automaticamente apenas para pré-visualização segura e podem ser publicados explicitamente no AEM sem publicação no DMS7 para entrega no domínio público.

   Consulte [Configuração do Dynamic Media Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Dynamic Media - Smart Imaging**

   Todo o tópico da Ajuda do Smart Imaging foi atualizado com novas informações, incluindo exemplos de ativos de imagem que representam a otimização adicionada do Smart Imaging.

   Consulte [Smart Imaging](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Configuração do Dynamic Media - Modo Scene7**

   Uma nova opção Sincronizar todo o conteúdo agora está disponível na página Configuração de Dynamic Media, localizada em **[!UICONTROL Ferramentas > Cloud Services]**.

   Consulte [Criação de uma configuração do Dynamic Media](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **O AEM Assets Brand Portal oferece suporte aos ativos AEM como um serviço na nuvem**

   Agora você pode publicar ativos do AEM Assets como um serviço em nuvem no AEM Assets Brand Portal.

   Consulte [Configurar AEM Assets com Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) e [Publicar ativos no Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 lançado**

   O Adobe Asset Link 2.0 é compatível com o trabalho com vários ambientes AEM e oferece suporte ao AEM como um serviço na nuvem. O AEM oferece suporte às necessidades dos comerciantes para configurar a execução automática do fluxo de trabalho de processamento de ativos quando os ativos são carregados para uma pasta usando o Adobe Asset Link.

   Consulte [Adobe Asset Link](https://helpx.adobe.com/br/enterprise/using/adobe-asset-link.html).

### Novos tutoriais da Experience Manager

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Configurar ferramentas locais do Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Saiba mais sobre como facilitar a configuração, validação e simulação do [!UICONTROL Dispatcher] localmente. |
| [Configurar ferramentas de desenvolvimento para Projetos AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | O desenvolvimento do Adobe Experience Manager (AEM) exige que um conjunto mínimo de ferramentas de desenvolvimento seja instalado e configurado na máquina do desenvolvedor. Essas ferramentas suportam o desenvolvimento e a criação de projetos do AEM. |
| [Configurar o AEM Runtime local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | O Adobe Experience Manager (AEM) pode ser executado localmente usando o AEM como um [!UICONTROL QuickStart Jar] do SDK do Cloud Service. Isso permite que os desenvolvedores implantem e testem código, configuração e conteúdo personalizados antes de confirmá-los no controle de origem e implantá-los em um AEM como um ambiente de serviço na nuvem. |
| [Navegação](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Explore as noções básicas de navegação no AEM Assets. |
| [Versões](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Explore como o AEM cria e mantém versões de ativos. |
| [AEM - [!DNL Magento] Integração usando a [!UICONTROL Estrutura de integração do Commerce]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Este vídeo o orienta pela configuração da integração entre o AEM e o [!DNL Magento]. |
| [Introdução à pilha de arquitetura do AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | O arquétipo do projeto CIF cria um projeto CIF mínimo do Adobe Experience Manager (AEM) como ponto de partida para projetos de clientes que usam os componentes principais do CIF. |
| [Introdução ao OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Uma introdução ao OSGi, uma arquitetura modular dinâmica para aplicativos Java que é a base do Adobe Experience Manager. |
| [Introdução ao Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Uma introdução ao Java Content Repository (JCR) usado pelo Adobe Experience Manager. |
| [Introdução ao Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Uma introdução ao [!DNL Sling], uma estrutura Web RESTful de código aberto que faz parte da pilha de tecnologia subjacente do Adobe Experience Manager. |
| [Introdução à camada Autor e Publicação](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Uma introdução aos níveis de [!UICONTROL Autor] e [!UICONTROL Publicação] como parte da arquitetura no Adobe Experience Manager. |
| [Introdução ao Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Uma introdução aos recursos do Dispatcher como parte da arquitetura do AEM. |
| [Introdução ao Desenvolvimento de componentes](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Uma visão geral do desenvolvimento de componentes com o Adobe Experience Manager Sites. Inclui uma introdução a [!UICONTROL Diálogos], [!UICONTROL Modelos Sling], [!UICONTROL scripts HTL] e [!UICONTROL Bibliotecas do lado do cliente]. |
| [Arquétipo de Projetos AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | O Projetos AEM contém todos os códigos e configurações para uma implementação. O arquétipo de [!UICONTROL projeto AEM] cria um projeto do Adobe Experience Manager mínimo, baseado em práticas recomendadas, como ponto de partida para seus próprios projetos AEM. |
| [Compreensão dos componentes principais](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | Os [!UICONTROL Componentes principais] do AEM são um conjunto de componentes padrão a ser usado com o Adobe Experience Manager. |
| [Uso do AEM Quickstart Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Saiba como instalar e executar uma instância local do Adobe Experience Manager em apenas alguns minutos com o [!UICONTROL AEM Quickstart jar]. |

### Recursos adicionais de ajuda

* [AEM como um Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
* [Página inicial de aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Página inicial de aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Página inicial de aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página inicial de aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/home.html)
* [Notas de versão do Dynamic Media](https://docs.adobe.com/content/help/pt-BR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

## ![Ícone](/assets/campaign.png) [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html)

### Tutoriais do Novo Campaign Standard {#tutorials-acs}

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Substituição de Perfil - Teste de mensagens de email usando perfis direcionados](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Teste suas mensagens de email usando o recurso Substituição de perfil. |

### Recursos adicionais de ajuda do Campaign

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

[!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes ao se envolverem em todas as jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte as [!DNL Marketo] [notas de versão](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) para obter mais informações.

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
