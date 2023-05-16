# AI Supply Chain Dataset

## Dataset and overview 

This dataset provides a comprehensive view of AI industry companies and their relative positions and influence in the development of AIaaS. It visualizes a dispersed learning process of ML models across third parties. It can be accessed via [Google sheets](https://docs.google.com/spreadsheets/d/1qXyGQEz300LXmOexZz6Mj8WsR6yJ0K4hpYuUhM4fjJI/edit?usp=sharing), or simply by downloading the CSV file included in this git repo. Largely sourced from existing datasets built by VC efforts to track the AIaaS stack, this dataset categorize companies by their contribution to the learning process of ML-powered tools. 

## Example Configurations

There are many possible configurations for AIaaS Pipelines. Using our dataset, we can understand some of the relationships presented in a particular supply chain, and see the multiple contributors to the learning process of one AIaaS product. We highlight a few interesting examples below!

![Group 23](https://user-images.githubusercontent.com/16675936/224842622-c3ab6c02-5a3b-4673-a557-a2c5ae43c75d.png)

## Background

There is a wide range of ML development options stemming from the increasing ML accessibility provided by foundation models and the rising trend of AI-as-a-Service (AIaaS). Modeled off the similarly structured Software-as-Service (SaaS), AIaaS was a natural progression for technology so easily associated with traditional software. The AIaaS stack consists of products and services to support every aspect of the ML-powered tool development process (Lins et al., [2021](https://doi.org/10.1007/s12599-021-00708-w))



<img width="1558" alt="Screenshot 2023-03-22 at 6 23 51 PM" src="https://user-images.githubusercontent.com/16675936/227051950-81d2dd8e-382a-4c92-a670-7bd16bfd5ad4.png">




## Navigation
The dataset includes AIaaS stack positions, categories, subcategories, industry-specific labels, company descriptions, and URLs. 

<img width="1263" alt="Screenshot 2023-03-17 at 10 12 19 AM" src="https://user-images.githubusercontent.com/99421791/225929347-3b0b853e-a58e-4268-a9d7-b943ef317bbb.png">

1. **AIaaS Stack Position:** Company's position within the 4-level AIaaS stack. Represents the company's contribution to the dispersed learning process of an ML-powered tool.

2. **Category:** Further breakdown of the company's position in the supply chain. Provides insight into the company's products and services.

3. **Industry Labels:** Assigned to companies tailored exclusively to a non-AI industry (e.g., Healthcare, Financial, Legal). Indicates likely fine-tuning of upstream models for curated tasks.

4. **Subcategory:** Additional details or keywords related to the company's offerings. Useful for quickly differentiating companies in similar roles within the ecosystem

5. **Descriptions:** Longer summary of company services. Company descriptions were sourced semi-automatically using Google Sheets IMPORTXML function. Remaining descriptions were manually obtained from company websites.


## Dateset Sources

Each dataset was manually filtered for dead or acquired companies as well as duplicates. 

- **The 2021 and 2023 Machine Learning, AI and Data (MAD) Landscape Datasets**. (FirstMark, [2021](https://airtable.com/shrXVKG1JI9EHyoFE/tbl8oBlGhRFr9iBBY)), (FirstMark, [2023](https://mad.firstmarkcap.com/card))
  - Developed by Matt Turk and John Wu for the venture capitalist firm FirstMark, this dataset seeks to provide a macro view of the ML, AI, and data science landscape and analyze trends in the industry’s development. Its accompanying report particularly notes a rise in AutoML. As the most thorough open-source map of the AIaaS stack to my knowledge, companies included in the FirstMark MAD Landscape make up about 75% of the compiled dataset. It is the main contributor of companies from across the AIaaS stack, and includes hundreds of companies making up every level from infrastructure services to ML-powered tools.

- **The Generative AI Index** (Scale Venture Partners, [2022](https://www.scalevp.com/generative-ai)). 
  - Scale VP claims the most comprehensive generative AI market map and upkeeps financial and descriptive details on a little over 200 companies in the generative AI landscape. This dataset was selected for its focus on relatively small generative AI-powered enterprises: a group almost entirely dependent on fine-tuned foundation models. As a result, its contributing companies are almost all ML-powered tools.

- **The Conversational AI Ecosystem** (Zubair Talib, [2021](https://docs.google.com/spreadsheets/d/1Ar40U3jI5cfRVz3DfiVpdRMfOKAPd85NGgQvMeAJ_rQ/edit#gid=1679115793)).
  - Focused specifically on conversational AI, this dataset of ~150 companies provides a broad view of the types of conversational AI products and development tools available in 2021. It was selected for its narrowed focus: a more focused group of companies using generative AI that largely developed their products using LLMs. Due to its inclusion of companies that support conversational AI development, it contributes companies in the MLOps and AutoML level of the AIaaS stack as well as ML-powered tools.

- **Startups** (@builtwgenai, [2022](https://airtable.com/appTJ9kD2LEld3W1F/tbla2oe5olD5uWpRD/viwgycsJWVlQAmwrV?blocks=hide)). 
  - A community (now called Homebrew AI) sourced dataset of ~150 companies developed by members passionate about the generative AI landscape. Also selected for its focus on generative AI, this dataset had consistent overlap with The Generative AI Index. Its contributing companies are also almost all ML-powered tools.

- **The 2022 AI 50** (Forbes, [2022](https://www.forbes.com/lists/ai50/?sh=79816f86290f)). 
  - One of many “companies to watch” lists developed by Forbes, this dataset was selected despite its limited size for its thorough vetting process and relatively limited overlap with the other datasets. It is the only dataset other than FirstMark’s MAD Landscapes that collects companies from across the AIaaS stack rather than exclusively from companies applying generative AI.
  
- **Ecosystem Graphs: The Social Footprint of Foundation Models** (Rishi Bommasani, Dilara
                  Soylu, Thomas I.
                  Liao, Kathleen A.
                  Creel,  Percy
                  Liang, [2023](https://crfm.stanford.edu/ecosystem-graphs/index.html?mode=home)). 
  - Built by members of the Stanford Center for Research on Foundation Models, this ecosystem graph "documents the foundation models ecosystem, namely both the assets (datasets, models, and applications) and their relationships". It was selected because its in depth study of existing foundation models offers the best available look at the highest upstream aspects of the AI ecosystem today.




