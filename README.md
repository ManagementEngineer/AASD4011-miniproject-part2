# AASD4011-miniproject-part2
Streamlit App for AASD4011 

Group Members:

Shreeya Shah
Aanandita Chavan
Ramuel John Batuigas
Yiu, Wing Han


Here are the Screenshots, of our Streamlit App


![image](https://github.com/ManagementEngineer/AASD4011-miniproject-part2/assets/97623578/5c25b80b-4f2d-47e0-b977-808aeea70154)




![image](https://github.com/ManagementEngineer/AASD4011-miniproject-part2/assets/97623578/2649b68e-9013-410f-a07f-719f982eb333)



The Changes we have made in the code is:

We have add the Error handling, The try block attempts to load the pre-trained ResNet-18 model using the torch.hub.load() function. 
In the except block, st.error() is called with the exception e as an argument. This displays an error message to the user using Streamlit's error display mechanism.
