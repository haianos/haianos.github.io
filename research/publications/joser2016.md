---
layout: page
title: Hierarchical Hypergraphs for Knowledge-centric Robot Systems -  a Composable Structural Meta Model and its Domain Specific Language NPC4
image:
  feature: abstract-5.jpg
comments: false
modified: 2016-12-22
---

# Abstract

<p align="justify">
Many robotics applications rely on graph models in one form or another: perception via probabilistic graphical models such as Bayesian Networks or Factor Graphs; control diagrams and other computational ``function block'' models; software component architectures; Finite State Machines; kinematics and dynamics of actuated mechanical structures; world models and maps; knowledge relationships as ``RDF triples''; etc.In traditional graphs, each edge connects just two nodes, and graphs are ``flat'', that is, a node does not contain other nodes.
This paper advocates the research hypothesis that hierarchical hypergraphs are a better structural meta model: (i) an edge can connect more than two nodes, (ii) the attachment between nodes and edges is made explicit in the form of ``ports'' to provide a uniquely identifiable view on a node's internal behaviour, and (iii) every node can in itself be another hierarchical hypergraph.These properties are encoded formally in a Domain Specific Language (or ``meta meta model''), called ``NPC4'', built with node, port, connector, and container as primitives, and contains and connects as relationships. The formal model of NPC4 is designed to maximally support its composability as a meta modelling language, for both the structural and behavioural parts of more concrete DSLs that can be built on top of it, each in a specific domain context.
NPC4 introduces a particular primitive, the container, to support  overlapping contexts. It targets the following major targets in knowledge-centric robotics systems: (i) various levels of abstraction in domain models, (ii) ``multiple inheritance'' from (or rather ``conformance to'') different knowledge domains, and (iii) connecting one or more domain DSLs to the same software infrastructure in which they all have to be ``activated''.
</p>

# Authors

  * Enea Scioni (University of Leuven, Belgium and University of Ferrara, Italy)
  * Nico Huebel (University of Leuven)
  * Sebastian Blumenthal (University of Leuven)
  * Azamat Shakhimardanov (University of Leuven)
  * Markus Klotzbuecher (University of Leuven)
  * Hugo Garcia (University of Leuven)
  * Herman Bruyninckx (University of Leuven, Belgium and Technical University of Eindhoven, the Netherlands)

# Paper

The paper is published on JOSER (Journal of Software Engineering for Robotics), publicly available [here](http://joser.unibg.it/index.php?journal=joser&page=article&op=view&path%5B%5D=99&path%5B%5D=36).