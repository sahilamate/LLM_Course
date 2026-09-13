Step 1: Install the google-genai package 
Step 2: Import the package 
Step 3: Create google api key with the help of google ai studio 
Step 4: Set the google api key into google collab secrets and give it the "GEMINI_API_KEY"
Step 5: Get the secret api key by importing the required module from google collab
Step 6: Call gemini module and use the Client class to set the api key and store the instance into client variable 
Step 7: Create the study_assistant function which takes the user's prompt as an input and with the help of client instance all the models.generate_content() method and provide the attributes such as model and user's prompt as the conntents. Finally return the generated response.
Step 8: Create the user_question varible to store the user's prompt and pass this varible to the study_assistant function and store the returned response in the output varibale and print the LLM response.

