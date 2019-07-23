---
title: Notas de versão técnica da Adobe Experience Cloud
description: Notas de versão de doc técnico da Experience Cloud july 019
doc-type: notas de versão
last-update: Julho de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 41b4cbb1b93fe857c80cebd631a785e234e2ce07

---


# Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 18 de julho de 2019**

* [Serviços principais e administração da Experience Cloud](#experiencecloud)
* [!DNL Analytics](#analytics) - **(atualizado em 15 de julho)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Principais serviços e administração {#experiencecloud}

Notas de versão da interface da Experience Cloud, incluindo serviços essenciais da [!UICONTROL plataforma] e administração de produtos.

* [Serviço da Experience Cloud ID](#ecid)
* [Mobile Services e SDK móvel](#mobile)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](#security)

### Serviço da Experience Cloud ID {#ecid}

**Correções e atualizações**

* `cookieDomain` atualização de configuração: a biblioteca atribuirá automaticamente um domínio de cookie de nível superior quando o `cookieDomain` no `initConfig` não estiver configurado. (CORE-29223)
* Correção de um problema do `getVisitorValue` no `localVisitor`. (CORE-31287)
* Correção de uma inconsistência do `MCOPTOUT` valor no visitante principal versus o visitante secundário do iframe do `getVisitorValue` método. (CORE-29719)
* Correção de um problema de vulnerabilidade no jQuery 3.2.1. (CORE-31183)
* Atualização de aceitação: adição de `optIn.off` para cancelar a inscrição nos eventos.
* Correção de um problema relacionado à `setTimeout` função. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services e SDK móvel {#mobile}

O iOS e o Android foram atualizados da seguinte maneira:

**iOS**

* Adobe Target: todas as solicitações agora incluem o cliente e o `sessionId` nos parâmetros de consulta de URL.
* Adobe Target: correção de um vazamento de memória.
* Serviço de ID do visitante: as APIs `visitorAppendToURL` e `visitorGetUrlVariablesAsync` não codificam mais duas vezes seus valores de retorno. A codificação dupla fazia com que os valores de retorno dessas APIs fossem sinalizados por determinadas revisões de segurança.

**Android**

* Target: todas as solicitações agora incluem o cliente e sessionId nos parâmetros de consulta de URL.
* Mensagens no aplicativo: correção de um problema em que, quando uma mensagem era acionada com um URL de clickthrough vazio, os aplicativos Android travavam.
* Serviço de ID do visitante: as APIs `Visitor.appendToURL` e `Visitor.getUrlVariablesAsync` não codificam mais duas vezes seus valores de retorno. A codificação dupla fazia com que os valores de retorno dessas APIs fossem sinalizados por determinadas revisões de segurança.

Para obter a documentação do produto, consulte [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Para obter mais informações sobre os Mobile SDKs, consulte: [Android SDK 4.x para Soluções da Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) e [iOS SDK 4.x para Soluções da Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Boletins e conselhos de segurança {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Novos recursos e correções no Adobe Analytics](#aa-features) **(atualizado em 15 de julho)**
* [Avisos importantes para administradores do Analytics](#aa-notices)

### Novos recursos no [!DNL Analytics] {#aa-features}

Para obter a documentação do produto, consulte [Página inicial de ajuda do Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Componente | Descrição |
| -----------| ---------- |   
| Analysis Workspace - Melhorias na análise de coorte | New [Cohort Analysis settings](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/cohort-table/t-cohort.html) have been added: <ul><li>Mostrar somente a porcentagem</li><li>Arredondar porcentagem ao inteiro mais próximo</li><li>Mostrar uma linha de porcentagem média</li></ul> |
| Analysis Workspace | No painel à esquerda, os usuários agora têm a opção de _Mostrar itens dos últimos 18 meses_. Anteriormente, o período de pesquisa era de no máximo 6 meses. Isso facilita a comparação com páginas ou campanhas do ano passado, até 18 meses atrás. |
| Novo modelo do Analysis Workspace | We added a new template called ["Magento: Marketing &amp; Commerce"](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html) to Analysis Workspace. Ele foi projetado especificamente para clientes de comércio eletrônico do Magento, mas qualquer varejista pode usá-lo para obter informações exclusivas sobre suas atividades de comércio. |

#### [!DNL Analysis Workspace] correções

* Correção de um problema que fazia com que caracteres com vários bytes fossem mostrados de cabeça para baixo ao detalhar as dimensões. (AN-180112)
* Correção de um problema com erros de visualização. Agora, exibimos uma barra de erro vermelha quando ocorre um erro de visualização.(AN-175542)
* Correção de um problema em que os nomes das dimensões apareciam em inglês em ambientes localizados.(AN-178695)

#### [!DNL Analytics] correções

* Correção de um problema que fazia com que o gráfico de linhas em um relatório detalhado em tempo real ficasse em branco. (AN-181690)
* Correção de um problema em que, em algumas circunstâncias, partes do histórico do feed de dados não eram exibidas na interface do usuário do Admin Console. (AN-176219)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | A partir de 18 de julho de 2019, os operadores de segmento "contém qualquer um de", "não contém qualquer um", e "contêm todos de" e "não contêm todos de" serão limitados a 100 palavras por campo de entrada. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Futuras alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração será aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futura alteração para cálculos de _Total de relatório_ | atualizado em: 9 de julho de 2019 | Em **18 de junho de 2019**, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 18 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, os segmentos que usam a lógica _existe_ ou _não existe_ podem ver resultados diferentes para algumas dimensões após essa mudança, especificamente dimensões em que _Não especificado_ tem um nome especial, como o item de linha "Digitado/Marcado" da dimensão Tipo de referenciador ou o item de linha "Outro" da dimensão Tipo de dispositivo. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV da [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas a **[!UICONTROL downloads CSV]** (e **[!UICONTORL Copiar para área de transferência]**) da [!DNL Analysis Workspace] para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da [!DNL Analysis Workspace] | 4 de abril de 2019 | O comando do Console para ativar o depurador da [!DNL Analysis Workspace] será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Links encurtados de [!DNL Analytics] relatórios do | 14 de janeiro de 2019 | Os links encurtados de [!DNL Analytics] relatórios do que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Desde 11 de fevereiro de 2019, os relatórios do Adobe Analytics não são mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Desde 20 de fevereiro de 2019, a coleta de dados do Adobe Analytics não é mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará [!DNL Analytics] dados do de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para terem suporte ao TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes de API que usam o Java 8 não deverão ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

### AppMeasurement {#appm}

Lançado em 15 de julho de 2019:

**AppMeasurement para JavaScript 2.15.0**

* Adicionado rastreamento de alcance de tolagem do Activity Map à extensão do Activity Map (AN-172949)
* DIL 9.2 adicionado ao AppMeasurement. (AN-182472)

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

* Na página [!UICONTROL Visão geral de segmentos], a largura da pasta de armazenamento do segmento agora é flexível. Isso permite distinguir entre segmentos com nomes mais longos. (AAM-48400)
* Correção de um problema em [!UICONTROL Modelos algorítmicos], em que mover o controle deslizante **Ajustar alcance e precisão** não afetava o alcance ou a precisão do modelo. (AAM-47996)
* Correção de um problema nos destinos do Analytics em que o botão para baixar um arquivo .csv de segmentos que entravam em conflito com controles de exportação de dados e/ou políticas de compartilhamento de dados de terceiros era interrompido. (AAM-48100)
* Correção de um problema em que os clientes viam erros "Acesso negado" aleatórios ao fazer logon na interface do usuário do Audience Manager. (AAM-47632)

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais implantem os patches mais recentes como um modo de assegurar estabilidade, segurança e desempenho superiores.

### Versões do produto

Informações sobre novos recursos dos seguintes produtos:

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Notas de versão do Cloud Manager 2019.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### Documentação XML 3.4

A solução da Documentação XML 3.4 agora está disponível.

***Notas de versão***

* Suporte adicionado para o AEM 6.5.
* Alterações no editor:
   * Visualização do nível do mapa.
   * Tabelas - forneceu a opção de copiar uma linha `entry` ou `complete` em uma tabela usando copiar e colar.
   * Tabelas - forneceu a opção para selecionar várias células em uma coluna e estendê-las ou uni-las.
   * Tabelas - forneceu uma maneira de definir propriedades de colunas da tabela no modo Autor do editor da Web.
   * Tabelas - forneceu uma maneira de ajustar as proporções e o tamanho da coluna em uma tabela padrão.
   * Tabelas - seleção de linhas e colunas na exibição Autor.
   * Tabelas - ativação de estilos e propriedades (alinhamento, valência) no editor da Web para alinhamento da célula da tabela.
   * Correções de erros na exibição Tags completas, incluindo cenários para copiar e colar e arrastar e soltar o conteúdo.
   * Mostrar títulos de tópico nas guias do Editor.
   * Solução de problemas de desempenho no editor da Web.
* Transferir linha de base para o conteúdo traduzido durante a tradução.
* A condição de transferência é predefinida durante o fluxo de trabalho de tradução.
* Adição da capacidade de aplicar rótulos a todos os dependentes de um mapa a partir da linha de base.
* Um botão foi fornecido para baixar o mapa com todos os dependentes como um zip.
* Melhorias na conversão de XHTML em DITA para o seguinte:
   * O nome do DITAMAP gerado agora é idêntico ao nome do arquivo zip carregado.
   * Adição do suporte para elementos e atributos HTML adicionais.
   * Suporte para assimilação de arquivo html-zip simultâneo.
   * A hierarquia de subpasta na qual o zip é carregado (*no caminho de entrada, como configurado em h2d_io.xml*), é retida para a saída gerada (*no caminho de saída configurado*).
* Registros de auditoria fornecidos para ver quem reverteu para qual versão e por quê.
* Regeneração do AEM Site:
   * Desativação da regeneração para submapas.
   * Ativação de fluxos de trabalho de pós geração para casos de uso de regeneração.
   * Desativação da opção para regenerar um tópico fragmentado e disponibilização da opção de um tópico principal onde o atributo fragmentado é aplicado.
* A pesquisa DITA agora funciona na lógica AND na pesquisa do AEM Asset.
* Resultados para não exibir os arquivos temporários armazenados na pasta de saída da tradução.
* Guia Linha de base:
   * Aprimoramentos de desempenho ao abrir uma linha de base.
   * Escolha de tópicos por data para funcionar no carimbo de data e hora do cliente.
* API para exclusão de rótulos.

#### Manutenção do produto

**AEM 6.2 SP1-CFP20**

O AEM 6.2 Service Pack 1–Cumulative Fix Pack 20 (6.2.1.20), lançado 6 de junho de 2019, é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.2 SP1 em dezembro de 2016.

* [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

O AEM 6.3.3.5, lançado 3 de julho de 2019, é uma atualização importante que inclui correções essenciais para o cliente, lançadas desde a disponibilização geral do AEM 6.3 em abril de 2017.

* [Notas de versão](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

O AEM 6.4.5.0, lançado 3 de julho de 2019, é uma atualização importante que inclui correções essenciais para o cliente, lançadas desde a disponibilização geral do AEM 6.4 em abril de 2018.

* [Notas de versão](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

O AEM 6.5.1.0, lançado 3 de julho de 2019, é uma atualização importante que inclui correções essenciais para o cliente, lançadas desde a disponibilização geral do AEM 6.5 em abril de 2019.

* [Notas de versão](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Autoajuda

**Atualização de invalidação do cache do AEM**

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

Para ver as notas de versão, consulte:

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

Para obter a documentação do produto, consulte:

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [ Notas de versão](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release information about Target.

## Magento {#magento}

Para obter informações sobre as notas de versão do Magento Commerce e do Magento Open Source, consulte:

* [Notas de versão do Magento Open Source 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Notas de versão do Magento Commerce 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
