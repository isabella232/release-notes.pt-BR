---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 80852c2797ad1a26b6c4a806fa2cf3ef59f84707

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
* [!DNL Analytics](#analytics)
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
* [Boletins e conselhos de segurança](https://helpx.adobe.com/br/security.html)  (Todos os produtos da Adobe)

## ![Ícone](/assets/analytics.png) [!DNL Analytics] {#analytics}

Data de lançamento: **16 de abril de 2020**

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)  (Atualizado em 7 de abril de 2020)
* [AppMeasurement](#appm) 
* [Novos tutoriais do Analytics](#tutorials-analytics)

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Análise]de jornada do cliente: Preenchimento retroativo de conjunto de dados [!UICONTROL automatizado] | Esta nova opção permite importar todos os dados históricos de uma conexão no [!UICONTROL Customer Journey Analytics]. (Documentação a seguir) |
| Suporte do Analytics para o [!UICONTROL Experience Edge] | Agora é possível encaminhar dados enviados ao [!UICONTROL Experience Edge] para o Analytics. |
| [!UICONTROL Área de trabalho]: Criar tabelas de forma livre automaticamente a partir de um estado em branco | Anteriormente, não era possível soltar componentes diretamente em um projeto em branco ou em um painel em branco. primeiro você tinha que adicionar uma tabela de forma livre. Agora é possível soltar componentes diretamente em um projeto ou painel em branco, e uma tabela de forma livre será criada automaticamente para você em um formato recomendado. Além disso, foram feitos aprimoramentos no modo como tipos de componentes mistos (por exemplo, dimensões e métricas) são tratados quando descartados em uma tabela de forma livre em branco. |

#### Correções do Analytics

* Correção de um problema que causava a ausência de dados de segmento do Analytics no Gerenciador de Audiências. (AN-206221)
* Correção de um problema com o processamento das Fontes  de Dados mostrando as datas erradas. (AN-213604)
* Correção de um problema no qual os arquivos de classificação não eram carregados corretamente no FTP. (AN-214102)
* Correção de um problema no qual o método da API `Segments.Get` não retornava uma resposta completa. (AN-206210)
* Correção de um problema em que os itens de linha da tabela eram convertidos em caracteres especiais no download de [!DNL Workspace] PDF. (AN-196153)
* Correção de um problema em que a chamada da API 1.4 do Adobe Analytics `visattrcustomeridcustomerattributes` não funcionava corretamente. (AN-186873)
* Correção de um problema com dados que apareciam em relatórios, mas que estavam ausentes no Feed [!UICONTROL de]dados. (AN-211923)
* Correção de um problema que impedia a cópia das permissões de Perfil  do produto. (AN-211113)
* Correção de um problema em que os usuários com Federated IDs não conseguiam fazer logon no Construtor de relatórios. (AN-207750)
* Correção de um problema em que os dados do [!UICONTROL AdWords] não eram exibidos no [!UICONTROL Advertising Analytics]. (AN-213249)
* Correção de um problema em que os dados de classificação não eram exibidos na visualização de tendência. (AN-212761)
* Correção de um problema que resultava em uma contagem de segmentos publicados incorreta no Gerenciador [!UICONTROL de segmentos]. (AN-213374)

#### Correções adicionais do Analytics

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição   ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Alteração na forma como [!UICONTROL as Entradas/Saídas] são calculadas no [!UICONTROL Workspace] | 7 de abril de 2020 | Na área de trabalho [!UICONTROL da]Análise, a partir de março de 2020, alteramos a forma como o valor _Nenhum_ interage com [!UICONTROL Entradas/Saídas]. Como agora você pode ativar e desativar _os não_ na área de trabalho [!UICONTROL da]Análise, aplicamos o valor _Nenhum_ após a entrada ou saída, enquanto (para eVars) ele costumava ser aplicado antes. Por exemplo, suponha que a primeira ocorrência de uma visita não tenha valor para eVars, mas a segunda ocorrência tem. Em [!UICONTROL Relatórios e análises] , será exibido como _Não especificado_ para a Entrada, mas na Área de trabalho [!UICONTROL da] Análise será exibido como o valor na segunda ocorrência. |
| EOL da configuração **[!UICONTROL Nível de conversão]** | 3 de março de 2020 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/pt-BR/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| EOL do **[!UICONTROL Arquivo do painel]** | 27 de março de 2020 | A configuração **[!UICONTROL Exibir arquivo]** em **[!UICONTROL Gerenciar painéis]** no [!UICONTROL Reports &amp; Analytics] não estará mais disponível a partir de março de 2020. |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Novo domínio do Adobe Analytics | 18 de dezembro de 2019 | Em 16 de janeiro de 2020, o Adobe Analytics começou a migrar para um novo domínio - `https://experience.adobe.com/analytics.`<br>**Observação:** essa alteração se aplica a todos os usuários que acessam o Analytics com sua Adobe ID ou Enterprise ID.<ul><li>O domínio pode causar problemas de cookie ao carregar o Analytics no Safari. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do [!DNL Safari], os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Analytics poderá funcionar nesse novo domínio da Adobe Experience Cloud. Você pode usar outros navegadores sem problemas, pois isso afeta somente os usuários do [!DNL Safari].</li><li>A alteração de domínio pode fazer com que o [!UICONTROL Activity Map] pare de funcionar para alguns clientes [em casos específicos](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fim da vida útil - APIs antigas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Cingapura, não apoiaremos mais a intermediação de dados entre Londres ou Cingapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fim da vida útil do Ad Hoc Analysis | 6 de agosto de 2018 | A Adobe anunciou a intenção de encerrar a vida útil do Ad Hoc Analysis. Uma data para o fim da vida útil será compartilhada assim que estiver disponível. Para obter mais informações, visite [Descubra a Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/appmeasurement-updates.html). A versão 2.20.0 foi lançada em 5 de março de 2020.

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
| [Principais problemas de suporte ao cliente](../support-issues/support-issues-overview.md) | Adicionamos uma nova seção ao nosso portal de documentação, que inclui respostas às perguntas mais frequentes recebidas pela nossa equipe de suporte ao cliente. |

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
