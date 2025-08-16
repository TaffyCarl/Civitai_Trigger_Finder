# Civitai_Trigger_Finder
Searches your local machine for LoRA's then heads to CivitAI to download the Triggers and Thumbnails - pretty simple really.

Edit these for your specific machine, the folder_path is where your LoRA's are and the output_folder is where the output files (html, txt) will end up.
def main():
    # Specify the folder to scan and output folder (modify these paths as needed)
    folder_path = r"C:\Users\AI\models\loras"
    output_folder = r"C:\Users\AI\lora_triggers"

Version 2 now downloads and saves thumbnails to your local machine and the mp4 error was fixed by downloading the mp4 in full to your local machine, no more keeping
your fingers crossed that the LoRA maker doesn't delete it thereby leaving you with a missing thumbnail. It also creates a seperate text file of LoRA's on your machine that
no longer exist on Civitai so you can hunt the interweb to see if they're elsewhere so you can find the trigger words.

The Windows GUI version is easy to use, just run it, add your LoRA location and your output location and hit run - then sit back and wait. It'll tell you when it's finished,
you will get the same html, text and missing LoRA text files as you do in the python file.

These are free to use, DON'T PAY FOR THEM! Just don't modify them unless of course you come here and mention the changes if any.
