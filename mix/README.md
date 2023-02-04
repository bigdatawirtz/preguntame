Os ficheiros nesta carpeta están creados como concatenación dos ficheiros individuais subidos polo alumnado.

Para concatenar os ficheiros utilizouse o seguinte código, que crea un único ficheiro, inserindo a maiores un par de saltos de liña entre o contido dos ficheiros concatenados.

```for f in *.gift; do (cat "${f}"; echo; echo) >> ../mix/preguntas_materia.gift; done```

