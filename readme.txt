Data Set Information:

This dataset was generated for use on 'Prediction of Motor Failure Time Using An Artificial Neural Network' project (DOI: 10.3390/s19194342). A cooler fan with weights on its blades was used to generate vibrations. To this fan cooler was attached an accelerometer to collect the vibration data. With this data, motor failure time predictions were made, using an artificial neural networks. To generate three distinct vibration scenarios, the weights were distributed in three different ways: 1) 'red' - normal configuration: two weight pieces positioned on neighboring blades; 2) 'blue' - perpendicular configuration: two weight pieces positioned on blades forming a 90Â° angle; 3) 'green' - opposite configuration: two weight pieces positioned on opposite blades. A schematic diagram can be seen in figure 3 of the paper.

Devices used:
Akasa AK-FN059 12cm Viper cooling fan (Generate the vibrations)
MMA8452Q accelerometer (Measure vibration)

Data collection method:
17 rotation speeds were set up, ranging from 20% to 100% of the cooler maximum speed at 5% intervals; for the three weight distribution configurations in the cooler blades. Note that the Akasa AK-FN059 cooler has 1900 rpm of max rotation speed.

The vibration measurements were collected at a frequency of 20 ms for 1 min for each percentage, generating 3000 records per speed. Thus, in total, 153,000 vibration records were collected from the simulation model.

Attribute Information:

There are 5 attributes in the dataset: wconfid,pctid,x,y and z.

wconfid: Weight Configuration ID (1 - 'red' - normal configuration; 2 - 'blue' - perpendicular configuration; 3 - 'green' - opposite configuration)
pctid: Cooler Fan RPM Speed Percentage ID (20 means 20%, and so on).
x: Accelerometer x value.
y: Accelerometer y value.
z: Accelerometer z value.

Relevant Papers:

Scalabrini Sampaio, Gustavo; Vallim Filho, Arnaldo R.d.A.; Santos da Silva, Leilton; Augusto da Silva, Leandro. 2019. Prediction of Motor Failure Time Using An Artificial Neural Network. Sensors 2019, 19, 4342. DOI: 10.3390/s19194342
