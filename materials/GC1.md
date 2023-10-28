Here's the provided text in Markdown format with headings and images:

# Google Colab - Introduction

Google is quite aggressive in AI research. Over many years, Google developed AI framework called **TensorFlow** and a development tool called **Colaboratory**. Today TensorFlow is open-sourced and since 2017, Google made Colaboratory free for public use. Colaboratory is now known as Google Colab or simply **Colab**.

Another attractive feature that Google offers to the developers is the use of GPU. Colab supports GPU and it is totally free. The reasons for making it free for public could be to make its software a standard in the academics for teaching machine learning and data science. It may also have a long term perspective of building a customer base for Google Cloud APIs which are sold per-use basis.

Irrespective of the reasons, the introduction of Colab has eased the learning and development of machine learning applications.

So, let us get started with Colab.

# Google Colab - What is Google Colab?

If you have used **Jupyter** notebook previously, you would quickly learn to use Google Colab. To be precise, Colab is a free Jupyter notebook environment that runs entirely in the cloud. Most importantly, it does not require a setup, and the notebooks that you create can be simultaneously edited by your team members - just the way you edit documents in Google Docs. Colab supports many popular machine learning libraries which can be easily loaded in your notebook.

## What Colab Offers You?

As a programmer, you can perform the following using Google Colab.

- Write and execute code in Python
- Document your code that supports mathematical equations
- Create/Upload/Share notebooks
- Import/Save notebooks from/to Google Drive
- Import/Publish notebooks from GitHub
- Import external datasets e.g. from Kaggle
- Integrate PyTorch, TensorFlow, Keras, OpenCV
- Free Cloud service with free GPU

# Google Colab - Your First Colab Notebook

In this chapter, you will create and execute your first trivial notebook. Follow the steps that have been given wherever needed.

**Note** - As Colab implicitly uses Google Drive for storing your notebooks, ensure that you are logged in to your Google Drive account before proceeding further.

**Step 1** - Open the following URL in your browser - [https://colab.research.google.com/notebooks/welcome.ipynb](https://colab.research.google.com/notebooks/welcome.ipynb) Your browser would display the following screen (assuming that you are logged into your Google Drive) -

![Colab Search](https://www.tutorialspoint.com/google_colab/images/colab_search.jpg)

**Step 2** - Click on the **NEW PYTHON 3 NOTEBOOK** link at the bottom of the screen. A new notebook would open up as shown in the screen below -

![New Notebook](https://www.tutorialspoint.com/google_colab/images/new_notebook.jpg)

As you might have noticed, the notebook interface is quite similar to the one provided in Jupyter. There is a code window in which you would enter your Python code.

## Setting Notebook Name

By default, the notebook uses the naming convention UntitledXX.ipynb. To rename the notebook, click on this name and type in the desired name in the edit box as shown here -

![Setting Notebook Name](https://www.tutorialspoint.com/google_colab/images/setting_notebook_name.jpg)

We will call this notebook as **MyFirstColabNotebook**. So type in this name in the edit box and hit ENTER. The notebook will acquire the name that you have given now.

## Entering Code

You will now enter a trivial Python code in the code window and execute it.

Enter the following two Python statements in the code window -

```python
import time
print(time.ctime())
```

## Executing Code

To execute the code, click on the arrow on the left side of the code window.

![Executing Code](https://www.tutorialspoint.com/google_colab/images/executing_code.jpg)

After a while, you will see the output underneath the code window, as shown here -

```python
Mon Jun 17 05:58:40 2019
```

You can clear the output anytime by clicking the icon on the left side of the output display.

![Output Display](https://www.tutorialspoint.com/google_colab/images/output_display.jpg)

## Adding Code Cells

To add more code to your notebook, select the following menu options -

```
Insert / Code Cell
```

Alternatively, just hover the mouse at the bottom center of the Code cell. When the **CODE** and **TEXT** buttons appear, click on the CODE to add a new cell. This is shown in the screenshot below -

![Code Text Buttons](https://www.tutorialspoint.com/google_colab/images/code_text_buttons.jpg)

A new code cell will be added underneath the current cell. Add the following two statements in the newly created code window -

```python
time.sleep(5)
print (time.ctime())
```
