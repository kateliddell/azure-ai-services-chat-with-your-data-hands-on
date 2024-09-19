# azure-ai-services-chat-with-your-data-hands-on

## Day 3
https://learn.microsoft.com/en-us/azure/search/search-query-overview#geospatial-search

Step 1: set up AML
Step 2: CLone git repo into AML
Step 3 set up resources

## Day 4
[How to work with the Chat Markup Language (preview) - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/chat-markup-language)

If you use vscode or jupyter notebooks to run AML notebooks remotely it struggles to find local files. You can add this code to the start of all notebooks to fix this. (There may be better long term solutions to this)
replace file_dir with your path
 
import os
 
#Get the directory of the currently running file

file_dir = "/home/azureuser/cloudfiles/code/Users/hannahhowell/azure-ai-services-chat-with-your-data-hands-on/Day3/Hands-on/"

#Get the current working directory

current_cwd = os.getcwd()
 
#Check if the current working directory is the same as the file directory

if current_cwd != file_dir:
    # Change the current working directory to the file directory
    os.chdir(file_dir)
    print(f"Changed current working directory to: {file_dir}")
else:
    print("Already in the correct directory.")
has context menu


https://learn.microsoft.com/en-us/azure/search/index-add-suggesters

