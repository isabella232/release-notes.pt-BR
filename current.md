---
title: Notas de versão mais recentes
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação para  [!DNL Experience Cloud] produtos e serviços. Encontre nova ajuda e tutoriais sobre [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: e3a7e1b80d25a3b9625ca0ee31a07bae674eda6f
workflow-type: tm+mt
source-wordcount: '5278'
ht-degree: 39%

---

# Notas de versão da Adobe Experience Cloud - Outubro de 2021

![Banner](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud]Os aplicativos e os serviços da são atualizados mensalmente. Esta página é o local central para encontrar as atualizações, a documentação e os tutoriais mais recentes para a [!DNL Experience Cloud] e a [!DNL Experience Platform]. Você também pode encontrar nova documentação para a [!DNL Creative Cloud for enterprise] e a [!DNL Document Cloud].

>[!NOTE]
>
>Assine a [Atualização mensal do produto de prioridade da Adobe](https://www.adobe.com/subscription/priority-product-update.html) para receber notificações por email sobre atualizações nesta página. Esta página é mantida durante todo o mês. Portanto, verifique regularmente se há atualizações de produtos empresariais da Adobe e da documentação da Experience League.

Última atualização: **4 de outubro de 2021**

* [[!DNL Experience League] Eventos ao vivo](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; Administração](#ecloud)
* [Status do [!UICONTROL Sistema da Adobe]](#status)
* [[!DNL Adobe Analytics]](#analytics) e do [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insight da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/experience-league.png) [!DNL Experience League] Eventos ao vivo {#events}

[!DNL Experience League] Eventos ao vivo são discussões com especialistas da Adobe e convidados especiais que são fundamentais para trazer a tecnologia da Adobe até você. Veja a programação a seguir e junte-se a nós ao vivo ou assista aos eventos previamente gravados.

| Data do evento | Nome do evento | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| 21 de outubro de 2021 | TBD | Evento de vídeo ao vivo | Detalhes em breve. |
| 23 de setembro de 2021 | [Dicas de especialistas para fazer suas campanhas de fim de ano se destacarem](https://www.youtube.com/watch?v=bsU1lAv0xes) | Evento de vídeo ao vivo | Assim como nunca é cedo demais para começar as compras de Natal, nunca é cedo demais para começar a planejar uma campanha de marketing de fim de ano de grande sucesso. Com o Adobe Campaign, você pode projetar, planejar e executar campanhas que realizam todos os desejos de fim de ano da sua empresa.<br>Mas você sabe todas as dicas para executar campanhas que terminam o ano com um estrondo? Junte-se a Sandra para uma discussão ao vivo com três especialistas em Adobe que possuem especialistas em experiência coletiva em fazer exatamente isso. |
| 26 de agosto de 2021 | [Torne seu próximo segmento de público-alvo mais inteligente do que nunca](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=pt-BR) | Gravação de evento | O sucesso de toda boa campanha de marketing depende precisamente do direcionamento ao público-alvo. Com o novo [!UICONTROL Construtor de segmentos] da Adobe Experience Platform, você pode construir seu próximo segmento de público-alvo usando dados de perfil e comportamento do usuário com base no tempo em todos os canais. Não há melhor maneira de garantir que suas mensagens cheguem às pessoas que mais precisam ouvi-las. |
| 29 de julho de 2021 | [Minhas três dicas de implementação favoritas do Adobe Analytics](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=br-BR) | Gravação de evento | Você o viu no palco na Summit. Você o ouviu compartilhar conselhos de especialistas no Adobe Insider Tours. Você pode até ter tido a vantagem de trabalhar com ele em sua própria implementação do Adobe Analytics. Agora, Eric Matisoff está trazendo suas três dicas favoritas de implementação do Adobe Analytics para esta discussão exclusiva do Experience League Live. |

{style=&quot;table-layout:auto&quot;}

Para ver mais vídeos, acesse o [Canal da Adobe Experience League](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) no YouTube.

## ![Ícone](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] e administração {#ecloud}

| Recurso | Descrição |
| ------- | ------- |
| Pesquisa unificada | A Pesquisa Unificada continua a adicionar tipos de objetos ao índice de pesquisa. Nesta atualização, a pesquisa global agora pesquisa por todo o conteúdo de Experience League e os seguintes tipos de objetos Journey Optimizer: <ul><li>Conjuntos de dados</li><li>Destinos</li><li>Consultas</li><li>Esquemas</li><li>Segmentos</li><li>Fontes</li><li>Ofertas</li><li>Componentes</li><li>Mensagens</li><li>Jornadas</li></ul> |
| Consentimento em dados de uso do produto | Após um logon inicial, você é solicitado a enviar preferências sobre como o Adobe pode fornecer conteúdo útil e personalizado, como tutoriais, guias, dicas rápidas, recomendações, vídeos de aprendizagem e muito mais, com base nos dados de uso do produto do Experience Cloud. Essa solicitação também inclui uma atualização das suas preferências para a coleta e uso desses dados em <https://experience.adobe.com/preferences>. |
| Navegação de Experience Cloud [!UICONTROL Triggers] | [Os ](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) Acionadores de Experience Cloud estão disponíveis para navegação direta do alternador de aplicativos no cabeçalho para usuários provisionados. |
| **Aviso:** Atualização da navegação na interface planejada | Em novembro de 2021, o recurso de navegação _[!UICONTROL Ir para o Launch / Data Collection]_ será removido de <https://experience.adobe.com/implement>. |

{style=&quot;table-layout:auto&quot;}

**Mais recursos de ajuda sobre o [!DNL Experience Cloud Central UI Components] e administração**

* Ajuda administrativa para [Componentes da interface central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=pt-BR) e gerenciamento de usuários
* Ajuda e notas de versão para [Places — serviço de localização](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=pt-BR)
* Ajuda sobre [Pessoas — Atributos do cliente e Biblioteca de público-alvo](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Ícone](/assets/adobe.png) [!DNL Adobe System Status] {#status}

O [!DNL Adobe System Status] fornece informações detalhadas, atualizações de status e notificações por email sobre eventos de interrupção e manutenção de produtos e serviços da Adobe. Confira em [status.adobe.com](https://status.adobe.com/).

(Encontre as informações da versão mais recente do [!DNL Adobe System Status] nas notas de versão de [21 de maio de 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=pt-BR).)

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **7 de outubro de 2021**

* [Novos recursos no Adobe Analytics](#aa-features)
* [Novos recursos no Customer Journey Analytics](#cust-journey)
* [Correções no Adobe Analytics](#aa-fixes)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [Cursos e tutoriais do Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | Descrição | [Disponibilidade geral](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=pt-BR) — Data do Target |
| ----------- | ---------- | ------- |
| Visualizações para painéis do Analytics | O Analytics [!UICONTROL Dashboards] está apresentando três novas visualizações para fornecer aos executivos e tomadores de decisão uma melhor compreensão imediata de seus dados. Os novos gráficos de barra [!UICONTROL Rosca], [!UICONTROL Linha] e [!UICONTROL Horizontal] facilitam a visualização dos dados de itens de dimensão individuais, sem precisar abrir uma visualização de detalhes. (Link da documentação a seguir) | 7 de outubro de 2021 |
| [!UICONTROL Tempo gasto com a reprodução da mídia] | A reprodução de mídia de transmissão Adobe [!UICONTROL Tempo gasto] fornece informações valiosas sobre o envolvimento do visualizador e permite que as organizações de mídia obtenham insights mais profundos e granulares com o envolvimento minuto a minuto do usuário por meio da análise de tempo gasto avançada com recursos de divisão de dia. Você pode observar o tempo gasto visualizando seus fluxos de mídia em um ponto específico do tempo. Você pode dividir a duração da reprodução por diferentes granularidades, incluindo novas granularidades de 5 minutos, 15 minutos e 30 minutos. [Saiba mais](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 18 de outubro de 2021 |
| Quick [!UICONTROL Construtor de segmentos] | Permite que usuários empresariais apliquem rapidamente segmentos básicos em um fluxo de trabalho simplificado e integrado do projeto. Não é necessário acessar o [!UICONTROL Construtor de segmentos]. [Saiba mais](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 21 de outubro de 2021 |
| Melhorias na pesquisa no painel esquerdo do Analysis Workspace | A pesquisa no painel esquerdo será 1) priorizar correspondências exatas acima de correspondências amplas, além de continuar levando em conta a recenticidade e relevância do componente. 2) Destaca caracteres correspondentes para tornar os resultados da pesquisa mais compreensíveis. 3) É mais fácil encontrar classificações relacionadas a uma dimensão. 4) Por fim, ele suporta curinga (`*`) procurando para encontrar mais facilmente componentes específicos de que você precisa. Observação: A pesquisa por curinga ainda não funciona no nível do item de dimensão. | 21 de outubro de 2021 |
| Tema Escuro do Analysis Workspace | O tema escuro está disponível como uma opção de exibição. | 21 de outubro de 2021 |

{style=&quot;table-layout:auto&quot;}

### Novos recursos no Customer Journey Analytics {#cust-journey}

| Recurso | Descrição | [Disponibilidade geral](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) — Data do Target |
| ----------- | ---------- | ----- |
| Suporte a Report Builder | O Report Builder é um Suplemento Microsoft® [!DNL Excel] que permite criar, editar e atualizar facilmente relatórios personalizados usando dados de Customer Journey Analytics. Com o Report Builder e o Excel, você pode usar a interface do usuário de arrastar e soltar simples, mas flexível, para criar facilmente solicitações de dados complexas. Com o Report Builder for Customer Journey Analytics, você pode:<ul><li>Faça referência às células da planilha existentes para obter a ordem perfeita das linhas, o intervalo de datas ou o filtro</li><li>Criar datas personalizadas usando calendário, referências de célula ou correspondência de datas</li><li>Projete tabelas e visualizações com ferramentas de formatação familiares do Excel</li><li>Disponível em macOS, Microsoft 365 para Web e Microsoft Windows</li></ul> | 7 de outubro de 2021 |
| Visualizações para painéis do Analytics | O Analytics [!UICONTROL Dashboards] está apresentando três novas visualizações para fornecer aos executivos e aos tomadores de decisão uma melhor compreensão instantânea de seus dados. Os novos gráficos de rosca, linha e barra horizontal facilitam a visualização de dados de itens de dimensão individuais sem precisar abrir uma visualização de detalhes. (Link da documentação a seguir) | 7 de outubro de 2021 |
| Logs de auditoria do Customer Journey Analytics (somente API) | Os logs de auditoria são uma parte importante da conformidade com a segurança e para a auditoria de dados e ações do usuário. | 7 de outubro de 2021 |
| Quick [!UICONTROL Filter Builder] | Permite que usuários empresariais apliquem rapidamente segmentos básicos em um fluxo de trabalho simplificado e integrado do projeto. Não é necessário acessar o [!UICONTROL Construtor de filtros]. [Saiba mais](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 21 de outubro de 2021 |
| Melhorias na pesquisa no painel esquerdo do Analysis Workspace | A pesquisa no painel esquerdo será 1) priorizar correspondências exatas acima de correspondências amplas, além de continuar levando em conta a recenticidade e relevância do componente. 2) Destaca caracteres correspondentes para tornar os resultados da pesquisa mais compreensíveis. 3) É mais fácil encontrar classificações relacionadas a uma dimensão. 4) Por fim, ele suporta curinga (`*`) procurando para encontrar mais facilmente componentes específicos de que você precisa. Observação: A pesquisa por curinga ainda não funciona no nível do item de dimensão. | 21 de outubro de 2021 |
| Tema Escuro do Analysis Workspace | O tema escuro está disponível como uma opção de exibição. | 21 de outubro de 2021 |

{style=&quot;table-layout:auto&quot;}

### Correções no Adobe Analytics e no CJA {#aa-fixes}

* Correção de um erro de relatório agendado no Customer Journey Analytics. (AN-271721)
* Correção de problemas com [!UICONTROL Pesquisar componentes] no [!UICONTROL Workspace] que não resultavam em correspondências exatas. (AN-253937; AN-271707)

#### Outras correções no Adobe Analytics

AN-256136; AN-265420; AN-268455; AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| ----------- | ---------- | ---------- |
| Fim da vida útil de três serviços de API do Analytics | 16 de setembro de 2021 | Em **28 de outubro de 2021**, os seguintes serviços de API do Analytics Legacy chegarão à data de término da vida útil e serão encerrados. Quaisquer integrações atuais criadas com esses serviços deixarão de funcionar nesse dia.<ul><li>APIs do Analytics 1.3</li><li>APIs do SOAP Analytics 1.4</li><li>Autenticação OAuth herdada (OAuth e JWT)</li></ul>A Adobe forneceu uma seção de [Perguntas frequentes sobre EOL da API herdada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ajudar a responder às suas perguntas e fornecer orientações sobre como proceder. As integrações de API que empregam esses serviços podem migrar para as [APIs REST do Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou as [APIs do Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). As contas OAuth herdadas podem migrar para uma conta de integração do Analytics [Adobe I/O](https://developer.adobe.com/console), que pode ser usada para acessar as APIs do Analytics 1.4 e as APIs do Analytics 2.0. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Para obter as atualizações mais recentes sobre as versões do AppMeasurement (versão 2.22.2), consulte as [notas de versão do AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=pt-BR).

### Cursos e tutoriais do Analytics {#tutorials-analytics}

Cursos, tutoriais e artigos mais recentes em [!DNL Analytics] e [!UICONTROL Customer Journey Analytics].

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Outubro de 2021 | [Uso de visualizações para contar suas histórias de dados](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | Curso | Quem deseja varrer tabela após tabela apenas para tentar extrair insights dos dados? Você não! Neste curso, aprenda as noções básicas sobre visualizações, incluindo como adicioná-las a um projeto, inserir dados neles e o que cada visualização pode mostrar a você. Saiba como definir as configurações para obter os dados exatos necessários. Além disso, obtenha algumas dicas e casos de uso para ajudá-lo a tornar as visualizações práticas na análise regular. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ajuda do Analytics

* [Documentação e tutoriais do produto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR)

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Novos recursos no Audience Manager - atualizado em **14 de setembro de 2021**:

| Recurso | Descrição |
| ------- | ------- |
| Consentimento para coleta de dados de ID de dispositivos móveis | Adição de suporte para consentimento de coleta de dados de ID de dispositivos móveis. Para se beneficiarem desta atualização, os clientes devem atualizar para o [SDK móvel da AEP iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) ou posterior. |

## ![Ícone](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Inclui informações de atualização da versão e nova documentação do Experience Platform e [!UICONTROL Mobile SDK].

**29 de setembro de 2021**

| Recurso | Descrição |
| ------- | ------- |
| [[!UICONTROL Zona de aterrissagem de dados]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL As ] zonas de aterrissagem de dados são uma  [!DNL Platform]loja  [!UICONTROL Azure Blob provisionada ] que permite que um armazenamento seguro e temporário por sandbox traga arquivos para o Experience Platform. |
| Suporte a fontes de fluxo para [preparação de dados](https://www.adobe.com/go/monitor-streaming-dataflows-en) | As fontes de transmissão agora oferecem suporte à preparação de dados, permitindo fornecer um esquema de origem JSON para mapear dados de origem não compatíveis com XDM para um esquema XDM de destino. |
| [Credenciais que não estão expirando](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | As Credenciais que não estão expirando para usuários do [!UICONTROL Serviço de query] permitem conexões mais permanentes a clientes externos, em vez de renovar credenciais a cada 24 horas. |
| [[!UICONTROL SDK de destino]](https://www.adobe.com/go/destination-sdk-overview-en) | Use [!UICONTROL SDK de destino] para integrar com [!DNL Platform] e contribuir para o catálogo de destinos em crescimento constante. O acesso a esse recurso está disponível somente para clientes do Experience Platform Ativation. |

Consulte as [notas de versão da Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR) para ver todos os detalhes.

### Tutoriais e cursos da Experience Platform {#tutorials-platform}

Vídeos, tutoriais ou cursos mais recentes publicados para o Experience Platform e serviços.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Outubro de 2021 | [[!DNL Platform] Administração](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | Curso | Saiba mais sobre as atividades de administração do Experience Platform, incluindo permissão e gerenciamento de sandbox. |

{style=&quot;table-layout:auto&quot;}

### SDK do Adobe Mobile

Consulte [Notas de versão e logs de alteração](https://aep-sdks.gitbook.io/docs/release-notes) dos SDKs móveis da Adobe Experience Platform.

## ![Ícone](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Saiba mais sobre os recursos, melhorias e correções mais recentes nas [Notas de versão do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=pt-BR).

### Tutoriais e cursos do Journey Optimizer {#tutorials-ajo}

Tutoriais mais recentes do Journey Optimizer:

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Outubro de 2021 | [Configurar e gerenciar dados  [!DNL Journey Optimizer] em engenheiros de dados](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | Curso | Saiba como configurar e gerenciar dados necessários para o gerenciamento de jornadas no Journey Optimizer. |
| Outubro de 2021 | [Introdução  [!DNL Journey Optimizer] ao para administradores e gerentes do Jornada](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | Curso | Saiba tudo o que você precisa saber para criar sua primeira jornada. |
| Outubro de 2021 | [ [!DNL Journey Optimizer] Configurar para administradores do Jornada](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | Curso | Entenda a arquitetura [!DNL Journey Optimizer] e os pontos de integração. Saiba como configurar o [!DNL Journey Optimizer]. |

{style=&quot;table-layout:auto&quot;}

### Mais recursos para [!DNL Journey Optimizer]

[Centro de ajuda](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Use o Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Versões mais recentes do produto [!DNL Journey Orchestration]

Saiba mais sobre os recursos, melhorias e correções mais recentes nas [[!DNL Journey Orchestration] Notas de versão do ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=pt-BR).

#### Mais recursos para [!DNL Journey Orchestration]

[Centro de ajuda](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL O Offer ] Decisioning é um serviço integrado à Adobe Experience Platform. Use o [!UICONTROL Offer Decisioning] para fornecer a melhor oferta e experiência aos seus clientes em todos os pontos de contato na hora certa.

### Últimas versões de produtos Offer Decisioning

Saiba mais sobre os recursos, as melhorias e as correções mais recentes nas [Notas de versão do Offer Decisioning](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

#### Mais recursos do [!UICONTROL Offer Decisioning]

[Centro de ajuda](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Ícone](/assets/aem.png) Experience Manager {#aem}

A Adobe recomenda visitar a página de [Atualizações e roteiros de versão do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para se manter atualizado sobre as informações de lançamento.

### Comunidade

* [Desenvolvedores Adobe Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)  | 4-5 de outubro de 2021, 7:00 PDT

   O Adobe Developers Live reúne desenvolvedores de Adobe e construtores de experiências com diversos planos de fundo e um propósito singular - para criar experiências completas e incríveis. Esta conferência de dois dias apresenta importantes atualizações para desenvolvedores, sessões técnicas e oportunidades de rede da comunidade.

   As equipes de produtos de Adobe no Adobe Experience Cloud, Document Cloud e Creative Cloud mostram os últimos avanços tecnológicos e ferramentas de desenvolvedor que acionam o design, os fluxos de trabalho de criação de conteúdo, os serviços de documento e o gerenciamento da experiência do cliente em todos os setores.

   O Adobe tem 20 sessões de Experience Manager planejadas. Espalhe a palavra!

   * [Lista completa de sessões](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [Registro livre - Faça logon no RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Comunidade Live de Desenvolvedores do Adobe](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### Novos cursos e tutoriais do Experience Manager {#tutorials-aem}

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Outubro de 2021 | [Introdução à documentação XML](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | Curso | Saiba como criar, organizar, criar e publicar conteúdo com a Documentação XML para Adobe Experience Manager. |
| Outubro de 2021 | [Gerenciamento de fluxos de trabalho criativos  [!DNL Workfront] usando o e o Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | Curso | Saiba como Adobe [!DNL Workfront] e Experience Manager. |
| Outubro de 2021 | [Introdução ao AEM Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | Curso | Saiba como o AEM Assets Essentials pode simplificar o gerenciamento de ativos para sua organização. |
| Outubro de 2021 | [[!UICONTROL Ferramenta de transferência de conteúdo]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | Vídeo | Saiba como a [!UICONTROL Ferramenta de transferência de conteúdo] ajuda a migrar o conteúdo para o AEM como um Cloud Service do AEM 6.3+. |
| Outubro de 2021 | [[!UICONTROL Serviço de importação em massa]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | Vídeo | Saiba como o AEM como [!UICONTROL Bulk Import Service] do Cloud Services pode ser usado para importar ativos de fontes não AEM. |
| Outubro de 2021 | [Comunicações (Serviço de Saída)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | Vídeo | Saiba como o AEM Forms as a Cloud Service suporta o caso de uso de comunicação. |
| Outubro de 2021 | [Inscrição digital](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | Vídeo | Saiba mais sobre como o AEM Forms as a Cloud Service suporta o caso de uso de Inscrição digital. |
| Outubro de 2021 | [Uso das ferramentas  [!UICONTROL do Cloud Acceleration ] Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | Vídeo | Uma apresentação narrada do uso das ferramentas do [!UICONTROL Cloud Acceleration Manager]. |
| Outubro de 2021 | [Navegação pelo  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | Vídeo | Explore a experiência de navegação do [!UICONTROL Cloud Acceleration Manager] para o Experience Manager como Cloud Service. |
| Outubro de 2021 | [Ferramenta Migração de fluxo de trabalho de ativos](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | Vídeo | Saiba como a ferramenta [!UICONTROL Migração de fluxo de trabalho de ativos] ajuda a migrar seus fluxos de trabalho existentes do AEM Assets para o AEM como Cloud Service. |
| Outubro de 2021 | [[!UICONTROL Conversor de índice]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | Vídeo | Saiba como o [!UICONTROL Index Converter] converte automaticamente as definições de índice de AEM existentes para serem AEM como Cloud Service compatível. |
| Outubro de 2021 | [[!UICONTROL Conversor do Dispatcher Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | Vídeo | Saiba como o [!UICONTROL Dispatcher Converter] atualiza automaticamente as configurações existentes AEM Dispatcher para serem AEM como Cloud Service compatível. |
| Outubro de 2021 | [[!UICONTROL Modernizador do Repositório de Código]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | Vídeo | Saiba como o [!UICONTROL Core Repository Modernizer] atualiza automaticamente os projetos AEM Maven existentes para serem AEM como Cloud Service compatível. |
| Outubro de 2021 | [[!UICONTROL Ferramentas de refatoração de código]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | Vídeo | Saiba como as [!UICONTROL Ferramentas de refatoração de código] do AEM ajudam a automatizar a conversão de projetos de AEM existentes para serem AEM como um Cloud Service compatível. |
| Outubro de 2021 | [[!UICONTROL Ferramenta de transferência de conteúdo]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | Vídeo | Saiba como a [!UICONTROL Content Transfer Tool] permite mover com eficiência o conteúdo de AEM 6.5 para AEM como Cloud Service. |
| Outubro de 2021 | [As fases de implementação do  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | Vídeo | Analise e entenda as principais fases de implementação ou mude para AEM como um Cloud Service usando o [!UICONTROL Cloud Acceleration Manager]. |
| Outubro de 2021 | [Analisador de disponibilidade e  [!UICONTROL práticas recomendadas]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | Vídeo | Saiba como o [!UICONTROL Analisador de práticas recomendadas] pode ajudá-lo a migrar do AEM no local ou do Adobe Managed Services para o Experience Manager as a Cloud Service. |
| Outubro de 2021 | [Introdução ao Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | Vídeo | Saiba como o [!UICONTROL Cloud Acceleration Manager] pode ajudá-lo a migrar rápida e facilmente para o Experience Manager como Cloud Service. |
| Outubro de 2021 | [AEM Forms as a Cloud Service - Migração para AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | Vídeo | Saiba mais sobre casos de uso e recursos compatíveis com o AEM Forms as a Cloud Service. |
| Outubro de 2021 | [Solução de problemas de AEM como Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | Vídeo | Saiba como solucionar problemas e depurar o SDK do AEM, AEM como Cloud Service e o processo de criação e implantação. |
| Outubro de 2021 | [AEM  [!UICONTROL Microsserviços de ativos]  - Migração para o AEM como Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | Vídeo | Saiba como os microsserviços de asset compute do AEM Assets as a Cloud Service permitem gerar de forma automática e eficiente qualquer representação dos ativos, substituindo essa função do fluxo de trabalho AEM tradicional. |
| Outubro de 2021 | [Pesquisa e indexação](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | Vídeo | Saiba mais sobre o AEM como índices de pesquisa do Cloud Service, como converter AEM 6 definições de índice para serem AEM como compatíveis com o Cloud Service e como implantar índices para AEM como Cloud Service. |
| Outubro de 2021 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | Vídeo | Saiba mais sobre AEM [!UICONTROL Dispatcher] para AEM como Cloud Service, com foco em alterações notáveis de [!UICONTROL Dispatcher] para AEM 6, a ferramenta de conversão [!UICONTROL Dispatcher] e como usar o SDK de ferramentas do Dispatcher. |
| Outubro de 2021 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | Vídeo | Saiba mais sobre o Cloud Manager para AEM as a Cloud Service e suas diferenças com o Cloud Manager para AEM no Adobe Manage Services (AMS). |
| Outubro de 2021 | [Integração com o AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | Vídeo | Saiba mais sobre a integração ao AEM como um Cloud Service, começando da fase de contrato até a configuração dos ambientes usando o [!UICONTROL Cloud Manager]. |
| Outubro de 2021 | [Modernização do Repositório](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | Vídeo | Saiba mais sobre a modernização do repositório, conteúdo mutável e imutável, estrutura de pacotes e a ferramenta CLI do modernizador de repositório. |
| Outubro de 2021 | [[!UICONTROL Ferramentas de Modernização do AEM]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | Vídeo | Saiba como AEM [!UICONTROL Ferramentas de Modernização] são usadas para atualizar um projeto de AEM existente e o conteúdo para ser AEM como um Cloud Service compatível. |
| Outubro de 2021 | [Ferramentas de Modernização do AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | Vídeo | Saiba como pensar de forma diferente sobre AEM como implementações de Cloud Service. |
| Outubro de 2021 | [Analisador de práticas recomendadas e Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | Vídeo | Saiba como o Best Practice Analyzer (BPA) e o Cloud Acceleration Manager (CAM) fornecem um guia personalizado para migrar para o AEM as a Cloud Service. |
| Outubro de 2021 | [Manter histórico de versão](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | Vídeo | Saiba como o Adobe Workfront e o Experience Manager [!UICONTROL Assets Essentials] ajudam a manter versões de [!DNL Workfront] documentos e ativos do Assets Essentials. |
| Outubro de 2021 | [Envio de documentos e vinculação de ativos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | Vídeo | Saiba como enviar documentos do Workfront para o Assets Essentials e vincular ativos do Assets Essentials ao Workfront. |
| Outubro de 2021 | [Configuração da integração](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | Vídeo | Saiba como configurar a integração do Adobe Workfront e do Assets Essentials. |
| Outubro de 2021 | [O que é uma assinatura digital](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Vídeo | Saiba mais sobre assinaturas digitais baseadas em certificados, que cumprem as mais rigorosas normas legais em todo o mundo e fornecem o mais alto nível de garantia da identidade de um assinante. |
| Outubro de 2021 | [Construtor de segmentos no Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | Vídeo | Divida seus dados com a segmentação no Adobe Analytics. Este vídeo o orienta pelo [!UICONTROL Construtor de segmentos] e fornece uma visão geral básica. |
| Outubro de 2021 | [Mapeamento de metadados](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | Vídeo | Saiba como configurar o mapeamento de metadados entre campos do Workfront e propriedades do Assets Essentials e configurar o Assets Essentials para exibir os valores mapeados. |

{style=&quot;table-layout:auto&quot;}

### Informações sobre a versão do Experience Manager {#aem-links}

As notas de versão e outros links para informações de lançamento do Experience Manager estão aqui:

* [[!DNL Experience Manager as a Cloud Service]  notas de versão](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=pt-BR)
* [[!DNL Experience Manager as a Cloud Service] informações da versão](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=pt-BR)
* [[!DNL Experience Manager Cloud Manager]  notas de versão](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=pt-BR)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=pt-BR)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=pt-BR)
* [Notas de versão do Cumulative Fix Pack do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=pt-BR)
* [[!DNL Experience Manager Assets Dynamic Media]  notas de versão](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=pt-BR)
* [[!DNL Experience Manager Brand Portal]  notas de versão](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=pt-BR)
* [Notas de versão do aplicativo para desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=pt-BR)
* [[!DNL Experience Manager Dispatcher]  notas de versão](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=pt-BR)
* [Notas de versão do Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=pt-BR)
* [Notas de versão do Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=pt-BR)

### Outros recursos de ajuda do Experience Manager

* [[!DNL Experience Manager as a Cloud Service] Guias](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR#previous-updates)
* [Versões anteriores da documentação do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager]  Guia do usuário](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=pt-BR)
* [[!DNL Dynamic Media Classic] Página inicial da ajuda](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=pt-BR)
* [Documentação do Experience Manager: atualizações recentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=pt-BR#aem-as-a-cloud-service)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produto do Campaign

Saiba mais sobre recursos, melhorias e correções mais recentes lançados:

* [Notas de versão do Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=pt-BR)
* [Notas de versão do Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=pt-BR)
* [Notas de versão do Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=pt-BR)

### [!UICONTROL Campaign]: novos cursos e tutoriais {#tutorials-campaign}

Tutoriais e cursos mais recentes do Adobe Campaign.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Outubro de 2021 | [Criar campanhas avançadas com o Adobe Campaign V8 para usuários empresariais](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | Curso | Saiba como configurar e executar campanhas de marketing avançadas usando o Adobe Campaign V8. Saiba mais sobre os pré-requisitos, crie e configure campanhas avançadas, deliveries e gerencie assinaturas. |
| Outubro de 2021 | [Usar APIs SOAP em fluxos de trabalho - Introdução](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | Tutorial | Saiba como usar as APIs do Adobe Campaign Soap e criar um workflow de delivery avançado com base nos dados recebidos por meio da API. |
| Outubro de 2021 | [Criar eventos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | Tutorial | Saiba como configurar um evento, especificar o endpoint de transmissão e a carga útil de um evento. |
| Outubro de 2021 | [Configurar fontes de dados](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | Tutorial | Entenda o que é uma fonte de dados e saiba como configurar o Experience Platform e fontes de dados externas. |
| Outubro de 2021 | [Caso de uso - mensagens de explosão](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | Tutorial | Entenda os casos de uso aplicáveis para mensagens de interrupção. Saiba como configurar uma jornada para mensagens de interrupção e quais práticas recomendadas aplicar. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ajuda do Campaign

* Adobe Campaign v8: [Centro de ajuda](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=pt-BR) — [Notas de versão](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=pt-BR) — [Guias de implementação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=pt-BR)
* Adobe Campaign Standard: [Documentação do Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=pt-BR) - [Planejamento de lançamento](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=pt-BR)
* Adobe Campaign Classic: [Documentação do Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=pt-BR)
* Painel de controle do Adobe Campaign: [Documentação](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=pt-BR) — [Notas de versão](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=pt-BR) — Vídeos explicativos do [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=pt-BR)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=pt-BR)

## ![Ícone](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notas de versão do [!DNL Adobe Advertising Cloud].

* [Novos recursos no  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Novos recursos no  [!DNL Advertising Cloud Search]](#adcloud-search)

### Novos recursos no [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última atualização: **28 de setembro de 2021**

| Recurso | Descrição |
| ------- | ----------- |
| Exibições de gerenciamento de campanha | Uma coluna &quot;[!UICONTROL Creation date]&quot; agora está disponível em conjuntos de colunas personalizados para as exibições [!UICONTROL Campaigns], [!UICONTROL Packages], [!UICONTROL Placement] e [!UICONTROL Ads]. Você também pode filtrar as exibições [!UICONTROL Disposições] e [!UICONTROL Anúncios] por [!UICONTROL Data de criação]. |
| Acordos programáticos garantidos | (Versão de 8 de setembro) Agora é possível editar o [!UICONTROL Lance máximo] para a disposição padrão de um negócio programático garantido (PG). No entanto, como as ofertas PG sempre têm um CPM fixo, somente os clientes internacionais devem editar o [!UICONTROL Lance máx] para considerar as taxas de câmbio de moeda. |
|  | (Versão de 8 de setembro) Os usuários com a permissão &quot;[!DNL FreeWheel Programmatic Guaranteed]&quot; agora podem enviar um anúncio para o [!DNL FreeWheel Programmatic Creative API] na exibição [!UICONTROL Anúncios] ou na exibição [!UICONTROL Disposições]. Você ainda pode enviar um anúncio da visualização [!UICONTROL Deals]. |

{style=&quot;table-layout:auto&quot;}

### Novos recursos no [!DNL Advertising Cloud Search] {#adcloud-search}

Última atualização: **28 de setembro de 2021**

| Recurso | Descrição |
| ------- | ----------- |
| Insights de publicidade | Os insights adicionais estão disponíveis no modo beta. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/magento.png) [!DNL Commerce]  (Magento) {#magento}

Consulte os seguintes links para as notas de versão do Adobe Commerce:

* [Adobe Commerce e Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite para Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Ícone](/assets/target.png) [!DNL Target] {#target}

Última atualização: **3 de agosto de 2021**

Consulte as [[!DNL Target] notas de versão](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=pt-BR) para obter as informações mais recentes.

## ![Ícone](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

O [!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes envolvendo-se em cada estágio de jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte a [!DNL Marketo Engage] [programação de lançamento](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=pt-BR) para obter as informações mais recentes sobre a programação de lançamento e notas de versão.

## ![Ícone](/assets/workfront.png) [!DNL Workfront] {#workfront}

O Adobe [!DNL Workfront] é um aplicativo unificado de gerenciamento de trabalho para compartilhar ideias, criar conteúdos, gerenciar processos complexos e fazer o melhor trabalho.

Consulte a página [[!DNL Workfront] lançamentos](https://one.workfront.com/s/product-releases) para obter um resumo das informações mais recentes para todos os produtos.

## ![Ícone](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Novos vídeos, tutoriais ou cursos publicados na Adobe Document Cloud.

### Cursos e tutoriais do Document Cloud {#tutorials-doc-cloud}

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Outubro de 2021 | [O que é uma assinatura digital?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Vídeo | Saiba como usar IDs digitais do mundo todo com o Adobe Sign. |
| Outubro de 2021 | [Introdução ao Adobe Sign para novos remetentes](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | Vídeo | Se você nunca usou o Adobe Sign, este tutorial é um ótimo local para começar. Este tutorial abrangente foca em todas as noções básicas para colocar você em operação rapidamente com o Adobe Sign. |
| Outubro de 2021 | [Carregar comentários em PDF no InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | Vídeo | Neste tutorial em vídeo de 60 segundos, saiba como carregar comentários em PDF de volta ao InDesign depois de uma revisão compartilhada pela Acrobat. Este fluxo de trabalho digital ajuda você a concluir revisões em tempo recorde. |
| Outubro de 2021 | [Obter uma ID digital de [!DNL Intesi Group]  (Qualificada)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | Vídeo | Saiba como obter um certificado de assinatura digital qualificado do Grupo [!DNL Intesi]. Depois de registrado e sua identidade ser verificada, [!DNL Intesi] o Grupo emite uma ID digital usada para aplicar uma assinatura na nuvem do Adobe Sign. |
| Outubro de 2021 | [Fazer logon usando [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | Vídeo | Saiba como usar a ID digital do Grupo Intel para autenticar sua identidade e autorizar uma assinatura digital remota (assinatura na nuvem) em um documento. |
| Outubro de 2021 | [Obter uma ID digital do [!DNL Intesi Group]  (Avançado)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | Vídeo | Saiba como obter um certificado de assinatura digital avançado do Grupo Intesi. Depois de registrado e sua identidade ser verificada, o Grupo Intel emite uma ID digital usada para aplicar uma assinatura em nuvem do Adobe Sign. |
| Outubro de 2021 | [Fazer logon usando [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | Vídeo | Saiba como usar sua [!DNL Digidentity] ID digital para autenticar sua identidade e autorizar uma assinatura digital remota (assinatura na nuvem) em um documento. |
| Outubro de 2021 | [Obter uma ID digital de [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | Vídeo | Saiba como obter um certificado de assinatura digital de [!DNL Digidentity]. Depois de registrado e sua identidade ser verificada, [!DNL Digidentity] emite uma ID digital usada para aplicar uma assinatura em nuvem do Adobe Sign. |
| Outubro de 2021 | [Detectar diferenças entre dois PDFs](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | Vídeo | Nunca cometa o erro de trabalhar com a versão errada de um arquivo. Detecte de forma rápida e precisa as diferenças entre dois arquivos PDF para melhorar os fluxos de trabalho de revisão do documento. |
| Outubro de 2021 | [Crie conteúdo PDF enquanto navega com o Microsoft® Edge](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | Vídeo | Saiba como arquivar páginas da Web em PDF dinamicamente com a extensão Adobe Acrobat para Microsoft® Edge. Essa ferramenta somente Windows é inestimável para projetos de pesquisa e visualização offline de informações baseadas na Web. |
| Outubro de 2021 | [Converter mensagens de email e anexos em PDF no Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | Vídeo | Saiba como arquivar mensagens de email e anexos em PDF no Outlook para seus projetos. Saiba como fornecer informações de maneira mais profissional e segura convertendo automaticamente anexos em PDF. Esta ferramenta só está disponível para Windows. |

{style=&quot;table-layout:auto&quot;}

Para obter ajuda sobre a Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem e suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Creative Cloud para corporações {#creative-cloud}

Consulte [Creative Cloud para tutoriais corporativos](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=pt-BR) para obter os tutoriais mais recentes.
