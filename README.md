# CNN_on_seis_ampl
To run the code first unzip the data present in the two folders Data_Patch and Data_Point. The data are synthetic data and in .csv format. All the files for testing and training are the .rar files, that needs to be extracted.

The code for even patches are cnn_patch_<patch_size>

The code for odd patches (point analysis) are cnn_point_<patch_size>

Name of code: CNN_on_seis_ampl.
Developer: Patitapaban Palo, Department of Electrical Engineering, IIT Kharagpur, West Bengal, India.
Contact address: email: patitapabanpalo@gmail.com, tel: +91-9437904634.
Year first available: 2021.
Hardware required: RAM(>16GB) and GPU(optional).
Software required: Python 3.7.4 and PyTorch 1.3.1
Program language: Python.
Details on how to access the source code: After having hardware and software requirements, extract the .rar files in the Data_Patch and Data_Point folders (There are 8 .rar files 1. Data_Patch/Training/Fault.rar 2. Data_Patch/Training/Non-Fault.rar 3. Data_Patch/Testing/Fault.rar 4. Data_Patch/Testing/Non-Fault.rar 5. Data_Point/Training/Fault.rar 6. Data_Point/Training/Non-Fault.rar 7. Data_Point/Testing/Fault.rar 8. Data_Point/Testing/Non-Fault.rar). Then run the codes to see the performance.
