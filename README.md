<div align="center">

# SoloRPG para Firecast

### Versao atual: 1.7.1

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

- **Versao:** 1.7.1
- **Arquivo:** `SoloRpg.rpk`
- **Compatibilidade:** Firecast 8

O arquivo desta pagina e gerado diretamente do projeto oficial do SoloRPG.

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
