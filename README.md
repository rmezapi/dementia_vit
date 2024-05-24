# dementia_vit

This project was intended to test the limits of the ViT on a tough dementia dataset. The data used can be found on HuggingFace at: https://huggingface.co/datasets/Falah/Alzheimer_MRI. The dataset has 4 classes:

*    0: mild_demented
*    1: moderate_demented
*    2: non_demented
*    3: very_mild_demented

The project follows closely the following tutorials: 

*   https://www.youtube.com/watch?v=r88L_yLJ4CE&ab_channel=code_your_own_AI
*   https://www.youtube.com/watch?v=qU7wO02urYU&ab_channel=JamesBriggs  


I modify the code presented in the video and tune all parameters to optimize performance using mostly the same libraries and tools. This is a practice project for myself as I return to coding/designing ML models after dedicating time to AI/ML theory (model architectures, transfer learning)

After hyperparameter tuning, the highest testing accuracy achieved is 66% using a learning rate of 2e-5, a weight decay of 0.001, batch size of 8, and iterating over 5 epochs.

<img width="546" alt="image" src="https://github.com/rmezapi/dementia_vit/assets/69809420/e55834d7-be90-42c3-8749-7a592b2e7667">

<img width="430" alt="image" src="https://github.com/rmezapi/dementia_vit/assets/69809420/6ba29c87-ab72-4312-b93d-56653d708f1f">

<img width="347" alt="image" src="https://github.com/rmezapi/dementia_vit/assets/69809420/785e3db3-9e61-4d94-9f6f-ec636e7ccf7c">

