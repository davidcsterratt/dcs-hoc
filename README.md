# David Sterratt's hoc library for NEURON

This is a library of hoc functions that I've found useful in my work
with NEURON in particular Sterratt et al (2012). I haven't used this
code actively for some time and it is largely undocumented. Please let
me know if you would like any explanation.

## PointProcessDistributor

Following
[this thread on the NEURON discussion forum](https://www.neuron.yale.edu/phpBB/viewtopic.php?f=8&t=2264),
the PointProcessDistributor.hoc file can be used to distribute point
processes on a morphology in NEURON. To run it, try
```
nrngui tests/test_PointProcessDistributor.hoc
```

## TreePlots

The TreePlot code can be useful for plotting quantities over dendritic
trees. Try:
```
nrngui tests/test_TreePlot.hoc
```

## References

* Sterratt, D. C., Groen, M. R., Meredith, R. M. and van Ooyen,
  A. (2012). ‘Spine calcium transients induced by synaptically-evoked
  action potentials can predict synapse location and establish
  synaptic democracy’. <a
  href="http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1002545">PLoS
  Computational Biology</a> 8(6): e1002545. <a
  href="http://dx.doi.org/10.1371/journal.pcbi.1002545">doi:10.1371/journal.pcbi.1002545</a>

<!--  LocalWords:  Sterratt's hoc Sterratt PointProcessDistributor
 -->
<!--  LocalWords:  nrngui TreePlots TreePlot Groen Ooyen href PLoS
 -->
