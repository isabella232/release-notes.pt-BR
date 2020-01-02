---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8a895d104abd20910aa37ec2ec3b6eeaccd8c461

---


# REVISÃO INTERNA - Notas de versão da Adobe Experience Cloud - janeiro de 2020

Novos recursos e correções na Adobe Experience Cloud.

> [!NOTE] Assine a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por e-mail sobre versões futuras. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: Janeiro de 2020**

* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)
* [!DNL Advertising Cloud](#adcloud) (Atualizado em 8/11)

Procurando a página principal da ajuda? Consulte [Documentação da Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Status.adobe.com

Usando sua ID da Adobe, você pode assinar notificações de eventos de status, com base nos produtos, na região e nas preferências do evento.

| Recurso | Descrição |
| -----------| ---------- |
| Assinar notificações por email em tempo real | <ul><li>Suporte para Experience Cloud, Creative Cloud, Document Cloud, AEP e Adobe Services</li><li>Suporte para preferências de região e tipo de evento</li><li>Suporte UX para superfícies Web, móveis e tablets</li></ul> |
| Gerenciamento de preferências de notificações | <ul><li>Editar e salvar preferências de notificação a qualquer momento</li><li>Cancelar a assinatura das notificações a qualquer momento</li><li>Item</li></ul> |
| Entrega de email personalizada e mais rápida | <ul><li>As notificações de eventos são enviadas assim que os CSOs e os CMR são abertos, atualizados ou fechados</li><li>Receba somente as notificações de evento relevantes que correspondem às preferências configuradas</li><li>Recebidas notificações localizadas com base no idioma configurado nas preferências de sua conta</li></ul> |
| Notificações personalizadas no produto | Os eventos que correspondem às preferências de notificação e aos direitos do produto são exibidos no painel Anúncio. |

## Interface da Experience Cloud {#ecloud}

Notas de versão da interface da Experience Cloud e administração de produtos.

* Item
* Item

Para consultar a documentação do produto, acesse [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Notas de versão da Experience Plataform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (Todos os produtos da Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para obter as notas de versão e a documentação do produto.

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices) (**Atualizado em 18 de dezembro de 2019**)
* [AppMeasurement](#appm)

Para obter a documentação do produto, consulte a [Página inicial de ajuda do Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- | 
|  |  |

#### Correções

* Correção
* Correção

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Novo domínio do Adobe Analytics | 18 de dez de 2019 | Em 16 de janeiro de 2020, o Adobe Analytics mudará para um novo domínio - https://experience.adobe.com/analytics. Essa alteração pode causar problemas de cookie ao carregar o Analytics no Safari. Ao desmarcar &quot;Impedir rastreamento entre sites&quot; nas Preferências de privacidade do Safari, os cookies serão ativados nos domínios (e em todas as experiências entre sites) e o Analytics poderá funcionar nesse novo domínio da Adobe Experience Cloud. Os usuários podem usar outros navegadores sem problemas, pois isso afeta apenas os usuários do Safari. |
| EOL (fim da vida útil) da opção **[!UICONTROL Exibir arquivo]** | 30 de outubro de 2019 | Anúncio do fim da vida útil da opção **[!UICONTROL Exibir arquivo]**no Gerenciador do painel (**[!UICONTROL  Componentes > Painéis]**) para janeiro de 2020. |
| EOL (fim da vida útil) da opção **[!UICONTROL Impor restrições de logon de IP]** | 30 de outubro de 2019 | Anúncio do fim da vida útil da funcionalidade de lista de permissões de logon de IP (**[!UICONTROL Impor restrições de logon de IP]**) no menu**[!UICONTROL  Admin > Configurações da empresa > Segurança]**. |
| Atualização do controle do atributo SameSite em cookies | 15 de outubro de 2019 | Em agosto de 2019, a Adobe anunciou a adição da configuração de cookie SameSite a todos os cookies definidos pelo Analytics. A lógica foi atualizada para os seguintes casos:<ul><li>Todos os cookies de terceiros não baseados no Webkit que não tiverem o atributo SameSite definido como `none`.</li><li>Todos os outros cookies que não tiverem definido o atributo SameSite.</li></ul> |
| Fim de suporte para TLS 1.1 | 3 de outubro de 2019 | Até 31 de março de 2020, o Adobe Analytics removerá o suporte ao TLS 1.1. Essa alteração faz parte de nossos esforços contínuos para manter os mais altos padrões de segurança e promover a segurança dos dados do cliente. |
| Ponto de FTP Broker em San Jose usado para Londres e Singapura | Julho de 2020 | Para clientes em Londres e Singapura, não apoiaremos mais a intermediação de dados entre Londres ou Singapura e o data center de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Cingapura, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Atualização dos totais da tabela de forma livre da Analysis Workspace | 12 de setembro de 2019 | Em outubro de 2019, as linhas de total da tabela de forma livre começarão a contabilizar para [filtros de relatório](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) foram aplicadas. Até hoje, os totais eram contabilizados somente para segmentação. Com essa alteração, as visualizações dependentes serão atualizadas (ex: visualizações vinculadas de [!UICONTROL Número de resumo]), bem como dados CSV e PDF exportados. |
| Alteração futura em relação ao campo `createDate` para usuários do Analytics | 30 de agosto de 2019 | Em outubro ou novembro de 2019, o campo `createDate` para os usuários do Analytics será atualizado da Hora do Pacífico dos EUA para um valor de data/hora corretamente formatado com as informações de fuso horário. (AN-183468) |
| Suporte para deslocamentos de fuso horário históricos | 8 de agosto de 2019 | O Analytics agora manipular automaticamente deslocamentos de fuso horário para ocorrências com carimbo de data e hora. Após essa mudança em 8 de agosto, os sistemas que carregam dados para o processamento histórico não precisarão mais ajustar para deslocamentos de fuso horário antes de enviar os dados. |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | Esses limites não são novos, mas foram adicionados à documentação [aqui](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | A partir de 18 de julho de 2019, os operadores de segmento _contêm um dos_, _não contém nenhum dos_, _contém todos os_ e _não contém nenhum dos_ serão limitados a 100 palavras por campo de entrada. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Alterações de suporte das Classificações **[!UICONTROL ativadas por data]**e**[!UICONTROL  numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração foi aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Alteração de cálculos de _Total de relatório_ | Atualizado em: 9 de julho de 2019 | Em **18 de junho de 2019**, o Adobe Analytics tornou os cálculos de _Total de relatório_ consistentes em todas as dimensões e métricas. Isso resultou em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 18 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, os segmentos que usam a lógica _existe_ ou _não existe_ podem ver resultados diferentes para algumas dimensões após essa mudança, especificamente dimensões em que _Não especificado_ tem um nome especial, como o item de linha &quot;Digitado/Marcado&quot; da dimensão Tipo de referenciador ou o item de linha &quot;Outro&quot; da dimensão Tipo de dispositivo. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios.<br>**Observação **: Este cálculo de Total _de_relatórios agora é chamado de Total __geral. Consulte &quot;Analysis Workspace: Atualizar para totais da tabela de forma livre&quot; acima. |
| Atualização de downloads em CSV na Analysis Workspace | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas aos **[!UICONTROL downloads CSV]**(e**[!UICONTORL  Copiar para área de transferência]**) da Analysis Workspace para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes > Configurações de relatórios > Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
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

### Novos recursos, melhorias e correções no Audience Manager {#aam-new-features}

| Recurso | Descrição |
|--- |----|
|  |  |

### Melhorias {#aam-enhancements}

Para obter mais informações, entre em contato com seu consultor do Audience Manager ou com o Atendimento ao cliente.

### Correções e melhorias {#aam-fixes-and-improvements}

* Correção
* Correção

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Versões do produto

### Autoajuda

* **Atualizações da documentação do AEM**

   Conheça as alterações importantes na documentação e as atualizações do Adobe Experience Manager nos últimos três meses.

   Consulte [Documentação do AEM: atualizações recentes](https://helpx.adobe.com/experience-manager/documentation-updates.html).

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

| Exibir | Recurso |
|------|---------|
|  |  |
