---
title: Notas de versão da Adobe Experience Cloud
description: Notas de versão da Experience Cloud
doc-type: notas de versão
last-update: Abril de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 147b01562e6c8d579a2bec0e4fa2841d1791a671

---


# Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: abril de 2019**

* [Serviços e administração da Experience Cloud](#experiencecloud)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Advertising Cloud](#adcloud)
* [Target](#target)
* [Experience Manager](#aem)
* [Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)

## Serviços e administração da Experience Cloud {#experiencecloud}

Notas de versão da interface da Experience Cloud, incluindo [!UICONTROL serviços] essenciais da plataforma e administração de produtos.

* [Principais serviços da Experience Cloud](#core-services)
* [Serviço da Experience Cloud ID](#ecid)
* [Mobile Services e SDK móvel](#mobile)
* [Launch da Adobe](https://docs.adobelaunch.com/) (links para a ajuda do produto)

### Principais serviços da Experience Cloud {#core-services}

Notas de versão da interface da Experience Cloud e de serviços principais.

* Atualização do alternador de aplicativo para incluir o Marketo no conjunto de soluções da Experience Cloud, além de atualizações de marca na Experience Platform. (MCUI-6529)
* Atualização da tela inicial da Experience Cloud para incluir links de navegação às páginas Feed e Administração. (MCUI-6682)
* Correção de um problema na definição [!UICONTROL Acionar] para uso correto da cláusula &quot;like&quot;. (MCUI-6611)
* Melhorias nos Atributos do cliente para melhores registros no serviço de Assinatura. (MCUI-6519)

Para obter a documentação do produto, consulte [Experience Cloud e principais serviços](https://marketing.adobe.com/resources/help/en_US/mcloud/)

### Serviço da Experience Cloud ID {#ecid}

* Atualizado para a versão 4.2.0.
* Adição de suporte para o plug-in do Audience Manager para IAB TCF, disponível por meio do objeto ECID Opt-in.

Para obter a documentação do produto, consulte [Serviço da Experience Cloud ID](https://marketing.adobe.com/resources/help/en_US/mcvid/).

### Mobile Services e SDK móvel {#mobile}

Recursos e correções nos Adobe Mobile Services:

**iOS versão 4.18.2**

* Target: correção de um problema que impedia o _purchasedProductIds_ de ser representado corretamente como uma matriz para ver notificações.

**Android versão 4.17.4**

* Geral: melhoria do suporte para aplicativos Android Instant ao tornar verificações de acessibilidade configuráveis no arquivo _ADBMobileConfig.json_ com a propriedade booliana _reachabilityChecksEnabled_ no objeto JSON raiz.

Para obter a documentação do produto, consulte [Mobile Services](https://marketing.adobe.com/resources/help/en_US/mobile/).

Para obter mais informações sobre os Mobile SDKs, consulte: [Android SDK 4.x para Soluções da Experience Cloud](https://marketing.adobe.com/resources/help/en_US/mobile/android/) e [iOS SDK 4.x para Soluções da Experience Cloud](https://marketing.adobe.com/resources/help/en_US/mobile/ios/).

## Analytics {#analytics}

* [Novos recursos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)

Para obter a documentação do produto, consulte [Página inicial de ajuda do Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Novos recursos no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| Segmentação em contagens distintas | Agora é possível segmentar em uma contagem distinta de itens em uma dimensão. Exemplos: “Visitantes que visualizaram mais de 5 produtos distintos”, ou “Visitas em que mais de 5 páginas distintas foram.” (Observe que a função Contagem distinta aproximada ainda está disponível em Métricas calculadas, se você quiser criar uma métrica que é uma contagem distinta de uma dimensão (por exemplo, # of customers, # of products etc)). |
| Suporte a análise ad hoc para Java 11 | A Ad Hoc Analysis agora é compatível com o Java 11. Estas são algumas limitações ao uso do Java 11. |
| Atualizações do Advertising Analytics | Estamos lançando algumas atualizações para o Advertising Analytics: <ul><li>O Yahoo Gemini foi absorvido pelo Microsoft Bing em 31 de março. Como consequência, a opção de conta de publicidade do Yahoo Gemini não está mais disponível. </li><li>O Google implementou um novo padrão de rastreamento e, em vez de usar o _Modelo de rastreamento_, agora usamos o _Sufixo de URL final_.</li></ul> |
| Analysis Workspace | Atualizações para Práticas recomendadas de otimização. |

**Correções**

* (Espaço de trabalho) Correção de problemas que impediam a criação de segmentos a partir de visualizações de Fallout. (AN-177042, AN-176876)
* (Espaço de trabalho) Correção de um problema que impedia a criação de segmentos a partir de visualizações de Fluxo. (AN-176681)
* (Espaço de trabalho) Correção de um problema de alinhamento incorreto em tabelas. (AN-176919)
* (Espaço de trabalho) Correção de um problema com a interface do usuário em japonês que ocorria ao recolher/expandir o painel de visualização. (AN-170601)
* Correção de um problema que ocorria ao tentar alternar segmentos em relatórios do painel. (AN-177056)
* (Reports &amp; Analytics) Correção de um problema em que não era possível selecionar métricas no relatório Visão geral do canal. (AN-176786)
* (Gerenciador de segmentos) Correção de um problema que resultava em uma mensagem de erro ao tentar editar um segmento compartilhado com várias fontes de dados do Audience Manager. (AN-175353)
* (Espaço de trabalho) Correção de um problema que impedia que usuários não administrativos vissem componentes (como segmentos) de sua propriedade que não fossem coletados em conjuntos de relatórios virtuais. (AN-175616)
* (Admin) Correção de um problema ao tentar editar eVars para vários conjuntos de relatórios. (AN-168150)
* (Admin) Correção de um problema que impedia a transferência de ativos para outro usuário, na interface de gerenciamento de usuários herdada. (AN-176630, AN-173974)
* (Espaço de trabalho) Correção de um problema com dados da detecção de anomalias sendo mostrados antes da hora. A correção deve resultar em menos falsos positivos. (AN-176724)

### Avisos importantes para administradores do Analytics {#aa-notices}

| Aviso | Data de adição  ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Futura alteração para cálculos de _Total de relatório_ | 16 de abril de 2019 | Em 13 de junho de 2019, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 13 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV na Analysis Workspace | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações serão feitas a downloads CSV (e Copiar para área de transferência) da Analysis Workspace para remover a formatação de dados exportados.  <ul><li>O separador de milhares não será mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **Componentes** &gt; **Configurações de relatórios** &gt; **Separador de milhar**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>Tabelas de coorte mostrarão apenas valores brutos; serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da Analysis Workspace | 4 de abril de 2019 | O comando Console para ativar o Depurador da Analysis Workspace está mudando para adobetools. debug. includeoberonxml em 13 de **junho de 23 19**. |
| Futuras alterações de suporte das Classificações ativadas por data e numéricas | 28 de fevereiro de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração será aplicada na Versão de manutenção de junho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Atualização da documentação sobre o plug-in getPercentPageViewed. | 12 de fevereiro de 2019 | [https://experiencecloud.adobe.com/resources/help/pt_BR/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html) |
| Admin &gt; Configurações gerais da conta | 7 de fevereiro de 2019 | * A configuração _Substituir o último octeto de endereços IP por 0_ fica habilitada por padrão para qualquer conjunto de relatórios criado no Data Center de Londres depois de janeiro de 2019, mas somente se as configurações desse conjunto de relatórios tiverem sido copiadas de um modelo listado no Admin Console. Os conjuntos de relatórios cujas configurações estiverem duplicadas de outros conjuntos de relatórios herdam todas as configurações do conjunto selecionado.<br/> * A configuração _Ofuscação de IP_ não é mais habilitada por padrão para todos os clientes com um conjunto de relatórios definido no EMEA. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da Ad Hoc Analysis | Atualizado em 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da Ad Hoc Analysis. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Links encurtados de relatórios do Analytics | 14 de janeiro de 2019 | Links encurtados de relatórios do Analytics que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | A partir de 11 de fevereiro de 2019, os relatórios do Adobe Analytics não serão mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. Se não conseguir se conectar aos relatórios do Adobe Analytics após 11 de fevereiro de 21 19, você deve atualizar o navegador para a [versão mais recente](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> A partir de 20 fevereiro de 2019, a coleta de dados do Adobe Analytics não será mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará dados do Analytics de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para terem suporte ao TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes de API que usam o Java 8 não deverão ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Atualizar o Adobe Report Builder devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do Adobe Report Builder (ARB) baixem o ARB v5.6.21 antes de 7 de fevereiro de 2019. **Depois dessa data, versões anteriores do ARB não funcionarão.** |
| Atualização de downloads em CSV na Analysis Workspace | 9 de janeiro de 2019 | A partir de 7 de fevereiro de 2019, os downloads em CSV (e Copiar para a área de transferência) na Analysis Workspace não mais incluirão o separador de milhar. Observação: a interface do usuário da Analysis Workspace continuará exibindo o separador de milhar. Além disso, o separador decimal continuará a ser incluído e seguirá o formato definido em **[!UICONTROL Componentes]** &gt; Configurações **[!UICONTROL do relatório]** &gt; **[!UICONTROL Separador de milhares]**. |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe planeja estender o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração tem como objetivo garantir que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do Analytics Live Stream inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro 2019, os endpoints do Live Stream sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da para saber sobre os endpoints do Live Stream e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Migração de servidor FTP para Dallas (ftp2.omniture.com) | 19 de outubro de 2018 | Em 23 de outubro de 2018, se você faz conexões com ftp2.omniture.com por meio do protocolo SFTP, pode ser necessário aceitar novamente o identificador de host do site SJ1. Isso aplica-se somente a 23 de outubro. Consulte [Atualização de servidores FTP da Adobe](https://marketing.adobe.com/resources/help/en_US/whitepapers/ftp/ftp_upgrade.html). |
| Atualização para dimensão de Dispositivo móvel | 16 de outubro de 2018 | Em 26 de setembro, a Adobe atualizou sua pesquisa de dispositivo para a API 2.1 do Device Atlas. Isso fez com que dispositivos mais detalhados (ex: Apple iPhone 7, Apple iPhone 8 Plus etc.) fossem exibidos na dimensão Dispositivo móvel em alguns navegadores. Esse novo nível de detalhe de dispositivo deve sere usado direcionalmente, uma vez que não aplica-se a todos os tipos de dispositivos e navegadores no momento. |
| Encerramento do suporte para Internet Explorer 11 | 12 de setembro de 2018 | A Adobe encerrará o suporte ao Internet Explorer 11 no Adobe Analytics em 13 de novembro de 2018. Alterne para o Microsoft Edge ou navegador compatível assim que possível. |
| Término da vida útil da Ad Hoc Analysis | 9 de agosto de 2018 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da Ad Hoc Analysis. Uma data para o fim da vida útil será compartilhada assim que estiver disponível. Para obter mais informações, visite [Descubra a Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). Não modifiaremos [!UICONTROL a Análise ad hoc] para suportar o Java 9 + a partir desse ponto. Se você atualizar para Java 9 +, [!UICONTROL a Análise] ad hoc deixará de funcionar. Somente o Java 8 será suportado. |
| Atualizar o Adobe [!UICONTROL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!UICONTROL Report Builder] (ARB) baixem o ARB v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do ARB não funcionarão. |
| Nova ajuda para a migração de usuário do Analytics | 10 de maio de 2018 | Atualizamos a ajuda da migração de ID de usuário do Analytics com informações sobre a migração de Enterprise e Federated IDs para o Admin Console. Consulte [Migrar contas de usuário do Analytics para Enterprise e Federated IDs](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html). |
| Futura remoção do Relatório de atividade na conta | 10 de maio de 2018 | O Relatório de atividade na conta será substituído pelo recurso de Uso de chamadas do servidor na versão do terceiro trimestre do Adobe Analytics. O Relatório de atividade na conta será removido permanentemente em 9 de agosto de 2018. Para exibir os dados de resumo sobre o tráfego de conjuntos de relatórios depois de 9 de agosto de 2018, use o recurso de Uso de chamadas do servidor. |
| Alterações nos modelos de alocação linear em Métricas calculadas | Em vigor em 19 de julho de 2018 | Em 19 de julho, o Adobe Analytics revisará a maneira como os modelos de alocação em métricas calculadas são avaliados. Como parte dessa alteração, as métricas calculadas que utilizam um modelo de alocação não padrão serão migradas para modelos de atribuição novos e melhorados. [!UICONTROL Os modelos de alocação de Último contato] do Canal de marketing e [!UICONTROL de Distribuição do] canal de marketing serão migrados para novos [!UICONTROL modelos de atribuição de Último contato] e [!UICONTROL de Primeiro toque] de forma seletiva. ([!UICONTROL Canais de marketing não se tornaram obsoletos, somente os dois modelos de alocação que aparecem nas métricas calculadas). ] Além disso, vamos corrigir a maneira como a alocação linear é calculada. Se você usa métricas calculadas com modelos de alocação linear, os relatórios podem ser levemente alterados para refletir o novo modelo de atribuição corrigido. Essa alteração nas métricas calculadas será refletida na [!UICONTROL Analysis Workspace], [!UICONTROL nos Relatórios e análises], na API [!UICONTROL de relatórios], [!UICONTROL no Construtor de relatórios]e [!UICONTROL na Análise ad hoc]. Consulte [a documentação Métricas](https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/m_metric_type_alloc.html) calculadas para obter mais informações sobre essa alteração. |
| [!UICONTROL ][!UICONTROL A funcionalidade de Detecção de anomalias e Análise de contribuição foi removida de ]Reports &amp; Analytics[!UICONTROL ] | 10 de abril de 2018 | A Detecção de anomalias e a Análise de contribuição foram removidas do conjunto de recursos do Reports &amp; Analytics e agora estão disponíveis apenas por meio da Analysis Workspace . Os clientes do Adobe Analytics Select e Foundation têm acesso apenas à Detecção de anomalias de “granularidade diária” no Workspace. |
| A Adobe interrompeu a emissão de cookies s_vi de terceiros para o Safari | 05 de abril de 2018 | Em 20 de março de 2018, a Adobe interrompeu a emissão de cookies s_vi de terceiros para o navegador Safari. Essa alteração não afeta clientes que usam cookies de coleta de dados originais. Essa alteração também remove o aumento de visita e visitante referente a alguns clientes resultantes do Safari ITP. |
| Alterações no back-end que afetam relatórios | 11 de abril de 2018 | Uma alteração feita ao mecanismo de pesquisa (back-end) afetará o uso de relatórios em várias maneiras. Estas alterações entraram em vigor no final de fevereiro de 2018: A renomeação de páginas não será mais permitida. Em breve, será necessário usar classificações para renomear páginas. Até a versão de 10 de maio de 2018, o sistema continuará a processar as páginas renomeadas conforme estão configuradas atualmente. A Adobe pede que todos os clientes migrem para classificações até essa data. Depois do lançamento de maio, as renomeações existentes não mais serão honradas e podem ser alteradas, retroativamente, sem aviso prévio. <br> <br>A metodologia de substituição de URL é diferente. Anteriormente, o Adobe Analytics armazenava (em maioria) o primeiro URL associado a cada nome de página por mês. Agora, armazenaremos o URL mais recente referente a cada nome de página. (Atualizado em 11 de abril de 2018) Relatórios de categoria para pacotes e dados atuais em Reports &amp; Analytics não são mais fornecidos. A desaprovação de relatórios de pacote de categoria na API do serviço de Web entrará em vigor na versão de manutenção do Adobe Analytics de 10 de maio de 2018. Não há mais suporte para dados de página/propriedade anteriores a aproximadamente janeiro de 2007 (em alguns casos, 2006). Isso só será aplicado a páginas, propriedades e eventos de página (links personalizados, links de saída, links de download). Observação: essa alteração não afeta relatórios na Analysis Workspace ou no Data Warehouse. Se você tiver dados antes dessas datas, espere o seguinte: Os dados não serão combinados corretamente no limite anterior de janeiro de 2007. Pesquisas não funcionarão em relação a dados anteriores a aproximadamente janeiro de 2007. |
| Futuras alterações de suporte das Classificações ativadas por data e numéricas | 7 de maio de 2018 | Na Versão de manutenção de 10 de maio de 2018, começaremos a limitar a funcionalidade de classificações ativadas por data e numéricas. Esses tipos de classificações serão removidos das interfaces Admin e Importador de classificações. A partir dessa data, nenhuma classificação ativada por data ou numérica será adicionada. As classificações existentes ainda podem ser gerenciadas (atualizadas, excluídas) por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futuras alterações de suporte do Custo e orçamento do Marketing Channel | 28 de fevereiro de 2018 | Na versão de manutenção de abril, removeremos o Custo e orçamento do Marketing Channel do menu Admin &gt; Marketing Channel. Nenhum novo dado de custo ou orçamento pode ser adicionado. Os dados de custo e orçamento existentes continuarão disponível nos relatórios, mas não poderão ser atualizados. |
| Atualize o Report Builder antes de migrar IDs de usuário para o Admin Console | 17 de março de 2018 | **Importante:** atualize sua instalação do Construtor de relatórios para a versão mais recente. Essa atualização é um pré-requisito para executar a migração de IDs de usuários do Analytics para o Admin Console, que terá início em abril de 2018. |
| Gerenciador de códigos - Código H herdado | 8 de fevereiro de 2018 | Não há mais suporte para baixar JavaScript herdado (código H) no Gerenciador de códigos. |
| Retenção de dados: verifique e defina a política de retenção de dados para o Adobe Analytics | 1 de fevereiro de 2018 | **Plano de fundo:** O Regulamento geral de proteção de dados (RGPD) da União Europeia, que se aplica a partir de 25 de maio de 25 18, especifica que a Adobe, na sua função de processador de dados, deve tomar as medidas apropriadas para ajudar seus clientes a cumprir o acesso, a exclusão e outras solicitações de indivíduos. A aplicação de políticas de exclusão oportunas, seguras e apropriadas é parte importante do cumprimento dessa obrigação. Como resultado, a Adobe gostaria de trabalhar com você para implementar uma política de retenção de dados antes da entrada em vigor do GDPR, em 25 de maio de 2018.<br> <br>**O que esperar:** A menos que já tenha uma política de retenção de dados do Adobe Analytics instalada, a Adobe começará a aplicar a retenção de dados conforme já especificado nos contratos do cliente do Adobe Analytics, a menos que outro acordo seja feito. A maioria dos contratos do Adobe Analytics especifica que a Adobe pode excluir os dados após 25 meses. Quando uma política de retenção de dados estiver em vigor para a sua organização, ela será aplicada mensalmente. Uma retenção de dados para períodos superiores a 25 meses está disponível por uma taxa adicional. Períodos de retenção de dados mais curtos também podem ser configurados, entrando em contato com o Atendimento ao cliente. Em breve você receberá um email contendo informações adicionais para a sua organização. <br> <br>A retenção de dados afeta todos os métodos de acesso a dados históricos do Adobe Analytics, incluindo, entre outros, os Reports &amp; Analytics, a Analysis Workspace, o Report Builder, as APIs de relatórios dos serviços da Web, o Data Warehouse e os feeds de dados. **Próximas etapas:** Identifique as partes interessadas na organização responsável por tomar decisões sobre retenção de dados. Sua organização tem melhor condição de determinar o período apropriado para o Adobe Analytics reter os dados. Entre em contato com o Gerente de sucesso do cliente da Adobe em caso de dúvidas relacionadas à retenção de dados do Adobe Analytics. |
| Vinculação da conta do usuário | 26 de outubro de 2017 | Os usuários do Analytics não precisam mais vincular manualmente suas contas entre a Experience Cloud e o Analytics. Os usuários podem entrar em contato com o administrador do Admin Console para solicitar acesso ao Analytics. A migração de ID de usuário do Analytics permite que os administradores migrem facilmente as contas de usuários do gerenciamento de usuários do Analytics para o Adobe Admin Console. Após a migração, os usuários terão acesso às soluções compradas e aos serviços principais disponíveis na Experience Cloud. [Saiba mais sobre a migração de ID de usuário do Analytics](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/). |

## Audience Manager {#aam}

| Recurso | Descrição |
| -----------| ---------- |  
| [Recomendações de característica](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/trait-recommendations.html) | O recurso Recomendações de característica, desenvolvido pelo [Adobe Sensei](https://www.adobe.com/sensei.html), leva a ciência de dados até seus fluxos de trabalho diários do Audience Manager. <br> Com as Recomendações de característica, ao criar ou editar um segmento no [Construtor de segmento](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html), você recebe recomendações sobre as características adicionais que você pode incluir, semelhantes às características na regra de segmento. Adicione as características recomendadas ao segmento para aumentar o público-alvo de destino. |
| [Fontes de dados globais](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) | As fontes de dados globais são acessíveis a todos os clientes do Audience Manager e contêm IDs de publicidade do dispositivo geradas pelos frabricantes do dispositivo, como os fabricantes de dispositivos Apple, Samsung, Microsoft, Roku e Android. Essas IDs são disponibilizadas pelos fabricantes para fins de publicidade. Use fontes de dados globais para sincronizar IDs de dispositivos e exportar dados extraídos desses mapeamentos. O Audience Manager valida as IDs de publicidade de dispositivos (DAID) importadas por clientes, com base em seus formatos, para garantir que correspondam ao formato padrão determinado pelos fabricantes. |
| [Limites de mapeamento de ID](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/usage-limits.html#id-mapping-limits) | Aprimoramos a segmentação, os relatórios e a exportação de segmentos ao limitar o número de mapeamentos de ID entre dispositivos associados a uma ID do dispositivo. Os limites impostos recentemente ajudam a reduzir o impacto que integrações incorretas e conjuntos de dados imprecisos podem ter na ingestão e no processamento de downstream. <br/> Os novos limites são: <ul><li>100 IDs de dispositivo por ID entre dispositivos</li><li>10 IDs entre dispositivos por ID de dispositivo</li><li>1000 IDs de dispositivos para 1 ID de dispositivo</li></ul> |

### Melhorias

* Agora, os usuários veem uma mensagem de erro quando tentam criar um Modelo [!UICONTROL algorítmico] usando um tipo de linha diferente de um tipo de traço diferente de baseado em regras, segmento ou integrados. A mensagem de erro é: “Somente características com base em regra, características integradas e segmentos podem ser usados como linha de base.” (AAM-45235).
* A [!UICONTROL métrica Tempo de vida] foi removida das páginas [!UICONTROL Características] e [!UICONTROL Características] da pasta.
* As datas de início e de término do mapeamento de segmento agora estão incluídas no [!UICONTROL Relatório geral de destinos] (AAM-44997).

### Correções

* Correção de um problema que fazia com que o Relatório de histórico de arquivo [!UICONTROL de saída] não fosse carregado em algumas situações (AAM -45713).
* Correção de um problema que fazia com que a característica selecionada anteriormente fosse adicionada ao [!UICONTROL Construtor] de segmentos ao clicar [!UICONTROL em Adicionar característica] em um campo vazio (AAM -45599).
* Correção de um problema que impedia que usuários editassem ou desativassem Modelos algorítmicos que continham características excluídas (AAM-45552).

## Advertising Cloud {#adcloud}

Atualizado em 15 de abril de 25 19, para a versão de April 3 de abril

| Recurso | Descrição |
| -----------| ---------- | 
| Campanhas de pesquisa | No seletor de intervalo de datas, o calendário agora é organizado de domingo a sábado. Anteriormente, era organizado de domingo a sábado. |
| Relatórios | O Relatório de Portfólio agora inclui a Estratégia opcional de Gastos _do Portfólio de Coluna_. |

A ajuda da Advertising Cloud está disponível no menu Ajuda **?** Todos os aplicativos.

## Target {#target}

Notas de versão para as seguintes versões do Adobe Target:

### Target Standard/Premium 19.4.1 (15 de abril de 2019)

Esta versão é uma versão de manutenção e inclui a seguinte alteração:

(Os números de edição entre parênteses são para o uso interno da Adobe.)

* Atualização da interface do usuário da Adobe Experience Cloud para apresentar alterações de marca e produto. (TGT-33546, TGT-33272 e TGT-33331)

### Target Standard/Premium 19.4.2 (29 de abril de 2019)

Esta versão inclui os seguintes recursos, alterações e melhorias:

(Os números de edição entre parênteses são para o uso interno da Adobe.)

| Recurso | Descrição |
| -----------| ---------- |  
| Mobile Visual Experience Composer | O Visual Experience Composer (VEC) para aplicativos móveis nativos permite criar atividades e personalizar o conteúdo de maneira autônoma, sem dependências de desenvolvimento contínuas e ciclos de lançamento de aplicativos. |
| Visual Experience Composer | O Visual Experience Composer (VEC) inclui os seguintes aprimoramentos para agilizar seu trabalho e deixá-lo mais eficiente: <ul><li>É possível editar o estilo de um elemento, incluindo a imagem de fundo, no VEC. (TGT-15001)</li><li>O Target suporta HTML5 usando configurações na v4.5.1 ou versão posterior. (TGT-33618)</li></ul> |

**Melhorias, correções e alterações**

* Aprimoramos o fluxo de trabalho ao excluir ativos usando o VEC. Os ativos excluídos agora são removidos da biblioteca de ofertas e do Scene 7 (se aplicável) Os ativos excluídos não são mais exibidos nos resultados da pesquisa. (TGT-31981)
* Melhoramos a renderização de ofertas de imagem no seletor de ativos. Exibir e selecionar ofertas de imagem agora é mais fácil e eficiente. (TGT-32897)
* Melhoramos o direcionamento para URLs ao cancelar o carregamento de uma página dentro do VEC. (TGT-33815)
* Os ícones da barra de ferramentas são exibidos corretamente após cancelar o carregamento de uma página dentro do VEC. Se ações específicas não puderem ser executadas após a página estar completamente carregada, os ícones da barra de ferramentas associados são desabilitados. (TGT-33811)
* Após selecionar uma coleção de Recomendações no seletor de coleções, clique no botão Salvar. Este fluxo de trabalho está consistente aos outros fluxos de trabalho no Target. (TGT-33205)

Consulte as [Notas de versão do Adobe Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) para obter as informações mais recentes da versão sobre os seguintes produtos:

* Target Standard e Premium
* Recommendations Classic

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais implantem os patches mais recentes como um modo de assegurar estabilidade, segurança e desempenho superiores.

### Versões do produto

**Cloud Manager 2019.3.0**

A versão deste mês do Cloud Manager (2019.3.0) adiciona relatórios SLA ao recurso de monitoramento de sistema introduzido na última versão. Também foi adicionada uma atualização virtual de algumas telas principais.

* [Notas de versão](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Manutenção do produto

**AEM 6.2 Service Pack 1-Cumulative Fix Pack 19**

O AEM 6.2 SP1-CFP19 (6.2.1.19), lançado em 07 de março de 2019, é uma atualização importante que inclui correções essenciais para o cliente lançadas desde a disponibilização geral do AEM 6.2 SP1 em dezembro de 2016.

* [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3 Service Pack 3-Cumulative Fix Pack 3**

AEM 6.3 SP 3-CFP 3 (6.3.3.3), lançado em 14 de março de 24 19, é uma atualização importante que inclui o cliente-chave fixo, lançado desde a disponibilização geral do AEM 6.3 abril de 2017.

* [Notas de versão](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
* [Versões CFP do AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Recursos adicionais

* [Página inicial de Aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notas de versão do Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)
