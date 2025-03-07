# Quantum Margulis Codes  

This repository provides the parity-check matrices for the quantum Margulis codes introduced in:  

- M. Pacenti and B. Vasić, **"Quantum Margulis Codes,"** *60th Annual Allerton Conference on Communication, Control, and Computing*, Sep. 2024.  
- M. Pacenti, D. Chytas, and B. Vasić, **"Construction and Decoding of Quantum Margulis Codes,"** [arXiv:2503.03936](https://arxiv.org/abs/2503.03936).  

## Format  
The parity-check matrices are stored in a sparse format: each row lists the positions of its nonzero entries, with indices starting from 0.  

- In *Quantum Margulis Codes*, the codes are named as in the paper.  
- In *Construction and Decoding of Quantum Margulis Codes*, codes are labeled as `"n_k_x/z"`, where:  
  - **n** is the blocklength  
  - **k** is the code dimension  
  - **x/z** indicates whether the matrix corresponds to the X or Z stabilizers.  

## Citation  
If you use these codes in your research, please cite the relevant work:  

@misc{pacenti2025constructiondecodingquantummargulis,
      title={Construction and Decoding of Quantum Margulis Codes}, 
      author={Michele Pacenti and Dimitris Chytas and Bane Vasic},
      year={2025},
      eprint={2503.03936},
      archivePrefix={arXiv},
      primaryClass={quant-ph},
      url={https://arxiv.org/abs/2503.03936}, 
}



