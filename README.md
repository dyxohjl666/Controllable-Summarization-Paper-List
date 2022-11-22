# Controllable-Summarization-Paper-List

A summary of must-read papers for Controllable Summarization.

- Contributed by **[Yixi Ding](https://github.com/dyxohjl666)**

Please follow [this link](./README_by_year.md) to view papers in chronological order. 

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Models</a></td></tr>

<tr><td colspan="2"><a href="#applications">3. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="#length-controllable-summ">3.1 Length Controllable Summrization</a></td>
    <td>&ensp;<a href="#language-controllable-summ">3.2 Language Controllable Summrization</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#content-controllable-summ">3.3 Content Controllable Summrization</a></td>
    <td></td>
</tr>

<tr><td colspan="2"><a href="#evaluation">4. Evaluation</a></td></tr>
<tr><td colspan="2"><a href="#resources">5. Resources</a></td></tr>
</table>

## [Survey papers](#content)

## [Models](#content)   

1. **Don't Give Me the Details, Just the Summary! Topic-Aware Convolutional Neural Networks for Extreme Summarization** EMNLP, 2018. 
[paper](https://paperswithcode.com/paper/dont-give-me-the-details-just-the-summary)
[github link](https://github.com/EdinburghNLP/XSum)

   *Shashi Narayan, Shay B. Cohen, Mirella Lapata*

## [Applications](#applications)

### [Generic Controllable Summarization](#generic-controllable-summ)

1. **CTRLsum: Towards Generic Controllable Text Summarization** arXiv preprint, 2020.

   *Junxian He, Wojciech Kryściński, Bryan McCann, Nazneen Rajani, Caiming Xiong*

### [Length Controllable Summarization](#length-controllable-summ)

This direction is about generating summaries within a specific length.

1. **Length-controllable Abstractive Summarization by Guiding with Summary Prototype** arXiv preprint, 2020. [paper](https://arxiv.org/abs/2001.07331)
   
   *Itsumi Saito, Kyosuke Nishida, Kosuke Nishida, Atsushi Otsuka, Hisako Asano, Junji Tomita, Hiroyuki Shindo, Yuji Matsumoto*

2. **Length Control in Abstractive Summarization by Pretraining Information** ACL, 2022. [paper](https://aclanthology.org/2022.acl-long.474/)

    *Yizhu Liu, Qi Jia, Kenny Zhu*
    
### [Language Controllable Summarization](#language-controllable-summ)

This direction is about generating summaries for layman or experts.

1. **TLDR: Extreme Summarization of Scientific Documents** ACL, 2020. 
[paper](https://aclanthology.org/2020.findings-emnlp.428/)
[dataset](https://github.com/allenai/scitldr)

    *Isabel Cachola, Kyle Lo, Arman Cohan, Daniel Weld*

### [Content Controllable Summarization](#content-controllable-summ)

This direction is about generating summaries based on specific entities or keywords.

1. **Planning with Learned Entity Prompts for Abstractive Summarization** TACL, 2021. [paper](https://aclanthology.org/2021.tacl-1.88/)

    *Shashi Narayan, Yao Zhao, Joshua Maynez, Gonçalo Simões, Vitaly Nikolaev, Ryan McDonald*


## [Evaluation](#evaluation)



## [Resources](#resources)

Controllable summarization datasets and toolkits. 

1. **LongSumm** [dataset](https://github.com/guyfe/LongSumm)

2. **Don't Give Me the Details, Just the Summary! Topic-Aware Convolutional Neural Networks for Extreme Summarization** EMNLP, 2018. 
[paper](https://paperswithcode.com/paper/dont-give-me-the-details-just-the-summary)
[dataset](https://github.com/EdinburghNLP/XSum)

   *Shashi Narayan, Shay B. Cohen, Mirella Lapata*

3. **TLDR: Extreme Summarization of Scientific Documents** ACL, 2020. 
[paper](https://aclanthology.org/2020.findings-emnlp.428/)
[dataset](https://github.com/allenai/scitldr)

    *Isabel Cachola, Kyle Lo, Arman Cohan, Daniel Weld*
    
4. **TLDR9+: A Large Scale Resource for Extreme Summarization of Social Media Posts** ACL Workshop, 2021.
[paper](https://aclanthology.org/2021.newsum-1.15/)
[dataset](https://github.com/sajastu/reddit_collector)

   *Sajad Sotudeh, Hanieh Deilamsalehy, Franck Dernoncourt, Nazli Goharian*
   
5. **Making Science Simple: Corpora for the Lay Summarisation of Scientific Literature** EMNLP, 2022.
[paper](https://arxiv.org/abs/2210.09932)
[github link](https://github.com/tgoldsack1/corpora_for_lay_summarisation)

   *Tomas Goldsack, Zhihao Zhang, Chenghua Lin, Carolina Scarton*
   
6. **ScisummNet: A Large Annotated Corpus and Content-Impact Models for Scientific Paper Summarization with Citation Networks** AAAI, 2019.
[paper](https://arxiv.org/abs/1909.01716?context=cs.IR)
[github link](https://github.com/WING-NUS/scisumm-corpus)

   *Michihiro Yasunaga, Jungo Kasai, Rui Zhang, Alexander R. Fabbri, Irene Li, Dan Friedman, Dragomir R. Radev*