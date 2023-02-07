/* package codechef; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;
import java.util.Arrays;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	    Scanner sc = new Scanner(System.in);
	    int t = sc.nextInt();
	    int[] a = new int[t];
	    int[] f = new int[100001];
	    int[] b = new int[100000];
	    for(int i=0;i<t;i++) {
	        a[i]=sc.nextInt();
	        f[a[i]]++;
	    }
	    int j=0;
	    for(int i=1;i<=t;i++) {
	        if(f[i]==0) {
	            b[j]=i;
	            j++;
	        }
	    }
	    int d[]=new int[j];
	    for(int i=0;i<j;i++) {
	        d[i]=b[i];
	    }
	    Arrays.sort(d);
	    for(int i=0;i<j;i++) {
	        System.out.print(d[i]+" ");
	    }
	}
}




International Hotel Booking Form (ongoing)
