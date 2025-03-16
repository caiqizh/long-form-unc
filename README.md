# Uncertainty in Long-Form Generation: An Overview
(last updated 16 Mar)


In this blog, we introduce key aspects of uncertainty in long-form generation. While uncertainty in short-form QA has been well explored, there is limited research on uncertainty in long-form QA.

## Long-Form Factuality

Before diving into long-form uncertainty, let's first examine long-form factuality. Popular long-form QA datasets primarily focus on a single topic entity for each question. For example:



```
Tell me a bio of Bill Gates.
```


A generated response might look like:


```
William Henry Gates III (born October 28, 1955) is an American businessman and philanthropist best known for co-founding the software company Microsoft with his childhood friend Paul Allen....
```


Notable datasets include:  
- [FactScore](https://arxiv.org/abs/2305.14251)  
- [LongFact](https://arxiv.org/abs/2403.18802)  
- [WildHallu](https://arxiv.org/abs/2407.17468)  

Regarding the evaluation of generated long-form responses, a common approach is [FactScore](https://arxiv.org/abs/2305.14251)-style fact-checking. This method involves breaking the response into atomic facts, fact-checking each piece, and then calculating the precision:

![FactScore](/long-form-unc/FactScore.png)

## Literature

Below are some relevant papers on uncertainty in long-form generation:

- [Calibrating Long-Form Generations from Large Language Models](https://arxiv.org/abs/2402.06544)  
- [LUQ: Long-Text Uncertainty Quantification for LLMs](https://arxiv.org/abs/2403.20279)  
- [Atomic Calibration of LLMs in Long-Form Generations](https://arxiv.org/abs/2410.13246)  
- [Linguistic Calibration of Long-Form Generations](https://arxiv.org/abs/2404.00474)  


## Contact

If you are interested in related topics or have any questions, please email cz391@cam.ac.uk
