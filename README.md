# Tensorflow
# Activation Function:-
The purpose of activation functions is to introduce non-linearities into the network , since we have a lot of non-linear data today.
1) tf.compat.v1.math.**sigmoid**(34.0)

**Sigmoid** :-  ![image](https://user-images.githubusercontent.com/68476475/122535023-c403cd80-d040-11eb-9f45-2fb74404cda9.png)
                 
                 f'(x)= f(x) (1-f(x))

 

 
2) tf.compat.v1.math.**tanh**(34.0)

**Hyperbolic Tangent**:- ![image](https://user-images.githubusercontent.com/68476475/122535633-5f953e00-d041-11eb-9026-53a5eadaa094.png)

                          f'(x)=1 -f(x)^2
 
3) tf.compat.v1.nn.**relu**(34.0)

**Recified Linear Unit** :- f(x)= max(0,x)
 
 
                            f'(x)= 1 if x>0 else 0
