# CML - 实践
* 目标：基于 GitAction ，通过代码提交自动训练模型，通过 CML 自动生成评估报告，并在 PR 阶段展示性能指标
    * CML 为一个工具，用来将生成的训练结果指标同步到 Git PR 阶段，并以 comment 的形式展示
* 承载平台：Amazon Sagemaker
* MLOPs：CML & DVC
* 算法：RandomForest
* 数据集：sklearn.datasets make_classification

## Example Continuous Machine Learning project

This repository contains code and data for a simple classification problem. To get the dataset, please run `python get_data.py`.
