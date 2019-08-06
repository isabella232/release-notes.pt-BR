---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: notas de versão
last-update: agosto de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 09b88aee612dfb84e3810d1f75da703d3d4c233d

---


# Acesso antecipado - Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!IMPORTANT]
>
>Esta página apresenta conteúdo de pré-lançamento e está sujeito a alterações até o lançamento da versão planejada.

>[!NOTE]
>
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: agosto de 2019**

* [Plataforma de experiência e administração](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)

## [!UICONTROL Plataforma de experiência] e administração {#platform}

Notas de versão da interface [!UICONTROL da Experience Platform], da interface da Experience Cloud, da administração de produtos, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Interface da Experience Cloud](#core-services)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (todos os produtos da Adobe)

### Interface da Experience Cloud {#core-services}

* Correção de um problema crítico no logon da Experience Cloud que levou ao logout da sessão para alguns usuários. (MCUI-6908)
* Atualização do logon da Experience Cloud para melhorar o desempenho e reduzir a latência. (MCUI -6854, MCUI -6869, MCUI -6883)
* Interface atualizada de forma uniforme. (MCUI -6861, MCUI -6911, MCUI -6862)
* Correção de um problema com [!UICONTROL Acionadores da Experience Cloud] que resultava na interpretação incorreta da cláusula _Curtir_ na definição [!UICONTROL Acionar] . (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, melhorias e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| Suporte para configurações de cookie do samesite | A configuração de cookie [samesite](https://web.dev/samesite-cookies-explained) será adicionada a todos os conjuntos de cookies do Analytics. Essa alteração permite que você seja compatível com as alterações do Chrome exigindo o campo de cookie samesite. Os cookies do Analytics `none`serão padronizados. Se você tiver usado exclusivamente um domínio próprio (por exemplo, stats.domain.com), você pode ter o Adobe clientcare configurado para `lax` a configuração para domínios de coleção próprios. |
| Área de trabalho: Aumentar limite de item para o filtro suspenso de 50 a 200 | Aumentamos o limite de itens que podem ser colocados em um filtro suspenso de 50 a 200. Esse aprimoramento acomoda uma variedade de casos de uso, como adicionar todos os países (195) a um filtro, ou todos os estados e municípios dos EUA (52). |
| IQ de atribuição ativado para métricas A 4 T | Ativamos duas métricas do Analytics para Target (A 4 T) para Atribuição IQ: Impressões da atividade e conversão de atividade. Na Analysis Workspace até o momento, essas métricas foram infladas em comparação com o Relatórios e análises. Com essa alteração, os usuários podem aplicar um modelo de atribuição "mesmo toque", que colocará a Analysis Workspace em conformidade com os Relatórios e análises. |

#### Correções

* Correção de um problema com o texto exibido em relatórios em tempo real quando no modo de tela cheia. (AN-183168)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | Esses limites não são novos, mas foram adicionados à documentação [aqui](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Futuras alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração será aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futura alteração para cálculos de _Total de relatório_ | atualizado em: 9 de julho de 2019 | Em **18 de junho de 2019**, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 18 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, os segmentos que usam a lógica _existe_ ou _não existe_ podem ver resultados diferentes para algumas dimensões após essa mudança, especificamente dimensões em que _Não especificado_ tem um nome especial, como o item de linha "Digitado/Marcado" da dimensão Tipo de referenciador ou o item de linha "Outro" da dimensão Tipo de dispositivo. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV da [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas a **[!UICONTROL downloads CSV]** (e **[!UICONTORL Copiar para área de transferência]**) da [!DNL Analysis Workspace] para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da[!DNL Analysis Workspace] | 4 de abril de 2019 | O comando do Console para ativar o depurador da [!DNL Analysis Workspace] será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Links encurtados de [!DNL Analytics] relatórios do | 14 de janeiro de 2019 | Os links encurtados de [!DNL Analytics] relatórios do que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Desde 11 de fevereiro de 2019, os relatórios do Adobe Analytics não são mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> Desde 20 de fevereiro de 2019, a coleta de dados do Adobe Analytics não é mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará [!DNL Analytics] dados do de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para terem suporte ao TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes de API que usam o Java 8 não deverão ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

### AppMeasurement {#appm}

[!UICONTROL Versões do appmeasurement] 2.16.0 em 8 de agosto de 2019.

| Recurso | Descrição |
| -----------| ---------- |
| `sendBeacon` suporte para links de saída | Suporte implementado `sendBeacon` no [!UICONTROL appmeasurement] para links de saída. Isso melhorará o rastreamento de links de saída e provavelmente resultará em maior tráfego. |
| Valores de ECID/fid | Os valores ECID/fid são agora armazenados em cache na primeira ocorrência, mesmo se as configurações optin forem alteradas. |
| DIL 9.3 | Módulo de gerenciamento de público-alvo atualizado para DIL 9.3 |
| Rastreamento de alcance de rolagem | Foi exposto em s. activitymap. trackscrollalcance para ativar ou desativar o rastreamento de alcance de rolagem. |
| Serviço de ID do visitante 4.4.0 | Appmeasurement atualizado para usar o Serviço de ID do visitante 4.4.0. |

#### Correções

* Correção de um bug na fila appmeasurement que ocorria antes de isreadytotrack ser verdadeiro.

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

## Audience Manager {#aam}

**Correções e melhorias**

* A guia Administração agora aparece somente para contas de usuário com privilégios administrativos (AAM -48557).
* A API de usuários da lista agora retorna os detalhes completos do usuário (AAM -48662).
* Agora é possível redimensionar a lista de pastas de características (AAM -48800).
* Diversas otimizações de acessibilidade da interface do usuário (AAM -48865, AAM -48933).
* Carregando otimizações para as páginas Administração e Fontes de dados (AAM -48514).

## [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Adobe Campaign Standard

[Versão do Campaign Standard 19.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Recurso | Descrição |
| -----------| ---------- |  
| Atividade de API externa (Beta público) | Para personalização mais profunda, a Atividade de API externa permite que você coloque dados de sistemas externos em um fluxo de trabalho por meio de uma chamada REST API. Os pontos finais REST podem ser um sistema de gerenciamento de cliente, Adobe I/O Runpoint ou terminal REST da Adobe Experience Cloud (por exemplo, Plataforma de dados, Target, Analytics, Campanha). No momento, esse recurso está em beta público. Para obter mais informações, consulte a documentação [detalhada](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) e o vídeo [passo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html)a passo. |
| Relatório sobre o segmento do fluxo de trabalho | Esse recurso permite que os profissionais de marketing analisem o desempenho de entrega por código de segmento. Quando você cria um fluxo de trabalho e usa uma atividade de segmentação para atribuir segmentos à população de entrega, esses segmentos agora podem entrar na mesma entrega. Isso permite exibir as estatísticas de aberturas/cliques com base em vários segmentos em uma única entrega. Para obter mais informações, consulte a documentação [detalhada](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) e o vídeo [passo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html)a passo. |

### Adobe Campaign Classic

[Atualização do Campaign Classic 19.1.3](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - compilação 9031

### Painel de controle do Adobe Campaign

[Os novos recursos do Painel de controle](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) incluem a capacidade de adicionar urls que o Campaign Classic conecta-se a transferências de dados/arquivos.

Observe que o Painel [!UICONTROL de controle] está disponível para clientes do Adobe Campaign Classic e do Adobe Campaign Standard hospedados em AWS. Nenhuma atualização é necessária para acessar o Painel de controle.

### Recursos adicionais

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)