---
title: Notas de versão da Adobe Experience Cloud
description: Notas de versão da Adobe Experience Cloud
doc-type: release notes
last-update: July 2020
author: mfrei
translation-type: tm+mt
source-git-commit: bfcc23bd8eaf02956fd2dacf711ce774d6bddb85
workflow-type: tm+mt
source-wordcount: '4377'
ht-degree: 99%

---


# Notas de versão da Adobe Experience Cloud - Julho de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Esta página descreve novos recursos, correções e avisos importantes na [!DNL Adobe Experience Cloud]. Ela também destaca a nova documentação, cursos de treinamento e tutoriais em vídeo para ajudar você a aproveitar ao máximo a Experience Cloud.

>[!NOTE]
>
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras.

**Data de lançamento: 16 de julho de 2020**

As datas de lançamento do produto podem variar. Verifique frequentemente se há atualizações.

Última atualização: **14 de julho de 2020**

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Orquestração da jornada](#journey-orch)
* [Analytics](#analytics) e [Customer Journey Analytics](#cust-journey)   (Atualizado em: 14 de julho de 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/br/primetime/user-guide.html) (links para a página de ajuda do Primetime)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insight da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/adobe.png) Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

Lançamento: **21 de maio de 2020**

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

**Menu de interface atualizado**

Na Experience Cloud, a versão de **16 de julho de 2020** atualiza o menu suspenso do Application Switcher. Ele foi simplificado para que os logotipos de solução sejam removidos e o menu exibe apenas os aplicativos e serviços aos quais você tem acesso.

Consulte a [documentação do produto](https://docs.adobe.com/content/help/pt-BR/core-services/interface/experience-cloud.html) da interface da Experience Cloud para ver um exemplo.

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

Notas de versão da [!DNL Experience Platform] e serviços de aplicativos, incluindo [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] e boletins de segurança.

Data de lançamento: **10 de junho de 2020**

Consulte as [notas de versão da Experience Platform](https://docs.adobe.com/content/help/pt-BR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) para obter as informações mais recentes da Experience Platform.

## ![Ícone](/assets/experience_platform_appicon_24.png) do Journey Orchestration {#journey-orch}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

### Recursos adicionais do Journey Orchestration

[Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **16 de julho de 2020**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Novos recursos no Media Analytics](#media-aa)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)   (Atualizado em: 13 de julho de 2020)
* [Novos cursos e tutoriais do Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- |-------|
| CDA: Arranque em campo | 27 de julho de 2020 | Um novo método para Analytics entre dispositivos que permite usar uma variável personalizada para ajudar a identificar visitantes. |
| Workspace: novas predefinições de intervalo de datas | 16 de julho de 2020 | Foram adicionados 4 novos intervalos de datas (_Esta semana/mês/trimestre/ano_ (exceto hoje)) para que os usuários possam escolher entre intervalos de datas que não incluem dados de dias parciais a partir de hoje. |
| API de reparo de dados - beta público | 14 de julho de 2020 | A [!UICONTROL API de reparo de dados] fornece um mecanismo para excluir ou editar determinados dados existentes do Adobe Analytics. As solicitações de [!UICONTROL Reparo de dados] são feitas enviando uma definição de tarefa para a [!UICONTROL API de reparo de dados], que inclui o conjunto de relatórios, o intervalo de datas, as variáveis e as ações que serão aplicadas aos dados. Após o lançamento do beta público, a [!UICONTROL API de reparo de dados] oferecerá suporte à exclusão de dados do [!UICONTROL Activity Map]. Recursos adicionais serão lançados posteriormente. Entre em contato com o Atendimento ao cliente para participar do beta público da API de reparo de dados. [Saiba mais...](https://github.com/AdobeDocs/analytics-2.0-apis/blob/master/data-repair.md) |

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- |-----|
| Nenhum recurso novo este mês |  |  |

### Novos recursos no [!UICONTROL Media Analytics] {#media-aa}

Data de lançamento: **16 de julho de 2020**

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| -----------| ---------- | ---------- |
| [Dispositivos e plataformas compatíveis](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/supported-devices.html) | 18 de junho de 2020 | A Extensão Media Launch com SDK AEP agora é compatível com os seguintes dispositivos OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [Dispositivos e plataformas compatíveis](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/supported-devices.html) | 18 de junho de 2020 | A Extensão Media Launch com SDK AEP agora é compatível com os seguintes dispositivos OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Rastreamento do estado do player](https://docs.adobe.com/content/help/pt-BR/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 de maio de 2020 | Os clientes do [!UICONTROL Media Analytics] podem capturar a interação do visualizador durante a reprodução usando um conjunto padrão de variáveis de solução para tela cheia, legendas ocultas, mudo, picture-in-picture e em foco. Você também tem flexibilidade para criar estados personalizados do player. As variáveis de Rastreamento de estado do player estão disponíveis para relatórios no [!UICONTROL Analysis Workspace]. Esse recurso exige um dos seguintes: <ul><li>Media [!DNL JavaScript] SDK 3.0 ou superior</li><li>Para uso com o SDK [!DNL Adobe Experience Platform] (AEP):</li><li>[!UICONTROL Extensão do Media Analytics] (para Web): [!UICONTROL Adobe Media Analytics] (SDK 3.x) for Audio and Video v1.0 ou superior</li><li>[!UICONTROL Extensão do Media Analytics] (para dispositivos móveis): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 ou superior</li><li>[!UICONTROL Coleção de mídia]</li></ul> |

### Correções no Adobe Analytics {#aa-fixes}

* Correção de um problema que ocorria após a alternância para um conjunto de relatórios com uma moeda diferente. O gráfico de linhas do [!UICONTROL Workspace] não refletia a moeda correta. (AN-216655)
* Correção de problemas com visualizações ilegíveis em PDFs baixados. (AN-217949)
* Correção de um problema que causava um erro ao adicionar uma variável de Hierarquia a um conjunto de relatórios. (AN-211974)
* Correção de um problema que ocorria ao editar um feed de dados associado a um conjunto de relatórios com um fuso horário diferente do conjunto de relatórios [!UICONTROL Reports &amp; Analytics] selecionado no momento. (AN-222474)
* Correção de um problema em que o [!UICONTROL Construtor de regras de classificação] não funcionava. (AN-219662)
* Correção de vários problemas com regras de classificações e classificações. (AN-223492, AN-220654, AN-219662, AN-223260)
* Correção de um problema em que o mesmo segmento retornava dados diferentes em um conjunto de relatórios virtual em comparação ao conjunto de relatórios pai. (AN-201074)
* Correção de um problema que impedia o download das configurações do conjunto de relatórios. (AN-223690)
* Correção de um problema nos [!UICONTROL Alertas inteligentes] que impedia que o link de email da _Recusa da programação_ funcionasse. (AN-223875)
* Correção de um problema que exibia uma moeda incorreta para um conjunto de relatórios virtual. (AN-224781)
* Correção de um problema com erros de _componentes ausentes_ em conjuntos de relatórios virtuais. (AN-224782)
* Correção de um problema em que a análise de uma classificação de uma dimensão por outra poderia retornar resultados vazios quando usada com uma métrica calculada com alocação de participação definida. (AN-214089)

#### Outras correções do Adobe Analytics

AN-222672, AN-222813; AN-222892; AN-223272, AN-223432; AN-224062; AN-224108; AN-224163; AN-224339; AN-224456; AN-224449; AN-224552; AN-224553; AN-224786

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição   ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Fim da vida útil dos conectores de dados da Adobe | 13 de julho de 2020 | Os Conectores de dados da Adobe são alimentados por tecnologia herdada que não é mais viável ou compatível. Temos um novo padrão no [Programa de parceiros Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud) que deve ser adotado para todas as integrações que desejam continuar sendo oferecidas e tendo suporte. A data oficial do fim da vida útil ainda será determinada, mas prevemos que seja nos próximos 12 a 18 meses (meados de 2021 até o final de 2021). [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/import/dataconnectors/data-connectors-eol.html) |
| Mapeamento do conjunto de relatórios para organização IMS | Julho de 2020 | A ferramenta de mapeamento do conjunto de relatórios será descontinuada em novembro de 2020. Esse recurso capacita integrações como o Advertising Analytics e a publicação de segmentos da Experience Cloud no Adobe Analytics. Um conjunto de relatórios deve ser mapeado para uma organização IMS para ativar esses e outros serviços. Os conjuntos de relatórios mais recentes são mapeados automaticamente após a criação. No entanto, os conjuntos de relatórios mais antigos devem ser mapeados manualmente para uma organização IMS. Consulte [Mapear conjuntos de relatórios para uma organização](https://docs.adobe.com/content/help/pt-BR/core-services/interface/about-core-services/report-suite-mapping.html) no guia do usuário dos Serviços principais para verificar se todos os conjuntos de relatórios pertencem a uma organização IMS. |
| Migração para o domínio de produto unificado | Data efetiva: 28 de maio de 2020 | A migração para um domínio de produto unificado do Adobe Analytics, que começou em janeiro de 2020, terminou em 28 de maio de 2020. Embora o Adobe Analytics funcione para remover todas as referências de domínio `omniture.com` de sua arquitetura, é importante adicionar uma lista de permissões `omniture.com` como um cookie de terceiros. Quando a migração da arquitetura for concluída (em breve), você será notificado por meio das notas de versão e essa etapa da lista de permissões não será mais necessária. [Esta](https://helpx.adobe.com/br/analytics/kb/adobe-ip-addresses.html) é uma lista completa de domínios e endereços IP recomendados que você deve incluir na lista de permissões.<br>Se sua organização bloquear cookies de terceiros, entre em contato com o Atendimento ao cliente para recuperar o acesso ao Adobe Analytics. |
| Nova página de aterrissagem padrão do Adobe Analytics | Data efetiva: 18 de junho de 2020 | Em 18 de junho de 2020, a landing page padrão do Adobe Analytics será alterada de [!UICONTROL Relatórios] para [!UICONTROL Workspace]. Essa alteração ocorrerá para qualquer usuário que não tenha definido uma landing page personalizada anteriormente. |
| Tecnologia de terceiros permitida | 12 de março de 2020 (data de efetivação) | O Adobe Analytics começou a utilizar tecnologias de terceiros para o gerenciamento da implantação de recursos e suporte no produto. Os seguintes URLs devem ser adicionados a qualquer lista de permissões de firewall de rede necessária para garantir o acesso total aos recursos:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Redundância aprimorada para disponibilidade do [!UICONTROL Analysis Workspace] | 21 de maio de 2020 | Para garantir a disponibilidade do [!UICONTROL Analysis Workspace], estamos adicionando uma CDN (Content Delivery Network) secundária para melhorar a redundância. Os seguintes URLs devem ser adicionados a qualquer lista de permissões de firewall de rede necessária:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws.com</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Alteração na forma como [!UICONTROL Entradas/Saídas] são calculadas no [!UICONTROL Workspace] | 7 de abril de 2020 | A partir de março de 2020, mudamos no [!UICONTROL Analysis Workspace] a forma como o valor _Nenhum_ interage com [!UICONTROL Entradas/Saídas]. Como agora é possível ativar ou desativar o valor _Nenhum_ no [!UICONTROL Analysis Workspace], aplicamos o valor _Nenhum_ após a entrada ou saída, enquanto que (para eVars) costumava ser aplicado antes da entrada ou saída. Por exemplo, suponha que a primeira ocorrência de uma visita não tenha valor para eVars, mas a segunda ocorrência tem. No [!UICONTROL Reports &amp; Analytics], a primeira ocorrência será exibida como _Não especificado_ para a Entrada, mas no [!UICONTROL Analysis Workspace] será exibida como o valor na segunda ocorrência. |
| EOL do **[!UICONTROL Arquivo do painel]** | 27 de março de 2020 | A configuração **[!UICONTROL Exibir arquivo]** em **[!UICONTROL Gerenciar painéis]** no [!UICONTROL Reports &amp; Analytics] não estará mais disponível a partir de março de 2020. |
| Fim da vida útil das APIs herdadas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Cingapura, não apoiaremos mais a intermediação de dados entre Londres ou Cingapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fim da vida útil do Ad Hoc Analysis | 6 de agosto de 2018 | A Adobe anunciou a intenção de encerrar a vida útil do Ad Hoc Analysis. Uma data para o fim da vida útil será compartilhada assim que estiver disponível. Para obter mais informações, visite [Descubra a Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Para obter as atualizações mais recentes das versões do AppMeasurement, consulte as [notas de versão do AppMeasurement para JavaScript](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/appmeasurement-updates.html).

#### Recursos de ajuda do Analytics

* [Tutoriais do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentação de produto do Adobe Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/landing/home.html)

## ![Ícone](/assets/audience-manager.png) do Adobe Audience Manager {#aam}

Novos recursos, correções, documentação e tutoriais no Audience Manager.

Data de lançamento: **16 de julho de 2020**

### Novos recursos e correções no Adobe Audience Manager

* Correção de um problema em que os clientes não conseguiam mapear alguns segmentos para destinos da Amazon. (AAM-54373)
* Correção de um problema em que a tela do navegador congelava quando os clientes abriam um segmento em uma nova guia. (AAM-55213)
* Correção de um problema no [Relatório de status de integração](https://docs.adobe.com/help/pt-BR/audience-manager/user-guide/reporting/onboarding-status-report.html), em que os clientes podiam ver uma incompatibilidade de datas ao clicar em uma barra no gráfico e na data na tabela. (AAM-55235)
* Correção de um bug na seção Administração em que a interface do usuário mostrava um ícone de erro em vez de uma mensagem de confirmação quando os clientes tentavam excluir usuários. (AAM-55186)
* Correção de um problema com a API Swagger, em que o cabeçalho `x-api-key` não era adicionado à solicitação de ondulação. (AAM-55392)
* A ordem de classificação padrão para segmentos mapeados para destinos na visualização de destinos foi aprimorada. Os segmentos mapeados agora são classificados por data de início do mapeamento de segmentos e, em seguida, por ID de segmento. (AAM-38494)
* Várias melhorias de acessibilidade na interface. (AAM-48956, AAM-49012, AAM-49364, AAM-49363, AAM-49374, AAM-49579, AAM-55037).

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Atualizações do produto

* **Dynamic Media Classic**

   Os usuários do Dynamic Media Classic agora têm acesso a uma nova experiência de aplicativo de desktop que não depende mais da tecnologia Adobe Flash no navegador. O novo aplicativo agora está disponível para Windows e MacOS.

   Consulte o [aplicativo Adobe Dynamic Media Classic Desktop - Agora disponível.](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/new-ui-2020.html)

* **Suporte a ativos 3D adicionado ao Dynamic Media**

   O Dynamic Media no AEM 6.5 e o AEM como serviço na nuvem agora permitem carregar, gerenciar, visualização e fornecer ativos 3D como experiências imersivas.

   * No AEM como serviço na nuvem, consulte [Trabalhar com ativos 3D no Dynamic Media.](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/assets/dynamicmedia/assets-3d.html)
   * No AEM 6.5, consulte [Trabalhar com ativos 3D no Dynamic Media.](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/assets/dynamic/assets-3d.html)

### Autoajuda

* **Atualizações na documentação do AEM 6.5.5 Forms**

   * Novos recursos e melhorias na versão 6.5.5:

      * [Personalize as colunas da Caixa de entrada do Adobe Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/authoring/essentials/inbox.html#inbox-admin-control).
      * [Salve as Comunicações interativas como um rascunho.](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#save-as-draft)
      * Suporte do servidor de aplicativos Oracle WebLogic para instalações de [um único servidor](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-single-server.pdf) e [cluster](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-cluster.pdf).
      * [Melhorias de acessibilidade.](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#accessibility-improvements)
      * [Autenticação com certificado X-509 para serviços da Web baseados em SOAP no modelo de dados de formulário.](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Suporte ao Oracle RAC.](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#other-improvements)
      * [Melhoria no registro de erros no relatórios de transações.](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)
   * Novos recursos e melhorias na versão 6.4.8.1:
      * [Autenticação com certificado X-509 para serviços da Web baseados em SOAP no modelo de dados de formulário.](https://docs.adobe.com/content/help/pt-BR/experience-manager-64/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Melhoria no registro de erros no relatórios de transações.](https://docs.adobe.com/content/help/pt-BR/experience-manager-64/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)

### **Comunidade**

* **Discussão da comunidade do AEM**

   Agora você pode ver todos os anúncios do AEM e referências interessantes para blogueiros internos e externos em um só lugar. Consulte a [seção Discussão](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions) da comunidade do AEM.

### Novos cursos e tutoriais do Experience Manager

Novos vídeos, tutoriais ou cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 25 de junho de 2020 | [Introdução aos formulários adaptativos](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/creating-your-first-adaptive-form/adaptive-forms-getting-started-tutorial-use.html) | Vídeo | Esses tutoriais orientam você pelas etapas envolvidas na criação de um formulário adaptável com várias guias. Saiba como usar tabelas, layout e editor de regras para criar regras de negócios. |
| 25 de junho de 2020 | [Criação de um fluxo de trabalho de revisão no AEM Forms](https://video.tv.adobe.com/v/35821/quality=9?captions=por_br) | Vídeo | Saiba como criar um fluxo de trabalho para revisar dados enviados a partir do envio de um formulário ativo. |
| 23 de junho de 2020 | [Processamento de perfis](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/processing-profiles.html) | Vídeo | Os perfis de processamento definem as representações que serão criadas para ativos no AEM como um serviço na nuvem. |
| 23 de junho de 2020 | [Práticas recomendadas do Dynamic Media Classic](https://docs.adobe.com/content/help/en/experience-manager-learn/dynamic-media-classic-tutorial/overview.html) | Artigo | Os usuários atuais e novos podem aprender mais sobre o Dynamic Media Classic, seus principais recursos e como _criar_, _compor_ e _fornecer_ um fluxo de trabalho. |
| 23 de junho de 2020 | [Depuração do AEM como criação e implantações de serviços na nuvem](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/build-and-deployment.html) | Artigo | Saiba como depurar a criação e as implantações do AEM como um serviço na nuvem. |
| 16 de junho de 2020 | [Depuração do AEM como um serviço na nuvem usando logs](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/logs.html) | Artigo | Saiba como usar os logs para depurar o AEM como um serviço na nuvem. Os registros atuam como linha de frente para depurar aplicativos do AEM, mas dependem do logon adequado no aplicativo AEM implantado. |
| 10 de junho de 2020 | [Uso do Dynamic Media 3D com o AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-3d-feature-video.html) | Vídeo | O suporte do Dynamic Media 3D para o Adobe Experience Manager permite personalizar e entregar com facilidade experiências interativas em 3D. |
| 5 de junho de 2020 | [Projeto do SPA Editor](https://docs.adobe.com/content/help/en/experience-manager-learn/spa-react-tutorial/create-project.html) | Artigo | Saiba como usar o arquétipo de projeto do Adobe Experience Manager (AEM) para gerar um projeto Maven de vários módulos como ponto de partida para um aplicativo React integrado ao AEM SPA Editor. |
| 3 de junho de 2020 | [Manuseio de envio de formulário HTML5 - Tutorial](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/html5-forms/handle-mobile-form-submission.html) | Artigo | Saiba como acessar dados enviados no manipulador de envio personalizado. |

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

* Build estável New Gold Standard. [Ler mais](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

#### Painel de controle do Campaign

* Auditoria de capacidade de entrega de subdomínio - [Leia mais](https://docs.adobe.com/content/help/pt-BR/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)

* Gerenciamento de chaves GPG - [Leia mais](https://docs.adobe.com/content/help/pt-BR/control-panel/using/instances-settings/gpg-keys-management.html)

### Novos cursos e tutoriais do Campaign

Novos vídeos, tutoriais ou cursos publicados no mês passado.

| Publicado | Nome | Solução | Descrição |
| ----------- | ----------- | ---------- | ---------- |  
| 26 de junho de 2020 | [Explore a interface do usuário do Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/exploring-the-adobe-campaign-classic-user-interface.html) | Campaign Classic | Este vídeo explica a principal interface do usuário do Adobe Campaign Classic e mostra como navegar pela funcionalidade principal. |
| 8 de julho de 2020 | [Instale e configure o cliente do Adobe Campaign](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Campaign Classic | Saiba como baixar e instalar o console do cliente do Adobe Campaign, criar e gerenciar suas conexões com vários ambientes e verificar o acesso ao console do cliente do Adobe Campaign. |
| 19 de junho de 2020 | [Introdução ao Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/introduction-to-adobe-campaign-classic.html) | Campaign Classic | Saiba como o Adobe Campaign Classic se encaixa no portfólio Adobe Digital Experience, bem como nos principais recursos e capacidades. |
| 12 de junho de 2020 | [Implantação de um template do delivery de email ad-hoc](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/deploying-ad-hoc-email-delivery-template.html) | Campaign Classic | Saiba como implantar um template de email ad hoc |
| 12 de junho de 2020 | [Configuração de um template de delivery](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/configuring-a-delivery-template.html) | Campaign Classic | Saiba como configurar um template de email |
| 12 de junho de 2020 | [Configuração das propriedades do template de delivery](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/setting-delivery-template-properties.html) | Campaign Classic | Saiba como definir propriedades de template de email |
| 12 de junho de 2020 | [Gerenciamento de chaves GPG](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management-overview.html) | Campaign Classic/Painel de controle do Campaign | Saiba como gerar e instalar um par de chaves GPG públicas/privadas para criptografia de dados e como importar e instalar uma chave pública para descriptografia de dados. |
| 26 de junho de 2020 | [Introdução à interface do usuário no Adobe Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/getting-started/getting-started-with-the-ui.html) | Campaign Standard | Este vídeo oferece uma visão geral sobre a interface do usuário do Adobe Campaign Standard e explica como navegar pelos principais recursos e funcionalidades. |
| 26 de junho de 2020 | [Gerenciamento de chaves GPG](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/gpg-key-management-overview.html) | Campaign Standard/Painel de controle do Campaign | Saiba como gerar e instalar um par de chaves GPG públicas/privadas para criptografia de dados e como importar e instalar uma chave pública para descriptografia de dados. |

### Recursos de ajuda

* Adobe Campaign Standard: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/campaign-standard-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/overview.html) - [Planejamento de lançamento](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-planning.html) - [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/campaign-classic-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/documentation-updates.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html)   - Vídeos explicativos do [Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notas de versão da Adobe Advertising Cloud.

### Novos recursos na [!UICONTROL Advertising Cloud Search] {#adcloud-search}

Atualizado em **8 de julho de 2020** para o lançamento do dia 11 de julho.

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Alertas beta] | Agora é possível abrir uma visualização filtrada somente leitura contendo os dados de qualquer alerta e, em seguida, abrir uma visualização filtrada das entidades na visualização de gestão de campanha relevante, a partir da qual você pode editar os logs de entidade. |
| [!UICONTROL Portfólios] | A descontinuação de métricas de posição em restrições e configurações de portfólio foi adiada para 8 de agosto. |

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
