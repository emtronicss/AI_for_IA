# AI_for_IA
Simple jupyter notebooks implementing FNNs for regression and classification problems for the course AI for IA November 2024, Master in Industrial Analytics in Uppsala University, Sweden.

There are a couple of notebooks with their corresponding data sources when required, they were made in google colab and the easiest way I've found for running them is to mount all the necesary files into a google drive folder and execute from there.

These notebooks were tested and evaluated so execunting each step in the order they are made should work without any error. This way is also guaranteed that the required libraries are imported.
If at any point there is an error related to the version of libraries, this usually is solved by reloading the runtime and running again from the begining.

**MA3_ANNforClassification.ipynb**

Here the main goal is:
To understand how common data like signals and images are represented as one/multi-dimensional numerical
arrays and tensors in order to be useful for FANN training.
Learn how to solve large-scale classification problems using FANNs in PyTorch

**MA4_AI_Agents_2.ipynb**

In this notebook I replicate the work in this article posted in medium: https://medium.com/towards-data-science/ai-agents-from-concepts-to-practical-implementation-in-python-fb26789b1560

In the article the author briefly introduces AI agents or LLMs (Large Language Models). He points out that a more robust system with better results can be obtained if instead of prompting a single LLM to handle a complex task, the task is split between multiple agents, each one specialized in a specific related area. The task consists in implementing a content creation workflow system that writes blog posts, LinkedIn content and Twitter posts, after extensive research about a topic selected by the user, which in this case is about analyzing the content of a video created by the author himself.

At the end of each file there are some reflections about each procedure.

Eric M.
