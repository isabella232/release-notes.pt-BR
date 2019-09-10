---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: notas de versão
last-update: Setembro de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: fdcc0f53ea326b9c440e511ca5968749e68861cd

---


# Acesso antecipado - Setembro de 2019 - Notas de versão da Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!IMPORTANT]
>
>Esta página apresenta conteúdo de pré-lançamento e está sujeita a alterações até o lançamento em 12 de setembro de 2019.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

## Data de lançamento: 12 de setembro de 2019

* [Interface da Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)

## Interface da Experience Cloud {#ecloud}

Notas de versão da interface da Experience Cloud e administração de produtos.

* Correção de uma vulnerabilidade de segurança para incluir cabeçalhos HTTP recomendados. (MCUI-9942)
* Correção de um problema ao alternar entre as empresas de logon do Analytics. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de versão da Experience Platform, da Experience Platform Launch, do Serviço de identidade e dos marcadores de segurança.

* [Experience Platform Launch](#launch)
* [Mobile Services e SDK móvel](#mobile)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (todos os produtos da Adobe)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services e SDK móvel {#mobile}

Data de lançamento: **26 de setembro**

**iOS (4.18.8)**

* Correção de um erro em que os dados do SDK são sincronizados a o aplicativo watchOS emparelhado em cada chamada do Analytics.
* Correção de um erro em que a carga de click-through de push não podia ser usada como característica das mensagens no aplicativo.
* Atualização para APIs de estrutura de notificação do usuário em vez da API UILocalNotification, que foi descontinuada do iOS 10 em diante.
* Atualização na WKWebView em vez de UIWebView, que foi descontinuada do iOS 12 em diante.

**Android 4.17.10**

* Adição do suporte para tags de idioma BCP 47.

**Unity**

* Plug-in atualizado para 4.18.7 para iOS e 4.17.9 para Android

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| **IQ da jornada: análise entre dispositivos** | Em setembro de 2019, o Adobe Analytics está apresentando um novo recurso poderoso chamado Jornada IQ: Análise entre dispositivos. (Observe que este recurso está disponível somente para clientes do Analytics Ultimate.) A Análise entre dispositivos (CDA) transforma o Adobe Analytics de centrado em um dispositivo para uma ferramenta de análise centrada em pessoas. Usando a CDA, você pode responder a perguntas como: <ul><li>Quantas pessoas interagem com minha marca? Quantos e quais tipos de dispositivos eles usam? Como eles se sobrepõem?</li><li>Com que frequência as pessoas iniciam uma tarefa em um dispositivo móvel e depois movem para um PC de desktop para concluí-la? Os click-throughs da campanha direcionados a um dispositivo levam para a conversão em outro lugar?</li><li>O quanto muda minha compreensão da eficácia da campanha se eu levar em conta as jornadas entre dispositivos? Como a minha análise de funil muda?</li><li>Quais são os caminhos mais comuns que os usuários fazem de um dispositivo para outro? Onde eles desistem? Onde eles têm sucesso?</li><li>Como o comportamento de usuários com vários dispositivos difere dos usuários com um único dispositivo?</li></ul><br/>Para saber mais, visite [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/). |
| **Arquitetura de classificações atualizada** | A partir de setembro, uma atualização na arquitetura de Classificações será migrada para os clientes ao longo de um período de vários meses. A versão de setembro inclui a migração para um pequeno número de participantes antecipados.<br/>A atualização reduz significativamente o tempo necessário para que os uploads (incluindo a lógica da regra) sejam importados/assimilados e disponibilizados para relatório. |

#### Correções

* Correção de um problema com os serviços principais de [!UICONTROL Pessoas] e [!UICONTROL Ofertas] que não eram acessíveis no menu principal da Experience Cloud. (AN-184294)
* Correção de um problema com o painel à esquerda na [!UICONTROL Analysis Workspace] que oscila entre ter e não ter uma barra de rolagem, o que causava um efeito de oscilação. (AN-183904)
* Correção de problemas com o relatório de erros. Você começará a ver mensagens de erro mais específicas em vez de apenas o indicador de erro vermelho. Mais especificamente, isso deve ajudá-lo a entender quando o problema é causado por carga pesada, por um erro ou por criar uma solicitação de relatório muito complexa. (AN -184135) [Mais…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* Correção de um problema que impedia o download bem-sucedido dos relatórios de fallout nos formatos `.pdf/.xls/.rtf`. (AN-183165)
* Correção de problemas ao fazer logon na Experience Cloud e alternar para diferentes soluções da Experience Cloud ou alternar para outra empresa de logon. (AN-183376)
* Correção de um problema com a transferência de ativos de projetos agendados que não funcionavam corretamente. Agora os grupos são gerenciados no [!UICONTROL Admin Console], portanto, não os copiamos entre os usuários ao transferir ativos. (AN-183751)
* Correção de um problema com a exclusão de relatórios agendados cujos proprietários foram excluídos. A partir de agora, uma notificação será enviada para o Administrador (que realizou a operação de exclusão) quando o proprietário do agendamento não existir mais. (AN-181000)

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Atualização dos totais da tabela de forma livre da Analysis Workspace | 12 de setembro de 2019 | Em outubro de 2019, as linhas do total da tabela de forma livre começarão a contabilidade para [filtros de relatório](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) aplicados. Até hoje, os totais eram contabilizados somente para segmentação. Com essa alteração, as visualizações dependentes serão atualizadas (ex: visualizações vinculadas de [!UICONTROL Número de resumo]), bem como dados CSV e PDF exportados. |
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
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Não há mais suporte para TLS 1.0 no |

### [!DNL AppMeasurement] {#appm}

Consulte [appmeasurement para notas de versão do Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Novos recursos, melhorias e correções no Audience Manager.

### Novos recursos e melhorias {#aam-features}

| Recurso | Descrição |
| -----------| ---------- |  
| **[[! Destinos com base em pessoas]](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNL People-Based Destinations] é um complemento pago do Audience Manager que ajuda a ativar segmentos de público-alvo primários em ambientes baseados em pessoas, como o Facebook, usando identificadores com hash, como endereços de email. |
| **[Configuração de públicos-alvo adaptados do Twitter como destino baseado em dispositivo autoatendimento](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | Estamos migrando os destinos do Twitter para um modelo de configuração de autoatendimento. Este artigo explica o que você precisa fazer nas integrações existentes do Twitter para continuar trabalhando após a migração. |
| **[Exemplos de cobrança do Audience Marketplace](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | Adicionamos um novo exemplo, Caso 3, em que detalhamos como o faturamento funciona para segmentos com casos de uso de ativação e de modelagem. |

**Correções e melhorias**

* Corrigimos um erro em que os usuários não conseguiam editar os destinos do Adobe Analytics para mapear segmentos manualmente. (AAM-49323)
* Corrigimos um erro em que os feeds duplicados do Audience Marketplace eram originados de uma única ID de fonte de dados. Deve haver um mapeamento 1:1 entre fontes de dados e feeds [!DNL Marketplace]. (AAM-48504)
* Melhoramos o fluxo de trabalho de criação de características e segmentos. Agora é possível filtrar a fonte de dados para armazenar a característica ou o segmento, para excluir fontes de dados que não são do Audience Manager (por exemplo, fontes de dados do conjunto de relatórios do Adobe Analytics). (AAM-35899)
* Corrigimos um problema na API das fontes de dados em que a definição do parâmetro de consulta `ExcludeReportSuites=true` não excluía fontes de dados do conjunto de relatórios do Adobe Analytics. (AAM-48545)
* Fizemos diversas melhorias relacionadas à acessibilidade da Interface do usuário do Audience Manager. (AAM-49024) and (AAM-49031)

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Versão do produto

**Cloud Manager 2019.8.0**

A versão 2019.8.0 do Cloud Manager corrige uma variedade de pequenos erros, melhora o desempenho da criação e adiciona suporte para pacotes de conteúdo construído seletivos.

* [Notas de versão do Cloud Manager 2019.8.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Manutenção do produto

**Roteiro da versão de manutenção do AEM**

Consulte o roteiro da versão de manutenção do AEM, conforme publicado [aqui](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html).

### Autoajuda

**Pré-lançamento do Asset Link 1.1**

* [Sobre o pré-lançamento do link de ativos da Adobe](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [Configuração do AEM para o link de ativos da Adobe para pré-lançamento](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

O AEM Desktop App 2.0 para MAC foi lançado em 30 de agosto de 2019. O AEM Desktop App 2.0 para Windows será lançado no começo de setembro.

Acesse a documentação e baixe [aqui](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html).

**Tags inteligentes do Assets**

Saiba como atualizar um certificado depois que ele expirar [aqui](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate).

**Guia do usuário do AEM 6.5 Screens**

Agora está disponível uma nova documentação sobre as _Diretrizes de implantação de rede_. Consulte o [Guia do usuário do ](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html).

**Serviço de conversão de formulários automatizado**

A documentação do serviço de conversão automatizada dos formulários do AEM Forms agora está disponível. Consulte [Introdução ao serviço Automatizado de conversão de formulários](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html).

### Comunidade

**Webinários do AEM Skill Builder**

* [Sites do Adobe Experience Manager](https://forums.adobe.com/thread/2647742)

   | Webinário | Data |
   | -----------| ---------- |  
   | _Criação de experiências na Web_ | 27 de agosto de 2019 |
   | _Pesquisar e navegar pelo conteúdo_ | 03 de setembro de 2019 |
   | _Gerenciar todo o conteúdo em evolução facilmente_ | 10 de setembro de 2019 |
   | _Experiências fluídas_ | 17 de setembro de 2019 |
   | _Criar e gerenciar multi-língue, multi-nacional para projetar uma estrutura global de site_ | 24 de setembro de 2019 |

* [Ativos Adobe Experience Manager](https://forums.adobe.com/thread/2647743)

   | Webinário | Data |
   | -----------| ---------- |  
   | _Estrutura de pastas e pesquisa_ | 29 de agosto de 2019 |
   | _Metadados_ | 05 de setembro de 2019 |
   | _Brand Portal_ | 12 de setembro de 2019 |
   | _Mídia dinâmica_ | 19 de setembro de 2019 |
   | _Asset Link_ | 26 de setembro de 2019 |

* [Formulários do Adobe Experience Manager](https://forums.adobe.com/thread/2647744)

   | Webinário | Data |
   | -----------| ---------- |  
   | _Forms 101_ | 04 de setembro de 2019 |
   | _Conectar formulários aos bancos de dados, Criar fluxos de trabalho e Integrar formulários com assinaturas eletrônicas_ | 11 de setembro de 2019 |
   | _Criar comunicações interativas e prontas para impressão responsivas para dispositivos móveis na Web_ | 25 de setembro de 2019 |

* [Gerenciador da Adobe Experience Manager Cloud](https://forums.adobe.com/thread/2647745)

   | Webinário | Data |
   | -----------| ---------- |  
   | _Práticas recomendadas de teste - Compilação, monitoramento, auditoria e insights com o Cloud Manager_ | 18 de setembro de 2019 |
   | _Configurações do Dispatcher com o Cloud Manager_ | 16 de outubro de 2019 |
   | _Criação de fluxos de trabalho com o Cloud Manager e Ferramentas de terceiros_ | 13 de novembro de 2019 |

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

### Fim da vida útil do produto

O [!DNL Digital Publishing Suite Classic] (DPSC) será encerrado em 31 de agosto de 2019. Para obter mais informações, consulte o [[! Perguntas frequentes sobre o fim da vida útil do DNL Digital Publishing Suite](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

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

### Adobe Campaign Classic

* [Atualização do Campaign Classic 19.1.4](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) - compilação 9032
* [Atualização do Campaign Classic 19.1.5](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) - compilação 9033

### [!UICONTROL Painel de controle] do Adobe Campaign

Adicionamos novos recursos para que usuários administradores recebam notificações antes que os certificados SSL de seus domínios expirem. Para obter mais informações, consulte a [documentação detalhada](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html).

Além disso, os usuários administradores agora podem excluir chaves SSH que foram adicionadas para acessar servidores SFTP.

Observe que o [!UICONTROL Painel de controle] está disponível para clientes do Adobe Campaign Classic e do Adobe Campaign Standard hospedados na AWS. Nenhuma atualização é necessária para acessar o [!UICONTROL Painel de controle].

### Recursos adicionais

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
