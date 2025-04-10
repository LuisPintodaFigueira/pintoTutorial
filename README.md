tutorial de camo usar o giter hubers 
public class AlturaPredio {
    public static void main(String[] args) {
        // Criando um objeto Scanner para ler entradas do usuário
        Scanner scanner = new Scanner(System.in);
        
        // Solicitando o número de andares
        System.out.print("Informe a quantidade de andares do prédio: ");
        int andares = scanner.nextInt();
        
        // Solicitando a altura de cada andar
        System.out.print("Informe a altura de cada andar (em metros): ");
        double alturaPorAndar = scanner.nextDouble();
        
        // Calculando a altura total do prédio
        double alturaTotal = andares * alturaPorAndar;
