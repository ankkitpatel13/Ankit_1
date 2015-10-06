# Ankit_1

//java code to find smallest and largest integer value from an array//


public class Question2 {
    
    public static void main(String[] args) {
        
    int num[] = new int[]{95,70,82,125,48,67,18,53};
   
    int smal = num[0];
 
    int larg = num[0];
     
    for(int i=1; i< num.length; i++)
        
      {
          
    if(num[i] > larg)
        
    larg = num[i];
    
    else if (num[i] < smal)
        
    smal = num[i]; }
    
    System.out.println("The smallest number is : " + smal);
    
   System.out.println("The largest number is : " + larg);
        } 
    
}
