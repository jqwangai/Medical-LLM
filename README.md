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
    <td>UFAL Medical Corpus, RedPajama </td>
  </tr>
  <tr>
    <td>QA</td>
    <td>Huatuo-26M, ChiMed, MedDialog, CMtMedQA, PubMedQA, MedQA,</td>
  </tr>
  <tr>
    <td>Human Preference Data</td>
    <td>Zhongjing\_rlhf, MedicalGPT</td>
  </tr>
  <tr>
    <td>Knowledge Graphs</td>
    <td>UMLS, CMeKG, BIOS</td>
  </tr>
  <tr>
    <td>NLP Tasks</td>
    <td>-</td>
  </tr></thead>
</table>

## Data Processing Prompt
