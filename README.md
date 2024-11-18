# CMSeg-Net
The source code of our copy-move detector will be released soon. 

Contact: <br>
shao.haochiang (at) gmail.com  (H.-C. Shao) <br>
box321eu2324 (at) gmail.com    (F.-Y. Lin)


# FakeParaEgg
We created this microscopic image dataset to support the development of future copy-move forgery detection algorithms. 

This dataset was made from the public source data provided by the ICIP 2022 Challenge: Parasitic Egg Detection and Classification in Microscopic Images (https://icip2022challenge.piclab.ai/).


======== <br>
For FakeParaEgg users, please cite the following papers: <br>
@article{shao2024copymove,<br>
  title={Copy-move detection in optical microscopy: a
segmentation network and a dataset},<br>
  author={Shao, H.-C. and Liao, Y.-R. and Tseng, T.-Y. and Chuo, Y.-L. and Lin, F.-Y.},<br>
  journal={(submitted manuscript)},<br>
  volume={xx},<br>
  pages={pp--pp},<br>
  year={202X},<br>
}<br>



The source data of FakeParaEgg was provided by:<br>
@inproceedings{anantrasirichai2022icip,<br>
  title={ICIP 2022 Challenge on Parasitic Egg Detection and Classification in Microscopic Images: Dataset, Methods and Results},<br>
  author={Anantrasirichai, N. and Chalidabhongse, T. and Palasuwan, D. and Naruenatthanaset, K. and Kobchaisawat, T. and Nunthanasup, N. and Boonpeng, K. and Ma, X. and Achim, A.},<br>
  booktitle={Proc. IEEE Int. Conf. Image Process.},<br>
  pages={4306--4310},<br>
  year={2022},<br>
}<br>


======== <br>
# CMF (with copy-move segmentation mask)
The original CMF dataset was designed for testing keypoint-based copy-move detection algorithms and, therefore, does not provide segmentation ground truths (i.e., copy-move masks) for its attacked forgery samples. We carefully semi-manually segmented the copy-move samples in the CMF dataset. If you downloaded this modified CMF dataset, please cite our paper please.
The modified CMF dataset can be downloaded at: 
https://www.dropbox.com/scl/fo/0klw6e7zuzgz9l2y8tpif/AOdDzAcsIXPftg8AhPrf2_w?rlkey=jn8zzmdff7cwa0xjlzx9xoob8&st=nz3cw1qi&dl=0 

@article{shao2024copymove,<br>
  title={Copy-move detection in optical microscopy: a
segmentation network and a dataset},<br>
  author={Shao, H.-C. and Liao, Y.-R. and Tseng, T.-Y. and Chuo, Y.-L. and Lin, F.-Y.},<br>
  journal={(submitted manuscript)},<br>
  volume={xx},<br>
  pages={pp--pp},<br>
  year={202X},<br>
}<br>
