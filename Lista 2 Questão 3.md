import java.io.*;
import java.util.*;

public class HuxleyCode {
  public static void main(String args[]) {
    	Scanner in = new Scanner(System.in);
		int N, V;
		N = in.nextInt();
		
		 
		for (int i = 1; i <= N; i++) {
			V = in.nextInt();
			if (V==i) {
				System.out.printf("o ingresso de numero %d foi sorteado", V);
			}
		}
  }
}
