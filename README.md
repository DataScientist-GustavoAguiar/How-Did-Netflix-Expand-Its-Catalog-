# How Did Netflix Grow Its Catalog? Find Out.

Here we will try to understand Netflix's growth through a data-driven approach based on the "Netflix Movies and TV Shows" dataset from Kaggle.

Link to Medium Article: https://medium.com/@gustavoaguiar_21700/how-did-netflix-grow-its-catalog-find-out-3793ad4b5157

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre](#Sobre)
   * [Tabela de Conteudo](#tabela-de-conteudo)
   * [Instalação](#instalacao)
   * [Como usar](#como-usar)
      * [Pre Requisitos](#pre-requisitos)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
   * [Tests](#testes)
   * [Tecnologias](#tecnologias)
<!--te-->

## Introduction
Netflix generates more than $25 billion in income each year. It features an extensive range of movies and TV shows, many high-quality original programs, and an easy-to-use interface. Netflix continues to work on growing its catalog.

You’ve probably had a conversation with a friend about a movie or a TV show, and one of you added

“And to top it all off, it’s available on Netflix!”

Actually, many prefer Netflix to alternative streaming services and television programs.

But why is that? What do the newly added movies and TV series data imply? Are there any patterns or trends?

In this blog, we will use the CRISP-DM method to understand better the titles that Netflix is adding and its efforts to maintain its leadership in the streaming sector.

Based on our primary business question, “How Did Netflix Become the Best?” I’ve defined five questions that can help us understand and answer our main question.

* “Is Netflix adding more content than ever before to its catalog?”

* “Which countries’ movies and TV series are being added to Netflix?”

* “Is there a difference in the number of movies and TV shows added to the catalog based on region?”

* “What were the varied strategies for adding content to regions?”

* “Based on title rating, who is the target audience for the titles added from the major countries?”

To answer these questions, I took data from the Netflix Movies and TV Shows dataset from Kaggle. The dataset includes 8807 titles.

## Programming language & libraries

This project was created with:
Python 3.6
ipython >= 7

This involves the use of common Python libraries: import numpy as np import pandas as pd import matplotlib.pyplot as plt import seaborn as sns import plotly.express as px %matplotlib inline

Libraries used: pandas, numpy, matplotlib, seaborn, flake8, pycountry.

## Autor

Gustavo Aguiar 👋🏽 Kindly Regards!

Production Engineer | Master's Student in Production Engineering and Computational System | Data Analyst and Physical Simulation Engineering

[![Linkedin Badge](https://img.shields.io/badge/-Gustavo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gjmaguiar/?locale=en_US)](https://www.linkedin.com/in/gjmaguiar/?locale=en_US) 
[![Gmail Badge](https://img.shields.io/badge/-gustavoaguiar@id.uff.br-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:gustavoaguiar@id.uff.br)](mailto:gustavoaguiar@id.uff.br)

## Copyright and license
Code and documentation copyright 2021 author. Code released under the MIT License. Docs released under Creative Commons.
