# insightsXRDCNN
Electronic resources for the paper named "Insights from the reciprocal space revealed by a convolutional neural network and transfer learning".
This paper is published now in Scripta Materialia (DOI: https://doi.org/10.1016/j.scriptamat.2025.116697)

The dataset is available in the following link: https://bit.ly/4iivld8 . There, you will find the files xset_macro.npy, xset_0250.npy, xset_0100.npy, and xset_0050.npy. These files correspond to the diffraction patterns modeled under different conditions of crystal sizes (data augmentation). The CIF number of the patterns in the files xset_{size}.npy are in their corresponding dfset_{size}.csv file. There are also two supporting files, dftraval.csv and dftest.csv, which contain the CIF list used for the training and test sets, respectively.

The output data corresponds to the file latpar.npy. You will also require an additional input tensor to train the base model, which is the file binformula.npy. Additionally, the base model informed in the publication is available in that link (baseModel.h5). 

In the directory "baseModel" of this repository you will find the jupyter-notebook that shows the performance of the base model.


For more details, you can consult the publication.
