for loop
--------
1) create script launch-rocket.sh


  create-and-launch-rocket lunar-mission
  --------------------------------------
     mission_name = $1
     mkdir lunar-mission

     rocket-add lunar-mission

     rocket-start-power lunar-mission
     rocket-internal-power lunar-mission
     rocket-start-sequence lunar-mission
     rocket-start-engine lunar-mission
     rocket-start-power lunar-mission
    
     rocket-lift-off lunar-mission

     rocket_status = rocket-status $mission name
     
     

     
     create-and-launch-rocket mars-mission
     ---------------------------------------

     mission_name = $1
     mkdir mars-mission

     rocket-add mars-mission

     rocket-start-power mars-mission
     rocket-internal-power mars-mission
     rocket-start-sequence mars-mission
     rocket-start-engine mars-mission
     rocket-start-power mars-mission
    
     rocket-lift-off mars-mission

    rocket_status = rocket-status $mission name
     
     create-and-launch-rocket jupiter-mission
    ------------------------------------------

     mission_name = $1
     mkdir jupiter-mission

     rocket-add jupiter-mission

     rocket-start-power jupiter-mission
     rocket-internal-power jupiter-mission
     rocket-start-sequence jupiter-mission
     rocket-start-engine jupiter-mission
     rocket-start-power jupiter-mission

     rocket-lift-off jupiter-mission

     rocket_status = rocket-status $mission name
     
     create-and-launch-rocket saturn-mission
    ----------------------------------------

     mission_name = $1
     mkdir saturn-mission

     rocket-add saturn-mission

     rocket-start-power saturn-mission
     rocket-internal-power saturn-mission
     rocket-start-sequence saturn-mission
     rocket-start-engine saturn-mission
     rocket-start-power saturn-mission
    
     rocket-lift-off saturn-mission
  
     rocket_status = rocket-status $mission name
     
     create-and-launch-rocket earth-mission
    --------------------------------------

     mission_name = $1
     mkdir earth-mission

     rocket-add earth-mission

     rocket-start-power earth-mission
     rocket-internal-power earth-mission
     rocket-start-sequence earth-mission
     rocket-start-engine earth-mission
     rocket-start-power earth-mission
    
     rocket-lift-off earth-mission

     rocket_status = rocket-status $mission name

     NOTE : why i have created $1 maeans everytime we have to come to script and make change missions that why we can change in start of created and launch cmd only
     ----
              eg: create-and-launch-rocket  lunar-mission
                                             -------------