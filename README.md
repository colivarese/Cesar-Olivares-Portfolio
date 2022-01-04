## Cesar Olivares
This is my portfolio of Data Science/Machine Learning projects.

# Potato Leaves Disease Classification on Google Cloud
On this project a Convolutional Neural Network model is trained using images from potato leaves,
with three clases, healthy and two with diseases. The model achieves an accuracy around 0.95.
The model is used in a React local webpage having a drag and drop function, which returns the
predicted class with its accuracy.

<p align="center">
<img width="480" alt="Captura de Pantalla 2022-01-03 a la(s) 19 39 26" src="https://user-images.githubusercontent.com/80273045/148007912-17dc44c5-2dc6-44fa-9126-0e345ffda445.png"> <img width="480" alt="Captura de Pantalla 2022-01-03 a la(s) 19 40 20" src="https://user-images.githubusercontent.com/80273045/148008320-02b47121-1c63-4eca-84c2-4f2a8664b7bf.png">
</p>

The trained model is then loaded into Google Cloud Platform, connected with the FastAPI to get
predictions with a cloud server and tested with Postman.

