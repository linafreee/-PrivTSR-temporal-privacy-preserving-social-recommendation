# -PrivTSR-temporal-privacy-preserving-social-recommendation
### Basic Information:
The source code and datasets are released for the paper "A Novel Temporal Privacy-Preserving Model for Social Recommendation".


### Usage:
1. Environment: I have tested this code with python3.6
2. Run PrivTSR: cd the sub-directory Code and create the corresponding folders first. Run the DP_data class and to_array (modify the parameter e). Run metapath_generation.py (modify the parameter e). Copy DP_trust/DP_user_friends.txt to the timestamp_metapath folder and replace all commas with spaces. Run embedding_generation.py (modify the parameter dim, etc.). Run the merge_embedding class (modify dim). Run model.py (modify dim).
3. Note: The timestamp_embedding is related to the dim of all_time_merge.

### Citation:
1.The algorithm PrivTSR is from the paper:
```bibtex
@ARTICLE{PrivTSR,
  author={Gao, Lina and Yu, Jiguo and Zhao, Jianli and Hu, Chunqiang},
  journal={IEEE Transactions on Computational Social Systems}, 
  title={A Novel Temporal Privacy-Preserving Model for Social Recommendation}, 
  year={2024},
  volume={11},
  number={5},
  pages={5658-5670},
  doi={10.1109/TCSS.2024.3378349}
}

```

2.The datasets we use are from the paper:
```bibtex
@INPROCEEDINGS{CiaoDVD,
  author={Guo, Guibing and Zhang, Jie and Thalmann, Daniel and Yorke-Smith, Neil},
  booktitle={2014 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM 2014)}, 
  title={ETAF: An extended trust antecedents framework for trust prediction}, 
  year={2014},
  volume={},
  number={},
  pages={540-547},
  doi={10.1109/ASONAM.2014.6921639}
}

```bibtex
@inproceedings{Lastfm,
title = "Second Workshop on Information Heterogeneity and Fusion in Recommender Systems (HetRec2011)",
keywords = "information heterogeneity, information integration, recommender systems",
author = "Iv{\'a}n Cantador and Peter Brusilovsky and Tsvi Kuflik",
year = "2011",
month = oct,
day = "23",
doi = "10.1145/2043932.2044016",
publisher = "Association for Computing Machinery",
pages = "387--388",
booktitle = "RecSys'11 - Proceedings of the 5th ACM Conference on Recommender Systems"
}

```

### Author contact:
Email: linafreee@163.com
