# About Me
*TLDR: I'm pretty good at context-agnostic data-driven Signal Processing.*

I am a graduate student in the Department of Electrical and Computer Engineering at Boston University, previously interned at Intuitive Surgical, in the division of the Advanced Imaging and Intelligence for Summer 2024. My academic background, expertise, and interests are primarily centered around the domains of Applied Signal Processing and AI.

In addition, I have gained valuable experience and proficiency in the fields of Computer Vision, Computational Imaging, Autonomous Driving, Audio, SONAR and High-Performance-Computing Programming. I firmly believe that the successful research and development of projects necessitates a deep understanding of a core domain, complemented by a working knowledge of related domains. Thus my project selection approach is rooted in fundamental principles rather than being constrained by specific domains.

## Research Interests
Due to my interest in applied signal processing, most of my projects lies in Signal & Image Processing, Computer Vision, Robotic Perception, Machine & Deep Learning. 

### Key Expertise:
- Domains: Signal Processing: Audio, Speech and Image, Computational Imaging, Machine Learning, Machine Vision, Supervised, Unsupervised, and Reinforcement Learning.
- Tools: Matlab, Matlab Executable CUDA(MexCuda), Numpy, SciPy, PyTorch, CUDA, CuBLAS, Nvidia Performance Primitives (NPP).
- Programming Languages: C, C++, CUDA, Python, Matlab, and Bash

## Education
- **Master of Science**: Electrical and Computer Engineering, *Boston University*
- **Bachelor of Technology**, College of Engineering Trivandrum, *Dr. A.P.J. Abdul Kalam Technical University*

## Experience
- **MS Project Intern**, Yobe Inc
- **Advanced Imaging SW Engr Intern**, Advanced Imaging and Intelligence, *Intuitive Surgical*
- **Electronics Engineer**, Naval Physical and Oceanographic Laboratory, *Defence Research and Development Organisation*
- **Project Intern**, Naval Physical and Oceanographic Laboratory, *Defence Research and Development Organisation*
- **Undergraduate Intern**, Naval Physical and Oceanographic Laboratory, *Defence Research and Development Organisation*
- **Undergraduate Assistant**, Department of Electronics and Communication Engineering, College of Engineering Trivandrum, *Dr. A.P.J. Abdul Kalam Technical University*


## Projects
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**MS Research Project**, *Electrical and Computer Engineering, BU* 
- Designed and trained a Wave-U-Net variant to reduce black-box ASR transcription errors (word-error-rate).
- Designed a custom loss function leveraging ASR system properties, STFT features, and auditory perception.
- Achieved WER reductions on OpenAI Whisper: **6.7%** at SNR = 3, **4.2%** at SNR = 6 and **1.37%** at SNR = 9.
- Code, Poster and Paper available at: [Speech Enhancement for Robust Automatic Speech Recognition](https://github.com/vrsreeganesh/asr-enhancer)


<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Advanced Imaging Internship**, *Advanced Imaging & Intelligence Group, Intuitive*
- Designed and implemented multiple imaging stages in Matlab and CUDA, to enhance the existing pipeline by highlighting procedure-specific features for **3** surgical procedures, enabling faster procedure completion.
- Wrote MATLAB library to integrate a proprietary inhouse CUDA framework with their legacy MATLAB imaging pipelines to achieve near real-time performance. The integration also enables uniformity and code re-use.
- Assessed the robustness of a prototype imaging stage. Wrote scripts for automated and rigorous testing to identify weaknesses, document associated metrics, all to provide actionable feedback.


<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Audio Denoising**, *Boston University, College of Engineering*
- Developed an audio denoising pipeline containing a classical audio processing stage and a neural-net based stage.
- The audio processing stage is based on smoothed spectral-subtraction and neural-net stage is a **4** layered FCN.
- Introduced novel method of combining heterodyning and denoising to overcome long-tail problem in neural nets.
- Code and Report available at: [*Audio Denoising: A Heterodyned Approach*](https://github.com/vrsreeganesh/AudioDenoising_A_HeteroDyned_Approach)
 

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Sim2Real AV-Agent Deployment**, *Boston University, College of Engineering*
- SIM2REAL is a robotics concept involving training an agent in simulation before deploying in real environments.
- The project involved pioneering a new domain randomization approach to enable robust SIM2REAL for vehicles. 
- Configured a robotic agent in CARLA and an RC car to collect expert driving data through manual operation, implemented diverse perception-to-control pipelines, and trained the vehicle pipelines using imitation learning.
- The proposed method produced significant improvements in agent performance: obtained an average decrease of **17%** in Steer-MAE, **11.5%** in Steer-SW-MAE, **11.5%** in Action-MAE. 
- Succesfully created an agent agnostic to appearance differences, enabling successful and similar performance in both simulation and reality. Code and Paper: [*A Style Transfer Approach To Appearance Agnostic Agents*](https://github.com/vrsreeganesh/StyleTransferApproachToAppearanceAgnosticAgents/blob/main/EC523_ProjectReport_SreeganeshValatharaRajendran.pdf)
 


<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**End-to-End Vehicle Autonomy**, *Boston University, College of Engineering*
- Implemented policy-function using reinforcement learning, imitation learning, and behavior cloning approaches.
- The policy function stage comprises of a CNN and a FCN for mapping images to car control commands.
- Secured **second prize** in class competition. 

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Underwater Signal Simulator**, *Naval Physical and Oceanographic Laboratory*
- Designed fast signal simulator for underwater sensor arrays: uniform linear arrays (ULAs) and planar arrays. 
- Engineered MATLAB-based vectorized signal simulator for diverse ocean environments and sensor arrays.
- Developed to assist and assess sonar imaging algorithms. Achieved 7x speed by further translating to CUDA C.

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Computational Sonar Imaging**, *Naval Physical and Oceanographic Laboratory*
- Realised **4** computational imaging algorithms **each** for front-looking, side-scan, and synthetic-aperture SONARs.
- Wrote MATLAB pipelines for beamforming-based imaging, employing full-aperture, dynamic-aperture, constant range-cell, and variable range-cell methods. 
- Wrote vectorized MATLAB code for a low latency implementation.

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**DSP Firmware**, *Naval Physical and Oceanographic Laboratory*
- Designed and developed DSP firmware with functionalities meeting client specifications and project constraints.
- Involves signal detection using matched-filtering and processing detected signal according to system mode.
- Programmed, tested, and integrated functionalities in MATLAB; later translated to C (primarily C89).
- Unified, tested, and assessed DSP firmware for deployment on TIVA-C, an ARM Cortex-M4F based MCU.

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Attendance Registration Using Face Recognition**, *College of Engineering Trivandrum*
- Created an attendance registration system that uses a deep learning pipeline to deploy in a classroom setting. 
- The machine learning stage consists of a CNN-based feature-extractor and a FCN based feature-classifier. 
- Submitted, presented and showcased system to project committee, faculty, and students as part of curriculum.

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Image Steganography**, *College of Engineering Trivandrum*
- Studied over 200 publications and reproduced 30+ image steganography methods in MATLAB and Python. 
- Publications consists of classical steganography methods and data-driven steganography methods. 
- Conducted to generate metrics for baseline comparisons added to graduate student's thesis and publications. 
- Performed as part of undergraduate assistant duty to assist professor's graduate students (assisted two students).

## Miscellaneous

### Matlab x CUDA
I'm writing a book! It introduces engineers to integrating MATLAB with CUDA backends to develop low-latency pipelines, an approach commonly used in various R&D environments. Its under construction but if you're impatient and don't mind half-cooked content, you can check it out here: [An Introduction to Matlab x CUDA](https://vrsreeganesh.github.io/MatlabxCUDA/intro.html#)

### Online Learning

- [Machine Learning](https://www.coursera.org/account/accomplishments/records/C3QMKPURUE4K), *Stanford University*
- [Data Science: Foundations using R Specialization](https://www.coursera.org/account/accomplishments/specialization/448DRD5CP3BJ), *Johns Hopkins University*
- [The Data Scientist's Toolbox](https://www.coursera.org/account/accomplishments/records/DU82QGR6NXGU), *Johns Hopkins University*
- [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/S5LNWNHS3C8D), *Deeplearning. AI*
- [R Programming](https://www.coursera.org/account/accomplishments/records/7FPVU9PMW69R), *Johns Hopkins University*
- [Getting and Cleaning Data](https://www.coursera.org/account/accomplishments/records/T6SHXFKUKM37), *Johns Hopkins University*
- [Exploratory Data Analysis](https://www.coursera.org/account/accomplishments/records/UMK922MMAMEB), *Johns Hopkins University*
- [Reproducible Research](https://www.coursera.org/account/accomplishments/records/LFUY3QTNAR3Y), *Johns Hopkins University*
- [Statistical Inference](https://www.coursera.org/account/accomplishments/records/4JRRY5J4R4R8), *Johns Hopkins University*
- [Regression Models](https://www.coursera.org/account/accomplishments/records/CP63HLYP57CF), *Johns Hopkins University*
- [Practical Machine Learning](https://www.coursera.org/account/accomplishments/records/TC8D47E8MQ8W), *Johns Hopkins University*
- [Developing Data Products](https://www.coursera.org/account/accomplishments/records/SSSKY6SEB6XK), *Johns Hopkins University*
- [Neural Networks and Deep Learning](https://www.coursera.org/account/accomplishments/records/2ZRFGW7EG9MS), *Deeplearning. AI*
- [Improving Deep Neural Networks: Hyperparameter tuning, Regularisation and Optimization](https://www.coursera.org/account/accomplishments/records/XEE7AFZR2HUA), *Deeplearning. AI*
- [Structuring Machine Learning Projects](https://www.coursera.org/account/accomplishments/records/JKCBWTCZU2BU), *Deeplearning. AI*
- [Convolutional Neural Networks](https://www.coursera.org/account/accomplishments/records/6822CBKF4HSK), *Deeplearning. AI*
- [Sequence Models](https://www.coursera.org/account/accomplishments/records/A58XSTA7WJD6), *Deeplearning. AI*

### Self Learning
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep Learning. MIT Press. 
- Sutton, R. S., & Barto, A. G. (2018). Reinforcement Learning: An Introduction. MIT Press.


## Contact
Boston University Mail: vrs [at] bu [dot] edu  (I highly suggest using this)
personal mail: vrsreeganesh [at] gmail [dot] com  
alternative: vrsreeganesh [at] cet [dot] ac [dot] in
