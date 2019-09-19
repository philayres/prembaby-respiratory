# Premature Baby Neonatal Resuscitation

## Flow measurements to detect resuscitation activity and cycle period

The notebook [Repiration Frequence](resp_frequency.ipynb) attempts to provide robust and repeatable detection of mask ventilation activity, and measurement of the flow cycle period (the time between the start of each ventilation cycle) and some simple statistical analysis of the active data.

The idea is that this model can easily load datasets and deliver some attributes of the ventilation activity, which could be compared against features of the baby to identify potential correlations that indicate good and bad outcomes.

The aim was to produce a mean so of measurement that could eventually be used in real time, looking at a limited set of trailing data, rather than relying on a complete dataset.
