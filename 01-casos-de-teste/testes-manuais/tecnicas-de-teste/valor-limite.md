 Análise de Valor Limite

 O que é
Técnica de teste focada nos valores extremos (limites) de um campo, onde normalmente ocorrem mais falhas.

 Quando usar
Quando um campo possui valores mínimos e máximos bem definidos.

 Exemplo prático
Campo: Idade permitida (18 a 65)

 Valores testados
- 17 → inválido (abaixo do mínimo)
- 18 → válido (limite mínimo)
- 19 → válido
- 64 → válido
- 65 → válido (limite máximo)
- 66 → inválido (acima do máximo)

