Description
=============

#### - TRAC-1 Shared Task on Aggression Identification
- Identifying trolling, aggression, cyber-bullying and hate speech etc.
- Aggression identification by classifying follow three classes in text: Overtly Aggressive (OAG), Covertly Aggressive (CAG), and Non-aggressive (NAG)
- Details: https://aclanthology.org/W18-4407.pdf

#### - BERT (Bidirectional Encoder Representations from Transformers)
- Pre-training of Deep Bidirectional Transformers for Language Understanding
- Stack of Transformer encoder layers
- Train: MLM, NSP methods
- Details: https://arxiv.org/abs/1810.04805

Contents
=============

#### - [Aggression identification using BERT](https://github.com/qbxlvnf11/aggression-identification-in-text/blob/main/Aggression_identification_using_BERT.ipynb)
- Input: english text
- BERT-based aggression identification model
- Validation throught confusion matrix
- Docker env run command

```
docker run --gpus all -it --rm -p 8886:8886 -e GRANT_SUDO=yes --user root -v {source code path}:/workspace -w /workspace pytorch/pytorch bash -c "pip install jupyter && pip install pandas && pip install seaborn && pip install sklearn && apt-get update && apt-get install -y python3-opencv && pip install torchmetrics && pip install pytorch_pretrained_bert && pip install tensorflow && pip install opencv-python && pip install torch_snippets torch_summary && jupyter notebook --ip='0.0.0.0' --port=8886 --allow-root"
```

Dataset
=============

#### Aggression identification dataset

- Aggression-annotated dataset for the Shared Task on Aggression Identification during First Workshop on Trolling, Aggression and Cyberbullying (TRAC - 1) at COLING - 2018

https://github.com/kmi-linguistics/trac-1

References
=============


#### - Details of TRAC-1 Shared Task on Aggression Identification
```
@article{
  title={TRAC-1 Shared Task on Aggression Identification: IIT(ISM)@COLING’18},
  author={Ritesh Kumar et al}
}
```

#### - BERT Paper
```
@article{BERT,
  title={BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding},
  author={Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova},
  journal = {arXiv},
  year={2018}
}
```

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com
