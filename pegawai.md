package jurnal;

import java.util.ArrayList;


/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
/**
 *
 * @author aqmalshadik
 */
public class dataSetEmployee {
    private ArrayList<String> nip;
    private ArrayList<String> nama;
    private ArrayList<String> gol;
    private ArrayList<String> status;
    private ArrayList<Integer> jumAnak;
    private ArrayList<Integer> masaKerja;
    
    public dataSetEmployee(){
        nip = new ArrayList<>();
        nama = new ArrayList<>();
        gol = new ArrayList<>();
        status = new ArrayList<>();
        jumAnak = new ArrayList<>();
        masaKerja = new ArrayList<>();
    }
    
    public void addNip (String value){
        nip.add(value);
    }
    
    public ArrayList<String> getDataNip(){
        return this.nip;
    }
    
    public void addNama (String value){
        nama.add(value);
    }
    
    public ArrayList<String> getDataNama(){
        return this.nama;
    }
    
    public void addGol(String value){
        gol.add(value);
    }
    
    public ArrayList<String> getDataGol(){
        return this.gol;
    }
    
    public void addStatus(String value){
        status.add(value);
    }
    
    public ArrayList<String> getDataStatus(){
        return this.status;
    }
    
    public void addJumAnak(int value){
        jumAnak.add(value);
    }
    
    public ArrayList<Integer> getDataJumAnak(){
        return this.jumAnak;
    }
    
    public void addMasaKerja(int value){
        masaKerja.add(value);
    }
    
    public ArrayList<Integer> getDataMasaKerja(){
        return this.masaKerja;
    }
    
    public void tambahKaryawan(String gol, String status, 
            int jumAnak, int masaKerja){
        
        addGol (gol);
        addStatus(status);
        addJumAnak(jumAnak);
        addMasaKerja(masaKerja);
    }
}
