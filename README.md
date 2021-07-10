# lung_cancer_metastasis_analysis
Rahul Sharma    <br>
Date:7/8/2021 

Objective: We need to measure how quickly the lung cancer cells can fill the wound which shows us their mobility


Completed:
1. Optimized threshold values at 3.8, cropping dimensions at [500:1200, 300:1200], and window size for entropy calculation at 8
2. Rewrote the code in terms of obkect orientied programming to better increase the functionality of the tool
3. Determined a new method of calculating the wound boundary using the second dervivtive of the entropy graph at each y level and then finding the 2 closest inflection points to the void
4. Packaged all of the data into a csv which tells file name, plate name, well name, num of hours elapsed, the area of the wound in terms of pixels, and the area of the wound in terms of percentage to the cropped area. 

Next Steps:
1. To add automatic thresholding
2. Add automatic guassaian blur by changing the window size 
3. Add automatic cropping
