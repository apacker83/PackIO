![PackIO Main Window](https://s3.amazonaws.com/webimagespacker/packio.png)
The software is useful for any experiment requiring acquisition and generation of data and can be triggered in several modes.

During graduate school, I was making electrophysiological recordings and trying to synchronize various pieces of equipment (cameras, lasers, galvanometers, etc.). I found no software that was up to the task so I began a project to develop an uber-system capable of performing any data acquisition or generation operation that could be completed with the National Instruments DAQ hardware in use at the Yuste lab at the time.  I jokingly referred to the project as "PackIO", a combination of my name and IO, as in input/output, as the software is supposed to be able to take any input or generate any output in any synchronized fashion. The name stuck and now PackIO is in use by members of [Rafael Yuste's laboratory](http://www.columbia.edu/cu/biology/faculty/yuste/), [Jason Maclean's laboratory](http://www.macleanlab.com/), [Roberto Araya's laboratory](http://neurosciences.umontreal.ca/recherche/les-chercheurs/roberto-araya/), and I continue to use PackIO in [Michael Hausser's laboratory](http://www.dendrites.org/).

## Quick Install
1. Download and install ([32-bit](http://www.ni.com/download/labview-run-time-engine-2014/4887/en/) or [64-bit](http://www.ni.com/download/labview-run-time-engine-2014/4889/en/)) LabVIEW Runtime Engine (free).
2. Download and install [DAQmx drivers](http://www.ni.com/dataacquisition/nidaqmx) (free). 
3. Download and run [32-bit](https://github.com/apacker83/PackIO/releases/download/v273/PackIO_v273_LVRT2014_x86.exe) or [64-bit](https://github.com/apacker83/PackIO/releases/download/v273/PackIO_v273_LVRT2014_x64.exe) PackIO!

## Documentation
Please read the [Github wiki](https://github.com/apacker83/PackIO/wiki).

## Compatible hardware
Most National Instruments DAQ cards should work.  The following cards are known to work:
* PCIe-6343
* PCI-6259
* PCI-6052e
* PCI-6711
* PCI-6713
* PCI-6733 
* USB-6009
* USB-6211
* USB-6343
* USB-6251

## Please cite the software
Packer, A.M. Understanding the nervous system as an information processing machine: dense, nonspecific, canonical microcircuit architecture of inhibition in neocortex and a neural circuit for angular velocity computation. PhD thesis, Columbia University (2011).  Software available from www.packio.org.

## Contributors
Thank you to Rafael Yuste and all of the early beta testers in the Yuste lab. Mor Dar contributed some features to seal test and Carmen F. Fisac contributed the auto-incrementer available in version 273.

## References

### 2015
Packer AM, Russell L, Dalgleish HWP, Häusser M (2015) Simultaneous all-optical targeted manipulation and recording of neural circuit activity with cellular resolution in vivo. Nature Methods 12:140-146.
[LINK](http://www.nature.com/nmeth/journal/v12/n2/full/nmeth.3217.html)

### 2014

Araya R, Vogels TP, Yuste R (2014) Activity-dependent dendritic spine neck changes are correlated with synaptic strength. PNAS 111(28):E2895-904.
[LINK](http://www.pnas.org/content/111/28/E2895.long)

Quirin, S, Jackson S, Peterka DS, Yuste R (2014) Simultaneous imaging of neural activity in three dimensions. Front Neural Circuits 8:29.
[LINK](http://journal.frontiersin.org/article/10.3389/fncir.2014.00029/full)

### 2013

Araya R, Andino-Pavlovsky V, Yuste R, Etchenique R (2013) Two-photon optical interrogation of individual dendritic spines with caged dopamine. ACS Chem Neurosci. 4(8):1163-7.
[LINK](http://pubs.acs.org/doi/abs/10.1021/cn4000692)

Sippy T, Yuste R (2013) Decorrelating action of inhibition in neocortical networks. J Neurosci. 33(23):9813-30.
[LINK](http://www.jneurosci.org/content/33/23/9813.long)

Packer AM, McConnell DJ, Fino E, Yuste R (2013) Axo-dendritic overlap and laminar projection can explain interneuron connectivity to pyramidal cells. Cerebral Cortex 23(12):2790-2802. *Selected for cover
[LINK](http://cercor.oxfordjournals.org/content/23/12/2790.long)

### 2012

Packer AM, Peterka DS, Hirtz JJ, Prakash R, Deisseroth K, Yuste R (2012) Two-photon optogenetics of dendritic spines and neural circuits. Nature Methods 9:1202-1205.
[LINK](http://www.nature.com/nmeth/journal/v9/n12/full/nmeth.2249.html)

### 2011

Poskanzer KE, Yuste R (2011) Astrocytic regulation of cortical UP states. Proc Natl Acad Sci U S A. 108(45):18453-8. 
[LINK](http://www.pnas.org/content/108/45/18453.long)

Woodruff AR, McGarry LM, Vogels TP, Inan M, Anderson SA, Yuste R (2011) State-dependent function of neocortical chandelier cells. J Neurosci. 2011 
[LINK](http://www.jneurosci.org/content/31/49/17872.long)

Fino E, Yuste R. (2011) Dense inhibitory connectivity in neocortex. Neuron 69(6):1188-203.
[LINK](http://www.sciencedirect.com/science/article/pii/S0896627311001231)

Packer AM, Yuste R (2011) Dense, unspecific connectivity of neocortical parvalbumin-positive interneurons: a canonical microcircuit for inhibition? Journal of Neuroscience 31(37):13260-13271. *Selected for cover
[LINK](http://www.jneurosci.org/content/31/37/13260.long)

Ahmadian Y, Packer AM, Yuste R, Paninski L (2011) Designing optimal stimuli to control neuronal spike timing. J. Neurophys. 106(2):1038-1053.
[LINK](http://jn.physiology.org/content/106/2/1038.long)

### 2010

Watson BO, Nikolenko V, Araya R, Peterka DS, Woodruff A, Yuste R (2010) Two-photon microscopy with diffractive optical elements and spatial light modulators. Front Neurosci. 29.
[LINK](http://journal.frontiersin.org/article/10.3389/fnins.2010.00029/abstract)

Vogelstein J, Packer AM, Machado T, Sippy T, Babadi B, Yuste R, Paninski L (2010) Fast non-negative deconvolution for spike train inference from population calcium imaging. J. Neurophys. 104(6):3691-704.
[LINK](http://jn.physiology.org/content/104/6/3691.long)

McGarry LM, Packer AM, Fino E, Nikolenko V, Sippy T, Yuste R (2010) Quantitative classification of somatostatin-positive neocortical interneurons identifies three interneuron subtypes. Frontiers in Neural Circuits 4:12.
[LINK](http://journal.frontiersin.org/article/10.3389/fncir.2010.00012/abstract)

### 2009

Woodruff A, Xu Q, Anderson SA, Yuste R (2009) Depolarizing effect of neocortical chandelier neurons. Front Neural Circuits Oct 20;3:15.
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.015.2009/full)

Vogelstein J, Watson B, Packer AM, Yuste R, Jedynak B, Paninski L (2009) Spike inference from calcium imaging using sequential Monte Carlo methods. Biophysical Journal 97:636-55.
[LINK](http://www.sciencedirect.com/science/article/pii/S0006349509003117)

Watson BO, Nikolenko V, Yuste R (2009) Two-photon imaging with diffractive optical elements. Front Neural Circuits. 3:6.
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.006.2009/full)

Fino E, Araya R, Peterka DS, Salierno M, Etchenique R, Yuste R (2009) RuBi-Glutamate: two-photon and visible-light photoactivation of neurons and dendritic spines. Front Neural Circuits 3(2).
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.002.2009/full)

### 2008

Nikolenko V, Watson BO, Araya R, Woodruff A, Peterka DS, Yuste R (2008) SLM microscopy: scanless two-photon imaging and photostimulation with spatial light modulators. Front Neural Circuits 2(5).
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.005.2008/full)

Watson BO, Maclean JN, Yuste R (2008) UP States Protect Ongoing Cortical Activity from Thalamic Inputs. PLOS One 3(12).
[LINK](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0003971#s4)

### 2007

Nikolenko V, Poskanzer KE, Yuste R (2007) Two-photon photostimulation and imaging of neural circuits. Nature Methods 4(11) :943-950.
[LINK](http://www.nature.com/nmeth/journal/v4/n11/full/nmeth1105.html)
