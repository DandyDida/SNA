uuih



package org.ukdw.data;

public class Ruangan {
    private int id;
    private String name;
    private int idGedung;

    // Constructor
    public Ruangan(int id, String name, int idGedung) {
        this.id = id;
        this.name = name;
        this.idGedung = idGedung;
    }

    // Getter dan Setter
    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getIdGedung() {
        return idGedung;
    }

    public void setIdGedung(int idGedung) {
        this.idGedung = idGedung;
    }

    // Override toString untuk debugging
    @Override
    public String toString() {
        return "Ruangan{id=" + id + ", name='" + name + "', idGedung=" + idGedung + "}";
    }
}



package org.ukdw.data;

public class Gedung {
    private int id;
    private String nama;
    private String alamat;

    // Constructor
    public Gedung(int id, String nama, String alamat) {
        this.id = id;
        this.nama = nama;
        this.alamat = alamat;
    }

    // Getter dan Setter
    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getNama() {
        return nama;
    }

    public void setNama(String nama) {
        this.nama = nama;
    }

    public String getAlamat() {
        return alamat;
    }

    public void setAlamat(String alamat) {
        this.alamat = alamat;
    }

    // Override toString untuk debugging
    @Override
    public String toString() {
        return "Gedung{id=" + id + ", nama='" + nama + "', alamat='" + alamat + "'}";
    }
}



