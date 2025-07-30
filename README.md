Project Overview:

This app allows users to upload an image and get a prediction of which CIFAR-10 class the image most likely belongs to. 
It uses a pre-trained deep learning model and displays both the predicted class and confidence score interactively on a web interface.

Features:

  1.Upload images through a simple web interface.
  
  2.Preprocess images appropriately for the CIFAR-10 model.
  
  3.Display predicted class and confidence.
  
  4.Quickly deployable using Streamlit.
  
  5.Public access via tunneling services like ngrok when run from Google Colab.




Running on Google Colab (with ngrok)- 
I have used google collab for backend:

  You can run the app on Google Colab and expose it using ngrok:
   Upload the model file that is the code- cifar10_model.h5 to Colab.
   Write app.py using the provided code.
   Use the pyngrok package to expose your localhost:8501 port.
   Get the public ngrok URL to share or use the app remotely.

How to Run Locally
Clone this repo:

bash

    git clone https://github.com/your-username/your-repo-name.git
  
    cd your-repo-name
  
    Install required packages:

bash

     pip install streamlit tensorflow pillow numpy
    
    Ensure your model file cifar10_model.h5 is in the same directory.

Run the Streamlit app:

bash

    streamlit run app.py

Open the displayed localhost URL in your browser to use the app.

How can you use the website:

  Upload a clear image in .png, .jpg, or .jpeg format.
  
  wait for the model to process and see the prediction with confidence.
  
  Refresh or upload new images as needed.


![Alt text](https://github.com/Mony1235/Image-Classification/blob/main/WhatsApp%20Image%202025-07-30%20at%2022.10.57_1fd81151.jpg)
![Alt text](https://github.com/Mony1235/Image-Classification/blob/main/horse.jpg)
![Alt text](https://github.com/Mony1235/Image-Classification/blob/main/WhatsApp%20Image%202025-07-30%20at%2021.53.08_e568b72a.jpg)
