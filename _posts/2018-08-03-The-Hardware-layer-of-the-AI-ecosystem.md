---
layout: post
title: "The hardware layer of the AI ecosystem"
date: 2018-08-03
---
_Depending on your goal there is a processor for that._

The hardware layer of the AI ecosystem is a very competitive business with giants like NVIDIA, Intel, Google, Apple, Amazon fighting for domination or looking to serve their own computing needs.

Hardware resources like the processors are required during 2 phases of the AI models. The first phase which is the most data and resource intensive is called the training phase. The second phase which is substantially less resource intensive is called the inference. AI smart applications use the inference models.

![hard_layer_ecosystem_1.jpg](/assets/img/hard_layer_ecosystem_1.jpg)
        _Mapping of processors based on design and usage_

The speed of the processors can vary depending upon whether they are generic or have been created specifically for a deep learning model.

**CPU:** The central processing unit is a processor that is driven typically by the clock speed, cache size and the number of cores. These characteristics define how fast the CPU can go through instructions/operations. The CPU communicates with Input/Output devices and memory storage thus more suited in a computer than to do simple matrix calculations as required in the training phase of an AI model.

**GPU:** The Graphics processing unit is a processor that was specifically built for graphics processing. An outcome of catering to the gaming industry, the GPU does simple operations such as matrix calculations, but at a massive scale. This scale of matrix operations capability gave the GPUs a distinct advantage when harnessed in the training phase of AI modelling. Since 2012, when AlexNet made a breakthrough at the Large Scale Visual Challenge by using deep learning techniques and the GPU, there has been a resurgence of deep learning and as a consequence the utility of GPUs in training deep learning models.

**FPGA:** Field programmable gate array is a generic chip that as the name suggests can be re-programmed for specific purposes. The driver behind re-programming the chip could be the creation of a new algorithm. Since AI algorithms and architectures are being always experimented with, FPGAs capability of being able to be repurposed play an interesting role.

**ASIC:** Application specific integrated circuits are purpose built for a specific application. A great example is Google’s TPU. Strategic needs of AI giants like Google, Microsoft, Apple, Amazon etc. is pushing these companies to come up with their own chip sets built to perform specific tasks, for example speech recognition and computer vision tasks. The outcome of creating their own chips at the very least will put a price ceiling on the pricing power of NVIDIA’s GPUs which dominate the market today.

The hardware market to say the least is still open to competition with the giants battling it out and is too early to call a winner. However the implication is, if you are a serious deep learning practitioner depending on your goal, you will most probably will be having a High Performance computing team which will be making a choice among the multitude of processors out there.

For most companies trying to leverage AI models it is most likely that the processing part of the modeling process will be abstracted away and High performance computing will be offered as a service.