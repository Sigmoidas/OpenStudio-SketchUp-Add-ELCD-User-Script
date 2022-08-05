# OpenStudio-SketchUp-Add-ELCD-User-Script  
Add Electric Load Center Distribution OpenStudio SketchUp Plug-in User Script.  
The intent of this script is to be able to create and add custom named Electric Load Center Distribution (ELCDs).  
Currently when the "Add Photovoltaics" OpenStudio SketchUp Plug-in User Script is run, it autogenerates ELECTRIC LOAD CENTER INVERTER SIMPLE 1, ELECTRIC LOAD CENTER INVERTER SIMPLE 2, ... etc.  
  
At least this is what is visible when the timeseries suimulation results are viewed on DWiew:    
<img src="https://raw.githubusercontent.com/Sigmoidas/OpenStudio-SketchUp-Add-ELCD-User-Script/master/Dview%20ELCD%20Timeseries.png" height="77%" width="77%" >  
This sort of naming convention gets confusing when there are mutiple BIPV surfaces placed around the OpenStudio Model.  
Therefore the aim of this "Add ELCD.rb" OpenStudio SketchUp Plug-in User Script is to be able to create custom named ELCDs  
