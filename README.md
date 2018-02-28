# Program-1.12
Intro to Java Programming, Comprehensive Version, 10th Edition, Y. Daniel Liang

Question:

        (Average speed in kilometers) Assume a runner runs 24 miles in 1 hour, 
        40  minutes, and 35 seconds. Write a program that displays the average 
        speed in kilometers per hour. (Note that 1 mile is 1.6 kilometers.)
        
Code:

        
    public class s_1_12 {

      public static void main (String args[]){
        
        //distance
        double miles = 24.0;
        double km = miles * 1.6;
        
        //time
        double hours = 1;
        double minutes = 40;
        double seconds = 35;

        double timeInMinutes = hours * 60.0 + minutes + seconds / 60.0;

        double kmPH = 60.0 * km / timeInMinutes;

        System.out.println(kmPH);


      }
    }
