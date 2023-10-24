Project 1, Aiden Kirk, Sammy Khalaf

           Prog01_aOrderedList    
----------------------------------
 - main(args: String[])           
 + GetInputFile(UserPrompt: String) : Scanner
 + GetOutputFile(UserPrompt: String) : PrintWriter 
---------------------------------
                  |
                  |
-----------------v-----------------
              aOrderedList         
----------------------------------
 - oList: Comparable[]             
 - listSize: int                   
 - numObjects: int                 
 - curr: int                       
----------------------------------
 + aOrderedList()                  
 + add(newObject: Comparable)      
 + size() : int                    
 + get(index: int) : Comparable    
 + isEmpty() : boolean             
 + remove()
 + reset()                         
 + next() : Comparable             
 + hasNext() : boolean             
 - resizeArray()                   
 + toString() : String             
----------------------------------
                  |
                  |
-----------------v-----------------
               Car                  
----------------------------------
 - make: String                    
 - year: int                       
 - price: int                      
----------------------------------
 + Car(make: String, year: int, price: int) |
 + getMake() : String              
 + getYear() : int                 
 + getPrice() : int                
 + compareTo(other: Car) : int     
 + toString() : String             

when creating car objects for the carList, remember to put make, year, and price information for all cars, even ones that are being deleted. 
