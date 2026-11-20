# Banco

## Comandos (Administrador)

| Comando | Qué hace |
|---|---|
| `/bancocongelar IBAN` | Congela una cuenta (no puede mover dinero) |
| `/bancodescongelar IBAN` | La descongela |
| `/bancosaldo IBAN\|trabajo\|banda` | Ver el saldo de una cuenta personal, de empresa o de banda |

Dar o quitar dinero a un jugador: panel → ficha → Dinero (efectivo o banco).

## Cifras del sistema

| Parte | Valor |
|---|---|
| Sucursales | 8 (Pacific Standard, 6 Fleeca, Blaine County). Préstamos solo en Pacific Standard y Blaine County |
| Ahorro | 0,5 % cada 24 h reales sobre el saldo (hasta 500.000 $). Máx. 2 cuentas |
| Compartidas | Máx. 3 cuentas y 8 cotitulares |
| Contactos | Máx. 20 |
| Comisión de transferencias | 0 % (nunca entre cuentas propias) |
| PIN | 3 fallos = tarjeta bloqueada (se desbloquea en sucursal) |
| Préstamos | Cuota cada 24 h, 6 h de gracia, recargo del 5 % por impago, mora a los 3 impagos |
| Crédito | 300-850, empieza en 600. +4 cuota a tiempo, +20 préstamo terminado, −25 impago, −80 mora |
| Movimientos | Se borran los de más de 90 días |

## Cuentas de empresa y banda

Cada trabajo y banda tiene su cuenta. La ven los rangos con permiso de cuenta o de jefe. Las nóminas de los
trabajos que pagan desde la empresa salen de ahí.

## Casos típicos

- **Tarjeta robada**: el titular puede congelarla o pedir un duplicado en el banco. Si no puede, `/bancocongelar`
  con su IBAN.
- **Cuenta sospechosa** (dinero duplicado, transferencias raras): `/bancocongelar` y avisar a un administrador para
  revisar los movimientos.
