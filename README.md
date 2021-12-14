# method-to-find-avg
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    static float avg(float n1,float n2,float n3)
    {
        float  sum = n1 + n2 + n3;
        return sum / 3;
    }
    public static void main (String args[])
    {

        Scanner k=new Scanner(System.in);
        int x,y,z;
        System.out.println("Enter #1 :");
        x=k.nextInt();
        System.out.println("Enter #2 :");
        y= k.nextInt();
        System.out.println("Enter #3 :");
        z=k.nextInt();
        System.out.println("avg =" + avg(x,y,z));
    }
}

