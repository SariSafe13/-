# -Assignment 1 
--------------------------------------------------------------
The assignment goal is to develop a an algorithm for elevator.
It consists of 4 interfaces and we are asked to implement the Elvator's Algorithm class.

--------------------------------------------------------------------------------------------------------------------------------------------------------------
 ElevatorAlgo interface  <--> ElevatorAlgorithm class (LastOne)

*To implement this class We used the collection data structure :arraylist 
Actually we used 2 arraylists: One is resposible for the elevors that are going UP.
The seconed one represents the elevetors that are going DOWN .
   
  properties :
    Arraylist<Callfoeelvator> E_UP   - The assending elevatores 
    Arraylist<Callfoeelvator> E_DOWN - The desecending elevatores 
     Building _building  - The building 

  constructor:
    public LastOne(Building b) 
   
  methods:
    
    Building getBuilding() 
     
    String algoName() 
     
    public int allocateAnElevator(CallForElevator c) - It allocats the call to the closest elevator to its source.
   
    public void cmdElevator(int elev) - The function that moves the elevator to its destination .
    
   secondary methods :
    there no use with secondary methods 

--------------------------------------------------------------------------------------------------------------------------
 Sari safe : 324832914
 


