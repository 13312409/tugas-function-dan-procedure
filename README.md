# tugas-function-dan-procedure
package tugas4;

/**
 *
 * @author Andreas Julianus Radja
 */
public class tugas4 {
    public static int hasilAkhir;
    public static void setHasilAkhir(int n)
    {
        hasilAkhir = n;
    }        
    public static int jumlah(int a,int b)
    {
        return a + b;
    }        
    
    public static void penjumlahan(int a, int b)
    {
        int hasil;
        hasil = jumlah(a,b);
        
        setHasilAkhir(hasil);
    }
    public static void cetakHasil()
    {
        System.out.println("Hasil : "+hasilAkhir);
    }        
    public static void main(String[] args) {
    penjumlahan(7,5);
    cetakHasil();
    
    }
    
}
