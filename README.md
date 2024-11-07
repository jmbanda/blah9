# BLAH 9 Proposal: Benchmarking and evaluation of automated phenotype definition extractions with large language models

Building on the work performed at [BLAH8](https://docs.google.com/presentation/d/1zfoxt6Kif8lygkLqJPGHxMpKzW7S04ULEcM9pWpcXpw/edit?usp=sharing), published at [Genomics and Informatics](https://genomicsinform.biomedcentral.com/articles/10.1186/s44342-024-00023-2) and presented at the [OHDSI 2024 symposium](https://www.ohdsi.org/2024showcase-52/), we propose to create a formal benchmark suite for the evaluation of automated extraction of phenotype definitions. We have expanded our phenotype definitions from 10 to 25 since BLAH8, and we will focus during BLAH9 to create a set of open-source jupyter notebooks that leverage Hugging Face LLM models to create a benchmark of open-source LLMs. We will use our current results from GPT3.5 and GPT4 as baseliness and will add at least results for five or more open-source models found via Hugging Face. The idea of having a benchmark is to have some baseline results and have all code available for reproducibility. With an advantage of the benchmark suite being jupyter notebooks is that other users can add their own LLMs to Hugging Face, and then just run our notebooks to evaluate and benchmark their methods. This approach will allow easier community participation, as well as incentivize the submission of custom LLMs to the Hugging Face platform and have a standard and transparent benchmark/feedback mechanism. Having a public and open-source benchmark, code-base, and methodology will allow for reliable evaluation of current and new LLMs as well as will enhance reproducibility as all prompts and engineering decisions will be available. Additionally, we will create a leaderboard style to guarantee the robustness of our evaluations. 

Additional background:

Electronic phenotyping is a process that uses electronic health records (EHRs) and other clinical data to identify patients with specific clinical characteristics. It can help with a variety of research and clinical tasks, including: 

- Clinical trials: Subject recruitment for clinical trials 
- Disease diagnosis: Provide real-world evidence for disease diagnosis 
- Drug development: Provide real-world evidence for drug development 
- Precision medicine: Identify special groups of patients that are important for precision medicine 

Electronic phenotyping harnesses both structured and unstructured data, integrating rule-based systems, machine learning techniques, natural language processing (NLP), and hybrid methodologies to analyze and categorize patient information [1](https://pubmed.ncbi.nlm.nih.gov/31218278/).
