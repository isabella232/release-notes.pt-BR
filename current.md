---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 01f2d4ae03be92da8d5d6feb1900cd4901a1b142

---


# Notas de versão da Adobe Experience Cloud - março de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Novos recursos e correções na [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.

>[!NOTE]
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: março de 2020**

Última atualização: 11 de março de 2020

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud e dos serviços principais](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) - Data de lançamento: **12 de março de 2020**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [Nova documentação e tutoriais](#selfhelp)

Procurando a página principal da ajuda? Consulte [Documentação da Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

(as datas de lançamento de produtos específicos podem variar.)

## ![Ícone](/assets/adobe.png) Status do sistema Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

**Novidades**

* Usando a Adobe ID, é possível assinar notificações de eventos com mais granularidade até a oferta de produtos e complementos. Procure esse novo recurso nos produtos da Experience Cloud, onde o processo de autoassinatura mostra as subofertas dos produtos e serviços que você deseja assinar. Esse aprimoramento deve reduzir significativamente o volume de notificações recebidas e tornar as notificações mais relevantes para os produtos e recursos utilizados.  Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Autoassinatura personalizada por subofertas de produtos | <ul><li>Autoassinatura por oferta de produtos ou complementos para produtos da Experience Cloud.</li><li>As notificações de eventos recebidas são relevantes para suas preferências de produto e ofertas de produtos.</li></ul> |
| Experiência personalizada com base nas preferências do usuário | <ul><li>A preferência de fuso horário com base na configuração do navegador é usada nas notificações por email.</li><li>Confirmação de email enviada ao assinar/cancelar a assinatura com todas as preferências selecionadas.</li></ul> |
| Melhor entrega das mensagens de eventos | <ul><li>O histórico de eventos foi classificado com base nas atualizações de eventos cronológicos.</li><li>Adição do carimbo de data e hora da resolução de eventos aos problemas principais/secundários encerrados.</li></ul> |

## ![Icon](/assets/experience-cloud.png) interface da Experience Cloud e principais serviços {#ecloud}

Novos recursos e correções na interface da Experience Cloud, incluindo administração e serviços principais (atributos do cliente, públicos-alvo, acionadores, cookies etc.).

| Recurso | Data de lançamento | Descrição |
| ----|----|---- |
| Ferramenta de administração - exibir detalhes do usuário | 26 de fevereiro de 2020 | Os administradores podem exibir uma lista classificável e filtrável de todos os usuários da Experience Cloud e seus detalhes na nova Ferramenta de administração. Os detalhes do usuário incluem o acesso ao produto, as funções e as últimas informações acessadas de um usuário. Consulte a ajuda da [Ferramenta de administração da Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) para obter detalhes. |

### Domínio de produto unificado

A Adobe está atualizando o domínio e o cabeçalho da interface para unificar e melhorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar a experiência de maneiras pequenas, mas importantes. Eles não alterarão seus fluxos de trabalho atuais.

As atualizações incluem:

* Novos URLs das soluções: `experience.adobe.com/<application name>`:
   * Todos os produtos acabarão por adotar esse padrão de URL. Procure novos URLs para se tornarem efetivos durante o mês.
   * Compatibilidade de navegador: os navegadores compatíveis incluem [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versões mais recentes). **Observação:** embora a interface da Experience Cloud seja compatível com esses navegadores, as soluções individuais podem não ser compatíveis com todos os navegadores. (Por exemplo, o [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) não é compatível com o [!DNL Opera] e o [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) não é compatível com o [!DNL Safari].)
   * (Somente para o [!DNL Safari]) A alteração de domínio pode causar problemas de cookie no [!DNL Safari]. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do [!DNL Safari], os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Experience Cloud poderá funcionar nesse novo domínio.
* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do produto aprimorada: a [!UICONTROL Experience League] está integrada ao produto para que a pesquisa de ajuda também inclua resultados de fóruns da comunidade e conteúdo em vídeo. Essa alteração simplifica o acesso a mais conteúdo e ajuda a aproveitar ao máximo a Experience Cloud. Além disso, clique em **[!UICONTROL Ajuda]** > **[!UICONTROL Feedback]** para relatar problemas ou compartilhar suas ideias com a Adobe.
* Notificações aprimoradas: o menu suspenso [!UICONTROL Notificações] agora tem duas guias, uma para suas próprias notificações de produtos e outra para anúncios de produtos globais.

**Observação:** a página do [!UICONTROL Feed] foi substituída em janeiro de 2020. Procure um aviso de desativação no produto.

Para obter a documentação do produto, consulte a ajuda da [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## ![Plataforma de experiência de ícone](/assets/platform.png){#platform}

Notas de versão da [!UICONTROL Experience Platform], do [!UICONTROL Experience Platform Launch], do [!UICONTROL Serviço de identidade] e dos marcadores de segurança.

* [Notas de versão da Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Orquestração da jornada](#journey)
* [Mobile Services e SDKs móveis](#mobile)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html)  (Todos os produtos da Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para obter as notas de versão e a documentação do produto.

### Orquestração da jornada {#journey}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

A versão do primeiro trimestre foi publicada. [Ler mais](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

**Recursos adicionais**

[Documentação](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services e SDKs móveis {#mobile}

**iOS v4.19.1**

* Geral - resolução de uma possível falha quando as enumerações [!UICONTROL Swift] são incluídas nos dados de contexto para chamadas de rastreamento.
* [!DNL Target] - Agora a ID da [!DNL Target] sessão será adicionada como parâmetro de dados de contexto `a.target.sessionId` na ocorrência interna do [!UICONTROL Analytics para Target] enviada para o Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] - Agora a ID da [!DNL Target] sessão será adicionada como parâmetro de dados de contexto &quot;a.target.sessionId&quot;  na ocorrência interna do [!UICONTROL Analytics para Target] enviada para o Adobe Analytics.

## ![Ícone](/assets/analytics.png) [!DNL Analytics] {#analytics}

Data de lançamento: **12 de março de 2020**

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm) 

Para obter a documentação do produto, consulte a [Página inicial de ajuda do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

* **Vários conjuntos de relatórios na[!UICONTROL Analysis Workspace ]**: Agora você pode trazer dados de vários conjuntos de relatórios para um único projeto da[!UICONTROL Analysis Workspace]para visualização em painéis lado a lado.[Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**: este recurso permite publicar segmentos na Experience Cloud em 8 horas (em vez do tempo de processamento anterior de 48 horas). [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - modelo do tutorial de treinamento**: este novo modelo padrão mostra as terminologias e etapas comuns para criar sua primeira análise no Workspace. Está disponível como modelo padrão no modal [!UICONTROL Novo projeto] e substitui o projeto de amostra atual para novos usuários que não têm outros projetos na lista.

#### Correções

* Correção de um problema no [!UICONTROL Reports &amp; Analytics] que impedia o download de `.xls` relatórios. Esse problema afetava os clientes que utilizavam moedas diferentes do dólar e do euro. (AN-206541, AN-204008)
* A implantação de um novo shell corrigiu vários problemas do cliente relacionados à alternância entre as organizações da Experience Cloud.(AN-200844, AN-186920)
* Correção de um problema em que fazer um detalhamento no item de linha _Não especificado_ (ou em alguns outros itens de linha do relatório), ao não incluir _Não especificado (Nenhum)_ nos filtros de pesquisa do detalhamento, não retornaria os resultados no detalhamento.
* Correção de um problema que ocorria ao usar uma dimensão classificada, os totais da métrica de entrada ou saída não correspondiam ao total do item de linha em um detalhamento.
* Correção de um problema em que os modelos de primeiro e último contatos no Attribution IQ não calculavam o crédito corretamente para alguns itens de linha em algumas dimensões da caixa.
* Correção de um problema em que detalhar uma dimensão de data por outra dimensão de data retornava resultados incorretos.
* Correção de um problema em que, às vezes, as métricas de entrada ou saída eram contadas incorretamente quando aplicadas a &quot;Não especificado&quot; em um relatório de dimensão classificado.

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição  ou atualização | Descrição |
| -----------| ---------- | ---------- |
| EOL da configuração **[!UICONTROL Nível de conversão]** | 3 de março de 2020 | A configuração inoperante [Nível de conversão](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) em **[!UICONTROL Ferramentas de administração]>[!UICONTROL Conjuntos de relatórios]>[!UICONTROL Configurações gerais da conta]** será removida da interface do usuário em 12 de março de 2020. |
| EOL do **[!UICONTROL Arquivo do painel]** | 3 de março de 2020 | A configuração **[!UICONTROL Exibir arquivo]** em **[!UICONTROL Gerenciar painéis]** no [!UICONTROL Reports &amp; Analytics], não estará mais disponível a partir de 12 de março de 2020. |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Novo domínio do Adobe Analytics | 18 de dezembro de 2019 | Em 16 de janeiro de 2020, o Adobe Analytics começou a migrar para um novo domínio - `https://experience.adobe.com/analytics.`<br>**Observação:** essa alteração se aplica a todos os usuários que acessam o Analytics com sua Adobe ID ou Enterprise ID.<ul><li>O domínio pode causar problemas de cookie ao carregar o Analytics no Safari. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do [!DNL Safari], os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Analytics poderá funcionar nesse novo domínio da Adobe Experience Cloud. Você pode usar outros navegadores sem problemas, pois isso afeta somente os usuários do [!DNL Safari].</li><li>A alteração de domínio pode fazer com que o [!UICONTROL Activity Map] pare de funcionar para alguns clientes [em casos específicos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fim da vida útil - APIs antigas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Cingapura, não apoiaremos mais a intermediação de dados entre Londres ou Cingapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). A versão 2.20.0 foi lançada em 5 de março de 2020.

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Novos recursos e atualizações do Audience Manager:

### Correções e melhorias {#aam-fixes-and-improvements}

* Correção de um bug em que os clientes não podiam atualizar o nome do segmento devido à falta de permissão RBAC [!UICONTROL VIEW_ALL_DESTINATIONS]. A permissão [!UICONTROL VIEW_ALL_DESTINATIONS] não deve ser necessária para atualizar um segmento. Para obter mais informações sobre permissões RBAC, consulte [Administração (controles RBAC)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Correção de um bug no [Data Explorer](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html), no qual alguns clientes não conseguiam visualizar o conteúdo na seção de informações básicas e os operadores no construtor de expressões, ao criar características baseadas nos sinais do [!UICONTROL Data Explorer]. (AAM-53130)
* Correção de um bug em que alguns clientes não podiam carregar a interface do [!UICONTROL Audience Marketplace]. (AAM-52070)
* Correção de um bug na [!UICONTROL API de segmentos], onde, devido a alguns segmentos sem descrição, a interface congelava quando os usuários tentavam acessar esses segmentos e os usuários tinham que sair dessa página. (AAM-53071)
* Várias melhorias de acessibilidade na interface. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058, AAM-49392)

## ![Ícone](/assets/aem.png) Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Atualizações do produto

* **AEM 6.5.4.0**
O AEM 6.5, Service Pack 4.0 (6.5.4.0 lançado em 5 de março de 2020), é uma atualização importante que inclui novos recursos, principais melhorias para o cliente, melhor desempenho, estabilidade e segurança, lançados desde a disponibilização geral do AEM 6.5, em abril de 2019.
   * [Novidades do Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Resultados da versão do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   O AEM 6.4, Service Pack 8.0 (6.4.8.0, lançado em 5 de março de 2020), é uma atualização importante que inclui correções essenciais para o cliente, lançadas desde a disponibilização geral do AEM 6.4 em abril de 2018.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   O AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8, lançado em 5 de março de 2019), é uma atualização importante que inclui correções essenciais para o cliente, lançadas desde a disponibilização geral do AEM 6.3 em abril de 2017.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   O AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 lançado em 5 de março de 2020), altera a forma como o AEM Assets é configurado com o [!UICONTROL Brand Portal.] Além disso, a versão inclui outros aprimoramentos e correções de erros.
   * [Notas de versão](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Autoajuda

* **AEM como um Cloud Service - Permissões baseadas em funções**

   O Cloud Manager tem funções pré-configuradas com permissões apropriadas. Cada uma das funções tem permissões específicas, tarefas pré-configuradas ou permissões associadas a cada função. O tópico de ajuda [Permissões baseadas em funções](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) identifica as funções disponíveis e as funções que podem executá-las.

* **AEM como um Cloud Service - Dispatcher**

   As seções de invalidação de cache do [Dispatcher e CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) e do [Explicit Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) foram atualizadas para esclarecer as opções disponíveis e seu funcionamento.

* **Configurar o AEM Assets com o Brand Portal**

   Agora o AEM Assets está configurados com o [!UICONTROL Brand Portal] por meio da E/S da Adobe, que obtém um token IMS para autorização do locatário do Brand Portal. Anteriormente, ele era configurado na interface Clássica por meio do [!UICONTROL Gateway OAuth herdado.]
Consulte [Configurar o AEM Assets com o Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM como um Cloud Service - Recorte inteligente na Mídia dinâmica**

   Uma nova opção está disponível no AEM como um Cloud Service ao trabalhar com o Recorte inteligente no componente de Mídia dinâmica:

   **Ativar correspondência de proporção de aspecto** - Selecione esta opção para permitir que a Mídia dinâmica escolha uma representação de recorte inteligente que melhor corresponda à proporção de aspecto da imagem original.
Consulte [Quando trabalhar com o Recorte inteligente](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Comunidade

* **Webinários do AEM Skill Builder**

   * AEM Sites - A partir de 17 de março de 2020, saiba mais sobre os componentes da criação de conteúdo e os conceitos e operações fundamentais do AEM Sites. [Inscreva-se já](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * AEM Assets - A partir de 19 de março de 2020, aprimore sua experiência em gerenciamento de ativos digitais, além de saber mais sobre as noções básicas do portal da marca, [!UICONTROL Mídia dinâmica], [!UICONTROL Link de ativos] e muito mais. [Inscreva-se já](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

### Recursos adicionais

* [AEM como um Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [Página inicial de aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página inicial de aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notas de versão do Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![Ícone](/assets/campaign.png) [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Campaign Classic

* [Atualização 19.1.4 do Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Recursos adicionais

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planejamento de versão](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Atualizado em 10 de fevereiro de 2020, para lançamento em 8 de fevereiro:

| Exibir | Recurso |
|------|---------|
| [!UICONTROL Portfólios] | Agora é possível adicionar [!DNL Yahoo!] campanhas da Rede de exibição do Japão (YDN) para portfólios, a fim de otimizar os orçamentos da campanha e os lances de nível de grupo de anúncios. A mesma licitação é aplicada a todos os anúncios em um grupo de publicidade. Os dados para campanhas da Rede de exibição do Japão são incluídos nas simulações do portfólio. |
| [!UICONTROL Pesquisar] > [!UICONTROL Bulksheets] | Agora você pode criar, editar e excluir anúncios de pesquisa responsivos do Google (RSAs) usando bulksheets. Anteriormente, o suporte estava disponível somente por meio da interface de gerenciamento de campanha padrão em **[!UICONTROL Pesquisar]** > **[!UICONTROL Campanhas]** |
| [!UICONTROL Pesquisar] > [!UICONTROL Campanhas, Relatórios] | As métricas de destaque do Google Ads `Impr. (Abs. Top) %` e `Impr. (Top) %` agora estão disponíveis em todos os relatórios básicos e exibições de gerenciamento de campanha no nível da entidade, exceto para grupos de produtos de compras, nos relatórios de [!UICONTROL Compartilhamento de impressão diária da campanha] e [!UICONTROL Compartilhamento de impressões diárias de palavra-chave], bem como nas exibições de rótulos e restrições. |

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Para ver as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ícone](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] é uma solução completa para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes ao se envolverem em todas as jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Data de lançamento: 21 de fevereiro de 2020

* **Ação de fluxo _Alterar proprietário na Microsoft_ do Microsoft Dynamics**: altere um cliente potencial ou proprietário de contato diretamente do Marketo Engage.
* **Melhorias nas chamadas de API:**
   * APIs de gerenciamento de usuários
   * APIs de esquema de objeto personalizadas
   * APIs de regras de redirecionamento de página de aterrissagem
* **Cache do descritor de formulário:** melhorias nas páginas de aterrissagem e formulários.

Consulte as notas de versão [!DNL Marketo] de [fevereiro de 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) para obter mais informações.

### Recursos futuros

Os seguintes recursos serão lançados ao longo do trimestre:

| Recurso | Descrição |
|------|---------|
| [!DNL Bizible] | <ul><li>Nova segmentação baseada em conta</li><li>Salvar filtros específicos do painel</li><li>Exportar painéis Bizible como PDFs</li></ul> |
| Conexão de vendas | Compor atualizações/aprimoramentos da Janela e do Centro de comando |

### Anúncios

**Centro de Sucesso do Marketo Engage:** lançamento em fevereiro de 2020. O Centro de sucesso é um centro de ajuda no produto que permite pesquisar em Documentos de produto e na Comunidade, iniciar guias tutoriais, acessar conteúdo de adoção e muito mais. Observação: esse recurso será lançado como um beta na ANZ para a América do norte posteriormente neste trimestre.

### Desativações

* **Parâmetro &quot;_method&quot; da API de ativo:** depois de setembro de 2020, os endpoints da API de ativos não aceitarão mais &quot;_method&quot; para transmitir os Parâmetros de consulta em um corpo POST para ignorar as limitações de comprimento de URI.
* **Desativação do suporte ao Internet Explorer:** a partir do lançamento realizado em 31 de julho de 2020, a interface do usuário do Marketo Engage não será mais compatível com o Internet Explorer.

Para obter as notas de versão cumulativas e históricas, consulte [Notas de versão do Marketo](https://docs.marketo.com/x/CgA6Ag).

## ![Ícone](/assets/experience-cloud.png) Nova documentação e tutoriais {#selfhelp}

Artigos e vídeos de autoajuda novos e recentes. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Solução | Conteúdo | Descrição |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Vídeo - [Criação de várias páginas de categorias e produtos](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Aprenda a criar um projeto mínimo de CIF do Adobe Experience Manager (AEM) como ponto de partida para projetos de cliente, usando os componentes principais de CIF. Aplique tema e estilos de CSS aos componentes e inspecione um novo projeto de CIF do AEM, gerado pelo arquétipo. Além disso, saiba como são organizados o CSS e o JavaScript usados pelos componentes principais de CIF. |
| [!UICONTROL AEM Forms] | Artigo - [Autenticar para o autor do AEM usando OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Aprenda a configurar seu aplicativo no portal OKTA e saiba mais sobre as configurações que você geralmente usa para registrar o novo aplicativo. |
| [!UICONTROL AEM Commerce] | Tutorial - [Personalizar os componentes principais de CIF](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Analise vários pontos de extensão diferentes fornecidos pelos componentes principais de CIF e pelo AEM em geral. Os Componentes principais de CIF fornecem um conjunto padrão de componentes do Commerce que podem ser usados para acelerar um projeto que integra as soluções Adobe Experience Manager (AEM) e Magento. |
| [!DNL Adobe Campaign] - Destinos do público-alvo | Vídeo - [Criar um público-alvo...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Crie um público-alvo no Campaign Standard usando o [!UICONTROL Construtor de segmentos da Adobe Experience Platform]. Você pode acessar esse recurso diretamente no Adobe Campaign Standard por meio dos módulos do [!UICONTROL Audiences]. |
| [!DNL Adobe Campaign] - Destinos do público-alvo | Vídeo - [Ativação de públicos-alvo da Adobe Experience Platform em um fluxo de trabalho de marketing](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Aprenda a ativar o [!UICONTROL Público-alvo de consulta dos serviços de dados] em um fluxo de trabalho, usando a atividade [!UICONTROL Ler público-alvo]. |
| [!DNL Adobe Campaign] | Tutorial - [Notificação por push com Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Envie notificações por push personalizadas e segmentadas para dispositivos móveis iOS e Android. Este tutorial mostra as etapas envolvidas no envio de notificações por push do Adobe Campaign e no recebimento dessas notificações no aplicativo Android. |
| [!DNL Adobe Campaign] | Vídeo - [Criar uma notificação por push](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Crie uma notificação por push no Adobe Campaign Standard. É possível enviar notificações por push personalizadas e segmentadas para dispositivos móveis iOS e Android. |
| [!DNL Adobe Campaign] - Conector de dados AEP | Vídeo - [Verifique o status de um trabalho de assimilação de dados](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Aprenda a verificar o status de um trabalho de assimilação de dados e se os dados foram assimilados do Adobe Campaign Standard para a Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Conector de dados AEP | Vídeo - [Modificar o mapeamento de dados](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Aprenda a verificar o status e modificar o mapeamento de dados. |
| [!DNL Adobe Campaign] - Conector de dados AEP | Vídeo - [Mapear os eventos de experiência](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Aprenda a mapear os eventos de experiência na Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Conector de dados AEP | Vídeo - [Mapear os recursos personalizados](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Aprenda a mapear diferentes tipos de dados entre o Adobe Campaign Standard e a Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Conector de dados AEP | Vídeo - [Noções básicas sobre o conector de dados da Adobe Experience Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Aprenda a disponibilizar os dados na Adobe Experience Platform, mapeando os dados XTK (dados assimilados no Campaign) para dados do Experience Data Model (XDM) na Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Conector de dados AEP | Vídeo - [Mapear os dados da tabela de propagação](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Aprenda a mapear os dados de propagação / perfis de teste com a Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Destinos do público-alvo | Vídeo - [Alterar a dimensão de direcionamento de uma entrega para um Público-alvo da plataforma](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Aprenda a alterar a dimensão de direcionamento de uma entrega para um Público-alvo da plataforma, fora da tabela de perfil principal no Adobe Campaign Standard. |
| [!DNL Adobe Campaign] | Vídeo - [Gerenciamento de big data no Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Utilize o conector Snowflake no Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - Destinos do público-alvo | Artigo - [Destinos do público-alvo (BETA) - Visão geral](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Aprenda a utilizar os dados de perfil centralizados e consolidados da Adobe Experience Platform para campanhas de marketing no Adobe Campaign Standard. |
| [!DNL Adobe Target] - SDK móvel | Tutorial - [Personalizar as experiências do aplicativo com o Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implemente o Adobe Target em seu próprio aplicativo Android. Valide a configuração do SDK do Mobile Services e implemente [!DNL Target] solicitações como pré-busca de conteúdo, bloqueio de solicitações e muito mais. |
| Adobe Analytics | Vídeo - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Assista a clips preparados da &quot;super session&quot; de alta tecnologia na Summit 2019. |
| Adobe Analytics | Vídeo - [Introdução às métricas calculadas na Análise da jornada do cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Analise os conceitos básicos da criação de [!UICONTROL Métricas calculadas] na [!UICONTROL Análise da jornada do cliente]. |
| Adobe Analytics | Vídeo - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Assista a clips preparados da sessão de viagem e hospitalidade do Summit 2019. |
| Adobe Analytics | Vídeo - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Veja os clipes preparados da sessão de varejo no Summit 2019. |
| Adobe Analytics | Vídeo - [Caso de uso do cliente: Accent Group investe na experiência do cliente para impulsionar vendas](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Veja como o Accent Group usa a Adobe Experience Cloud para criar experiências digitais perfeitas. |
| Adobe Analytics | Vídeo - [Caso de uso do cliente: ServiceNow obtém os insights certos para se conectar com os prospectos](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Descubra como a [!DNL ServiceNow] obtém dados acionáveis de seus canais de marketing e aumenta o ROI em publicidade de pesquisa paga com a Adobe Advertising Cloud e o Adobe Analytics. |
| Adobe Analytics | Vídeo - [Adobe Analytics - É mais do que dados, é inteligência do cliente](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Saiba mais sobre o marketing orientado por dados e como levar a maturidade da sua análise, dos dados aos insights para a ação. |
| Adobe Analytics | Vídeo - [Adobe Sensei e Adobe Analytics - Versão estendida](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Veja os principais recursos do Adobe Analytics alimentados pela Adobe [!DNL Sensei,], incluindo [!UICONTROL Detecção de anomalias,] [!UICONTROL Análise de contribuição,] [!UICONTROL Alertas inteligentes,] [!UICONTROL Clustering,] [!UICONTROL IQ de segmentos,] e [!UICONTROL Modelagem de propensão.] |
| Adobe Analytics | Vídeo - [Como a Adobe Analysis Workspace pode mudar sua empresa](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Saiba como você pode realizar análise ad hoc, análise flexível, análise de coorte e análise de fallout usando a [!UICONTROL Analysis Workspace]. Você também pode compartilhar o ambiente de trabalho da análise com todos na sua empresa. Além disso, a função de arrastar e soltar permite que todos analisem os dados com facilidade e obtenham insights rapidamente. |
| Adobe Analytics | Vídeo - [Caso de uso do cliente: a Home Depot inova com o Gerenciamento de experiência do cliente](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Saiba como a [!DNL Home Depot] usa as soluções da Adobe para criar fidelidade à marca e satisfação do cliente com uma experiência personalizada de compras. |
| Adobe Analytics | Apresentação - [Noções básicas sobre a análise da jornada do cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Saiba como a [!UICONTROL Análise da jornada do cliente] da Adobe, um serviço de aplicativos integrado no [!DNL Adobe Experience Platform], traz a [!UICONTROL Analysis Workspace] para a Experience Platform. Este recurso permite a análise de vários canais em qualquer um dos seus conjuntos de dados [!DNL Adobe Experience Platform]. |
| Adobe Analytics | Vídeo - [Atribuição entre canais no CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Saiba como você pode usar as visualizações para mostrar a atribuição (dar crédito) entre canais na [!UICONTROL Análise da jornada do cliente]. |
| Adobe Analytics | Artigo - [Dicas do cliente para continuar sua jornada de aprendizado no Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Conheça três clientes da Adobe que têm dicas e truques para oferecer a você sobre como aproveitar ao máximo o Adobe Analytics. |
| Adobe Analytics | Vídeo - [Criar visualizações entre canais no CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Descubra como a [!UICONTROL Análise da jornada do cliente] permite criar visualizações que incluem dados de vários conjuntos de dados em vários canais, incluindo a mesclagem de dados por visitante. |
| Adobe Analytics | Vídeo - [Transferir as métricas calculadas do Adobe Analytics para a Análise da jornada do cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Encontre dicas para recriar as [!UICONTROLCmétricas calculadas] do Analytics na [!UICONTROL Análise da jornada do cliente]. |
