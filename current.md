---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ed727b23cbc90965f44c4bb914728bbc2394d6b

---


# Notas de versão da Adobe Experience Cloud - março de 2020

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: março de 2020**

(as datas de lançamento de produtos específicos podem variar)

* [Status de sistema da Adobe](#status)
* [Interface da Experience Cloud e dos serviços principais](#ecloud)  (Atualização: **26 de fevereiro de 2020**)
* [Experience Platform](#platform)
* [Mobile Services e SDKs móveis](#mobile)
* [!DNL Analytics](#analytics) (Atualização: 21 de fevereiro de 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)

Procurando a página principal da ajuda? Consulte [Documentação da Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Status de sistema da Adobe {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

**Novidades**

* Usando sua Adobe ID, você pode assinar notificações de eventos, com base nos produtos, na região, no evento e nas preferências de idioma. Os usuários que configuram suas preferências de assinatura são notificados sobre incidentes relevantes do produto e eventos de manutenção assim que forem abertos, atualizados ou fechados. Comece em [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| -----------| ---------- |
| Percepção mais rápida dos eventos do produto | <ul><li>Receba informações 30 dias antes da manutenção futura do serviço. Esse recurso oferece mais tempo para avaliar o impacto potencial nas operações de negócios, permitindo que você implemente um plano de atenuação, se necessário.</li><li>As notificações avançadas estão disponíveis na Web/dispositivos móveis/tablets e por notificações de email.</li></ul> |
| Personalize sua experiência com base no idioma preferencial | <ul><li>Escolha um idioma preferencial para receber notificações por email. O recurso de Autoassinatura agora está disponível em dezenove idiomas.</li></ul> |
| Experiência do usuário de assinatura e notificação aprimorada | <ul><li>Especifique a região e as preferências de evento com apenas um clique para todos os produtos que você deseja assinar.</li><li>Receba notificações quando problemas _em potencial_ forem promovidos para problemas _menores_ ou _graves_.</li><li>A página do navegador é atualizada automaticamente quando qualquer produto ou status de evento é atualizado.</li></ul> |

## Interface da Experience Cloud e dos serviços principais {#ecloud}

Atualização da versão: **26 de fevereiro de 2016**

Novos recursos e correções na interface da Experience Cloud, incluindo administração e serviços principais (atributos do cliente, públicos-alvo, acionadores, cookies etc.).

| Recurso | Descrição |
| -----------| ---------- |
| Ferramenta de administração - exibir detalhes do usuário | Os administradores podem exibir uma lista classificável e filtrável de todos os usuários da Experience Cloud e seus detalhes na nova Ferramenta de administração. Os detalhes do usuário incluem o acesso ao produto, as funções e as últimas informações acessadas de um usuário. Consulte a ajuda da [Ferramenta de administração da Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) para obter detalhes. |

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

**Observação:** a página do [!UICONTROL Feed] será substituída em janeiro de 2020. Procure um aviso de desativação no produto.

Para consultar a documentação do produto, acesse [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Notas de versão da Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html)  (Todos os produtos da Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para obter as notas de versão e a documentação do produto.

## Mobile Services e SDKs móveis {#mobile}

Conteúdo móvel.

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)  (Atualizado em 21 de fevereiro de 2020)

Para obter a documentação do produto, consulte a [Página inicial de ajuda do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

* **Vários conjuntos de relatórios na Analysis Workspace**: Agora é possível trazer dados de vários conjuntos de relatórios para um único projeto da Analysis Workspace para visualização lado a lado. A partir de 12 de março de 2020, o recurso será lançado para todos os clientes durante várias semanas. [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Otimização** do público-alvo da Experience Cloud: Esse recurso permite que você publique segmentos na Experience Cloud dentro de 8 horas (em vez do tempo de processamento anterior de 48 horas). [Saiba mais...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)

#### Correções

* Correção de um problema no Relatórios e análises que impedia os clientes de baixar relatórios .xls.(AN-206541, AN-204008)
* O lançamento de um novo shell corrigiu vários problemas do cliente relacionados à alternância entre as organizações da Experience Cloud.(AN-200844, AN-186920)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição  ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Definição EOL da definição &quot;Nível de conversão&quot; | 3 de março de 2020 | A configuração Nível [de](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) conversão que não funciona em Ferramentas administrativas > Report Suites > Configurações gerais de conta está sendo removida da interface do usuário em 12 de março de 2020. |
| EOL do arquivo do painel | 3 de março de 2020 | A configuração &quot;Exibir arquivo&quot; em Gerenciar painéis no Relatórios e análises não estará mais disponível a partir de 12 de março de 2020. |
| Novo domínio do Adobe Analytics | 18 de dezembro de 2019 | Em 16 de janeiro de 2020, o Adobe Analytics começou a migrar para um novo domínio - `https://experience.adobe.com/analytics.`<br>**Observação:** essa alteração se aplica a todos os usuários que acessam o Analytics com sua Adobe ID ou Enterprise ID.<ul><li>O domínio pode causar problemas de cookie ao carregar o Analytics no Safari. Ao desmarcar _Impedir rastreamento entre sites_ nas Preferências de privacidade do Safari, os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Analytics poderá funcionar nesse novo domínio da Adobe Experience Cloud. Você pode usar outros navegadores sem problemas, pois isso afeta somente os usuários do Safari.</li><li>A alteração de domínio pode fazer com que o [!UICONTROL Activity Map] pare de funcionar para alguns clientes [em casos específicos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fim da vida útil - APIs antigas do Analytics | 9 de janeiro de 2020 | Em novembro de 2020, os seguintes serviços de API do Analytics Legacy chegarão ao fim da vida útil e serão encerrados. As integrações atuais criadas com esses serviços deixarão de funcionar. <ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| EOL (fim da vida útil) da opção **[!UICONTROL Exibir arquivo]** | 30 de outubro de 2019 | Anúncio do fim da vida útil em janeiro de 2020 da opção **[!UICONTROL Exibir arquivo]** no Gerenciador do painel (**[!UICONTROL Componentes > Painéis]**) para janeiro de 2020. |
| EOL (fim da vida útil) da opção **[!UICONTROL Impor restrições de logon de IP]** | 30 de outubro de 2019 | Anúncio do fim da vida útil da funcionalidade de lista de permissões de logon de IP (**[!UICONTROL Impor restrições de logon de IP]**) no menu **[!UICONTROL Admin > Configurações da empresa > Segurança]**. |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Singapura, não apoiaremos mais a intermediação de dados entre Londres ou Singapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Alteração futura em relação ao campo `createDate` para usuários do Analytics | 30 de agosto de 2019 | Em outubro ou novembro de 2019, o campo `createDate` para os usuários do Analytics foi atualizado do Horário do Pacífico dos EUA para um valor de data/hora corretamente formatado com as informações de fuso horário.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). A versão 2.19.0 foi lançada em 21 de fevereiro de 2020.

## Audience Manager {#aam}

Correções e recursos adicionados ao Audience Manager.

### Novos recursos, melhorias e correções no Audience Manager {#aam-features}

| Recurso | Descrição |
|----|----|
|  |  |
|  |  |

### Correções e melhorias {#aam-fixes-and-improvements}

Correções para o AAM.

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

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

### Recursos adicionais

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planejamento de versão](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Atualizado em 10 de fevereiro de 2020, para lançamento em 8 de fevereiro

## [!DNL Magento] {#magento}

Para ver as notas de versão do Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

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

**** Centro de sucesso de envolvimento de marketing: Lançamento em fevereiro de 2020. O Centro de sucesso é um centro de ajuda no produto que permite pesquisar em Documentos de produto e na Comunidade, iniciar guias tutoriais, acessar conteúdo de adoção e muito mais. Observação: esse recurso será lançado como um beta na ANZ para a América do norte posteriormente neste trimestre.

### Desativações

* **Parâmetro &quot;_method&quot; da API de ativo:** depois de setembro de 2020, os endpoints da API de ativos não aceitarão mais &quot;_method&quot; para transmitir os Parâmetros de consulta em um corpo POST para ignorar as limitações de comprimento de URI.
* **Desativação do suporte ao Internet Explorer:** a partir do lançamento realizado em 31 de julho de 2020, a interface do usuário do Marketo Engage não será mais compatível com o Internet Explorer.

Para obter as notas de versão cumulativas e históricas, consulte [Notas de versão do Marketo](https://docs.marketo.com/x/CgA6Ag).