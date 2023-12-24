# Persiapan Pra Ukl Java

## Deskripsi

Dalam repo ini, berisikan documentation belajar java pribadi saya untuk mempermudah belajar bagi pemula untuk mendalami bahasa pemrograman java, materi ini didapat dari [Materi SMK Telkom Malang](https://www.smktelkom-mlg.sch.id/).

### Installation

Pastikan sudah menginstal Java msi atau download menggunakan link:

[Download Java for Windows](https://javadl.oracle.com/webapps/download/AutoDL?BundleId=249203_b291ca3e0c8548b5a51d5a5f50063037).


modifier, getter setter, constructor, polimorphisme

1. sebutkan apa itu enkapulasi?
jawaban: 

cintih modifier ada 4 dan jiliskin: 
public : bisa diakses dimana pun, paling fleksibel
protected : hanya bisa diakses dari superclass, subclass, beda file
no modifier(kosongan) : bisa diakses disubclass dan class itu sendiri
private : hanya bisa diakses dari class itu sendiri (paling introvert)

contoh penerapan:
public static void pan(){}
protected String pin(){}
void pinpan(){}
private relationship(){}

2. apa itu getter setter?
jawaban:

dari namanya bisa diketahui bahwa getter untuk mendapatkan dan setter untuk meng-set sesuatu. hanya bisa digunakan di private class, karena
private class tidak bisa dipanggil dari class lain (Istilah gampangnya orang dalam)

contoh penerapan getter setter:
public void setNama(String nama){
    this.namaMember.add(nama);
}

public String getNama(int idMember){
    return this.namaMember.get(idMember);
}

3.apa itu constructor?
jawaban:

constructor adalah nilai default dari sebuah codingan, contoh penerapan:
public class hts{
    public hts(){
        sout("yah kasihan hts mulu ga pernah jadian");
    }
}

4.apa itu polimorphisme?
jawaban:

polimorphisme adalah pewarisan dari sebuah code ke code lain
ada dua polimorphisme yaitu interface dan inheritance

interface adalah bentuk awal yang abstrak/tidak berbentuk, supaya code tsb tidak eror harus dibentuk setiap fungsi yg ada didalamnnya
interface memiliki ciri2 yaitu ada tambahan implements di nama classnya

contoh penerapan:
interface pan{
    *ada dua cara membuat nya yaitu dengan interface/ abstrak
    public interface cina{
        public void marga(String xu);
        public void suku(String hokkian);

        public String getMarga(int idMarga);
    }

    *jika disuruh merubah ke codingan abstract
    public abstract class cina{
        public abstract void marga(String xu);
        public void suku(String hokkian){

        }

        public abstract String getMarga(int idMarga){
        
        }
        
    }
}

inheritance adalah cara menumpuk code persis seperti superclass nya (jadi apapun yg ada diindukan juga turun ke anakannya)
inheritance memiliki ciri2 yaitu menggunakan extends
contoh penerapan:
    public class luas{
        int luas(){
        sout("Hitung Luas");
        return 0; 
        }
    }

    class persegi extends luas{
        int s;
        
        public int luas(){
            sout(s*s)
            return luas;
        }
    
    }

    SEMANGAT PRA UKL, SEMOGA PAHAM!! :)