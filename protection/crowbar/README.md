# Crowbar circuit

This circuit is used as a protection circuit to prevent overvoltage from
a power supply from damaging other components in the circuit. It
utilizes a zenner diode in order to detect the overvoltage and an SCR
(thyristor) to create a short circuit. A TRIAC could also be used in the
place of an SCR. This should then activate the current limiting features
of the power supply or failing that, a fuse or circuit breaker. Once
this circuit is triggered, the only way to reset it is to power down the
circuit before powering it back up again, thus resetting the SCR in the
process.

# Further reading

https://en.wikipedia.org/wiki/Crowbar_(circuit)