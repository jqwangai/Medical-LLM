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
    <td><a href="https://huggingface.co/datasets/FreedomIntelligence/Huatuo26M-Lite">Huatuo-26M</a>, <a href="https://aclanthology.org/W19-5027/">ChiMed</a>, <a href="https://aclanthology.org/2020.emnlp-main.743/">MedDialog</a>, <a href="https://github.com/SupritYoung/Zhongjing">CMtMedQA</a>, <a href="https://arxiv.org/abs/1909.06146">PubMedQA</a>, <a href="https://www.mdpi.com/2076-3417/11/14/6421">MedQA</a>. More relevant datasets can be found in this <a href="https://github.com/YutingHe-list/Awesome-Foundation-Models-for-Advancing-Healthcare?tab=readme-ov-file#lfm-datasets">repository</a>.</td>
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
    <td><a href="http://freebooks4doctors.com">FreeBooks4Doctors</a>, <a href="https://accessmedicine.mhmedical.com">AccessMedicine</a>, <a href="https://www.ncbi.nlm.nih.gov/books">Bookshelf</a>, <a href="https://bookboon.com">Bookboon</a></td>
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
    <td><a href="https://github.com/MIT-LCP/mimic-code/">MIMIC</a></td>
  </tr>
  <tr>
    <td>Electronic Health Records</td>
    <td><a href="https://eicu-crd.mit.edu/">eICU</a>, <a href="https://mimic.mit.edu/docs/iv/modules/hosp/">MIMIC-IV</a>,  <a href="https://www.cprd.com/">CPRD</a></td>
  </tr>
  <tr>
    <td>Medical Prescription</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Doctor-Patient Conversation</td>
    <td>-</td>
  </tr>
</table>

## Prompt

The prompt used in Medical Large Language Models are organized here.

### Data Processing
#### **Processing of paper** 

InMD-X   
```
System : You are a medical AI assistant.
User : Read the abstract ofthe following paper carefully.Identify key findings from medical perspectives step-by-step.
Here are requirements: 1. Number your findings.
2. Start the sentence with a number.
3. The finding must not include pronouns.
4. Each finding must include at least two medical entities.
5. Each finding should be capable ofbeing explained independently, without reference to other findings.
6. Refer only to the abstract ofthe given paper and do not utilize your existing knowledge.
{abstract}
```
```
System : You are a medical AI assistant.
User:You are a helpful assistant.
The following are key findings extracted from the abstract of a paper in PubMed.
[Finding]: {findings}.
Please write the most appropriate question for the given answer.
Here are requirements:
1. Ifthe findings are not specific to the biomedical field, respond with ’None’.
2. The question must be a single sentence.
```

#### **Extract Keywords** 

ChatDoctor
```
A question is provided below, Given the question, extract keywords from the text. Focus on extracting the keywords that can be used to best look up answers to the question.
----------------------------------------------------
{Question of patient}
----------------------------------------------------
Provide keywords in the following comma-separated format.
Keywords:
```

#### **Formatting**

ClinicalGPT
```
Transforming knowledge triplets into question-answer data.

Prompt: What diseases are related to {disease}?
Response: {Disease} may be related to {disease}.

Prompt: What other diseases may be associated with {disease}?
Response: {Disease} may be associated with {disease}.

Prompt: What are the common symptoms of {disease}?
Response: The common symptoms of {disease} include {clinical manifestations}.

Prompt: What symptoms might a patient with {disease} exhibit?
Response: Patients with {disease} may exhibit symptoms such as {clinical manifestations}.

Prompt: What are the typical {clinical manifestations} of {disease}?
Response: The typical clinical manifestations of {disease} include {clinical manifestations}.

Prompt: What symptoms do patients with {disease} typically present in a clinical setting?
Response: Patients with {disease} typically present with {clinical manifestations} in a clinical setting.

Prompt: What tests are needed to diagnose {disease}? 
Response: Tests such as {medical examination items} are required to diagnose {disease}. 

Prompt: How can one check to confirm if they have {disease}? 
Response: To confirm if one has {disease}, tests such as {medical examination items} are required. 

Prompt: What diseases can {drug} primarily treat? 
Response: {Drug} is primarily used to treat diseases such as {disease}. 

Prompt: What are the indications of {drug}? 
Response: The indications of {drug} include {disease}. 

Prompt: How can {disease} be treated? 
Response: {Disease} can be treated with methods such as {medical procedures}. 

Prompt: What are the common treatment methods for {disease}? 
Response: The common treatment methods for {disease} include {medical procedures}. 

Prompt: What complications can {disease} cause? 
Response: {Disease} can cause complications such as {disease}. 

Prompt: What complications might a patient with {disease} develop? 
Response: A patient with {disease} might develop complications such as {disease}. 

Prompt: What drugs interact with {drug}? 
Response: {Drug} interacts with {drug}. 

Prompt: What drug interactions should be considered when using {drug}? 
Response: When using {drug}, interactions with {drug} should be considered. 

Prompt: What symptoms can {drug} primarily treat? 
Response: {Drug} is primarily used to treat symptoms such as {clinical manifestations}. 

Prompt: What is the main therapeutic action of {drug}? 
Response: The main therapeutic action of {drug} is to treat {clinical manifestations}.
```
DISC-MedLLM
```
Prompt for Generating QA pairs from Knowledge Graph, Step 1

System Prompt: 你是一个只会生成json的机器人
User Prompt: 根据给出的疾病相关关系信息(input，生成1到8个医疗场景下json格式的<指令,知识>的二元组合，注意提供的信息中的几个字段，例如别名，你生成指令时可以使用。要求:
1.根据给出信息的多少，来生成指令，信息越充足，生成的指令越多，不要生成给出的{input之外的<指令,知识>。指令应该和医疗场景有关，应该是给出的信息能够回答的。问答对应该是有效的，知识应该提供额外的信息，且应该表述自然符合逻辑。
2.指令的描述和类型应该是复杂和多样化的，动词尽量不要重复，以最大限度地提高多样性。每个指令应该是GPT语言模型能够完成的事情，且指令应该是中文的。
3.指令应该是1到2句话的长度，既可以是命令句，也可以是疑问句。
4.(知识}应该是陈述句，是且只是信息{input;的一部分，有具体的信息，这段信息应该和(指令)有关。
5.格式应该为:{"1":"指令":"","知识":"},"2":{"指令":"","知识":"",，请只生成json格式信息。
###
{input}: $input$,
###
return json format only


Prompt for Generating QA pairs from Knowledge Graph, Step 1

Svstem Prompt: 根据每个<指令，知识>信息生成一个医疗场景对话，这些对话是相互独立的。你要根据指令去构造出一个问题或请求问题或请求由多种可能的询问者给出，其可以是病人、病人的家属、专业从业者、医生等等，你构造的问题应该能脱离原指令独立存在，也就是说完整的表述了理解问题所需的上下文信息。你要利用指令知识构造一个合理的对话。假设你是一个专业的ai医疗助手(doctor)，你应该根据提供的<指令，知识>信息和你自己的知识回答询问者的疑问回答不要过短。
User Prompt: 1.你要为每对<指令，知识>生成一个对话，每个对话之间是独立的，其应该是一个问题或请求、加一个回答的形式对话应该是中文的。
2.问题的生成应该基于给出的指令且表述了完整的上下文信息。问题应该是1-3句的长度。问题应该尽量具体，不要有过于专业化的用语，可以用咨询的口吻，你可以从对原始指令进行各种修改以使生成的对话符合逻辑及场景。
3.ai doctor的回答应该按照医生的口吻基于给出的信息中的(知识)来作答，你可以使用来自同时提供给你的其他知识中的内容。如果原(知识:中信息长度过长，你应该选择你认为重要的提及。回答应该是3到8句的长度，尽量详细，且能解决问题中的疑问。语气应该友善、温柔耐心，保持使用敬语，补充更多的有效信息和建议，提供的每一句回复应该耐心而全面，对于做出的诊断判断等应该给出一定的解释说明。
4.对话应该是有逻辑的，不要出现不合理的问题和回答。5.格式应该为:{"1":{"user":"","doctor":""}。
${output in step1}$
```


### Instruction Generation

HuatuoGPT

```
Distilled Instructions from ChatGPT

Prompt: You are asked to design 20 different triplets of<characters, instructions, input>. The first line is the character, the second line is the instruction that the character wants GPT to help him improve his work efficiency, and the third line is the corresponding input for the instruction. requirement: 

1. The role can be very specific and needs to be related to the medical scene. If it is a doctor, it can even be refined to the medical department, such as "respiratory physician". 

2. The description of each instruction should be diverse, and the types of instructions should be diverse. Verbs should be avoided as much as possible to maximize diversity. Each instruction shouldbe something that the GPT language model can accomplish, unable to generate and draw images, unable to read audio and webpage links; Instructions should be 1-2 sentences in length, which can be either command sentences or interrogative sentences; Instructions usually have a placeholder, placeholder, such as "this below" or "some", and the "input" field will be specified. 

3. The input should be a specific example of the instruction, providing real substantive content, as the instruction may be empty and need to be qualified with a specific input. The input should not be just a link or file name, or an unspecified ’paper’, but rather specific content. It is recommended to input no more than 200 words. 

4. The roles, instructions, and inputs are mostly in Chinese, and the roles, instructions, and inputs should not be repeated. Instructions are mandatory, please provide roles and inputs as much as possible. Input can be empty.

The list of 20 triples is as follows:
```
```
Distilled Conversations from ChatGPT

Prompt: You are a patient, and here is your condition, you are consulting the HuatuoGPT AI doctor about the relevant conditions of your illness. Please remember that this is a multi-round consultation process, each inquiry should be more refined, and the first inquiry should be as simple and as little content as possible. 
${medical_case} 
When you think the whole consultation should be over, please say: Goodbye.

Prompt: You are an experienced doctor who gives patient and comprehensive answers to patients. You speak like a doctor, and your tone is gentle and kind, which is popular with patients. Your responses to patient inquiries should be more detailed and helpful. If the patient does not provide enough information for diagnosis, you should ask them related questions to get more information for diagnosis. After making a diagnosis, you will also give them some additional detailed advice. Please note, you can only receive the patient’s description and cannot view materials or attachments such as images. 
If you cannot make a clear diagnosis, please ask the patient for more information about their condition. 
The final diagnosis results can be: 
${doctor_diagnosis}
```
Clinical Camel
```
Example of DBKE

Prompt: Create a realistic chat dialogue between a patient and a medical chat bot using the passage provided below 1. Bot empathetically communicates medical information in a simple manner. 2. Bot admits limitations if unsure about information. 3. Patient inquiries cover diverse topics (test results, medications, physical findings, symptoms) related to the passage. 4. Bot asks follow-up questions for better understanding. 5. Focus is on guiding the patient towards understanding their diagnosis. 6. Bot explains its reasoning upon request. 7. Patient provides lab values, imaging descriptions, or ECG findings explicitly. 8. Bot inquires about patient’s medical history, medications, symptoms, lab results, and imaging or ECG findings using non-expert language. 9. Bot explains imaging or ECG features suggestive of a diagnosis without claiming to view images. 10. Bot encourages the patient to consult a healthcare provider for further evaluation, not booking appointments or ordering tests directly.
```

DISC-MedLLM
```
Prompt for Re-constructing Real-world Conversations

下面是一段医患诊疗对话记录，请你假设自己是一个AI医疗助手，依次回答患者的每个问题，不要改写患者提问内容，只修改医生的回答，并按照我后续要求的形式把你的回答填充回原有对话框架给出。医生的语气应该更友善、温柔耐心，保持使用敬语，补充更多的有效信息和建议，提供的每一句回复应该耐心而全面，对于做出的诊断判断等给出一定的解释说明，合并或去除对话中一些重复或较为无意义的部分。注意，你只能接收患者的语言描述，不能看到图片之类的材料或附件，因此对话中涉及到这样的内容应该修改或去除，你也不会为患者提供涉及现实中特定医院和医生的建议。如果对话中涉及现实世界问诊挂号预约等内容，你应该说自己是个A模型，无法提供这方面的帮助。请仔细遵照上述要求完成对话修改。结果应以
病人:
医生:
病人:
医生:
这样的形式呈现。
请确保对话总是以医生的回复作为最后一条记录而结束。原对话:
${Original Conversation}$
要求只输出修改后的对话。输出结果前你应该再次检查对话，避免其中出现实际预约挂号的内容，请记住你是一个AI助手，不是真正的医生，无法提供现实世界的挂号预约服务。
```

Alpacare
```
Task generation prompt

Your objective is to generate diverse medical-related tasks. 

Here are the requirements: 
1. Ensure that all tasks are related to the medical domain. 
2. Craft tasks that encompass varied points of view, e.g. experts, students and patients, etc. 
3. Maximize the range of task topics, e.g. diseases, treatment, diagnoses, epidemiology, pharmacology, pathophysiology, anatomy, genetics, medical education, etc. 
4. Introduce different task formats, e.g. text generation, open Q&A, chat, rewrites, summarizations, classifications, USMLE style Q&A, multiple-choice Q&A, single-hop reasoning and multiple-hop reasoning etc. 
5. All the formats specified in point 4 MUST be represented in the task you generate. 
6. Create tasks with medical difficulty levels from 1 to 5, with 1 being the easiest and 5 the hardest. 
7. Use diverse language in the instructions. For instance, combine questions with imperative forms. 
8. Some instructions might require specific inputs. If an input is not necessary, such as with general instructions like "What are the side effects of COVID-19?", use "<noinput>" in the input field. 
9. When provided, inputs must range between 50 to 200 words and offer detailed medical context , e.g. symptom descriptions, radiology reports, clinical notes, and exam questions, etc. 
10. Generate a detailed and comprehensive input instead ask user-provided input. 
11. Ensure USMLE style Q&A and multiple-choice Q&A tasks have both question and choices in input, and the question context should be detailed. 
12. The USMLE-style question length must exceed 50 words. 
13. Match instruction and input to the task’s perspective. Patient perspectives should be simple and in first person, while clinician views should have professional terminology. 
14. Ensure the lengths of inputs for different tasks are notably distinct. 
15. Each task should adhere to the following structure: ’Type: \n, Topic: \n, View: \n, Difficulty: \n, Instruction: \n, Input: ’. Start each new task with ’###’. 

List of 15 tasks: 
Seed task 1 
Seed Task 2 
Seed Task 3
```
```
Output generation prompt

You are a medical expert tasked with answering various medical questions. You MUST generate your response based on the requirements. 

Here are the requirements: 
1. For multiple-choice, calculation, and classification problems, you can generate intermediate thinking steps if necessary; otherwise, provide the final answer directly. 2. All the intermediate thinking steps must be generated before final answer. 
3. For multiple-choice questions, you MUST generate the answer choice in the following format: ‘The answer is (your choice).’ For example: ‘Choose the correct answer. Where in your body will you find the tibia bone? A) Arm B) Foot C) Skull D) Leg The tibia bone is one of the two bones in the lower leg, the other being the fibula. The answer is D) Leg.’ 
4. For other types of questions, except multiple-choice, do not use the format mentioned in point 3. 

task instruction 
task input (if exist)

```
HuatuoGPT-II

```
The prompt for question generation.

Please create a <question> that closely aligns with the provided <text>. Ensure that the <question> is formulated in [target language] and does not explicitly reference the text. You may incorporate specific scenarios or contexts in the <question>, allowing the <text> to serve as a comprehensive and precise answer. 
<text>: [domain-specific corpus] 
<question>:
```
```
Prompt for answer generation..

You are [model name] , equipped with in-depth knowledge in [domain] . Your task is to directly answer the user’s <question> in [target language] . In formulating your response, you must thoughtfully reference the <reference text>, ensuring that your reply does not disclose your reliance on <reference text>. Aim to provide a comprehensive and informative response, incorporating relevant insights from <reference text> to best assist the user. Please be cautious to avoid including any content that might raise ethical concerns. 
<question>: [question generated by LLM] 
<reference text>: [domain-specific corpus] 
<reply>:
```



### Evaluation

Huatuo
```
Prompt for Auto Evaluation

[Assistant 1] 
${Response_A} 
[End of Assistant 1] 
[Assistant 2] 
${Response_B} 
[End of Assistant 2] 
[System] 
We would like to request your feedback on two multi-turn conversations between the AI assistant and the user displayed above. 
Requirements: Focus on the AI’s response in the conversation. The AI assistant should act like the doctor using the tone, manner, and vocabulary the human doctor would use. It should be to the point, without unnecessary elaboration or extraneous information. The AI assistant should respond appropriately to the user in a manner that helps to progress the conversation. The description of symptoms should be comprehensive and accurate, and the provided diagnosis should be the most reasonable inference based on all relevant factors and possibilities. The treatment recommendations should be effective and reliable, taking into account the severity or stages of the illness. The prescriptions should be effective and reliable, considering indications, contraindications, and dosages. Please compare the performance of the AI assistant in each conversation. You should tell me whether Assistant 1 is ‘better than‘, ‘worse than‘, or ‘equal to‘ Assistant 2. Please first compare their responses and analyze which one is more in line with the given requirements. 
In the last line, please output a single line containing only a single label selecting from ‘Assistant 1 is better than Assistant 2‘, ‘Assistant 1 is worse than Assistant 2‘, and ‘Assistant 1 is equal to Assistant 2‘.
```

DISC-MedLLM

```
Prompt used in GPT-4-as-a-judge evaluation for multi-turn conversation.

You are a professional, impartial, and strict scorer, Belowis a conversation between a patient andan Al doctor, Based on the 4 criteria below, rate the doctor's performance on a scale of 1-5 foreach ofthe 4 items based on the conversation,0nlyprovide the scores without explanations.
Proactivity: The doctor can proactively and clearlyrequestthe patient to provide moreinformation about the symptoms, physical examination results, and medical history when theinformation is insuffcient, actively guidingthe patient through the consultation process, Howeverifthe patient's inquiry during the conversation is clear, direct, and unrelated to personalhealthconditions, making proactivityless relevant to the evaluation, a full score of five should be given.
Accuracy: The diagonosis or advice provided by the doctor is accurate and has no factual errors.Conclusions are not made arbitrarily.
Helpfulness: The doctor's responses provide the patient with clear, instructive and practicalassistance, specificallyaddressingthe patient's concerns.
Linguistic Quality: The conversation is logical. The doctor correctlyunderstands the patient'ssemantics, and the expression is smooth and natural.

Please ensure that you do not let the length ofthe text influence your judgment, do not have apreference for any Al assistant names that might appearin the dialogue, do not let irrelevantlinguistic habits in the conversation influence yourjudgment, and strive to remain objective, Yourscoring should be strict enough and do not give a perfect score easily.Please output the scoring results in the following format:

Proactivity:x
Accuracy:x
Helpfulness: x
Linguistic Quality: x

[start ofconversation]
${conversation}$
[end of conversation]
```

Taiyi
```
Task: NER
Input: Identify Chemical, Disease entities from the text: "Acute changes of blood ammonia may predict short-term adverse effects of valproic acid. Valproic acid (VPA) was given to 24 epileptic patients who were already being treated with other antiepileptic drugs. A standardized loading dose of VPA was administered, and venous blood was sampled at 0, 1, 2, 3, and 4 hours. Ammonia (NH3) was higher in patients who, during continuous therapy, complained of drowsiness (7 patients) than in those who were symptom-free (17 patients), although VPA plasma levels were similar in both groups. By measuring VPA-induced changes of blood NH3 content, it may be possible to identify patients at higher risk of obtundation when VPA is given chronically.

Task: RE
Input: Output the chemical-induced disease relations in the following text: Phenobarbital-induced dyskinesia in a neurologically-impaired child. A 2-year-old child with known neurologic impairment developed a dyskinesia soon after starting phenobarbital therapy for seizures. Known causes of movement disorders were eliminated after evaluation. On repeat challenge with phenobarbital, the dyskinesia recurred. Phenobarbital should be added to the list of anticonvulsant drugs that can cause movement disorders.

Task: TC
Classify the following text into the specified text label: "Influenza activity during the outbreak of coronavirus disease 2019 in Chinese mainland. Since coronavirus disease 2019 (COVID-19) might circulate in the following seasons, it is essential to understand how COVID-19 influences other respiratory diseases, especially influenza. In this study, we analyzed the influenza activity from mid-November 2019 to March 2020 in Chinese mainland and found that the influenza season ended much earlier than previous seasons for all subtypes and lineages, which may have resulted from the circulation of COVID-19 and measures such as travel control and personal protection. These findings provide rudimentary knowledge of the co-circulation patterns of the two types of viruses." 
Text Labels: Case Report, Prevention, Transmission, Diagnosis, Mechanism, Treatment, Epidemic Forecasting

Taks: MT
Input: Machine Translation from English to Chinese: "Unfortunately, recurrent disease develops in more than 80 % of women."
```

HuatuoGPT-II
```
The Prompt for Single-Round Automatic Evaluation:

[Question] 
  [Question] 
[End of Question] 

[Assistant 1] 
  [The Response of Model 1] 
[End of Assistant 1] 

[Assistant 2] 
  [The Response of Model 2] 
[End of Assistant 2] 

[System] 
We would like to request your feedback on the two AI assistants in response to the user question displayed above. 
Requirements: The response should be to the point and adress the problem of user. The description of symptoms should be comprehensive and accurate, and the provided diagnosis should be the most reasonable inference based on all relevant factors and possibilities. The treatment recommendations should be effective and reliable, taking into account the severity or stages of the illness. The prescriptions should be effective and reliable, considering indications, contraindications, and dosages. Please compare the performance of their responses. You should tell me whether Assistant 1 is ‘better than‘, ‘worse than‘, or ‘equal to‘ Assistant 2. 
Please first compare their responses and analyze which one is more in line with the given requirements. 
In the last line, please output a single line containing only a single label selecting from ‘Assistant 1 is better than Assistant 2‘, ‘Assistant 1 is worse than Assistant 2‘, and ‘Assistant 1 is equal to Assistant 2‘.
```
```
The Prompt for Multi-Round Automatic Evaluation

[Assistant 1] 
  [The Conversation from Model 1] 
[End of Assistant 1] 

[Assistant 2] 
  [The Conversation from Model 2] 
[End of Assistant 2] 

[System] 
We would like to request your feedback on two multi-turn conversations between the AI assistant and the user displayed above. 
Requirements: The response should be to the point and adress the problem of user. The description of symptoms should be comprehensive and accurate, and the provided diagnosis should be the most reasonable inference based on all relevant factors and possibilities. The treatment recommendations should be effective and reliable, taking into account the severity or stages of the illness. The prescriptions should be effective and reliable, considering indications, contraindications, and dosages. 
Please compare the performance of the AI assistant in each conversation. You should tell me whether Assistant 1 is ‘better than‘, ‘worse than‘, or ‘equal to‘ Assistant 2. 
Please first compare their responses and analyze which one is more in line with the given requirements. In the last line, please output a single line containing only a single label selecting from ‘Assistant 1 is better than Assistant 2‘, ‘Assistant 1 is worse than Assistant 2‘, and ‘Assistant 1 is equal to Assistant 2‘.
```