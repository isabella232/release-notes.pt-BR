---
title: Notas de versão da Adobe Experience Cloud
description: Notas de versão da Experience Cloud de july 019
doc-type: notas de versão
last-update: julho de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: b4a91b853cfb5d228fc2195d65b4370e607475f2

---


# Acesso antecipado - Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!IMPORTANT]
>
>Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.

>[!NOTE]
>
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 18 de julho de 2019**

* [Serviços principais e administração da Experience Cloud](#experiencecloud)
* [!DNL Analytics](#analytics)**(Atualizado em July 5 de julho)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

Notas de versão da interface da Experience Cloud, incluindo serviços essenciais da [!UICONTROL plataforma] e administração de produtos.

* [Serviço da Experience Cloud ID](#ecid)
* [Mobile Services e SDK móvel](#mobile)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](#security)

### Serviço da Experience Cloud ID {#ecid}

**Correções e atualizações**

* `cookieDomain` atualização de configuração: A biblioteca atribuirá automaticamente um domínio de cookie de nível superior quando `cookieDomain` não `initConfig` estiver configurado. (CORE-29223)
* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE-31287)
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE-29719)
* Correção de um problema de vulnerabilidade no jquery 3.2.1. (CORE-31183)
* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services e SDK móvel{#mobile}

iOS e Android foram atualizados da seguinte maneira:

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target: Correção de um vazamento de memória.
* Visitor ID Service: The `visitorAppendToURL` and `visitorGetUrlVariablesAsync` APIs no longer double-encode their return values. A codificação dupla fazia com que os valores de retorno dessas apis fossem sinalizados por certas revisões de segurança.

**Android**

* Target: Todas as solicitações agora incluem o cliente e a sessionid nos parâmetros de consulta de URL.
* Mensagens no aplicativo: Correção de um problema em que, quando uma mensagem era acionada com um URL clicado vazio, os aplicativos Android travavam.
* Visitor ID Service: The `Visitor.appendToURL` and `Visitor.getUrlVariablesAsync` APIs no longer double-encode their return values. A codificação dupla fazia com que os valores de retorno dessas apis fossem sinalizados por certas revisões de segurança.

Para obter a documentação do produto, consulte [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Para obter mais informações sobre os Mobile SDKs, consulte: [Android SDK 4.x para Soluções da Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) e [iOS SDK 4.x para Soluções da Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Novos recursos e correções no Adobe Analytics](#aa-features) **(atualizado em July 5 de julho)**
* [Avisos importantes para administradores do Analytics](#aa-notices)

### Novos recursos no [!DNL Analytics] {#aa-features}

Para obter a documentação do produto, consulte [Página inicial de ajuda do Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Componente | Descrição |
| -----------| ---------- |   
| Analysis Workspace - Melhorias na análise de coorte | Novas configurações de Análise de coorte foram adicionadas: <ul><li>Mostrar somente %</li><li>Arredondar % ao inteiro mais próximo</li><li>Mostrar uma linha média % ao longo da parte superior</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. Anteriormente, o período de pesquisa era de um máximo de 6 meses. Isso facilita a comparação com páginas ou campanhas do ano passado, até 18 meses atrás. |
| Novo modelo da Analysis Workspace | Adicionamos um novo modelo chamado &quot;Magento: Marketing e comércio &quot;para a Analysis Workspace. Ela foi projetada especificamente para clientes de comércio eletrônico, mas qualquer varejista pode usá-lo para obter insights exclusivos sobre suas atividades de comércio. |

#### [!DNL Analysis Workspace] correções

* Correção de um problema que fazia com que caracteres multibytes fossem mostrados de cabeça para baixo ao analisar dimensões. (AN-180112)
* Correção de um problema com erros de visualização. Agora, exibimos uma barra de erro vermelha quando ocorre um erro de visualização.(AN-175542)
* Correção de um problema em que os nomes das dimensões apareciam como inglês em ambientes localizados.(AN-178695)

#### [!DNL Analytics] correções

* Correção de um problema que fazia com que o gráfico de linha em um relatório detalhado em tempo real ficasse em branco. (AN-181690)
* Correção de um problema em que, em algumas circunstâncias, partes do histórico de feed de dados não eram exibidas na interface do usuário do Console de administração. (AN-176219)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | A partir de 18 de julho de 2019, os operadores de segmento &quot;contém qualquer um de&quot;, &quot;não contém qualquer um&quot;, e &quot;contêm todos de&quot; e &quot;não contêm todos de&quot; serão limitados a 100 palavras por campo de entrada. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Futuras alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração será aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futura alteração para cálculos de _Total de relatório_ | atualizado em: 9 de julho de 2019 | Em **18 de junho de 2019**, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 18 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the &quot;Typed/Bookmarked&quot; line item for Referrer Type dimension or the &quot;Other&quot; line item for the Device Type dimension. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV da [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas a **[!UICONTROL downloads CSV]** (e **[!UICONTORL Copiar para área de transferência]**) da [!DNL Analysis Workspace] para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da [!DNL Analysis Workspace] | 4 de abril de 2019 | O comando do Console para ativar o depurador da [!DNL Analysis Workspace] será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | 14 de janeiro de 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Desde 11 de fevereiro de 2019, os relatórios do Adobe Analytics não são mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>[!DNL Analytics] Desde 20 de fevereiro de 2019, a coleta de dados do Adobe não é mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará dados do Analytics de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para terem suporte ao TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes de API que usam o Java 8 não deverão ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

### AppMeasurement {#appm}

Lançamento em 15 de julho de 25 19

**JavaScript 2.15.0**

* Adicionado DIL 7.2 para appmeasurememt. (AN-175142)
* Correção de um problema que ocorria quando a optin do serviço da Experience Cloud ID era definida como true e a MID não era gerada na chamada s. t () sem um recarregamento de página. (CORE-30890)

Consulte o [Histórico de versões do AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) para obter um histórico das versões do AppMeasurement nas seguintes plataformas:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight e .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

### Data Workbench {#aa-dwb}

* Updated the help definition for [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) metric syntax documentation. (AN-180527)

Consulte as [Notas de versão do Data Workbench](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/) para obter as informações mais recentes.

## Audience Manager {#aam}

**Correções e aprimoramentos**

* On the [!UICONTROL Segments Overview] page, the width of the segment storage folder is now flexible. Isso permite distinguir entre segmentos com nomes mais longos. (AAM-48400)
* Fixed an issue in [!UICONTROL Algorithmic Models], where moving the **Adjust Reach &amp; Accuracy** slider did not affect the model&#39;s reach or accuracy. (AAM-47996)
* Correção de um problema nos destinos do Analytics em que o botão para baixar um arquivo. csv de segmentos que entravam em conflito com controles de exportação de dados e/ou políticas de compartilhamento de dados de terceiros era interrompido. (AAM-48100)
* Correção de um problema em que os clientes visualizavam erros aleatórios &quot;Acesso negado&quot; ao fazer logon na interface do usuário do Audience Manager. (AAM-47632)

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais implantem os patches mais recentes como um modo de assegurar estabilidade, segurança e desempenho superiores.

### Versões do produto

Informações sobre novos recursos para os seguintes produtos:

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Notas de versão do Cloud Manager 2019.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### Documentação XML 3.4

A solução da Documentação XML 3.4 agora está disponível.

***Notas de versão***

* Suporte adicionado para o AEM 6.5.
* Alterações no editor:
   * Visualização do nível do mapa.
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * Tabelas - forneceu uma opção para selecionar várias células em uma coluna e uma sequência de caracteres ou uni-las.
   * Tabelas - forneceu uma maneira de definir propriedades de colunas da tabela no modo Autor do editor da Web.
   * Tabelas - forneceu uma maneira de ajustar as proporções e o tamanho da coluna em uma tabela padrão.
   * Tabelas - Seleção de linhas e colunas na exibição Autor.
   * Tabelas - estilos e propriedades ativadas (alinhamento, valência) no editor da Web para alinhamento da célula da tabela.
   * Correções de erros na exibição de tags completas, incluindo cenários para copiar e colar, e arrastar e soltar o conteúdo.
   * Mostrar títulos de tópico nas guias do Editor.
   * Resolvidos os problemas de desempenho no editor da Web.
* Transferir linha de base para o conteúdo convertido durante a tradução.
* A condição de transferência é predefinida durante o fluxo de trabalho de tradução.
* Adição da capacidade de aplicar rótulos a todas as dependências de um mapa a partir da linha de base.
* Um botão foi fornecido para baixar o mapa com todas as dependências como um zip.
* APRIMORAMENTOS DE CONVERSÃO XHTML para o seguinte:
   * O nome do DITAMAP gerado agora é idêntico ao nome do arquivo zip carregado.
   * Adicionado suporte para elementos e atributos HTML adicionais.
   * Suporte para assimilação de arquivo ztml-zip simultâneo.
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* Registros de auditoria fornecidos para ver quem reverteu para qual versão e por quê.
* Regeneração do AEM Site:
   * Desativar regeneração para submapas.
   * Fluxos de trabalho de geração de postagem ativados para casos de uso de regeneração.
   * Desative a opção regenerar para um tópico chunked e disponibilize a opção para um tópico pai onde o atributo chunked é aplicado.
* A pesquisa DITA agora funciona em lógica E na pesquisa do AEM Asset.
* Resultados para não exibir os arquivos temporários armazenados na pasta de saída de tradução.
* Guia Linha de base:
   * Melhorias de desempenho ao abrir uma linha de base.
   * Escolha tópicos por data para funcionar no carimbo de data e hora do cliente.
* API para exclusão de rótulos.

#### Manutenção do produto

**AEM 6.2 SP1-CFP20**

AEM 6.2 Service Pack 1-Cumulative Fix Pack 20 (6.2.1.20), lançado em 6 de junho de 2019, é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.2 SP 1 dezembro, 2016.

* [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

O AEM 6.3.3.5, lançado em 3 de julho de 2019, é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.3 de abril de 2017.

* [Notas de versão](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

O AEM 6.4.5.0, lançado em 3 de julho de 2019, é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.4 em abril de 2018.

* [Notas de versão](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

O AEM 6.5.1.0, lançado em 3 de julho de 2019, é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.5 em abril de 2019.

* [Notas de versão](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Autoajuda

**Atualização de invalidação do cache AEM**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

### Recursos adicionais

* [Página inicial de Aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notas de versão do Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

Para obter as notas de versão, consulte:

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

Para obter a documentação do produto, consulte:

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [ Notas de versão](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

Para obter informações sobre as notas de versão de Magento Commerce e Magento Open Source, consulte:

* [Notas de versão do Magento Open Source 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Notas de versão do Magento Commerce 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
