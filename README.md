# Programa-engenharia
package engenhariasoftware;

/**
 *
 * @author Bruna Gabriele
 */
import java.util.Scanner;
public class EngenhariaSoftware {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
    Scanner entrada = new Scanner (System.in);
int x,y,soma,multiplicacao;
System.out.println("Introduza dois numeros");
x = entrada.nextInt ();
y  = entrada.nextInt ();
soma = x+y;
media = (x+y)/2;
System.out.println("O resultado da soma e:"+soma);
System.out.println("O resultado da multiplicacao e:"+multiplicacao);
}
}

