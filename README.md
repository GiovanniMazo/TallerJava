# TallerJava


public class Jornada {
        private int horas;
    private String fechaInicio;
    private String fechaFin;
    
    // Constructor
    public Jornada(int horas, String fechaInicio, String fechaFin) {
        this.horas = horas;
        this.fechaInicio = fechaInicio;
        this.fechaFin = fechaFin;
    }
    
    // Getters y Setters
    public int getHoras() {
        return horas;
    }
    
    public String getFechaInicio() {
        return fechaInicio;
    }
    
    public String getFechaFin() {
        return fechaFin;
    }
}
