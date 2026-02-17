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
