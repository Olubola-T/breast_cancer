# Deeep learning for breast cancer diagnosis using histology images

Computer vision is one of the domains of artificial intelligence that has proved useful in medical
practice, especially in specialties such as radiology, dermatology, and histopathology. Breast
cancer is the most common cancer in women, and its diagnosis is established through microscopic
examination of the architecture of specially prepared tissue samples. It takes about 20 minutes to
examine a slide of breast tissue and make a diagnostic decision, and in centres that serve large
populations while being short-staffed, rapid turnaround times for histopathological diagnosis is
desirable for reducing the workload of histopathologists and expediting the commencement of
definitive therapy based on histology reports.

This project presents a deep neural network for diagnosing breast cancer using breast histology
images in a binary classification task.

Image vectors of breast tissue (both malignant and benign) were prepared and split into training
and test datasets. Vectors of malignant tissue were assigned class label of 1, while those of benign
tissue were assigned 0. The model fitted to the dataset had two convolutional layers with ReLu
activation and max pooling applied. There were six fully connected dense layers having a total of
neurons. The model had 635,633 trainable parameters, and it was trained with 34,946 images. It
achieved accuracy of 96.7% and 90.4% on the training and test datasets, respectively. The recall
of the model for the positive class was 0.86, and the area under the receiver-operating
characteristic curve was 0.96.

