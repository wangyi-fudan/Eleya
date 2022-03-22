# Eleya
Artificial Intelligence That Generate Novel **Biomedical** Text

![Eleya](Eleya.jpg)
  
# User Agreement

1: All rights, obligations and responsibilities of the text generated by Eleya belong to the user, and the developer does not assume any rights, obligations or responsibilities.

2: Due to its limited intelligence, Eleya should be regarded as an incapacitated supervised artificial intelligence, and the user assumes the role of guardian.

3: If the text generated by Eleya needs to be published in public, it should be manually reviewed by the publisher before publishing. After publishing, it will be regarded as the publisher's own speech, and the publisher will be responsible for all the influence of the published speech.

4: If you do not agree to this user agreement, please **DO NOT** use this software. If you use this software, you **AGREED** to this user agreement.

# Hardware and OS requirements

2GB RAM, modern CPU with SSE2 instructions.

Eleya.exe:  Windows XP and above, 32-bit or 64-bit systems.

Eleya: 64-bit Linux systems.

# How to use Eleya

1: Open a console.

2: Enter ./Eleya "Lung cancer is the most common".

3: The algorithm will continue the text in quotation marks.

4: You can dump the output into a file by using ">".

# Download Links

The training is in progress and may not stop for a long period. The long term goal of BPC is around 0.830.

Lastest weight: **20220322** BPC=0.908

链接: https://pan.baidu.com/s/1AN8Oc-fig1YufVCBWuQt6g  

密码: na8b

# The algorithm behind Eleya

Eleya is based on an improved GPT-like character-level transformer architecture. 

It has 31 transformer blocks and 864 embeding dimensions with 1024 byte context and has 250M weights.

It is coded by cuda C++ from scratch using my own tiny deep learning framework and was trained on an A100 GPU for 41 days now.

The training corpus is 136 GB PubMed abstracts + PMC full text.

I estimate that the power of Eleya should be similar to that of GPT-2.

# Why not open source it?

It takes me a whole year to develop Eleya day and night. Technically it is more advanced than Google etc. I want to keep the technology right now. I share the software because I feel lonely.

# Dr. Wang Yi 王一

School of Life Sciences, Fudan University

Mar 22, 2022

godspeed_china@yeah.net

