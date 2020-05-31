# Neural-Network-Visualizer
#Weekend_Project - Neural Network Visualizer web application using Streamlit, a simple model server using Keras and Flask.  
A web application that will visualize the outputs of all the nodes of all the layers of the neural network (using Keras' functional API) for a given input image (MNIST dataset)

## Neural Network architecture (Keras)
```
model = tf.keras.models.Sequential([
    tf.keras.layers.Dense(32, activation='sigmoid', input_shape=(784,)),
    tf.keras.layers.Dense(32, activation='sigmoid'),
    tf.keras.layers.Dense(10, activation='softmax')
])
```  

## Demo
![](Demo.gif)
