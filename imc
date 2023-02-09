import javax.swing.JOptionPane;
//O IMC é reconhecido como padrão internacional para avaliar o grau de sobrepeso e obesidade. É calculado dividindo o peso (em kg) pela altura ao quadrado (em metros).
//IMC = Peso ÷ (Altura × Altura)//
 
//* @author Alunas Andressa e Julia 

  
public class calculadoraimc {
    
    public static void main( String[] args){
        
        String firstNumber = 
                JOptionPane.showInputDialog("insira seu peso em kg : ");
        String secondNumber =
                JOptionPane.showInputDialog("insira sua altura em metros : ");
        
 
       double Number1 = Double.parseDouble(firstNumber);
       double Number2 = Double.parseDouble(secondNumber);
       double imc =  Number1/(Number2*Number2 ) ;
        
       JOptionPane.showMessageDialog(null, "seu imc é: " + imc, "T", JOptionPane.PLAIN_MESSAGE);
    }
}
