# Machine Learning Final Project: Can you rely on your model evaluation? Improving model evaluation with synthetic test data

> **Project Collaboration Notes**  
> Most of the code for this project was written collaboratively by both group members in **Google Colab**.  
> GitHub Usernames: **JoeNissen** and **pnagpal1**
> Original and Updated model found in folder original_and_updated_code
>  
> The work was split evenly between both group members. Both collaborators worked together to get the original code running and to implement the hypothesis.  
>  
> **Division of Slides and Report Work:**  
> • *Joe Nissen* created the slides and wrote the report section for the original methods and model.  
> • *Param Nagpal* created the slides and wrote the report section for the hypothesis component.

---

# Start of the original README file from the authors of the paper

[![arXiv](https://img.shields.io/badge/arXiv--b31b1b.svg)](https://arxiv.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/vanderschaarlab/3S-Testing/blob/main/LICENSE)

This repository contains code for the paper "Can you rely on your model evaluation? Improving model evaluation with synthetic test data"

For more details, please read our [NeurIPS 2023 paper](https://arxiv.org)

## Installation
1. Clone the repository
2. Create a new conda environment with Python 3.7. e.g:
```shell
    conda create --name 3s_env python=3.7
```
3. Install requirements in env
```shell
    pip install -r requirements.txt
```
4. Link the venv to the kernel:
```shell
    python -m ipykernel install --user --name=3s_env
 ```

## Use-cases

We highlight different use-cases of 3S-Testing for both subgroup and shift testing in notebooks which can be found in the ``/use_cases`` folder.


## Citing

If you use this code, please cite the associated paper:

```
@inproceedings
{3STesting,
title={Can you rely on your model evaluation? Improving model evaluation with synthetic test data},
author={van Breugel, Boris and Seedat, Nabeel and Imrie, Fergus and van der Schaar, Mihaela},
booktitle={Advances in Neural Information Processing Systems},
year={2023}
}
```
