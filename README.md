# Healthcare clinical notes extraction, summarization in standard clinical reporting format
This repository will highlight leveraging power of LLM to uncover insights from unstructured disparate medical/clinical notes and standardize/summarize it in medical standard clinical reporting format like SBAR 

# Healthcare Usecase 1:  - Data extraction and Summarization of clinical notes in SBAR format
In this example we will be extracting a wide range of tabular data and summarize it in standard SBAR structure. SBAR is an acronym for Situation, Background, Assessment, Recommendation; a technique that can be used to facilitate prompt and appropriate communication. This communication model has gained popularity in healthcare settings, especially amongst professions such as physicians and nurses. It is a way for health care professionals to communicate effectively with one another, and also allows for important information to be transferred accurately. The format of SBAR allows for short, organized and predictable flow of information between professionals.

## INPUT

![input](tab.png)


:arrow_down:
:arrow_down:
:arrow_down:

## OUTPUT

 ![input](sbar.png)





## [Solution notebook](/usecase1.ipynb)

# Healthcare Usecase 2:  - Extract data and create structured insights from medical history images and unstructured data.
In this example we will be extracting text from medical history images and create medical insights and summary from it.


## Example 1  - INPUT

![input](hp1.png)

:arrow_down:
:arrow_down:
:arrow_down:

## Example 1  - OUTPUT
![input](summary.png)



 

## Example 2  - INPUT

![input](hp2.png)

:arrow_down:
:arrow_down:
:arrow_down:

## Example 2  - OUTPUT
![input](soap.png)




## [Solution notebook](/usecase2.ipynb)

# Run the solution
### Pre-requisite
You can run the solution in Sagemaker Studio notebooks. Ensure that your domain user has the permission to access bedrock and textract. 
You can check out more details : https://docs.aws.amazon.com/sagemaker/latest/dg/studio.html

### Run the notebook
Once the pre-requisite is taken care, you can git clone this repository and run the notebook in Sagemaker studio. The kernel can be Data Science 3.0 , python 3 and ml.t3medium.

You can use the notebook as a baseline and iterate from there. 

# Stay in touch and connect with me
Connect and follow me on [Linkedin](https://www.linkedin.com/in/neelam-koshiya-3b8407120/)

<a href="https://www.linkedin.com/in/neelam-koshiya-3b8407120/" rel="Follow me">![Neelam](linkedin.jpg)</a>


