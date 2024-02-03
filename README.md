# gomera-project
The architecture and preprocessing functions for an E2E Automatic Whistled Speech Recognition (AWSR) system for the whistled language Silbo Gomero / the Gomeran Whistle.

The Gomeran Whistle, more commonly referred to as El Silbo Gomero (or just "Silbo Gomero") is a whistled language used by the inhabitants of the island of La Gomera off the coast of Spain.
Silbo Gomero is a whistled register of Spanish, meaning each Spanish phoneme has a whistled version, though it's been found that some whistles are used to represent several Spanish phonemes, the specific one 
represented being based on the context.

This project establishes the first ever attempt at creating an E2E deep learning model for speech-to-text on a whistled language.

The dataset used is from https://www.openslr.org/137/, which was initially created for an HMM-GMM model attempting to perform speech-to-text for the same language.

The model was modelled off of the shared encoder and LAS decoder from the paper Two-Pass End-to-End Speech Recognition by Sainath et al. [2019].






Citations / References:
@inproceedings{jakubiak23_interspeech,
  author={Agata Jakubiak},
  title={{Whistle-to-text: Automatic recognition of the Silbo Gomero whistled language}},
  year=2023,
  booktitle={Proc. INTERSPEECH 2023},
  pages={3402--3406},
  doi={10.21437/Interspeech.2023-989}
}

@misc{sainath2019twopass,
      title={Two-Pass End-to-End Speech Recognition}, 
      author={Tara N. Sainath and Ruoming Pang and David Rybach and Yanzhang He and Rohit Prabhavalkar and Wei Li and Mirkó Visontai and Qiao Liang and Trevor Strohman and Yonghui Wu and Ian McGraw and Chung-Cheng Chiu},
      year={2019},
      eprint={1908.10992},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
