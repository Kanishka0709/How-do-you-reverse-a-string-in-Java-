# How-do-you-reverse-a-string-in-Java-
import java.util.*; public class Main{   public static void main(String[] args){     String s="Kanishka";     int length=s.length();     String reverse="";      for(int i=length-1;i>=0;i--)     {       reverse=reverse+s.charAt(i);     }   System.out.print("Reverse of"+reverse); } }
