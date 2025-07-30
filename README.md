# Civitai_Trigger_Finder
Searches your local machine for LoRA's then heads to CivitAI to download the Triggers and Thumbnails - pretty simple really.

Edit these for your specific machine, the folder_path is where your LoRA's are and the output_folder is where the output files (html, json and txt) will end up.

def main():
    # Specify the folder to scan and output folder (modify these paths as needed)

    folder_path = r"C:\Users\AI\models\loras"
    
    output_folder = r"C:\Users\AI\lora_triggers"
