---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: notas de versão
last-update: Agosto de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 3bd946a9ef7d6d6d2e17cec4385a2dd53a41df97

---


# Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 8 de agosto de 2019**

* [Experience Cloud e Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Atualizado em 20 de agosto de 2019**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Ad Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links para a ajuda da solução)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links para a ajuda da solução)

## [!DNL Experience Cloud] e [!DNL Experience Platform] {#platform}

Notas de versão da [!UICONTROL Experience Platform], interface da Experience Cloud, administração de produtos, Experience Platform Launch, Serviço de identidades e boletins de segurança.

* [Interface da Experience Cloud](#core-services)
* [Experience Platform Launch](#launch)
* [Boletins e conselhos de segurança](https://helpx.adobe.com/security.html) (Todos os produtos da Adobe)

### Interface da Experience Cloud {#core-services}

* Correção de um problema crítico no login da Experience Cloud que resultava no logout da sessão para alguns usuários. (MCUI-6908)
* Atualização do login da Experience Cloud para melhorar o desempenho e reduzir a latência. (MCUI-6854, MCUI-6869, MCUI-6883)
* Atualização da aparência da interface. (MCUI-6861, MCUI-6911, MCUI-6862)
* Correção de um problema com os [!UICONTROL Triggers] da Experience Cloud que resultava na interpretação incorreta da cláusula _Curtir_ na definição do [!UICONTROL Acionador]. (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos, aprimoramentos e correções no Adobe Analytics](#aa-features)  (**Atualizado em 20 de agosto de 2019**)
* [Avisos importantes para administradores do Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Novos recursos, aprimoramentos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| Suporte para configurações de cookie SameSite | The [SameSite cookie setting](https://web.dev/samesite-cookies-explained) will be added to all cookies set by Analytics. Essa alteração possibilita a compatibilidade com as alterações do Chrome que exigem o campo de cookie SameSite. Os cookies do Analytics `none` serão padronizados. Se você tiver usado exclusivamente um domínio próprio (por exemplo, stats.domain.com), você pode ter o Adobe clientcare configurado para `lax` a configuração para domínios de coleção próprios. |
| Workspace: aumentar limite de itens para o filtro suspenso de 50 para 200 | Aumentamos o limite de itens que podem ser colocados em um filtro suspenso de 50 para 200. Esse aprimoramento abrange uma variedade de casos de uso, como adicionar todos os países (195) a um filtro, ou todos os estados e províncias dos EUA (52). |
| Impressões de atividade e conversões de atividade do A4T ativadas para Attribution IQ | Ativamos duas métricas do Analytics para Target (A4T) para Attribution IQ: Impressões da atividade e conversão de atividade. Anteriormente, na Analysis Workspace, essas métricas eram infladas em relação ao Relatórios e análises. Com essa alteração, os usuários podem aplicar um modelo de atribuição "mesmo toque", que colocará a Analysis Workspace em conformidade com os Reports &amp; Analytics. |

#### Correções

* Correção de um problema com a exibição de texto nos relatórios em tempo real no modo de tela cheia. (AN-183168)
* (**Atualizado em 20 de agosto de 20 19**) A coleta de dados agora rejeita urls de redirecionamento que contêm «@» para impedir que invasores redirecionem para sites maliciosos por domínios de lista de permissões.
* (**Atualizado em 20 de agosto de 20 19**) A Migração do visitante agora é desativada para todas as ocorrências que vêm de navegadores que não oferecem suporte ao atributo de cookie samesite e se a ocorrência contém um cookie de terceiros.
* (**Atualizado em August 0 de agosto de 20 19**) Corrigido um problema no qual as primeiras ocorrências não enviavam o cookie s_ vi para um novo visitante.

### Avisos importantes para administradores do [!DNL Analytics] {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Suporte para deslocamentos de fuso horário históricos | 8 de agosto de 2019 | O Analytics agora manipular automaticamente deslocamentos de fuso horário para ocorrências com carimbo de data e hora. Após essa mudança em 8 de agosto, os sistemas que carregam dados para o processamento histórico não precisarão mais ajustar para deslocamentos de fuso horário antes de enviar os dados. |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | Esses limites não são novos, mas foram adicionados à documentação [aqui](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | A partir de 18 de julho de 2019, os operadores de segmento _contêm um dos_, _não contém nenhum dos_, _contém todos os_ e _não contém nenhum dos_ serão limitados a 100 palavras por campo de entrada. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Futuras alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração será aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futura alteração para cálculos de _Total de relatório_ | atualizado em: 9 de julho de 2019 | Em **18 de junho de 2019**, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 18 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, os segmentos que usam a lógica _existe_ ou _não existe_ podem ver resultados diferentes para algumas dimensões após essa mudança, especificamente dimensões em que _Não especificado_ tem um nome especial, como o item de linha "Digitado/Marcado" da dimensão Tipo de referenciador ou o item de linha "Outro" da dimensão Tipo de dispositivo. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV da [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas a **[!UICONTROL downloads CSV]** (e **[!UICONTORL Copiar para área de transferência]**) da [!DNL Analysis Workspace] para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da [!DNL Analysis Workspace] | 4 de abril de 2019 | O comando do Console para ativar o depurador da [!DNL Analysis Workspace] será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Links encurtados de [!DNL Analytics] relatórios do | 14 de janeiro de 2019 | Os links encurtados de [!DNL Analytics] relatórios do que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Desde 11 de fevereiro de 2019, os relatórios do Adobe Analytics não são mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> Desde 20 de fevereiro de 2019, a coleta de dados do Adobe Analytics não é mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará [!DNL Analytics] dados do de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para terem suporte ao TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes de API que usam o Java 8 não deverão ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

### AppMeasurement {#appm}

Versões 2.16.0 do [!UICONTROL AppMeasurement] em 8 de agosto de 2019.

| Recurso | Descrição |
| -----------| ---------- |
| `sendBeacon` suporte para links de saída | Implementação de `sendBeacon` suporte no [!UICONTROL AppMeasurement] para links de saída. Isso melhorará o rastreamento de links de saída e provavelmente resultará em maior tráfego. |
| Valores de ECID/fid | Os valores de ECID/fid são agora armazenados em cache na primeira ocorrência, mesmo se as configurações OptIn forem alteradas. |
| DIL 9.3 | Atualização do módulo Gerenciamento de Público-Alvo para DIL 9.3 |
| Rastreamento de alcance de rolagem | Exibição do botão no s.ActivityMap.trackScrollReach para ativar ou desativar o rastreamento de alcance de rolagem. |
| Serviço de ID de Visitante 4.4.0 | Atualização do AppMeasurement para usar o Serviço de ID de Visitante 4.4.0. |

#### Correções

* Correção de um bug na fila do AppMeasurement que ocorreu antes do isReadyToTrack ser verdadeiro.

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

* A guia Administração agora é exibida somente para contas de usuário com privilégios administrativos (AAM-48557).
* A API de usuários da lista agora retorna os detalhes completos do usuário (AAM-48662).
* Agora é possível redimensionar a lista de pastas de características (AAM-48800).
* Diversas otimizações de acessibilidade da interface do usuário (AAM-48865, AAM-48933).
* Otimizações de carregamento para as páginas Administração e Fontes de dados (AAM-48514).

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais que implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

### Fim da vida útil do produto

O Digital Publishing Suite Classic (DPSC) será encerrada em 31 de agosto de 2019. Para obter mais informações, consulte [as Perguntas frequentes do Digital Publishing Suite Classic Classic](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

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

### Adobe Campaign Standard

[Versão do Campaign Standard 19.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Recurso | Descrição |
| -----------| ---------- |  
| Atividade da API externa (Beta público) | Para maior personalização, a Atividade da API externa permite que você insira dados de sistemas externos em um fluxo de trabalho por meio de uma chamada de API REST. Os endpoints REST podem ser um sistema de gerenciamento de clientes, tempo de execução de E/S da Adobe ou endpoint REST da Adobe Experience Cloud (por exemplo, Plataforma de dados, Target, Analytics, Campaign). No momento, esse recurso está em beta público. Para obter mais informações, consulte a documentação [detalhada](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) e o vídeo [passo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html)a passo. |
| Relatório sobre o segmento do fluxo de trabalho | Esse recurso permite que os profissionais de marketing analisem seu desempenho de entrega por código de segmento. Ao criar um fluxo de trabalho e usar uma atividade de segmentação para atribuir segmentos à população de entrega, esses segmentos agora podem fazer parte da mesma entrega. Isso permite exibir as estatísticas de aberturas/cliques com base em vários segmentos em uma única entrega. Para obter mais informações, consulte a documentação [detalhada](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) e o vídeo [passo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html)a passo. |

### Adobe Campaign Classic

[Atualização do Campaign Classic 19.1.3](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - compilação 9031

### Painel de controle do Adobe Campaign

[Os novos recursos do Painel de controle](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) incluem a capacidade de adicionar urls que o Campaign Classic conecta-se a transferências de dados/arquivos.

Observe que o [!UICONTROL Painel de controle] está disponível para clientes do Adobe Campaign Classic e do Adobe Campaign Standard hospedados na AWS. Nenhuma atualização é necessária para acessar o Painel de controle.

### Recursos adicionais

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Atualizado em: 9 de agosto de 2019, para o lançamento do dia 10 de agosto

* (Anunciantes com o serviço de rastreamento de conversão da Advertising Cloud) Com a Apple Tracking Prevention (ITP) 2.2, lançada em maio, os cookies de rastreamento de conversão da Advertising Cloud são excluídos automaticamente dos navegadores Apple Safari após 24 horas. A Advertising Cloud tem uma nova solução ITP. No entanto, permite rastrear conversões que ocorrem no Safari por mais de 24 horas após o clique original. A solução usa armazenamento local e tecnologia iframe. Entre em contato com o gerente de conta de pesquisa da Advertising Cloud para obter instruções de implementação.
* Em Pesquisar &gt; Avançado (ACM), agora é possível configurar os sufixos finais do URL de nível de campanha para modelos de anúncios de texto e anúncios de compra do Google.
* Os anunciantes com contas do Google Ads qualificados para a Correspondência do cliente agora podem fazer o seguinte:
   * Crie um público-alvo de correspondência do cliente do Google Ads usando IDs de usuário de um segmento de público-alvo da Adobe. Para ver esse recurso, a conta do anunciante deve ser configurada para permitir isso.
   * Crie um público-alvo de correspondência do cliente do Google Ads ao fazer upload de um arquivo de dados do cliente. O arquivo pode consistir em informações de contato (endereços de email, endereços de envio ou números de telefone), IDs de usuário ou IDs de dispositivo móvel. Alguns tipos de informações de contato devem ser transformados em hash usando o algoritmo SHA -256.
   * Atualize qualquer público-alvo de correspondência do cliente do Google, exceto os públicos-alvo criados de um público da Adobe. Carregue dados para adicionar, excluir ou substituir todos os dados existentes do público-alvo. Todas as informações de contato devem ser transformadas em hash usando o algoritmo SHA -256.
* As exibições Públicos-alvo &gt; Direcionamento e públicos-alvo &gt; Exclusões incluem uma coluna "Tipo".
