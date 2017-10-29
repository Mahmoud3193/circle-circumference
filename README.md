# circle-circumference

package com.and.ch1;
import java.lang.Math ;
import java.util.Scanner ;

public class HelloAndroid {

  public static void main(String[] args) {
   Scanner no = new Scanner(System.in) ;
   System.out.println("the pi is "+Math.PI) ;
   System.out.println("enter circle diameter") ;
   double D = no.nextDouble () ;
   System.out.println("the circle circumferance is "+Math.round(D*Math.PI)+" rounded") ;
   no.close() ;
  }
}
