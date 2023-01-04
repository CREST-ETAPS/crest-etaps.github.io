## Keynote
<a href="https://www.cs.cornell.edu/home/halpern/"><b>Joseph Halpern</b></a>, Cornell University, US  <br><br>
<b>Title:</b> A Causal Analysis of Harm <br>
<b>Abstract:</b> It has proved notoriously difficult to define harm.  Indeed, it has been
claimed that the notion of harm is a "Frankensteinian jumble" that
should be replaced by other well-behaved notions.    On the other hand,
harm has become increasingly important as concerns about the potential harms
that may be caused by AI systems grow.  Indeed, the European Union's
draft AI act mentions "harm" over 25 times and points out that, given its
crucial role, it must be defined carefully.<br>

I start by defining a qualitative notion of harm that
uses causal models and is based on a well-known definition of actual
causality.  The key features of the definition
are that it is based on contrastive causation
and uses a default utility to which the utility of actual outcomes
is compared.  I show that our definition is able to handle
the  problematic examples from the literature.
I extend the definition to a quantitative notion of harm, first in the case
of a single individual, and then for groups of individuals.
I show that the ``obvious'' way
of doing this (just taking the expected harm for an individual and
then summing the expected harm over all individuals) can lead to
counterintuitive or inappropriate answers, and discuss alternatives,
drawing on work from the decision-theory literature.<br>

This is joint work with <a href="https://sanderbeckers.github.io/website/about/">Sander Beckers</a> and <a href="https://www.hanachockler.com">Hana Chockler</a>.

## Invited Talks
<a href="https://www.bell-labs.com/about/researcher-profiles/armen-aghasaryan/#gref"><b>Armen Aghasaryan</b></a>, Nokia Bell Labs, France<br><br>
<b>Title:</b> Challenges and Opportunities for Causal Modeling of (Telco) Networks <br>
<b>Abstract:</b> Networks such as modern telecommunications networks or distributed embedded systems are permanently monitored to allow identification of failure situations; thousands of new data points reflecting the system state changes are generated every minute. In networks, faults propagate driven by local and remote dependencies, which makes it challenging to distinguish causes from effects among the thousands of highly correlated alerts. A timely identification and root cause analysis (RCA) of the origins of performance issues is necessary for executing the appropriate corrective actions and preventing their further propagation. Today’s AI/ML-based approaches teach the machine to associate patterns to specific meaning. This approach fails when the possibilities to learn are too many, and there is not enough data evidence to generalize over the unobserved possibilities. True machine intelligence must be built based on the ability to reason on why it is observing a specific phenomenon. To allow understanding the current situation and taking the most appropriate decisions, one needs to focus on causally relevant aspects of the information flow.
 
Identifying the cause-and-effect relationships from data is a harder problem than identifying merely the associations. In our research we address several fundamental challenges that underpin the applicability of causal modelling in real systems. Data quality and appropriate selection of relevant variables are essential for causal discovery to provide meaningful findings. We address this challenge by carefully examining the problem specifics in each application domain. In the telecom field, the large scale and partial observability of the system need to be considered while learning causal models from data. Partial observability namely relates to information hiding across vertical layers of the network or to partial visibility of the end-to-end service chain due to administrative boundaries or technical limitations of the monitoring system. Furthermore, faults and anomalies are rare events which imposes an additional challenge for causal inference with highly imbalanced datasets. Finally, creation of data generating models and digital twins that allow to mimic robustly the focused behavior of the real system is another challenge that we address in our research. Such a solution will allow to build synthetic datasets with a known ground truth (causal relationships) for development and validation of causal discovery algorithms. With digital twins, we will be able to emulate realistic (but not yet observed) what-if scenarios for fault resilience or optimal network policy design.<br><br>
 

<a href="https://www.hanachockler.com"><b>Hana Chockler</b></a>, King's College London, UK  <br><br>
<b>Title:</b> Causality and learning in software engineering <br>
<b>Abstract:</b> In this talk I will look at the connections between causality and learning on one side, and software engineering on the other side. I will introduce the relevant concepts and discuss how causality and learning can help to improve the quality of systems and reduce the amount of human effort in designing and verifying systems. I will (briefly) introduce the theory of actual causality as defined by Halpern and Pearl. This theory turns out to be extremely useful in various areas of computer science due to a good match between the results it produces and our intuition. I will illustrate the definitions by examples from formal verification. I will also argue that active learning can be viewed as a type of causal discovery. 
