# armorcore-s.l

## 1. Fundamentos del sistema
la idea principal del sistema consiste en poder facilitar el poder llevar el ciclo contable de cada año de forma facil de entender

## 2. Análisis y especificación de requisitiso

## 3. Diseño

## 4. Implementación

## 5. Plan de pruebas del sistema
//**
*clase de alumno
/*
public class alumno{
private String nombre;

private int edad;private double notaFinal;
public alumno(String n,int e,double nf){NOMBRE=n;edad=e;NotaFinal=nf;}

public void mostrarDatos(){System.out.println("Alumno: "+nombre+", edad:"+edad+", notaFinal:"+notaFinal);}

public boolean aprobado(){if(notaFinal>=5.0){return true;}else{return false;}}
public void mensajeFinal(){if(aprobado()){System.out.println("felicidades "+nombre+" aprobaste!");}

else{System.out.println("Lo siento "+nombre+" no aprobaste");}}
}

class curso{
private String nombreCurso;
private alumno[] lista;
public curso(String n, alumno[] l){nombreCurso=n;lista=l;}
public void mostrarTodo(){System.out.println("curso: "+nombreCurso);for(alumno a:lista){a.mostrarDatos();a.mensajeFinal();}}
public static void main(String[] args){

alumno a1=new alumno("ana",18,6.5);
alumno a2=new alumno("PEDRO",19,4.3);
alumno a3=new alumno("Lucia",17,8.7);
alumno[] lista={a1,a2,a3};

curso c1=new curso("programacion",lista);
c1.mostrarTodo();}}

