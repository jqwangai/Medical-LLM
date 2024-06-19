# A Survey on Large Language Models from General Purpose to Medical Applications: Datasets, Methodologies, and Evaluations

## Medical LLMs
**Detailed Information of Medical Large Language Models. Note: "Para." denotes parameters, "CP" denotes continued pretraining, "IFT" denotes instruction fine-tuning, and "HA" denotes human alignment.**
| Models | Backbone | Para. (B) | CP | IFT | IFT Methods | HA | Preferred Languages | Open Sources | Data |
|---|---|---|---|---|---|---|---|---|---|
| Med-PaLM  | PaLM  | 540 |  | $\checkmark$ | Prompt Tuning |  | EN |  | 01/2023 |
| ChatDoctor  | LLaMA  | 7 |  | $\checkmark$ | Full Para. |  | EN | [Link](https://github.com/Kent0n-Li/ChatDoctor) | 03/2023 |
| DoctorGLM   | ChatGLM  | 6 |  | $\checkmark$ | LoRA |  | CN | [Link](https://github.com/xionghonglin/DoctorGLM) | 04/2023 |
| BenTsao   | LLaMA  | 7 |  | $\checkmark$ | LoRA |  | CN | [Link](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | 04/2023 |
| ChatGLM-Med | ChatGLM  | 6 |  | $\checkmark$ | LoRA |  | CN | [Link](https://github.com/SCIR-HI/Med-ChatGLM) | 04/2023 |
| MedAlpaca | LLaMA  | 7, 13 |  | $\checkmark$ | Full Para., LoRA |  | CN | [Link](https://github.com/kbressem/medAlpaca) | 04/2023 |
| PMC-LLaMA | LLaMA2  | 13 | $\checkmark$ | $\checkmark$ | Full Para. |  | CN | [Link](https://github.com/chaoyi-wu/PMC-LLaMA) | 04/2023 |
| HuatuoGPT | Baichuan ,  Ziya-LLaMA  | 7, 13 |  | $\checkmark$ | Full Para. | $\checkmark$ | CN | [Link](https://github.com/FreedomIntelligence/HuatuoGPT) | 05/2023 |
| ChatMed-Consult  | LLaMA  | 7 |  | $\checkmark$ | LoRA |  | CN | [Link](https://github.com/michael-wzhu/ChatMed) | 05/2023 |
| Med-PaLM 2  | PaLM2  | - |  | $\checkmark$ | - |  | EN |  | 05/2023 |
| Clinical Camel  | LLaMA2  | 13, 70 |  | $\checkmark$ | QLoRA |  | EN | [Link](https://github.com/bowang-lab/clinical-camel) | 05/2023 |
| ShenNong-TCM  | LLaMA  | 7 |  | $\checkmark$ | LoRA |  | CN | [Link](https://github.com/michael-wzhu/ShenNong-TCM-LLM) | 06/2023 |
| MedicalGPT  | Ziya-LLaMA , Baichuan-Chat  | 13 | $\checkmark$ | $\checkmark$ | LoRA | $\checkmark$ | EN, CN | [Link](https://github.com/shibing624/MedicalGPT) | 06/2023 |
| ClinicalGPT  | BLOOM  | 7 |  | $\checkmark$ | LoRA | $\checkmark$ | CN |  | 06/2023 |
| DISC-MedLLM | Baichuan  | 13 |  | $\checkmark$ | Full Para. |  | CN | [Link](https://github.com/FudanDISC/DISC-MedLLM) | 08/2023 |
| Zhongjing | Ziya-LLaMA  | 13 | $\checkmark$ | $\checkmark$ | LoRA | $\checkmark$ | CN | [Link](https://github.com/SupritYoung/Zhongjing) | 08/2023 |
| BianQue | ChatGLM  | 6 |  | $\checkmark$ | Full Para. |  | CN | [Link](https://github.com/scutcyr/BianQue) | 10/2023 |
| Alpacare | LLaMA  | 7, 13 |  | $\checkmark$ | Full Para. |  | EN | [Link](https://github.com/scutcyr/BianQue) | 10/2023 |
| Qilin-Med | Baichuan  | 7 | $\checkmark$ | $\checkmark$ | LoRA | $\checkmark$ | CN | [Link](https://github.com/williamliujl/Qilin-Med) | 10/2023 |
| Taiyi | Qwen  | 7 |  | $\checkmark$ | QLoRA |  | EN, CN | [Link](https://github.com/DUTIR-BioNLP/Taiyi-LLM) | 11/2023 |
| ChiMed-GPT | Ziya-LLaMA  | 13 | $\checkmark$ | $\checkmark$ | Full Para. | $\checkmark$ | CN | [Link](https://github.com/synlp/ChiMed-GPT) | 11/2023 |
| MediTron | LLaMA2  | 7, 70 | $\checkmark$ | $\checkmark$ | Full Para. |  | EN | [Link](https://github.com/epfLLM/meditron) | 11/2023 |
| HuatuoGPT-II | Baichuan2 ,  Yi  | 7, 13, 34 |  | $\checkmark$ | Full Para. |  | CN | [Link](https://github.com/FreedomIntelligence/HuatuoGPT-II) | 12/2023 |
| AntGLM-Med  | GLM  | 10 | $\checkmark$ | $\checkmark$ | Full Para., LoRA, Cpoly |  | EN, CN |  | 12/2023 |
| GPT-doctor | Baichuan2-Chat  | 13 |  | $\checkmark$ | LoRA |  | CN |  | 12/2023 |
| EpilepsyLLM  | LLM-JP , LLaMA  | 1.3, 7 |  | $\checkmark$ | LoRA |  | EN, JP | [Link](https://github.com/masa3141/japanese-alpaca-lora) | 01/2024 |
| BioMistral | Mistral-Instruct  | 7 | $\checkmark$ | $\checkmark$ | QLoRA |  | Multilingual | [Link](https://huggingface.co/BioMistra) | 02/2024 |
| MMedLM  | InternLM  | 7 | $\checkmark$ | $\checkmark$ | Full Para., LoRA |  | Multilingual | [Link](https://github.com/MAGIC-AI4Med/MMedLM) | 02/2024 |
| InMD-X  | Neural-Chat  | 7 | $\checkmark$ | $\checkmark$ | Full Para., LoRA |  | EN |  | 02/2024 |
| Me-LLaMA  | LLaMA2  | 13, 70 | $\checkmark$ | $\checkmark$ | LoRA |  | EN | [Link](https://github.com/BIDS-Xu-Lab/Me-LLaMA) | 02/2024 |
| JMLR  | LLaMA2  | 7, 13 | $\checkmark$ | $\checkmark$ | - |  | EN |  | 02/2024 |
| BiMediX  | Mixtral-8x7B  | 8x7 |  | $\checkmark$ | QLoRA |  | EN, Arabic | [Link](https://github.com/mbzuai-oryx/BiMediX) | 02/2024 |
| OncoGPT  | LLaMA  | 7 |  | $\checkmark$ | LoRA |  | EN | [Link](https://github.com/OncoGPT1/OncoGPT1) | 02/2024 |
| Apollo  | Qwen ,  Gemma ,  Yi  | 0.5, 1.8, 2, 6, 7 | $\checkmark$ | $\checkmark$ | Full Para. |  | Multilingual | [Link](https://github.com/FreedomIntelligence/Apollo) | 03/2024 |
| Qibo  | LLaMA  | 7, 13 | $\checkmark$ | $\checkmark$ | Full Para. |  | CN |  | 03/2024 |
| Hippocrates  | LLaMA2 , Mistral  | 7 | $\checkmark$ | $\checkmark$ | LoRA | $\checkmark$ | EN, CN | [Link](https://cyberiada.github.io/Hippocrates) | 04/2024 |
| MING-MOE  | Qwen1.5-Chat  | 1.8, 4, 7, 14 |  | $\checkmark$ | LoRA |  | EN, CN | [Link](https://github.com/MediaBrain-SJTU/MING) | 04/2024 |
| Aloe  | Mistral ,  LLaMA3  | 7, 8 |  | $\checkmark$ | Full Para. | $\checkmark$ | EN | [Link](https://huggingface.co/HPAI-BSC/Llama3-Aloe-8B-Alpha) | 05/2024 |

## Corpus Source

<table><thead>
  <tr>
    <td rowspan="5">Existing Public Datasets</td>
    <td>Unstructured Data</td>
    <td><a href="https://ufal.mff.cuni.cz/ufal\_medical\_corpus">UFAL Medical Corpus</a>, <a href="https://github.com/togethercomputer/RedPajama-Data">RedPajama</a>, <a href="https://commoncrawl.org">Common Crawl</a> </td>
  </tr>
  <tr>
    <td>QA</td>
    <td><a href="https://huggingface.co/datasets/FreedomIntelligence/Huatuo26M-Lite">Huatuo-26M</a>, <a href="https://aclanthology.org/W19-5027/">ChiMed</a>, <a href="https://aclanthology.org/2020.emnlp-main.743/">MedDialog</a>, <a href="https://github.com/SupritYoung/Zhongjing">CMtMedQA</a>, <a href="https://arxiv.org/abs/1909.06146">PubMedQA</a>, <a href="https://www.mdpi.com/2076-3417/11/14/6421">MedQA</a></td>
  </tr>
  <tr>
    <td>Human Preference Data</td>
    <td><a href="https://github.com/SupritYoung/Zhongjing">Zhongjing_rlhf</a>, <a href="https://github.com/shibing624/MedicalGPT">MedicalGPT</a></td>
  </tr>
  <tr>
    <td>Knowledge Graphs</td>
    <td><a href="https://www.nlm.nih.gov/research/umls/index.html">UMLS</a>, <a href="https://github.com/king-yyf/CMeKG_tools">CMeKG</a>, <a href="https://bios.idea.edu.cn">BIOS</a></td>
  </tr>
  <tr>
    <td>NLP Tasks</td>
    <td>-</td>
  </tr></thead>
  <tr>
    <td rowspan="6">Public Medical Corpus</td>
    <td>Medical Encyclopedias</td>
    <td><a href="https://medlineplus.gov">MedlinePlus</a>, <a href="https://bios.idea.edu.cn">Mayo Clinic</a>, <a href="https://www.webmd.com">WebMD</a></td>
  </tr>
  <tr>
    <td>Medical Textbooks</td>
    <td><a href="http://freebooks4doctors.com">FreeBooks4Doctors</a>, <a href="https://archive.org">Internet Archive</a>, <a href="https://bookboon.com">Bookboon</a></td>
  </tr>
  <tr>
    <td>Medical Academic Literature</td>
    <td><a href="https://pubmed.ncbi.nlm.nih.gov">PubMed</a>, <a href="https://www.embase.com">Embase</a>, <a href="https://www.sciencedirect.com">ScienceDirect</a></td>
  </tr>
  <tr>
    <td>Medical Websites</td>
    <td><a href="https://www.teladochealth.com">Teladoc Health</a>, <a href="https://www.dxy.cn">Ding Xiang Yuan</a>, <a href="https://www.pagd.net">Ping An Good Doctor</a>, <a href="https://www.98point6.com">98point6</a>, <a href="https://www.haodf.com">Haodf</a></td>
  </tr>
  <tr>
    <td>Medical Guidelines</td>
    <td><a href="https://www.cancercareontario.ca/en/guidelines-advice">CCO</a>, <a href="https://www.cdc.gov">CDC</a>, <a href="National Institute for Health and Care Excellence">NICE</a>, <a href="https://www.who.int/publications/who-guidelines">WHO</a></td>
  </tr>
  <tr>
    <td>Package Inserts</td>
    <td><a href="https://www.rxlist.com">RxList</a>, <a href="https://www.drugs.com">Drugs</a></td>
  </tr>
  <tr>
    <td rowspan="4">Professional Medical Organization Corpus</td>
    <td>Clinical Notes</td> 
    <td></td>
  </tr>
  <tr>
    <td>Electronic Health Records</td>
    <td><a href="https://eicu-crd.mit.edu/">eICU</a>, <a href="https://mimic.mit.edu/docs/iv/modules/hosp/">MIMIC-IV</a>,  <a href="https://www.cprd.com/">CPRD</a></td>
  </tr>
  <tr>
    <td>Medical Prescription</td>
    <td></td>
  </tr>
  <tr>
    <td>Doctor-Patient Conversation</td>
    <td></td>
  </tr>
</table>

## Data Processing Prompt
