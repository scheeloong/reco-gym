# Reco-Gym

Python code for the RecSys 2018 REVEAL workshop paper entitled 'RecoGym: A Reinforcement Learning Environment for the problem of Product Recommendation in Online Advertising'. A pre-print version of the paper can be found here - https://arxiv.org/abs/1808.00720

RecoGym is a Open-AI gym RL environment for recommendation, which is defined by a model of user traffic patterns on e-commerce and the users response to recommendations on the publisher websites. We hope that reco-gym will be an important step forward for the field of recommendation systems research, that could open up an avenue of collaboration between the recommender systems and reinforcement learning communities and lead to better alignment between offline and online performance metrics.

For getting starting with reco-gym please view the 'Getting Started' Jupyter Notebook which will explain the functionality of the environment and detail the creation of a simple agent. The 'Compare Agent' notebook compares the recommendation performance of a selection of our included agents. The agent we include with reco-gym can be found in the agents directory of this repository. 

## Dependencies and Requirements
The code has been designed to support python 3.6+ only. The project has the following dependences and version requirements:

- python3 - 3.6.5+
- numpy - 1.14.5+
- scipy - 1.1+
- pandas - 0.22+
- gym - 0.10.5+
- torch - 0.4.1+

In this repository we provide a Anaconda environment setup file with all the required python packages and versions all ready configured. You can install it as follows:

```bash
# install conda env
conda install -c conda conda-env

# create environment based on environment.yml
conda-env create environment.yml

# conda support is missing, use pipinstead
pip install gym
```

## Cite

Please cite the associated paper for this work if you use this code:

```
@article{rohde2018recogym,
  title={RecoGym: A Reinforcement Learning Environment for the problem of Product Recommendation in Online Advertising},
  author={Rohde, David and Bonner, Stephen and Dunlop, Travis and Vasile, Flavian and Karatzoglou, Alexandros},
  journal={arXiv preprint arXiv:1808.00720},
  year={2018}
}
```

## License

Copyright CRITEO

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.