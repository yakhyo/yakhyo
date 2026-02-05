[GitHub 🐱‍💻](https://github.com/yakhyo) | [Google Scholar 📚](https://scholar.google.com/citations?user=I66QbJIAAAAJ&hl=en) | [StackOverflow 🖥️](https://stackoverflow.com/users/14815986/yakhyo) | [LeetCode 🧩](https://leetcode.com/y_valikhujaev) | [LinkedIn 🔗](https://www.linkedin.com/in/y-valikhujaev/)

## ML Software Engineer 🤖

Passionate ML/DL/CV/NLP Engineer with ~4 years of industrial and 2+ years of academic experience delivering
impactful solutions across various industries. Proficient in supervised, self-supervised, and transfer learning, with in-depth
experience in OCR, object detection, segmentation, tracking, video recognition, and action classification.

Skilled in developing and deploying machine learning models on AWS and GCP, building and optimizing pipelines, containerization,
and collaborating with cross-functional teams to drive business growth.

## Skills Summary 🛠️

- **Programming Languages:** Python, C/C++, Java.
- **Database Management:** MySQL, PostgreSQL, PySpark.
- **ML:** Numpy, Scikit-learn, PyTorch, PyTorch Lightning, Tensorflow, Keras, HuggingFace, Transformers, RAG, LangChain.
- **MLOps:** Docker-compose, Dockerization, Kubeflow, MLFlow, Flask, Fast API, gRPC, TorchServe, Triton, TensorRT.
- **Development Tools:** Git/Github, Docker, CI & CD.
- **Cloud:** AWS EC2, GCP.
- **Main Competencies:** Object Detection, Object Tracking, OCR, Clustering, Re-Identification, Medical Imaging, Image Restoration & Enhancement, DeepFakes, Generative Models, Vision-Language Models, Large-Language Models, Natural Language Processing, Building End-to-End Pipelines, Deployment Pipelines, GCP Deployment.

## Work Experience 💼

### ML Engineer 🧠

**[Aria Studios Co. Ltd](https://showaria.com/)** | **March 2024 - Present**

- **In-cabin Companion**: Developed an in-cabin assistant utilizing large language models (LLMs) to enhance the driving experience. The system integrates multiple models for user interaction, including [face identification](https://github.com/yakhyo/face-reidentification), [gender and age estimation](https://github.com/yakhyo/facial-analysis), and emotion recognition. These features facilitate personalized conversations with the driver. For speech-to-text functionality, the **whisper** model was employed. Deployed all services using Fast API on GCP and local machine.
- **LG Ground 220**: Designed and implemented the AI backend for MusicStudio and DJingStudio, enabling features such as lyrics generation from user input, cover image creation, and music generation using OpenAI, StabilityAI, and MixAudio APIs. Leveraged **LangChain** and concurrent programming to optimize API calls and reduce latency. Can be seen [here](https://www.youtube.com/shorts/rkDN3T3bmQE).
- **Data collection tool for Virtual Character**: Developed a user interface that simulates a virtual character with predefined characteristics. The data collection team interacts with virtual character to gather additional data for fine-tuning a large language model (LLM). The tool is deployed on Google Cloud Platform (GCP) using FastAPI, with PostgreSQL used to store the collected data.
- **GPT Fine-tuning**: Fine-tuned the GPT-3.5-turbo model on conversation data of a virtual character to build a custom API for the virtual assistant. Performed several data augmentations using the OpenAI API for paraphrasing conversations.
- **LLMs Deployment**: Deployed a lightweight Phi-3 model for emotion detection from text on GCP using FastAPI and prepared a deployment container. The main objective was to detect users' emotions while interacting with a virtual character and responding accordingly.
- **VLMs Deployment**: Developed an "eye" for a virtual character to see and understand its surroundings, enabling it to interact with users. Deployed the Phi-3-Vision model on GCP for this purpose.
- **Face Parsing**: To improve face swapping performance, employed a Face Parsing model to segment the face. Enhanced model performance by modifying the feature extractor (backbone) and training strategy. Implementation can be found [here](https://github.com/yakhyo/face-parsing).
- **Image enhancement & Face restoration & DeepFake**: Worked on image enhancement and face restoration to improve DeepFakes. Created a DeepFake video for KBS election process coverage. Can be seen [here](https://www.youtube.com/live/CGbvG8S7HHo?si=8j4R4-f5ICfz01GF).

### ML Engineer 🖥️

**[Pyler Co. Ltd](https://www.pyler.tech/)** | **July 2022 - September 2023**

- **Video-based Visual Content Moderation**: Built a Video Moderation Pipeline to flag inappropriate video content using video recognition models, achieving over a 10% improvement in model accuracy.
- **Detection-based Visual Content Moderation**: Utilized segmentation and detection techniques to precisely detect unsuitable content for brand safety. Implemented state-of-the-art models in terms of real-time speed and efficiency, improving model precision and recall by around 15% through active learning techniques. Built an end-to-end pipeline on Kubeflow for training and deployment.
- **Classification-based Visual Content Moderation**: Leveraged multi-label and multi-head classification techniques to improve precision by approximately 20% using self-supervised and supervised training approaches. This novel approach showcases the adaptability and efficacy of the model for hard samples. Prepared Docker images for each development and deployment environment (containerization).
- **Model Assisted Labeling**: Created a pipeline for doing inference on existing labeled data and doing inference on unlabeled data. Improved labeling quality and speed using **Active Learning**.

### AI Research Engineer 🧠

**[D-Meta Co. Ltd](https://www.d-meta.ai/)** | **November 2020 - July 2022**

- **Slab Text Recognition**: Developed and designed a text detection and recognition model to efficiently recognize handwritten texts on slab metals using Spatial Transformer Networks and Sequential modeling. Built a complete pipeline from data pre-processing to training and evaluation of the model. Achieved over 90% accuracy by integrating state-of-the-art detection and recognition models for scene text images.
- **Automatic Number Plate Recognition**: Designed and developed an ANPR model to accurately detect and recognize number plates. Leveraged active learning and synthetic image generation techniques to improve precision and recall by around 15%.
- **Car Damage Detection**: Built a lightweight damage detection model and deployed it on an Android device using TorchScript. Improved the precision of the model by around 10% by tuning the model parameters.

## Research Experience 📚

### Research Assistant 🧑‍🔬

**AI and SC Lab** | **Sep 2018 - Nov 2020**

- **Computer Vision based Fire and Smoke Detection**: Designed and implemented a dilated CNN architecture for improved feature extraction and recognition in images/videos. By carefully tuning and optimizing the model, achieved a high level of accuracy in fire and smoke detection, reducing false positives and achieving 1.5x faster inference speed compared to the fastest counterpart.
- **Model Optimization for Edge Devices**: Improved the FPS on Edge device (Raspberry PI 2) by using hyper-parameter tuning and quantization for the detection model.

## Education 🎓

| **Institution**                                 | **Degree**                                                                | **Duration**        |
| ----------------------------------------------- | ------------------------------------------------------------------------- | ------------------- |
| Gachon University                               | MSc in Computer Engineering; advised by Prof. Young Im Cho; CGPA: 4.0/4.5 | Sep 2018 - Feb 2021 |
| Tashkent University of Information Technologies | BSc in Computer Engineering; CGPA(%): 85/100                              | Sep 2014 - Jun 2018 |

## Publications 📝

- **Valikhujaev Y**, Abdusalomov A, Cho YI. Automatic Fire and Smoke Detection Method for Surveillance Systems Based on Dilated CNNs. Atmosphere, **IF 2.9**. 2020; 11(11):1241. [https://doi.org/10.3390/atmos11111241](https://doi.org/10.3390/atmos11111241).
- Muksimova SH, **Valikhujaev Y**, Cho YI. Automatic Fire and Smoke Detection System for Open Street CCTV Systems in Smart City Platforms. Korean Society of Information Scientists and Engineers, 412-414 pages, Domestic Conference.

## Honors 🏆

- **Best paper award** from Fire Investigation Society of Korea (FISK); (Domestic Conference, 2020)
- **Best presentation award** from ISIS2019 & ICBAKE2019; (Domestic Conference, 2019)

## Languages 🌐

- **English:** Full Professional Proficiency (C1 Advanced, IELTS band 7)
- **Korean:** Limited Working Proficiency (B1 Pre-Intermediate)
- **Uzbek:** Native Proficiency
- **Russian:** Limited Working Proficiency

---

<br>
_Last Updated: 2024-09-19_

<code> Click below to download in .pdf format </code>

<a href="https://github.com/yakhyo/yakhyo.github.io/releases/download/v0.0.1/yakhyo_cv.pdf"> <img src="assets/icons/download-pdf.png" width="128px"> </a>
