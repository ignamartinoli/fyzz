# Sets 

## Presupuesto (Decimal)

### Inadecuado

- for 0 <= x <= 30 is
$$(-(x / 30) + 1)$$

### Marginal

- $((x / 15) - (4 / 3))$ for x between 20 and 35
- $((- (x / 15)) + (50 / 15))$ for 35 <= x <= 50 is

### Adecuado

- $((x / 30) - (4 / 3))$ for 40 <= x <= 70
- $1$ para x entre 70 y 90

## Staff (Entero)

### Pequeño

- $1$ FOR 0 <= x <= 6
- $((- (x / 8)) + (7 / 4))$ para 6 <= x <= 14

### Grande

- $((x / 8) - (3 / 4))$ for 6 <= x <= 14
- $1$ FOR x BETWEEN 14 AND 20.

# Objetivo

## Riesgo

### Bajo

- $1$ para x entre 0 y 30
- $((- (x / 10)) + 4)$ para x entre 30 y 40

### Medio

- $((x / 10) + 3)$ para x entre 30 y 40
- $1$ para 40 <= x <= 60
- $((- (x / 10)) + 7)$ para x entre 60 y 70

### Alto

- $((x / 10) - 6)$ para 60 <= x <= 70
- $1$ para x entre 70 y 100

# Reglas

- If presupuesto is Adecuado or the Staff is Pequeño, then riesgo is low
- SI EL presupuesto ES marginal Y Staff ES grande, ENTONCES el riesgo es Medio.
- Si el presupuesto es inadecuado, el riesgo es grande.
