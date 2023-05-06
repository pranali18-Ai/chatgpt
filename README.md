# chatgpt

Step 1: Create an account on OpenAI and log into an account.

Step 2: After login click on ‘Personal‘ on the top-right side and then click on ‘View API keys‘ as seen in the below image.
Step 1: Create an account on OpenAI and log into an account.

Step 2: After login click on ‘Personal‘ on the top-right side and then click on ‘View API keys‘ as seen in the below image.
Step 4: Now, open any code editor or online notebooks such as Google Colab or Jupyter Notebook. Here, we are using Google Colab notebook and installing the Open Ai library in Python using the below command.
If you are using any other code editor you can install the openai library in Python by executing the below command in the terminal or command prompt.
Step 5: Import openai library and Store the key in a variable that we have generated in Step 3 as given below.
Step 6: Set a context for the ChatGPT API that is used to tell the API what is it supposed to do using the JSON file. In this, we have defined the role as a system because we are creating this for users and this ChatGPT is a system and also defined the content.
Step 7: Here is the rest of the code where 

We are using an infinite while loop so that we can chat with the ChatGPT API repeatedly without executing the code again and again. 
In the second line we a taking input from the user and store it in a variable ‘message’.
If a user inputs any question then only we enter the if condition and make a JSON of file and append it to the JSON file that we have created in step 6 after that generate the chat using openai.ChatCompletion.create()
Store the answer in the variable ‘reply’ and print that reply using the print() function.
Output: After running the above code we have to input any query as in the below output query is ‘What is geeks for geeks’,’ Which is best DSA course on gfg ‘ and we are getting the output from ChatGPT and as the while loop is infinite it again asks input from the user.
ChatGPT Output:

We can also check the output from OpenAI (Chatgpt) it will same as our Python code output.
