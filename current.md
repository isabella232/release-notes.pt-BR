---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 51e45852d84bd30b5d0fb21640b2e9f31080840c

---


# Acesso antecipado - Notas de versão da Adobe Experience Cloud - janeiro de 2020

Novos recursos e correções na Adobe Experience Cloud.

>[!IMPORTANT]
>Esta página contém conteúdo de pré-lançamento e está sujeita a alterações antes do lançamento planejado para cada produto.

>[!NOTE]
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por e-mail sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 16 de janeiro de 2020**

* [Status do sistema Adobe](#status)
* [Interface da Experience Cloud e principais serviços](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services e Mobile SDKs](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)
* [!DNL Advertising Cloud](#adcloud)

Procurando a página principal da ajuda? Consulte [Documentação da Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Adobe System Status {#status}

[!UICONTROL O status] do sistema da Adobe fornece informações detalhadas, atualizações de status e notificações por e-mail sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Dê uma olhada em [status.adobe.com](https://status.adobe.com/).

**Novidades**

* Usando sua Adobe ID, você pode assinar notificações de eventos com base nas preferências do produto, região e evento. Os usuários que configuram suas preferências de assinatura são notificados apenas de incidentes relevantes do produto e de eventos de manutenção assim que forem abertos, atualizados ou fechados. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Inscrever-se em notificações por email proativas | <ul><li>Suporte para Experience Cloud, Creative Cloud, Document Cloud, Adobe Experience Platform e Adobe Services</li><li>Suporte para preferências de região e tipo de evento</li></ul> |
| Gerenciar preferências de notificação | <ul><li>Editar e salvar preferências de notificação a qualquer momento</li><li>Cancelar a assinatura das notificações a qualquer momento</li></ul> |
| Receba email personalizado e mais rápido | <ul><li>As notificações de eventos são enviadas assim que os eventos são abertos, atualizados ou fechados</li><li>Receba somente as notificações de evento relevantes que correspondem às preferências configuradas</li><li>Receber notificações localizadas com base no idioma configurado nas preferências de sua conta</li></ul> |
| Obter notificações personalizadas no produto | <ul><li>Os eventos que correspondem às preferências de notificação e aos direitos do produto são exibidos no painel Anúncios</li></ul> |

## Experience Cloud interface and core services {#ecloud}

Novos recursos e correções na interface da Experience Cloud, incluindo administração e principais serviços (atributos do cliente, públicos-alvo, acionadores, cookies etc.).

### Domínio de produto unificado

A Adobe está atualizando o domínio e o cabeçalho da interface para unificar e melhorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar sua experiência de maneiras pequenas, mas importantes. Esses aprimoramentos não alterarão seus fluxos de trabalho atuais.

As atualizações incluem:

* Novos URLs de solução: `experience.adobe.com/<application name>.` Todos os produtos irão eventualmente adotar esse padrão de URL. Procure novos URLs para se tornarem efetivos durante o mês.
* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do produto aprimorada: A [!UICONTROL Experience League] é integrada ao produto para que a pesquisa de ajuda inclua também resultados de fóruns da comunidade e conteúdo de vídeo. Essa alteração simplifica o acesso a mais conteúdo e ajuda a aproveitar ao máximo a Experience Cloud. Além disso, clique em **[!UICONTROL Ajuda]**>**[!UICONTROL  Feedback]** para reportar problemas ou compartilhar suas ideias com o produto Adobe.
* Notificações aprimoradas: O menu suspenso [!UICONTROL Notificações] agora tem duas guias, uma para suas próprias notificações de produtos e outra para anúncios de produtos globais.

**** Observação: A página do [!UICONTROL Feed] está sendo substituída em janeiro de 2020. Procure um aviso de desativação no produto.

Para consultar a documentação do produto, acesse [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Cookies da Experience Cloud

A Adobe está ajustando a configuração `same-site` dos cookies para se preparar para as alterações que o Chrome fará no Chrome 80 (a ser lançado em fevereiro de 2020).

Não é necessário fazer alterações a menos que você use um CNAME para coleta de dados primários, mas use esse CNAME em vários domínios (domínios amigáveis de terceiros) e não use o Serviço de ID da Experience Cloud (Visitante). Com a versão do Chrome 80, o Chrome fornece automaticamente aos cookies de ID de visitante do Analytics um valor do SameSite, o `Lax,` que impede o uso desses cookies em outros domínios. Se quiser continuar usando seu CNAME em todos os domínios, entre em contato com o Atendimento ao cliente da Adobe e solicite que ele altere o valor do SameSite para seu CNAME `None.`

Observe que a Adobe recomenda usar um CNAME separado para cada um dos domínios, independentemente de você estar usando o Serviço da Experience Cloud ID.

[Mais…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Notas de versão da Experience Plataform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (Todos os produtos da Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para obter as notas de versão e a documentação do produto.

## Mobile Services and Mobile SDKs {#mobile}

16 de janeiro de 2020: Versão 4.18.0

* Aquisição - Adicionada uma nova API, `Analytics.processGooglePlayInstallReferrerUrl(final String url)`, para suportar [!DNL Google Play] Instalar APIs de referência.

Para obter mais informações sobre as APIs de referência de instalação, consulte [Ainda usando o InstallBroadcast? Alterne para a API do referenciador Play até 1º de março de 2020](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html).

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

Para obter a documentação do produto, consulte a [Página inicial de ajuda do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- | 
| Analysis Workspace - Criador de tabela de forma livre | Com o Criador de tabela ativado, você pode arrastar e soltar em muitas dimensões, detalhamentos, métricas e segmentos para criar tabelas que respondam a perguntas comerciais mais complexas. Os dados não serão atualizados imediatamente. Em vez disso, as atualizações ocorrem depois que você clica em **[!UICONTROL Criar]**, economizando tempo depois de saber qual tabela deseja criar. Além disso, este recurso oferece:<ul><li>**Visualização**: É possível visualizar o formato de uma tabela antes de gastar tempo para renderizar dados reais.</li><li>**Configurações** flexíveis de linhas e detalhamento: Você pode definir seus níveis de linha e detalhamento para cada linha de dimensão. Anteriormente, o Workspace impunha padrões que não podiam ser alterados até que os dados fossem retornados.</li><li>**Detalhamento por posição**: É possível definir linhas de dimensão para _detalhar sempre por posição_ em vez de _por item_ específico (o padrão).</li><li>**Ordenação** manual de linha estática: É possível ordenar manualmente linhas estáticas para que as linhas da tabela sejam exibidas exatamente como você precisa. Anteriormente, linhas estáticas podiam ser classificadas somente por uma coluna de métrica ou alfabeticamente.</li></ul>A documentação associada será publicada quando este recurso for lançado em janeiro. |
| Nova dimensão de Estado  identificado para CDA (Cross-Device Analytics) | Estamos adicionando uma nova dimensão chamada Estado  identificado aos conjuntos de relatórios virtuais CDA. A dimensão tem dois valores possíveis, _Identificado_ e _Não identificado_. _Identificado_ significa que a pessoa foi identificada pelo gráfico do dispositivo. _Não identificado_ significa que a pessoa não foi identificada pelo gráfico de dispositivos.<br>Isso significa que os usuários do CDA agora podem criar métricas calculadas, como Cobertura [!UICONTROL do gráfico de]dispositivo, que descreve quantas pessoas no conjunto de relatórios virtual são conhecidas pelo gráfico de dispositivo. Essa métrica é útil para solucionar problemas de taxas de compactação CDA. Se forem identificadas poucas pessoas, o nível de costura será baixo. |
| Suporte a VRS na API do Data Warehouse | Os Conjuntos de relatórios virtuais agora estarão disponíveis para uso por meio da API do Data Warehouse. Anteriormente, eles só estavam disponíveis por meio da interface do usuário do Data Warehouse. Ao usar a API do Data Warehouse, agora é possível visualizar e consultar conjuntos de relatórios virtuais, mas somente se os segmentos aplicados a um Conjunto de relatórios virtuais forem compatíveis com o Data Warehouse. |
| API do Privacy Service: CCPA | A Lei de Privacidade do Consumidor da Califórnia (California Consumer Privacy Act, ou CCPA) aprimora os direitos de privacidade e a proteção do consumidor para os moradores da Califórnia, nos Estados Unidos. Esta Lei entrou em vigor em 1 de janeiro de 2020.<br><br/>A CCPA oferece novos direitos de privacidade de dados aos moradores da Califórnia, como o direito de acessar e excluir seus dados pessoais, de saber se seus dados pessoais são vendidos ou divulgados (e para quem) e de recusar a venda de seus dados pessoais.<br><br/>O Privacy Service oferece suporte a solicitações de recusa da venda de dados pessoais.<br><br/>O Privacy Service era anteriormente o GDPR Service e retém toda a funcionalidade anterior, agora estendida para suportar CCPA.<br/><br/>[CCPA no Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Visão geral de privacidade](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### Correções

* Correção de um problema que impedia que notificações de alerta fossem enviadas para números de telefone no Egito. (AN-197079)
* Correção de vários problemas com o [!DNL DFA Data Connector]. (AN-193281, AN-193075, AN-193484, AN-193737)
* [!UICONTROL Relatórios e análises]: Correção de um problema no qual o relatório Funil de conversão de produto era cortado e exibia números não claros. (AN-186901)
* Correção de um problema que impedia os usuários de alternar conjuntos de relatórios em projetos do Workspace que eram baseados em conjuntos de relatórios com a nova arquitetura Classificações. (AN-199076)
* Correção de um problema que impedia o funcionamento correto da função [!UICONTROL Cumulative] em Métricas  calculadas. (AN-184257)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Novo domínio do Adobe Analytics | 18 de dezembro de 2019 | Em 16 de janeiro de 2020, o Adobe Analytics começará a migrar para um novo domínio - `https://experience.adobe.com/analytics.`<br>**Observação **: Essa alteração se aplica a todos os usuários que acessam o Analytics com sua Adobe ID ou Enterprise ID.<ul><li>A alteração de domínio pode causar problemas de cookie ao carregar o Analytics no Safari. Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Você pode usar outros navegadores sem problemas, pois isso afeta somente os usuários do Safari.</li><li>A alteração de domínio pode fazer com que o [!UICONTROL Activity Map] pare de funcionar para alguns clientes [em casos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)específicos.</li></ul> |
| Fim da vida útil - APIs antigas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>1.3 APIs do Analytics</li><li>1.4 APIs do SOAP Analytics</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos perguntas frequentes sobre [EOL API](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) herdada para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as APIs [REST do Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 1.4 ou as APIs [do Analytics](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)2.0. As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| EOL (fim da vida útil) da opção **[!UICONTROL Exibir arquivo]** | 30 de outubro de 2019 | Anúncio do fim da vida útil da opção **[!UICONTROL Exibir arquivo]** no Gerenciador do painel (**[!UICONTROL  Componentes > Painéis]**) para janeiro de 2020. |
| EOL (fim da vida útil) da opção **[!UICONTROL Impor restrições de logon de IP]** | 30 de outubro de 2019 | Anúncio do fim da vida útil da funcionalidade de lista de permissões de logon de IP (**[!UICONTROL Impor restrições de logon de IP]**) no menu **[!UICONTROL  Admin > Configurações da empresa > Segurança]**. |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Singapura, não apoiaremos mais a intermediação de dados entre Londres ou Singapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Alteração futura em relação ao campo `createDate` para usuários do Analytics | 30 de agosto de 2019 | In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Correções e recursos adicionados ao Audience Manager.

### Novos recursos, melhorias e correções no Audience Manager {#aam-features}

| Recurso | Descrição |
| -----------| ---------- |
| [Visão geral do suporte e da documentação de privacidade da California Consumer Privacy Act (CCPA)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | A [California Consumer Privacy Act (CCPA)](https://www.caprivacy.org/about), que entrou em vigor em 1º de janeiro de 2020, fornece aos residentes da Califórnia novos direitos sobre suas informações pessoais e impõe responsabilidades de proteção de dados a determinadas entidades que realizam negócios na Califórnia. <br><br> O Audience Manager ajuda você a cumprir suas obrigações conforme as regulamentações de privacidade, por meio de ferramentas de privacidade como o [Adobe Experience Platform Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) para acesso a dados e solicitações de exclusão. <br><br> Atualizamos o processo atual de gerenciamento [de](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) não participação para incluir a não participação de qualquer ID declarada (por exemplo, ID do CRM). Em caso de recusa por ID declarada, a ID declarada e o último dispositivo vinculado serão excluídos da coleta de dados do Audience Manager. As solicitações de cancelamento também enviam solicitações de cancelamento de segmento para parceiros [de](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) destino que suportam esse recurso, tanto em lote quanto em tempo real. <br><br> Além disso, reprojetamos nossa documentação sobre Segurança [de](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)dados, Privacidade [de](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)dados e Controle [de](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) dados, para facilitar a localização das informações necessárias para cumprir os regulamentos acima. |

### Correções e melhorias {#aam-fixes-and-improvements}

* Correção de um problema no fluxo de trabalho [!UICONTROL Criar destino] em que, ao selecionar Plataformas ****integradas como[!UICONTROL Categoria], a seção Informaçõesbásicas desaparecia e o fluxo de trabalho seria impossível de ser concluído. (AAM-52397, AAM-52414)
* Corrigimos um erro no qual a página [!UICONTROL Criar/editar] destinos não carregava nos navegadores Apple Safari e Mozilla Firefox. (AAM-51784)

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Manutenção do produto

* **AEM 6.5.3.0** AEM 6.5, Service Pack 3.0 (6.5.3.0 lançado em 12 de dezembro de 2019) é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.5, abril de 2019.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4, Service Pack 7.0 (6.4.7.0 lançado em 12 de dezembro de 2019) é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.4, abril de 2018.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 7 (6.3.3.7 lançado em 12 de dezembro de 2019) é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.3, abril de 2017.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   O AEM Desktop App 2.0.1.1 fornece uma atualização para logon único com Okta e a capacidade de especificar o local dos arquivos temporários em Preferências. O suporte para o AEM 6.3.x está obsoleto para o aplicativo para desktop 2.x com esta versão.
   * [Notas de versão](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **O Adobe Asset Link 1.1 encerra o suporte ao AEM 6.3.x**

   O suporte para o AEM 6.3.x está obsoleto no Adobe Asset Link desde abril de 2019. O Adobe Asset Link 1.1 remove o suporte ao AEM 6.3.x a partir de 13 de janeiro de 2020.
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### Versões do produto

* **Serviço de conversão de formulários automatizado**

   O serviço de conversão automatizada de formulários, o serviço para converter automaticamente formulários PDF em lindos formulários HTML prontos para dispositivos móveis, tornou-se disponível para consumo geral em 12 de dezembro de 2019.

   * [Introdução](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [Configurar o serviço](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [Converter formulários PDF em formulários adaptáveis](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### Autoajuda

* **Visualização de ativos 3D**

   O AEM 6.5 é compatível com upload, entrega e visualização interativa de ativos 3D como parte do processo de criação. O visualizador 3D interativo está disponível na página de detalhes do ativo no AEM. O visualizador inclui, entre outras coisas, uma coleção de controles interativos de câmera que permitem que você orbite, aplique zoom e desloce o ativo 3D.
Consulte [Visualizar ativos](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)3D.

* **Componentes principais**

   Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Arquétipo de projeto AEM**

   O módulo [](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) ui.front-end do [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) é uma ferramenta útil e flexível para facilitar o desenvolvimento front-end para seu projeto AEM.

### Recursos adicionais

* [Página inicial de aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página inicial de aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notas de versão do Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Campaign Classic 19.2

| Recurso | Descrição |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | A CCPA é a nova lei de privacidade do estado da Califórnia que harmoniza e moderniza os requisitos de proteção de dados que entram em vigor em 1° de janeiro de 2020. O CCPA se aplica aos clientes do Adobe Campaign que detêm dados para pessoas de dados residentes na Califórnia. <br> Além dos recursos de privacidade já disponíveis (incluindo gerenciamento de consentimento, configurações de retenção de dados e funções de usuário), o Adobe Campaign ajuda a facilitar a preparação para CCPA: <ul><li>__ Direito de acesso _e_ direito de exclusão: estamos aproveitando as capacidades que foram adicionadas ao RGPD. [Saiba mais](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>Você pode rastrear se um consumidor optou pela venda de Informações pessoais. Para isso, é necessário estender a tabela [!UICONTROL Perfis] e adicionar um campo **[!UICONTROL Recusar para CCPA]**.[Saiba mais](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> Consulte o vídeo [como fazer](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Monitoramento ao vivo do fluxo de trabalho | Agora você pode monitorar o status de execução de todos os fluxos de trabalho na sua instância usando exibições predefinidas. <br> Para obter mais informações, consulte [Filtrar fluxos de trabalho de acordo com seu status](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status). |
| Conteúdo interativo com AMP | O Adobe Campaign permite que você experimente o novo [AMP interativo para o formato de email](https://amp.dev/about/email/) , que permite que os profissionais de marketing incluam componentes AMP dentro de mensagens para aprimorar a experiência de email com conteúdo avançado, dinâmico e interativo, acionável diretamente na própria mensagem. <br> Esse recurso é lançado como um beta público. <br> Para obter mais informações, consulte a documentação [](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) detalhada e o vídeo [do](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)tutorial. |
| Mensagens SMS seguras (TLS) | O SMS seguro agora é suportado por meio do Conector SMPP genérico estendido. Isso permite uma conexão criptografada com o provedor. <br> **Aviso**: este recurso requer um certificado atualizado em todos os servidores. Certificados inválidos, revogados ou expirados gerarão erros que afetarão os recursos gerais de envio de SMS. <br>[ Para obter mais informações, consulte a documentação detalhada](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |

Consulte [Notas de versão do Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) para correções e melhorias.

### Campaign Standard 19.4

| Recurso | Descrição |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | A CCPA é a nova lei de privacidade do estado da Califórnia que harmoniza e moderniza os requisitos de proteção de dados que entram em vigor em 1° de janeiro de 2020. O CCPA se aplica aos clientes do Adobe Campaign que detêm dados para pessoas de dados residentes na Califórnia. <br> Além dos recursos de privacidade já disponíveis no Adobe Campaign (incluindo gerenciamento de consentimento, configurações de retenção de dados e funções de usuário), estamos aproveitando esta oportunidade para incluir recursos adicionais, para ajudar a facilitar sua preparação para CCPA: <ul><li> Direito de acesso e direito de exclusão: estamos aproveitando as capacidades que foram adicionadas ao RGPD. [Saiba mais](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> Ao criar uma solicitação de privacidade, o tipo de regulamento (RGPD ou CCPA) foi adicionado ao Privacy Core Service. Este método é o que você deve usar para todas as solicitações de acesso e exclusão. O uso da API de campanha e da interface para acessar e excluir solicitações está obsoleto. Consulte o artigo [Recursos removidos e](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)obsoletos. </li><li> Um campo **CCPA Opt-Out** foi adicionado ao recurso Perfis para permitir que os usuários do Adobe Campaign rastreiem se um consumidor optou pela venda de Informações pessoais. [Saiba mais](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> Consulte o vídeo [como fazer](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Integração do Microsoft Dynamics 365 (GA) | A integração entre o Adobe Campaign Standard e o Microsoft Dynamics 365 está disponível. Você poderá transferir seus registros de contato e entidade personalizados do Dynamics 365 para o Campaign e obter dados de eventos de email do Campaign para o Dynamics 365 para melhorar o alinhamento de vendas/marketing. <br> Consulte a documentação [](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) detalhada para configurar essa integração e exibir o vídeo [de](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)instruções. |

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Painel de controle do Adobe Campaign

Adicionamos novos recursos para usuários administradores delegarem subdomínios e renovarem certificados SSL do Painel de controle.

Para obter mais informações, consulte estas páginas:

* Configurar um novo subdomínio - [Leia mais](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* Renovando um certificado SSL de subdomínio - [Leia mais](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>Esses recursos estarão disponíveis na versão beta até o final de janeiro e estão sujeitos a atualizações e modificações frequentes sem aviso prévio.

### Recursos adicionais

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planejamento de versão](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - Notas [de versão](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Atualizado para 11 de janeiro de 2020, versão

| Exibir | Recurso |
|------|---------|
| Rastreamento de conversão | Todos os cookies da Advertising Cloud foram atualizados para atender aos novos requisitos de controle de cookies do Google Chrome 80, que será lançado em 4 de fevereiro. As alterações foram implementadas nos servidores da Adobe usando os cookies existentes, sem nenhum efeito nas métricas do visitante. Nenhuma atualização do anunciante é necessária. |
| Insights > Alertas Beta, Pesquisar > Campanhas | (Recurso Beta somente para contas de pesquisa) Um novo Alertas Beta permite que você crie modelos de alerta para identificar quando qualquer campanha de pesquisa, grupo de publicidade, palavra-chave ou anúncio atende a condições específicas. como as métricas de desempenho — durante um período especificado e gerar um alerta. Os alertas estão disponíveis para um único anunciante. |
| Relatórios | Os dados para anúncios de listagem de produtos agora estão incluídos nos relatórios Classificação de etiqueta, Valor de etiqueta, Regra de lance e Restrição. |
