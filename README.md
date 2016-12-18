# Middlemen and Contestation in Directed Networks

## 1 About

This directory contains a set of TeX files which, when compiled into a PDF, the paper **Contestability and Critical Nodes in Directed Networks**. The paper provides an analysis of central and critical nodes within a general network topology. 

### 1.1 Abstract

This article develops and assesses the notions of contestability and critical nodes within a topological structure. We quote the abstract of the article below.
>
> Critical nodes---or ``middlemen''---have an essential place in both social and economic networks, particularly when considering the flow of information and trade. This paper extends the concept of critical nodes to directed network and, in doing so, identifies string and weak middlemen.
>
> Node contestability is introduced as a form of competition in network; a duality between uncontested intermediaries and middlemen is established. The brokerage power of middlemen is formally expressed and a general algorithm constructed to measure the brokerage power of each node from the network's adjacency matrix. Augmentations of the brokerage power measure are discussed to encapsulate relevant centrality measures. Furthermore, we extend these notions and provide measures of the competitiveness of a network. To this we also provide measurements of the robustness of a middleman position.
>
> We use these concepts to identify and measure middleman power and robustness in two empirical socio-economic networks: Krackhardt’s advice network of managers in a large corporation and the well-known Florentine marriage network as a proxy of power brokerage in Renaissance Florence.

## 2 Compiling the article

The latest PDF should have already been compiled and uploaded to the repository. If the latest PDF has not been compiled, or to make changes and compile yourself, you must have a LaTeX executable installed on your system. 

* For Windows I suggest using [MiKTex](http://miktex.org/download),
* For Mac OSX I suggest using [MacTeX](https://tug.org/mactex/), and
* For Ubuntu Linux I suggest using [TeX Live](https://help.ubuntu.com/community/LaTeX).

## 3 Statistical code and visualisation tools

We provide a number of functions written in the `R` programming languages that were used in conjunction with the mathematical tools developed in the article. The functions were used for network analysis. Some data, which was also used throughout the article, has been provided to test the tools on. These functions can be found in the `code` directory.

### 3.1 Network visualisation

All networks, and some of the analysis, were rendered with the `Gephi` software package which can be found [here](https://gephi.org/). I created a wrapper for `Gephi` such that data generated in `R` could be passed between it and `Gephi`.

## 4 Contact

Please contact [me](mailto:sims.owen@gmail.com) with regards any issues or queries that you have.