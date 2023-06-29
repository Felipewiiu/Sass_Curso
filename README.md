# Sass_Curso

## Funções no Sass

A maneira de se declarar funções no Sass é usando a palavra reservada @mixins 
Mixins são funções que não retornam valores mas sim estilos. Um mixin recebe um nome e pode receber argumentos. O intuito do mixin é maximizar a sua capacidade de reutilizar regras de CSS com valores diferentes, tornando seu código mais limpo e menos repetitivo ou DRY (Don't Repeat Yourself).

```

//Um mixin pode receber um ou nenhum argumento
@mixin colorize($cor){
  //...
}

```
## Variáveis

As variáveis são declaradas com o simbolo `$nomeVariavel`

