---
date: 2026-06-12
tipo: estudo
areas:
  - Pediatria
  - Neonatologia
publish: true
---
A reanimação deve sermpre seguir passos lógicos já pré-estabelecidos.

## Equipe
Deve-se sempre ter **uma equipe para cada bebê**. (Atenção para gemelares)
Deve-se sempre considerar os **Fatores de Risco Perinatais**.
- **Sem fatores de Risco**: 1 profissional habilitado nas manobras de reanimação
- **Com fatores de Risco**: 2-3 profissionais habilitados nas manobras de reanimação
	- Ao menos 1 Pediatra que sabe intubar.

## Considerações Iniciais

### Vitalidade após nascimento
Verifica-se 3 parâmetros. Necessita dos 3
- Respiração / Choro
- Movimento respiratório regular
- Tônus

## Na Sala de Parto
O protocolo muda se for $\ge$ 34 semanas ou < 34 semanas. Mas de maneira geral, segue a sequência abaixo.

### Bebê com $\ge$ 34 semanas

```mermaid
graph TD
subgraph Vitalidade
	A(RN - Boa Vitalidade)
	B(RN - Má Vitalidade)
end
C(Clamp Oportuno > 60s)
D(Ordenha 20 cm / 2s +<br/>Clamp Precoce > 30s)
E{{Estímulo Tátil<br/>em dorso 15s}}
H(Reanimação)

A --> C
B --> E
E -- Respirar /<br/>Tônus em Flexão --> C
E -- Não Respirou e/ou<br/>Hipotônico --> D
D --> H
```

> [!error] Insuficiência Placentária = Clamp Imediato
### Bebê com $<$ 34 semanas

```mermaid
graph TD
subgraph "Vitalidade < 34 sem"
	A(Boa Vitalidade)
	B(Má Vitalidade)
end
C(Clamp Oportuno > 60s)
D(Clamp Precoce > 30s)
E{{Estímulo Tátil<br/>em dorso 15s}}

A --> C
B --> E
E -- Respirar /<br/>Tônus em Flexão --> C
E --> F[Não Respirou e/ou<br/>Hipotônico]
F --> G[".>= 28 semanas"]
F --> H["< 28 semanas"]
G -- "Ordenha" --> D
H --> D
D --> I(Reanimação)
```


> [!attention]- Ventilar é mais importante que Coração
> Tempo é cérebro

**Pilares**
