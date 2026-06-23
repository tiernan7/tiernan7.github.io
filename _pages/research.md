---
layout: page
title: research
permalink: /research/
description: Research in molecular programming, scientific discovery, experimental optimization, and automation.
nav: true
nav_order: 2
---

> ## When confronted with a system that is high-dimensional, partially observable, difficult to model, impossible to optimize along all axes simultaneously, and expensive to explore experimentally, how do we discover the principles that make understanding and engineering systematic rather than ad hoc?

Many important scientific and engineering problems are difficult not simply because their design spaces are large, but because consequential behavior emerges from interacting processes that are incompletely observed and imperfectly modeled. The relevant variables, mechanisms, measurements, and objectives may themselves be only partially known, while experimentation is costly enough that the process by which we learn and design must itself be engineered.

We must often decide what to measure before we know which distinctions matter, construct models before we know the right representation, and design interventions that both reveal how a system works and improve what it can do.

My research examines how representations, inference, experimental design, optimization, and automation can be coordinated under these conditions. My goal is to develop research processes in which **discovery produces new engineering capability, engineering produces new means of discovery, and each cycle makes the next less dependent on intuition and trial and error**.

## Discovery and engineering as a reinforcing cycle

I do not view scientific discovery and engineering as separate stages in a linear pipeline. Mechanistic understanding enables new technologies, but engineered systems also provide new ways to perturb, measure, and understand the phenomena from which they arise.

An intervention can simultaneously test a hypothesis, expose a design principle, and establish a new technological capability. New capabilities then expand what can be observed and learned, beginning another cycle of discovery and engineering.

<!-- Add unifying research figure here. -->

My work approaches this cycle through four connected questions:

1. **Representation:** What abstractions expose the structure needed for reasoning and design?
2. **Inference:** What can be learned from the available measurements, and what remains unobservable?
3. **Intervention:** Which experiments distinguish mechanisms while moving the system toward useful behavior?
4. **Process:** How can optimization and automation make successive cycles of discovery more reliable, efficient, and cumulative?

## Research directions

The following directions are different manifestations of this shared research program, spanning molecular systems, computational inference, biological function, and the design of scientific processes.

### Robust molecular programming

My doctoral research at the University of Washington focused on making DNA strand-displacement systems more robust and systematically engineerable.

I developed computational and experimental approaches spanning multi-objective design optimization, circuit architecture, sequence-level design, and chemically expanded genetic alphabets. These systems must balance kinetics, leak, crosstalk, physical realizability, sequence constraints, and behavior across changing contexts. Because these objectives interact and frequently conflict, scalable design requires more than optimizing a single metric.

DNA strand displacement provided a concrete physical system in which to investigate a broader problem: how can reliable design principles emerge when exhaustive models are unavailable, objectives compete, and system-level behavior arises from many coupled molecular interactions?

<!-- Add molecular programming project image here. -->

### Observability and learnability

In structure learning, I am interested in distinguishing what is computationally difficult to infer from what is impossible to infer from the available observations.

A system may contain meaningful structure while its measurement process erases precisely the distinctions needed to recover it. This raises questions that precede model fitting: Which properties are identifiable? What interventions would make hidden structure observable? When does apparent algorithmic failure instead reflect insufficient information? What claims can the evidence actually support?

Untangling observability from learnability is necessary for methods that know not only how to infer a model, but when the available data cannot determine one and what experiment should come next.

<!-- Add observability or structure-learning figure here. -->

### Mechanism-forward functional bioinformatics

Modern biological research generates enormous quantities of descriptive data, but converting associations into experimentally grounded accounts of function remains difficult.

I am interested in synthetic and mechanism-forward approaches that connect computational inference to interventions capable of distinguishing among biological explanations. Candidate mechanisms can be embodied in designed sequences, perturbations, or molecular systems and evaluated experimentally.

In this framework, engineering is also a mode of discovery. Successful interventions provide evidence about natural biological function while revealing principles for constructing new functions.

<!-- Add functional bioinformatics project image here. -->

### Experimental optimization and scientific automation

Scientific automation is not merely a means of performing more experiments. Its larger promise is the ability to redesign the process by which experiments are selected, interpreted, and connected across time.

I am interested in integrating robust experimental infrastructure with mechanistic models, principled design of experiments, active learning, and multi-objective optimization. A useful automated platform should identify which uncertainties matter, choose experiments that are informative as well as performant, recognize when its models or objectives are inadequate, and preserve enough context for knowledge to accumulate across experimental campaigns.

This matters both scientifically and economically. In industrial research and startups, an incorrect experimental trajectory can consume months of labor and a substantial portion of a company's runway. Reliable automation combined with model-based experimental design can expose failing assumptions earlier, prevent expensive commitment to the wrong mechanism or design space, and turn experimental learning into a cumulative organizational capability.

<!-- Add experimental automation or optimization figure here. -->