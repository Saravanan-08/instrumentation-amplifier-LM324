# instrumentation-amplifier-LM324

This report details the design and principles behind an instrumentation amplifier built using the LM324 op-amp. Known for its cost-effectiveness and reliability, the LM324 is well-suited for amplifying small differential signals with high precision. This design focuses on achieving accurate signal processing through high input impedance and effective common-mode rejection, critical features that enhance measurement accuracy in various applications

## A Glance at the Instrumentation Ampifier LM324

An instrumentation amplifier using the LM324 op-amp is a differential amplifier setup designed for precise measurement of small signals amidst noise, commonly used in medical equipment, strain gauges, and sensor applications. The LM324, a quad op-amp, operates on a single supply (3V–32V), making it ideal for low-power applications. The typical design uses three op-amps: two as input buffers for high input impedance and one for differential gain, which amplifies the difference between inputs while rejecting common-mode noise. This setup provides high common-mode rejection ratio (CMRR) and adjustable gain, allowing accurate signal measurement even in electrically noisy environments.

## Block Diagram of the Instrumentation Ampifier
