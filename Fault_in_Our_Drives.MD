# Fault in Our Drives
As cheeky as it may sound, electrical drives face faults as a result of which a plant wide shutdown may or may not take place. That all
depends on the kind of fault we are dealing with. Whether its a severe one or minor deviation from regular behaviour that maybe on the
account of normal fluctuations. How good would it be if we knew what was going to happen well before it happens? Prognosis? Sounds familiar
with other things that are normally discussed? Weather forecasting, [load forecasting](www.github.com/ansh103/load_forecasting_project) and so much more. Fault Prognosis in electrical machines and drives is an active area of research for students and professors alike. There has been significant development in ways to approach the problem. With advent of Deep Learning, the ways are becoming more sophisticated and provide more accurate and reliable(depends on the error we are getting) results. So lets dive into the basics of all fault diagnosis for now before dealing with various methods to approach the problem. 
## Objectives of Fault Diagnosis
_At the basic level_:
* Detect abnormal operation of a subsystem or system 
* Determine which component is failing 
* Estimate how it is failing, and how severe the fault is.  

_Next Steps_:
* Evaluate the information of the type, severity and confidence of the fault  determination
* Schedule maintenance, based on fault severity and operating  requirements and conditions
* Alternatively, employ redundancies.  

## What does it take to identify?
Diagnosis of a non‐catastrophic fault requires:
* a data or a physics based model, based on the fault characteristics, or  alternatively a priori training, based on observations of known faults.
* a method to extract a limited number of features from observations,
* a classification, i.e. a signal processing method to make determinations from these.  

## Types of Faults
* **Bearing faults**: affected by wear, temperature, loading, environment 
* **Insulation**: temperature, overvoltage, initial manufacturing quality
* **Connections**: welding, crimping, corrosion
* **Rotor eccentricity**: manufacturing, loading, wear
* **Rotor bar breakage in induction motors**: manufacturing problems, starting  cycles
* **Permanent magnet demagnetization**: load, temperature, controller error, noise 
* **Gears** 
* **Sensor failure** (e.g. rotor position sensor, current sensor).
* **Power electronics components**: switches, capacitors, gate drivers
