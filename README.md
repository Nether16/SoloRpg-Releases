<div align="center">

# SoloRPG para Firecast

### Versao atual: 1.8.9

[![Baixar SoloRPG](https://img.shields.io/badge/BAIXAR_SOLORPG-00b8d9?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/Nether16/SoloRpg-Releases/main/output/SoloRpg.rpk)

**Clique no botao acima e o download comeca. Nao precisa entender ou usar o GitHub.**

</div>

## Como instalar

1. Clique em **BAIXAR SOLORPG**.
2. Aguarde o arquivo `SoloRpg.rpk` terminar de baixar.
3. Abra o arquivo baixado.
4. Confirme a instalacao no Firecast.
5. Feche e abra novamente a ficha caso ela ja estivesse aberta.

## Atualizacao

Para atualizar, baixe o arquivo novamente e abra o novo `SoloRpg.rpk`. O Firecast substitui a versao anterior.

## Informacoes do arquivo

- **Versao:** 1.8.9
- **Arquivo:** `SoloRpg.rpk`
- **Compatibilidade:** Firecast 8

O arquivo desta pagina e gerado diretamente do projeto oficial do SoloRPG.

## Patch 1.8.9

- A transferencia da conta agora permite escolher entre SoloCoins e itens do cofre no mesmo painel.
- Itens transferiveis podem ser enviados em quantidade para outra conta usando o mesmo destino e PIN transacional.
- O banco move os itens atomicamente, valida propriedade e estoque e impede entregas duplicadas por repeticao da requisicao.
- Compras de pacotes com varios itens entregam todos os componentes diretamente no cofre e informam a quantidade recebida.
- Corrigidos erros `401 Unauthorized` e `Forbidden` nas operacoes SoloCoin protegidas por PIN valido.

## Patch 1.8.8

- A Loja agora mantem o catalogo em memoria e cria somente 20 cards por pagina, reduzindo o tempo de abertura e o travamento da ficha.
- A paginacao da Loja ganhou botoes numericos, anterior e proximo fora da grade; filtros e ordenacao trabalham direto no cache.
- Compras atualizam saldo e estoque localmente sem baixar novamente o catalogo inteiro.
- Todos os Materiais Rank F e E foram adicionados a Loja Base com venda ilimitada e preco do catalogo.
- Inventario Geral e Materiais receberam pesquisa e filtros, com cards alinhados ao mesmo padrao visual dos equipamentos.
- Corrigido o salvamento da imagem da Propriedade e reforcado o bloqueio modal dos pop-ups internos da ficha.
- Incluido o tipo Abissal para Anjo Caido no catalogo de racas.

## Patch 1.8.7

- Companion Ascendente: corrigida a selecao, o salvamento e o recebimento da segunda recompensa, com multiplicador x4 e tempos de espera individuais.
- Aba Cacador recuperada e incluida no pacote recompilado da ficha.
- Corrigida no servidor a autenticacao das contas SoloCoin ativas, liberando compras e transferencias com PIN valido sem remover as protecoes existentes.
- Doacoes de itens agora consultam o banco para listar suas outras fichas e as fichas de jogadores online, inclusive quando estao ocultas na Biblioteca.
- Compras de loot boxes mostram os premios recebidos na confirmacao e no chat.
- Incluido suporte ao teto de nivel do rank Z.

## Patch 1.8.6

- A confirmacao do Daily Reward agora mostra separadamente a recompensa diaria, o premio semanal e cada recompensa de companion.
- Materiais semanais exibem o nome exato do item sorteado, evitando que uma recompensa entregue pareca ausente.
- Validado no banco que recompensas semanais de Nivel, Nexus, Treino, Material e Ticket sao registradas e aplicadas corretamente.

## Patch 1.8.5

- O multiplicador de treino agora aumenta somente o custo e a recompensa, mantendo 7, 14 ou 21 perguntas conforme a dificuldade.
- O treino por IA recebeu tempo limite e retorno local para evitar carregamento infinito quando o provedor falhar.
- A producao da Base ficou mais clara, mostrando custos, recompensas, postos participantes e efeitos ativos separadamente.
- Trocar uma habilidade entre conjuracao e ativacao no Solo App nao apaga mais o custo de MP.
- Os textos das passivas raciais foram limpos sem remover os campos, preparando a reformulacao do sistema de racas.

## Patch 1.8.4

- Corrigida a identificacao de mestre ao salvar itens e quantidades no inventario.
- Operacoes da ficha agora enviam a identidade Firecast para validacao no banco.
- Corrigida a quantidade do Ticket de Item de Craft Rank B entregue pelo companion Eirik Vhalen.

## Patch 1.8.3

- Adicionada auditoria central das fichas, com snapshots e historico de alteracoes importantes.
- O SoloApp ganhou uma tela para consultar personagens, categorias, origens e registros da auditoria.
- Controle Banco e Controle NPC deixaram de solicitar PIN e validam o mestre cadastrado pelo banco.
- As protecoes financeiras do Banco SoloCoin continuam isoladas e preservadas.
- Corrigido o salvamento de MundoSync e recompilados os plugins e a ficha sem alertas.

## Patch 1.8.2

- O resumo da Propriedade agora mostra corretamente os Slots ocupados e comprados.
- Trabalhadores e proprietarios da Base foram alinhados aos Vinculos selados.
- O responsavel de um Slot fica travado ate que o Slot seja limpo explicitamente.
- A ficha representada por um Vinculo Player foi separada dos personagens que possuem o Vinculo.
- Corrigidos fluxos de Daily Reward, treino por IA e carregamento das integracoes Supabase.
- SoloApp, Controle Banco e Controle NPC receberam ajustes de estabilidade e foram recompilados.

## Patch de seguranca 1.8.1

- Permissoes de mestre agora sao confirmadas pelo banco de dados.
- Operacoes criticas da ficha exigem uma credencial individual validada no servidor.
- A credencial completa fica somente na ficha; o banco armazena apenas seu hash.
- Alterar uma copia local do plugin nao concede permissao para modificar os dados protegidos.
- Controle Banco 1.1 provisiona e valida automaticamente as credenciais das fichas existentes.

## Novidades da 1.8
- Novo sessão para marca sessões dentro da ficha
- Nova aba de Base
- Daily Rewards


## Novidades da 1.7.7

- A aba Cacador recebeu um popup completo de detalhes da habilidade, com identidade, requisitos, custos por ativa, acerto, dano calculado, efeitos, lore, ativacoes e desativacoes.
- O resumo de dano agora calcula as escalas usando a ficha do personagem e exibe formula, faixa total e media sem precisar rolar a habilidade.
- O inventario passou a abrir os itens em um popup centralizado, reunindo edicao, uso, venda, doacao, exclusao, dados tecnicos, craft relacionado e habilidades vinculadas.
- Consumiveis mantem um atalho de uso no card, enquanto venda parcial e doacao respeitam a quantidade possuida e so alteram a ficha depois da confirmacao do banco.
- Itens podem ser doados entre fichas pelo Firecast e pelo Solo App em uma operacao atomica, preservando pilhas, IDs e vinculo com o catalogo.
- O controle de itens do Solo App ganhou abas para inventario e catalogo, pesquisa e filtros por processo, tipo, rank e destino.
- O carregamento de detalhes da Loja foi ampliado para incluir recuperacao, bonus, craft, ingredientes canonicos e habilidades do item.
- As regras de craft foram ajustadas para validar processo, material principal, livro e ferramentas sem consumir entradas em uma tentativa invalida.
- Aplicados ajustes visuais e de estabilidade nos cards do inventario, tabelas do popup de habilidade e verificacao de presets ativos.

## Novidades da 1.7.6

- O inventario da ficha agora permite doar itens diretamente para outra ficha, escolhendo o destinatario e a quantidade.
- As doacoes atualizam os dois inventarios na mesma operacao, preservam os IDs existentes e mantem as pilhas zeradas.
- O Controle de Itens recebeu filtros por posse, processo, tipo, rank e destino.
- Itens que ja estao no inventario e itens disponiveis no catalogo agora aparecem em grupos separados e recolhiveis.
- Os cards foram reorganizados para facilitar a leitura, com estado, informacoes e acoes melhor distribuidos.
- O botao de doar aparece apenas nos itens realmente possuidos pelo personagem.
- O sistema de craft e refinamento recebeu as regras canonicas de matrizes, materiais principais, ferramentas, livros, rank e efeitos.

## Novidades da 1.7.5

- Habilidades inativas continuam visiveis no Cacador, recebem identificacao visual e nao podem ser conjuradas ate serem ativadas pelo mestre.
- Presets de habilidade agora permanecem ativos ao criar, copiar, duplicar e salvar; o mestre ainda pode desativar a habilidade depois de aplica-la ao personagem.
- A Loja agora permite comprar varias unidades de uma vez, calcula o valor total e respeita estoque normal ou ilimitado.
- Cards e detalhes da Loja passaram a informar em qual aba do inventario o item sera entregue.
- Dados do personagem agora sincronizam grupo, data no mundo e ponto de continuidade com o controle central.
- A aba de IA do mestre recebeu Save State para registrar e restaurar recursos, atributos base e distribuicao de pontos.
- O inventario reforca a sincronizacao de quantidade e atributo escolhido dos itens personalizados.
- O catalogo VIP Absolute agora lista somente os produtos Absolute e mantem esses produtos fora da loja SoloCoin comum.
- Aplicados ajustes de estabilidade nas recompensas, na sincronizacao de habilidades e no carregamento das integracoes Supabase.

## Patch 1.7.4

- Correcoes leves de bugs e ajustes nas opcoes de skill das requisicoes.

## Novidades da 1.7.3

- Famas agora sao sincronizadas pelo Supabase e podem adicionar suas habilidades ao Cacador conforme o nivel da fama.
- Itens receberam bonus de subatributos e os calculos foram alinhados entre ficha, inventario e ControleNPC.
- Fluxos de VIP e SoloCoin foram reforcados, incluindo planos por produto, vencimento mensal e suporte a multiplos VIPs ativos.
- O SoloApp recebeu o gerador e catalogo de NPCs e pets, com ocupacoes administradas pelo banco.
- Requisicoes de skill podem ser aprovadas sem consumir pontos de pos-sessao; apenas atividades de pos-sessao usam esses pontos.
- Corrigida a paginacao da Loja que podia causar assertion do RecordList ao carregar ou filtrar itens.
- SoloRPG, ControleBanco e ControleNPC foram recompilados sem alertas do RDK.

## Novidades da 1.7.2

- A Loja recebeu pesquisa, filtros de preco, rank, tipo e finalidade, alem de novas opcoes de ordenacao.
- Cards e detalhes dos itens foram reorganizados para facilitar leitura, compra e comparacao.
- O popup do item agora exibe recuperacao, dano, bonus de atributo e uma previa das habilidades vinculadas.
- Valores de dinheiro agora usam separadores de milhar; mensagens de recompensas negativas preservam corretamente o sinal.
- O sistema de rank passou a guardar niveis sobressalentes ao atingir o teto e reaplica-los quando houver espaco.
- Compras na Loja SoloCoin agora sao anunciadas no chat do Firecast.
- Carregar habilidades cria uma pasta vazia para o personagem quando nenhuma pasta estiver vinculada, usando o nome do item da Biblioteca.
- A criacao automatica de pasta foi limitada a uma operacao especifica no Supabase, sem liberar edicao de rank, classe ou habilidades.

## Novidades da 1.7.1

- A opcao de ocultar mensagens de recursos agora silencia completamente o envio ao chat.
- A configuracao permanece salva na ficha ate o mestre desmarcar a opcao.
- A checkbox continua visivel exclusivamente para o mestre.

## Novidades da 1.7

- A calculadora de Vida, Mana, Folego e recurso customizado agora trabalha com valor fixo ou porcentagem.
- Alteracoes manuais de recursos recebem mensagens formatadas no chat com valor anterior e atual.
- Mestres podem manter alteracoes de recursos de NPCs visiveis somente no proprio chat.
- Bonus de transformacoes e ativacoes agora afetam STR, VIT, INT, STK, FAD e ENG corretamente.
- Corrigida a exibicao do custo de MP durante a conjuracao de habilidades.
- O sistema SoloCoin agora mostra mensagens detalhadas para PIN invalido, operacao ausente e erros retornados pelo Supabase.
- Removidos avisos temporarios de depuracao da conjuracao.

## Novidades da 1.6.23

- Requisicoes de skill e pos-sessao agora possuem telas separadas no ControleBanco.
- Cada tela foi dividida nas abas Ativos e Em espera.
- Adicionado o estado Em espera, com opcoes para aguardar ou retomar a analise.
- Requisicoes pendentes ou em espera nao consomem slots de habilidade.
- Ajustados os indicadores visuais e a sincronizacao das filas de requisicoes.

## Novidades da 1.6.22

- Aplicados patches leves de estabilidade e sincronizacao.
- Personalizacoes locais dos vinculos agora permanecem ao recarregar os dados.

## Novidades da 1.6.20

- Adicionada confirmacao Sim/Nao antes de vender um item.
- A confirmacao mostra o preco original e o valor recebido na venda.
- Cancelar a venda mantem o item e o dinheiro sem alteracoes.

## Novidades da 1.6.19

- Corrigida a venda de itens sem credito de dinheiro ou exclusao indevida.
- Itens vendidos agora rendem metade do preco original.
- Itens locais deixam de ser procurados incorretamente no inventario remoto.
- Itens da aba Geral agora apenas sao mostrados no chat e nao sao consumidos.

## Novidades da 1.6.18

- Corrigidos os erros genericos de Bad Request nas operacoes SoloCoin.
- Mensagens de PIN incorreto ou desatualizado agora aparecem claramente.
- PINs copiados com espacos ou quebra de linha passam a ser normalizados.
- Itens aplicados pelo SoloCoin agora entram na categoria correta do inventario.
- Corrigido o erro ao salvar itens remotos com tipo desconhecido.
- Atualizados o SoloRPG App, ControleBanco, catalogos e migrations do Supabase.

## Novidades da 1.6.17

- A conjuracao agora envia os quatro textos de efeito de ativacao preenchidos.
- Cada descricao aparece em seu proprio bloco, separada por uma linha em branco.

## Novidades da 1.6.16

- Corrigida a compra de slots de personagem na loja SoloCoin.
- Requisicoes de desenvolvimento e pos-sessao agora preservam melhor status, tipo e custo.
- Ajustes na sincronizacao de habilidades, equipamentos e alinhamentos.

## Novidades da 1.6.15

- Controle de grupos, agenda recorrente, sessoes e historico pelo HabilidadesWeb.
- Controle de fim de sessao com nivel, dinheiro, treino e pontos de pos-sessao.
- Loja de Nexus integrada a ficha, com catalogo, detalhes e compra de itens.
- Requisicoes de desenvolvimento e pos-sessao organizadas em listas para jogador e mestre.
- Gerador de portais com configuracoes, imagens e habilidades de criaturas salvas no Supabase.
- Habilidades de itens, modos de ativacao e sincronizacao ao equipar ou desequipar.
- Estado ativo ou inativo por habilidade, com regras iniciais para jogadores, NPCs e presets.
- Versao Essencial atualizada com habilidades, grupos, recompensas e gerador de portais.
