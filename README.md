import java.util.Scanner;
public class Main {

  public static void main(String[] args) {
    Scanner input = new Scanner (System.in);
  double nota;
    boolean notaValida = false;
  do{ 
    System.out.println("Coloque o valor da nota:");
    nota = input.nextDouble();

    if(nota >=0 && nota <=10) {
     notaValida = true;
      System.out.println("O valor digitado é:"+nota);

    }else{ 
      System.out.println ("Você digitou uma nota"+nota+"inválida, tente novamente.");
          }
  }while(!notaValida);
  }


}
