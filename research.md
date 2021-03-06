---
layout: default
title: Research
---

### Research background



By training I am a theoretical computer scientist with the focus on artificial intelligence and machine learning. Towards the end of my
studies, I have increasingly often tapped neuroscience and psychology for inspirations on how to build intelligent systems.
This dual interest lead me to join a program in [Neuroinformatics](http://www.anc.ed.ac.uk/dtc/) at the [Unviersity of Edinburgh](http://www.ed.ac.uk/home), where my interest in the brain
grew further, eventually leading to my PhD thesis on the topic of [Development of functional properties in primary visual cortex](https://www.era.lib.ed.ac.uk/handle/1842/4875) under the
supervision of [James Bednar](http://homepages.inf.ed.ac.uk/jbednar/). My first post-doctoral post was in the lab of [Tom-Mrsic Flogel](http://www.biozentrum.unibas.ch/research/groups-platforms/overview/unit/mrsic-flogel/) at UCL, where I had the chance to
brush up my machine learning skills while investigating novel ways to estimate receptive fields in local populations of mouse
primary visual cortex neurons. Next I have switched my attention to studying cat early vision  using [large-scale spiking neural modelling approach](http://127.0.0.1:4000/projects.html) under the co-supervision of <a href="http://andrewdavison.info/">Andrew Davison</a> and <a href="https://www.unic.cnrs-gif.fr/people/Yves_Fr%C3%A9gnac/"> Yves Frégnac</a> at 
the <a href="https://www.unic.cnrs-gif.fr/">UNIC</a> department of CNRS.  I then continued to pursue the study of early vision at <a href="http://www.institut-vision.org/en/">Institute de la Vision</a> in Paris in the
group of <a href="http://www.institut-vision.org/en/vision-and-natural-computation/item/109-benosman-ryad.html">Pr. Ryad Benosman</a>, where I applied the large scale models of V1 to 
the problem of [optogenetic based cortical visual prosthesis](https://www.darpa.mil/news-events/2017-07-10), as well as utilized my experience in artificial intelligence and 
cortical modeling to pursue projects in the field of [Neuromorphic Vision](http://neuromorphic-vision.com/). Currently I continue to pursue all these lines of research at my alma mater, 
the <a href="https://www.mff.cuni.cz/">Faculty of Mathematics and Physics</a> of <a href="https://cuni.cz/">Charles University</a> in Prague. 


<br>

### Current research interests

* visual system
* computational neuroscience
* system identification
* machine learning
* neuromorphic computation

<br>


### Available student projects

Would you like to contribute to our research? This is a list of projects available for interested students. 
Most are designed to be completed within 3 to 6 month, but some can be expanded into longer projects even 
full PhD scope. If you are interested in working on any of the projects please [contact me](./index.html).


#### Computational Neuroscience Projects



* <a href="javascript:void(0)" onclick="$('#project_RF').toggle();">Characterizing RFs in V1 model.</a>   
    <small id="project_RF" class="studentprojectlist" style="display: none;">
    We have recently constructed a detailed large-scale [model](https://www.biorxiv.org/content/biorxiv/early/2019/02/20/416156.full.pdf) of cat primary visual cortex.
    One of the major approaches for characterizing the functional properties of sensory neurons is called system indetification, wherby one applies machine learning
    techniques to long recordings of neurons responding to sensory stimuli. Many such studies have been undertaken for primary visual cortex. In this project the goal
    is to analyze our model of V1 with the same system identification techniques to compare how neurons in the model encode visual information in comparison to 
    their biological counterparts.
</small>


* <a href="javascript:void(0)" onclick="$('#project_macaque').toggle();">Model of Macaque V1.</a>   
    <small id="project_macaque" class="studentprojectlist" style="display: none;">
    We have recently constructed a detailed large-scale [model](https://www.biorxiv.org/content/biorxiv/early/2019/02/20/416156.full.pdf) of cat primary visual cortex.
    Along with cat, macaque is the most common animal model in which vision in higher mammals is studied. Recently, a comprehensive 
    dataset on macaque physiology and function has been [published](https://academic.oup.com/cercor/article-abstract/30/6/3483/5691251?redirectedFrom=fulltext). The goal of this project would be to utilize this new data and
    reparametrize the existing model of cat V1 to obtain analogouse model of macaque V1. Exploration of the implication of species differences
    on V1 processing is a possible future extension of the project. 
  </small>

* <a href="javascript:void(0)" onclick="$('#project_body').toggle();">Biologically plausible model of body representation development.</a>   
    <small id="project_body" class="studentprojectlist" style="display: none;">
This project is performed in tight collaboration with the robotics group of [Matej Hoffman](https://sites.google.com/site/matejhof/home).
The goal of this project is to explain how body representations can be learned in humanoid robots during
haptic self-exploration based on inputs provided by ‘artificial skin’ covering the robot’s body.
We hypothesize that [our model of cortical development proposed](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3082289/pdf/fncom-05-00017.pdf) 
can aid this goal in following two ways:  (i) the model itself, when fed with the somatosensory data will form effective, 
biologically plausible representation of body surface, (ii) the novelty signal that can be straightforwardly 
obtained from the model can within the closed loop paradigm guide self-exploration behavior towards efficient 
exploration of the body space. The novelty signal is readily available in the model, as novel inputs are poorly 
represented by the evolving cortical representation and thus the input will have high distance from the most representative 
(close within input space) cortical neuron. Thus a simple winner-take-all mechanism at the cortical level, that outputs 
the distance between the input and the point in input space the winner neuron represents will yield effective novelty signal. 
The student will test these hypotheses in collaboration with the [Hoffman group](https://sites.google.com/site/matejhof/home) guided by following milestones. He/she will
implement and validate the model of somatosensory map formation from artificial skin inputs, implement the novelty signal extraction 
mechanism, test its impact on map formation in closed-loop system, integrate the resulting model within the humanoid 
robotic system at Hoffman group, and perform experiments to confirm effectiveness of the model and search for bio-morphic 
correlates in the resulting behavior.
    </small>

* <a href="javascript:void(0)" onclick="$('#project_mozaik_ON_OFF').toggle();">OFF centred thalamic V1 convergence.</a>   
    <small id="project_mozaik_ON_OFF" class="studentprojectlist" style="display: none;">
    Recent [work](https://www.nature.com/articles/nature17936) by Alonso Lab has shown that thalamic ON and OFF afferents converging onto neurons in primary visual cortex
    have a very specific organization, which is OFF dominated, OFF centric and runs orthogonal to ocular dominance columns. Our current <a href="./projects.html">large-scale integrative model </a> 
    of V1 does not feature this specific organization of thalamo-cortical afferents. The goal of this project will be to integrate this specific thalamo-cortical convergence 
into the model, and then analyze the impact of this more specfific connectivity on the functional properties of the model.
    </small>


* <a href="javascript:void(0)" onclick="$('#project_tw').toggle();">Travelling waves.</a>   
    <small id="project_tw" class="studentprojectlist" style="display: none;">
       During spontaneous activity, mammalina cortex exhibits regular spontaneous emergence of waves of activity that travel across the cortical surface. 
       Furthermore, spatially, these waves tend to be correlated with the functional organization across cortical surface. Such highly structured spontaneous
       activity, present even in low-level sensory cortical areas,  has been hypothesized to be linked to such phenomena, as imagination, dreams, formation 
       of long-term memory and other high-level cognitive phenomena. In this project student will explore the presence of such spontaneos waves in our comprehensive model
of cat primary visual cortex. He/she will expand the <a href="https://github.com/antolikjan/mozaik">Mozaik</a> framework with the ability to record Local Field Potential
type of signal. Perform experiments in which the waves will be recorded and will compare such in-silico generated data to in-vivo data from our international collaborators.
    </small>

* <a href="javascript:void(0)" onclick="$('#project_assoc').toggle();">Association field in visual cortex of higher mammals.</a>   
    <small id="project_assoc" class="studentprojectlist" style="display: none;">
       In the visual environment, human observers directly extract continuous contours effortlessly. This could be explained by the existence of lateral 
       interactions between cortical cells in V1 that facilitate the binding of collinear, and to a certain extent co-circular, edges in the visual field. 
       Recent electrophysiological data from [collaborating group in France](http://neuro-psi.cnrs.fr/spip.php?page=ICN&lang=fr) supports this hypothesis. 
       Coherent flows of oriented stimuli originating from the far periphery and converging towards the receptive field center of V1 single cells are able 
       to elicit an earlier and stronger response when compared to the sole stimulation of the receptive field center. This lateral interaction is the 
       synaptic footprint of a dynamic association field that favours the binding of form and motion as early as V1. One of the ongoing projects in our group 
       is the development of a large-scale integrative model of cat primary visual cortex (V1). The student’s task will be to analyse in this model the progressive build-up 
       of activity by multiple nearby neurons that contribute to the emergence of the assocation field.
    </small>

* <a href="javascript:void(0)" onclick="$('#project_v1dnn').toggle();">Early visual cortex vs Deep Neural Networks.</a>   
    <small id="project_v1dnn" class="studentprojectlist" style="display: none;">
    Deep neural networks are becoming an important tool in understanding biological neural computation. For example, the computational power of different cortical 
    areas along the visual hierarchy has been successfully estimated by comparing the recordings of neurons from these areas to neurons in different layers of 
    DNNs trained on visual data. Such studies with in-vivo data, however, have limitations due to the ability to record only single cell at a time. In this project 
    we will explore the possibility of using DNNs to estimate the computing power of a detailed model of cat primary visual cortex, as well as apply techniques 
    developed for analysis of transformations happening along the layers of DNNs to estimate the transformation performed by early visual system. This way, we will
    surprass the limitations imposed by in-vivo recordings, and further our understanding of computation happening in early visual system.
    </small>


* <a href="javascript:void(0)" onclick="$('#project_dev_ON_OFF').toggle();">Reconciling activity driven development of orientation maps with ON/OFF V1 convergence.</a>   
    <small id="project_dev_ON_OFF" class="studentprojectlist" style="display: none;">
    During post-natal development, primary visual cortex undergoes remarkable functional organization resulting in expression
    of topologically smooth orientation map across it's surface. The most common type of explenation for this phenomena is activity based development,
    whereby internally generated or visually driven activity coupled with plasticity in the thalamo-cortical and corico-cortical pathway
    induces gradual establishment of the orientation maps. [LISSOM](http://ioam.github.io/topographica/Tutorials/GCAL_Tutorial.html) based familiy of models is an example of such activity + plasticity driven theoretical explanation of this phenomena.
    Recent [work](https://www.nature.com/articles/nature17936) by Alonso Lab has shown that thalamic ON and OFF afferents converging onto neurons in primary visual cortex
    have a very specific organization, which is OFF dominated, OFF centric and runs orthogonal to ocular dominance columns. The current activity driven models of V1 development 
    cannot explain this specific organization of thalamo-cortical afferents. The goal of this project will be the expand these models to account for these new findings.
    </small>


* <a href="javascript:void(0)" onclick="$('#project1').toggle();">Unifying retinal mozaik model with activity based development.</a>   
    <small id="project1" class="studentprojectlist" style="display: none;">
        During post-natal development, primary visual cortex undergoes remarkable functional organization resulting - among others - in expression
        of topologically smooth orientation map across it's surface. The most common type of explenation for this phenomena is activity based development,
        whereby internally generated or visually driven activity coupled with plasticity in the thalamo-cortical and corico-cortical pathway
        induces gradual establishment of the orientation maps. [LISSOM](http://ioam.github.io/topographica/Tutorials/GCAL_Tutorial.html) based familiy of models is an example of such activity + plasticity driven models.
        An alternative explanation has been proposed by [Ringach](http://jn.physiology.org/content/92/1/468) (see also [this](http://www.nature.com/neuro/journal/v14/n7/full/nn.2824.html)) , in which the initial orientation maps are directly established by
        the very specific geometric properties of retinal ganglion cells RFs positions in visual space: [retinal mozaiks](http://labs.nri.ucsb.edu/reese/benjamin/PubsRetinalMosaics.html). However, this explanation
        can account only for initial very weak orientation maps, and low orienation selectivities of individual neurons in particular, and it is clear that
        the system has to undergo major further refinement in order to match the experimentally observed adult state. The goal of this project is to combine
        the two hypothesis of orientation map development and investigate their possible interactions.
        Specifically retinal mozaiks will be introduced into a LISSOM model, thus inducing the initial orientation maps based on Ringach et al. theory.
        This will be followed by simulation of the activity and plasticity driven development, which should lead to refinement of the intial maps.
        The correspondance between the initial retinal mozaik induced map with the final developed map will be assesed, and possible advantages of such
        dual orientation map development mechanism will be investigated.
    </small>

* <a href="javascript:void(0)" onclick="$('#project2').toggle();">Embedding of detailed compartmental neuron models into large-scale model of V1.</a>  
    <small id="project2" class="studentprojectlist" style="display: none;">
        One of the ongoing projects in our group is development of  <a href="./projects.html">large-scale integrative model </a> of cat primary visual cortex (V1).
        This model is based on the <a href="http://www.scholarpedia.org/article/Adaptive_exponential_integrate-and-fire_model">Adaptive-Exponential Leaky Integrate and Fire</a> 
        neuron model, which reduces biological neurons to a point process, ignoring
        its geometrical properties. In this project student will embed single compartmental model of V1 pyramidal neuron into the large scale point process
        simulation available in the group, and investigate the behavior of the added detailed neuron under the influence of the input coming from the large scale 
        V1 simulation, focusing on properties influenced by the neuron's geometry.
    </small> 

* <a href="javascript:void(0)" onclick="$('#project3').toggle();">Local-field potentials (LFP) in a large-scale model of cat primary visual cortex.</a>    
    <small id="project3" class="studentprojectlist" style="display: none;">
        One of the ongoing projects in our group is development of  <a href="./projects.html">large-scale integrative model </a> of cat primary visual cortex (V1).
        [LFP](https://en.wikipedia.org/wiki/Local_field_potential) is an electrophysiological signal generated by the summed electric current flowing from multiple 
        nearby neurons within a small volume of nervous tissue. The goal of this project is to investigate the LFP signals that would be generated 
        in our simulations of V1. The V1 model under investigation does not explicitly  contain LFP signals, only the sub-threshold and spiking responses of 
        individual neurons are available. Therefore one of previously proposed models 
        of LFP signals such as [this one](https://github.com/INM-6/hybridLFPy) will be used to generate artifical LFP signals based on the outputs of the V1 simulation. 
        This will be followed by thourough analysis of the resulting LFPs and results compared to previous findings, including recent data recorded at <a href="http://www.unic.cnrs-gif.fr/teams.html">UNIC</a> by the 
        <a href="https://www.unic.cnrs-gif.fr/teams/Research%20group%20of%20Yves%20Fr%C3%A9gnac">Yves Frégnac group</a>. 
  </small>        

* <a href="javascript:void(0)" onclick="$('#project9').toggle();">Processing of higher order correlations in early visual cortex\: a computational modelling investigation.</a>   
  <small id="project9" class="studentprojectlist" style="display: none;">
    Recent experimental studies have revealed differences in how neurons in primary (V1) and secondary (V2) visual cortices (the first two stages of visual cortical processing) process high-order statistics in visual scenes, indicating emergence of sensitivity to 2nd order correlations in V2 but not V1 neurons \[[1](https://doi.org/10.1038/nn.3402),[2](https://doi.org/10.1016/j.visres.2014.10.004),[3](https://doi.org/10.7554/eLife.03722)\]. However, the neural mechanisms of such sensitivity, and their implementation in biological neural substrate remain unknown.  To address this question, we will use detailed large-scale spiking neural network modelling paradigm to formulate hypothesis of neural circuits that can explain such neural functional properties. The student will be responsible for the first stage of longer-term project, in which he will implement a set of specialized visual stimuli as in \[[1](https://doi.org/10.1038/nn.3402)\]. Subsequently, student will test an existing model of V1 using the same experimental paradigm as in \[[1](https://doi.org/10.1038/nn.3402)\] for sensitivity to 2nd order correlations.
  </small> 

* <a href="javascript:void(0)" onclick="$('#project10').toggle();">Stimulation protocols for cortical visual prosthesis.</a>   
  <small id="project10" class="studentprojectlist" style="display: none;">
    Recently we have applied the large-scale models developed in our team to the problem of cortical visual prosthesis. New approach to sensory prosthetics is being developed, 
wherby the the cortex is stimulated via opto-genetic tools, which are being translated from mice to higher-order mammals including primates. While all the technological components
of the visual prosthesis are still under development, an important question remains open: how to stimulate the cortex to elicit percepts that are close to those due to the perception
of the given stimulus under normal vision. This is where our large-scale modelling approach comes in.  Using our V1 model simulations to test potenial stimulation strategies, we are 
making progress at answering this question. Currently, we have gained insights
on how to eleicit simple canonical visual stimuli, specifically sinusoidal gratings. In the next step the student will be responsible for expanding the design and analysis to generic 
stimulation protocol capable of eliciting arbitrary visual stimuli. The current protocol can be straightforwardly expanded to this general case . The student't responsibility will be 
to implement this new stimulation protocol in our simulation framework, test the protocol in our model of V1, and implement and perform all the required analysis. Strong programming and 
analytical skills required. Knowledge of Python, computation neuroscience or neurobiology of visual system a plus.
</small> 


* <a href="javascript:void(0)" onclick="$('#project11').toggle();">Deep biologically structured system identification approaches for studying primary visual cortex function.</a>   
  <small id="project11" class="studentprojectlist" style="display: none;">
    A common approach for studying the function of early sensory systems is to determine the relationship between sensory inputs and associated (experimentally recorded) neural responses. In the past, mostly linear \[[1](http://www.ncbi.nlm.nih.gov/pubmed/12938771
)\], or shallow non-linear techniques were utilized, leading to limited predictive and consequently explanatory power of models fitted in this way. More recently, the popular deep convolutional architectures were successfully tested on the neural data \[[2](https://arxiv.org/abs/1711.02653),[3](https://doi.org/10.1101/201764)\]. These general, machine-learning motivated models ,however, ignore the known anatomical and functional architecture of visual system. Recently, we have presented a multi-stage model of V1 which reflected some of the most prominent features of the retino-cortical pathway \[[4](https://doi.org/10.1371/journal.pcbi.1004927)\], and demonstrated that such incorporation of V1 biology can improve performance in comparison to state-of-the-art models. In this project we will  built upon these early results, and develop novel deep-architectures inspired by the deep convolutional networks, but enriched by biologically inspired elements. The student will be responsible for designing, implementing and subsequently testing the new models on neural population recordings from cat primary visual cortex. This project will be undertaken in collaboration with experimental lab of Yves Fregnac, CNRS, France, and computational lab of Dan Butts, University of Maryland. Prior experience in machine learning is a plus.
  </small> 




#### Software engineering projects

* <a href="javascript:void(0)" onclick="$('#project5').toggle();">Mozaik data-store module based on object oriented database.</a>   
    <small id="project5" class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations,
        with a highly modular architecture. One of the core Mozaik modules is a data-store, in which recordings from simulations richly
        annotated with metadata regarding experimental context are stored. Currently the data-store module is implemented as a
        database-like system based on [Neo](http://neuralensemble.org/neo/) library for internal representation of recorded data. 
        The goal of this project is to develop an alternative data-store module based around dedicated key-value database such as
        [BerkelyDB](http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html) or [CodernityDB](http://labs.codernity.com/codernitydb/).
    </small>

* <a href="javascript:void(0)" onclick="$('#project6').toggle();">A model inspection/visualization tool for Mozaik.</a>   
    <small id="project6"  class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations.
        The [model of primary visual cortex](/projects.html) developed in our lab, and implemented in Mozaik, has a complex connectivity structure. 
        Although there are various tests that the connectivity has been realized as expected, currently, there is no easy way to 
        visualize the network spatial structure and connectivity in [Mozaik](https://github.com/antolikjan/mozaik). The aim of this project is to develop a 
        model inspection and visualization tool, for Mozaik, possibly building on existing tools such as [ConnPlotter](http://arken.umb.no/~plesser/software.html), [Moogli](http://moose.ncbs.res.in/moogli/), and [NeurAnim](http://software.incf.org/software/neuranim).
    </small>

* <a href="javascript:void(0)" onclick="$('#project8').toggle();">Sumatra integration with Mozaik.</a>    
    <small id="project8" class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations.
        <a href="http://neuralensemble.org/sumatra/">Sumatra</a> is a tool for provenance tracking. Sumatra shares several features with Mozaik,  but it also 
        posses features that would enhance the Mozaik workflow. The goal of this project is to integrate Sumatra with Mozaik, and 
        remove overlapping features from Mozaik and delegating them to Sumatra, in line with long term goal of outsourcing 
        as much functionality from Mozaik to dedicated tools. This project is suitable for students with interest in Neuroinformatics
        and moderate skills in Python and versioning systems. 
    </small> 



#### Web development projects

* <a href="javascript:void(0)" onclick="$('#project12').toggle();">Open Vision project.</a>    
    <small id="project12" class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations. Inspired by the [OpenWorm](http://www.openworm.org)
	initiative, this project strives to bring neural based modelling of vision to the public. It will seek to engage the cognitive sciences enthusiast community into
	coordinate effort to build a comprehensive model of early and higher vision. We envision multiple phases of the project: <br>
	(1) Build a server running mozaik based V1 model and serve it on the new Open Vision website. The website will allow any member of public to submit a video and receive back the responses of selected model cells.<br>
	(2) Develop a web frontend to the Mozaik toolkit and use it to expand the Open Vision website to allow full configuration of the served model. Publish more models and experimental protocols already develop in our group. <br>
	(3) Expand upon 1 and 2 to build full open science platform similar to OpenWorm project, and build striving community around it.
    </small> 

* <a href="javascript:void(0)" onclick="$('#project4').toggle();">Graphical user interface for Mozaik datastore and analysis.</a>    
    <small id="project4" class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations.
        Mozaik automatically records data from simulations, annotates it with metadata regarding experimental context, and stores
        them in an internal data-store. An query based interface allows analysis and visualization modules to efficiently navigate
        through the stored data based on the attached metadata. Currently, Mozaik offers only programatic API to perform these interactions
        with data-store. The goal of this project would be to write a HTML based graphical user interface frontend, to the Mozaik data-store, that will
        allow users to conveniently and interactively navigate and select data from the data-store and subsequently execute on them anaysis and
        visualization routines from Mozaik libraries.      
    </small> 

* <a href="javascript:void(0)" onclick="$('#project7').toggle();">Deployment of Mozaik on a HPC platrform.</a>   
    <small id="project7" class="studentprojectlist" style="display: none;">
        [Mozaik](https://github.com/antolikjan/mozaik) is a an automated workflow for large-scale neural simulations.
        Mozaik depends on a moderate software stack including [PyNN](http://neuralensemble.org/PyNN/) as a simulator independent
        model specification language, and [Nest](http://www.nest-initiative.org/) as the simulator of choice in our projects.
        Currently we deploy Mozaik (together with the software stack) on a local cluster, however already at this relatively 
        small scale we are aware of number of inefficiencies in terms of its performance in the parallel environment. Furthermore, in future we would like 
        to deploy Mozaik on a large-scale High Performance Computing (HPC) platform such as [ADA](http://www.idris.fr/ada/). The goal of this project is to test and optimize Mozaik and it's underlying
        software stack to run efficiently on the local cluster, and subsequently scale it up to a large-scale HPC platform.
        This project is suitable for students with experience and interest in parallel programming and HPC.
    </small>


