# ejercicio-tema-8-bootcamp

public class Main {
    public static void main(String[] args) throws Exception {
 Persona p = nueva Persona();

       System.out.println("Contenido de variables antes de los getters y los setters");
       System.out.println(p.get_nombre());
       System.out.println(p.get_edad());
       System.out.println(p.get_telefono());

       System.out.println("Contenido de variables despues de los getters y los setters");
       p.set_edad(25);
 p.set_telefono 7018661);
       p.set_nombre("Ricardo");
       System.out.println(p.get_edad());
       System.out.println(p.get_nombre());
       System.out.println(p.get_telefono());
    }

    public static class Persona {
 int edad privada;
 telefono privado int;
        private String nombre;

        public int get_telefono(){
 teléfono de retorno;
        }

        public int get_edad(){
 devolver edad;
        }

        public String get_nombre() {
 devolver nombre;
        }

        public int set_edad(int edad) {
            return this.edad = edad;
        }
        public int set_telefono(int telefono) {
            return this.telefono = telefono;
        }
        public String set_nombre(String nombre) {
            return this.nombre = nombre;
        }



    }


}
