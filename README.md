# CMSeg-Net
**"Copy-move detection in optical microscopy: a segmentation network and a dataset", IEEE Signal Processing Letters, 2025.**

The source code for our copy-move detector, named **CMSeg-Net**, will be released soon.

In the meantime, you can access an **unfinalized** version of the code, which includes testing scripts and some unpolished comments, via the following Dropbox link:  
🔗 [FongYi_code.zip (Dropbox)](https://www.dropbox.com/scl/fi/d70p1q7sh2qd0o983cbs5/FongYi_code.zip?rlkey=i3jdpdbhx40d69lwy3m06ov05&st=jn850ccp&dl=0)  <br>
🔗 [prediction_folder_FongYi (Dropbox, model file)](https://www.dropbox.com/scl/fi/aym6cdp84mqa6iehzf80h/prediction_folder_FongYi.zip?rlkey=74vzkqo2up7gg2wakemkropls&st=9gq730vy&dl=0)

Please stay tuned for the finalized version and the updated, renamed experimental dataset.


Contact: <br>
shao.haochiang (at) gmail.com  (H.-C. Shao) <br>
box321eu2324 (at) gmail.com    (F.-Y. Lin)

**For CMSeg-Net users, please cite the following papers:** <br>
@article{shao2024copymove,<br>
  title={Copy-move detection in optical microscopy: a
segmentation network and a dataset},<br>
  author={Shao, H.-C. and Liao, Y.-R. and Tseng, T.-Y. and Chuo, Y.-L. and Lin, F.-Y.},<br>
  journal={IEEE Signal Processing Letters},<br>
  volume={32},<br>
  pages={1106--1110},<br>
  year={2025},<br>
}<br>


# FakeParaEgg
We created this microscopic image dataset to support the development of future copy-move forgery detection algorithms. 

**FakeParaEgg** simulates real-world copy-move processes, where forgeries often involve foreground objects with their backgrounds removed (i.e., made transparent). These manipulations, common in academic fraud, are difficult to detect using traditional methods due to the nonidentical background context. **FakeParaEgg** contains 1,400 forged images for training and 100 for testing. To create it, we cropped parasitic eggs using ground-truth bounding boxes, removed the backgrounds using **Rembg**, and randomly pasted the background-free patches onto the original image, producing the final synthetic copy-move forgeries, as illustrated in the figure below.
![alt text](https://github.com/YoursEver/FakeParaEgg/blob/main/fakeparaegg_preparation.png?raw=true)

Finally, note that the FakeParaEgg dataset was made from the public source data provided by the ICIP 2022 Challenge: Parasitic Egg Detection and Classification in Microscopic Images (https://icip2022challenge.piclab.ai/).


======== <br>
**For FakeParaEgg users, please cite the following papers:** <br>
@article{shao2024copymove,<br>
  title={Copy-move detection in optical microscopy: a
segmentation network and a dataset},<br>
  author={Shao, H.-C. and Liao, Y.-R. and Tseng, T.-Y. and Chuo, Y.-L. and Lin, F.-Y.},<br>
  journal={IEEE Signal Processing Letters},<br>
  volume={32},<br>
  pages={1106--1110},<br>
  year={2025},<br>
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
**The modified CMF dataset can be downloaded at:**
https://www.dropbox.com/scl/fo/0klw6e7zuzgz9l2y8tpif/AOdDzAcsIXPftg8AhPrf2_w?rlkey=jn8zzmdff7cwa0xjlzx9xoob8&st=nz3cw1qi&dl=0 

@article{shao2024copymove,<br>
  title={Copy-move detection in optical microscopy: a
segmentation network and a dataset},<br>
  author={Shao, H.-C. and Liao, Y.-R. and Tseng, T.-Y. and Chuo, Y.-L. and Lin, F.-Y.},<br>
  journal={IEEE Signal Processing Letters},<br>
  volume={32},<br>
  pages={1106--1110},<br>
  year={2025},<br>
}<br>
