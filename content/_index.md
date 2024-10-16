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



# Call for Submissions

We invite researchers to submit work for the NeurIPS 2024 workshop on Bayesian Decision-making and Uncertainty, to be held on December 14, 2024. We welcome submissions in areas including but not limited to:

* Decision-making under uncertainty
* Bayesian optimization
* Probabilistic modeling
* Gaussian processes
* Active learning
* Uncertainty quantification
* Spatiotemporal modeling
* Sequential experimental design
* Forecasting for dynamical systems
* Bayesian methods for large language models and frontier AI
* Scaling Bayesian methods to handle complex, high-dimensional data and models
* Applications in scientific discovery, drug design, hyperparameter tuning, environmental monitoring, robotics and other domains

**Submission Guidelines:**

* Submissions should be in the form of a 4-page extended abstract using the [workshop's LaTeX style](bdu_2024.sty).
* Manuscripts should be anonymized in accordance with the [same rules as NeurIPS papers](https://neurips.cc/Conferences/2024/CallForPapers).
* Unlike the main conference, we do not require a checklist to be added to the submission PDF.
* References and appendices may extend beyond the 4-page limit. We encourage the use of BibLaTeX.
* If the submitted work has previously appeared in a journal or refereed workshop/conference proceedings, including the current NeurIPS proceedings, the workshop submission should extend the previous work. Simultaneous submission of the same 4-page manuscript to multiple workshops is not allowed.
* Accepted manuscripts will be made available on the workshop's website, but - following the standard format used by NeurIPS workshops - will not be published as part of official NeurIPS proceedings.
* Submission should be done via [OpenReview](https://openreview.net/group?id=NeurIPS.cc/2024/Workshop/BDU).

**Important Dates:**

* Submission deadline: **September 5, 2024 (anywhere on earth)**
* Notification of acceptance: by **October 14, 2024**
* Workshop dates: **December 14, 2024**
* Code of Conduct: Participants must agree to adhere to the NeurIPS code of conduct.

## [Submit via OpenReview](https://openreview.net/group?id=NeurIPS.cc/2024/Workshop/BDU)



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
| 09:30 - 10:00 | Invited Talk |
| 10:00 - 10:30 | **Coffee and Discussion** |
| 10:30 - 11:00 | Invited Talk |
| 11:00 - 11:10 | Contributed Talk |
| 11:10 - 11:20 | Contributed Talk |
| 11:20 - 11:30 | Contributed Talk |
| 11:30 - 12:00 | Placeholder |
| 12:00 - 13:00 | **Lunch and Poster Session Setup** |
| 13:00 - 13:30 | Invited Talk |
| 13:30 - 13:40 | Contributed Talk |
| 13:40 - 13:50 | Contributed Talk |
| 13:50 - 14:00 | Contributed Talk |
| 14:00 - 14:30 | **Coffee and Discussion** |
| 14:30 - 15:00 | Invited Talk |
| 15:00 - 15:30 | Lightning Talks |
| 15:30 - 16:30 | **Poster Session** |
| 16:30 - 17:00 | Invited Talk |
| 17:00 - 17:55 | **Panel Discussion** | 
| 17:55 - 18:00 | **Closing Remarks** |



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
    ]) }}