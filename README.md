# PRiR zadania lab 12
##Obrazy wejściowe:<br>
![](cat.png)
![](artwork.jpg)<br><br>
##Wyniki ze względu na ilość iteracji <br>
100: <br>![](100(1).png)<br>
700: <br>![](700(1).png)<br>
1500: <br>![](1500(1).png)<br>
4000: <br>![](4000(1).png)<br>

##Wpływ wyboru warstw:
Podstawowe: (obrazy wyżej)
```
style_layer_names = [
    "block1_conv1",
    "block2_conv1",
    "block3_conv1",
    "block4_conv1",
    "block5_conv1",
]
```

Zmienione: (obrazy poniżej)
```
style_layer_names = [
    "block1_conv1",
    "block2_conv1",
    "block3_conv1",
]
```
100: <br>![](100(2).png)<br>
700: <br>![](700(2).png)<br>
1500: <br>![](1500(2).png)<br>

##Źródła
https://keras.io/examples/generative/neural_style_transfer/
