# SRIMATHI
```
* * * * *  * * * * * * * * * * *         * * * * * * * * * * * *       * * * * * *   * * * * *
*          *       *     *     *  *   *  * *       *     *     *       *     *           *
* * * * *  * * * * *     *     *    *    * * * * * *     *     * * * * *     *           *
        *  *   *         *     *         * *       *     *     *       *     *       *   *
* * * * *  *     *   * * * * * *         * *       *     *     *       * * * * * *   * * *
  ```

```
public class SRII {
    public static void main(String[] args) {
        int n = 5;
        int m = 6;
        int k = 1;

         // ur 'S'
         for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= n; j++) {
                if (i == 1 || i == 5 || i == 3 || (j == 1 && i == 2) || (j == 5 && i == 4)) {
                    System.out.print("* ");
                } else {
                    System.out.print("  ");
                }
            }
        
            System.out.print("  ");  // space between S and R

          // ur'R'
          if (i <= m) {
            for (int j = 1; j <= 5; j++) {
                if (i == 1 || i == 3 || j == 1 || (j == 5 && i <= 2) || (i + j == k)) {
                    System.out.print("* ");
                } else {
                    System.out.print("  ");
                }
            }
            k += 2;
        }
        System.out.print("  ");  // space between R and I

        //ur I
        for(int j = 1 ; j<= n ; j++){
            if( i == 1 || i == 5 || j == 3)
            {
                System.out.print("* ");
            }else
            {
                System.out.print("  ");
            }  
         }
         System.out.print("  ");  // space between I and M


         //ur M
         {
            for(int j = 1 ; j <= n ; j++ )
            {
                if( j == 1 || j == 5  || (i + j == 6 && i <= 3) || (i == 2 && j == 2))
                {
                    System.out.print("* ");
                }
                else{
                    System.out.print("  ");
                }
        }
        System.out.print("  ");  // space between M and A
        //ur A
        for(int j = 1 ; j <= n; j++)
        {
        if( i == 1 || i == 3 || j == 1 || j == 5)
        {
            System.out.print("* ");
        }
        else {
            System.out.print("  ");
        }
    }
            System.out.print("  ");  // space between M and A
        //ur T
        for(int j = 1 ; j <= n ; j++){
            if( i == 1 || j == 3)
            {
                System.out.print("* ");
            }
            else {
                System.out.print("  ");
            }
        }
        System.out.print("  ");  // space between T and H
        //ur H
        for(int j = 1; j <= n ; j++)
            {
             if(j == 1 || j == 5 || i == 3)
             {
                System.out.print("* ");
             }
             else {
                System.out.print("  ");
             }
    }
    System.out.print("  ");  // space between H and I
    //ur I
    for(int j = 1 ; j<= n ; j++){
        if( i == 1 || i == 5 || j == 3)
        {
            System.out.print("* ");
        }else
        {
            System.out.print("  ");
        }
    }
    System.out.print("    ");  // space between H and I
    //ur J
    for(int j = 1 ; j<= n ; j++){
        if( i == 1 || (i==5 && j<=3) || j == 3 || (i == 4 && j == 1))
        {
            System.out.print("* ");
        }else
        {
            System.out.print("  ");
        }
    }
    System.out.println(); // next line  
    }
   }   
  }
 }  
 ```
