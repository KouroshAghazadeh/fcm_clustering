Fcm clustering on Hyperspectral Images(HSI)

spectral imaging is the parallel acquisition of spatial and their corresponding spectral information in an image space and their combination thereof. It is kind of similar to an RGB colour image, but it has a lot more channels and thereby poses a challenge to be visualized as a whole.
So, the image acquired from any HSI camera will be in the form of a hypercube, having n-dimensional image data which can be overwhelming at times. Thus, it is not uncommon to apply dimensional-reduction techniques to the same and have many other approaches to process the hypercube. Here, if we try to focus on a single hyper-pixel, we would be able to plot a continuous spectrum data for the same.

this project inspired from Xiaojun Yang , Mingjun Zhu, Bo Sun , Member, IEEE, Zheng Wang , and Feiping Nie , Senior Member, IEEE ' s paper.
paper's link: https://ieeexplore.ieee.org/document/10068280

right now, i'm focusing on FCMM clutering on HSI Images. . It is wellknown that many pixel points in HSI are distributed
anomalously. The proposed algorithm can directly cluster HSI data points represented by multiple subclusters, and this reduces the impact of anomalies on the
algorithm.
