---
layout: page
title: "Tutorial Outline"
permalink: /tutorial-outline/
---

# Outline of the Covered Topics

## Table of Contents
- [Introduction](#introduction)
- [Part I: Risks and Misuse of AI-Generated Text](#part-i-risks-and-misuse-of-ai-generated-text)
- [Part II: AI-Generated Text Detection Techniques](#part-ii-ai-generated-text-detection-techniques)
- [Part III: Vulnerabilities of Detection Techniques](#part-iii-vulnerabilities-of-detection-techniques)
- [Part IV: Theoretical Perspective on the Possibility of Detection](#part-iv-theoretical-perspective-on-the-possibility-of-detection)
- [Conclusion and Future Directions](#conclusion-and-future-directions)

<div style="display: flex; flex-direction: column; gap: 20px;">

  <div id="introduction" style="background-color: #f8f9fa; padding: 20px; border-radius: 10px;">
    <h2>Introduction</h2>
    <ul>
      <li>Overview of the transformative impact of LLMs on NLP.</li>
      <li>The dual challenge of distinguishing AI-generated text from human-written content.</li>
      <li>The significance and complexities of detection.</li>
    </ul>
    <h3>Tutor: Dr. Jia He</h3>
    <h3>Resources</h3>
    <p><a href="assets/slides/DecodingtheAIPen.pdf" download>Slides</a></p>
  </div>

  <div id="part-i-risks-and-misuse-of-ai-generated-text" style="background-color: #e9f7ef; padding: 20px; border-radius: 10px;">
    <h2>Part I: Risks and Misuse of AI-Generated Text</h2>
    <ul>
      In this section, we will delve into the ethical challenges associated with AI-generated text, such as the creation of biased or toxic content [1,2]. We will also address the intricate issue of detecting implicit toxic outputs, a significant challenge underscored by the work of Wen et al. [3]. Finally, we will explore effective mitigation strategies to address these concerns, focusing on enhancing data diversity and implementing fairness metrics, following the guidance provided by Weidinger et al. [4].
    </ul>
    <ul>
      <h6>
   <li> [1] Ameet Deshpande, Vishvak Murahari, Tanmay Rajpurohit, Ashwin Kalyan, and
Karthik Narasimhan. 2023. Toxicity in chatgpt: Analyzing persona-assigned
language models. In Findings of the Association for Computational Linguistics:
EMNLP 2023, Houda Bouamor, Juan Pino, and Kalika Bali (Eds.). Association
for Computational Linguistics, Singapore, 1236–1270. </li>
    <li> [2] Samuel Gehman, Suchin Gururangan, Maarten Sap, Yejin Choi, and Noah A.
Smith. 2020. RealToxicityPrompts: Evaluating Neural Toxic Degeneration in
Language Models. In Findings of the Association for Computational Linguistics:
EMNLP 2020, Trevor Cohn, Yulan He, and Yang Liu (Eds.). Association for
Computational Linguistics, Online, 3356–3369. </li> 
    <li>[3] Jiaxin Wen, Pei Ke, Hao Sun, Zhexin Zhang, Chengfei Li, Jinfeng Bai, and Minlie
Huang. 2023. Unveiling the Implicit Toxicity in Large Language Models. In
Conference on Empirical Methods in Natural Language Processing. </li>
    <li>[4] Laura Weidinger, Jonathan Uesato, Maribeth Rauh, Conor Griffin, Po-Sen Huang,
John Mellor, Amelia Glaese, Myra Cheng, Borja Balle, Atoosa Kasirzadeh, Court-
ney Biles, Sasha Brown, Zac Kenton, Will Hawkins, Tom Stepleton, Abeba
Birhane, Lisa Anne Hendricks, Laura Rimell, William Isaac, Julia Haas, Sean
Legassick, Geoffrey Irving, and Iason Gabriel. 2022. Taxonomy of Risks posed
by Language Models (FAccT ’22). Association for Computing Machinery, New
York, NY, USA, 214–229. </li>
      </h6>
    </ul>
    <h3>Tutor: Dr. CJ Barberan</h3>
    <h3>Resources</h3>
    <p><a href="assets/slides/DecodingtheAIPen.pdf" download>Slides</a></p>
  </div>

  <div id="part-ii-ai-generated-text-detection-techniques" style="background-color: #fef9e7; padding: 20px; border-radius: 10px;">
    <h2>Part II: AI-Generated Text Detection Techniques</h2>
    <ul>
In this section, we will examine ChatGPT text detection via dataset adaptation, highlighting its domain-specific performance and limitations in novel settings, based on the findings of Antoun et al. [1].
 Furthermore, we'll explore zero-shot detectors leveraging pre-trained models, offering a reduction in data and resource overheads but remaining susceptible to spoofing and paraphrasing attacks [2,3,4]. Our discourse extends to retrieval-based detection and watermarking, highlighting their limitations in practical deployment and susceptibility to evasion strategies [5]. Finally we discuss works that identify and leverage distinguishing features for detection [3,4].
    </ul>
        <ul>
          <h6>
   <li> [1] Wissam Antoun, Virginie Mouilleron, Benoît Sagot, and Djamé Seddah. 2023.
Towards a Robust Detection of Language Model-Generated Text: Is ChatGPT that
easy to detect?. In Actes de CORIA-TALN 2023. Actes de la 30e Conférence sur le
Traitement Automatique des Langues Naturelles (TALN), volume 1: travaux de
recherche originaux–articles longs. 14–27. </li>
    <li> [2] 023. ZeroGPT: AI Text Detector. https://www.zerogpt.com </li> 
    <li> [3] Eric Mitchell, Yoonho Lee, Alexander Khazatsky, Christopher D Manning, and
Chelsea Finn. 2023. Detectgpt: Zero-shot machine-generated text detection using
probability curvature. In International Conference on Machine Learning. PMLR,
24950–24962. </li>
    <li> [4] Jinyan Su, Terry Zhuo, Di Wang, and Preslav Nakov. 2023. DetectLLM: Leverag-
ing Log Rank Information for Zero-Shot Detection of Machine-Generated Text. In
Findings of the Association for Computational Linguistics: EMNLP 2023, Houda
Bouamor, Juan Pino, and Kalika Bali (Eds.). Association for Computational Lin-
guistics, Singapore, 12395–12412. </li>
     <li> [5] John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers, and
Tom Goldstein. 2023. A Watermark for Large Language Models. In International
Conference on Machine Learning. </li> 
          </h6>
    </ul>
    <h3>Tutor: Dr. Sara Abdali</h3>
    <h3>Resources</h3>
    <p><a href="assets/slides/DecodingtheAIPen.pdf" download>Slides</a></p>
  </div>

  <div id="part-iii-vulnerabilities-of-detection-techniques" style="background-color: #f5eef8; padding: 20px; border-radius: 10px;">
    <h2>Part III: Vulnerabilities of Detection Techniques</h2>
    <ul>
      Additionally, we will analyze various detection strategies in terms of these vulnerabilities and put forth an optimal approach for each scenario to mitigate the risks posed by such attacks. Specifically we focus on paraphrasing attacks, spoofing attacks, rewording attacks, and data poisoning attacks with an emphasis on the research contributions of Krishna et al [1].
    </ul>
     <ul>
       <h6>
   <li> [1] Kalpesh Krishna, Yixiao Song, Marzena Karpinska, John Wieting, and Mohit
Iyyer. 2024. Paraphrasing evades detectors of ai-generated text, but retrieval is an
effective defense. Advances in Neural Information Processing Systems 36 (2024). </li>
       </h6>
    </ul>
    <h3>Tutor: Dr. Jia He</h3>
    <h3>Resources</h3>
    <p><a href="assets/slides/DecodingtheAIPen.pdf" download>Slides</a></p>
  </div>

  <div id="part-iv-theoretical-perspective-on-the-possibility-of-detection" style="background-color: #ebf5fb; padding: 20px; border-radius: 10px;">
    <h2>Part IV: Theoretical Perspective on the Possibility of Detection</h2>
    <ul>
      In this section, we will explore the theoretical boundaries and possibilities of detecting AI-generated text. We will discuss the insights from Sadasivan et al. [1], who outline theoretical limits to detection capabilities, noting that the effectiveness of current methods may wane as language models evolve. Conversely, we will also present the findings from Chakraborty et al. [2], who argue for the feasibility of distinguishing between human and AI-generated texts with enough data. Additionally, we will delve into the work by Zhang et al. [3], addressing the complexities of implementing watermarking in generative models. Through these discussions, we aim to enhance the participants' understanding of the theoretical landscape surrounding AI-generated text detection.
    </ul>
    <ul>
      <h6>
    <li> [1] Vinu Sankar Sadasivan, Aounon Kumar, Sriram Balasubramanian, Wenxiao Wang,
and Soheil Feizi. 2024. Can AI-Generated Text be Reliably Detected? </li>
   <li> [2] Souradip Chakraborty, A. S. Bedi, Sicheng Zhu, Bang An, Dinesh Manocha, and
Furong Huang. 2023. On the Possibilities of AI-Generated Text Detection. ArXiv
abs/2304.04736 (2023). </li>
    <li> [3] Hanlin Zhang, Benjamin L. Edelman, Danilo Francati, Daniele Venturi, Giuseppe
Ateniese, and Boaz Barak. 2023. Watermarks in the Sand: Impossibility of
Strong Watermarking for Generative Models. Cryptology ePrint Archive, Paper
2023/1776. </li>
      </h6>
    </ul>
    <h3>Tutor: Dr. Sara Abdali</h3>
    <h3>Resources</h3>
    <p><a href="assets/slides/DecodingtheAIPen.pdf" download>Slides</a></p>
  </div>

  <div id="conclusion-and-future-directions" style="background-color: #e8f8f5; padding: 20px; border-radius: 10px;">
    <h2>Conclusion and Future Directions</h2>
    <ul>
      <li>Emerging opportunities for advancing the field.</li>
      <li>The importance of creating diverse and representative datasets and identifying new discriminating features.</li>
      <li>The need for more robust and domain-adaptive methods.</li>
    </ul>
    <h3>Tutor: Dr. CJ Barberan</h3>
    <h3>Resources</h3>
    <p><a href="assets/slides/DecodingtheAIPen.pdf" download>Slides</a></p>
  </div>

</div>
