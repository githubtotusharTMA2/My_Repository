# My_Repository
Making Frame as per the user defined size. If you want to use built-in class's object of a particular type only one or two time in your code then follow this style of code, because this makes code runs faster.


import java.awt.*;

class MyFrameClass
{
  public static void main(String gsar[]) throws java.io.IOException
  {
    System.out.println("Hello User");
    System.out.println("Enter size i.e heigth and width");
    java.util.StringTokenizer str = new java.util.StringTokenizer(new java.io.BufferedReader(new java.io.InputStreamReader(System.in)).readLine();
    int h = Integer.parseInt(str.nextToken());
    int w = Integer.parseInt(str.nextToken());
    java.awt.Frame f = new java.awt.Frame("FrameFirst");
    f.setSize(h,w);
    f.setVisible(true);
    f.setLayout(null);
    }
 }
