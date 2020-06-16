# SMOMI5

В пятой лабораторной работе использовалась нейросеть VGG16, обученная на imagenet, с обученным классификатором в 3-ей лабораторной, обучаемая с методами аугментации данных. 

### Step decay

`def step_decay(epoch):
   initial_lrate = 0.0000000001
   drop = 0.5
   epochs_drop = 10.0
   lrate = initial_lrate * math.pow(drop, math.floor((1+epoch)/epochs_drop))
   return lrate  ` 
   
#### Initial learning rate = 1e-10
 
![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/A_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/A_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/L_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/L_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/lr_a.PNG)

#### Initial learning rate = 1e-11

![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/A_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/A_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/L_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/L_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay/lr_b.PNG)


### Exponential decay
#### Initial learning rate = 1e-10

![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/A_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/A_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/L_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/L_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/lr_a.PNG)

#### Initial learning rate = 1e-11

![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/A_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/A_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/L_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/L_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay/lr_b.PNG)

### Step decay with warmup
#### Initial learning rate = 1e-10

![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/A_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/A_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/L_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/L_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/lr_a.PNG)

#### Initial learning rate = 1e-11

![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/A_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/A_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/L_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/L_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/step_decay_warmup/lr_b.PNG)


### Exponential decay with warmup

#### Initial learning rate = 1e-10

![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/A_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/A_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/L_train_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/L_val_a.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/lr_a.PNG)

#### Initial learning rate = 1e-11

![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/A_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/A_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/L_train_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/L_val_b.PNG)![.](https://github.com/VictoriaIL/SMOMI5/blob/master/exp_decay_warmup/lr_b.PNG)




