# Teste da técnica Fimathe através de automação

Esse algoritmo para MT5 usa a técnica Fimathe, do Marcelo Ferreira, adaptado para não depender de um humano para determinar o canal de referência. Em vez disso, pega um intervalo de candles, subdivide-o a partir de máximas diferenças, calcula e ordena as distâncias, e usa a distância mediana como canal de referência.
Foi criado no intuito exclusivo de testar o método. Não está pronto para negociações sérias, embora mostre pontencial por, mesmo não usando martigale, se manter acima do prejuízo total que se obteria com lances aleatórios com pagamento de spread.
