package com.Time;
import java.util.Scanner;
public class Main
{
  public static void main(String[] args)
  {
    Scanner input = new Scanner (System.in);
    int m;
    System.out.print("Enter the number of minutes:");
    m=input.nextInt();
    Conversion(m);
  }
  public static long Conversion(int minutes)
  {
    int years,days;
    years=minutes/(365*24*60);
    days=minutes%(365*24*60);   
    System.out.println(m+" minutes are equivalent to "+years +" years and " + days + " days ");
  }
}
    
    
