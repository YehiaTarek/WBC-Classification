# WBC-Classification
A prototype python Model that works on the classification of white blood cells in an image 
the original photo comes in as below grainy and out of color


![1](https://user-images.githubusercontent.com/82836901/133134980-5b8eb2be-b6c5-4446-982e-1e5f1e61fefd.jpg)


 The program first adds enhancements to the photo and removes the noise and grain
 
 
 ![66](https://user-images.githubusercontent.com/82836901/133135580-1b840043-457b-4c0a-b148-6cacffaa0f39.PNG)

After enhancements the program becomes capble of identifing the cell through masking

![77](https://user-images.githubusercontent.com/82836901/133135685-a0aa3331-1b4a-4944-8538-9de83cfc01d9.PNG)
![88](https://user-images.githubusercontent.com/82836901/133135701-648e9a0b-03fa-49fe-8931-0ae270ba514d.PNG)
![99](https://user-images.githubusercontent.com/82836901/133135716-60d2e635-c818-489b-8e92-a22458fc3e8c.PNG)

After identifing the cell the program tries to enhance the detected spot through threshholding

![100](https://user-images.githubusercontent.com/82836901/133135807-e6a4aa47-8451-40ce-9386-1ac922b0ad9c.PNG)

Finally the program compares the final output with the output that should have been Through IoU measure
![101](https://user-images.githubusercontent.com/82836901/133135950-44c69368-1ff1-4c56-aa29-038d94956c12.PNG)

