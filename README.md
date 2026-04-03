# Conversor Cloudbeds → Orçamentador

Conversor standalone em HTML para transformar o arquivo bruto de disponibilidade do Cloudbeds (.xlsx ou .csv) no formato CSV aceito pelo Orçamentador da Pousada Viva Mar.

## O que faz
- Lê arquivo bruto do Cloudbeds
- Extrai automaticamente o bloco do quarto selecionado
- Usa:
  - Tarifário base
  - Preço para o adulto 3
  - Estadia mínima
  - Fechado para Chegada
  - Fechado para Partida
- Gera CSV compatível com o Orçamentador
- Aplica regra de segurança após a última data com preço válido

## Observações
- A linha "Preço para o adulto 3" é obrigatória
- Adulto 4 / criança 2 / criança 3 são ignorados por redundância operacional
- Arquivo de saída: `orcamento_VIVA_MAR_SAFE.csv`

## Versão atual
v7.3 Golden
