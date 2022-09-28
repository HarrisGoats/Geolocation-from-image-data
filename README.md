# Geolocation-from-image-data

This project is a work in progress, the network is mostly put together, current issue is handing giving the network image data without downloading over 150gb worth of uncompressed images onto my computer. 

Next steps:
* Have Pytorch read data without unzipping it
* Test different ammount and sizes of layers to get optimal training results
* Randomize labels and retrain network. Goal is to compare the loss over time graphs with the original network and make sure network is finding patterns and not just overfitting data
* Currently labels are just one per city, next step is to view each city as a grid of nxn mile squares, and relable data where each image is labeled by a more exact location than just the city
