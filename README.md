# Scratch the Surface of ML
ML Webinar Reference and Code
 
> keywords: machine learning, ml5.js, p5.js, friendly, introduction, workshop

## About

Welcome to this friendly introduction to machine learning with ml5.js. We're happy you're here.

## Code of Conduct

ml5.js is about machine learning and people.A major part of the ml5.js project is about creating broader engagement with machine learning and its effects on you, me, and the people and environment. As a user of ml5.js you are agreeing to abide by the ml5.js [code of conduct](https://github.com/ml5js/ml5-library/blob/development/CODE_OF_CONDUCT.md). It's easy and fun to be nice and respectful to those around you. Let's have a wonderful workshop together. If you're looking for more details on what constitutes being "not nice" please see [Mozilla's Community Participation Guidelines](https://www.mozilla.org/en-US/about/governance/policies/participation/) which are applicable to the space that ml5.js wants to create. 

If you have any questions or need to report any issues please contact: info@ml5js.org


## Overview:
- [Agenda]()
- [Key Questions and Takeaways]()
- [Resources]()
- [Terms]()
- [References]()
- [FAQ]()



## Agenda
>  ~2 hours

+ Hello!
+ Intro to Machine Learning 
+ Intro to ml5.js 
+ Quick 5 Min Break
+ Coding session
+ Build a quick demo 
+ Present demo 
+ Q&A, Closing notes 
+ Final Presentation

## Key Questions and Takeaways

> This is an introductory workshop to machine learning. We are focused on helping you to not only *learn through making* but also start to *reflect through making*. The following questions are here to help focus the **learning** and **reflecting**. 

+ What is ml5.js?
+ What is the relationship between ml5 and tensorflow.js?
+ Why machine learning in the browser is possible? and why is this amazing?
+ Why machine learning in the browser is important also for democratizing machine learning?
+ Why we need to be able to “poke” at machine learning as creatives - to see how the implications of “state of the art” impact people differently?


## The AI/ML universe

> AI/ML isn't just about advancements in technology, it is about a broader universe of things that are coming together (or diverging). These include changes (or lackthereof) in governance, cultural and social interactions with, awareness of, and attitudes, and feelings towards these new technologies, the development of new tools and communities around and against AI/ML, expansion of AI/ML education, and use of AI/ML in art and design or other domains outside "traditional AI/ML" spaces (e.g. engineering and computer science). 
>
> We increasingly interact with machine learning every day, whether it is through the way we access content through media providers such as Netflix, Twitter, and Instagram, or how we get from A to B on transit and vehicles. These increasingly algorithmically and data driven interactions do not come from the ether, but rather are the result of a complex and chaotic assemblage of social and technical forces.
>
> It is worth thinking about how the following factors affect or are affected by changes in AI/ML.

+ Research
+ Policies
+ Environment
+ Tools
+ Communities
+ Education
+ Art/Design

## Coding session

Let’s build a The Detection System if People Entering Home or Shop with face Mask built with ml5.js in which the audience shows their face the computer “sees 👀”  tells the if they are Safe or Not”. 

The Project uses ml5.js to use machine learning models trained in Google’s Teachable Machine and tensorflow.js to allow the Project to recognize custom objects 👜.

## Link to Presentation
+ (https://docs.google.com/presentation/d/1HlOiluUxyqvOcSYcodL33BsBbDs4jnYjYrjAM0FqhcQ/edit?usp=sharing)

## Resources

<!-- TODO -->
+ [Link to slides](https://docs.google.com/presentation/d/10cLjPGNKspZvVgR6KiG29bJKlnn_W-or9wLXTVuIVig/edit?usp=sharing)
  + Slide presentation with introductions, overview of terms, project highlights and more.
+ [ml5.js **website**](https://ml5js.org/): 
  + The main ml5.js website
+ [ml5.js **organization**](https://github.com/ml5js): 
  + The ml5.js github organization. Here you can see all the repositories that make up the ml5.js project.
+ [ml5.js **library**](https://github.com/ml5js/ml5-library):
  + The main library for ml5.js. This is where all the ✨happens!
+ [ml5.js **examples**](https://github.com/ml5js/ml5-examples):
  + The examples that correspond to all of the functions that are available in the ml5.js library. Emphasis is given to p5.js examples.
+ [ml5.js examples on **p5 web editor**](https://editor.p5js.org/ml5/sketches)
  + The examples can be found as well in the p5 web editor. You can run the sketches directly and tweak the examples as you'd like. Note, some of the examples currently do not work in the editor.  
+ [ml5.js Medium blog page](https://medium.com/@ml5js) 
  + ml5's Medium blog page.

## Terms

> Collected from "https://github.com/ml5js/ml5-friendly-intro-to-ml/blob/master/README.md"

- **Artificial Intelligence**:
  - AI is the science of making things smart:
  - Human Intelligence Exhibited by Machines
  - A broad term for getting computers to perform human tasks
  - **General AI**: fabulous machines that have all our senses (maybe even more), all our reason, and think just like we do.
  - Most of AI today is **Narrow AI** systems that can only do one (or a few) defined things as well or better than humans.
- **Machine Learning**:
  - One of the Approaches to Achieve Artificial Intelligence
  - A field of computer science that uses statistical techniques to give computer systems the ability to "learn" with data, without being explicitly programmed.
  - LOTS OF DATA
  - **Types of machine learning learning styles**:
    - **Supervised Learning**: 
      - Training data is labeled
    - **Unsupervised Learning**: 
      - The machine learn from an unlabelled data set.
      - Unsupervised learning can be grouped into clustering and dimensionality reduction.
    - **Reinforcement Learning**:
      - The machine learn by trial-and-error through reward or punishment.
  - **Types of machine learning outputs**:
    - **Regression**: Predict continuous values (price of a stock)
    - **Classification**: Predict a class/label (cat or dog?)
    - **Clustering**: Most similar other examples (Amazon related products recommendation)
    - **Sequence Prediction**: Predict the next word/sentence
  - **Types of machine learning use cases**:
    - Object Recognition
    - Speech and Sound Detection
    - Natural Language Processing
    - Prediction
    - Translation
- **Deep Learning**:
  - A technique for implementing Machine Learning
  - Deep learning - Uses multi-layered artificial neural networks to deliver state-of-the-art accuracy.
  - Can automatically learn representations/features from data such as images, video or text.
 
## The Machine Learning Process:

> The process of machine learning is messy. Like most data related projects, 80% of your time or more will be spent cleaning and preparing data for use. The rest of the time will be the actual "making" of your project. The machine learning process might be broadly (over)simplified into a handful of steps which includes: Data collection, data preparation, Training a machine learning model, and product/service integration.

* **Data collection**
  * E.g. an artist writes a script to automatically download all images of cats, dogs, and badgers from the internet. 
* **Data preparation**
  * E.g. the artist uses a crowd tasking service to 1. confirm that the image is either a cat, dog or badger, 2. Tag the image with the animal type, 3. Crop the image of the animal to a square aspect ratio. The artist then resizes all the images to 64x64px
* **Training a machine learning model**
  * E.g. the artist: 1. Uses a popular machine learning framework called Tensorflow in python to create a neural network. To create a neural network the artist, writes code that specifies image processing and data crunching methods that aim to pull out unique features for each animal type in the given images. The artist then 2. Iteratively refines and tests the model to achieve the highest accuracy.
* **Product/service integration...and awesome art projects**
  * E.g. the artist opensources this new pre-trained dog/cat/badger model. This comes just in time since the ASPCA in NYC has been in great need of a method to differentiate between the animals in their shelters. The artist is hired to create a web application that uses this model to label their shelter animals “cat”, or “dog” or “badger”. 

## ml5 in 3 

- Train the model in teachable machine
- Download the Model
- Copy the code and Run it !

> Team up and come up with a machine learning application using some of these suggestions below!

- [Image Classifier With Webcam](https://github.com/ml5js/ml5-examples/tree/release/p5js/ImageClassification)
- [PoseNet Code Examples](https://github.com/ml5js/ml5-examples/tree/release/p5js/PoseNet)
- [BodyPix Code Examples](https://github.com/ml5js/ml5-examples/tree/release/p5js/BodyPix)
- [Sounce Classifier Code Examples](https://github.com/ml5js/ml5-examples/tree/release/p5js/SoundClassification/SoundClassification_speechcommand)

... Or try adapting code from any of the other ml5 examples:

- [link to code](https://github.com/ml5js/ml5-examples/tree/release/p5js)
- [examples index](https://github.com/ml5js/ml5-examples#examples-index)


## References

### Online Learning Materials, Courses, and Workshops

+ [Coding Train Video Series](https://www.youtube.com/channel/UCvjgXvBlbQiydffZU7m1_aw):
  + [A Beginner's Guide to Machine Learning with ml5.js](https://www.youtube.com/watch?v=jmznx0Q1fP0&list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
  + [Neural Networks and Machine Learning](https://www.youtube.com/user/shiffman/playlists?view=50&sort=dd&shelf_id=16)
+ [ML - Basics] (https://www.youtube.com/watch?v=cKxRvEZd3Mw&list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
+ [Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291)

### Project references
+ Various curated ML projects  
  + [ML projects and inspiration](https://github.com/yining1023/machine-learning-for-the-web/wiki/References---Inspiration---Links)
  + [ml5.js community section](https://ml5js.org/community)
+ [Dan Shiffman's EyeO Talk 2019](https://github.com/CodingTrain/Eyeo-Festival-2019)
+ [Experiments with Google](https://experiments.withgoogle.com/)
+ [Food Chain Game](https://wp.nyu.edu/lillianritchie/2019/05/13/nature-of-code-final-food-chain-game/) by [Lillian Ritchie](https://wp.nyu.edu/lillianritchie/)

### Tools

#### Friendlier ML tools
+ [ml5.js](https://ml5js.org/)
+ [RunwayMl](https://runwayml.com/) - Machine learning for creators. "Bring the power of artificial intelligence to your creative projects with an intuitive and simple visual interface. Start exploring new ways of creating today."
+ [Google's teachable machine](https://teachablemachine.withgoogle.com/) - do transfer learning in the browser with google's teachable machine.

#### ML APIs for Python and javascript (advanced)
+ [Tensorflow](https://www.tensorflow.org/overview/) for python 
+ [Tensorflowjs](https://www.tensorflow.org/js/) - TensorFlow.js is a library for developing and training ML models in JavaScript, and deploying in browser or on Node.js 
+ [Keras](https://keras.io/) - Keras: The Python Deep Learning library

#### Cloud computing (advanced)
+ [Google co-lab](https://colab.research.google.com/) - 
+ [Spell.run](https://spell.run/) - "The most flexible and powerful end-to-end platform for ML and deep learning engineering." 
+ [Paperspace](https://www.paperspace.com/) - "The first cloud built for the future. Powering next-generation applications and cloud ML/AI pipelines."

### Other
+ [AI Winter](https://en.wikipedia.org/wiki/AI_winter)
+ [Book of Shaders](https://thebookofshaders.com/) - referred to for explaining CPU vs. GPU
+ [Red Burns, Founder of ITP](https://en.wikipedia.org/wiki/Red_Burns)
+ [P5.js](https://p5js.org/)
+ [Openmoji](https://openmoji.org/) - "Open-source emojis for designers, developers and everyone else!"


