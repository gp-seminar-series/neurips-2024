+++
title = "NeurIPS Workshop on Bayesian Decision-making and Uncertainty"
+++

# Abstract

Recent advances in ML and AI have led to impressive achievements, yet models often struggle to express uncertainty, and more importantly, make decisions that account for uncertainty. 
This hinders the deployment of AI models in critical applications, ranging from scientific discovery, where uncertainty quantification is essential, to real-world scenarios with unpredictable and dynamic environments, where models may encounter data vastly different from their training sets.

Through the use of probability, Bayesian methods offer a powerful framework to address these limitations by quantifying uncertainty, incorporating prior knowledge, enabling adaptive decision-making and information gathering in uncertain environments. 
These approaches have led to significant progress and success in relevant fields, tackling critical problems such as drug discovery, hyperparameter tuning and environmental monitoring. 
However, challenges remain in both theory and practice, such as establishing performance guarantees and scaling up these methods to handle the complexity and dimensionality of larger data and models. 
On the other hand, the development of frontier models (e.g., based on large language models) presents new opportunities to enhance Bayesian methods with stronger priors and tools not previously available.

This workshop aims to bring together researchers from different but closely related areas, including Bayesian optimization, active learning, uncertainty quantification, Gaussian processes, spatiotemporal modeling, and sequential experimental design. 
We seek to foster a vibrant exchange of ideas, showcase successful applications, and prompt fruitful discussion to collaboratively tackle the emerging challenges and shape the future directions of Bayesian decision-making and uncertainty in the new era of ML and AI.



{{ new_block() }}



# Speakers

{{ grid(
    text = [
        ["Roman Garnett","Washington University in St. Louis and Uber"], 
        ["Jacob R. Gardner","University of Pennsylvania"],
        ["Virginia Aglietti","Google DeepMind"],
        ["Esther Rolf","University of Colorado Boulder"],
        ["Mark van der Wilk","University of Oxford"],
    ],
    urls = [
        "https://www.cse.wustl.edu/~garnett/",
        "https://jacobrgardner.github.io",
        "https://virgiagl.github.io/",
        "https://estherrolf.com",
        "https://mvdw.uk",
    ],
    image_dir = "speakers",
    narrow = true) }}



{{ new_block() }}



# Schedule

| Time (Canada) | Event |
|---------------|-------|
| 09:00 - 09:30 | **Introduction and Opening Remarks: Andreas Krause** |
| 09:30 - 10:00 | Invited Talk: Mark van der Wilk - _Open Problems in Gaussian Process Approximation and Benchmarking_ |
| 10:00 - 10:30 | **Discussion Break** |
| 10:30 - 11:00 | Invited Talk: Esther Rolf - _We need to talk (more) about uncertainty in geospatial machine learning_ |
| 11:00 - 11:10 | Contributed Talk: Mathieu Alain - _Graph Classification Gaussian Processes via Hodgelet Spectral Features_ |
| 11:10 - 11:20 | Contributed Talk: Taiwo Adebiyi - _Gaussian Process Thompson Sampling via Rootfinding_ |
| 11:20 - 11:30 | Contributed Talk: Freddie Bickford Smith - _Rethinking Aleatoric and Epistemic Uncertainty_ |
| 11:30 - 12:30 | **Lunch and Poster Session Setup** |
| 12:30 - 12:40 | Contributed Talk: Patrick O'Hara - _Distributionally Robust Optimisation with Bayesian Ambiguity Sets_ |
| 12:40 - 12:50 | Contributed Talk: Joachim Schaeffer - _Lithium-Ion Battery System Health Monitoring and Resistance-Based Fault Analysis from Field Data Using Recursive Spatiotemporal Gaussian Processes_ |
| 12:50 - 13:00 | Contributed Talk: Rafael Oliveira - _Variational Search Distributions_ |
| 13:00 - 13:30 | Invited Talk: Roman Garnett - _What I learned while writing the BayesOpt book_ |
| 13:30 - 14:00 | **Discussion Break** |
| 14:00 - 14:30 | Invited Talk: Jacob R. Garnder - _Bayesian optimization needs better deep learning_ |
| 14:30 - 15:00 | Lightning Talks: Joshua Hang Sai Ip, Dingyang Chen, Guiomar Pescador-Barrios, Sebastian W. Ober, Conor Heins, Richard Bergna, Martin Trapp, Yibo Jiang |
| 15:00 - 16:00 | **Poster Session** |
| 16:00 - 16:30 | Invited Talk: Virginia Aglietti - _FunBO: Discovering Acquisition Functions for Bayesian Optimization with FunSearch_ |
| 16:30 - 17:25 | **Panel Discussion** | 
| 17:25 - 17:30 | **Closing Remarks** |



{{ new_block() }}



# Organizers

{{ grid(
    text = [
        ["Alexander Terenin","Cornell University"],
        ["Natalie Maus","University of Pennsylvania"],
        ["Renato Berlingheiri","MIT"],
        ["Zi Wang","Google DeepMind"],
    ],
    urls = [
        "https://avt.im/",
        "https://sites.google.com/seas.upenn.edu/natalie-maus/home/",
        "https://renatoberlinghieri.github.io/",
        "https://ziw.mit.edu/",
    ],
    image_dir = "organizers") }}



{{ new_block() }}



# Advisory Committee

{{ grid(
    text = [
        ["Eytan Bakshy","Meta"],
        ["David Bindel","Cornell University"],
        ["Tamara Broderick","MIT"],
        ["Carl Henrik Ek","University of Cambridge"],
        ["Seth Flaxman","University of Oxford"],
        ["Emtiyaz Khan","RIKEN"],
        ["Andreas Krause","ETH Zürich"],
        ["Jasper Snoek","Google DeepMind"],
    ],
    urls = [
        "https://eytan.github.io",
        "https://www.cs.cornell.edu/~bindel/",
        "https://tamarabroderick.com/",
        "http://carlhenrik.com/",
        "https://sethrf.com/",
        "https://emtiyaz.github.io/",
        "https://las.inf.ethz.ch/krausea",
        "https://research.google/people/jasper-snoek/",
    ],
    image_dir = "advisors") }}



{{ new_block() }}



# Sponsors

{{ grid(
    text = [
        ["Google Research"],
        ["Meta"],
    ],
    urls = [
        "https://research.google/",
        "https://ai.meta.com/",
    ],
    images = [
        "sponsors/google-research.svg",
        "sponsors/meta.svg"
    ],
    dark_invert = [
        false,
        true
    ]) }}



{{ new_block() }}



# Accepted Workshop Papers

{{ table(
    data = "papers.csv", 
    button_names = ["paper"], 
    button_data_columns = [2], 
    button_output_columns = [1]) }}