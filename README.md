# Simulador de Valorização CUB-SC | Gessele

Simula a correção do valor pago de uma unidade pelo CUB-SC, a cada 12 meses, do mês da compra até o mês atual, com comissão.

## Atualizar índices CUB-SC

Os índices ficam no `index.html`, dentro de `<script type="application/json" id="cub-data">`, no formato `["AAAA-MM", valor CUB R$/m², variação do mês em decimal]`. Ex.: `["2026-12",3195.10,0.0038]`.
