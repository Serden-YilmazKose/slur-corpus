### [Project Github repo](https://github.com/Serden-YilmazKose/NLP-Project-5)

## INFO FOR RUNNING THE PROJECT:
All tasks except for task 12 are found in the "NLP-course-project.ipynb file". Code for task 12 is found in "task_12.py".

To install all required libraries you can run the following command: **pip install -r requirements.txt**

This will install all of the required libraries **EXCEPT pytorch**:

In Task 10, Nvidia CUDA is used to enable running DistilBERT on the GPU. If you don't have CUDA installed it will run on CPU and take for a very long time.

If you have CUDA, install the correct version of pytorch by going [here](https://pytorch.org/get-started/locally/) and selecting the correct configuration, and then running the command it gives you, such as "pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124".

If you don't have CUDA, you can opt for the regular pytorch package by running *pip install pytorch*, although then running the DistilBERT task will be extremely slow. **This is why we have saved the embeddings generated by DistilBERT into pickle files, which can instead be loaded by running the cell below.**