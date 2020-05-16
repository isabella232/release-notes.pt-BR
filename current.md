---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: ea42901b975981a10d42b9681d494604c385018c
workflow-type: tm+mt
source-wordcount: '4766'
ht-degree: 38%

---


# Acesso antecipado - Notas de versão da Adobe Experience Cloud - maio de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Esta página fornece novos recursos, correções e avisos importantes em [!DNL Adobe Experience Cloud]. As datas de lançamento da solução podem variar. Verifique novamente com frequência para obter as atualizações mais recentes.

>[!IMPORTANT]
>
>Esta página contém conteúdo de pré-lançamento e está sujeita a alterações antes de 21 de maio de 2020. Serão anotadas novas informações publicadas posteriormente, com a data adicionada.

>[!NOTE]
>
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras.

**Data de lançamento: maio de 2020**

Última atualização: **15 de maio de 2020**

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
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

* Usando a Adobe ID, é possível assinar notificações de eventos com mais granularidade até a oferta de produtos e complementos. Para ajudá-lo a configurar sua subscrição mais rapidamente, o processo de subscrição automática agora recomenda uma seleção de produtos e ofertas com base em seus direitos de produto. Isso deve reduzir o número de emails recebidos e fornecer notificações mais relevantes na sua caixa de entrada. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Experiência do usuário de assinatura e notificação aprimorada | <ul><li>[!DNL Marketo Engage] as localizações regionais agora são filtradas com base na lista de ofertas de produtos selecionadas.</li><li>[!DNL Marketo Engage] as notificações por email são relevantes para as preferências de região, local e ambiente do usuário.</li></ul> |
| Confirmação de subscrição do Evento | <ul><li>Agora você pode obter uma confirmação por email ao assinar atualizações de evento único em andamento.</li></ul> |
| Melhorias na utilização da navegação global | <ul><li>Experiência do usuário consistente com `Adobe.com` o menu de navegação de nível superior.</li></ul> |

## ![Ícone](/assets/ec_appicon_24.png) Interface da Experience Cloud {#ecloud}

Atualizações gerais na interface da Experience Cloud.

**Domínio de produto unificado**

A Adobe tem atualizado o domínio e o cabeçalho da interface para unificar e aprimorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar a experiência de maneiras pequenas, mas importantes. Esses aprimoramentos não alteram seus workflows atuais.

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
| home page da Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Gerenciamento de jornada | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Painel de controle do Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Serviço de locais | `experience.adobe.com/places` |
| Distribuição de software | `experience.adobe.com/downloads` |
| Ferramenta de administração (beta) | `experience.adobe.com/admin` |

## ![Ícone](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notas de versão para [!DNL Experience Platform,] incluir [!DNL Experience Platform Launch,] [!UICONTROL Orquestração de jornada], [!UICONTROL Ofertas], [!UICONTROL Pessoas], [!UICONTROL Places], [!UICONTROL Mobile Services] e boletins de segurança.

### Aprimoramentos na interface

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] O está lançando atualizações no domínio e na barra de cabeçalho para melhorar sua experiência e se unificar com outros aplicativos da Experience Cloud. As atualizações incluem:

* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do usuário aprimorada, incluindo artigos em destaque e documentação relevante para contexto no menu Ajuda.
* Capacidade de fornecer feedback sobre a plataforma da experiência e os tíquetes de suporte a arquivos.

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### Atributos do cliente - nova documentação

Updated: **May 15, 2020**

* [Suporte a Atributos do cliente para CCPA](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Suporte a Atributos do cliente para RGPD](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) (Regulamento geral de proteção de dados)

### Orquestração da jornada {#journey}

Usando a Adobe Experience Platform, orquestre as jornadas individuais dos clientes em escala em todos os canais de experiência, prevendo de forma inteligente as necessidades de cada cliente em tempo real, onde quer que a jornada o leve.

* [Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html)
* [Notas de versão](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html)
* [Vídeos tutoriais](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Informações adicionais sobre a versão da Experience Platform

* [Notas de versão da Experience Platform Launch](https://docs.adobe.com/content/help/pt-BR/launch/using/intro/release-notes/current.html)
* [Notas de versão da Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/br/security.html) (Todos os produtos da Adobe)

## ![Ícone](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Novos recursos no Análise de jornada do cliente](#cust-journey)
* [Novos recursos no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)
* [Novos tutoriais do Analytics](#tutorials-analytics)

### Novos recursos no Análise de jornada do cliente {#cust-journey}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Análise]de jornada do cliente: Disponibilidade global | Torna a Análise [!UICONTROL de jornada do] cliente disponível para clientes na EMEA e na APAC. |
| [!UICONTROL Análise]de jornada do cliente: Suporte para caixas de proteção da plataforma [!UICONTROL Adobe Experience] | Permite selecionar caixas de proteção específicas da plataforma [!UICONTROL Adobe Experience para] criar conexões CJA. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics-platform/using/cja-connections/create-connection.translate.html) |

### Novos recursos no Adobe Analytics {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Recurso | Descrição |
| -----------| ---------- |
| Suporte do Analytics para [!UICONTROL Adobe Experience Platform Edge Network] | Permite que você use uma única tag para enviar dados para várias soluções da Adobe, como o Adobe Analytics, o Adobe Público alvo, o Adobe Audiência Manager, o Adobe Experience Platform Data Lake, o Unified Perfil e o Serviço da Experience Cloud ID. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/experience-platform/edge/home.html) |
| [!UICONTROL painéis do Adobe Analytics] | [!UICONTROL Os painéis] do Adobe Analytics são um aplicativo móvel que permite que os usuários acessem informações do Adobe Analytics a qualquer momento e em qualquer lugar. Este aplicativo é destinado a executivos que buscam acesso móvel a métricas principais. Ele permite o acesso a scorecards curados e interativos e estará disponível para os sistemas operacionais iOS e Android. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace][!UICONTROL : crie automaticamente tabelas de forma livre a partir de um estado em branco] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. Além disso, foram feitos aprimoramentos no modo como tipos de componentes mistos (como dimensões e métricas) são tratados quando colocados em uma Tabela de forma livre em branco juntos. |

#### Correções do Adobe Analytics

* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. (AN-206221)
* Correção de um problema com o processamento de [!UICONTROL Fonte de dados] mostrando as datas erradas. (AN-213604)
* Correção de um problema em que os arquivos de classificação não eram carregados corretamente no FTP. (AN-214102)
* Correção de um problema em que o método da API `Segments.Get` não retornava uma resposta completa. (AN-206210)
* Correção de um problema em que os itens de linha da tabela eram convertidos em caracteres especiais no [!DNL Workspace] download de PDF. (AN-196153)
* Correção de um problema em que a chamada da API 1.4 do Adobe Analytics `visattrcustomeridcustomerattributes` não funcionava corretamente. (AN-186873)
* Correção de um problema com dados que apareciam em relatórios, mas que estavam ausentes no [!UICONTROL Feed de dados]. (AN-211923)
* Correção de um problema que impedia a cópia das permissões de [!UICONTROL Perfil de produto]. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. (AN-207750)
* Correção de um problema em que os dados do [!UICONTROL AdWords] não eram exibidos no [!UICONTROL Advertising Analytics]. (AN-213249)
* Correção de um problema em que os dados de classificação não eram mostrados na exibição de tendências. (AN-212761)
* Correção de um problema que resultava em uma contagem de segmentos publicados incorreta no [!UICONTROL Gerenciador de segmentos]. (AN-213374)
* Correção de um problema com **[!UICONTROL Mostrar tendência para cima como...]** no Editor [!UICONTROL de métricas] calculadas - não funcionava ao aplicar filtros. (AN-214223)
* Correção de vários problemas com Importação e Exportação de [!UICONTROL Classificação] . (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Correção de vários problemas com o Construtor [!UICONTROL de regras de]classificação. (AN-213826, AN-213550, AN-213095)
* Correção de problemas com o processamento das Fontes  de dados. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-217551, - 217947, AN-219018, AN-214691, AN-218401)
* Correção de problemas de conectividade FTP. (AN-115525)
* Correção de vários problemas [!DNL Analytics] de feeds  de dados. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, (217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Correção de problemas com solicitações do [!UICONTROL Data Warehouse] . (AN-181836)
* Correção de problemas em projetos da [!UICONTROL Workspace] baixados em PDF, nos quais os valores eram convertidos em caracteres especiais. (AN-196153)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions in [!UICONTROL Admin Console]. (AN-211113)
* Correção de um problema em que os formatos de hora em métricas calculadas eram quebrados para valores negativos. (AN-210900)
* Correção de um problema que impedia que os usuários alterassem o Modelo [!UICONTROL de] atribuição em métricas de linha estáticas. (AN-207872)
* Correção de um problema que fazia com que o construtor de relatórios  agendados ficasse preso em um status na fila. (AN-215317)
* Correção do Conector [!UICONTROL de dados]ExactTarget. (AN-210794)
* Correção de problemas de latência na API [!UICONTROL de ingestão em]massa. (AN-210165)
* Correção de um problema que impedia os usuários de fazer logon no Construtor [!UICONTROL de] relatórios com uma ID federada. (AN-207750)
* Correção de um problema no [!UICONTROL Advertising Analytics] que impedia que [!DNL Google AdWords] os dados fossem exibidos. (AN-213249)
* Correção de um problema que impedia que eventos [!UICONTROL do Workspace] [!UICONTROL Project Viewed] fossem exibidos nos registros. (AN-214134)
* Correção de um problema que ocorria ao alterar o intervalo de datas no [!UICONTROL Workspace] e selecionar **[!UICONTROL Aplicar a todos os painéis]**. A data não foi alterada em alguns painéis. (AN-214944)
* Correção de um problema que impedia a criação ou edição de alertas. (AN-215920)
* Correção de um problema em que todos os intervalos de datas dinâmicos no [!UICONTROL Workspace] exibiam datas incorretas devido ao primeiro dia da semana alternando esporadicamente para um domingo a partir de uma segunda-feira. (AN-218835)

#### Correções adicionais do Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Alteração na forma como [!UICONTROL Entradas/Saídas] são calculadas no [!UICONTROL Workspace] | 7 de abril de 2020 | A partir de março de 2020, mudamos no [!UICONTROL Analysis Workspace] a forma como o valor _Nenhum_ interage com [!UICONTROL Entradas/Saídas]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. Por exemplo, suponha que a primeira ocorrência de uma visita não tenha valor para eVars, mas a segunda ocorrência tem. In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
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
| [Modelo do tutorial de treinamento na área de trabalho da Análise](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | O Tutorial de treinamento da área de trabalho [!UICONTROL de] Análise orienta você pela terminologia e etapas comuns para criar seu primeiro projeto no [!UICONTROL Workspace]. |
| [Adicionando Comparações entre Mês e Ano Anterior a Tendências](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Saiba como aplicar intervalos de datas personalizados para criar comparações de tendências mensais e anuais para qualquer métrica na área de trabalho da [!UICONTROL Análise]. |
| [Extensão do modo escuro para a área de trabalho de Análise](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Ative a extensão do Chrome do Reader Escuro para tornar a área de trabalho Análise escura. |
| [Extensão do Conta-gotas de Cor para Definição de Paletas Personalizadas](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Saiba como usar a extensão ColorPick EyeDropper Chrome para localizar facilmente os valores hexadecimais necessários para uma paleta de cores personalizada em seus projetos do [!UICONTROL Workspace] . |

#### Recursos de ajuda do Analytics

* [Tutoriais do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentação de produto do Adobe Analytics](https://docs.adobe.com/content/help/pt-BR/analytics/landing/home.html)

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Novos recursos, correções, documentação e tutoriais no Audiência Manager.

### Atualizações da interface do usuário

O Audiência Manager está lançando atualizações no domínio e na barra de cabeçalho para melhorar sua experiência e se unificar com outros aplicativos da Experience Cloud.

* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do usuário aprimorada, incluindo artigos em destaque e vídeos relevantes ao contexto no menu Ajuda.
* Capacidade de fornecer feedback sobre a plataforma da experiência e os tíquetes de suporte a arquivos.
* Um novo padrão de URL mais fácil. Atualize seus marcadores para o novo url: `experience.adobe.com/audience-manager`.

Essas atualizações estão disponíveis somente para usuários que fazem logon usando a Adobe ID. Para alternar para um logon da Adobe ID, consulte [Gerenciar usuários e produtos](https://docs.adobe.com/content/help/br/core-services/interface/manage-users-and-products/admin-getting-started.html)da Experience Cloud.

### Novos recursos e correções no Adobe Audience Manager

| Recurso | Descrição |
| -----------| ---------- |  
| [Ferramentas de gerenciamento em massa (BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Carregamos uma nova planilha de ferramentas de gerenciamento em massa que: <br><br><ul><li>Permite que você lista as subpastas na sua hierarquia de características (AAM-51528)</li><li>Recupera métricas quando solicitado para características associadas a CRM IDs (IDs entre dispositivos) (AAM-52135)</li><li>Corrige um problema de codificação de idioma para caracteres coreanos (AAM-AAM-54006)</li></ul> |

**Correções**

* Correção de um problema em que os relatórios de tendências expiravam para pastas com um grande número de características. (AAM-54457)
* Correção de um problema em que os clientes não conseguiam ver o construtor de [!UICONTROL Expressões] no fluxo de trabalho de criação/edição de características. (AAM-54255)
* Correção de um problema em que as mensagens de erro na interface do usuário eram exibidas por pouco tempo, desaparecendo antes que os clientes tivessem a chance de lê-las. Isso ocorreu, por exemplo, ao tentar excluir um segmento que estava mapeado para um destino. (AAM-54031)
* Correção de um problema em que os clientes que não estão mais usando o [!UICONTROL Audiência Marketplace] recebiam e-mails de faturamento mensais. (AAM-54602)
* Correção de um problema em que os clientes que clicavam em certas características de outros locais na interface do usuário viam links quebrados em vez das características. (AAM-54768)
* Correção de um problema em que, no modo de edição de expressão de característica, pressionar ENTER atualizava a página e a expressão de característica era perdida. (AAM-54210)
* Várias melhorias de acessibilidade na interface. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Novos tutoriais do Gerenciador de Audiências {#tutorials-aam}

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Noções básicas sobre termos e conceitos básicos no Audiência Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | Este vídeo aborda alguns dos termos e conceitos básicos que o orientam no Audiência Manager, incluindo sinais, características, segmentos etc. |
| [Como entender o fluxo de dados no Audiência Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Este vídeo ajuda você a entender o Adobe Audiência Manager descrevendo o fluxo de dados para dentro, para dentro e para fora do aplicativo. |
| [Gerenciador de Audiências - Visão geral de um DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Entenda os principais desafios com a personalização entre canais e como o Adobe Audiência Manager alimenta a jornada do cliente. Saiba também quais tipos de dados podem ser integrados no Audiência Manager e identifique os parceiros de ecossistema ad-tech integrados ao Audiência Manager. |
| [Casos de uso do gerenciador de Audiências](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | Neste vídeo, identificamos quatro casos de uso comuns do Gerenciador de Audiências e descrevemos as práticas recomendadas associadas a eles. |
| [Como entender as métricas entre dispositivos no Gerenciador de Audiências](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | Neste vídeo, discutimos a diferença entre perfis de dispositivos e perfis entre dispositivos e mostramos onde os números na interface do usuário correspondem a esses diferentes tipos de perfis. |
| [Como entender Audiências previsíveis no Audiência Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | Neste vídeo, discutimos o que são Audiências preditivas do Gerenciador de Audiências, apresentamos detalhes sobre como funcionam e indicamos casos de uso. |
| [Configurar e relatar Audiências previsíveis no Gerenciador de Audiências](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | Neste vídeo, percorremos a configuração Audiências preditivas na interface do Audiência Manager. Também vemos os relatórios que mostram os resultados do modelo. |

## ![Ícone](/assets/aem.png) Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Atualizações do produto

* **AEM como um Cloud Service**

   * Melhorias e correções no processamento de ativos. A caixa de diálogo de reprocessamento de ativos dá ao usuário mais controle, permite selecionar um perfil de processamento específico e se o fluxo de trabalho de pós-processamento deve ser acionado.
   * Aprimoramentos no desempenho de ingestão de ativos do Dynamic Media.

### Autoajuda

* **Serviço de conversão de formulários automatizado - versão AFC-2020.03.1**

   Uma nova opção está disponível ao instalar o conector mais recente:

   **[!UICONTROL Detectar automaticamente seções]** lógicas: você pode usar a opção Detectar seções [!UICONTROL lógicas] automaticamente para soltar painéis em nível de página (painéis baseados em números de página) e criar apenas painéis lógicos. Ele também pausa os campos que não pertencem a nenhuma seção com seções lógicas anteriores e campos de uma seção lógica que é espalhada por duas páginas adjacentes em uma única seção lógica. Por exemplo, se alguns campos de uma seção lógica estiverem no final da página um e alguns estiverem no start da página dois, todos esses campos serão agrupados em uma única seção lógica.

* **Formatos de imagem não suportados no Dynamic Media**

   Informações sobre os subtipos de formatos de arquivo de imagem rasterizada que não são suportados no [!UICONTROL Dynamic Media].

   Consulte Formatos de imagem rasterizada [não suportados no Dynamic Media](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Fragmentos de conteúdo**

   Informações sobre o suporte a fragmentos de [conteúdo na API](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)HTTP do AEM Assets, juntamente com [personalização e extensão de fragmentos](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)de conteúdo e fragmentos de [conteúdo Configurando componentes para renderização](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **Comunidade da AEM Experience League**

   Conecte-se com a Comunidade [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)do AEM Experience League: Faça perguntas aos colegas alunos e especialistas do AEM, navegue por processos e compartilhe suas dicas e seu conhecimento!

* **Newletters do AEM**

   O Newsletter do AEM pela [!UICONTROL Experience League] foi projetado para ajudá-lo a se atualizar com o AEM, para que você possa obter o valor imediatamente após o start. Esta é a newsletter mais recente:

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): O Experience Manager agora está disponível como um serviço em nuvem.
   * [Assine](https://adobeeventsonline.com/AEM/2017/NL/Optin/) a Newsletter do Experience Insider.
   * Arquivos de newsletters de Visualização na seção de recursos [do](https://helpx.adobe.com/br/support/experience-manager/6-5.html) AEM da página Aprendizagem e suporte do Adobe Experience Manager 6.5.

### Novos tutoriais da Experience Manager

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Configurar o AEM Runtime local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [Introdução aos ativos AEM](https://video.tv.adobe.com/v/33624?captions=por_br) | Um vídeo de introdução sobre como começar a usar os ativos AEM para usuários comerciais. |
| [schemas de pastas de metadados](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Os schemas de pastas de metadados permitem que os usuários gerenciem e revisem metadados associados às próprias pastas de ativos, em vez de diretamente nos ativos. |
| [Marcação com tags](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | As tags são uma ferramenta integral para gerenciar ativos na hierarquia de pastas dos ativos. Estabelecer uma taxonomia de marcação é essencial para permitir que os usuários descubram e organizem ativos no AEM. |
| [Perfis de metadados](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Os perfis de metadados permitem a aplicação automática de metadados padrão em ativos nas pastas de ativos. Isso ajuda a reduzir a carga do gerenciamento de metadados sobre os usuários do AEM e aumenta a consistência dos metadados. |
| [schemas de metadados](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Os schemas de metadados definem a interface que expõe os metadados do ativo no AEM. Este vídeo explora a combinação de abordagens usadas para aplicar ativos. |

### Recursos adicionais

* [Notas de versão do AEM como serviço de nuvem](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [Documentação do AEM como um serviço em nuvem](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
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

* [Versão 20.3 do Adobe Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Painel de controle da Campanha

| Recurso | Descrição |
| -----------| ---------- |  
| Gerenciamento de chaves GPG | Instale e/ou gere chaves GPG em uma instância de marketing, para criptografar dados enviados da Campanha e descriptografar dados recebidos. |
| Gerenciamento de certificados para subdomínios CNAME | O Painel de controle agora permite que você renove os certificados SSL de seus subdomínios que foram delegados com o método CNAME. |

### Tutoriais da nova campanha

* Tutoriais do Novo Campaign Standard

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Painel de controle - Gerenciamento de registros do Google TXT](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Saiba como adicionar registros de verificação de site do Google TXT a todos os seus subdomínios usados para enviar emails para endereços GMAIL com o Painel de controle de Campanha. |
| [Configurar e executar um fluxo de trabalho com a atividade de API externa](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Saiba como chamar um terminal REST da API externa usando a atividade de API externa. |
| (ACS) [Introdução às notificações por push para tutorial do Android](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | Este tutorial explica as etapas necessárias para configurar notificações por push com o Campaign Standard e o aplicativo Android. |

* Tutoriais do New Campaign Classic

| Conteúdo | Descrição |
| -----------| ---------- |  
| [Grande gestão de dados no floco de neve](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Saiba como aproveitar o conector Snowflake no Adobe Campaign Classic. |
| [Painel de controle - Gerenciamento de registros do Google TXT](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Saiba como adicionar registros de verificação de site do Google TXT a todos os seus subdomínios usados para enviar emails para endereços GMAIL com o Painel de controle de Campanha. |

### Recursos de ajuda da Campanha

* Padrão Adobe Campaign: [Centro](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/campaign-standard-home.html) de ajuda - Notas [de](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html) versão - vídeos [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) explicativos - Planejamento [de](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.htmll) versão - Atualizações [] de documentação mais recentes (https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/campaign-classic-home.html) de ajuda - Notas [de](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.translate.html) versão - vídeos [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)&quot;como fazer&quot; - Atualizações [de documentação] mais recentes (https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Novos recursos na Advertising Cloud DSP](#adcloud-dsp)
* [Novos recursos da Pesquisa na Marketing Cloud](#adcloud-search)

### Novos recursos na Advertising Cloud DSP {#adcloud-dsp}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanha Classic] e [!UICONTROL Campanha Beta] | As configurações de mensuração do IAS para fraude e segurança de marca, que você pode configurar opcionalmente para cada campanha, agora incluem opções para medir no inventário VAST e VPAID. |
| [!UICONTROL Campanha Beta] | Visualizações de dados e tempos de carregamento de página foram aprimorados. |
|  | Em todas as páginas, agora é possível baixar relatórios do Excel baseados nos filtros e visualizações atuais. |
|  | (Na versão de 22 de maio) As novas métricas incluem as métricas &quot;All-time&quot;, &quot;Current Interval Delivery&quot;, &quot;Date Specific OTS&quot; (OTS específico para a data). |
| [!UICONTROL Blacklists] | O sistema de previsão agora usa automaticamente a lista negra do anunciante ou da conta. Os usuários não precisam mais colar a lista negra nas configurações de posicionamento. |
| [!UICONTROL Contratos de inventário] | (Beta fechado) Um novo formulário simplificado permite que você configure, edite e solucione rapidamente as ofertas da plataforma do lado do suprimento (SSPs) que não estão disponíveis na Caixa de entrada da ID do contrato. |
|  | Quando você aceita um pacote de ofertas programáticas garantidas na Caixa de entrada da ID do contrato, agora você é alertado de que precisa criar uma disposição padrão para cada uma das IDs do negócio. |

### Novos recursos da Pesquisa na [!UICONTROL Advertising Cloud] {#adcloud-search}

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanhas] | (Contas do Google Ads; serviço beta) A partir do final de maio, a Pesquisa da Advertising Cloud poderá sincronizar os dados das campanhas de exibição do Google Gmail e das campanhas do Google Smart Shopping com as conversões do Google para rastreamento e relatórios. O serviço também permitirá que você edite as configurações de campanha e as configurações de grupo de publicidade para suas campanhas existentes nas visualizações de Campanhas e grupos de anúncios. O serviço será opcional. Quando o serviço estiver geralmente disponível, será aplicada uma taxa adicional.<br>Para obter mais informações sobre o serviço, incluindo o programa beta e o escopo futuro, entre em contato com seu gerente de contas da Adobe. |

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Para ver as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ícone](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes ao se envolverem em todas as jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte as notas [!DNL Marketo] de [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) versão para obter as informações mais recentes.

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
