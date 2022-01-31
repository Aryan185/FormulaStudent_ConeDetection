# FormulaStudent_ConeDetection
Formula Student (FS) is Europe's most established educational engineering competition, which usually forms part of a degree-level project and is viewed by the motorsport industry as the standard for engineering graduates to meet, transitioning them from university to the workplace.
Each year, Formula Student sees over 100 university teams from around the globe compete in static and dynamic events that will test their preparation and hard work.

These events include both driver controlled as well as driverless events. Here we will be talking about the latter.
For a DV car to move, it requires the layout of the path for it to navigate. This path is formed by the FS authorities using cones. There are basically four different categories of cones:

![2-Figure2-1](https://user-images.githubusercontent.com/82220795/151790376-9ae24240-9da5-45a0-bd6e-9e55b49bc6b7.png)

# Dataset

Here, the dataset used here consists of three cones; blue cone, yellow cone and small red cone.
The dataset consists of 978 images with each image containing numerous instances of different cones.

    Instances of yellow cones: 2638
    Instances of blue cones: 1300
    Instances of small red cones: 2237

The dataset is annonated manually using the Labelmg tool in .txt format

# Training
 The dataset is trained using the YoloV4 model over 6000 iterations and a custom config file.
 The accuracy reached was at 5500 iteration and came out to be 99.43%
 
 ![Capture](https://user-images.githubusercontent.com/82220795/151791580-1f5cd4b4-c498-40f9-82a2-76e18a629e91.JPG)
