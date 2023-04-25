# Glasgow-coma-scale
Python code using GUI interface to calculate the Glasgow coma scale and to know the severity of head injury
Being a widely utilized assessment tool, glasgow coma scale(GCS) objectively quantifies the extent of impaired consciousness in all types of acute medical and trauma patients. The scale evaluates patients based on their eye opening, verbal and motor responses. It is a widely recognised and utilized tool in both clinical and research environments. Providing a structured and standardized GCS using interface can ensure reliability and consistency in evaluating the score. GUI interface creates an intuitive, user friendly interface which helps in managing and communicating with a global network of devices and systems by using concise and understandable view. Furthermore, users can easily interact with the network using sliders, buttons, and other graphical elements making it efficient and intuitive. This interface improves the communication, performance and  collaboration across the global network.

Currently, the GCS scores are inserted and calculated manually using pen and paper which is time consuming and error-prone. Additionally, it can pose a challenge to healthcare professionals who are new to the GCS scoring system which can reportedly lead to misinterpretation and mismanagement. These issues should be minimized as it is the critical tool in evaluating the treatment for patients by interpreting the results. Hence it's necessary to create an automated GCS calculator that can lessen the errors and save time. 

Python and Tkinter libraries are used to develop the GUI interface in this project to design a GCS calculator. Labels and radio buttons for eye, verbal and motor responses along with the "Calculate GCS" button are incorporated. Clicking on the button after inputting the response values will allow the program to retrieve the input values thus applying them to the formula in the code to evaluate the GCS score. In a display box the GCS score gets displayed by applying the Tkinter module to the message box. For ensuring the accuracy and flexibility of the calculator, using different input values the program will be subjected to multiple test cases. Finally, pyinstaller will be utilized to contain a self executable file that can be conveniently used by healthcare professionals whenever available.
