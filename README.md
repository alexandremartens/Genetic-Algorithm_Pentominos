# Genetic-Algorithm_Pentominos

info section explains the behaviour of the algorithm<br />
Using only L,P,T without values? -> Section 1<br />
Using values? -> Section 2<br />
Don't forget to adjust the time limit. this is going to stop the execution<br />
  of the program if no solution found<br />

  ## Section 1
  Step 1.0: fill L,P,T number of parcels<br/>
  Step 1.1: set the boolean ValueBoolean = false;<br/>
  Step 1.2: Add a time-limit of execution in milliseconds.<br/>
  Step 1.3: RUN the program<br/>
  Using the bruteforce will modify the way the Simulation method places the parcels. advised to keep it 'True'<br/>

  info 0.0: Volume total parcels > container volume?<br/>
    --> try to fill the parcel as best as possible<br/>
  info 1.0: Volume total parcels <= container volume<br/>
  info 1.1: Volume total parcels = container volume and all parcels CAN be placed<br/>
    --> Will find the container, all filled<br/>
  info 1.2: Volume total parcels < container volume and all parcels CAN be placed<br/>
    --> Will find the container, with gaps obviously<br/>
  info 1.3: Volume total parcels < container volume and all parcels CAN't be placed<br/>
    --> Will remove some pieces and try to get the most pieces placed, will stop with the time-limit<br/>

  ## Section 2
  Step 2.0: fill L,P,T number of parcels, if 'unlimited', enter <br/>
  Step 2.1: fill L,P,T's respective weights<br/>
  Step 2.2: set the boolean ValueBoolean = true;<br/>
  Step 2.3: Add a time-limit of execution in milliseconds.<br/>
  Step 2.4: RUN the program<br/>

  info 0.0: Volume total parcels > container volume?<br/>
    --> Will stop after the timeLimit and show the best result<br/>
  info 1.0: Volume total parcels <= container volume<br/>
  info 1.1: Volume total parcels = container volume and all parcels CAN be placed<br/>
    --> Will find the container, all filled and show the best result<br/>
  info 1.2: Volume total parcels < container volume and all parcels CAN be placed<br/>
    --> Will find the container, with gaps obviously and show the best result<br/>
  info 1.3: Volume total parcels < container volume and all parcels CAN't be placed<br/>
    --> Will stop after the timeLimit and show the best result<br/>
