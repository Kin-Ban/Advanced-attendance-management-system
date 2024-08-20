# Advanced-attendance-management-system

This is an end-to-end attendance management system built using deep convolutional neural networks. We followed two approaches to develop the system:

Building the Model from Scratch:
We constructed a deep convolutional neural network from scratch for this system. We used three Inception blocks with an adjusted number of filters, followed by additional customized layers with a specific number of nodes tailored to our requirements. This model achieved an accuracy score of over 96%.

Transfer Learning:
We also experimented with transfer learning to train deep convolutional models for our system. We selected multiple models, including InceptionV3, Xception, VGG16, and ResNet50. After freezing the weights of the base models, we added customized layers as per our needs. The accuracy scores for these models ranged between 80% and 92%. (All model architectures and the entire system workflow are described in detail in the report.)

Since our custom-built model achieved the highest accuracy, we used it in the backend to recognize individuals and mark their attendance using the advanced attendance management system.

The frontend is built using Flask, and all attendance data get stored in a MySQL database, which can be accessed and viewed as needed.  
