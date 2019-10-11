---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: notas de versão
last-update: Outubro de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 11f19eef3e0d5fec9b7008c51a3afbb94ec1c2c6

---


# Notas de versão da Adobe Experience Cloud - outubro de 2019

Novos recursos e correções na Adobe Experience Cloud.

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
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (Todos os produtos da Adobe)

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
| API do Privacy Service: CCPA | A Lei de Privacidade do Consumidor da Califórnia (California Consumer Privacy Act, ou CCPA) aprimora os direitos de privacidade e a proteção do consumidor para os moradores da Califórnia, nos Estados Unidos. Esta lei deve entrar em vigor em 1º de janeiro de 2020.<br/><br/>A CCPA oferece novos direitos de privacidade de dados aos moradores da Califórnia, como o direito de acessar e excluir seus dados pessoais, de saber se seus dados pessoais são vendidos ou divulgados (e para quem) e de recusar a venda de seus dados pessoais.<br/><br/>Antecipando o CCPA, o Privacy Service apoiará pedidos de recusa da venda de dados pessoais.<br/><br/>O Privacy Service era anteriormente chamado de GDPR Service e mantém todas as funcionalidades anteriores, agora estendidas para oferecer suporte à CCPA.<br/><br/>[CCPA em Visão geral do](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br/><br/>[Analytics Privacy Service](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Relatórios de privacidade: Admin Console do Analytics | Habilitar o Relatório de privacidade no Analytics adiciona um conjunto de variáveis reservadas a um conjunto de relatórios.  As variáveis são projetadas para ajudar na coleta de dados de consentimento do consumidor no nível da ocorrência.<br/><br/>Novas dimensões:<br/><ul><li>Recusa no gerenciamento de consentimento</li><li>Aceitação no gerenciamento de Consentimento</li><li>[Variáveis do gerenciamento de consentimento](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Analytics de áudio e vídeo: suporte à privacidade | Duas novas variáveis foram adicionadas à API Media Collection:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Essas são variáveis opcionais que podem ser usadas para capturar o status do consentimento do consumidor no momento da ocorrência.<br/><br/>[Documentação da API de coleta de mídiaAs novas variáveis de dados de contexto do Gerenciamento de consentimento do Analytics foram adicionadas ao formulário do Federated Analytics.](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/> Essas variáveis agora estão disponíveis para uso no sinalizador Recusar das ocorrências Compartilhamento ou Venda para federação.<br/><br/>[Download de formulário federado](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace: atualização dos totais das tabelas de forma livre | As tabelas de forma livre agora incluem dois totais, um **[!UICONTROL total da tabela]** e um **[!UICONTROL total geral]**. As contas de linhas totais da tabela para os filtros [de](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) relatório aplicados. Anteriormente, somente a segmentação afetava os totais. [Saiba](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>maisAlém disso, as opções **[!UICONTROL Mostrar totais]** e **[!UICONTROL Mostrar total]** geral foram adicionadas às Configurações **[!UICONTROL de]** coluna.<br/>Com essa alteração nos totais das tabelas de forma livre, as visualizações dependentes serão atualizadas (ex: visualizações de **[!UICONTROL Número de resumo]** interligadas), bem como dados CSV e PDF exportados. |
| Analysis Workspace: opção para remover Não especificado/Nenhum | A capacidade de remover facilmente "Não especificado (Nenhum)" foi adicionada como uma opção de filtro de relatório. |
| Analysis Workspace: substituição de componentes com granularidade violeta | Os componentes de tempo com granularidade violeta (minuto, hora, dia, semana, mês, trimestre, ano) foram descontinuados. Os componentes de tempo violeta sempre se comportaram exatamente como seus equivalentes na dimensão laranja, então essa alteração simplificará a experiência. **Nenhuma ação** precisa ser executada se você tiver usado anteriormente um dos componentes de tempo violeta.<br/>Com essa alteração, a seção **[!UICONTROL Tempo]** violeta, além disso, foi renomeada para **[!UICONTROL Intervalos de datas]**. |

#### Correções

* Analysis Workspace: correção de um problema que resultava em resultados de pesquisa incorretos ao pesquisar itens de dimensão no painel esquerdo. (AN-185065)
* Correção de problemas relacionados à impossibilidade de excluir ou cancelar a publicação de segmentos compartilhados no Adobe Audience Manager (AAM). A correção é não excluir o segmento se o AAM não responder. (AN-185882, AN-185883, AN-184607)
* Corrigido um problema de limite de tempo ao não conseguir carregar segmentos no Ad Hoc Analysis. (AN-184654)
* Correção de um problema que ocorria quando o conjunto de relatórios usado pela última vez era oculto posteriormente ou quando você não tinha mais permissões para acessar esse conjunto de relatórios. Nesse caso, não é mais possível fazer logon via Experience Cloud. (AN-181777)
* Corrigido um problema de limite de tempo em segmentos que dificultava a criação de um VRS com base em um segmento. (AN-179684)
* Correção de um problema em que os dados eram truncados se houvesse uma codificação incorreta em casos raros. (AN-186707)
* Os Mecanismos de Pesquisa Yandex agora são devidamente divididos por país. (AN-181728)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Singapura, não apoiaremos mais a intermediação de dados entre Londres ou Singapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Atualização dos totais da tabela de forma livre da Analysis Workspace | 12 de setembro de 2019 | Em outubro de 2019, o total de linhas da tabela de forma livre começará a contabilidade dos filtros [de](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) relatório aplicados. Até hoje, os totais eram contabilizados somente para segmentação. Com essa alteração, as visualizações dependentes serão atualizadas (ex: visualizações vinculadas de [!UICONTROL Número de resumo]), bem como dados CSV e PDF exportados. |
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
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

### [!DNL AppMeasurement] {#appm}

Consulte [AppMeasurement para notas](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)de versão do Javascript.

## Audience Manager {#aam}

Novos recursos, melhorias e correções no Audience Manager.

**Correções e melhorias**

* Todas as contas de clientes criadas após 1º de julho de 2019 receberão automaticamente uma licença [!DNL Tableau], fornecendo a eles acesso a seus relatórios. Se sua conta foi criada antes de 1º de julho de 2019 e você ainda não tem acesso aos seus relatórios [!DNL Tableau], entre em contato com o Atendimento ao cliente.
* Corrigimos um erro que causava características de geração de atividade incorretas e aumento artificial das taxas de correspondência e do tamanho do público-alvo. Após essa correção, você pode notar reduções no tamanho dos segmentos criados com características de atividade geradas automaticamente. Esse é um comportamento normal esperado (AAM-45371).
* Removemos IDs de dispositivos globais inválidas das fontes de dados globais. Consulte Fontes [de dados](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) globais para saber como as IDs de dispositivo válidas devem ser aceitas pelo Audience Manager (AAM-41259).
* Corrigido um erro que fazia com que a página Segmentos parasse de responder quando alguém tentava excluir um segmento protegido (AAM-49881).
* Ao editar destinos para públicos-alvo personalizados do Twitter, o seletor de [!UICONTROL contas] agora estará ativo apenas se o destino não tiver uma [!DNL Twitter Ads] conta atribuída a ele (AAM-49975).
* Corrigido um erro que impedia que os usuários desativassem os feeds de dados do [!UICONTROL Audience Marketplace] quando as assinaturas eram desativadas (AAM-49640).
* Fizemos diversas melhorias relacionadas à acessibilidade da Interface do usuário do Audience Manager.

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Versão do produto

* **Cloud Manager 2019.9.0**

   * O Cloud Manager 2019.9.0, lançado em 12 de setembro de 2019, atualiza os critérios de teste de segurança, adiciona gráficos de monitoramento disponíveis para download e corrige alguns problemas de usabilidade relatados pelo cliente.
   * [Notas de versão](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Manutenção do produto

* **AEM 6.3.3.6**

   O AEM 6.3 Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6, lançado 25 de setembro de 2019) é uma atualização importante que inclui correções essenciais para o cliente, lançadas desde a disponibilização geral do AEM 6.3 SP em abril de 2017.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   O AEM 6.4, Service Pack 6.0 (6.4.6.0, lançado em 19 de setembro de 2019), é uma atualização importante que inclui correções essenciais para clientes, lançadas desde a disponibilização geral do AEM 6.4 em abril de 2018.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0**
AEM 6.5, Service Pack 2.0 (6.5.2.0, lançado em 19 de setembro de 2019), é uma atualização importante que inclui correções essenciais para clientes, lançadas desde a disponibilização geral do AEM 6.5 em abril de 2019.
   * [Notas de versão](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Autoajuda

* **Scene7: fluxo de trabalho de reprocessamento de ativos**

   Agora é possível reprocessar ativos em uma pasta que já tenha um perfil de processamento existente que você alterou posteriormente.
Consulte [Reprocessando ativos em uma pasta depois de ter editado seu perfil](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)de processamento.

* **Integração do Dynamic Media Viewers com o Adobe Analytics e o Adobe Launch**

   A extensão do Dynamic Media Viewers para o Adobe Launch, juntamente com o lançamento do Dynamic Media Viewers 5.13, permite que os clientes do Dynamic Media, do Adobe Analytics e do Adobe Launch usem eventos e dados específicos para o Dynamic Media Viewers na configuração do Adobe Launch.
See [Integrating Dynamic Media Viewers with Adobe Analytics and Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **Aplicativo para desktop do AEM**

   O aplicativo para desktop 2.0 do AEM agora está disponível para pessoas criativas, profissionais de marketing e usuários da área de negócios trabalharem com AEM Assets.
Consulte as [notas de versão do aplicativo para desktop do AEM.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Componentes principais**
   * Saiba mais sobre os recursos de localização dos Componentes principais e como eles trabalham com modelos do AEM.
      [Consulte o exemplo](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
   * Os Componentes principais 2.6.0 apresentam um componente de fragmento de experiência. The component is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Assets**
   * Nova documentação sobre recursos de pesquisa visual/por semelhança.
Consulte [Localizar imagens](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)semelhantes.
   * A funcionalidade Ativos conectados agora usa documentos que estão disponíveis na implantação remota de DAM, além de formatos de arquivos de imagens.
Consulte [Usar ativos conectados para compartilhar ativos DAM no AEM Sites](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html).
   * Conteúdo novo na pesquisa e descoberta de ativos. O tópico _Pesquisar ativos no AEM_ é o seu balcão central para obter informações sobre como usar, configurar, solucionar problemas, limitações e dicas.
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
