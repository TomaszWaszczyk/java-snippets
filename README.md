# java-snippets

```
// Online Java Compiler
// Use this editor to write, compile and run your Java code online

// Write java function to find number of 
// occurrences of some number in given array of numbers
 


class Main {
    
    public static int countOccurences(int[] array, int target){
        int count = 0;
        // O(n)
        // 
        for(int num: array){
            if(num == target){
                target++;
            }
        }
        return count;
    }
    
    public static void main(String[] args) {
        int []numbers = {1,2,3,1,2,3,4,5,6,7,8}
        
        System.out.println("Try programiz.pro");
    }
}
```

```
Optional
 

if (request.getDateBegin() != null) {
  DateTime dateBegin = request.getDateBegin();
  if (!dateBegin.equals(ad.startDate())) {
    // ...
  }
}

 

 

Functional interface, Lambda
 

interface StringFunction {
  String run(String str);
}

 

Lambda która robi uppercase ( "".toUpperCase() );

 

public static void printFormatted(String str, StringFunction format) {
  ...........
  System.out.println(result);
}

 

printFormatted(...........)

 

 

 

Streams API
 

List names = Arrays.asList("Anna", "Piotr", "Kasia", "Andrzej", "Paweł", "Agnieszka");
1) String @@Anna|Piotr|Kasia|Andrzej|Paweł|Agnieszka@@
2) List ["ANNA",  "ANDRZEJ", "AGNIESZKA"]
3) Map [
          "A" , ["Anna",  "Andrzej", "Agnieszka"] 
      "P" , ["Piotr",  "Paweł"] 
      "K" , ["Kasia"] 
     ]

 
```
