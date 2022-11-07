---

The MUG dataset used in paper [MUG: Interactive Multimodal Grounding on User Interfaces](https://arxiv.org/abs/2209.15099)
```
@inproceedings{li2022mug,
      author    = {Li, Tao and Li, Gang and Zheng, Jingjie and Wang, Purple and Li, Yang},
      title     = {MUG: Interactive Multimodal Grounding on User Interfaces},
      booktitle = {arXiv},
      year      = {2022}
  }
```
---

# Data structures
* mug_v1.[SPLIT].csv: contain RICO screen id, target object id, and up to 5 pairs of pairs of user instruction and object id clicked by agent.
* mug_objects_v1.[SPLIT].json: contain object ids we filtered from RICO. Criteria include visibility, clickability, and leaf.

# Additional Resources
* Original view hierarchy is presented in the [RICO dataset](https://interactionmining.org/rico)
* Auxiliary object labels are presented in the [CLAY dataset](https://github.com/google-research-datasets/clay)

---

For more information, please [contact us](tlinlp@google.com)
