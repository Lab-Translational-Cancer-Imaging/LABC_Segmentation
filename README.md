# LABC_Segmentation
This repository contains the trained network weights for the paper *"Deep learning-based segmentation of locally advanced breast cancer on MRI in relation to residual cancer burden: a multi-institutional cohort study"*.

## Usage
Clone the git repository in your nnU-Net results folder. The Task ID used is 789. You can then use the weights like any other nnU-Net. For more information on how to use nnU-Net, see https://github.com/MIC-DKFZ/nnUNet

The network assumes six channels: one pre-contrast channel and five post-contrast channel (spaced at 60 to 90 seconds). In case you have less than five post-contrast channels, copying the last channel forward seems to work. In principle, only fat-supressed MRI is supported and in the training set, but you may have some luck with non-fat suppressed MRI, too.

For more details regarding applicabilty of these network weights, we refer to our paper for more information regarding the training and testing sets. Feel free to reach out if there's any questions.

## Citation
If you use these network weights for your own research, please cite our publication!

M.H.A. Janse, L.M. Janssen, B.H.M. van der Velden, M.R. Moman, E.J.M. Wolters-van der Ben, M.C.J.M. Kock, M.A. Viergever, P.J. van Diest, K.G.A. Gilhuijs, "Deep learning-based segmentation of locally advanced breast cancer on MRI in relation to residual cancer burden: a multi-institutional cohort study", *Journal of Magnetic Resonance Imaging*, In Press, 2023. DOI: [10.1002/jmri.28679](https://dx.doi.org/10.1002/jmri.28679)
