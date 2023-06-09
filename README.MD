# PrivateGPT

Create a QnA chatbot on your documents without relying on the internet by utilizing the capabilities of local LLMs. Ensure complete privacy and security as none of your data ever leaves your local execution environment. Seamlessly process and inquire about your documents even without an internet connection. Inspired from [imartinez](https://github.com/imartinez)

<img width="948" alt="pgpt" src="https://github.com/nu11secur1ty/privateGPT/blob/main/Screen/Screenshot%202023-06-11%20084021.png"><br>
<img width="948" alt="pgpt" src="https://github.com/nu11secur1ty/privateGPT/blob/main/Screen/Screenshot%202023-06-11%20084956.png"><br>

## Math:
<img width="948" alt="pgpt" src="https://github.com/nu11secur1ty/privateGPT/blob/main/Screen/Screenshot%202023-06-11%20083003.png"><br>
<img width="948" alt="pgpt" src="https://github.com/nu11secur1ty/privateGPT/blob/main/Screen/math.png"><br>


## Shell answer:
<img width="948" alt="pgpt" src="https://github.com/nu11secur1ty/privateGPT/blob/main/Screen/Screenshot%202023-06-10%20230258.png"><br>

## Contents

* [Getting started](#getting-started)
* [Requirements](#requirements)
* [How to run](#how-to-run)
* [Support](#support)
* [Data](#data)
* [Check repos](#check-repos)

## Support Python versions:
```python
3.10
--------------------------------------------------------------------------
3.11
# Python 3.11.4 (tags/v3.11.4:d2340ef, Jun  7 2023, 05:45:37) [MSC v.1934 64 bit (AMD64)] on win32
# Type "help", "copyright", "credits" or "license" for more information.
````

## Getting started

Code is up, ⭐ (Star) the repo meanwhile to receive updates

## Requirements

* Python 3.10.0 RECOMMENDED!
* Minimum 16GB of memory

## How to run

1. Go to client folder and run the below commands

   ```shell
   npm install   
   ```

   ```shell
   npm run dev
   ```

2. Go to server folder and run the below commands

   ```shell
   pip install -r requirements.txt
   ```

   ```shell
   python privateGPT.py
   ```

3. Open <http://localhost:3000>, click on download model to download the required model initially

4. Upload any document of your choice and click on Ingest data. Ingestion is fast

5. Now run any query on your data. Data querying is slow and thus wait for sometime

## Support

Join our discord <https://discord.gg/A6EzvsKX4u> to get support

And <https://github.com/nu11secur1ty/privateGPT>

## Data

The supported extensions for documents are:

* .csv: CSV,
* .docx: Word Document,
* .enex: EverNote,
* .eml: Email,
* .epub: EPub,
* .html: HTML File,
* .md: Markdown,
* .msg: Outlook Message,
* .odt: Open Document Text,
* .pdf: Portable Document Format (PDF),
* .pptx : PowerPoint Document,
* .txt: Text file (UTF-8),

## Check repos

* [Langchain Course](https://github.com/SamurAIGPT/langchain-course)
* [ChatGPT Developer Plugins](https://github.com/SamurAIGPT/ChatGPT-Developer-Plugins)
* [Camel AGI](https://github.com/SamurAIGPT/Camel-AutoGPT)
