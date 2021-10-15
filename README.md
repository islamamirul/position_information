#    How much Position Information Do Convolutional Neural Networks Encode?, ICLR 2020

**[ How much Position Information Do Convolutional Neural Networks Encode?](https://openreview.net/pdf?id=rJeB36NKvB)**
<br>
**[Md Amirul Islam*](https://www.cs.ryerson.ca/~amirul/)**, **[Sen Jia*](https://scholar.google.com/citations?user=WOsy1foAAAAJ&hl=en)**, **[Neil Bruce](http://socs.uoguelph.ca/~brucen/)** 

<br>



#  Decoding Absolute Position Information
 
   We train the whole system on the DUT-S dataset and validate on the PASCAL-S dataset, they both are originally used for salient object detection. The position information we explored is content-agnostic, so any natural images can be used. You might want to avoid the ImageNet dataset, because the backbone(vgg) is commonly pre-trained on the data. Please run the following commands to train and evaluate the network.

            cd position_attack/
            python train_network.py folder $abs_train_folder $abs_test_filder


# BibTeX
If you find this repository useful, please consider giving a star :star: and citation :t-rex:


      @InProceedings{islam2020position,
       title={How much Position Information Do Convolutional Neural Networks Encode?},
       author={Islam, Md Amirul and Jia, Sen and Bruce, Neil},
       booktitle={International Conference on Learning Representations},
       year={2020}
     }

