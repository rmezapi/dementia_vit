# dementia_vit

This project was intended to test the limits of the ViT on a tough dementia dataset. The data used can be found on HuggingFace at: https://huggingface.co/datasets/Falah/Alzheimer_MRI. The project follows closely the following tutorials: 


*   https://www.youtube.com/watch?v=r88L_yLJ4CE&ab_channel=code_your_own_AI
*   https://www.youtube.com/watch?v=qU7wO02urYU&ab_channel=JamesBriggs  


I modify the code presented in the video and tune all parameters to optimize performance using mostly the same libraries and tools. This is a practice project for myself as I return to coding/designing ML models after dedicating time to AI/ML theory (model architectures, transfer learning)

After hyperparameter tuning, the highest testing accuracy achieved is 63% using a learning rate of 2e-5, a weight decay of 0.001, and iterating over 5 epochs.
