# Knowledge Distillation

Alfred test change.  Okay.

PyTorch implementations of algorithms for knowledge distillation.

## Setup

### build

```bash
$ docker build -t kd -f Dockerfile .
```

### run

```bash
$ docker run -v local_data_path:/data -v project_path:/app -p 0.0.0.0:8084:8084 -it kd
```

## Experiments

1. [Task-specific distillation from BERT to BiLSTM](https://github.com/pvgladkov/knowledge-distillation/blob/master/experiments/sst2). Data: SST-2 binary classification.


## Papers

1. Cristian Bucila, Rich Caruana, Alexandru Niculescu-Mizil "**ModelCompression**" (2006) [pdf](https://www.cs.cornell.edu/~caruana/compression.kdd06.pdf).

2. Victor Sanh, Lysandre Debut, Julien Chaumond, Thomas Wolf "**DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter**" (2019) https://arxiv.org/abs/1910.01108.

3. Raphael Tang, Yao Lu, Linqing Liu, Lili Mou, Olga Vechtomova, Jimmy Lin "**Distilling Task-Specific Knowledge from BERT into Simple Neural Networks**" (2019) https://arxiv.org/abs/1903.12136.

4. Zhenzhong Lan, Mingda Chen, Sebastian Goodman, Kevin Gimpel, Piyush Sharma, Radu Soricut "**ALBERT: A Lite BERT for Self-supervised Learning of Language Representations**" (2019) https://arxiv.org/abs/1909.11942.

5. Rafael Müller, Simon Kornblith, Geoffrey Hinton "**Subclass Distillation**" (2020) https://arxiv.org/abs/2002.03936.

6. Iulia Turc, Ming-Wei Chang, Kenton Lee, Kristina Toutanova "**Well-Read Students Learn Better: On the Importance of Pre-training Compact Models**" (2020) https://arxiv.org/abs/1908.08962.