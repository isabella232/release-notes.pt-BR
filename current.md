---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: notas de versão
last-update: de outubro de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 7a62b190f260c5384340559b237e17eaf21e1892

---


# Early Access - Experience Cloud Release Notes - October 2019

Novos recursos e correções na Adobe Experience Cloud.

>[!IMPORTANT]
>
>Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.
>
>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

## Data de lançamento: 10 de outubro de 2019

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| Privacy Service API: CCPA | The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act is set to become effective on January 1, 2020.<br><br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br><br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out of the selling of personal data.<br><br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/>CCPA in Analytics: Privacy Service Overview<br><br/>[](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Privacy Reporting: Analytics Admin Console | Enabling Privacy Reporting for Analytics adds a set of reserved variables to a report suite.  The variables are designed to assist in the collection of consumer consent data at a hit level.<br/>New Dimensions:<br/><ul><li>Consent Management Opt-Out</li><li>Aceitação do Gerenciamento de Consentimento</li><li>Variáveis de gerenciamento de consentimento: </li></ul> |
| Análise de áudio e vídeo: Suporte à privacidade | Duas novas variáveis foram adicionadas à API Media Collection:<br/><ul><li> analytics.optOutServerSideForwarding</li><li> analytics.optOutShare</li></ul>Essas são variáveis opcionais que podem ser usadas para capturar o status do consentimento do consumidor no momento da ocorrência. [Documentação da API de coleta de mídiaAs novas variáveis de dados de contexto do Gerenciamento de consentimento do Analytics foram adicionadas ao formulário do Federated Analytics.](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/> Essas variáveis agora estão disponíveis para uso no sinalizador Recusar compartilhamento ou Ocorrências de venda para federação. [Download de formulário federado](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace: Atualizar para totais de tabelas de forma livre | As tabelas de forma livre agora incluem dois totais, um total **[!UICONTROL de]** tabela e um total **** geral. As contas de linhas totais da tabela para os filtros [de](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) relatório aplicados. Anteriormente, somente a segmentação afetava os totais. [Saiba](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>maisAlém disso, as opções **[!UICONTROL Mostrar totais]** e **[!UICONTROL Mostrar total]** geral foram adicionadas às Configurações **[!UICONTROL de]** coluna.<br/>Com essa alteração nos totais de forma livre, as visualizações dependentes serão atualizadas (por exemplo, as visualizações vinculadas do Número **[!UICONTROL de]** resumo), bem como os dados CSV e PDF exportados. |
| Analysis Workspace: Opção para remover Não especificado/Nenhum | A capacidade de remover facilmente "Não especificado (Nenhum)" foi adicionada como uma opção para reportar filtros. |
| Analysis Workspace: Substituição de componentes de granularidade violeta | Os componentes de tempo de granularidade violeta (Minuto, Hora, Dia, Semana, Mês, Trimestre, Ano) foram descontinuados. Os componentes de tempo violeta sempre se comportaram exatamente como seus equivalentes de dimensão laranja, então essa alteração simplificará a experiência. **Nenhuma ação** precisa ser executada se você tiver usado anteriormente um dos componentes de tempo violeta.<br/>Com essa alteração, a seção **[!UICONTROL Tempo]** violeta também foi renomeada para Intervalos **[!UICONTROL de datas]**. |

#### Correções

* Analysis Workspace: Correção de um problema que resultava em resultados de pesquisa incorretos ao pesquisar itens de dimensão no painel esquerdo. (AN-185065)
* Correção de problemas com a impossibilidade de excluir ou cancelar a publicação de segmentos compartilhados no Adobe Audience Manager (AAM). The fix is to not delete the segment if AAM is unresponsive. (AN-185882, AN-185883, AN-184607)
* Correção de um problema de tempo limite com a impossibilidade de carregar segmentos na Análise ad hoc. (AN-184654)
* Correção de um problema que ocorria quando o conjunto de relatórios usado pela última vez era posteriormente oculto ou você não tinha mais permissões para acessar esse conjunto de relatórios. Nesse caso, não é mais possível fazer logon por meio da Experience Cloud. (AN-181777)
* Fixed a timeout issue in segments that made it difficult to create a VRS based on a segment. (AN-179684)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. |
| Agente FTP de San Jose terminando em Londres e Cingapura | Julho de 2020 | For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center ftp.omniture.com.[](ftp://ftp.omniture.com/)<br/>Para Londres, use [ftp3.omniture.](ftp://ftp3.omniture.com/)<br/>comPara Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/) |
| Atualização dos totais da tabela de forma livre da Analysis Workspace | 12 de setembro de 2019 | Em outubro de 2019, o total de linhas da tabela de forma livre começará a contabilidade dos filtros [de](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) relatório aplicados. Até hoje, os totais eram contabilizados somente para segmentação. Com essa alteração, as visualizações dependentes serão atualizadas (ex: visualizações vinculadas de [!UICONTROL Número de resumo]), bem como dados CSV e PDF exportados. |
| Alteração futura em relação ao campo `createDate` para usuários do Analytics | 30 de agosto de 2019 | Em outubro ou novembro de 2019, o campo `createDate` para os usuários do Analytics será atualizado da Hora do Pacífico dos EUA para um valor de data/hora corretamente formatado com as informações de fuso horário. (AN-183468) |
| Suporte para deslocamentos de fuso horário históricos | 8 de agosto de 2019 | O Analytics agora manipular automaticamente deslocamentos de fuso horário para ocorrências com carimbo de data e hora. Após essa mudança em 8 de agosto, os sistemas que carregam dados para o processamento histórico não precisarão mais ajustar para deslocamentos de fuso horário antes de enviar os dados. |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | These limits are not new, but have been added to the documentation here.[](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html) |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | A partir de 18 de julho de 2019, os operadores de segmento _contêm um dos_, _não contém nenhum dos_, _contém todos os_ e _não contém nenhum dos_ serão limitados a 100 palavras por campo de entrada. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração foi aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Alteração de cálculos de _Total de relatório_ | atualizado em: 9 de julho de 2019 | Em **18 de junho de 2019**, o Adobe Analytics tornou os cálculos de _Total de relatório_ consistentes em todas as dimensões e métricas. Isso resultou em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 18 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, os segmentos que usam a lógica _existe_ ou _não existe_ podem ver resultados diferentes para algumas dimensões após essa mudança, especificamente dimensões em que _Não especificado_ tem um nome especial, como o item de linha "Digitado/Marcado" da dimensão Tipo de referenciador ou o item de linha "Outro" da dimensão Tipo de dispositivo. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV na Analysis Workspace | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas aos **[!UICONTROL downloads CSV]** (e **[!UICONTORL Copiar para área de transferência]**) da Analysis Workspace para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da Analysis Workspace | 4 de abril de 2019 | O comando do Console para ativar o depurador da Analysis Workspace será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Links encurtados de [!DNL Analytics] relatórios do | 14 de janeiro de 2019 | Os links encurtados de [!DNL Analytics] relatórios do que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

### [!DNL AppMeasurement] {#appm}

See AppMeasurement for Javascript release notes.[](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)

## Audience Manager {#aam}

Novos recursos, melhorias e correções no Audience Manager.

**Correções e melhorias**

* All customer accounts created after July 1st, 2019, will automatically be assigned a  license, providing them access to their reports. [!DNL Tableau] Se sua conta tiver sido criada antes de 1º de julho de 2019 e você ainda não tiver acesso aos seus [!DNL Tableau] relatórios, entre em contato com o Atendimento ao cliente.
* Removemos associações de características de atividade geradas incorretamente para perfis de visitantes que não tinham uma sincronização de ID com a fonte de dados de característica (AAM-45371).
* We've removed invalid global device IDs from global data sources. See Global Data Sources to learn what valid device IDs should look like to be accepted by Audience Manager (AAM-41259).[](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)
* Fixed a bug causing the Segments page to stop responding when you attempt to delete a protected segment (AAM-49881).
* Ao editar destinos para Públicos personalizados do Twitter, o seletor [!UICONTROL Conta] agora está ativo somente se o destino não tiver uma [!DNL Twitter Ads] conta atribuída (AAM-49975).
* Fixed a bug preventing users from disabling Audience Marketplace data feeds when subscriptions are disabled (AAM-49640).
* Fizemos diversas melhorias relacionadas à acessibilidade da Interface do usuário do Audience Manager.

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Manutenção do produto

* **AEM 6.3.3.6**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6 lançado em 25 de setembro de 2019) é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.3, abril de 2017.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4, Service Pack 6.0 (6.4.6.0 lançado em 19 de setembro de 2019) é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.4, abril de 2018.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0** AEM 6.5, Service Pack 2.0 (6.5.2.0 lançado em 19 de setembro de 2019) é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.5, abril de 2019.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Autoajuda

* **Scene7: Reprocess Assets workflow**

   Agora é possível reprocessar ativos em uma pasta que já tem um perfil de processamento existente que você alterou posteriormente.
See Reprocessing assets in a folder after you have edited its processing profile.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)

* **Integração de visualizadores de mídia dinâmica com o Adobe Analytics e o Adobe Launch**

   A extensão do Dynamic Media Viewers para o Adobe Launch, juntamente com o lançamento do Dynamic Media Viewers 5.13, permite que os clientes do Dynamic Media, do Adobe Analytics e do Adobe Launch usem eventos e dados específicos para o Dynamic Media Viewers na configuração do Adobe Launch.
Consulte [Integração de visualizadores de mídia dinâmica com o Adobe Analytics e o Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **Aplicativo de desktop do AEM**

   AEM desktop app 2.0 is now available for creatives, marketers, and line-of-business users, to work with AEM Assets.
See the AEM desktop app Release notes.[](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Componentes principais**
   * Saiba mais sobre os recursos de localização dos Componentes principais e como eles trabalham com modelos do AEM.
      [Consulte o exemplo](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
   * Componentes principais 2.6.0 apresenta um componente de fragmento de experiência. O componente agora está disponível junto com a documentação [de](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) criação e os detalhes do [desenvolvedor e o download do projeto disponível no GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Assets**
   * Nova documentação para recursos de pesquisa visual/de semelhança.
Consulte [Localizar imagens](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)semelhantes.
   * A funcionalidade Ativos conectados agora usa documentos que estão disponíveis na implantação remota de DAM, além de formatos de arquivo de imagens.
Consulte [Usar ativos conectados para compartilhar ativos DAM no AEM Sites](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html).
   * Conteúdo novo na pesquisa e descoberta de ativos. O tópico _Pesquisar ativos no AEM_ é o seu balcão único para obter informações sobre como usar, configurar, solucionar problemas, limitações e dicas.
Consulte [Pesquisar ativos no AEM](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html).

### Recursos adicionais

* [Página inicial de Aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Página inicial de ajuda do Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notas de versão do Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Adobe Campaign Classic

* [Atualização](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) do Campaign Classic 19.1.4 - compilação 9032
* [Atualização](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) do Campaign Classic 19.1.6 - compilação 9035

### Recursos adicionais

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
