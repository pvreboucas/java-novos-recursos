```shell
jshell> System.out.println("Hello world")
jshell> String nome = "João";
jshell> nome.toUpperCase();
jshell> "Renata"
jshell> $4.toLowerCase();
jshell> /set feedback verbose
jshell> int idade;
jshell> /set feedback silent 
jshell> int numero;
jshell> /set feedback normal
jshell> public void somar(int a, int b) {
   ...> System.out.println(a + b);
   ...> }
jshell> somar(1, 1);
jshell> /edit
class Principal{
public void somar(int a, int b) {
System.out.println(a + b);
}
}
jshell> /drop 8
```
