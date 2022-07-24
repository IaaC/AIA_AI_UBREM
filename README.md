# AIA_AI_UBREM


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#About-the-project">About The Project</a>
      <ul>
        <li><a href="#credits">Credits</a></li>
      </ul>
    </li>
    <li><a href="#Data-Preparation"> Data Generation</a></li>
    <ul>
        <li><a href="#Energy-Consumption">Energy-Consumption</a></li>
      </ul>
    </li>
  <ul>
        <li><a href="#Solar-Radiation">Solar-Radiation</a></li>
      </ul>
    </li>
    <li><a href="#DNN-ml">Machine Learning-DNN</a></li>
    <ul>
        <li><a href="#DNN-Energy-Consumption">DNN-Energy-Consumption</a></li>
      </ul>
    </li>
  <ul>
        <li><a href="#DNN-Solar-Radiation">DNN-Solar-Radiation</a></li>
      </ul>
    </li>
    <li><a href="#gh">Grasshopper Analytics and Generation</a></li>
    <li><a href="#web">Web development and Mapbox Integration</a></li>
    <li><a href="#bibliography">Bibliography and Other Resources</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- About the Project -->
## About-the-project
This project addresses Energy consumption(EC) mitigation to manifest the concept of postitive Energy District (PED) relying on renewable energy (RE) resources like thermal, Biogas, wind and PV cells. The project utilizes ANN to predict energy consumption of 5 building typologies in Vienna city, residential, detched, apartments, school and office. Shedding light to the fact that vienna city energy conumption of household contributes to almost one third of vienna's total EC.

![image](https://user-images.githubusercontent.com/108461498/180659915-480110e7-adf0-43a9-bdcd-b5ab9dc8df5f.png)



<!-- Credits -->
## Credits

AI-UBREM is a project of IAAC, Institute for Advanced Architecture of Catalonia developed in the Module of Artificial Intellignece in Architecture (AIA) for  MACAD in 2022/23 by Sammar Z. Allam, Naitik Sharma, and Alexander Lopez. Faculty: Angelos Chronis .

<!-- Data-Generation-->
## Data-Preparation

An intensive research process for more than a month to gather energy data about consumption, use, and u-values of buildings in Vienna city to rely on and build a  AI-UBREM dataset to put to test.  Multiple UN-funded projects and reliable governmental city websites, in addition to the AIT of Vienna city along with published data , reports, and simulation results are utilized to build both BEC and PV potential datasets

![image](https://user-images.githubusercontent.com/108461498/180660406-dcb0da21-3190-49bb-9c61-49e3fdae42c4.png)

<!-- Energy-Consumption -->
## Energy-Consumption
Building Energy consumption data has been gathered from multiple resources including UN-funded projects and published research conducted by researchers and scholars from the AIT Austrian Institute of Technology. 
 
![image](https://user-images.githubusercontent.com/108461498/180660414-5aa2c8c7-0618-4ea9-a4ae-51e82196ac19.png)

![image](https://user-images.githubusercontent.com/108461498/180660419-f21c2e50-5ad1-4da2-b836-1e5ebb470014.png)

Tabula Project 
![image](https://user-images.githubusercontent.com/108461498/180660421-57acc278-39de-4482-869c-f144564f3bd4.png)

 


Entranze Project:

 ![image](https://user-images.githubusercontent.com/108461498/180660429-4d173dd4-49ef-420e-9c1e-c3d5c22b0449.png)

![image](https://user-images.githubusercontent.com/108461498/180660435-2ec2f7e2-41a3-4633-826c-b3893005ca6f.png)

 ![image](https://user-images.githubusercontent.com/108461498/180660439-ad45c6cd-97fa-4cad-b684-62d8b7e0dd33.png)




 


Links: 
1.	https://www.wien.gv.at/umweltgut/public/grafik.aspx?ThemePage=9
2.	Tabula Project Vienna,  link: https://episcope.eu/fileadmin/tabula/public/docs/scientific/AT_TABULA_ScientificReport_AEA.pdf
3.	Entranze Project by EU and UN Link: https://www.entranze.eu/files/downloads/D2_3/Heating_and_cooling_energy_demand_and_loads_for_building_types_in_different_countries_of_the_EU.pdf

<!-- Solar-Radiation -->
## Solar-Radiation
In order to manifest PED conceptualization, a renewable energy resource quantification is essential not only to meet but exceed the predicted BEC after retrofitting by decreasing the building’s envelope u-value.  Simulation tools have been utilized to simulate solar radiation, hence building a dataset for Vienna building solar radiation and PV potential. 


 
![image](https://user-images.githubusercontent.com/108461498/180660452-8a7e5aee-415e-4b0a-8648-2dbede9947d1.png)

![image](https://user-images.githubusercontent.com/108461498/180660471-a9273ca6-7a2b-412b-a499-5b1b778f9e27.png)




<!-- Machine-Learning (DNN) -->
## DNN-ml
An intesive research process for more than a month to gather energy data about consumption, use, and u-values of buildings in Vienna city to rely on and build AI-UBREM dataset to put to test. 

<!-- DNN-Energy-Consumption -->
## DNN-Energy-Consumption
 Deep neural network regression has been trained through 4 layers with 36 neurons, then 16 , 8, and finally 4 neurons which are the number of output predicted data.  Dataset has 11 features to train DNN model which are ‘area', 'Heating_energy_kWh_per_m2_a', 'Cooling_energy_kWh_per_m2_a', 'DHW_energy_kWh_per_m2_a', 'total_energy_kWh_per_m2_a', 'u_value_walls_W_per_m2K', 'u_value_roof_W_per_m2K', 'u_value_basement_W_per_m2K', 'u_value_glass_W_per_m2K', 'g_value_glass_W_per_m2K', 'bdgcode'.
 
 
 ![image](https://user-images.githubusercontent.com/108461498/180660493-5e81b7b3-becd-4d6c-b5c0-45d57e3f568b.png)


 
<!-- DNN-Solar-Radiation -->
## Dnn-Solar-Radiation



<!-- Grasshopper-Scripts -->
## gh

<!-- Web-Development -->
## web
