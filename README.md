# PackIO
![PackIO Main Window](https://s3.amazonaws.com/webimagespacker/packio.png)

During graduate school, I was making electrophysiological recordings and trying to synchronize various pieces of equipment (cameras, lasers, galvanometers, etc.). I found no software that was up to the task at the time so I began a project to develop an uber-system capable of performing any data acquisition or generation operation that could be completed with the National Instruments DAQ hardware in use at the Yuste lab at the time.  I jokingly referred to the project as "PackIO", a combination of my name and IO, as in input/output, because the software is meant to acquire any input or generate any output in any synchronized fashion. The name stuck and now PackIO is in use by members of [Rafael Yuste's laboratory](http://www.columbia.edu/cu/biology/faculty/yuste/), [Jason Maclean's laboratory](http://www.macleanlab.com/), [Roberto Araya's laboratory](http://neurosciences.umontreal.ca/recherche/les-chercheurs/roberto-araya/), and I continue to use PackIO in [Michael Hausser's laboratory](http://www.dendrites.org/).

### Requirements
This software requires a freely downloadable LabVIEW runtime engine ([32-bit](http://www.ni.com/download/labview-run-time-engine-2014/4887/en/) or [64-bit](http://www.ni.com/download/labview-run-time-engine-2014/4889/en/)) to run one of the downloadable [executables](https://github.com/apacker83/PackIO/releases).  [DAQmx](http://www.ni.com/dataacquisition/nidaqmx) drivers are required for the hardware. A full installation of LabVIEW is required to edit the source code (LLB files).

### Documentation
Please see the [wiki](https://github.com/apacker83/PackIO/wiki).
