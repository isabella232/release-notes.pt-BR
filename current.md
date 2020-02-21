---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: c62d85f09ce596482a019aa5d0f1d517bf2df9fe

---


# Notas de versão da Adobe Experience Cloud - fevereiro de 2020

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por e-mail sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 20 de fevereiro de 2020**

(As datas de lançamento de produtos específicos podem variar)

Última atualização: 10 de fevereiro de 2020

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud e dos serviços principais](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services e SDKs móveis](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

Procurando a página principal da ajuda? Consulte [Documentação da Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

**Novidades**

* Usando sua Adobe ID, você pode assinar notificações de evento com base nas preferências de produto, região, evento e idioma. Os usuários que configuram suas preferências de assinatura são notificados de incidentes relevantes do produto e eventos de manutenção assim que forem abertos, atualizados ou fechados. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Consentimento mais rápido dos eventos do produto | <ul><li>Fique informado 30 dias antes da manutenção futura do serviço. Esse recurso oferece mais tempo para avaliar o impacto potencial nas operações de negócios, permitindo que você implemente um plano de mitigação, se necessário.</li><li>As notificações avançadas estão disponíveis em telas Web/móvel/tablet e por email.</li></ul> |
| Personalize sua experiência com base no idioma preferencial | <ul><li>Escolha um idioma preferencial para notificações por email. O recurso Autoassinatura agora está disponível em dezenove idiomas.</li></ul> |
| Experiência do usuário de assinatura e notificação aprimorada | <ul><li>Especifique a região e as preferências de evento em apenas um clique para todos os produtos que você deseja assinar.</li><li>Receba notificações quando _problemas potenciais_ forem promovidos para problemas _menores_ ou _principais_ .</li><li>A página do navegador é atualizada automaticamente quando qualquer produto ou status de evento é atualizado.</li></ul> |

## Interface da Experience Cloud e dos serviços principais {#ecloud}

Novos recursos e correções na interface da Experience Cloud, incluindo administração e serviços principais (atributos do cliente, públicos-alvo, acionadores, cookies etc.).

**Correções**

* **** Atributos do cliente: A interface do usuário de atributos do cliente agora exibe status adicionais de perfis sincronizados no Target. (MCUI-10231)
* **** Acionadores principais do serviço: Devido à falta de uso, a pontuação de propensão &quot;Probabilidade de retorno em 30 dias&quot; ao criar um acionador do tipo Abandono foi removida. (MCUI-10056)

### Domínio de produto unificado

A Adobe está atualizando o domínio e o cabeçalho da interface para unificar e melhorar sua experiência em todos os aplicativos da Experience Cloud. Esses aprimoramentos foram projetados para simplificar a experiência de maneiras pequenas, mas importantes. Eles não alterarão seus fluxos de trabalho atuais.

As atualizações incluem:

* Novos URLs das soluções: `experience.adobe.com/<application name>`:
   * Todos os produtos acabarão por adotar esse padrão de URL. Procure novos URLs para se tornarem efetivos durante o mês.
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **Observação:** embora a interface da Experience Cloud seja compatível com esses navegadores, as soluções individuais podem não ser compatíveis com todos os navegadores. (Por exemplo, o [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) não é compatível com o [!DNL Opera] e o [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) não é compatível com o [!DNL Safari].)
   * (Somente para o [!DNL Safari]) A alteração de domínio pode causar problemas de cookie no [!DNL Safari]. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* É mais fácil alternar entre suas organizações ou para um aplicativo diferente.
* Ajuda do produto aprimorada: a [!UICONTROL Experience League] está integrada ao produto para que a pesquisa de ajuda também inclua resultados de fóruns da comunidade e conteúdo em vídeo. Essa alteração simplifica o acesso a mais conteúdo e ajuda a aproveitar ao máximo a Experience Cloud. Além disso, clique em **[!UICONTROL Ajuda]** > **[!UICONTROL Feedback]** para relatar problemas ou compartilhar suas ideias com a Adobe.
* Notificações aprimoradas: o menu suspenso [!UICONTROL Notificações] agora tem duas guias, uma para suas próprias notificações de produtos e outra para anúncios de produtos globais.

**Observação:** a página do [!UICONTROL Feed] será substituída em janeiro de 2020. Procure um aviso de desativação no produto.

Para consultar a documentação do produto, acesse [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Notas de versão da Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (Todos os produtos da Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para obter as notas de versão e a documentação do produto.

## Mobile Services e SDKs móveis {#mobile}

**4 de fevereiro de 2020: Versão 4.19.0**

A seguinte atualização foi feita nesta versão:

**** Ciclo de vida: Adicionada uma nova API, `pauseCollectingLifecycleData`, para atenuar os dados de duração anormais da sessão reportados em alguns dispositivos iOS antigos.

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features) (Atualizado em 21 de janeiro de 2020)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

Para obter a documentação do produto, consulte a [Página inicial de ajuda do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **Novo modelo** da Workspace para organizações que usam o Cross-Device Analytics:Este modelo mostra como o CDA é eficaz ao unir visitas e educa você sobre dimensões e métricas exclusivas do CDA. É necessário um conjunto de relatórios usando o CDA. Consulte [Configuração de análises](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) entre dispositivos para obter mais informações.
* **** A latência de costura de CDA para organizações que usam o Gráfico privado é reduzida para um dia: A funcionalidade Gráfico privado foi aprimorada para reduzir a latência de geração de gráficos de um processo em lote semanal para um gráfico atualizado diário, permitindo que os clientes CDA acessem gráficos de identidade e links mais atualizados.
* **** Laboratórios (Visualizações de tecnologia): Esse novo recurso do Analytics permite que você teste protótipos de novos recursos na produção e forneça feedback valioso para a Adobe. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **Novas teclas de atalho no Workspace:**<ul><li>Recolher/Expandir todos os painéis: `alt + m`</li><li>Recolher/Expandir painel ativo: `alt + ctrl + m`</li><li>Pesquisar painel esquerdo: `ctrl + /`</li><li>Move para o próximo painel: `alt + Right Key`</li><li>Mover para o painel anterior: `alt + Left Key`</li></ul>[Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **Outras melhorias na Workspace:**<ul><li>Quando um painel ou uma visualização é colocada no [!UICONTROL Workspace], o painel esquerdo muda automaticamente para componentes para um fluxo de trabalho mais simples.</li><li>Os componentes do modelo agora podem ser ativados (por exemplo, marcados como favorito, aprovados).</li><li>As listas de segmentos e métricas filtradas oferecem o `+` botão para adicionar um novo componente se você não encontrar o que precisa.</li></ul>
* O depurador **da** Workspace foi adicionado ao menu Ajuda, fornecendo uma maneira mais simples de habilitá-lo para depurar solicitações da Workspace. [Saiba mais...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** Navegador Microsoft Edge baseado em crômio: Esta versão inclui alterações para reconhecer o navegador Microsoft Edge baseado em Chroium (versão 79 e superior) para fins de relatório.

#### Correções

* Correção de um problema com a interface do segmento informando que as dimensões do Canal [!UICONTROL de] marketing eram compatíveis com o [!UICONTROL Data Warehouse], quando, na realidade, não eram compatíveis. No futuro, o Construtor [!UICONTROL de] segmentos não mostrará mais essas dimensões como compatíveis com o [!UICONTROL Data Warehouse] . (AN-202297)
* Correção de um problema com o nome de um segmento publicado que foi atualizado no Analytics e não foi atualizado no Audience Manager em 24 horas. (AN-199974)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Novo domínio do Adobe Analytics | 18 de dezembro de 2019 | `https://experience.adobe.com/analytics.`<br>** Em 16 de janeiro de 2020, o Adobe Analytics começou a mudar para um novo domínio - **Observação: Essa alteração se aplica a todos os usuários que acessam o Analytics com sua Adobe ID ou Enterprise ID.<ul><li>O domínio pode causar problemas de cookie ao carregar o Analytics no Safari. Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Você pode usar outros navegadores sem problemas, pois isso afeta somente os usuários do Safari.</li><li>A alteração de domínio pode fazer com que o [!UICONTROL Activity Map] pare de funcionar para alguns clientes [em casos específicos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fim da vida útil - APIs antigas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| EOL (fim da vida útil) da opção **[!UICONTROL Exibir arquivo]** | 30 de outubro de 2019 | Anúncio do fim da vida útil da opção **[!UICONTROL Exibir arquivo]** no Gerenciador do painel (**[!UICONTROL Componentes > Painéis]**) para janeiro de 2020. |
| EOL (fim da vida útil) da opção **[!UICONTROL Impor restrições de logon de IP]** | 30 de outubro de 2019 | Anúncio do fim da vida útil da funcionalidade de lista de permissões de logon de IP (**[!UICONTROL Impor restrições de logon de IP]**) no menu **[!UICONTROL Admin > Configurações da empresa > Segurança]**. |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Singapura, não apoiaremos mais a intermediação de dados entre Londres ou Singapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Alteração futura em relação ao campo `createDate` para usuários do Analytics | 30 de agosto de 2019 | Em outubro ou novembro de 2019, o campo `createDate` para os usuários do Analytics foi atualizado do Horário do Pacífico dos EUA para um valor de data/hora corretamente formatado com as informações de fuso horário.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). A versão 2.18.0 foi lançada em 13 de fevereiro de 2020.

## Audience Manager {#aam}

Correções e recursos adicionados ao Audience Manager.

### Novos recursos, melhorias e correções no Audience Manager {#aam-features}

| Recurso | Descrição |
|----|----|
| [Relatório de uso de atividade](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | O Relatório [!UICONTROL de uso da] atividade ajuda a visualizar e rastrear o uso da atividade da sua instância do Audience Manager, fornecendo uma ideia clara de como o uso da atividade se compara ao compromisso contratual. |

### Correções e melhorias {#aam-fixes-and-improvements}

* Correção de um erro que resultava na quebra do fluxo de criação da interface do usuário para a seleção de Contas integradas (AAM-52414).
* Correção de um bug que resultava na quebra da interface do usuário ao navegar pelo fluxo de criação de Modelos algorítmicos (AAM-37942).
* Corrigido um erro que fazia com que a seleção de Exportação de dados não fosse salva ao salvar os Controles de exportação de dados para destinos novos ou existentes, para clientes que usam a integração da plataforma Adobe Experience (AAM-52814).
* Corrigido um erro que fazia com que as recomendações de características de terceiros funcionassem incorretamente para características que contêm caracteres de barra vertical (`|`) no nome (AAM-51635).
* Várias melhorias de acessibilidade na interface do usuário.

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Versões do produto

* **Cloud Manager 2020.2.0**

   O Cloud Manager 2020.2.0 simplifica o gerenciamento de autoatendimento de caixas de proteção para o Adobe Experience Manager como um serviço em nuvem.

   Consulte as [Notas de versão](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Autoajuda

* **Tutoriais do AEM como um serviço em nuvem**

   Comece rapidamente com os [tutoriais do AEM como um serviço](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html)em nuvem.

* **API em lote de comunicações interativas do AEM Forms**

   A API em lote de comunicação interativa do AEM Forms permite que os clientes produzam várias comunicações interativas, automaticamente ou sob demanda. Os clientes podem gerar saídas de Impressão e Web simultaneamente.
Consulte [Gerar várias comunicações interativas usando a API](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html)de lote.

* **Plataformas compatíveis com AEM Forms em JEE**

   Adição de suporte ao Oracle 19c para AEM Forms em clientes JEE.
Consulte Plataformas [suportadas para AEM Forms no JEE](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html).

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

## [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Campaign Classic 19.2.3

Consulte [Notas de versão do Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) para correções e melhorias.

### Campaign Standard 20.1

Consulte [Notas de versão do Adobe Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) para correções e melhorias.

### Recursos adicionais

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planejamento de versão](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Atualizado em 10 de fevereiro de 2020, para lançamento em 8 de fevereiro

| Exibir | Recurso |
|------|---------|
| Portfólios | Agora você pode adicionar o Yahoo! Campanhas da rede de exibição do Japão (YDN) para portfólios, a fim de otimizar os orçamentos da campanha e os lances de nível de grupo de anúncios. A mesma licitação é aplicada a todos os anúncios em um grupo de publicidade. Os dados para campanhas YDN são incluídos nas simulações do portfólio. |
| Pesquisar > Bulksheets | Agora você pode criar, editar e excluir anúncios de pesquisa responsivos do Google (RSAs) usando bulksheets. Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| Pesquisar > Campanhas, Relatórios | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

Para obter as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Fonte aberta do Magento 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
