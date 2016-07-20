# datasets-for-VANET
There are a number of datasets with traces for VANET, some datasets are generated based on simulations of real cities while others are generated based on specific parameters.

The datastes are:

### - 32: this dataset is generated from a simulation using SUMO with a maximum of 32 neighboring cars.
### - 64: this dataset is generated from a simulation using SUMO with a maximum of 64 neighboring cars.
### - 128: this dataset is generated from a simulation using SUMO with a maximum of 128 neighboring cars.
### - Bologna: this dataset is generated from a simulation of the Bologna city in Italy.
### - Erlangen: this dataset is generated from a simulation of the Erlangen city in Germany.

Every dataset folder have the following files:

- filename_disc.csv: this file contains all traces

All datasets have the following fields:

- Start time: time in seconds when the request arrives.
- End time: time in seconds when the request is done.
- Time Period: end time - start time
- Packets: number of packets required by this request.
- Rate: number of packets divided by time period, packets per second
- Sender Stopping Distance: in meters.
- Receiver Stopping Distance: in meters.
- Actual Distance: distance in meters between sender and receiver.
- Severity: severity of the request.
