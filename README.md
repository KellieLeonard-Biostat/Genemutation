# Gene Mutations and Their Impact on Cancer Types

**Abstract**
This report investigates the relationship between gene mutations and their association with various cancer types. Using a dataset of 1,000 samples, we analysed gene names, mutation types, and mutation frequencies across several cancers. Through a series of visualisations, including heatmaps, bar plots, and interactive bubble charts, we identified key mutations and their correlations with specific cancers. This study aims to uncover patterns that may inform personalised treatment strategies and contribute to the understanding of cancer's molecular underpinnings. The results highlight the importance of genes like TP53, BRCA1, and KRAS in cancer development while also suggesting that mutation types may vary significantly across cancers.

**Introduction**
Gene mutations are central to the development of cancer. Mutations in specific genes can drive the uncontrolled growth of cells, leading to tumour formation. Over the years, numerous genes have been identified as critical players in cancer, such as TP53, BRCA1, and KRAS. These mutations often serve as biomarkers for cancer diagnosis and prognosis, and their identification has paved the way for targeted therapies.
Understanding the distribution of mutations across different cancer types is crucial for developing precision medicine strategies. The dataset used in this study contains information on various gene mutations and their associated cancer types, providing an opportunity to explore the frequency and distribution of mutations across a broad spectrum of cancers. This report aims to present the findings in a clear, visual format and discuss the implications of these mutations in cancer biology.

**Methods**
**Dataset Overview**
The dataset used in this analysis consists of 1,000 records detailing gene mutations and their association with cancer. Key features include:
•	Gene Name: The gene that is mutated.
•	Mutation Type: The type of mutation categorised as Substitution, Insertion, or Deletion.
•	Cancer Type: The cancer type associated with the mutation.
•	Mutation Frequency: The frequency of the mutation in the dataset.

**Data Analysis**
The analysis was conducted using Python and the following libraries:
•	matplotlib for basic plotting.
•	seaborn for statistical visualisations.
•	plotly for interactive charts.

**Key analyses included:**

•	Descriptive Statistics: To summarise the mutation frequencies.

•	Heatmaps: To examine correlations between mutations and cancer types.

•	Bar Plots: To visualise the distribution of mutations across cancer types.

•	Interactive Bubble Charts: To display the relationship between gene mutations and their frequencies across various cancers.
 
**Results**

**1. Top 10 Gene Mutations Frequency**
The bar plot displays the top 10 genes with the highest mutation frequencies. Genes such as TP53, BRCA1, and KRAS emerge as the most frequently mutated, indicating their central role in cancer development. These genes are well known for their involvement in tumour suppression, DNA repair, and cell cycle regulation.

<img width="425" alt="image" src="https://github.com/user-attachments/assets/60bd10be-0b49-4187-8b04-1607acd7e5a7" />

Figure 1. Top 10 gene mutation frequencies 

**2. Mutation Type Distribution by Cancer Type**
The stacked bar plot illustrates how mutation types (Substitution, Insertion, and Deletion) are distributed across different cancer types. The most common mutation type is Substitution, followed by Deletion and Insertion. Notably, Substitution mutations are predominant across all cancer types, aligning with existing studies that suggest this mutation type is most commonly associated with environmental factors such as smoking or radiation exposure.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/53e6ff35-b8d0-4b7d-8a35-36a6008f5d74" />

Figure 2. Mutation type distribution by cancer type 

**3. Gene Mutations Across Different Cancer Types (Bubble Chart)**
This interactive bubble chart visualises the frequency of mutations across different genes and cancer types. Each bubble represents a gene, with its size corresponding to the mutation frequency. This chart provides an intuitive way to see which mutations are more prevalent in specific cancers.

<img width="478" alt="image" src="https://github.com/user-attachments/assets/f2ce743a-6145-4616-a281-dd0521c603a0" />

Figure 3. Gene mutations across different cancer types 

**4. Correlation Between Mutation Frequency and Cancer Type (Heatmap)**
The heatmap highlights the relationship between mutation frequency and cancer type. Certain genes, such as TP53 and BRCA1, show high mutation frequencies across multiple cancer types, while other genes are more cancer-type specific. This suggests that some mutations may be indicative of particular cancers, and identifying these mutations could improve diagnostic precision.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/9b11b023-9316-4f98-87dc-ec81d2431c6f" />

Figure 4. Correlation between mutation frequency and cancer type 

**5. Distribution of Mutation Types by Gene**
This stacked bar plot displays the distribution of mutation types (Substitution, Insertion, Deletion) for each gene. TP53 is strongly associated with Substitution mutations, while other genes, such as EGFR, exhibit a more balanced distribution of mutation types. This variation suggests that different genes may have distinct mutation patterns, potentially influencing their role in cancer biology.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/7abf98a9-83a2-48ab-9016-1b5a71f646d5" />

Figure 5. Distribution of mutation types by gene 

**6. Gene Mutation Frequency Across Cancer Types (Heatmap)**
This heatmap visualizes the frequency of mutations in specific genes across different cancer types. For example, BRCA1 mutations are highly associated with Breast cancer, while KRAS mutations are more common in Pancreatic cancer. These findings align with well-established cancer genetics, highlighting the potential for targeted therapies based on specific gene mutations.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/a7ad7994-5f70-40c2-8911-4d40b6fba6d6" />

Figure 6. Gene mutation frequency across cancer types 

**7. Gene Mutation Frequency Histogram**
The histogram shows the distribution of mutation frequencies across all genes. Most genes exhibit moderate mutation frequencies, while a small number of genes show very high frequencies. This indicates that while many genes are frequently mutated, there are a few genes that are far more prone to mutations, which may play a more significant role in cancer development.

<img width="421" alt="image" src="https://github.com/user-attachments/assets/4c237c39-98f9-4bcb-9ed3-8f359235f3ec" />

Figure 7. Distribution of mutation frequency 
 
 

**Analysis**
The analysis reveals several important insights:

•	High Mutation Frequencies: Genes like TP53, BRCA1, and KRAS are frequently mutated across different cancer types. These genes are well-known for their roles in tumour suppression, DNA repair, and oncogenesis, making them key targets for cancer research and treatment.

•	Mutation Type Distribution: Substitution mutations are the most common type across all cancer types. This is consistent with studies that link substitution mutations to environmental exposures such as UV radiation and carcinogens. The presence of Insertion and Deletion mutations in specific cancers suggests that these mutation types may be associated with particular molecular mechanisms or environmental factors.

•	Cancer-Type Specificity: Certain genes are more frequently mutated in specific cancers. For example, BRCA1 mutations are more prevalent in Breast cancer, while KRAS mutations are common in Pancreatic cancer. This highlights the potential for targeted genetic testing and personalised treatment strategies based on mutation profiles.
 

**Discussion**
**Gene Mutation Profiles in Cancer**
This study supports existing research suggesting mutations in genes like TP53, BRCA1, and KRAS are pivotal in developing various cancers. TP53 mutations, for instance, are frequently observed in Lung, Colorectal, and Breast cancers, which is consistent with its well-known role as a tumour suppressor. BRCA1 mutations, on the other hand, are strongly linked with Breast and Ovarian cancers, as this gene is involved in DNA repair mechanisms.
The predominance of Substitution mutations across cancer types is not surprising, given the well-established relationship between environmental carcinogens and DNA damage. The high mutation frequencies in TP53 and KRAS also suggest that these genes may serve as biomarkers for detecting and monitoring cancer progression.

**Implications for Targeted Therapies**
The findings of this study have significant implications for cancer therapy. By identifying the most frequently mutated genes in specific cancer types, clinicians can develop more effective, targeted therapies. For instance, targeted therapies that inhibit the activity of KRAS in Pancreatic cancer or BRCA1 in Breast cancer could improve patient outcomes and reduce side effects compared to conventional treatments.

**Limitations and Future Research**
One limitation of this study is the use of a synthetic dataset, which may not accurately reflect real-world mutation distributions. Future studies should use real genomic data to validate these findings. Additionally, further research is needed to investigate the functional consequences of specific mutations, as this could provide more insight into how these mutations drive cancer development.
