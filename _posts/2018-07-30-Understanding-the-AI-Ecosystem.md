---
layout: post
title: "Understanding the AI ecosystem"
date: 2018-07-18
---

_A 4 layer framework approach is proposed to understand the various players and technologies contributing to the AI ecosystem.An in-depth exploration of each layer will follow in subsequent posts._


We often come across many AI related terms, technologies, companies and applications. However, with new developments happening at a fast pace it gets confusing how these various terms, technologies etc. are inter-related.

For example Google is a well known for it’s Google Assistant that is akin to Amazon’s Alexa or Apple’s Siri. But it also manufactures something called a TPU, a piece of hardware and is a leader in providing an AI development platform called Tensorflow which is used by nearly 80% of the Data scientists(well, by those on GitHub). So what is Google actually trying to do?Microsoft along with it’s cloud platform Azure offers a platform called AzureML along with Cognitive services.

NVIDIA kickstarted the deep learning revolution with it’s GPU. Waymo, Tesla, Drive.ai and Uber are a handful of companies working on driverless cars. There cannot be enough articles about Alexa’s tremendous promise to be your personal genie.

How similar or dis-similar are these companies in what they do? How can one make sense of how all these technologies fit together to create some value?

The 4 layer framework is inspired by a friend and deep learning expert Saurabh Tiwary of Microsoft who first articulated this characterization of the AI ecosystem. Even as the landscape evolves you will still be able to put your finger on where the development is taking place and it’s over all value to the ecosystem.
The 4 layer approach is also very useful for companies and startups to get an understanding of their competition where they fit in and what value they can add in the value chain.

![Understanding_AI_Ecosystem_1.jpg](/assets/img/Understanding_AI_Ecosystem_1.jpg)

This post is just an introduction to the 4 layer approach and contains an example based description of each layer. In future posts I will describe each layer more comprehensively.

**Layer 1:The Hardware**

One of the key catalysts for the rise of deep learning was the tremendous progress made in hardware computations. Deep learning requires massive parallel matrix calculations and for a while although the theory existed there was no practical way of implementing it. But by a happy co-incidence the GPU being built by NVIDIA for graphic intensive gaming systems turned out to be exactly what was need to crunch the numbers for Deep learning. And thus started the story of deep learning and the creation of new kind of hardware chips like the TPU,FPGA and new purposes for the humble CPU.

**Layer 2: The programming languages and Platforms**

Since Deep learning was initially restricted to the academic world most of the initial libraries and algorithms were built using Python and R. The great support for Python within the community also led to having key libraries like Pandas, Scikitlearn etc. which enabled a rich community of python machine learning developers. As machine learning became more prevalent companies like Google started to provide platforms like tensorflow which also provided a rich library of functions and capabilities at a higher programming level. These platforms abstract the computation of the underlying calculations to a large extent, enable troubleshooting of algorithms through visualizations and finally also provide the ability to render the models to production.

**Layer 3:The technologies and models**

The Image-net challenge by Dr Fei Fei Li and team at Stanford was a great stimulus for experimenting with new machine learning and deep learning techniques. A new architecture of layering neural networks along with implementing the concept of back propagation was a tremendous success in the Image-net challenge and subsequently launched the resurgence of deep learning.

Deep learning primarily can be categorized as Feed forward networks, used typically in predictive use cases. Convolutional neural networks have been in the news for their amazing computer vision applications. Recurrent Neural networks which tend to leverage the temporal nature of data have also found tremendous success in speech recognition and translation. We also have upcoming unsupervised technologies like Reinforcement learning where the algorithms are rewarded or punished for the choices they make as they make their way to the expected goal. In order to solve for lack of large amounts of labelled data that is usually required in supervised deep learning we have the technology of Generative Adversarial Networks invented by Ian Goodfellow. It is apparent the technology invention and experiment phase is super vibrant in the industry and it is only the beginning.

**Layer 4:The applications**

The applications of AI have caught the common people’s imagination on fire with help from the media which has tended to bring a little bit of hollywood into today’s AI capabilities. AI has been compared to taking over the human race to not even as smart as a 5 year old.
But we do see applications like driverless cars, near real time language translations, detecting cancer cells etc. which are making a difference in human lives and productivity. We might not yet be all Hollywood has made AI to be, but we are on our way and it will be a tremendous ride.

Thus by looking at the AI ecosystem in a layered approach one can build a coherent story as to what is happening with the technology and where it is going.