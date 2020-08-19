# logging
DUNE DAQ logging package

This package is mainly based on ERS and secondarily based on TRACE.
One link to ERS information can be found [here](https://atlas-tdaq-monitoring.web.cern.ch/OH/refman/ERSHowTo.html).
One link to TRACE information can be found [here](https://cdcvs.fnal.gov/redmine/projects/trace/wiki).
ERS provides:
- Assertion Macros
- Logging Macros<code>*</code>
- Macros for declaring Custom Issues

<code>*</code> TRACE provides high-speed dynamically activated debug logging and is integrated with the ERS logging; new macros are defined.

Users should be able to use the Assertion Macros from ERS and also declare Custom Issues. The issues can be used in logging and exception processing.

For logging, six streamer macros are provided:
1. LOG_FATAL()
2. LOG_ERROR()
3. LOG_WARNING()
4. LOG_INFO()
5. LOG_LOG()
6. LOG_DEBUG(lvl)

