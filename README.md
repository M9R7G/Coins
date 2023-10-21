# Coins

The goal of the project is to design a convolutional network that classify
coin images into two classes:

1) Coins from the Roman times. 
2) Other coins.

Two different datasets will be used: The coinsdataset available from
https://github.com/despoisj/CoinsDataset/blob/master/README.md
and the Coin Image Dataset containing which is available from
https://cvl.tuwien.ac.at/research/cvl-databases/coin-image-dataset/.
The joint coin dataset will be very unbalanced.

Steps followed for the implementation: 

1) Create a single dataset with the images of  scaled to the same size. 
2) Preprocess the images. 
3) Design the network architecture and train it. 
4) Validate the network.