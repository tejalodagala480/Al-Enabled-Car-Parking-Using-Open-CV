In this section, we will be building a web application that is integrated to the model we built. A UI is provided for the uses where he has to enter the values for predictions. The enter values are given to the saved model and prediction is showcased on the UI.

This section has the following tasks

  Building HTML Pages 
  Building python code

  Building Html Pages
For this project, we have created 2 HTML files and saved them in the templates folder. Let’s see what those HTML pages looks like:


Build Python Code
Import the libraries
![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/ceff9d12-4803-4a0e-8799-1045b871979f)

Importing the Flask module into the project is mandatory. An object of the Flask class is our WSGI application. The Flask constructor takes the name of the current module (__name__) as an argument.

    ![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/c4ed6582-65a9-4e1d-86b5-dbd6fc0e8a6e)
 
Render HTML page:
![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/8979311a-dd3c-43d2-8919-9d9405115133)

Here we will be using the declared constructor to route to the HTML page that we created earlier. In the above example, the ‘/’ URL is bound with the index.html function. Hence, when the home page of the web server is opened in the browser, the HTML page will be rendered. 


Create a decorator to route to ‘/predict_live’. Go to milestone 3 and copy the entire code and paste it inside the function liv_pred. 
![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/ac1a9f5f-23e7-4c63-ae73-acdb214c2e33)

![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/afeac640-0f46-468d-9502-360362434e70)

![image](https://github.com/tejalodagala480/Al-Enabled-Car-Parking-Using-Open-CV/assets/106898126/5880b6ca-8214-4439-a436-bee5d40def7e)





