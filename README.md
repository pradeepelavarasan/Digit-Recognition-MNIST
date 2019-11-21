# Digit-Recognition-MNIST

This repository is about creating an optimized custom CNN model for Number Recognition application on MNIST data with the below conditions and results:

## Conditions:
- No bias to be used
- No fully connected layer
- No. of epochs should be less than or equal to 20
- No. of total parameters should be less than 15,000 paramters

## Results:
- Total params: 13,904
- Trainable params: 13,712
- Non-trainable params: 192
- Training Accurary: 99.05
- Validation Accuracy: 99.41

## Strategy:
- 

## Validation Accuracy
score = model.evaluate(X_test, Y_test, verbose=0)
print(score)
[0.01831436900636472, 0.9941]

## Training Logs

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 12s 205us/step - loss: 0.3021 - acc: 0.9037 - val_loss: 0.0677 - val_acc: 0.9779
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 9s 152us/step - loss: 0.0914 - acc: 0.9720 - val_loss: 0.0471 - val_acc: 0.9842
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 9s 152us/step - loss: 0.0689 - acc: 0.9781 - val_loss: 0.0398 - val_acc: 0.9866
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0606 - acc: 0.9805 - val_loss: 0.0325 - val_acc: 0.9899
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0537 - acc: 0.9829 - val_loss: 0.0318 - val_acc: 0.9904
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0488 - acc: 0.9847 - val_loss: 0.0292 - val_acc: 0.9918
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0469 - acc: 0.9855 - val_loss: 0.0336 - val_acc: 0.9904
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0447 - acc: 0.9856 - val_loss: 0.0292 - val_acc: 0.9918
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0401 - acc: 0.9873 - val_loss: 0.0217 - val_acc: 0.9930
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 9s 156us/step - loss: 0.0393 - acc: 0.9877 - val_loss: 0.0257 - val_acc: 0.9928
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 9s 156us/step - loss: 0.0376 - acc: 0.9880 - val_loss: 0.0236 - val_acc: 0.9933
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 9s 154us/step - loss: 0.0357 - acc: 0.9892 - val_loss: 0.0208 - val_acc: 0.9937
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 9s 154us/step - loss: 0.0367 - acc: 0.9881 - val_loss: 0.0212 - val_acc: 0.9937
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 9s 154us/step - loss: 0.0346 - acc: 0.9891 - val_loss: 0.0231 - val_acc: 0.9929
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0341 - acc: 0.9892 - val_loss: 0.0220 - val_acc: 0.9936
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0336 - acc: 0.9893 - val_loss: 0.0193 - val_acc: 0.9948
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0316 - acc: 0.9898 - val_loss: 0.0224 - val_acc: 0.9929
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 9s 153us/step - loss: 0.0306 - acc: 0.9902 - val_loss: 0.0216 - val_acc: 0.9932
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 9s 152us/step - loss: 0.0297 - acc: 0.9907 - val_loss: 0.0200 - val_acc: 0.9932
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 9s 152us/step - loss: 0.0298 - acc: 0.9905 - val_loss: 0.0183 - val_acc: 0.9941
<keras.callbacks.History at 0x7fe05bd2d940>
