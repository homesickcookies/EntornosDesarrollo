# 1. En la función 1, ¿qué hacen estas lineas de código?
    String string2 = "string2";
    
    string2= string2.substring(0, string2.length()-1);
    string2=string2+"1";

>1: Declara una variable de tipo string llamada **string2** y le da el valor *"string2"*. <br>
>3: resta 1 a la longitud de la cadena de texto de la variable **string2** (el valor se convierte en *"string"*) <br>
>4: añade *"1"* a la cadena de texto de la variable **string2** (el valor se convierte en *"string1"*).

# 2. ¿Qué valen las variables string1 y string2 antes de ejecutar el siguiente codigo de comprobación?
    if(string1 == string2 ) {
        System.out.println("SÓN IGUALS " + a );
    }
    else {
        System.out.println("SÓN DIFERENTS");
    }

> ambas variables contienen la cadena *"string1"*.

# 3. ¿Por qué no funciona el operador *"=="*? ¿Que operador se debe usar en su lugar? 

> porque estamos comparando dos Strings, para eso se usa la funcion .equals().

    if(string1.equals(string2)) {...}

# 4. La funcion2() está declarada de esta manera:
    public void funcion2() {
        System.out.println("--------------------");
        System.out.println("Aquesta és la funció 2");
        System.out.println("Com faig la crida perquè funcione????");
    }

# Está función debe salir por el metodo main para que funcione. Existen 2 opciones, explícalas:

> Primero hay que declarar el metodo como estático.

    Public static void funcion2() {...}

> Después hay que llamar a la funcion desde main

    public static void main(String[] args) {

		int a = 3;
		int i;
		for(i = 0; i<10; i++)
			a *= i;
		
		System.out.println("El valor de a es: "+a);
		
		
		funcion1();

		funcion2();
    }