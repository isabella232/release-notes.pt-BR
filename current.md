---
title: Notas de versão da Adobe Experience Cloud
description: Modelo para notas de versão da Experience Cloud
doc-type: notas de versão
last-update: Maio de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 4dd5facd0c7c7088f177285fe04991254da17ff9

---


# Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.


**Data de lançamento: maio de 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Notas de versão da Adobe Experience Platform

Versão 1.0, 15 de maio de 25 19

* Consulte [Notas de versão da Plataforma de experiências](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) no Adobe. io para obter as últimas atualizações da Experience Platform.

### Experience Platform Launch

* Consulte [Launch Platform Launch](https://docs.adobelaunch.com/) para obter as informações mais recentes.

### Serviço da Experience Cloud ID

Lançamento em **13 de maio de 2019**

* Suporte para a API de visitante 4.3.0
* Suporte para o ITP 2.1.
* Correção de um problema relacionado à configuração do secureCookie.

## Analytics {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)

Para obter a documentação do produto, consulte [Página inicial de ajuda do Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Novos recursos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| [!DNL AppMeasurement Version 2.14.0] <ul><li>Correção de problemas com o gerenciamento do estado dos parâmetros do rastreador quando várias ocorrências estavam pendentes. (AN -176931, AN -176629, DTM -12758)</li><li>Atualização do appmeasurement para incluir Visitor. js 4.3.0 (AN -180049)</li></ul> |
| [!DNL Analysis Workspace]: Nova configuração de visualização de fluxo _Incluir instâncias de repetição_ | A configuração de fluxo _Incluir instâncias de repetição_ oferece a opção de incluir ou excluir instâncias repetidas, como Recarregamentos de página. Além disso, todas as visualizações de Fluxo agora são baseadas apenas em instâncias. |
| [!DNL Ad Hoc Analysis]: Compatibilidade com o Java 11 | A Ad Hoc Analysis agora é compatível com o Java 11. Saiba como executar [a Análise ad hoc no Java 11](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html). |
| **Coleta de dados:** Novo cookie s_ ecid | Um um novo cookie de servidor primário foi adicionado, s_ecid, em que a coleta de dados armazena a ECID do visitante. |

**Correções da Analysis Workspace**

* Correção de um problema que afetava **[!UICONTROL Tempo gasto na página]**. [!DNL Analysis Workspace]Os relatórios do não usarão mais Nome da página ao calcular intervalos de Tempo gasto, permitindo que as ocorrências granulares e com intervalos sejam contadas. **[!UICONTROL ]****[!UICONTROL ]** (AN-140479)
* Correção de problemas de desempenho de visualização de linha como parte de um esforço maior para melhorar [!DNL Analysis Workspace] o desempenho. (AN-174878)
* Correção de um problema de falta de codificação UTF-8 em arquivos .csv baixados. (AN-178393)
* Correção de problemas com o desempenho lento [!DNL Analysis Workspace] do projeto. (AN-177710)
* Correção de problemas de exibição da visualização de linha com pequenos intervalos na granularidade do eixo y. (AN-176467)

**Outras correções do Analytics**

* [!DNL Audience Analytics]: Correção de um problema que ocorria depois que um nome de público-alvo era alterado [!DNL Audience Manager (AAM)] . O nome atualizado não era refletido no Audience Analytics. (AN-176237)
* Fixed an issue that prevented users from saving [!DNL Analytics segments in [!DNL Audience Manager]. Isso era causado por pastas AAM existentes com nomes mistos de letras maiúsculas e minúsculas. Agora, todas as pastas diferenciam maiúsculas de minúsculas, para que sejam sincronizadas. (AN-177934)
* Correção de um problema que ocorria quando os usuários faziam logon [!DNL Analytics][!DNL Experience Cloud] via e depois a sessão expirava. Ao retomar a sessão, o usuário era redirecionado para um URL com defeito. (AN-176812)
* Correção de um problema com deslocamentos de fuso horário em [!DNL Data Warehouse] solicitações. (AN-177585)

### Avisos importantes para administradores do Analytics {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Futuras alterações de suporte para **[!UICONTROL Classificações ativadas por data e]** **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração entrará em vigor com a Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futura alteração para cálculos de _Total de relatório_ | Atualizado em 2 de maio de 2019 | Em **13 de junho de 2019**, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 13 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, segmentos que usam a lógica _existe_ ou _não existe_ poderão apresentar resultados diferentes para algumas dimensões após essa mudança. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização para downloads CSV de [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir de 11 de abril de 21 19, foram feitas várias alterações em **[!UICONTROL downloads CSV]** (e **[!UICONTORL Copiar para a área de transferência]**) para [!DNL Analysis Workspace] remover a formatação dos dados exportados.  <ul><li>O separador de milhar não é mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando [!DNL Analysis Workspace] Depurador | 4 de abril de 2019 | O comando Console para ativar [!DNL Analysis Workspace] o Depurador está mudando para adobetools. debug. includeoberonxml em 13 de **junho de 23 19**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Fim da vida útil [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de fim da vida [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Links encurtados de relatórios do Analytics | 14 de janeiro de 2019 | Links encurtados de relatórios do Analytics que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Desde 11 de fevereiro de 2019, os relatórios do Adobe Analytics não são mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. Se não conseguir se conectar aos relatórios do Adobe Analytics após 11 de fevereiro de 21 19, você deve atualizar o navegador para a [versão mais recente](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Desde 20 de fevereiro de 2019, a coleta de dados do Adobe Analytics não é mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará dados do Analytics de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para terem suporte ao TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes da API que usam Java 8 não devem ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que os valores de evar de comercialização adicionados a post_ product_ list durante o processamento não provoquem truncamento de valores de produto e receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam [!DNL Analytics Live Stream] pontos finais inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, [!DNL Live Stream] os pontos finais sem conexões de consumidor ativas por 90 dias podem ser desativados. Você pode entrar em contato com o Atendimento ao cliente para perguntar sobre os [!DNL Live Stream] pontos finais e, se necessário, fazer com que eles sejam reativados. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte ao TLS 1.0, recomendamos [!DNL Report Builder] que os usuários baixem a versão v 5.6.21 antes de fevereiro de 2019. Após essa data, versões anteriores não [!DNL Report Builder] funcionarão. |

## Audience Manager {#aam}

| Recurso | Descrição |
| -----------| ---------- |  
| [Ofuscação de endereço IP](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | Sua empresa pode desejar ofuscar o endereço IP em muitos países devido aos regulamentos globais de privacidade. O Audience Manager permite ofuscar os endereços IP de visitantes em uma base global ou de país por país. |
| [Integrações personalizadas de parceiros - Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | Esta página lista as integrações personalizadas entre o Audience Manager e os parceiros de dados. O Audience Manager assimila dados de cookies e de IDs de dispositivos móveis do Oracle Data Cloud para o Audience Marketplace por meio de arquivos de dados de entrada. As especificações de integração personalizadas descritas nesta página referem-se somente a arquivos de dados de entrada que contêm IDs de dispositivos móveis (IDs de dispositivos Android e IDFA). |

**Correções, melhorias e desaprovações**

* Adicionamos duas novas colunas aos Relatórios gerais para destinos. Agora, é possível encontrar a Data inicial e a Data final para um mapeamento de segmento para um destino. (AAM-44781)

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais implantem os patches mais recentes como um modo de assegurar estabilidade, segurança e desempenho superiores.

### Versões do produto

**AEM 6.5**

O AEM 6.5, disponível a partir de 8 de abril de 2019, é uma versão de atualização da base de código do AEM 6.4. Nossas atualizações mais recentes do AEM 6.5 oferecem acesso instantâneo a melhorias interessantes que ajudam sua empresa a avançar mais rapidamente.

* [Novidades no Adobe Experience Manager 6.5](https://www.adobe.com/marketing/experience-manager/new.html)
* [Notas de versão do Adobe Experience Manager 6.5](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

A versão mais recente do Cloud Manager (2019.4.0, lançada em 18 de abril de 2019) adiciona uma interface de usuário traduzida em francês, alemão e japonês. Além disso, as etapas de implantação foram aprimoradas.

* [Notas de versão do Cloud Manager 2019.4.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Manutenção do produto

**AEM 6.4.4.0**

O AEM 6.4, Service Pack 4 (6.4.4.0, lançado em 4 de abril de 2019), é uma atualização importante que inclui correções essenciais para clientes, lançadas desde a disponibilização geral do AEM 6.4 em abril de 2018.

[Notas de versão do AEM 6.4 Service Pack](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[Versões de AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**Conector AEM S3**

As instâncias do AEM com versões antigas do conector S3 Datastore podem tornar-se indisponíveis devido a falhas de acesso ao S3 após o término do suporte para o Signature versão 2 em 24 de junho de 2019. Como cliente do AEM, a Adobe recomenda que você verifique a versão do conector S3 Datastore que está sendo usada. Se necessário, atualize para uma versão recente.

Consulte [O resultado da descontinuação da versão 2 do AWS Signature para o Amazon S3](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)

### Autoajuda

**Modernização de sua base de código do AEM Sites**

Saiba como aproveitar a tecnologia AEM mais recente para modernizar a sua base de códigos do AEM Sites. [Modernizar a base de codebase dos sites existentes do Adobe Experience Manager](https://expleague.azureedge.net/labs/L761/index.html)

**Editor de Rich Text do AEM - Informações avançadas**

Descubra as práticas recomendadas de uso das configurações avançadas e do Editor de Rich Text no AEM.

Consulte [Editor de Rich Text do AEM (RTE) - Informações avançadas](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)

### Recursos adicionais

* [Página inicial de Aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notas de versão do Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campanha {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

* Campaign Classic 18.10.4 - compilação 8983
* Campaign Classic 18.10.5 - compilação 8984

Consulte [Notas de versão do Adobe Campaign Classic](http://docs.campaign.adobe.com/doc/AC/en/RN.html) para correções e melhorias.

Para obter a documentação do produto, consulte:

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [ Notas de versão](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| Recurso | Descrição |
| -----------| ---------- |  
| Pesquisa Ferramentas | (Profissionais de marketing com contas do Google Ads) A Advertising Cloud pode, opcionalmente, fazer o upload para o Google Ads de todos os dados de conversão rastreados referentes a campanhas do Google Ads que usam o serviço de rastreamento de conversões da Advertising Cloud. Os uploads diários incluem o valor de conversão definido usando o modelo de atribuição no nível do profissional de marketing. Todas as conversões enviadas são prefixadas com “Adobe_ACS_” (como “Adobe_ACS_Assinaturas” para a conversão “Assinaturas”). <br/> **Observação:** os uploads não incluirão dados de conversão enviados para a Advertising Cloud a partir de arquivos de feed. |
| Campanhas de pesquisa | O menu em **Pesquisar** &gt; **Campanhas** &gt; **Campanhas** agora é hierárquico, com Campanhas em Contas; Grupos de publicidade em Campanhas; e Palavras-chave (com submenu), Publicidades, Grupos de produtos (apenas visualizações ao vivo), Disposições (com submenu) e Segmentações automáticas em Grupos de publicidade.<br/>Nas Exibições ao vivo, Públicos-alvo e Extensões estão no mesmo nível que Contas, com seus próprios submenus. |

## Target Standard/Premium 19.5.1 {#target}

Esta versão inclui os seguintes recursos, alterações e melhorias:

(Os números de edição entre parênteses são para o uso interno da Adobe.)

### Recurso atualizações

| Recurso/Aprimoramento | Descrição |
| --- | --- |
| Compositor de experiência visual de aplicativo de página única (SPA VEC) | O SPA VEC inclui os seguintes aprimoramentos para agilizar seu trabalho e deixá-lo mais eficiente:<ul><li>É possível cancelar o carregamento de um site da web no VEC para desbloquear a edição de uma atividade. Esse aprimoramento é útil, por exemplo, caso você deseje fazer uma pequena edição na atividade, revisar os ajustes ou adicionar código personalizado, mas não quer esperar até que o site termine de carregar. (TGT-33872)</li><li>É possível executar muitas ações antes que a página seja carregada no VEC ou até mesmo se a página não carregar completamente (por exemplo, o código personalizado não é mais operacional). Ações que não podem ser editadas antes que o site seja carregado estão desabilitadas na interface do Target. (TGT-33851 e TGT-34149)</li></ul> |
| Atividades de Personalização automatizada (AP) e Direcionamento automático | É possível selecionar uma experiência para ser usada como controle ao criar uma atividade de AP ou de Direcionamento automático. Esse recurso permite rotear todo o tráfego de controle para uma experiência específica, com base na porcentagem de alocação de tráfego configurada na atividade. Como consequência, você poderá avaliar o desempenho das entregas personalizadas em relação à experiência de controle. (TGT-26572) |
| Recomendações   | Você pode usar a opção Recomendar itens comprados anteriormente ao criar a lógica de Itens visualizados recentemente. (TGT-34030) |

### Melhorias, correções e alterações

* Os ícones da barra de ferramentas são exibidos corretamente após cancelar o carregamento de uma página dentro do VEC. Se ações específicas não puderem ser executadas após a página estar completamente carregada, os ícones da barra de ferramentas associados são desabilitados. (TGT-33811)
* Agora, é possível listar e navegar mais facilmente por meio de pastas de ofertas no seletor de Ativos, em vez de navegar por uma hierarquia de pastas simples. (TGT-33725)

Consulte as [Notas de versão do Adobe Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) para obter as informações mais recentes da versão sobre os seguintes produtos:

* Target Standard e Target Premium
* Recommendations Classic

## Magento {#magento}

O Magento é uma plataforma de e-commerce que fornece a vendedores online um sistema de carrinho de compras flexível e controle sobre a aparência, o conteúdo e a funcionalidade da loja online. O Magento está disponível em uma versão de código aberto e uma versão de comércio fuller-featured.

O Magento Commerce faz parte da Adobe Commerce Cloud e oferece uma solução de eCommerce com potência empresarial, escalabilidade ilimitada e flexibilidade de código aberto para experiências B2C e B2B.

Notas de versão para as edições de Open Source e Commerce podem ser encontradas na página [Informações](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) da versão.

## Primetime {#primetime}

O Adobe Primetime é uma plataforma de TV multitelas, que ajuda empresas de mídia a criarem e monetizarem experiências de visualização personalizadas e atraentes.

[Notas de versão do Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Página inicial de ajuda do Primetime](http://help.adobe.com/en_US/primetime/)