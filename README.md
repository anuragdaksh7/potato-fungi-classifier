# potato-fungi-classifier

Model: "sequential_3"
Link to pretrained mdoel: https://drive.google.com/file/d/1JvezsjRmBPSfY1_-pEF2L2Fgqp8XmcZB/view?usp=sharing
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d_9 (Conv2D)           (None, 254, 254, 32)      896       
                                                                 
 max_pooling2d_9 (MaxPooling  (None, 127, 127, 32)     0         
 2D)                                                             
                                                                 
 conv2d_10 (Conv2D)          (None, 125, 125, 64)      18496     
                                                                 
 max_pooling2d_10 (MaxPoolin  (None, 62, 62, 64)       0         
 g2D)                                                            
                                                                 
 conv2d_11 (Conv2D)          (None, 60, 60, 128)       73856     
                                                                 
 max_pooling2d_11 (MaxPoolin  (None, 30, 30, 128)      0         
 g2D)                                                            
                                                                 
 flatten_3 (Flatten)         (None, 115200)            0         
                                                                 
 dense_6 (Dense)             (None, 64)                7372864   
                                                                 
 dense_7 (Dense)             (None, 3)                 195       
                                                                 
=================================================================

Total params: 7,466,307

Trainable params: 7,466,307

Non-trainable params: 0

_________________________________________________________________
