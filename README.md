<p align="center">
  <h1 align="center">
    <img src="static/logo.png" alt="Nexus-o" height="40" style="position:relative; top:6px;">
  Nexus-o: An Omni-Perceptive And -Interactive Model for Language, Audio, And Vision</h1>
    <p align="center">
    <strong>Che Liu</strong>
    ,
    <strong>Yingji Zhang</strong>
    ,
    <strong>Dong Zhang</strong>
    ,
    <strong>Weijie Zhang</strong>
    ,
    <strong>Chenggong Gong</strong>
    ,
     <strong>Yu Lu</strong>
    ,
     <strong>Shilin Zhou</strong>
    ,
     <strong>Ziliang Gan</strong>
    ,
    <br>
    <strong>Ziao Wang</strong>,
    <strong>Haipang Wu</strong>,
    <strong>Ji Liu</strong>,
    <strong>Andre Freitas</strong>,
    <strong>Qifan Wang</strong>,
    <strong>Zenglin Xu</strong>,
    <br>
    <strong>Rongjunchen Zhang</strong><sup>♠</sup>,
    <strong>Yong Dai</strong><sup>♠</sup>
  </p>
  <div class="is-size-5 publication-authors" align="center">
        <span class="author-block">
            <sup>♠</sup>Corresponding author, daiyongya@outlook.com, zhangrongjunchen@myhexin.com
        </span>
    </div>
    <br>
  📖<a href="https://arxiv.org/pdf/2503.01879">Paper</a> |🏠<a href="https://hithink-research.github.io/MME-Finance/">Homepage</a></h3>|🤗<a href="https://huggingface.co/datasets/hithink-ai/MME-Finance">Huggingface</a></h3>
  
<div align="center"></div>
<p align="center">
  <p>
Human beings perceive the real world through a spectrum of sensory modalities, encompassing auditory, visual, and linguistic faculties. This work proposes an industry-level omni-modal large language model (LLM) pipeline that integrates auditory, visual, and linguistic modalities to overcome challenges such as limited tri-modal datasets, high computational costs, and complex feature alignments. Our pipeline consists of three main components: First, a modular, end-to-end framework enabling flexible configuration of various encoder–LLM–decoder architectures. Second, a lightweight training strategy that pre-trains audio-language alignment on the state-of-the-art vision-language model Qwen2.5-VL, thus avoiding the costly pre-training of vision-specific modalities. Third, an audio synthesis pipeline that generates high-quality audio-text data from diverse real-world scenarios, supporting applications such as Automatic Speech Recognition and Speech-to-Speech chat. To this end, we introduce an industry-level omni-modal LLM, NEXUS-O. Extensive experiments validate the efficacy of our pipeline, yielding the following key findings: (1) In the visual understanding task, NEXUSO exhibits superior performance compared with its backbone model - Qwen2.5-VL-7B, validating the efficiency of our training strategy. (2) Within the English Spoken Question-Answering task, the model achieves better accuracy than the same-period competitor (i.e, MiniCPM-o2.6-7B) in the LLaMA Q. benchmark. (3) In our realworld ASR testset, NEXUS-O achieves outstanding performance, indicating its robustness in real scenarios. (4) In the Speech-to-Text Translation task, our model outperforms Qwen2-Audio-Instruct-7B. (5) In the Text-to-Speech task, based on pretrained vocoder (e.g., Fishspeech1.4 or CosyVoice2.0), NEXUS-O is comparable to its backbone vocoder on Seed-TTS benchmark. (6) An in-depth analysis of tri-modal alignment reveals that incorporating the audio modality enhances representational alignment between vision and language.

## 📢 News 
- 🚀 [08/01/2025] Our paper has been accepted for ACM MM 2025.

## 💡 Highlights


## Results



## ✒️Citation
```
@article{liu2025nexus,
  title={Nexus: An Omni-Perceptive And-Interactive Model for Language, Audio, And Vision},
  author={Liu, Che and Zhang, Yingji and Zhang, Dong and Zhang, Weijie and Gong, Chenggong and Li, Haohan and Lu, Yu and Zhou, Shilin and Lu, Yue and Gan, Ziliang and others},
  journal={arXiv preprint arXiv:2503.01879},
  year={2025}
}
```

## 📄 License
![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg) ![Data License](https://img.shields.io/badge/Data%20License-CC%20By%20NC%204.0-red.svg) **Usage and License Notices**: The data and code are intended and licensed for research use only.
License: Attribution-NonCommercial 4.0 International It should abide by the policy of OpenAI: https://openai.com/policies/terms-of-use

## 💖 Acknowledgement
