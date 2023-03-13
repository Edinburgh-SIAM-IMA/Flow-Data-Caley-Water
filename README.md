# Flow-Data-Caley-Water

## Project Description
Caley Water receives and utilises observed rainfall and flow survey data for the use within catchment hydraulic modelling verification studies. This data is fundamental in developing reliable, high-quality hydraulic models to be used for a range of feasibility flooding impact assessments and future catchment development strategies. This project is primarily interested in reviewing and analysing this data with new and innovative approaches to gauge a broader understanding of the quality and application of this data. Our aim is to establish a process to provide statistical conclusions regarding the data quality to:
1. aid the process of selecting event data to be used for Flow Verification,
2. evaluating the overall quality of the dataset, and
3. review or contrast against theoretical predictions.

## About Caley Water:
Caley Water is an environmental consultancy which specialises in the assessment of both sewer and clean water networks. Specialists in hydraulic modelling, we can carry out a range of modelling activities from new model builds to impact assessments and design solutions. 

## Aim:
How can we better analyse the quality of the data inputs used for Flow Verification?

Assuming the data quality is good, how can we we make better inferences on pipe data and wider flow mechanisms?

## Provided inputs:
**1. Rainfall data**
    We use local rain gauge data as an input for simulations to produce predicted catchment inflows within hydraulic model networks of stormwater, combined and foul pipes. We also use national radar data to validate the quality of the recorded rain gauge data.

**2. Flow Data**
    We also receive raw flow data from flow monitors in placed with network pipes at various locations within a catchment. These flow monitors measure flow using a depth monitor and speedometer within a specific pipe. 

**3. Pipe Parameters**
The pipe’s parameters, namely diameter, gradient (depends on the upstream invert, downstream invert and length of pipe) and roughness influence flow.

**4. Theoretical Colebrook-White Equation**
A theoretical equation used to predict what the flowrate (l/s) in a pipe at particular depth of flow (m) based on pipe parameters.

We have included 3 projects worth of data.  The amount of data you use is your choice.

## What we do with this data:
1. We use radar rainfall data to visually decide what periods of rain gauge rainfall data appear most reliable.
2. Looking at periods of mostly higher quality rainfall data we select rainfall periods using the CIWEM Rainfall Guide and WaPUG User Note 06.
3. We make a visual quality assessment using a scatter graph (X = depth (m) / Y = flowrate (l/s)) of Colebrook White theory against recorded flow data for different periods by seeing how well it matches up during dry periods and periods of rainfall events. We then decide which periods of flow data to use based off a balance of the quality of flow data and selected dry/rainfall events. For example, we may choose a period when there is medium quality rainfall data instead of high-quality rainfall data because there is higher quality flow data during the period of medium quality rainfall data.
4. If the Flow data does not match perfectly with Colebrook White Theory, we then see how the pipe parameters (along with other upstream catchment characteristics that are not accounted for in this project) could be altered to make the data match better. This may involve us looking at various permutations of pipes with different gradients, widths and roughness values within reasonable bounds.

## Expected outputs:
Basically, we want to change our assessment of data quality from the visual to more robust, quantitative methods. Further, we think there is scope in step 4 to automate the making of various permutations of ‘improved’ pipe parameters. The specifics of the improvements we would like related to the 4 processes outlined in previous section [What we do with this data](#what-we-do-with-this-data) are:
1. We would like a more robust method to validate the quality of the rain gauge data.
2. We would like an automated way of selecting high quality rainfall data for dry weather and storm periods.
3. We would like a more robust method to validate the quality of the flow data during periods when we have high quality rainfall data. We then want a more robust method of selecting flow data periods based off an alignment of both good quality flow data and rainfall data.
4. Where we have the best alignment of high quality rainfall and flow data, can we adapt pipe parameters so that the ‘line of best fit’ with CW theory matches best?
5. A way to automate say 10 different permutations of pipe parameters within reasonable bounds would be ideal. 

## Limitations and assumptions:
The distance from Flow Monitor to rain gauge is unaccounted for here, and so are the characteristics of the upstream network and catchment which influence the timing of response from rainfall to the pipe.

## Essential reading:
CIWEM Rainfall Guide: https://www.ciwem.org/assets/pdf/Special%20Interest%20Groups/Urban%20Drainage%20Group/CIWEM-UDG-Rainfall-Guide-2016.pdf 

WAPUG User Note Guide: https://www.ciwem.org/assets/pdf/Special%20Interest%20Groups/Urban%20Drainage%20Group/WAPUG_User_Note_06.pdf 