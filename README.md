# AID-UCM-DegradingWeather
Gradually degrading weather conditions synthesized on publicly available AID and UCM datasets

We synthesize gradually degrading weather conditions (cloud cover and snowfall) on two aerial image datasets AID [1] and UCM [2] for evaluate continual domain adaptation models. A breif description of the synthesized datasets, and three benchmarks on these datasets can be found in our paper titled "Continual Domain Adaptation on Aerial Images under Gradually Degrading Weather", authored by Chowdhury Sadman Jahan and Dr. Andreas Savakis. The google drive link to the dataset is as follows.



The 4 benchmarking datasets are named AID-CC, AID-SF, UCM-CC, and UCM-SF (CC for cloud cover, SF for snowfall). The source domains are the original unaltered AID and UCM datasets. In the drive, the cloud cover degradation type ranges from 1 to 7, with 7 being the target domain and 1-6 being the gradually degrading intermediate domains in the ascending order. Similarly, for snowfall degradation, 5 has the highest degradation and is the target domain, while 1-4 are the gradually worsening degradations. The images are synthesized using the Python library imgaug.augmenters.weather. If you use this dataset, or any part of our work, please cite our paper. 


[1] G.-S. Xia, J. Hu, F. Hu, et al., “Aid: A benchmark data set for performance evaluation of aerial scene classification,” IEEE Transactions on Geoscience and Remote Sensing 55(7), 3965–3981 (2017)
[2] Y. Yang and S. Newsam, “Bag-of-visual-words and spatial extensions for land-use classification,” in Proceedings of the 18th SIGSPATIAL international conference on advances in geographic information systems, 270–279 (2010)
