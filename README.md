# Introduction

This is a fine tuning project to fine tune [TAIDE-LX-7B-Chat](https://huggingface.co/taide/TAIDE-LX-7B-Chat).
Let it can write Tang poems.Give the AI the first two sentences, we want it to continue the rest.

# Usage

## Fine tuning

Run FinetuneTaide.py(you have to download Taide7b-chat model and dataset first).
You can change the finetuning setting like **num_train_data**, **num_epoch** and **LEARNING_RATE**

## Testing

Run TestingTaide7b.py(you have to download dataset first).

# Dataset

[GenAI-Hw5](https://github.com/CheeEn-Yu/GenAI-Hw5)

# Model

[TAIDE-LX-7B-Chat](https://huggingface.co/taide/TAIDE-LX-7B-Chat)

# Reference

- https://www.youtube.com/@HungyiLeeNTU/featured
- https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php
- https://docs.google.com/presentation/d/1NINc4Av4pJDMsGL1N_B4CUviwU13-H0RiCvs2K01O-I/edit?slide=id.g26623f2086c_1_42#slide=id.g26623f2086c_1_42
- https://colab.research.google.com/drive/1nB3jwRJVKXSDDNO-pbURrao0N2MpqHl8?usp=sharing#scrollTo=7AI9jvvGtav2
- https://huggingface.co/taide/TAIDE-LX-7B-Chat
- https://github.com/CheeEn-Yu/GenAI-Hw5
