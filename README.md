# RHEED-K-Means
A repository for performing principal component analysis (PCA) and k-means clustering the frames of RHEED videos or sequential RHEED images, as described in the paper "Machine learning analysis of perovskite oxides grown by molecular beam epitaxy", Sydney R. Provence, Suresh Thapa, Rajendra Paudel, Tristan K. Truttmann, Abhinav Prakash, Bharat Jalan, and Ryan B. Comes, Phys. Rev. Materials 4, 083807 – Published 21 August 2020. 

Please note that the full analysis can be performed by running the main.m script in the repo, although individual stages of analysis can be performed through running the individual functions. SVD can be rather slow, so it is recommended to limit the crop size to as small as possible, and eliminate any unnecessary frames in the video that are not useful to analysis. 
