---
title: Notas de versão para Experience Cloud e Experience Platform
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação para Experience Cloud e Experience Platform. Encontre nova ajuda e tutoriais sobre Creative Cloud para empresas e Document Cloud.
doc-type: release notes
last-update: February 2021
author: mfrei
translation-type: tm+mt
source-git-commit: 803595c63ab6db90fb17c9998c623c03e834aaa0
workflow-type: tm+mt
source-wordcount: '6384'
ht-degree: 32%

---


# Notas de versão da Adobe Experience Cloud - Fevereiro de 2021

![Banner](/assets/experience-cloud-banner-3.png)

As soluções e os serviços do Experience Cloud são atualizados mensalmente. Esta página é o local central para encontrar as atualizações, a documentação e os tutoriais mais recentes para [!DNL Experience Cloud] e Experience Platform. Você também pode encontrar nova documentação para [!DNL Creative Cloud for Enterprise] e [!DNL Document Cloud].

>[!IMPORTANT]
>
>Esta página contém conteúdo de pré-lançamento e está sujeita a alterações antes das datas de lançamento.

>[!NOTE]
>
>Assine a [Atualização mensal do produto de prioridade da Adobe](https://www.adobe.com/subscription/priority-product-update.html) para receber notificações por email sobre atualizações nesta página. Esta página é mantida durante todo o mês, portanto, verifique regularmente se há atualizações no produto Adobe enterprise e na documentação do Experience League.

Última atualização: **12 de fevereiro de 2021**

* [Status de sistema da Adobe](#status)
* [Serviços e administração da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [](#analytics) **Analytics atualizado em 19 de fevereiro de 2021**
* [Customer Journey Analytics](#cust-journey)`
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insight da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/adobe.png) Adobe da sistema de Status {#status}

O [!UICONTROL Status de sistema da Adobe] fornece informações detalhadas, atualizações de status e notificações por email sobre produtos e serviços em nuvem da Adobe, interrupção e eventos de manutenção. Confira em [status.adobe.com](https://status.adobe.com/).

Não foi atualizado este mês.

Consulte o [Status do sistema da Adobe - 21 de maio de 2020](https://docs.adobe.com/content/help/pt-BR/release-notes/experience-cloud/previous/2020/05212020.html#status) para obter as informações da versão mais recentes.

## ![Ícone](/assets/ec_appicon_24.png) Serviços e administração da Experience Cloud {#ecloud}

[A documentação de serviços e administração da Experience Cloud](https://docs.adobe.com/content/help/pt-BR/core-services/interface/experience-cloud.html) inclui Atributos do cliente, Biblioteca de público-alvo ([!UICONTROL serviço de] Pessoas), Activation, gerenciamento de usuário e produto e cookies da Experience Cloud.

**4 de fevereiro de 2021**

* **Atualização de logon:** uma atualização para o Experience Cloud remove a tela inicial de introdução de login no Experience Cloud. A partir de 4 de fevereiro, você será redirecionado diretamente de `https://experience.adobe.com/login` para a tela de logon da Adobe.

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Inclui informações de atualização de versão da Experience Platform e do Experience Platform Launch.

* [Notas de versão da Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR). (27 de janeiro de 2021)
* [Notas de versão da Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=pt-BR). (13 de janeiro de 2021)

### Tutoriais e cursos sobre Experience Platform

Novos vídeos, tutoriais ou cursos publicados para a Experience Platform e serviços.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 10 de fevereiro de 2021 | [Configurar o destino do blob do Azure](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | Vídeo | Saiba como percorrer as etapas necessárias para configurar e configurar o destino do Armazenamento Blob do Azure na Plataforma de Dados do Cliente em Tempo Real (CDP em Tempo Real). |
| 4 de fevereiro de 2021 | [Gráficos de identidade de visualização](https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/view-identity-graphs.html) | Vídeo | Como usar o recurso do visualizador de gráficos de identidade para pesquisar, explorar e filtrar gráficos de identidade para validação e depuração. |
| 3 de fevereiro de 2021 | [Visão geral da ingestão de dados em lote](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/batch-ingestion-overview.html) | Vídeo | Uma visão geral da ingestão de dados em lote no Adobe Experience Platform. Saiba como assimilar dados em lote usando a API. |
| 3 de fevereiro de 2021 | [Ativar dados para aplicativos que não sejam de Adobe](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/activate-data-to-non-adobe-applications.html) | Vídeo | Saiba como a CDP em tempo real do Adobe ajuda a criar estratégias de personalização verdadeiras com suas audiências. Além disso, saiba como ele se dobra em seu ecossistema existente e em aplicativos que não sejam de Adobe da Microsoft, do Google e do Facebook. |
| 21 de janeiro de 2021 | [Introdução ao curso para introdução aos serviços inteligentes para profissionais de marketing](https://video.tv.adobe.com/v/330805?quality=12&learn=on) | Vídeo | Uma introdução ao curso Introdução aos Serviços inteligentes para profissionais de marketing. |
| 13 de janeiro de 2021 | [Introdução à Introdução ao Offer Decisioning para profissionais de marketing](https://video.tv.adobe.com/v/330520?quality=12&learn=on) | Vídeo | E introdução ao curso Introdução ao Offer Decisioning para profissionais de marketing. |
| 31 de janeiro de 2021 | [Treinar, marcar e produzir modelos com o modelo do construtor de receitas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/train-score-and-productize-models.html) | Vídeo | Saiba como usar o modelo atualizado do construtor de receitas para criar uma receita usando o schema de vendas de varejo e os conjuntos de dados. |
| 31 de janeiro de 2021 | [Carregar dados em notebooks JupyterLab](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/load-data-in-jupyterlab-notebooks.html) | Vídeo | Saiba mais sobre o JupyterLab na Data Science Workspace. |
| 12 de janeiro de 2021 | [Criar Políticas de Mesclagem](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/create-merge-policies.html) | Vídeo | Saiba como criar políticas de mesclagem no Adobe Experience Platform. |

## ![Ícone](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Use a Adobe Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Últimas versões de produtos

Saiba mais sobre os recursos, melhorias e correções mais recentes nas [Notas de versão do Journey Orchestration](https://docs.adobe.com/content/help/pt-BR/journeys/using/release-notes/release-notes.html).

### Novos cursos e tutoriais do Journey Orchestration

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 22 de janeiro de 2021 | [Mudar para outra jornada](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/jumping-to-another-journey.html) | Vídeo | Saiba como conduzir indivíduos de uma jornada para outra. |

### Mais recursos para o Journey Orchestration

[Documentação](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **18 de fevereiro de 2021**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices) **Atualizado em 19 de fevereiro de 2021**
* [Cursos e tutoriais do Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/pt-BR/analytics/landing/an-releases.html) - Data do Target | Descrição |
| ----------- | ---------- | ------- |
| Analysis Workspace - seleção de componentes | 4 de fevereiro de 2021 | O componente de zona suspensa/de lançamento encontrado em [!UICONTROL Quick Insights] foi adicionado a todas as zonas de lançamento no [!UICONTROL Workspace]. Essa melhoria permite que você escolha em uma lista suspensa de componentes compatíveis ou continue a usar o espaço como uma zona de lançamento. |
| Seleção de idioma dos painéis do Analytics | 14 de janeiro de 2021 | Navegue até **[!UICONTROL Configurações]** > **[!UICONTROL Preferências]** > **[!UICONTROL Idioma]** para selecionar um idioma no painel do Analytics. |

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | [Disponibilidade geral](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Data do Target | Descrição |
| ----------- | ---------- | ----- |
| Analysis Workspace - seleção de componentes | 4 de fevereiro de 2021 | O componente de zona suspensa/de lançamento encontrado em [!UICONTROL Quick Insights] foi adicionado a todas as zonas de lançamento no [!UICONTROL Workspace]. Essa melhoria permite que você escolha em uma lista suspensa de componentes compatíveis ou continue a usar o espaço como uma zona de lançamento. |
| API CJA | 18 de fevereiro de 2021 | As APIs CJA agora estão disponíveis. Essas APIs permitem que você edite componentes de forma programática e recupere relatórios. Consulte a [documentação da API CJA](https://adobe.io/cja-apis/docs) para obter mais informações. |

### Correções no Adobe Analytics {#aa-fixes}

* Correção de um problema que resultava no aumento do tempo limite do gateway da API do Adobe Analytics 2.0 para 300 segundos (5 minutos). (AN-232335)
* Correção de problemas de desempenho com o Workspace, a API 2.0 e o relatórios Adobe Report Builder (AN-245644, AN-244504, AN-243060)
* Correção de um problema que causava um erro ao clicar em **Adicionar** no Feed de dados do Analytics [!UICONTROL Feed]. (AN-243171)
* Correção de problemas com classificações que não classificavam dados. (AN-243823, AN-247049, AN-244114)
* Correção de um problema com projetos agendados: os clientes só podiam ver os projetos que tinham, mas não todos os projetos agendados (AN-246955)
* Correção de um problema com o painel A4T em [!UICONTROL Workspace] que fazia com que os projetos não fossem abertos. (AN-246881)
* Correção de um problema com [!UICONTROL Workspace] a gerar um erro relacionado a A4T [!UICONTROL Métricas calculadas]. (AN-247082)
* Correção de um problema em que as solicitações de API de Data Warehouse não retornavam dados. (AN-236931)
* Correção de um problema que fazia com que o acesso a um conjunto de relatórios virtual só fosse possível em conjunto com o acesso ao conjunto de relatórios pai. (AN-247042)
* Correção de um problema que causava um erro ao converter projetos de [!UICONTROL Ad Hoc Analysis] para [!UICONTROL Workspace]. (AN-221215)
* Correção de um problema com o número incorreto de projetos filtrados exibidos no [!UICONTROL Gerenciador de projetos da Workspace]. (AN-244934)

#### Outras correções do Adobe Analytics

AN-224987; AN-229009; AN-239750; AN-239765; AN-241620; AN-242996; AN-243577; AN-243774; AN-244509; AN-244746; AN-244763; AN-244868; AN-244960; AN-245016; AN-245097; AN-245727; AN-246141; AN-246283; AN-246340; AN-246532; AN-246669; AN-246744; 246763; AN-246892; AN-246898; AN-246961; AN-247643; AN-247048; AN-247134; AN-247758; AN-247774; AN-248179; AN-248226; AN-248297; AN-248300; AN-248303; AN-248376; AN-248495; AN-248647

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| ----------- | ---------- | ---------- |
| Opções de landing page do Relatórios e análises | 19 de fevereiro de 2021 | Em 25 de março de 2021, as opções para definir novos painéis do Relatórios e análises ou outro conteúdo conforme sua landing page Adobe Analytics serão removidas. Se você tiver definido anteriormente uma página de Relatórios e análises como sua landing page personalizada, ela continuará a funcionar até que sua landing page seja modificada em [!UICONTROL Preferências do usuário]. A partir de 25 de março de 2021, não será mais possível definir novas landings page personalizadas do Relatórios e análises. |
| Fim da vida útil do Ad Hoc Analysis | Jan. 2021 | [!UICONTROL A ] análise ad hoc atinge sua data de término em 1º de março de 2021. Para obter mais informações, visite [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| Fim da vida útil para três serviços de API do Analytics | 6 de janeiro de 2021 | Em 30 de abril de 2021, os serviços de API herdados a seguir do Analytics estão programados para atingir sua data de fim de vida e serão encerrados. Quaisquer integrações atuais criadas com esses serviços deixarão de funcionar nesse dia.<ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>Fornecemos uma seção [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder às suas perguntas e fornecer orientação sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics, que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |
| Fim da vida útil do Data Connectors da Adobe | 13 de julho de 2020 | Os [!UICONTROL Data Connectors] da Adobe são alimentados por tecnologia herdada que não é mais viável ou compatível. Um novo padrão está disponível no Programa [Adobe Exchange Partner](https://partners.adobe.com/exchangeprogram/experiencecloud). Você pode usar esse padrão para que qualquer integração continue a ser oferecida e suportada. A data de término oficial é 1º de agosto de 2021. [Saiba mais...](https://docs.adobe.com/content/help/pt-BR/analytics/import/dataconnectors/data-connectors-eol.html) |
| Adicionar cabeçalho HSTS a todas as solicitações HTTPS recebidas | 29 de setembro de 2020 | Em 29 de setembro de 2020, o Adobe começou a adicionar o cabeçalho HSTS a todas as solicitações recebidas que usam HTTPS. Esse cabeçalho instrui o navegador ou cliente a fazer todas as solicitações futuras em HTTPS, o que é uma prática recomendada de segurança. Nesse ponto, o Adobe não imporá isso para solicitações recebidas usando HTTP. |
| Alteração na configuração de cookie do [!UICONTROL Experience Cloud ID Service]. | 22 de setembro de 2020 | Uma atualização das configurações de privacidade do Chrome versão 80 afetou a capacidade do Adobe Analytics de rastrear alguns usuários que visualizam páginas do Google AMP. Especificamente, impede o rastreamento entre domínios de usuários que visualizam páginas do AMP hospedadas no Google. Isso pode resultar em contagens infladas de visitantes únicos. Essa correção permite que os usuários solucionem esse problema alterando as configurações de seus cookies da ECID.<br>Atualmente, o Analytics define cookies da [!UICONTROL Experience Cloud ID] (ECID) com a configuração `SameSite = Lax` que, antes da versão 80 do Chrome, permitia o rastreamento em vários domínios. Isso não acontece mais. Essa alteração permite que os usuários atualizem a configuração SameSite para cookies da ECID `None`.<br>Essa alteração permite que o cookie do Analytics seja compartilhado em mais situações, mas os cookies do Analytics não contêm informações confidenciais. Além disso, ao escolher essa configuração, os cookies devem ser definidos como `Secure` para que os dados só possam ser transmitidos por conexões HTTPS. Se você quiser fazer essa alteração, um usuário suportado poderá abrir um ticket com o Atendimento ao cliente. |

### AppMeasurement {#appm}

Para obter as atualizações mais recentes das versões do AppMeasurement, consulte as [notas de versão do AppMeasurement para JavaScript](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/appmeasurement-updates.html).

### Cursos e tutoriais do Analytics {#tutorials-analytics}

Novos cursos, tutoriais e artigos no [!DNL Analytics] e no [!UICONTROL Customer Journey Analytics].

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 8 de fevereiro de 2021 | [Adicionar linhas de tendência a visualizações de linha](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/adding-trendlines-to-line-visualizations.html?lang=en) | Vídeo | Em Configurações de visualização, você pode optar por adicionar uma regressão ou mover a linha de tendência média para sua série de linhas. Esse recurso ajuda a retratar um padrão mais claro nos dados. |
| 8 de fevereiro de 2021 | [Adicionar plug-ins de implementação no Platform Launch](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/implementation/via-adobe-launch/adding-implementation-plug-ins-in-launch.html?lang=en#implementation) | Vídeo | Os plug-ins de implementação são partes do código JavaScript que podem ser adicionadas à implementação do Analytics para rastrear dados adicionais e personalizados. Neste vídeo, saiba como e onde adicionar o código no Platform Launch. |
| 6 de janeiro de 2021 | [Painel Visualizadores simultâneos de mídia no Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) | Vídeo | Entenda onde o pico de simultaneidade ocorreu ou onde as quedas ocorreram. Obtenha insight valioso sobre a qualidade do envolvimento do conteúdo e do visualizador, e ajuda na solução de problemas ou no planejamento de volume e escala. |

### Recursos de ajuda do Analytics

* [Documentação e tutoriais do produto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR)

## ![Ícone](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Novos recursos, correções, documentação e tutoriais no Audience Manager.

| Recurso | Data de adição ou atualização | Descrição |
|----|----|----|
| [Migração de usuário Audience Manager para Admin Console](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/admin-console-migration.html) | 1 de fevereiro de 2021 | O gerenciamento de conta de usuário do Audience Manager está migrando para a Adobe Admin Console, para obter uma experiência mais simplificada nas soluções de Adobe. <br>Siga as etapas descritas neste artigo para facilitar a migração do usuário. Todos os administradores de Audience Manager devem start para migrar suas contas de usuário para a Adobe Admin Console o mais rápido possível. |

### Correções e melhorias {#aam-fixes-and-improvements}

* Correção de um problema no [Relatório de status onboard](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html). Nesse problema, havia uma discrepância entre os registros no relatório e os do arquivo carregado por um parceiro onboard. (AAM-57415)
* Correção de um problema com a clonagem **[!UICONTROL Model]** no recurso **[!UICONTROL Audiências preditivas]**. (AAM-56775)
* Correção de um problema com características e segmentos duplicados em que o traço ou segmento errado era duplicado. (AAM-57351)
* Correção de um problema em que a caixa de seleção **[!UICONTROL Marcar todos]** em **[!UICONTROL Modelos > Excluir características]** não era clicável para usuários. (AAM-57366)
* Correção de um problema no Construtor de segmentos **** em que a caixa de seleção **[!UICONTROL Selecionar tudo]** não selecionava todas as características. (AAM-55640)

### Cursos e tutoriais do Audience Manager {#tutorials-aam}

Novos vídeos, tutoriais ou cursos publicados para o Audience Manager.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 5 de fevereiro de 2021 | [Etapas para inserir dados baseados em arquivo](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/steps-for-ingesting-file-based-data.html?lang=en#integrating-offline-data) | Vídeo | Saiba mais sobre as etapas que você deve considerar como dados offline integrados no Audience Manager, incluindo os requisitos de nome de arquivo para o arquivo de dados. |
| 5 de fevereiro de 2021 | [Formatação e inserção de dados baseados em arquivo](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/formatting-and-ingesting-file-based-data.html?lang=en#integrating-offline-data) | Vídeo | Ao trazer seus dados primários para o Audience Manager para melhor entender e público alvo seu cliente, existem determinados requisitos de formatação para os dados. Saiba mais sobre algumas das principais opções e onde obter mais informações. |
| 5 de fevereiro de 2021 | [Criação de uma fonte de dados entre dispositivos e autenticação](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/data-sources/creating-a-cross-device-data-source-and-authenticating.html?lang=en#setup-and-admin) | Vídeo | Saiba como criar uma fonte de dados entre dispositivos para armazenar as IDs e os dados do CRM ao trazer seus dados do CRM primários para o Audience Manager. Este vídeo mostra como fazer isso e configurar o método `setCustomerIDs()` no Experience Platform Launch para logons. |
| 3 de fevereiro de 2021 | [Introdução ao curso - Criação e gerenciamento da Ativação de dados no Audience Manager](https://video.tv.adobe.com/v/331001) | Vídeo | Segmentos de audiência não valem nada a não ser que você realmente faça algo com eles. Este curso ensina como usar o audiência para personalizar a experiência do usuário. Este vídeo introdução faz com que você comece no seu caminho. |
| 28 de janeiro de 2021 | [Criação e gerenciamento de características](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.3) | Curso | Saiba mais sobre como criar e organizar características do [!UICONTROL Construtor de características] no [!UICONTROL Gerenciamento em massa] ferramenta. Saiba também como usar a ferramenta [!UICONTROL Data Explorer] para descobrir sinais importantes que entram no Audience Manager e criar características para eles. |
| 22 de janeiro de 2021 | [Usando relatórios de Audience Optimization para entender o desempenho da mídia](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/using-audience-optimization-reports-to-understand-media-performance.html?lang=en#reports) | Vídeo | Saiba mais sobre como usar os Relatórios de Audience Optimization para melhorar suas campanhas, como entender onde investir seus dólares de marketing e onde parar de investir. Saiba também como determinar o limite de frequência ideal e encontrar outros gems nesses relatórios. |
| 15 de janeiro de 2021 | [Entender Audiências relacionadas com relatórios de sobreposição](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/understand-related-audiences-with-overlap-reports.html?lang=en#reports) | Vídeo | Os relatórios de sobreposição permitem que você veja como as audiências de características e segmentos se sobrepõem (mesmo visitante em vários traços ou segmentos), para que você saiba onde pode agir com seus dados para aumentar a conversão ou o foco no alcance de expansão. |
| 12 de janeiro de 2021 | [Usando rótulos de exportação de dados para controlar o fluxo de dados](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/data-activation/destinations-basics/using-data-export-labels-to-control-data-flow.html?lang=en#data-activation) | Vídeo | As Rótulos de exportação de dados fornecem um mecanismo no Audience Manager para controlar o fluxo de diferentes tipos/fontes de dados, para que você possa atender aos seus requisitos de privacidade. Saiba como e onde definir os Controles de exportação de dados e os Rótulos de exportação de dados, para trabalhar em conjunto com esse fim. |
| 22 de janeiro de 2021 | [Importar segmentos do Adobe Analytics para o Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/import-aa-segments-into-aam.html?lang=en#build-and-manage-audiences) | Vídeo | Além de encaminhar dados em tempo real da Adobe Analytics para o Audience Manager, você também pode importar segmentos que incluem dados pós-processados do Analytics para o Audience Manager através do Experience Cloud. |

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

Novos recursos, correções e atualizações no Experience Manager. A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

>[!NOTE]
>
>A Adobe recomenda visitar a página [atualizações de versões do Experience Manager e roteiro](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para manter-se atualizado com as informações de lançamento.

### Versões do produto

* **Experience Manager as a Cloud Service**

   Novos recursos no Experience Manager como Cloud Service

   * **Experience Manager Assets as a Cloud Service**

      * **Serviço de Gestão de conteúdo sem cabeça**

         * [API GraphQL para o Delivery](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-api-content-fragments.html) de fragmento do conteúdo: Capacidade de query de Fragmentos de Conteúdo usando a sintaxe GraphQL e schemas com base em modelos de Fragmento de Conteúdo, para saída no formato JSON.
         * [Suporte de autenticação para solicitações](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-authentication-content-fragments.html) da API GraphQL: Capacidade de autenticar solicitações de API GraphQL com tokens de acesso para APIs do lado do servidor.
         * [O componente](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html) RemotePage: Adição de suporte para exibição e edição de SPA externos em AEM usando.
         * [Edição de um SPA externo em AEM](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html): Foi adicionada a capacidade de carregar um aplicativo independente de página única em uma instância AEM, adicionar seções editáveis de conteúdo e ativar a criação.
         * Saída JSON aprimorada da API GraphQL, incluindo a capacidade de produzir rich text no formato JSON e localidades.
         * Suporte para aninhamento de modelos de Fragmento de conteúdo para permitir a criação de estruturas aninhadas de Fragmento de conteúdo, por meio de tipos de dados dedicados de Referência de fragmento de conteúdo ou referências de fragmento de conteúdo embutidas em campos de texto de várias linhas.
         * Mais regras de validação disponíveis nos tipos de dados do modelo de Fragmento de conteúdo, incluindo &quot;exclusivo&quot;, &quot;obrigatório&quot; e &quot;traduzível&quot;.
         * Capacidade de marcar modelos de Fragmento de conteúdo e permitir a criação de Fragmento de conteúdo em uma pasta com políticas por tags ou caminhos.
         * Aprimoramentos de usabilidade no editor de Fragmento de conteúdo, incluindo ação de publicação e exibição do modelo no qual um fragmento é baseado.
         * Capacidade de pré-visualização da saída JSON diretamente no editor de fragmento de conteúdo.
      * **Aplicativos Web progressivos (PWA)**

         * [Uma versão de aplicativo da Web progressivo (PWA) de um ](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/enable-pwa.html?lang=en) sitecan agora pode ser ativada no nível do projeto por meio de uma configuração simples.
   * **Experience Manager Assets como um Cloud Service**

      * O Experience Manager como Cloud Service estende a funcionalidade de Tags inteligentes para suportar a identificação de palavras-chave e entidades em ativos baseados em texto. O texto é identificado, indexado e disponibilizado como metadados para melhorar a experiência de pesquisa sem a necessidade de qualquer configuração. Consulte [Tags inteligentes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/smart-tags.html).
      * O formato de arquivo MXF agora é compatível. Consulte [formatos de arquivo suportados](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/file-format-support.html#video-formats).
   * **Experience Manager Commerce as a Cloud Service**

      * **Novidades?**

         * Gerenciamento da experiência do produto: Nova guia de propriedades &quot;Comércio&quot; para Ativos e Fragmentos de experiência. Esta guia permite que você vincule produtos / categorias a ativos e fragmentos de experiência. A guia também mostra dados em tempo real para produtos/categorias vinculados e um link para mostrar detalhes no console do produto.
         * Lançamento do site de referência CIF Venia - 2021.02.02 que inclui a versão mais recente dos componentes principais CIF v1.7.0. Consulte [CIF Site de Referência de Venia](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.02) para obter mais detalhes.
         * Componentes principais CIF lançados v1.7.0. Consulte [CIF Componentes principais](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.7.0) para obter mais detalhes.
      * **Analisadores de compilação do SDK**

         O Experience Manager como um plug-in Cloud Service SDK Build Analyzer Maven detecta problemas em um projeto maven, incluindo dependências ausentes. Ele oferece aos desenvolvedores uma oportunidade de encontrar problemas durante o desenvolvimento local, bem antes de implantar ambientes da Cloud com o Cloud Manager.

         Dois novos analisadores foram adicionados para esta versão:

         * analisador de repontas
         * bundle-nativecode

         Para obter mais informações, consulte a documentação [here](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html#developing).
   * **Ferramentas de transição para a nuvem**

      * **Novidades da Ferramenta de transferência de conteúdo**

         * Novo recurso e interface adicionada à Ferramenta de transferência de conteúdo - Ferramenta de mapeamento do usuário. Esse recurso mapeia automaticamente usuários e grupos existentes para suas IDs de sistema Adobe Identity Management como parte da atividade de migração de conteúdo.
Consulte [Usando a Ferramenta de Mapeamento de Usuário](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-user-mapping-tool.html).
         * A Ferramenta de transferência de conteúdo agora migra todos os grupos e usuários referenciados no conjunto de migração, incluindo filhos.
         * Os usuários podem selecionar determinados caminhos em `/etc` ao criar conjuntos de migração.







### **Comunidade**

* **Desenvolvedores Adobe Live 2021 | lista Concluir sessão**

   Por solicitação popular, [here](https://adobe.ly/3cldljt) é uma lista agregada de todas as sessões Experience Manager que ocorrem no Adobe Developers Live. Todas as gravações e P&amp;R de cada sessão são publicadas nos respectivos Threads contextuais.

* **Lista do conteúdo mais recente do Adobe Experience Manager no Experience League | Janeiro de 2021**

   A fonte oficial do conteúdo técnico da Digital Experience produzido pela Adobe. Veja a lista completa [aqui](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156).

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Atualizações de versão e roteiro do Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager como informações de lançamento de Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/release-notes/home.html)
* [Notas de versão do Experience Manager Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://docs.adobe.com/content/help/pt-BR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://docs.adobe.com/content/help/pt-BR/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager 6.4 Notas de versão do Cumulative Fix Pack](https://docs.adobe.com/content/help/pt-BR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notas de versão do Experience ManagerAssets Dynamic Media](https://docs.adobe.com/content/help/pt-BR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de versão do Portal de marcas do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=pt-BR)
* [Notas de versão do aplicativo para desktop Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-desktop-app/using/release-notes.html)
* [Notas de versão do Dispatcher Experience Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notas de versão do Livefyre](https://docs.adobe.com/content/help/pt-BR/livefyre/using/release-notes/c-rn.html)

### cursos e tutoriais de Experience Manager

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 11 de fevereiro de 2021 | [Autenticação para AEM como Cloud Service de um aplicativo externo](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | Curso | Saiba como um aplicativo externo pode usar [!UICONTROL Token de acesso de desenvolvimento local] e [!UICONTROL Credenciais de serviço] para autenticar programaticamente para Experience Manager como Cloud Service por HTTP. |
| 11 de fevereiro de 2021 | [Relacionar e não relacionar ativos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | Vídeo | Saiba como estabelecer e gerenciar relações entre ativos no Experience Manager. |
| 8 de fevereiro de 2021 | [AEM Sites - Tutorial WKND](https://docs.adobe.com/content/help/en/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html) | Tutorial | Bem-vindo a um tutorial de várias partes projetado para desenvolvedores novos ao Experience Manager. Este tutorial aborda a implementação de um site de Experience Manager para uma marca de estilo de vida fictício na WKND. |
| 1 de fevereiro de 2021 | [Criando seu primeiro pacote OSGi](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/create-your-first-osgi-bundle.html?lang=en) | Artigo | Saiba como criar seu primeiro pacote OSGi usando o maven e o eclipse. |
| 1 de fevereiro de 2021 | [Publicar ativos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/publish.html) | Vídeo | Saiba mais sobre como publicar ativos e suas execuções do Autor do Experience Manager para o AEM Publish. |
| 4 de fevereiro de 2021 | [Desenvolvimento local](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/local-development-environment.html) | Vídeo | Saiba como baixar e configurar um ambiente de desenvolvimento local usando o Experience Manager como um SDK de Cloud Service. |
| 4 de fevereiro de 2021 | [Estrutura do projeto](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/project-structure.html) | Vídeo | Explore as práticas recomendadas para estruturar um projeto Experience Manager Maven para AEM como Cloud Service. |
| 4 de fevereiro de 2021 | [Migrar configurações do Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/dispatcher-configuration.html) | Vídeo | Visão geral das diferenças nas configurações do Dispatcher e dicas e truques para migrar o Dispatcher do Adobe Managed Services (AMS) para o Experience Manager como Cloud Service. |
| 2 de fevereiro de 2021 | [Introdução ao AEM SDK](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/aem-sdk.html) | Vídeo | Usar e configurar o SDK para Experience Manager como Cloud Service. |
| 2 de fevereiro de 2021 | [O que é AEM Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/what-is-aem-as-a-cloud-service.html) | Vídeo | Explore o que é Experience Manager como um Cloud Service e como ele é diferente de outras versões do Adobe Experience Manager. |
| 2 de fevereiro de 2021 | [Função do Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/cloud-manager.html) | Vídeo | Explore a finalidade do [!UICONTROL Cloud Manager] e como ele funciona com o Experience Manager como um Cloud Service. |
| 2 de fevereiro de 2021 | [Evolução da AEM como Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/evolution.html) | Vídeo | Explore o histórico do Experience Manager e as diferenças entre o Experience Manager local, o AEM de serviços gerenciados da Adobe e o Experience Manager como Cloud Service. |
| 2 de fevereiro de 2021 | [Arquitetura do AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/architecture.html) | Vídeo | Explore a arquitetura subjacente e as peças importantes do Experience Manager como um Cloud Service. Analise detalhadamente o Cloud Manager e as APIs. |
| 2 de fevereiro de 2021 | [Usar APIs do Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/cloud-manager-apis.html) | Vídeo | Saiba como as APIs do Cloud Manager podem ser usadas para estender e integrar-se a outros sistemas. |
| 2 de fevereiro de 2021 | [Analisar resultados do teste](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/analyze-test-results.html) | Vídeo | Explore quaisquer erros de compilação no código e se este código segue as práticas recomendadas para o Experience Manager como Cloud Service |
| 2 de fevereiro de 2021 | [Configurar Pipelines](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/configure-pipelines.html) | Vídeo | Explore os diferentes tipos de pipelines no Cloud Manager e como configurá-los para um projeto bem-sucedido. |
| 2 de fevereiro de 2021 | [Gerenciar configurações do Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/dispatcher-configurations.html) | Vídeo | Use as práticas recomendadas e exemplos para explorar como o dispatcher funciona com o Experience Manager como Cloud Service e o Cloud Manager. |
| 2 de fevereiro de 2021 | [Integrações contínuas e Gerenciador de nuvem](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/continuous-integration.html) | Vídeo | Entenda as práticas recomendadas e a integração contínua usando o Adobe Cloud Manager. |
| 2 de fevereiro de 2021 | [Mesclar AEM projetos para implantação usando o Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/merge-projects.html) | Vídeo | Saiba como vários projetos podem ser mesclados em um único projeto para implantação no Experience Manager como Cloud Service usando o Cloud Manager. |
| 2 de fevereiro de 2021 | [Implantação de projetos do Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/deploy-code.html) | Vídeo | Integre o repositório git do gerenciador de nuvem com um repositório git externo e implante um projeto no Experience Manager como Cloud Service. |
| 2 de fevereiro de 2021 | [Publicação de conteúdo](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/content-publishing.html) | Vídeo | Saiba como a publicação de conteúdo no Experience Manager como um Cloud Service, incluindo conceitos de Distribuição de conteúdo e pipeline do Adobe. |
| 2 de fevereiro de 2021 | [Autenticação baseada em token - Credenciais de serviço](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials.html?lang=en#authentication) | Vídeo | Saiba mais sobre a autenticação baseada em token para integrações com Experience Manager como Cloud Service. |
| 2 de fevereiro de 2021 | [Assinar vários Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/introduction.html?lang=en#sign-multiple-documents) | Tutorial | Se estiver solicitando uma hipoteca ou abrindo uma nova conta bancária, você deverá preencher e assinar vários formulários. A integração entre o Experience Manager Forms e o Adobe Sign facilita o preenchimento e a assinatura de vários formulários. |
| 28 de janeiro de 2021 | [Autenticação baseada em token - Token de acesso de Desenvolvimento local](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/local-development-access-token.html?lang=en#authentication) | Vídeo | Saiba como o Console do Desenvolvedor permite que o desenvolvedor gere tokens de acesso temporários que podem ser usados para acessar o Experience Manager de forma programática. |
| 28 de janeiro de 2021 | [Autenticação baseada em token para AEM como Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | Vídeo | Saiba como um aplicativo externo pode autenticar e interagir programaticamente com o Experience Manager como um Cloud Service por HTTP usando tokens de acesso. |
| 24 de janeiro de 2021 | [Criar o formulário principal para acionar o processo](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/create-initial-form.html) | Artigo | O formulário inicial (Formulário de refinanciamento) é usado para assinar vários formulários acionando o fluxo de trabalho [!UICONTROL Assinar vários AEM] do Forms. |
| 8 de janeiro de 2021 | [Execução do pipeline de produção CI/CD do Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | Vídeo | A configuração do CI/CD Production Pipeline define o acionador que inicia o pipeline, os parâmetros que controlam a implantação da produção e os parâmetros de teste de desempenho. |
| 8 de janeiro de 2021 | [Atividade do Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/activity.html) | Vídeo | O Cloud Manager fornece uma visualização consolidada para a atividade de um Programa, listando todas as execuções do CI/CD Pipeline, tanto de produção quanto de não produção. Esse recurso permite que os usuários visualizações todos os pipelines em andamento e revisem implantações anteriores. |
| 8 de janeiro de 2021 | [Pipelines de não produção do Adobe Cloud Manager CI/CD](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-non-production-pipeline.html) | Vídeo | IC/CD Os gasodutos de não produção são divididos em duas categorias, dutos de qualidade de código e pipelines de implantação. A qualidade do código pipelines todo o código de uma ramificação Git para criar e ser avaliado em relação à verificação da qualidade do código do Cloud Manager. |
| 8 de janeiro de 2021 | [Configuração do pipeline de produção CI/CD do Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | Vídeo | A configuração do CI/CD Production Pipeline define o acionador que inicia o pipeline, os parâmetros que controlam a implantação da produção e os parâmetros de teste de desempenho. |
| 8 de janeiro de 2021 | [Ambientes do Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/environments.html) | Vídeo | Os Ambientes do Cloud Manager são compostos de Experience Manager Author, Experience Manager Publish e Dispatcher Services. Diferentes ambientes suportam funções e podem ser envolvidos usando diferentes Pipelines de CI/CD. Os ambientes do Cloud Manager geralmente têm um ambiente de produção, um ambiente de estágio e um ambiente de desenvolvimento. |
| 8 de janeiro de 2021 | [Visão geral do GraphQL sem cabeçalho](https://internal.adobedemo.com/content/demo-hub/en/demos/internal/aem-headless-graphql.html) | Demonstração | Experience Manager de conteúdo expõe o conteúdo da APIs do Experience Manager para downstream. As APIs GraphQL podem ser usadas em casos de uso sem cabeçalho e híbrido. |
| 8 de janeiro de 2021 | [Programas do Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/programs.html) | Vídeo | Os Programas do Cloud Manager representam conjuntos de ambientes Experience Manager que suportam conjuntos lógicos de iniciativas de negócios, geralmente correspondentes a um SLA (Service Level Agreement, contrato de nível de serviço) adquirido. |
| 8 de janeiro de 2021 | [Autenticação baseada em token](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | Vídeo | Os Programas do Cloud Manager representam conjuntos de ambientes Experience Manager que suportam conjuntos lógicos de iniciativas de negócios, geralmente correspondentes a um SLA (Service Level Agreement, contrato de nível de serviço) adquirido. |
| 8 de janeiro de 2021 | [Importação em massa](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html) | Vídeo | A ferramenta Importação em massa no Experience Manager como Cloud Service permite que os administradores importem ativos em massa do armazenamento em nuvem (Armazenamento Blob do Azure ou Amazon S3) de uma maneira segura e eficiente. |

### Outros recursos de Ajuda para Experience Manager

* [Experience Manager como guias de Cloud Service](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-service/landing/home.html)
* [Página inicial de aprendizado e suporte do Experience Manager 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Página inicial de Aprendizagem e suporte do Experience Manager 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do Experience Manager 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Página inicial de aprendizado e suporte do Experience Manager 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://docs.adobe.com/content/help/pt-BR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versões anteriores da documentação do Experience Manager](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/pt-BR/dynamic-media-classic/using/home.html)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produtos

Saiba mais sobre os recursos, melhorias e correções mais recentes lançados:

* [Notas de versão do Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-notes.html)
* [Notas de versão do Campaign Classic](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/release-notes/latest-release.html)

### Novos cursos e tutoriais do Campaign

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Solução | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 5 de fevereiro de 2021 | [Introdução ao Adobe Campaign Classic for Business Users](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.classic) | Campaign Classic | Após concluir este curso, você entenderá os conceitos da Adobe Campaign Classic e saberá como criar sua primeira campanha de marketing. |
| 1 de fevereiro de 2021 | [Introdução ao canal múltiplo e ao canal cruzado](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/introduction-to-cross-and-multi-channel-campaigns.html) | Campaign Classic | Entenda a diferença entre a campanha de múltiplos canais e canais cruzados e os casos de uso das campanhas de vários canais e canais cruzados. |
| 1 de fevereiro de 2021 | [Criar um Delivery SMS](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/sms-channel/create-a-sms-delivery.html) | Campaign Classic | Saiba como criar um delivery SMS. |
| 1 de fevereiro de 2021 | [Criar campanhas entre canais](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/cross-channel-campaigns.html) | Campaign Classic | Saiba como criar e executar uma campanha entre canais. |
| 29 de janeiro de 2021 | [Usar Grupos de controle](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/use-control-groups.html) | Campaign Classic | Entenda o conceito de grupos de controle e aprenda a usar um grupo de controle para o seu delivery. |
| 28 de janeiro de 2021 | [Enviar e validar provas](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/send-and-validate-proofs.html) | Campaign Classic | Saiba como enviar e validar uma prova. |
| 28 de janeiro de 2021 | [Projetar emails para entrega](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/design-emails-for-deliverability.html) | Campaign Classic | Saiba como aplicar as práticas recomendadas de entrega. |
| 28 de janeiro de 2021 | [Criar e projetar delivery de e-mail](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/create-and-design-email-deliveries.html) | Campaign Classic | Entenda o processo de criação de um delivery de email e saiba como projetar e personalizar o conteúdo de email. |
| 27 de janeiro de 2021 | [Criar campanhas acionadas por eventos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/getting-started/create-event-triggered-campaigns.html) | Campaign Classic | Saiba como criar uma campanha acionada pelo evento e entender seus usos. |

### Recursos de ajuda

* Adobe Campaign Standard: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/campaign-standard-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/overview.html) - [Planejamento de lançamento](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/release-notes/release-planning.html) - [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ajuda](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/campaign-classic-home.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/pt-BR/campaign-classic-learn/tutorials/overview.html)- [Atualizações mais recentes da documentação](https://docs.adobe.com/content/help/pt-BR/campaign-classic/using/documentation-updates.html)
* Painel de controle do Adobe Campaign: [Documentação](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.html) - [Notas de versão](https://docs.adobe.com/content/help/pt-BR/control-panel/using/release-notes.html) - Vídeos explicativos do [Campaign Standard](https://docs.adobe.com/content/help/pt-BR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/pt-BR/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notas de versão da Adobe Advertising Cloud.

* [Novos recursos na Advertising Cloud DSP](#adcloud-dsp)
* [Novos recursos na Advertising Cloud Search](#adcloud-search)

### Novos recursos no [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última atualização: **28 de outubro de 2020**

| Recurso | Descrição |
| -----------| ---------- |
| Novo Ajuda | (Versão de 28 de outubro) A ajuda herdada foi substituída por páginas atualizadas, que estão disponíveis no link Ajuda no menu principal do DSP e também estão sempre disponíveis em [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=pt-BR](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=pt-BR) |
| Campanhas | (Versão de 28 de outubro) As visualizações anteriores do Campaigns Beta agora são as visualizações padrão do Campaigns, para obter insights mais rápidos, fluxos de trabalho simplificados e visualizações personalizadas. |
| Inventário privado | (Versão de 15 de outubro) Todos os usuários agora podem configurar e editar informações da ID de negócios usando um novo formulário, que é uma versão simplificada do formulário antigo de [!UICONTROL Veiculação de anúncios inteligentes]. Para configurar as informações da nova ID de negócios, acesse **[!UICONTROL Inventário > Vendas]**, clique em **[!UICONTROL Criar]** e, em seguida, clique em **[!UICONTROL ID de acordo beta]**. |
| Previsão de posicionamento | (Versão de 15 de outubro) Para inserções com ritmo de nível de inserção, a seção [!UICONTROL Previsão] das configurações de inserção inclui uma nova seção [!UICONTROL Máximos estimados], que indica quanta capacidade está disponível com a configuração de direcionamento atual. |

### Novos recursos no [!DNL Advertising Cloud Search] {#adcloud-search}

Última atualização: **22 de janeiro de 2021, para lançamento em 23 de janeiro**

| Recurso | Descrição |
| -----------| ---------- |
| [!UICONTROL Campanhas de pesquisa]<br> Relatórios | A Advertising Cloud Search não relata mais novos dados de posição média para campanhas do Microsoft Advertising. A coluna Posição média mostra valores de zero (0) para datas a partir de 23 de janeiro. Esse processo é uma preparação para a descontinuação dos dados de posição média da Microsoft em janeiro de 2021.<br>Os dados de posição média coletados até 22 de janeiro ainda estão disponíveis nos relatórios. |

### Tutoriais e cursos da Ad Cloud

Atualizado: **2 de dezembro de 2020**

## ![Ícone](/assets/magento.png) [!DNL Magento] {#magento}

Consulte Magento Commerce e Notas de versão [de código aberto](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) para obter as informações mais recentes.

## ![Ícone](/assets/target.png)[!DNL Target] {#target}

Consulte as [[!DNL Target] notas de versão](https://docs.adobe.com/content/help/pt-BR/target/using/release-notes/target-release-notes.html) para obter as informações mais recentes.

## ![Ícone](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e profissionais de marketing B2B que buscam transformar as experiências dos clientes ao se envolverem em todos os estágios de jornadas complexas de compra.

### Atualizações do Core Marketo Engage

Consulte as [!DNL Marketo Engage] [notas de versão](https://docs.marketo.com/display/public/DOCS/Release+Notes) para obter as informações mais recentes.

### Recursos futuros

Os seguintes recursos serão lançados ao longo do trimestre:

| Recurso | Descrição |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nova segmentação baseada em conta</li><li>Salvar filtros específicos do painel</li><li>Exportar painéis Bizible como PDFs</li></ul> |
| Conexão de vendas | Compor atualizações/aprimoramentos da Janela e do Centro de comando |

### Desativações

* **Parâmetro &quot;_method&quot; da API de ativos:** a partir de setembro de 2020, os access points da API de ativos não aceitarão mais `_method` passar parâmetros de consulta em um corpo do POST para ignorar as limitações de comprimento do URI.
* **Desativação do suporte ao Internet Explorer:** a partir do lançamento realizado em 31 de julho de 2020, a interface do usuário do Marketo Engage não será mais compatível com o Internet Explorer.

## ![Ícone](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Novos vídeos, tutoriais ou cursos publicados na Adobe Document Cloud.

### Tutoriais do Acrobat

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 8 de fevereiro de 2021 | [Visão geral da Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html) | Hub de aprendizagem | Bem-vindo ao Adobe Acrobat Learning Hub. Você encontrará uma ampla variedade de experiências de aprendizado focadas no Adobe Acrobat. Nossos tutoriais, webinars e casos de uso foram projetados para fornecer rapidamente aos usuários iniciantes e avançados o máximo de velocidade no Adobe Acrobat. |

### Tutoriais do Adobe Sign

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 8 de fevereiro de 2021 | [Página inicial da visão geral - Ativo de suporte](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html) | Hub de aprendizagem | Bem-vindo ao Adobe Sign Learning Hub. Você encontrará uma grande variedade de experiências de aprendizado focadas no Adobe Sign. Nossos tutoriais, webinars e casos de uso foram projetados para agilizar os iniciantes e administradores no Adobe Sign. |

Para obter ajuda sobre a Document Cloud, consulte:

* [Hub de aprendizagem do Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Hub de aprendizagem do Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem e suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IconCreative Cloud Enterprise  {#creative-cloud}

Novos tutoriais para o Creative Cloud Enterprise.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 3 de fevereiro de 2021 | [Criação de parágrafos gráficos com o Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/cinemagraphps.html?lang=en#cceoverview) | Vídeo | Saiba como criar uma fotografia ao vivo combinando vídeos do Adobe Stock com técnicas inteligentes de mascaramento no Photoshop. |
| 3 de fevereiro de 2021 | [Crie compostos exclusivos com Adobe Stock e Photoshop para iPad](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/compositepsipad.html?lang=en) | Vídeo | Aprenda a usar um de seus aplicativos de Creative Cloud favoritos de uma forma totalmente nova, com uma interface reformulada baseada em toque. |
| 3 de fevereiro de 2021 | [Personalize e marque um modelo 3D com Dimension e Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/3ddimensionstock.html?lang=en) | Vídeo | Personalize e marque um modelo 3D no Dimension usando materiais, propriedades ambientais, iluminação e fotografia, para criar imagens fotorealistas para qualquer projeto de design. |
| 2 de fevereiro de 2021 | [Fique à vontade com os componentes no Adobe XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/xdoverview/components.html) | Vídeo | Saiba como usar os Componentes para oferecer flexibilidade sem precedentes para aplicar velocidade e consistência ao fluxo de trabalho de design. |
| 2 de fevereiro de 2021 | [Dicas e técnicas para dominar a iluminação 3D na CGI](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/mastering3dlighting.html?lang=en) | Artigo | Saiba mais sobre iluminação 3D e como criar diferentes condições de luz que podem alterar completamente uma cena gerada pelo computador e a forma como os objetos aparecem nela. |
| 2 de fevereiro de 2021 | [Criação de fotografias virtuais fotorrealistas com renderização e composição 3D](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/photorealistic.html?lang=en#3doverview) | Artigo | Saiba como criar fotografias virtuais fotorealistas com renderização e composição 3D. |
| 29 de janeiro de 2021 | [Guias de referência rápida do CCE](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/overview-ref.html) | Guias de referência rápida | Obtenha acesso a guias de referência rápidos que ajudam você a aprender novos recursos no Creative Cloud. |
