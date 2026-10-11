# sistemasdenota
public class Main {
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        
        float nota1 = entrada.nextFloat();
        float nota2 = entrada.nextFloat();
        float nota3 = entrada.nextFloat();
        
        float media = (nota1 + nota2 + nota3) / 3.0f;
        
        System.out.printf("%.2f\n", media);
        
        if (media >= 60.0f) {
            System.out.println("Aprovado");
        } else if (media >= 30.0f) {
            System.out.println("Recuperacao");
        } else {
            System.out.println("Reprovado");
        }
    }
}