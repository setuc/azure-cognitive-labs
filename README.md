# Microsoft Cognitive Services Labs

The sample code in this repository is for use in hands-on exercises in various cognitive services.

## Setup on Gitpod
[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/setuc/azure-cognitive-labs)

Once the docker is setup and the envoirnment is available, use the terminal to run the following command:
```
jupyter notebook --ip 0.0.0.0 --no-browser --allow-root
```

## Setup on Visual Studio

The exercises are designed to be completed in Visual Studio Online. To complete the labs, you'll need the following:

- A Microsoft Azure subscription. If you don't already have one, you can sign up for a free trial at [https://azure.microsoft.com](https://azure.microsoft.com?azure-portal=true).
- A Visual Studio Codespace based on the **setuc/azure-cognitive-labs** code repository. This provides a hosted instance of Visual Studio Code, in which you'll be able to run the notebooks for the lab exercises.

To set up a Visual Studio Codespace:

1. Open <a href = "https://online.visualstudio.com/environments/new?azure-portal=true&name=azure-cognitive-labs&repo=setuc/azure-cognitive-labs" target="_blank" rel="noopener">Visual Studio Online</a> in a new browser tab; and if prompted, sign in using the Microsoft account associated with your Azure subscription.
2. If you don't already have a Visual Studio Codespaces billing plan, create one. Then create a codespace with the following settings:
    - **Codespace Name**: *A name for your codespace - for example, **ai-fundamentals**.*
    - **Git Repository**: setuc/azure-cognitive-labs
    - **Instance Type**: Standard (Linux) 4 cores, 8GB RAM
    - **Suspend idle Codespace after**: 30 minutes
3. Wait for the codespace to be created. This will take around 3 minutes. You'll see the following things happen:
    - A script will initialize and configure your codespace.
    - A list of notebook (.ipynb) files will appear in the pane on the left.
    - After a few minutes, a file named **z REFRESH NOW!** will appear at the bottom of the list of files. This is your indication that everything has been installed.
5. After the **z REFRESH NOW!** file has appeared, ***refresh the web page*** to ensure all of the required extensions are loaded and set the color scheme to a light background. Then you're ready to start.
6. After you have refreshed the web page, you can close the **Welcome** panes and delete the **z REFRESH NOW** file if you want to. You can also change the color scheme to suit your preference - just click the **&#9881;** icon at the bottom left and select a new **Color Theme**. A light color theme is recommended to make it easier to read the Python code in the notebooks.
