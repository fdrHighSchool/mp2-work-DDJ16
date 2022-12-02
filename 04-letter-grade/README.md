# Letter Grade
#### Respond to the following:

1. Write a plan for the following extension:
  * Attach a "+" on their grade if the grade ends in a 7, 8 or 9 (eg: 78 -> C+, 89 -> B+)
  * Attach a "-" on their grade if the grade ends in a 0, 1 or 2 (eg: 92 -> A-, 61 -> D-)

    * **YOUR WRITING HERE**
      if ( grade >= 7 ){
       system.out.print("c+)
      } 
      else if( grade <= 2){
       System.out.println("c-"
      }
      else{
       System.out.println('c')
      }
2. Discuss how you would make sure 100 is not misrepresented as an A-.
  * **YOUR WRITING HERE**
      put if(grade >= 100){} first to check it first.
          
      
3. Discuss how you would make sure grades that are an F are not mislabeled as F- or F+ (eg: 49 -> F+ and 52 -> F-)
  * **YOUR WRITING HERE**
     when you use else just make it print F no f- or f+
