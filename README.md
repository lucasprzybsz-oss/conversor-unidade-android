# Conversor de Unidades de Comprimento

Aplicativo Android desenvolvido em Java para realizar conversões entre diferentes unidades de comprimento de forma automática e dinâmica.

O usuário informa um valor numérico, seleciona a unidade de entrada e a unidade de saída, e o aplicativo realiza a conversão imediatamente.

O projeto foi desenvolvido com Android Studio e utiliza componentes de interface em XML combinados com lógica implementada em Java.

---

## Funcionalidades

O aplicativo permite converter valores entre as seguintes unidades:

- Quilômetro (`km`)
- Hectômetro (`hm`)
- Decâmetro (`dam`)
- Metro (`m`)
- Decímetro (`dm`)
- Centímetro (`cm`)
- Milímetro (`mm`)

A conversão é realizada automaticamente quando:

- O usuário digita ou altera um valor;
- A unidade de entrada é modificada;
- A unidade de saída é modificada.

Não é necessário pressionar um botão para realizar o cálculo.

---

# Conteúdos aplicados no desenvolvimento

## 1. Desenvolvimento de interface Android

A interface do aplicativo utiliza componentes do Android, como:

- `EditText`
- `Spinner`
- `TextView`

O `EditText` é utilizado para entrada do valor numérico.

Os dois `Spinner` permitem selecionar:

- A unidade de entrada;
- A unidade de saída.

O `TextView` apresenta o resultado final da conversão.

---

## 2. Associação entre XML e Java

Os componentes definidos no layout XML são associados ao código Java por meio do método:

```java
findViewById()
