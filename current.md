---
title: Notas de versão da Adobe Experience Cloud
description: Notas de versão de junho de 2019 da Experience Cloud
doc-type: notas de versão
last-update: Junho de 2019
author: mfrei
translation-type: ht
source-git-commit: 9fbbe902ba5f95b86f8bf2eed7d3e85b4785ba6e

---


# Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>Assine a [Atualização de produto prioritária da Adobe](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 13 de junho de 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Notas de versão da Adobe Experience Platform

* Consulte as [notas de versão da Adobe Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) no Adobe.io para obter as atualizações mais recentes da [!DNL Experience Platform].

### [!DNL Experience Platform Launch]

* Consulte [!DNL Experience Platform Launch](https://docs.adobelaunch.com/) para obter as informações mais recentes.

## Analytics {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)

Para obter a documentação do produto, consulte [Página inicial de ajuda do Analytics](https://marketing.adobe.com/resources/help/pt_BR/reference/).

### Novos recursos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| **Segmentação** | Novos modelos de atribuição para dimensões na segmentação:<ul><li>Repetitivo (padrão): inclui instâncias + valores persistentes da dimensão.</li><li>Instância: inclui instâncias da dimensão.</li><li>Instância não repetitiva: inclui instâncias exclusivas (não repetitivas) da dimensão.</li></ul> [Mais](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **Segmentação** | Novos operadores de segmento: **[!UICONTROL Igual a qualquer um]** e **[!UICONTROL Não equivale a nenhum]**. [Mais…](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **Depurador** | Quando conectado com sua Adobe ID, agora há a opção de recuperar ocorrências pós-processadas no depurador da Experience Cloud. As ocorrências pós-processadas são chamadas do servidor após terem passado pelas [!UICONTROL Regras de processamento] e Regras VISTA, permitindo validar as [!UICONTROL Regras de processamento] e regras VISTA. **Observação**: se estiver usando A4T (SupplementalDataID), os dados de pós-processamento poderão levar alguns minutos para retornar. |
| **Analysis Workspace:** | Adição de novos filtros prontos para uso na pesquisa do painel à esquerda. Além do que você vê hoje (Dimensões, Métricas, Aprovado etc.), novos filtros como Métricas calculadas, Atributos do cliente, eVars, Props, Vídeo etc. foram adicionados para facilitar a localização dos componentes necessários. |
| **Analysis Workspace** | Adicionamos um aviso à visualização de Fallout que será exibido ao adicionar um segmento como um ponto de contato - determinadas combinações de contêiner de segmento inválidas resultarão em diagramas de fallout inválidos, como <ul><li>Usar um segmento com base em visitantes como um ponto de contato dentro de uma visualização de Fallout de contexto do visitante</li><li>Usar um segmento com base em visitantes como um ponto de contato dentro de uma visualização de Fallout de contexto de visitas</li><li>Usar um segmento com base em visita como um ponto de contato dentro de uma visualização de Fallout de contexto de visitas</li></ul> <br> [Mais…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html) </br> |
| **Melhorias na documentação do Analytics** | A documentação do Analytics foi reorganizada e agora inclui recursos de colaboração que permitem melhorar o conteúdo! Registre problemas com a documentação e sugera edições. O conjunto de doc foi movido para um [novo domínio](https://docs.adobe.com/content/help/en/analytics/landing/home.html). Os redirecionamentos devem estar em vigor. |
| **Novo Guia do usuário de Notas técnicas** | O [Guia do usuário de Notas técnicas](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) está disponível. Atualmente, é voltado para ajudar os usuários mais experientes com ferramentas de análise de terceiros, como o Google Analytics, a se familiarizarem com o Adobe Analytics. O guia do usuário de notas técnicas será expandido nos próximos meses para incluir conteúdo adicional. |

**Correções da Analysis Workspace**

* Correção de um problema com informações de data localizada em japonês nas visualizações [!DNL Analysis Workspace]. (AN-180114)
* Correção de um problema que ocorria após copiar e colar itens de dimensão. Pesquisas subsequentes no item resultavam em um erro. (AN-177394)
* Corrição de um problema com a opção de edição ausente nos painéis de segmentos dentros das tabelas de forma livre. (AN-171703)
* Correção de um problema com o recurso **[!UICONTROL Definir como página inicial]** que funcionava quando compartilhado com um grande conjunto de destinatários. (AN-163922)
* Correção de um problema em que as cadeias de caracteres eram recortadas verticalmente nos relatórios em tempo real. (AN-175980)

**Outras correções do Analytics**

* Correção de um problema em que os usuários administradores não conseguiam ativar os **[!UICONTROL Eventos de sucesso]**. (AN-176689)
* Correção de um problema que ocorria ao criar um alerta com a métrica **[!UICONTROL Taxa de saída]**. (AN-177476)

### Avisos importantes para administradores do Analytics {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Limites do construtor de regras de classificação | Adicionado em 5 de junho de 2019 | Esses limites não são novos, mas foram adicionados à documentação [aqui](https://marketing.adobe.com/resources/help/pt_BR/reference/classification_rule_builder.html). |
| Limites de operadores de novos segmento | Adicionado em 31 de maio de 2019 | A partir de 18 de julho de 2019, os operadores de segmento &quot;contém qualquer um de&quot;, &quot;não contém qualquer um&quot;, e &quot;contêm todos de&quot; e &quot;não contêm todos de&quot; serão limitados a 100 palavras por campo de entrada. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Futuras alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração será aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futura alteração para cálculos de _Total de relatório_ | Atualizado em 2 de maio de 2019 | Em **13 de junho de 2019**, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 13 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, segmentos que usam a lógica _existe_ ou _não existe_ poderão apresentar resultados diferentes para algumas dimensões após essa mudança. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV da [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas a **[!UICONTROL downloads CSV]** (e **[!UICONTROL Copiar para área de transferência]**) da [!DNL Analysis Workspace] para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da [!DNL Analysis Workspace] | 4 de abril de 2019 | O comando do Console para ativar o depurador da [!DNL Analysis Workspace] será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Links encurtados de relatórios do Analytics | 14 de janeiro de 2019 | Links encurtados de relatórios do Analytics que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Desde 11 de fevereiro de 2019, os relatórios do Adobe Analytics não são mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. Se não conseguir se conectar aos relatórios do Adobe Analytics após 11 de fevereiro de 2019, você deve atualizar seu navegador para a [versão mais recente](https://marketing.adobe.com/resources/help/pt_BR/sc/user/requirements.html).<br/> Desde 20 de fevereiro de 2019, a coleta de dados do Adobe Analytics não é mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará dados do Analytics de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para suportar TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes de API que usam o Java 8 não deverão ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

## Audience Manager {#aam}

**Correções, melhorias e desaprovações**

* O Audience Manager agora conta somente modelos algorítmicos ativos em relação ao limite de uso.
* Solução de um problema que fazia com que o alcance do modelo algorítmico não fosse exibido para características que usassem o modelo correspondente.
* Correção de um problema que fazia com que os conteúdos das pastas de características não fossem exibidos, e os nomes das pastas continham parantheses e/ou colchetes.
* Correção de um problema que causava a falha da classificação de características ao selecionar apenas um tipo de característica.
* Correção de um problema que fazia com que a árvore da pasta de características fosse reduzida à exibição [!UICONTROL Todas as características] sempre que você criasse ou atualizasse uma nova subpasta.
* Solução de um problema que fazia com que a permissão [!DNL VIEW_DATASOURCES] fosse necessária ao tentar excluir um parceiro.
* Solução de um problema que fazia com que a caixa de diálogo [!UICONTROL Pesquisar], na página [!UICONTROL Segmentos], pesquisasse em todas as pastas em vez da selecionada.
* Correção de um problema que impedia que a tabela [!UICONTROL Excluir características] fosse classificada pelos controles de cabeçalho, ao criar um novo modelo algorítmico.
* Solução de um problema que fazia com que o Audience Manager travasse ao executar qualquer relatório com datas de intervalo vazias.

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais implantem os patches mais recentes como um modo de assegurar estabilidade, segurança e desempenho superiores.

### Versões do produto

**Cloud Manager 2019.5.0**

A versão mais recente do Experience Cloud Manager (2019.5.0) não contém alterações funcionais significativas, embora ofereça algumas correções de erros.

* [Notas de versão do Cloud Manager 2019.5.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**Documentação XML do AEM**

A versão 3.3 da solução XML Documentation agora está disponível. Consulte as notas de versão a seguir:

***Recursos do mapa avançado***
* Adicione referências de tópico usando a opção de arrastar e soltar da exibição de repositório ou a barra horizontal e o catálogo de elementos.
* Adicione metadados a um tópico ref, prefixo, como título de navegação, formato, escopo e assim por diante.
* Clicar na referência do tópico deve abrir o tópico no editor (o modo de visualização, se não for desmarcado e desativar a edição com o checkout ativado).
* Adicione Cabeçalho de tópico e Grupo de tópico.
* Adicione marcadores com o Frontmatter (Tópicos, Prefácio, lista de livros, avisos etc.) e o Backeding (Tópicos, Apêndices, Glossário e assim por diante).
* No modo Autor, os links quebrados são realçados, as navegações estruturais são exibidas e a Exibição de tags completas é disponibilizada.
* Capacidade de definir atributos de nível de mapa.
* Capacidade de definir Título/BookTitle.
* Suporte para Reltables com a capacidade de adicionar cabeçalho rel, colunas, arrastar/soltar tópicos do mapa e repositório para a tabela rel, definir links, escopo e outros parâmetros para os links, reordenar links dentro da célula.
* Widget de barra de ferramentas para inserir antes, inserir depois e inserir elemento.
* Realçar se uma condição for aplicada em um tópico.
* Capacidade de editar vários mapas por vez (cada mapa é aberto como uma guia no mesmo navegador).
* No painel de mapa e na exibição de repositório, ao passar o mouse - mostrar o título completo do tópico e o nome do arquivo.

***Exibição de Tags completa***

* Insira novas tags entre dois elementos.
* Copie e cole tags.
* Arraste e solte tags em posições permitidas e não permitidas dentro de um arquivo.
* Expandir e recolher tags.

***Aprimoramentos de pesquisa específicos de DITA***

* Uma ferramenta de serialização foi fornecida para reindexar o conteúdo selecionado
* Os usuários podem usar `contains` e `exact match` em sua pesquisa. Além de poderem pesquisar usando os seguintes parâmetros. :
   * Metadados de ativos. Por exemplo, `file name`, `title` ou qualquer metadado personalizado definido pelo cliente.
   * Nome do atributo DITA e seu valor. Por exemplo, `platform=winOS`.
   * Nome do elemento DITA e seu valor. Por exemplo, `author = Joe Smith`.
   * Nome do elemento DITA e seu atributo aplicado. Por exemplo, tabela com o par nome/valor do atributo product=SpaceBase aplicado a ele.
   * Tópico DITA e metadados do mapa.
   * Tipo de informações DITA. Por exemplo, mapa, tópico, conceito e assim por diante.
   * Caminho da pasta raiz onde o ativo está localizado.
   * Estado do documento.
   * Status com checked-out.
   * Intervalo de datas modificado.
   * Tags do CQ.
* É possível criar consultas complexas combinando um ou mais parâmetros de pesquisa acima.

***Revisar alterações do recurso***

* Dicas para um revisor:
   * Importe todos os comentários e incorpore as alterações de revisões em andamento antes de atualizar para o build 3.3.
   * Certifique-se de que várias guias não estejam abertas no editor.
   * Certifique-se de que a exibição Tags completas não esteja ativada.
   * Não alterne entre o modo Autor e o modo Origem enquanto a revisão estiver em andamento.
* Capacidade de especificar a versão do meu conteúdo que deve ser revisada.
* Capacidade de escolher as versões dos tópicos selecionados com base em uma linha de base, data, rótulo ou versão ativa no momento, ou especificar as versões de cada um dos tópicos ao criar uma revisão.
* Capacidade de enviar o mesmo tópico/mapa para revisão várias vezes e o autor pode acessar todas as revisões no painel de revisão do editor.
* Como iniciador, a capacidade de transmitir uma versão posterior do conteúdo para os revisores. Os revisores receberão uma notificação quando um novo conteúdo for transmitido para revisão.
* Como autor, o usuário poderá visualizar os comentários de revisão de todas as versões de seu conteúdo no painel de revisão do editor. Os autores poderão filtrar os comentários por número de versão.
* Como um usuário autor, terá a capacidade de exibir e importar comentários em uma versão mais antiga do conteúdo no editor, que estava sob revisão.

***Diversos***

* Crie uma nova pasta, tópico ou mapa na exibição Repositório.
* Exibir na interface do usuário do Assest - adicione uma opção de menu para pastas e tópicos - &quot;Exibir na interface do usuário do Assets&quot;. Essa opção abre a interface de usuário do Assets, na qual o usuário pode visualizar a árvore de conteúdo à esquerda e todos os arquivos na exibição em lista à direita com todos os menus de ativos na parte superior.
* Um painel Revisão agora está disponível como um Bloco no projeto DITA, que acompanha a revisão em um Nível de revisor e em um Nível de tarefa de revisão.
* Adição da capacidade de converter IDML em DITA.
* Forneça a API para aplicar determinado rótulo em todas as versões especificadas em uma linha de base.
* Ative um evento depois que a conversão de XHTML/DOCX em DITA estiver concluída. É possível usar esse evento para adicionar atributos especializados ao conteúdo convertido, ou para qualquer outra lógica personalizada que você precise implementar.
* Melhorias na guia de Desempenho da linha de base. Primeiro, o usuário precisa executar um script em todas as linhas de base existentes.
* Foram feitos aprimoramentos na conversão de XHTML em DITA.
* Descarregamento do DITA-OT para Otimização de publicação.
* Correção da classificação na coluna Tipo da exibição em lista.
* Capacidade de lidar com estilos em cascata na conversão de Word em DITA.

### Comunidade

**[Série de webnário Cloud Manager Skill Builder](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

Interessado em saber como os processos do DevOps podem simplificar as atividades diárias do gerenciamento do Adobe Experience Manager na nuvem? O Cloud Manager fornece a funcionalidade nativa de nuvem de primeira geração do Adobe Experience Manager que permite a agilidade da nuvem, seja se a sua organização estiver iniciando a transformação DevOps ou a procura de estratégias para aumentar os processos DevOps existentes.

[Nesta série mensal](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/), você pode aprender diretamente da equipe de produtos da Adobe sobre como começar a usar os recursos do Cloud Manager para simplificar o gerenciamento do Adobe Experience Manager na nuvem.

Você aprenderá o seguinte:
* Como começar a usar o Cloud Manager e configurar o CI/CD Pipeline
* Como funciona o Dimensionamento automático e a Entrega de serviço transparente e como eles podem simplificar o gerenciamento de ambiente do Adobe Experience Manager na nuvem
* Como usar a API do Cloud Manager e integrar os processos DevOps existentes

### Recursos adicionais

* [Tela inicial de Aprendizagem e Suporte do AEM 6.5](https://helpx.adobe.com/br/support/experience-manager/6-5.html)
* [Tela inicial de Aprendizagem e Suporte do AEM 6.4](https://helpx.adobe.com/br/support/experience-manager/6-4.html)
* [Tela inicial de Aprendizagem e Suporte do AEM 6.3](https://helpx.adobe.com/br/support/experience-manager/6-3.html)
* [Tela inicial de Aprendizagem e Suporte do AEM 6.2](https://helpx.adobe.com/br/support/experience-manager/6-2.html)
* [Guia de usuário do Cloud Manager](https://helpx.adobe.com/br/experience-manager/cloud-manager/user-guide.html)
* [Documentação de versões anteriores do AEM](https://helpx.adobe.com/br/experience-manager/aem-previous-versions.html)
* [Notas de versão do sistema de publicação do Scene7](https://marketing.adobe.com/resources/help/pt_BR/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### [!DNL Campaign Classic]Versão da primavera do 19.1

| Recurso | Descrição |
| ------------- | ----------- |
| Painel de controle | Para aumentar a eficiência do trabalho como usuário administrador, gerencie as configurações dos servidores SFTP monitorando o armazenamento, os endereços IP na lista de permissões e instalando chaves SSH para cada instância. Observe que o Painel de controle está disponível somente para clientes hospedados no AWS a partir de hoje. [Faça logon por meio da Experience Cloud](https://experiencecloud.adobe.com/campaign/controlpanel/). <br> Para obter mais informações, consulte a [documentação detalhada](https://helpx.adobe.com/br/campaign/kb/control-panel.html) e o [tutorial em vídeo](https://helpx.adobe.com/br/campaign/kt/acc/using/acc-control-panel-video-use.html). |
| Trilha de auditoria | Como administrador, aumente a produtividade ao monitorar e gerenciar alterações feitas na instância do Adobe Campaign Classic. A Trilha de auditoria registrará ações feitas no Esquema de origem, Fluxo de trabalho e Opção. Veja rapidamente se um elemento foi criado, modificado ou excluído.<br>Para obter mais informações, consulte a [documentação detalhada](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) e o [tutorial em vídeo](https://helpx.adobe.com/br/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html). |
| Grade de proteção, robustez e escalonabilidade | Uma série de melhorias foi adicionada ao [!DNL Campaign Classic]. Os aprimoramentos na grade de proteção, robustez e escalonabilidade estão listados nas [Notas de versão do Adobe Campaign Classic](https://docs.campaign.adobe.com/doc/AC/en/RN.html). |
| Mensagens SMS seguras (TLS) | O SMS seguro agora é suportado por meio do Conector SMPP genérico estendido. Isso permite uma conexão criptografada com o provedor. <br> Para obter mais informações, consulte a [documentação detalhada](https://helpx.adobe.com/br/campaign/kb/sms-connector-protocol-and-settings.html). |
| Atualização da matriz de compatibilidade | Com esta nova versão, o Adobe Campaign agora oferece suporte aos seguintes sistemas de banco de dados. Consulte a [Matiz de compatibilidade](https://helpx.adobe.com/br/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18c</li><li>MySQL 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>PostgreSQL 11</li></ul> |

Consulte as [Notas de versão do Adobe Campaign Classic](http://docs.campaign.adobe.com/doc/AC/en/RN.html) para obter correções e melhorias.

### [!DNL Campaign Standard]Versão da primavera do 19.2

| Recurso | Descrição |
| ------------- | ----------- |
| Painel de controle | Para ajudar a aumentar a eficiência do seu trabalho como usuário administrador, é possível monitorar facilmente a capacidade e gerenciar as configurações de suas instâncias (começando pelo gerenciamento de servidores SFTP). <br> Para obter mais informações, consulte a [documentação detalhada](https://helpx.adobe.com/br/campaign/kb/control-panel.html) e o [tutorial em vídeo](https://helpx.adobe.com/br/campaign/kt/acs/using/acs-control-panel-video-use.html). |
| Notificações locais | As mensagens de notificação locais permitem informar aos usuários quando os novos dados são disponibilizados em seus aplicativos móveis, mesmo sem ter acesso à Internet ou o aplicativo móvel em execução em primeiro plano. As notificações locais são acionadas por um aplicativo móvel em um determinado momento e dependendo de um evento.<br>Para obter mais informações, consulte a [documentação detalhada](https://helpx.adobe.com/br/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| Aprimoramento do fluxo de trabalho - Adicione uma carga à atividade de sinal externo | Inicie um fluxo de trabalho com uma carga quando as condições definidas forem cumpridas com êxito de outro fluxo de trabalho ou uma chamada da API REST para integrar com seus sistemas externos. Isso também inclui uma nova atividade de teste, na qual é possível executar testes nesta funcionalidade. <br>Para obter mais informações, consulte a [documentação detalhada](https://helpx.adobe.com/br/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) e o [tutorial em vídeo](https://helpx.adobe.com/br/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html). |
| Aprimoramento das páginas de aterrissagem - reCAPTCHA do Google | Aproveite o Google reCAPTCHA para evitar spam em suas páginas de aterrissagem sem solicitar uma ação de seus clientes. <br>Para obter mais informações, consulte a [documentação detalhada](https://helpx.adobe.com/br/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

Para obter a documentação do produto, consulte:

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/br/support/campaign/standard.html) - [Notas de versão](https://helpx.adobe.com/br/campaign/standard/rn/using/release-notes.html) - [Vídeos de recursos](https://helpx.adobe.com/br/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/br/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de recurso](https://helpx.adobe.com/br/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* O TLS 1.0 foi desativado em todos os servidores da Adobe. Para dispositivos Android 4.x se conectares aos serviços da Adobe por meio do SSL, o SDK agora forçará o TLS 1.1/TLS 1.2 ao estabelecer um handshake.

## Advertising Cloud {#adcloud}

Última atualização: 5 de junho de 2019, para a versão de 8 de junho

| Produto | Recurso | Descrição |
| -----------| ---------- | ----------  |
| Campanhas de pesquisa, classificações de rótulos e restrições | Atalhos de teclado | Agora você pode usar o atalho <b>Shift + clique</b> para selecionar várias linhas consecutivas, e <b>Ctrl + clique</b> para selecionar várias linhas não consecutivas. |
|  | Selecionar tudo vs. Selecionar tudo na página | Nas tabelas de dados, ao selecionar a caixa de seleção superior para selecionar todas as linhas, o novo padrão é selecionar todas as linhas na página (se você estiver visualizando 25 linhas, 50 linhas, 100 linhas, 200 linhas ou Rolagem contínua). Ainda há uma opção para selecionar todas as linhas disponíveis. |
| Exibições padrão, visualizações personalizadas e configurações de personalização de coluna independente | Reorganização de coluna | Os novos botões Para cima e Para baixo permitem reordenar as colunas. Ainda é possível arrastar e soltar colunas para reordená-las, como anteriormente. |

## Target Standard/Premium 19.6.1 (25 de junho de 2019) {#target}

Consulte as Notas de versão do Adobe Target para obter as informações da versão mais recente:

[Notas de versão do Target (pré-lançamento)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Notas de versão do Target (atual)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

O Magento é uma plataforma de e-commerce que fornece a vendedores online um sistema de carrinho de compras flexível e controle sobre a aparência, o conteúdo e a funcionalidade da loja online. O Magento está disponível em uma versão de código aberto e uma versão de comércio fuller-featured.

O Magento Commerce faz parte da Adobe Commerce Cloud e oferece uma solução de eCommerce com potência empresarial, escalabilidade ilimitada e flexibilidade de código aberto para experiências B2C e B2B.

Notas de versão das edições de Open Source e Commerce podem ser encontradas na página [Informações de versão](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html).

## Primetime {#primetime}

O Adobe Primetime é uma plataforma de TV multitelas, que ajuda empresas de mídia a criarem e monetizarem experiências de visualização personalizadas e atraentes.

[Notas de versão do Primetime](https://helpx.adobe.com/br/support/primetime.html)
[Página inicial da Ajuda do Primetime](https://helpx.adobe.com/br/support/primetime.html)
