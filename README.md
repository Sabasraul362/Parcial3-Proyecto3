
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;
import javax.swing.JoptionPane;
import javax.swing.table.DefaultTableMode1;

/*
 * To change this file, choose Tools | Templates
 * To change this template, choose Tools | Templates
 * and open the template in the editor
*/
/**
 *
 *@Author Sabas
 */
public class CLIENTES extends javax.swing.JFrame {

    Scanner Sabas = new Scanner(System.in);
    List<Cliente> cartera = new ArrayList<>();
    
    /**
     * Creates new form CLIENTES
     */
     public void InfoClientes(){

     }
         this.telefono = telefono;
         this.correo = correo;
}

     public String getNombre;{
         return nombre;
     }

     public void setNombreString nombre){
         this.nombre = nombre;
     }

     public int getedad(){
         return edad;
     }

     public void setedad(int edad){
         this.edad = edad;
     }

     public int getid(){
         return id;
     }

     public void setid(int codigo){
         this.id = codigo;
     }

     public String getTelefono(){
         return telefono;
     }

     public void setTelefono(String telefono){
         this.telefono = telefono
     }

     public String getCorreo(){
         return correo;
     }

     public void setCorreo(String correo){
         this.correo = correo;
     }
}
