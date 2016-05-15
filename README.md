# hello-world
My First Experience in Github 

// Recorded beneath is the sample Java code for famous Fibanachi Problem

public class Fibanachi{
	public static void main(String args[]){
  System.out.print("Fibanachi Numbers--------");
	
  int X;
	int Y;
	int Z;
	X = 0;
	Y = 1;
	Z = 0;

  
	for(int i=1;i<=10;i++){

 X = Y;
	Y = Z;
	Z = X + Y;

  System.out.print(" "+Z+" ");
	
	}
	}
}


