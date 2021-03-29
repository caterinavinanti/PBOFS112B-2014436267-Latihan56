# PBOFS112B-2014436267-Latihan56

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author ASUS
 *Nama      : Caterina Vinanti
 *Kelas     : PBO FS112B
 *NIM       : 2014436267
 *Deskripsi Program : Program ini berisi tentang pemrograman Umur Barang Antik
 */
class BarangAntik {
    int umur;
    
    BarangAntik(int umur) {
        this.umur = umur;
    }
    
    void tampilUmur() {
        System.out.println("Umur barang antik ini adalah : " + this.umur + " tahun");
    }
    
    // tambahan
    int getUmur() {
        return this.umur;
    }
}

class Radio {
    String name;
    
    Radio(int umur){
    }
    
    String getName() {
        return this.name;
    }
    
    void setName(String name) {
        this.name = name;
    }
}

/**
 *
 * @author eLx
 */
public class PBOFS112B_2014436267_Latihan56_UmurBarangAntik {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        BarangAntik barang = new BarangAntik(234);
        Radio radio = new Radio(barang.getUmur());
        radio.setName("Radio AM");
        System.out.println("Nama barang antik : " + radio.getName());
        barang.tampilUmur();
    }
    
}

