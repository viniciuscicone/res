
```javascript
let INDICE = 12, SOMA = 0, K = 1;

while (K < INDICE) {
    K = K + 1;
    SOMA = SOMA + K;
}

console.log(SOMA);
//valor de SOMA será 77
```

    a) 1, 3, 5, 7, 9
    
    
    b) 2, 4, 8, 16, 32, 64, 128
    
    
    c) 0, 1, 4, 9, 16, 25, 36, 49
    
    
    d) 4, 16, 36, 64, 100
    
    
    e) 1, 1, 2, 3, 5, 8, 13
    
    
    f) 2, 10, 12, 16, 17, 18, 19, 20

```javascript
    const faturamentoDiario = [];
    
    const faturamentoFiltrado = faturamentoDiario.filter(valor => valor > 0);
    
    const menorFaturamento = Math.min(...faturamentoFiltrado);
    const maiorFaturamento = Math.max(...faturamentoFiltrado);
    const mediaAnual = faturamentoFiltrado.reduce((acc, valor) => acc + valor, 0) / faturamentoFiltrado.length;
    const diasAcimaDaMedia = faturamentoFiltrado.filter(valor => valor > mediaAnual).length;
    
    console.log(`Menor faturamento: ${menorFaturamento}`);
    console.log(`Maior faturamento: ${maiorFaturamento}`);
    console.log(`Dias acima da média: ${diasAcimaDaMedia}`);

```



```sql
SELECT c.id, c.nome, t.numero
FROM Clientes c
JOIN Telefones t ON c.id = t.cliente_id
JOIN Estados e ON c.estado_id = e.id
WHERE e.sigla = 'SP';
```
```
Distância total: 125 km
Velocidade do carro: 90 km/h
Velocidade do caminhão: 80 km/h
Tempo adicional do carro nos pedágios: 3 pedágios * 5 minutos = 15 minutos = 0,25 horas
Tempo de viagem sem pedágios:

Carro: ( \frac{125}{90} \approx 1,39 ) horas
Caminhão: ( \frac{125}{80} \approx 1,56 ) horas
Tempo de viagem com pedágios:

Carro: ( 1,39 + 0,25 = 1,64 ) horas
Distância percorrida até se cruzarem:

Carro: ( 90 \times 1,64 \approx 147,6 ) km
Caminhão: ( 80 \times 1,56 \approx 124,8 ) km
```




