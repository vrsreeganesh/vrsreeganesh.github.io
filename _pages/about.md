---
permalink: /
title: "Personal Webpage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<!-- # About Me -->
*TL;DR: I'm pretty good at context-agnostic Signal Processing, Machine/Deep Learning and High Performance Computing.*

I'm a Senior Engineer at KLA Ann Arbor, where I build tools for process control and yield management for the semiconductor industry. 

Professionally, I've had the privilege of working in state-of-the-art environments in multiple industries. During my time in defense R&D, I built signal processing pipelines for SONAR technologies ranging from uniform-linear-array systems to SOTA synthetic-aperture imaging systems. I also had the opportunity to intern at Intuitive Surgical in the AI&I division, where I built imaging stages and enabled integration of R&D pipeline with CUDA-backend. And prior to joining KLA, I was a Visiting Researcher in Computational Imaging Systems Laboratory at Boston University, where I built fast NeRF-based methods for ptychographic pipelines and accelerated pipelines for multi-camera array microscope.

During graduate school, my areas of focus were various topics in Applied Signal Processing and Deep Learning. 

My endeavors have allowed me to gain valuable experience and proficiency in Applied Signal Processing & Deep Learning: Computer Vision, Computational Imaging, Autonomous Driving, Audio, SONAR, and High-Performance-Computing Programming. I firmly believe that creative and successful R&D stems from a deep understanding of a core domain, complemented by a working knowledge of related domains. Thus my project selection approach is rooted in fundamental principles rather than being constrained by specific domains. That being said, I have a soft spot for projects that involve going from theorizing, all the way to low-latency builds. 

## Research Interests
Due to my interest in applied signal processing, most of my projects lies in Signal & Image Processing, Computer Vision, Robotic Perception, Machine & Deep Learning. Currently, I'm learning how to build low-latency C++ pipelines for these topics. While building an effective pipeline is a great achievement, building a faster pipeline is even better. Professionally, I'm investigating low-latency deep neural methods to improve computational imaging methods without performance trade-offs. 

### Key Expertise:
- *Domains*: Signal Processing: Audio, Speech and Image, Computational Imaging, Machine Learning, Machine Vision, Supervised, Unsupervised, and Reinforcement Learning.
- *Tools*: Matlab, Matlab Executable CUDA(MexCuda), Numpy, SciPy, PyTorch, CUDA, CuBLAS, Nvidia Performance Primitives (NPP), LibTorch (C++ backend/API to PyTorch).
- *Programming Languages*: C, C++, CUDA, Python, Matlab, and Bash

## Education
- **Master of Science**: Electrical and Computer Engineering, [*Boston University*](http://www.bu.edu)
- **Bachelor of Technology**, Electronics and Communication Engineering, [*College of Engineering Trivandrum*](https://www.cet.ac.in)



## Experience
- **Senior Algorithm Engineer**, [KLA](https://www.kla.com)
- **Visiting Researcher**, [Computational Imaging Systems Lab](https://sites.bu.edu/tianlab/)
- **MS Project Intern**, [Yobe Inc](https://yobeinc.com)
- **Advanced Imaging SW Engr Intern**, Advanced Imaging and Intelligence, [*Intuitive Surgical*](https://www.intuitive.com/en-us)
- **Electronics Engineer**, [Naval Physical and Oceanographic Laboratory](https://www.drdo.gov.in/drdo/labs-and-establishments/naval-physical-oceanographic-laboratory-npol), *Defence Research and Development Organisation*
- **Project Intern**, [Naval Physical and Oceanographic Laboratory](https://www.drdo.gov.in/drdo/labs-and-establishments/naval-physical-oceanographic-laboratory-npol), *Defence Research and Development Organisation*
- **Undergraduate Intern**, [Naval Physical and Oceanographic Laboratory](https://www.drdo.gov.in/drdo/labs-and-establishments/naval-physical-oceanographic-laboratory-npol), *Defence Research and Development Organisation*
- **Undergraduate Assistant**, Department of Electronics and Communication Engineering, [*College of Engineering Trivandrum*](https://www.cet.ac.in)

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

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Underwater Signal Simulator**, *Naval Physical and Oceanographic Laboratory*
- Authored fast signal simulator for underwater sensor arrays: uniform linear arrays (ULAs) and uniform planar array (UPAs).
- Engineered MATLAB-based vectorized signal simulator for diverse ocean environments and sensor arrays.
- Involved designing efficient ray-tracing and simulating doppler shifting and other signal propagation characteristics. 
- Developed to assist and assess sonar imaging algorithms. Achieved 7x speed by further translating to CUDA C.

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Computational Sonar Imaging**, *Naval Physical and Oceanographic Laboratory*
- Realised **4** beamforming-based computational imaging algorithms **each** for front-looking SONAR and side-scan SONAR.
- Wrote MATLAB pipelines employing full-aperture, dynamic-aperture, constant range-cell, and variable range-cell methods. 
- Wrote vectorized MATLAB code for a low latency implementation.
- Setup test-benches with physics-based signal simulation pipelines and imaging pipelines to mimic real-time performance.


<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**DSP Firmware**, *Naval Physical and Oceanographic Laboratory*
- Created DSP firmware with multiple modes and functionalities meeting client specifications and project constraints. 
- Modes involved match-filtering for signal detection, and signal processing based on the current mode of operation. 
- Programmed, tested, and integrated functionalities in MATLAB; later translated to C (primarily C89).
- Unified, tested, and assessed DSP firmware for deployment on TIVA-C, an ARM Cortex-M4F based MCU.

<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
<!-- =============================== -->
**Attendance Registration Using Face Recognition**, *College of Engineering Trivandrum*
- Built an attendance registration system using a deep learning pipeline to deploy in a classroom setting. 
- The machine learning stage consists of a CNN-based feature-extractor and a FCN based feature-classifier.
- The final attendance registration pipeline produced *precision* $ = **98.4%**, *recall* = **98.4%** and an *F-1 score* of **0.984**.
- Submitted, presented and showcased system to project committee, faculty, and students as part of curriculum.j

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


<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
<!-- Miscellaneous = Miscellaneous = Miscellaneous -->
## Miscellaneous

<!-- Matlab x CUDA = Matlab x CUDA -->
<!-- Matlab x CUDA = Matlab x CUDA -->
<!-- Matlab x CUDA = Matlab x CUDA -->
<!-- Matlab x CUDA = Matlab x CUDA -->
<!-- Matlab x CUDA = Matlab x CUDA -->
### Matlab x CUDA
I'm writing a book! It introduces engineers to integrating MATLAB with CUDA backends to develop low-latency pipelines, an approach commonly used in various R&D environments. Its under construction but if you're impatient and don't mind half-cooked content, you can check it out here: [An Introduction to Matlab x CUDA](https://vrsreeganesh.github.io/MatlabxCUDA/intro.html#)


<!-- Coursera = Coursera = Coursera -->
<!-- Coursera = Coursera = Coursera -->
<!-- Coursera = Coursera = Coursera -->
<!-- Coursera = Coursera = Coursera -->
<!-- Coursera = Coursera = Coursera -->
### Online Learning

The following courses allowed me to gain a deep and rigorous understanding of machine learning and the data-driven paradigm. Thanks to [*College of Engineering Trivandrum*](https://www.cet.ac.in) for sponsoring and allowing me to learn free of cost. 

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


<!-- AUV = AUV = AUV = AUV = AUV = AUV -->
<!-- AUV = AUV = AUV = AUV = AUV = AUV -->
<!-- AUV = AUV = AUV = AUV = AUV = AUV -->
<!-- AUV = AUV = AUV = AUV = AUV = AUV -->
<!-- AUV = AUV = AUV = AUV = AUV = AUV -->
### Autonomous Underwater Vehicles: A Perception & Control Approach

This side-project is an attempt to bring together my skills in beamforming-based computational imaging, signal simulation, perception \& control and reinforcement learning to enable the simulation and demonstration of an AUV designed for seafloor surveillance. 

The objectives involve the creation of signal simulation pipelines to mimic the signals received by the uniform-linear-arrays of the AUV in a real underwater environment, imaging pipeline to produce acoustic images from the simulated signals using beamforming techniques, and a control pipeline that takes the acoustic images and produce state-to-action mappings to control the AUV. 

The project is written in C++ (with STL as primary library) and  is currently under development, but you can explore its progress at [AUV Repository](https://github.com/vrsreeganesh/AUV/tree/main).



<!-- Books = Books = Books = Books -->
<!-- Books = Books = Books = Books -->
<!-- Books = Books = Books = Books -->
<!-- Books = Books = Books = Books -->
<!-- Books = Books = Books = Books -->
### Self Learning
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep Learning. MIT Press. 
- Sutton, R. S., & Barto, A. G. (2018). Reinforcement Learning: An Introduction. MIT Press.
- Kirk, D. B., & Hwu, W.-m. W. (2016). Programming massively parallel processors: A hands-on approach (3rd ed.). Morgan Kaufmann.
- Guntheroth, Kurt. Optimized C++: Proven Techniques for Heightened Performance. O'Reilly Media, 2015.
- Hennessy, John L., and David A. Patterson. Computer Architecture: A Quantitative Approach. 6th ed., Morgan Kaufmann, 2017.
- Sehr, V., & Andrist, B. (2018). C++ High Performance. Packt Publishing.
- Bancila, M. (2017). Modern C++ Programming Cookbook. Packt Publishing.

<!-- Contact = Contact = Contact = Contact -->
<!-- Contact = Contact = Contact = Contact -->
<!-- Contact = Contact = Contact = Contact -->
<!-- Contact = Contact = Contact = Contact -->
<!-- Contact = Contact = Contact = Contact -->
## Contact
- *primary email*: vrs [at] bu [dot] edu  (I highly suggest using this)
- *personal mail*: vrsreeganesh [at] gmail [dot] com  
- *alternative*: vrsreeganesh [at] cet [dot] ac [dot] in


<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
