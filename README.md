<html>
<body>
<div style="color:#435987;
            border-style: solid;
            border-radius: 25px;
            border-color: #435987;
            padding-left: 10px">
       
<span style="color:#26488F; font-size:20px; font-weight: bold;">  Brief Description Predictive Maintenance </span><br>
    
This dataset reflects real predictive maintenance encountered in the industry with measurements from real equipment. The features description is taken directly from the dataset source. <br>    


<span style="font-weight: bold;"> The six features are: </span> <br>
<li>Type: the quality of the product, consisting of a letter L, M, or H. Meaning low, medium, and high, respectively. <br>
<li>Air temperature [K]: generated using a random walk process later normalized to a standard deviation of 2 K around 300 K.<br>
<li>Process temperature [K]: generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature<br> plus 10 K.<br>
<li>Rotational speed [rpm]: calculated from power of 2860 W, overlaid with a normally distributed noise.<br>
<li>Torque [Nm]: torque values are normally distributed around 40 Nm with an Ïƒ = 10 Nm and no negative values.<br>
<li>Tool wear [min]: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process.<br>
<br>

<span style="font-weight: bold;"> The targets are: </span> <br>
<li>Target: failure or no failure (to perform binary classification).<br>
<li>Failure Type: type of failure (to perform multiclass classification).<br>

<br>
It also includes the following information, which is not useful for building the models:<br>
<li>UID: unique identifier ranging from 1 to 10000.<br>
<li>ProductID: the id of the product.<br>
<br>

<span style="font-weight: bold;"> Dataset source: </span> https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification <br>
</p>
</div>

</body>
</html>