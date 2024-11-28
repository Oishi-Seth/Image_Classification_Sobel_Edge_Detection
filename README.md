# Image_Classification_Sobel_Edge_Detection

### Steps to recreate the project

1. Download the source code of the example project from github- https://github.com/Xilinx/BNN-PYNQ
2. Open a web browser and navigate to http://192.168.2.99 to connect to jupyter notebook. Enter Username xilinx and password xilinx.
![image](https://github.com/user-attachments/assets/d375e3c4-7ada-420b-9efd-4b2fd7c53b7d)
 
3. Upload the code to jupyter notebook using UPLOAD option. Select the downloaded zip folder and click open.
![image](https://github.com/user-attachments/assets/4301de9c-7503-4eee-9f85-905fe3ea63a0)

4. Open a new notebook and unzip the file using below code:
![image](https://github.com/user-attachments/assets/797b0fe1-9d64-4dd8-86cd-55326323fd7e)

5. Then open a new terminal in jupyter notebook and run the setup.py file using “python3 setup.py install” command.
![image](https://github.com/user-attachments/assets/7717efd6-cf7d-4bf9-b1e5-db442bc7148b)

6. This will install the project package on board and create a directory in the jupyter home area.
![image](https://github.com/user-attachments/assets/8ff6c31e-8e2f-41d7-9f54-48f6468a175e)

7. Copy the files: QNN_Cifar10_Sobel_Webcam.ipynb, base.bit, base.hwh from this github and paste it in the "bnn" folder that got installed now.

8. Connect a USB camera with the PYNQ USB Port.
9. Open the QNN_Cifar10_Sobel_Webcam.ipynb and run the jupyter notebook.
