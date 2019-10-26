---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: notas de versão
last-update: de novembro de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 2c6076aa0af7b9a273e31b1f8919e006ff48e6b4

---


# Acesso antecipado - Notas de versão da Adobe Experience Cloud - novembro de 2019

> [!IMPORTANT] Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.

Novos recursos e correções na Adobe Experience Cloud.

> [!NOTE] Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por e-mail sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 30 de outubro de 2019**

* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)
* [!DNL Advertising Cloud](#adcloud)

## Interface da Experience Cloud {#ecloud}

Notas de versão da interface da Experience Cloud e administração de produtos.

* A página do Feed está sendo substituída em dezembro de 2019. Procure um aviso de desaprovação no produto. (MCUI-10039)
* Atualização do link [Saiba mais](https://www.adobe.com/marketing/campaign.html) para o Adobe Campaign no seletor de aplicativos. (MCUI-10034)
* Estabilidade e agilidade da plataforma principal aprimoradas para a interface da Experience Cloud. (MCUI-6822)
* Corrigidas as vulnerabilidades de segurança na interface do usuário da Experience Cloud. (MCUI-9942)
* Corrigido um problema crítico nos Atributos do cliente que bloqueava a validação do esquema para alguns clientes. (MCUI-10024, MCUI-6479)
* Melhoria da Biblioteca de público-alvo para remover dimensões que não são suportadas para criação de público-alvo em tempo real. (MCUI-10046)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (Todos os produtos da Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para obter as notas de versão e a documentação do produto.

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

Para obter a documentação do produto, consulte a [Página inicial de ajuda do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- | 
| Análise de jornada do cliente | Em 21 de novembro de 2019, a Adobe disponibilizará o [Customer Journey Analytics](https://www.adobe.com/analytics/customer-journey-analytics.html) como um complemento do Adobe Analytics.<br><br/>O Customer Journey Analytics permite que você forneça todos os dados de seus clientes de qualquer canal. tanto online como offline — na Adobe Experience Platform e, em seguida, analise esses dados da mesma forma que faria com seus dados digitais existentes usando a Analysis Workspace hoje. O Customer Journey Analytics inclui a capacidade de controlar como você conecta seus dados online e offline na Analysis Workspace em qualquer ID de cliente comum, permitindo, finalmente, que você faça atribuição, segmentação, fluxo, fallout etc. em todo o conjunto de dados do cliente no Adobe Analytics.<br><br/>Os clientes do Analytics Select, Prime e Ultimate estão qualificados para comprar este produto complementar. Entre em contato com a equipe de sua conta da Adobe para obter mais detalhes. |
| API do Privacy Service: CCPA | A Lei de Privacidade do Consumidor da Califórnia (California Consumer Privacy Act, ou CCPA) aprimora os direitos de privacidade e a proteção do consumidor para os moradores da Califórnia, nos Estados Unidos. Esta lei deve entrar em vigor em 1º de janeiro de 2020.<br><br/>A CCPA oferece novos direitos de privacidade de dados aos moradores da Califórnia, como o direito de acessar e excluir seus dados pessoais, de saber se seus dados pessoais são vendidos ou divulgados (e para quem) e de recusar a venda de seus dados pessoais.<br><br/>Em antecipação à CCPA, o Privacy Service dará suporte a solicitações de recusa de permissão da venda de dados pessoais.<br><br/>O Privacy Service era anteriormente chamado de GDPR Service e mantém todas as funcionalidades anteriores, agora estendidas para oferecer suporte à CCPA.<br/><br/>[CCPA no Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Visão geral de privacidade](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Relatórios de privacidade: Admin Console do Analytics | Habilitar o Relatório de privacidade no Analytics adiciona um conjunto de variáveis reservadas a um conjunto de relatórios.  As variáveis são projetadas para ajudar na coleta de dados de consentimento do consumidor no nível da ocorrência.<br><br/>Novas dimensões:<br/><ul><li>Recusa no gerenciamento de consentimento</li><li>Aceitação no gerenciamento de Consentimento</li><li>[Variáveis do gerenciamento de consentimento](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Analytics de áudio e vídeo: suporte à privacidade | Duas novas variáveis foram adicionadas à API Media Collection:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Essas são variáveis opcionais que podem ser usadas para capturar o status do consentimento do consumidor no momento da ocorrência.<br/><br/>[Documentação da API de coleta de mídia](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>As novas variáveis de dados de contexto do Gerenciamento de consentimento do Analytics foram adicionadas ao formulário do Federated Analytics. Essas variáveis agora estão disponíveis para uso na sinalização de Desativar compartilhamento ou Venda de hits para federação.<br/><br/>[Faça o download do formulário federado](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### Correções

* Correção de um problema que resultava em erro ao tentar excluir intervalos de datas pertencentes a "Usuário desconhecido". (AN-185540)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Opção EOL do arquivo de **[!UICONTROL visualização]** | 30 de out de 2019 | Anunciando a data de janeiro de 2020, fim da vida útil da opção **[!UICONTROL Exibir arquivo]** no Gerenciador de painel (**[!UICONTROL Componentes &gt; Painéis]**). |
| Opção EOL de **[!UICONTROL impor restrições]** de logon de IP | 30 de out de 2019 | Anunciando a data de janeiro de 2020, fim da vida útil da funcionalidade de lista de permissões de logon de IP (**[!UICONTROL Impor restrições]** de logon de IP) no menu **[!UICONTROL Admin &gt; Configurações da empresa &gt; Segurança]** . |
| Manuseio atualizado para o atributo SameSite em cookies | 15 de outubro de 2019 | Em agosto de 2019, a Adobe anunciou que adicionou a configuração de cookie SameSite a todos os cookies definidos pelo Analytics. Uma atualização na lógica é aplicada onde:<ul><li>Todos os cookies de terceiros que não são baseados no Webkit têm o atributo SameSite definido como `none`.</li><li>Todos os outros cookies não têm o atributo SameSite definido.</li></ul> |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Singapura, não apoiaremos mais a intermediação de dados entre Londres ou Singapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Atualização dos totais da tabela de forma livre da Analysis Workspace | 12 de setembro de 2019 | Em outubro de 2019, as linhas de total da tabela de forma livre começarão a contabilizar para [filtros de relatório](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) foram aplicadas. Até hoje, os totais eram contabilizados somente para segmentação. Com essa alteração, as visualizações dependentes serão atualizadas (ex: visualizações vinculadas de [!UICONTROL Número de resumo]), bem como dados CSV e PDF exportados. |
| Alteração futura em relação ao campo `createDate` para usuários do Analytics | 30 de agosto de 2019 | Em outubro ou novembro de 2019, o campo `createDate` para os usuários do Analytics será atualizado da Hora do Pacífico dos EUA para um valor de data/hora corretamente formatado com as informações de fuso horário. (AN-183468) |
| Suporte para deslocamentos de fuso horário históricos | 8 de agosto de 2019 | O Analytics agora manipular automaticamente deslocamentos de fuso horário para ocorrências com carimbo de data e hora. Após essa mudança em 8 de agosto, os sistemas que carregam dados para o processamento histórico não precisarão mais ajustar para deslocamentos de fuso horário antes de enviar os dados. |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | Esses limites não são novos, mas foram adicionados à documentação [aqui](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | A partir de 18 de julho de 2019, os operadores de segmento _contêm um dos_, _não contém nenhum dos_, _contém todos os_ e _não contém nenhum dos_ serão limitados a 100 palavras por campo de entrada. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração foi aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Alteração de cálculos de _Total de relatório_ | atualizado em: 9 de julho de 2019 | Em **18 de junho de 2019**, o Adobe Analytics tornou os cálculos de _Total de relatório_ consistentes em todas as dimensões e métricas. Isso resultou em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 18 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, os segmentos que usam a lógica _existe_ ou _não existe_ podem ver resultados diferentes para algumas dimensões após essa mudança, especificamente dimensões em que _Não especificado_ tem um nome especial, como o item de linha "Digitado/Marcado" da dimensão Tipo de referenciador ou o item de linha "Outro" da dimensão Tipo de dispositivo. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV na Analysis Workspace | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas aos **[!UICONTROL downloads CSV]** (e **[!UICONTORL Copiar para área de transferência]**) da Analysis Workspace para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da Analysis Workspace | 4 de abril de 2019 | O comando do Console para ativar o depurador da Analysis Workspace será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Links encurtados de [!DNL Analytics] relatórios do | 14 de janeiro de 2019 | Os links encurtados de [!DNL Analytics] relatórios do que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimento, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Novos recursos, melhorias e correções no Audience Manager.

| Recurso | Descrição |
|--- |----|
| [Aprimoramentos das regras de mesclagem de perfil](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | Lançamos uma série de aprimoramentos para Regras [!UICONTROL de mesclagem de]perfis: <ul><li>A avaliação de segmentos agora é suportada em lote, para até 100 dispositivos.</li><li>Melhoramos a precisão dos relatórios para as populações de características e segmentos.</li><li>Melhoramos a precisão dos arquivos em lote gerados com IDs de vários dispositivos.</li><li>Atualizamos a documentação com casos de uso mais detalhados para cada regra. Consulte Casos de uso [gerais para Regras](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)de mesclagem de perfil, Casos [de uso do gráfico de dispositivo](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)externo e Casos [de uso do gráfico de dispositivo de link de](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)perfil.</li></ul> |
| [Ferramentas de gerenciamento em massa](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Lançamos uma nova versão da planilha de Gerenciamento em massa que funciona em sistemas operacionais MacOS e Microsoft Windows e oferece suporte ao logon da Experience Cloud. |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | Adicionamos suporte para [!DNL HTTP Strict-Transport-Security], uma política de segurança da Web que protege contra ataques de sequestro de cookies e downgrade de protocolos. |

**Correções e melhorias**

* Corrigimos um erro no Audience Marketplace, onde a interface retornava o Erro 409 quando os clientes enviavam o uso mensal do segmento. (AAM-50825)
* Corrigimos um bug nos Sinais derivados, onde por pouco tempo os clientes não conseguiam criar novos sinais derivados. (AAM-50968)
* Corrigimos um erro em Destinos baseados em pessoas, onde os clientes não conseguiam alterar o nome de um destino. (AAM-51025)
* Corrigimos um erro em que alguns usuários tinham contas duplicadas para fazer logon na interface do usuário do Audience Manager. Devido às permissões associadas às contas duplicadas, esses usuários não conseguiram acessar algumas partes da interface do usuário e executar operações. (AAM-50818)
* Continuamos a melhorar a acessibilidade da interface do usuário do Audience Manager. (AAM-48932, AAM-49043, AAM-49054, AAM-49371, AAM-49375)

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Versões do produto

* **Brand Portal 6.4.5**

   O Adobe Experience Manager Assets Brand Portal 6.4.5 é uma versão de recurso que tem como objetivo fornecer aos usuários do Brand Portal (agências/equipes externas) a capacidade de carregar conteúdo no Brand Portal e publicá-lo nos ativos AEM, sem precisar acessar o ambiente do autor. Esse recurso é chamado de Fonte de [ativos no Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)de marcas e melhora as experiências do cliente, fornecendo um mecanismo bidirecional para que os usuários contribuam e compartilhem ativos com outros usuários do Portal de marcas distribuídos globalmente.

   Consulte [Novidades do AEM Assets Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html).

   See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **Serviço de conversão automatizada do AEM Forms**

   O serviço de Conversão de formulários automatizados ajuda a acelerar a digitalização e a modernização de experiências de captura de dados por meio da conversão automatizada de formulários PDF em formulários adaptáveis. O serviço, desenvolvido pelo Adobe Sensei, converte automaticamente seus formulários PDF em formulários adaptáveis compatíveis com dispositivos, responsivos e baseados em HTML5. Ao aproveitar os investimentos existentes em PDF Forms e XFA, o serviço também aplica validações, estilo e layout apropriados aos campos de formulário adaptáveis durante a conversão.

   Consulte Serviço [de conversão automatizada de formulários do](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)Adobe Experience Manager.

* **Cloud Manager 2019.10.0**

   As Notas de versão gerais do Cloud Manager 2019.10.0 estão disponíveis. As notas também listam atualizações para etapas de implantação e manuseio de versão de projeto inteligente.

   Consulte Notas [de versão do](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)Cloud Manager 2019.10.0.

### Autoajuda

* **Activity Map**

   Devido a alterações de segurança na API do Adobe Analytics, não é mais possível usar a versão do Activity Map incluída no AEM. Consulte [Configuração da conexão com o Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics).

   Agora você deve usar o plug-in [do navegador do](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) Activity Map para Chrome, Firefox ou Internet Explorer, conforme fornecido pelo Adobe Analytics.

* **Guia de práticas recomendadas para projetos do AEM Screens**

   O novo Guia de práticas _recomendadas para o AEM Screens_ fornece insight abrangente e conselhos práticos para imaginar, projetar e trazer experiências intencionais do cliente para a implementação da sinalização digital. Ele também o orienta a criar um impacto positivo em seus negócios usando as práticas recomendadas, tudo isso ao implantar um projeto de sinalização digital no AEM Screens.

   Consulte Guia de práticas [recomendadas para projetos](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html)do AEM Screens.

* **Gerenciamento de experiência sem cabeçalho**

   Os recursos do [Remote Content Renderer](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) que é usado para renderização de aplicativos de página única no servidor agora estão documentados.

* **Renderização do SPA e do servidor**

   Você pode estender e personalizar o serviço de renderização remota de conteúdo que seus SPAs orientados por AEM usam para renderização no servidor para atender às suas necessidades.

   Consulte Renderização [SPA e do servidor](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer).

* **Arquivo de projeto do AEM**

   O AEM Project Archetype cria um projeto Adobe Experience Manager mínimo baseado em práticas recomendadas como ponto de partida para seus próprios projetos do AEM. As propriedades que devem ser fornecidas ao usar esse arquétipo permitem que você especifique os nomes para todas as partes deste projeto, bem como controle determinados recursos opcionais.

   Consulte [Arquivo de projeto do AEM](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html).

* **Atualizações da documentação do AEM**

   Leia sobre alterações importantes na documentação e atualizações do Adobe Experience Manager nos últimos três meses.

   Consulte Documentação do [AEM: Atualizações](https://helpx.adobe.com/experience-manager/documentation-updates.html)recentes da documentação.

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

### Recursos de documentação

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de versão](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planejamento de versão](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos explicativos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Atualizado para 12 de outubro de 2019, versão

| Exibir | Recurso |
|------|---------|
| Campanhas de pesquisa | A Advertising Cloud agora pode sincronizar e fornecer rastreamento de nível de anúncio para contas no Yahoo! Japan Display Network. Se você fornecer detalhes de logon para uma conta, todas as campanhas, grupos de anúncios e anúncios existentes na conta estarão disponíveis como somente leitura nas exibições de gerenciamento de campanha. Os dados de cliques, custos, conversões e outros dados de desempenho estão disponíveis nas exibições de gerenciamento de campanhas e em relatórios básicos e avançados. |
|  | (Anunciantes com o Google Analytics) A Advertising Cloud Search pode sincronizar métricas de conversão de uma conta, propriedade e combinação de exibição específica do Google Analytics para otimização e relatórios. Exibições de página, Sessões, Taxa de rejeição (calculada como rejeições/sessões) e Duração da sessão são incluídas automaticamente. É possível incluir até 16 métricas adicionais por fonte de dados. |
|  | (Contas do Google Ads existentes para anunciantes com integração da Advertising Cloud-Adobe Analytics) Um novo formato está disponível para o código de rastreamento s_kwcid, permitindo que a Advertising Cloud compartilhe dados sobre a conta com o recurso de relatórios e análises do Adobe Analytics. O formato mais recente inclui parâmetros para a ID da campanha e a ID do grupo de anúncios, que são necessários para relatar com precisão os níveis da campanha e do grupo de anúncios para campanhas de Rascunhos e Experimentos do Google no Analytics. Se suas contas existentes do Google incluírem campanhas de Rascunhos e Experimentos do Google, edite as configurações de Rastreamento de cada conta individual para migrar para o novo s_kwcid. Se você não tiver campanhas de Rascunhos e Experimentos do Google, a migração para o novo formato é opcional. Observação: todas as novas contas do Google usam o novo formato automaticamente. |
| Gerenciamento de campanhas avançadas de busca (ACM) | (Campanhas do Google Ads) Agora você pode configurar sufixos de URL finais no nível de campanha para modelos de anúncios de texto e compras do Google. |
|  | (Campanhas do Google Ads) Os campos opcionais "Título 3" e "Descrição 2" estão disponíveis para anúncios de texto expandidos do Google. |
| Relatórios | As seguintes métricas de compartilhamento de impressão do Bing Ads, que foram descontinuadas com a mais recente API do Bing Ads, não foram coletadas após 11 de outubro: pesquisa IS% perdida para classificação, pesquisa IS% perdida para lance (Bing), pesquisa IS% perdida para relevância de página (Bing) e pesquisa IS% perdida para relevância de palavra-chave (Bing). Métricas coletadas anteriormente ainda estão disponíveis para relatórios. |
| Integração do Adobe Analytics | (Somente anunciantes com o Adobe Analytics) Na Analysis Workspace, a dimensão "Dispositivo (ID AMO)", que nunca coletou dados, não está mais disponível. Para criar relatórios sobre dados do Analytics online, use a dimensão "Tipo de dispositivo móvel". Para relatar as métricas de tráfego do mecanismo de pesquisa (como cliques, custo e impressões) por tipo de dispositivo, continue a usar os relatórios na Advertising Cloud Search. |
