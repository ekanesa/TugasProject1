import javax.swing.JOptionPane;


/**
 *
 * @author I Putu Eka Nesa Suarsa 2201010116
 */
public class project1jopsi {

    public static void main(String args[]) {
        Double setengah, luas;
        int a = 0;
        String nilai1="";
        int t = 0;
        String nilai2="";
        
        setengah = 0.5;
        String name = "";
        
        nilai1 = JOptionPane.showInputDialog("Masukkan Alas Segitiga : ");
        a = Integer.parseInt(nilai1);
        nilai2 = JOptionPane.showInputDialog("Masukkan Tinggi Segitiga : ");
        t = Integer.parseInt(nilai2);
        
        luas = setengah * a * t;
        
        
        JOptionPane.showMessageDialog(null, "Alas Segitiga: " + a + "\nTinggi Segitiga: " + t + "\nLuas Segitiga: " + luas);

    }
}
