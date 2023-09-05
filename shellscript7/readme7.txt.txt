  for loop
 --------------
  for mission in <mars,lunar,earth,jupiter,saturn>
  do
    create-and-launch-rocket $mission
  done
  while loop
 ----------------
  in this if rocket is lauching it may take 1hr or 2hrs or more every time we have check whether it is fail or success
  if it is success ok orelse if it is fail we have write script for that in for loop we have sleep for every 2 seconds
  keep doing  for every 2 seconds it is not good script thats why we use whileloop script


   while [ $rocket_status = "launching"
    d0
        rocket_status = rocket-status $mission-name
    done
  
    if [rocket_status = "faied"
     then
        rocket-debug $mission-name
    fi