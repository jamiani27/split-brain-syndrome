% Author: Jack Damiani
$ Project Started 4/20/22


Goal of the project:
Model Split Brain Syndrome

Description:
Split brain syndrome is the condition where a patient has a lesion of the corpus callosum. 
The condition was initially noticed from lesions to limit epileptic seizures, but it can be from other causes or purposes. 
Split brain syndrome creates a disconnect between the left and the right brain. 
The corpus callosum allows the two hemispheres to communicate. 
Many conditions have been observed, but in this case, visual and language disconnect will be modeled. 


Patients with lesion of the corpus callosum have been observed to not be able to verbally say what is viewed in the left visual field. 
This is because the language center of the brain is on the left side, and the visual field cortical representation is contralateral.
This means the right visual field is represented in the left cortex, where language is represented.
Likewise, the left visual field is represented in the right cortex, without verbal language representation. 
Patients with split brain syndrome will be able to verbally announce what is in the right visual field but will be silent or not know if an object is only in the left visual field.
They will, however, be able to draw what is in the left visual field with their left hand. 
Then, they would be able to say what that object is (if viewed with their right eye), but there is a disconnect on why they just drew that object. 
Patients will make up a reason for drawing that object.


In this project, only the verbal part of the project will be represented. 
There will be two input layers, represented as the left and right visual fields, represented by a 2D grid, split down the middle.
Objects will be presented.
After training occurs, only one side of the object will be shown for the test. 
In a normal patient, enough activation from the left or right side will be enough to activate the language output layer, only on the left cortical side. 
In a complete lesion, the right visual field will be able to achieve the correct output, but the left will not. 
Then, incomplete lesions will be analyzed to see the level of connectiveness needed to provide the correct verbal output from the left visual field.


The project will consist of two input layers, two hidden layers, and one output layer.
The input layers will be 10x5 each (making a 10x10 image).
Hidden layers will be ??????, found by experimentation for ideal problem solving.
Output layers will be 1xI, where I is the number of images.


Citations:
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7305066/


