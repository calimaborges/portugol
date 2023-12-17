# resumo

## `escreva`

```
programa {
    funcao inicio() {
        escreva("Ola mundo\n")
    }
}
```

## `leia`

```
programa {
    funcao inicio() {
        inteiro valor
        escreva("Informe um valor: ")
        leia(valor);
    }
}
```


## `se`

```
programa {
    funcao inicio() {
        inteiro magico = 5;
        inteiro palpite;

        se (palpite == magico) {
            escreva("Acertou mizeravi!\n");
        }
    }
}
```

## `senao`

```
programa {
    funcao inicio() {
        inteiro magico = 5;
        inteiro palpite;

        se (palpite == magico) {
            escreva("Acertou mizeravi!\n");
        } senao {
            escreva("Eroooou!\n");
        }
    }
}
```

## `senao se`

```
programa {
    funcao inicio() {
        inteiro magico = 5;
        inteiro palpite;

        se (palpite == magico) {
            escreva("Acertou mizeravi!\n");
        } senao se (palpite > magico) {
            escreva("Palpite muito alto!\n");
        } senao {
            escreva("Palpite muito baixo!\n");
        }
    }
}
```

## `faca-enquanto`

```
programa {
    funcao inicio() {
        inteiro contador = 0;
        
        faca {
            escreva("contador = ", contador)
            contador++
        } enquanto (contador < 10)
    }
}
```

## `enquanto`

```
programa {
    funcao inicio() {
        inteiro contador = 0;

        enquanto (contador < 10) {
            escreva("contador = ", contador)
            contador++
        }
}
```
