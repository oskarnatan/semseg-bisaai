# GPU-accelerated Semantic Image Segmentation with PyTorch

## Implementasi program untuk [webinar BISA AI](https://tampil.id/event/detail/VFdwWk1FNUJQVDA9):
<img src="docs/event.jpg" width="400">


## Step:
1. Download dan extract set dataset [cityscapes](https://www.cityscapes-dataset.com/) 
    - leftImg8bit_trainvaltest.zip (11GB)
    - gtFine_trainvaltest.zip (241MB)
2. Run jupyter notebook dan buka semseg.ipynb
3. Jalankan program sesuai instruksi yang tertulis di notebook
4. Trained model untuk inference dapat didownload [di sini](https://drive.google.com/drive/folders/15oUOVwLhZWFzAhYSWukMzPMeGERx8zWk?usp=sharing)


## Other:
1. Deep learning juga dapat digunakan untuk memproses multiple input dan output.
    - O. Natan and J. Miura, "Semantic Segmentation and Depth Estimation with RGB and DVS Sensor Fusion for Multi-view Driving Perception," in Proc. Asian Conf. Pattern Recognition (ACPR), Jeju Island, South Korea, Nov. 2021, pp. 352–365. [[paper]](https://doi.org/10.1007/978-3-031-02375-0_26) [[code]](https://github.com/oskarnatan/RGBDVS-fusion)
2.  Proses learning untuk multiple task dapat diseimbangkan dengan algoritma tertentu.
    - O. Natan and J. Miura, “Towards Compact Autonomous Driving Perception with Balanced Learning and Multi-sensor Fusion,” IEEE Trans. Intelligent Transportation Systems, 2022. [[paper]](https://doi.org/10.1109/TITS.2022.3149370) [[code]](https://github.com/oskarnatan/compact-perception)
3. Setelah tahapan perception, planning dan control juga dapat dilakukan secara simultan.
    - O. Natan and J. Miura, “End-to-end Autonomous Driving with Semantic Depth Cloud Mapping and Multi-agent,” IEEE Trans. Intelligent Vehicles, 2022. [[paper]](https://doi.org/10.1109/TIV.2022.3185303) [[code]](https://github.com/oskarnatan/end-to-end-driving)
    - O. Natan and J. Miura, “DeepIPC: Deeply Integrated Perception and Control for Mobile Robot in Real Environments,” arXiv:2207.09934, 2022. [[preprint]](https://arxiv.org/abs/2207.09934) [[video]](https://www.youtube.com/watch?v=h8lMCzJsbi8)