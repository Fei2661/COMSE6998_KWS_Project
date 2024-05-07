This folder cotains the model builded in this project.
### Attention-RNN model
For the AttentionRNN model, the pre-trained model reqired a specific version(2.10.1) for tensorflow.
I feel like TensorFlow versions are incompatible with CUDA in colab. I did not find the way solve for it.
In this case, I run the model with cpu in colab, it works.

The pre-trained Attention-RNN model is from
@ARTICLE{2018arXiv180808929C,
   author = {{Coimbra de Andrade}, D. and {Leo}, S. and {Loesener Da Silva Viana}, M. and 
	{Bernkopf}, C.},
    title = "{A neural attention model for speech command recognition}",
  journal = {ArXiv e-prints},
archivePrefix = "arXiv",
   eprint = {1808.08929},
 keywords = {Electrical Engineering and Systems Science - Audio and Speech Processing, Computer Science - Sound},
     year = 2018,
    month = aug,
   adsurl = {http://adsabs.harvard.edu/abs/2018arXiv180808929C},
  adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}

### CNN
The pre-trained CNN model is from
@misc{rai2023keyword,
      title={Keyword spotting -- Detecting commands in speech using deep learning}, 
      author={Sumedha Rai and Tong Li and Bella Lyu},
      year={2023},
      eprint={2312.05640},
      archivePrefix={arXiv},
      primaryClass={cs.SD}
}
