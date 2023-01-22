![PackIO Main Window](https://s3.amazonaws.com/webimagespacker/packio.png)

The software is useful for any experiment requiring acquisition and generation of data and can be triggered in several modes.

During graduate school, I was making electrophysiological recordings and trying to synchronize various pieces of equipment (cameras, lasers, galvanometers, etc.). I found no software that was up to the task so I began a project to develop an uber-system capable of performing any data acquisition or generation operation that could be completed with the National Instruments DAQ hardware in use at the Yuste lab at the time.  I jokingly referred to the project as "PackIO", a combination of my name and IO, as in input/output, as the software is supposed to be able to take any input or generate any output in any synchronized fashion. The name stuck and now PackIO is in use by members of [Rafael Yuste's laboratory](http://www.columbia.edu/cu/biology/faculty/yuste/), [Jason Maclean's laboratory](http://www.macleanlab.com/), [Roberto Araya's laboratory](http://neurosciences.umontreal.ca/recherche/les-chercheurs/roberto-araya/), and I continue to use PackIO in [Michael Hausser's laboratory](http://www.dendrites.org/).

## Quick Install
1. Download and install ([32-bit](http://www.ni.com/download/labview-run-time-engine-2014/4887/en/) or [64-bit](http://www.ni.com/download/labview-run-time-engine-2014/4889/en/)) LabVIEW Runtime Engine (free).
2. Download and install [DAQmx drivers](http://www.ni.com/dataacquisition/nidaqmx) (free). 
3. Download and run [32-bit](https://github.com/apacker83/PackIO/releases/download/v273/PackIO_v273_LVRT2014_x86.exe) or [64-bit](https://github.com/apacker83/PackIO/releases/download/v273/PackIO_v273_LVRT2014_x64.exe) PackIO!
4. See wiki on [How to view or import data created by PackIO](https://github.com/apacker83/PackIO/wiki/How-to-view-or-import-data-created-by-PackIO).

## Documentation
Please read the [Github wiki](https://github.com/apacker83/PackIO/wiki).

## Licensing
PackIO and EphysViewer are released under the GNU General Public License.

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
Watson BO, Yuste R, Packer AM (2016) PackIO and EphysViewer: software tools for acquisition and analysis of neuroscience data. bioRxiv http://dx.doi.org/10.1101/054080 Software available from www.packio.org.

## Contributors
Thank you to Rafael Yuste and all of the early beta testers in the Yuste lab. Mor Dar contributed some features to seal test and Carmen F. Fisac contributed the auto-incrementer available in version 273.

## References

### 2023

49. Shah PT, Valiante TA, Packer AM (2023) All-optical interrogation of excitability during seizure propagation reveals high local inhibition amidst baseline excitability. bioRxiv 524224 [LINK] (https://doi.org/10.1101/2023.01.16.524224)
### 2022

48: Shelton AM, Oliver DK, Grimstvedt JS, Lazarte IP, Kapoor I, Swann JA, Ashcroft CA, Williams SN, Conway N, Robinson A, Kentros CG, Witter MP, Butt SJB, Packer AM (2022) Single neurons and networks in the claustrum integrate input from widespread cortical sources. bioRxiv 490864 [LINK](https://doi.org/10.1101/2022.05.06.490864)

### 2021

47: Bando Y, Wenzel M, Yuste R (2021) Simultaneous two-photon imaging of action potentials and subthreshold inputs in vivo. Nature Communications [LINK](https://doi.org/10.1038/s41467-021-27444-9)

46: Rowland JM, Van der Plas TL, Loidolt M, Lees RM, Keeling J, Dehning J, Akam T, Priesemann V, Packer AM (2021) Perception and propagation of activity through the cortical hierarchy is determined by neural variability. bioRxiv 474343 [LINK](https://doi.org/10.1101/2021.12.28.474343)

45: Russell LE, Dalgleish HWP, Nutbrown R, Gauld OM, Herrmann D, Fişek M, Packer AM, Häusser M (2021) All-optical interrogation of neural circuits in behaving mice bioRxiv 450430 [LINK](https://doi.org/10.1101/2021.06.29.450430)

### 2020

44: Dalgleish HWP, Russell LE, Packer AM, Roth A, Gauld OM, Greenstreet F, Thompson EJ, Häusser M (2020) How many neurons are sufficient for perception of cortical activity? eLife [LINK](https://doi.org/10.7554/eLife.58889)

### 2019

43: Russell LE, Yang Z, Pei LT, Fisek M, Packer AM, Dalgleish HWP, Chettih S, Harvey CD, Häusser M (2019) The influence of visual cortex on perception is modulated by behavioural state bioRxiv 706010 [LINK](https://doi.org/10.1101/706010)

42: Bando Y, Sakamoto M, Kim S, Ayzenshtat I, Yuste R (2019) Comparative evaluation of genetically encoded voltage indicators. Cell Reports [LINK](https://doi.org/10.1016/j.celrep.2018.12.088)

41: Kostadinov D, Beau M, Blanco-Pozo M, Häusser M (2019) Predictive and reactive reward signals conveyed by climbing fiber inputs to cerebellar Purkinje cells. Nature Neuroscience [LINK](https://www.nature.com/articles/s41593-019-0381-8)

40: Szymanski J, Yuste R (2019) Mapping the whole-body muscle activity of Hydra vulgaris. Current Biology [LINK](https://doi.org/10.1016/j.cub.2019.05.012)

### 2018

39: Izquierdo-Serra M, Hirtz JJ, Shababo B, Yuste R (2019) Two-photon optogenetic mapping of excitatory synaptic connectivity and strength [LINK](https://doi.org/10.1016/j.isci.2018.09.008)

38: Zhang Z, Russell LE, Packer AM, Gauld OM, Häusser M (2018) Closed-loop all-optical interrogation of neural circuits in vivo Nature Methods [LINK](https://doi.org/10.1038/s41592-018-0183-z)

### 2017

37: Kwon T, Sakamoto M, Peterka DS, Yuste R (2017) Attenuation of Synaptic Potentials in Dendritic Spines. Cell Reports 20(5):1100-1110.
[LINK](https://doi.org/10.1016/j.celrep.2017.07.012)

36: Agetsuma M, Hamm JP, Tao K, Fujisawa S, Yuste R (2017) Parvalbumin-Positive Interneurons Regulate Neuronal Ensembles in Visual Cortex. Cerebral Cortex 1-15.
[LINK](https://doi.org/10.1093/cercor/bhx169)

35: Aitchison L, Russell L, Packer AM, Yan J, Castonguay P, Häusser M, Turaga SC (2017) Model-based Bayesian inference of neural activity and connectivity from all-optical interrogation of a neural circuit. Advances in Neural Information Processing Systems 3489-3498.
[LINK](http://papers.nips.cc/paper/6940-model-based-bayesian-inference-of-neural-activity-and-connectivity-from-all-optical-interrogation-of-a-neural-circuit)

34: Dupre D, Yuste R (2017) Non-overlapping Neural Networks in Hydra vulgaris. Current Biology 27:1085-1097.
[LINK](https://www.sciencedirect.com/science/article/pii/S0960982217302208)

### 2016

33: Jayant K, Hirtz JJ, Jen-La Plante I, Tsai DM, De Boer WDAM, Semonche A, Peterka DS, Owen JS, Sahin O, Shepard KL, Yuste R (2016) Targeted intracellular voltage recordings from dendritic spines using quantum-dot-coated nanopipettes. Nature Nanotechnology 12:335-342.
[LINK](https://www.nature.com/articles/nnano.2016.268)

32: Karnani MM, Jackson J, Ayzenshtat I, Tucciarone J, Manoocheri K, Snider WG, Yuste R (2016) Cooperative subnetworks of molecularly similar interneurons in mouse neocortex. Neuron 90:86-100.
[LINK](http://www.sciencedirect.com/science/article/pii/S0896627316001744)

31: Karnani MM, Jackson J, Ayzenshtat I, Sichani AH, Manoocheri K, Kim S, Yuste R (2016) Opening holes in the blanket of inhibition: localized lateral disinhibition by VIP interneurons. J Neurosci 36(12):3471-3480.
[LINK](http://www.jneurosci.org/content/36/12/3471.full)

### 2015

30: Packer AM, Russell LE, Dalgleish HWP, Häusser M (2015) Simultaneous all-optical targeted manipulation and recording of neural circuit activity with cellular resolution in vivo. Nature Methods 12:140-146.
[LINK](http://www.nature.com/nmeth/journal/v12/n2/full/nmeth.3217.html)

29: Sederberg AJ, Palmer SE, MacLean JN (2015) Decoding thalamic afferent input using microcircuit spiking activity. J Neurophysiol 113(7):2921-33. 
[LINK](http://jn.physiology.org/content/113/7/2921.long)

### 2014

28: Runfeldt MJ, Sadovsky AJ, MacLean JN (2014) Acetylcholine functionally reorganizes neocortical microcircuits. J Neurophysiol 112(5):1205-16.
[LINK](http://jn.physiology.org/content/112/5/1205.long)

27: Sadovsky AJ, MacLean JN (2014) Mouse visual neocortex supports multiple stereotyped patterns of microcircuit activity. J Neurosci 34(23):7769-77.
[LINK](http://www.jneurosci.org/content/34/23/7769.long)

26: Neubauer FB, Sederberg A, MacLean JN (2014) Local changes in neocortical circuit dynamics coincide with the spread of seizures to thalamus in a model of epilepsy. Front Neural Circuits 8:101.
[LINK](http://journal.frontiersin.org/article/10.3389/fncir.2014.00101/abstract)

25: Araya R, Vogels TP, Yuste R (2014) Activity-dependent dendritic spine neck changes are correlated with synaptic strength. PNAS 111(28):E2895-904.
[LINK](http://www.pnas.org/content/111/28/E2895.long)

24: Quirin, S, Jackson S, Peterka DS, Yuste R (2014) Simultaneous imaging of neural activity in three dimensions. Front Neural Circuits 8:29.
[LINK](http://journal.frontiersin.org/article/10.3389/fncir.2014.00029/full)

23: Izquierdo-Serra M, Gascón-Moya M, Hirtz JJ, Pittolo S, Poskanzer KE, Ferrer È, Alibés R, Busqué F, Yuste R, Hernando J, Gorostiza P (2014) Two-photon neuronal and astrocytic stimulation with azobenzene-based photoswitches. J Am Chem Soc 136(24):8693-701.
[LINK](http://pubs.acs.org/doi/abs/10.1021/ja5026326)

### 2013

22: Araya R, Andino-Pavlovsky V, Yuste R, Etchenique R (2013) Two-photon optical interrogation of individual dendritic spines with caged dopamine. ACS Chem Neurosci. 4(8):1163-7.
[LINK](http://pubs.acs.org/doi/abs/10.1021/cn4000692)

21: Sippy T, Yuste R (2013) Decorrelating action of inhibition in neocortical networks. J Neurosci. 33(23):9813-30.
[LINK](http://www.jneurosci.org/content/33/23/9813.long)

20: Packer AM, McConnell DJ, Fino E, Yuste R (2013) Axo-dendritic overlap and laminar projection can explain interneuron connectivity to pyramidal cells. Cerebral Cortex 23(12):2790-2802. *Selected for cover
[LINK](http://cercor.oxfordjournals.org/content/23/12/2790.long)

19: Sadovsky AJ, MacLean JN (2013) Scaling of topologically similar functional modules defines mouse primary auditory and somatosensory microcircuitry. J Neurosci.  Aug 28;33(35):14048-60, 14060a.
[LINK](www.jneurosci.org/content/33/35/14048.abstract)

18: Kruskal PB, Li L, MacLean JN (2013) Circuit reactivation dynamically regulates synaptic plasticity in neocortex. Nat Commun 4:2574.
[LINK](http://www.nature.com/ncomms/2013/131010/ncomms3574/full/ncomms3574.html)

### 2012

17: Packer AM, Peterka DS, Hirtz JJ, Prakash R, Deisseroth K, Yuste R (2012) Two-photon optogenetics of dendritic spines and neural circuits. Nature Methods 9:1202-1205.
[LINK](http://www.nature.com/nmeth/journal/v9/n12/full/nmeth.2249.html)

### 2011

16: Poskanzer KE, Yuste R (2011) Astrocytic regulation of cortical UP states. Proc Natl Acad Sci U S A. 108(45):18453-8. 
[LINK](http://www.pnas.org/content/108/45/18453.long)

15: Woodruff AR, McGarry LM, Vogels TP, Inan M, Anderson SA, Yuste R (2011) State-dependent function of neocortical chandelier cells. J Neurosci. 2011 
[LINK](http://www.jneurosci.org/content/31/49/17872.long)

14: Fino E, Yuste R. (2011) Dense inhibitory connectivity in neocortex. Neuron 69(6):1188-203.
[LINK](http://www.sciencedirect.com/science/article/pii/S0896627311001231)

13: Packer AM, Yuste R (2011) Dense, unspecific connectivity of neocortical parvalbumin-positive interneurons: a canonical microcircuit for inhibition? Journal of Neuroscience 31(37):13260-13271. *Selected for cover
[LINK](http://www.jneurosci.org/content/31/37/13260.long)

12: Ahmadian Y, Packer AM, Yuste R, Paninski L (2011) Designing optimal stimuli to control neuronal spike timing. J. Neurophys. 106(2):1038-1053.
[LINK](http://jn.physiology.org/content/106/2/1038.long)

11: Sadovsky AJ, Kruskal PB, Kimmel JM, Ostmeyer J, Neubauer FB, MacLean JN (2011) Heuristically optimal path scanning for high-speed multiphoton circuit imaging. J Neurophysiol 106(3):1591-8.
[LINK](http://jn.physiology.org/content/106/3/1591.long)

### 2010

10: Watson BO, Nikolenko V, Araya R, Peterka DS, Woodruff A, Yuste R (2010) Two-photon microscopy with diffractive optical elements and spatial light modulators. Front Neurosci. 29.
[LINK](http://journal.frontiersin.org/article/10.3389/fnins.2010.00029/abstract)

9: Vogelstein J, Packer AM, Machado T, Sippy T, Babadi B, Yuste R, Paninski L (2010) Fast non-negative deconvolution for spike train inference from population calcium imaging. J. Neurophys. 104(6):3691-704.
[LINK](http://jn.physiology.org/content/104/6/3691.long)

8: McGarry LM, Packer AM, Fino E, Nikolenko V, Sippy T, Yuste R (2010) Quantitative classification of somatostatin-positive neocortical interneurons identifies three interneuron subtypes. Frontiers in Neural Circuits 4:12.
[LINK](http://journal.frontiersin.org/article/10.3389/fncir.2010.00012/abstract)

### 2009

7: Woodruff A, Xu Q, Anderson SA, Yuste R (2009) Depolarizing effect of neocortical chandelier neurons. Front Neural Circuits Oct 20;3:15.
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.015.2009/full)

6: Vogelstein J, Watson B, Packer AM, Yuste R, Jedynak B, Paninski L (2009) Spike inference from calcium imaging using sequential Monte Carlo methods. Biophysical Journal 97:636-55.
[LINK](http://www.sciencedirect.com/science/article/pii/S0006349509003117)

5: Watson BO, Nikolenko V, Yuste R (2009) Two-photon imaging with diffractive optical elements. Front Neural Circuits. 3:6.
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.006.2009/full)

4: Fino E, Araya R, Peterka DS, Salierno M, Etchenique R, Yuste R (2009) RuBi-Glutamate: two-photon and visible-light photoactivation of neurons and dendritic spines. Front Neural Circuits 3(2).
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.002.2009/full)

### 2008

3: Nikolenko V, Watson BO, Araya R, Woodruff A, Peterka DS, Yuste R (2008) SLM microscopy: scanless two-photon imaging and photostimulation with spatial light modulators. Front Neural Circuits 2(5).
[LINK](http://journal.frontiersin.org/article/10.3389/neuro.04.005.2008/full)

2: Watson BO, Maclean JN, Yuste R (2008) UP States Protect Ongoing Cortical Activity from Thalamic Inputs. PLOS One 3(12).
[LINK](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0003971#s4)

### 2007

1: Nikolenko V, Poskanzer KE, Yuste R (2007) Two-photon photostimulation and imaging of neural circuits. Nature Methods 4(11) :943-950.
[LINK](http://www.nature.com/nmeth/journal/v4/n11/full/nmeth1105.html)
