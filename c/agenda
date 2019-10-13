
#include <string.h>
#include<stdio.h>
#include<stdlib.h>
#include <locale.h>
#include <dos.h>
#include <conio.h>
#include <windows.h>
// FIM INCLUDES
int main(void){
	setlocale(LC_ALL, "Portuguese");
 int autenticacao();
 	autenticacao();

}
 int autenticacao(){
 	
FILE *file;

int x;

file = fopen("Autenticacao_De_Primeio_Acesso.txt","r");
fscanf(file,"%i",&x);
fclose(file);

if(x==0){
	
	int mmain();
	char nome[20];
	
	system("color f8");
	
	printf("Olá! Obrigado por utilizar este softwaree. \n");
	printf("Qual o seu nome: ");
	scanf("%s",nome);
	
	printf("Bem-vindo, %s \n",nome);
	
	FILE *file;
	file = fopen("Nome.txt","w");
    fprintf(file,"%s",nome);
    fclose(file);
    
FILE *file2; 
x = 1;

file2 = fopen("Autenticacao_De_Primeio_Acesso.txt","w");
fprintf(file2,"%i",x);
fclose(file2);
system("cls");

FILE *file3; 

int var1 = 0;

file3 = fopen("Número_De_Contatos.txt","w");
fprintf(file3,"%i",var1);
fclose(file3);
FILE *var2; 

int var3 = 0;

var2 = fopen("cora.txt","w");
fprintf(var2,"%i",var3);
fclose(var2);
FILE *var4; 

var4 = fopen("corb.txt","w");
fprintf(var4,"%i",var3);
fclose(var4);

	mmain();
} else {
	
int mmain();
mmain();
}
}
 
 

//------- FIM DA AUTENTICAÇÃO DA AGENDA -------

int mmain(void){
	setlocale(LC_ALL, "Portuguese");
 
 int addcontato();
 int menu();
 int op1();
 int op2();
 int op3();
 int op4();
 int op5();
 int config();
 menu(); 
 return 0;
}

//---------------------------------------------

int op1(){

FILE *file;

int x;

file= fopen("teste.txt","r");
fscanf(file,"%i",&x);

x = x + 1;

fclose(file);
file= fopen("teste.txt","w");
fprintf(file,"%i",x);
fclose(file);

int ver_contato();



ver_contato();
}

ver_contato(){


	struct 	contato{
		
 char NomeContato[20];
 char email[50];
 char numero[15]; 
};
typedef struct contato con[50];

int identificador[50];

con b;

	FILE *file;
int nr,tt;
file= fopen("Número_De_Contatos.txt","r");
fscanf(file,"%i",&nr);
fclose(file);
printf("____Contatos_____\n");
 FILE *file4; 
file4= fopen("contatos_lista.txt","r");

for(tt=0; tt<=nr; tt++){
  
    fscanf(file4,"%s",&b[tt].NomeContato);
    fscanf(file4,"%s",&b[tt].email);
    fscanf(file4,"%s",&b[tt].numero);



 
 }

fclose(file4);

//--------------------------------------------

for(tt=0; tt<=nr; tt++){
	
    printf("\n %s\n",b[tt].NomeContato);
    printf("%s\n",b[tt].email);
    printf("%s\n",b[tt].numero);
    
  }
  	
 //-------------------------------------------
 
 printf("____________\n");
 char nome[50];
 
int var6;
 do{
 
printf("pesquise um contato ou digite sair para voltar ao menu: ");
scanf("%s*",nome);

char testeespera[]="sair";

int var5 = 0;

var6 = strcmp(nome,testeespera);
if(var6 == 0){
	mmain();
}

int ChecadorNomeCont=765, ChecadorEmail=876, ChecadorNumero=77;
	for(tt=0;tt<=nr;tt++){
ChecadorNomeCont = strcmp(nome,b[tt].NomeContato);		
ChecadorNomeCont = strcmp(nome,b[tt].NomeContato);
ChecadorEmail = strcmp(nome,b[tt].email);
ChecadorNumero = strcmp(nome,b[tt].numero);

if(ChecadorNomeCont == 0){
printf("%s  %s  %s \n",b[tt].NomeContato,b[tt].email,b[tt].numero);
}
if(ChecadorNomeCont =! 0){
var5 = var5 + 1;
}
if(ChecadorNumero == 0){
printf("%s  %s  %s\n",b[tt].NomeContato,b[tt].email,b[tt].numero);
}
if(ChecadorNumero =! 0){
var5 = var5 + 1;
}
if(ChecadorEmail == 0){
printf("%s  %s  %s \n",b[tt].NomeContato,b[tt].email,b[tt].numero);
}
if(ChecadorEmail =! 0){
var5 = var5 + 1;
}

}}while(var6 != 0);
} 	

//--------------Adicionar Contato--------------

int op2(){
	
printf("Adicionar novo contato\n");
system("color f8");
addcontato();
  
  }
  
//-------------Procurar Contato----------------


int apagar(){}
int editar(){}
//----------------------------------------
int op3(){
	int gugu;

printf("você deseja editar ou apagar o contato\n\n");
printf("1=apagar 2=editar\n\n");
scanf("%d",gugu);
if(gugu==1){
apagar();
}
if(gugu==2){
	editar();
}else{mmain();
}

}
//----------------------------------------------

//----------------------------------------------
int op4(){
printf("\n\nSAIR\n");
int s=3;
int n=3;

char con[1];
char sim[]="y", nao[]="n";
printf("\n\nconfirmar y or n?\n\n");
scanf("%s", &con);
s= strcmp(con,sim);
n= strcmp(con,nao);




if(s==0){
	int c;
printf("voce saiu");



       
        
system("break");

}
else if(n==0){
 system("cls");
 int menu();
menu();
 
}
else{
	system("color fc");
	system("cls");
	printf("y=SIM n=NãO SOMENTE S OU N SãO ACEITOS");
	sleep(2);

	op4();
}

}
//-----------------------------------------------------
op5(){
	
	config();
	
	
	
	
}
//---------------------------------------------------------
void mensagembv(){
	FILE *file;
	char nome[10];
file= fopen("nome.txt","r");
fscanf(file,"%s",&nome);
fclose(file);
printf("seja bem vindo %s \n",nome);
}
//-----------------------------------------------------------
int menu(){
 int check;
   int a,c;
   int cora();
   cora();




printf("  \n");

printf("                                                                                                               \n");
printf("            A            GGGGGGGGGGGGGG   EEEEEEEEEEEEEE   NNNN          N  DDDDD                 A          \n");
printf("           A A          G                 E                N   N         N  D    DDDD            A A         \n");
printf("          A   A         G                 E                N    N        N  D        DDD        A   A        \n");
printf("         A     A        G                 E                N     N       N  D           DD     A     A       \n");
printf("        AAAAAAAAA       G                 EEEEEEEEEE       N      N      N  D             D   AAAAAAAAA      \n");
printf("       A         A      G       GGGGGG    E                N       N     N  D           DD   A         A     \n");
printf("      A           A     G             G   E                N        N    N  D        DDD    A           A    \n");
printf("     A             A    G             G   E                N         N   N  D    DDDD      A             A   \n");
printf("    A               A    GGGGGGGGGGGGG    EEEEEEEEEEEEEE   N          NNNN  DDDDD         A               A  \n");
printf("                                                                                                               \n");

 system("cls");
int corb();
   corb();
mensagembv();

printf("Selecione o numero desejado\n");
printf("---------------------------\n");
printf("1. Ver contatos\n");
printf("2. Adicionar novo contato\n");
printf("3. Apagar ou Editar contato\n");
printf("4. Sair\n");
printf("5. Config\n");
 scanf("%d", &a);
 system("cls");
 
 	switch (a)
{
case 1:
     op1();
      break;

case 2:
     op2();
     break;
     
case 3:
op3();
   break;

case 4:
     op4();
   break;
   
case 5:
     op5();
   break;
   
     default:
     menu();
     break;
}
 
    return 0;
}
//-------------Cor Tela Inicial-----------------------------
int cora(){
	FILE *file;
int x;
file= fopen("cora.txt","r");
fscanf(file,"%i",&x);
fclose(file);
if(x==0){

	system("color 02");
}
if(x==1){
	system("color fd");
}
if(x==2){
	system("color 70");
}
}

//---------------Cor do Menu--------------------------------



int corb(){
		FILE *file;
int x;
file= fopen("corb.txt","r");
fscanf(file,"%i",&x);
fclose(file);
if(x==0){

	system("color 02");
}
if(x==1){
	system("color f5");
}
if(x==2){
	system("color f3");
}
}
//-----------------------------------------------------
config(){
	int g;
	printf("bem vindo as configuraçoes\n");
	printf("selecione o numero desejado\n");
printf("1.editar meu nome\n");
printf("2.mudar cores  da tela de entrada\n");
printf("3.mudar cores do menu\n");
printf("4.exportar todos os contatos\n");
printf("5.sons\n");
printf("6.voltar\n");
 scanf("%d", &g);
 system("cls");
	
	switch (g)
{
case 1:
     config1();
     
    break;

case 2:
     config2();
     break;
case 3:
	config3();
   break;

   case 4:
     config4();
   break;
   case 5:
    config5();
   break;
   case 6:
   	menu();
   break;
     default:
     config();
     break;
}
}
//-------------------------------------------------------------
int config1(){
	char nome[50];
	printf("insira seu nome\n");
	scanf("%s",nome);
	printf("bem vindo %s \n",nome);
	FILE *file;
	file= fopen("nome.txt","w");
    fprintf(file,"%s",nome);
    fclose(file);
printf("Seu nome foi alterado.");
sleep(2);
system("cls");
main();
}
//--------------------------------------------------------------------
int config2(){
	
	int g,x;
	printf("bem vindo a mudança de cor\n");
	printf("selecione o numero desejado\n");
printf("1.fundo preto letra verde\n");
printf("2.fundo branco brilhante e letra lilas \n");
printf("3.fundo cinza e letra preta\n");

 scanf("%d", &g);
 system("cls");
	FILE *file;
	file= fopen("cora.txt","w");
	switch (g)
{
case 1:
     x=0;
       fprintf(file,"%i",x);
        
     
    break;

case 2:
     x=1;
       fprintf(file,"%i",x);
         
     break;
case 3:
	x=2;
       fprintf(file,"%i",x);
   break;

     default:
       fclose(file);
      system("cls");
     config2();
     break;
}
	
  fclose(file);
  mmain();	
	
}
//-----------------Mudar Cores do Menu-----------------------------------
int config3(){
	
	int g,x;
	
	printf("Bem-vindo a mudança de cor!\n\n");
	
	printf("1. Fundo preto com a letra verde\n");
	printf("2. Fundo branco brilhante com a letra lilas \n");
	printf("3. Fundo cinza com a letra preta\n\n");
	
	printf("Selecione a opção desejada: \n");
	scanf("%d", &g);
	
	system("cls");
 
	FILE *file66;
	file66= fopen("corb.txt","w");
	
	switch (g)
{
case 1:
     x = 0;
       fprintf(file66,"%i",x);
         
     
    break;

case 2:
     x = 1;
       fprintf(file66,"%i",x);
         
     break;
     
case 3:
	x = 2;
       fprintf(file66,"%i",x);
   break;

     default:
       fclose(file66);
      system("cls");
     config2();
     break;
}
	
  fclose(file66);
  mmain();	
	
}
//--------------------------------------------------------------------
int config4(){
printf("O arquivo lista de contatos foi disponibilizado para você nos arquivos do programa\n\n ");
sleep(5);
mmain();
}
//--------------------------------------------------------------------
int config5(){
	printf("A linguagem C não suporta musicas,abra no seu navegador\n\n ");
sleep(5);
mmain();
}
//--------------------------------------------------------------------
int config6(){
	mmain();
}
//-------------------------------------------------------------------
