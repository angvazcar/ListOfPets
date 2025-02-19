# README #

This readme will document whatever steps are necessary to get ListOfPets running.

### What is this repository for ###

This code covers the exercise 3, section 2 related to data in APIs. Section 2 related to listing the name and the id of the sold pets. 
As there is a dependency with the other sections what we have done is create the following structure:

ListOfPetsProject/

*  PetStore.java         # Crea un cliente HTTP, envia la solicitud, obtiene la respuesta Json y recorre el json para mostrarlo en formato {id,name}.  
* pom.xml                     # Si usas Maven, aquí puedes gestionar dependencias(en ppio las he añadido todas no necesario editar)  
* readme.txt  # Archivo con instrucciones para ejecución en IntelliJ IDEA


### Download and installation ###

* Download the corresponding git repository from the ListOfPets branch: https://github.com/angvazcar/ListOfPets.git
* Execute the following comands on your prompt/terminal:
_git clone https://github.com/angvazcar/ListOfPets.git_

### Preconditions before code execution ###

*  Have Java version 11 or higher installed (you can download from here [Oracle JDK](https://www.oracle.com/java/technologies/downloads/#java11?er=221886)
*  Have IntelliJ IDEA installed
*  Have Maven installed

### Usage and code execution ###

* Open the project downloaded in the previous steps with IntelliJ (File--> Open and select the downloaded code)
* In IntelliJ terminal run:
_mvn clean install_
* Open PetStore.java in IntelliJ
* Click on the run green button on the left of the code line _public static void main(String[] args)_ (if you do not see it in the top right corner,right click on Main.java and select Run 'Main.main()')


Once the execution has finshed you will see an exit like: 

PetStore  
{7, toto}  
{109, doggie}  
{-2025415031, hello kity}  
{-1426268571, hello kity}  
{464634152, hello kity}  
{127905248, hello kity}  
{664072556, hello kity}  
{13, Sin nombre}  
{1520128754, Marinus384}  
{9415, JKXPuCoXSF}  
{98765, полосатая}  
{9, King Kong}  
{2425, Annie}  

Process finished with exit code 0
