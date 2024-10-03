# learn_linux_by_doing
i## Azalie Oga
Worked on the task of deleting the useless file in the data directory named test-1  
```rm test-1```  
## amaliza-shal
worked on moving the top-5 lowest temperature file to analysed directory  
```mv top-5-lowest-temperature.csv analysed```  
## HonourGod
Renamed the files in the analyzed directory properly and removed duplicates from the satelite_temperature_data.csv file  
```mv top5-highest-temperatures.csv top-5-highest-temperatures.csv```  
```sort -u satelite_temperature_data.csv > temp.txt && mv temp.txt satelite_temperature_data.csv```  
## Chiagoziem Eke
He worked on extracting data on all the heat recorded from his own country (Nigeria) into a new file.  
```grep "Nigeria" satelite_temperature_data.csv | cut -d ',' -f 1-3```  
##Jolly Gift Burabyo
''' moved top five lowest temperatures from satelite_temperature_data.csv to the file top-5-lowest-temparatures.csv in analyze directory
'''lowest=$(sort -n temperatures.txt | head -n 1)
echo "Lowest temperature: $lowest" '''
