
#include <stdio.h>
#include <stdlib.h>
#include <locale.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char *argv[]) {
	setlocale(LC_ALL, "Portuguese");
	
	char animal;
	
	//Criamos o código utilizando a IDE Dev-C++.
	//inicio
	
	printf("\nPense em um dos animais a seguir para o sistema advinhar:");
	printf("\nLeao, Cavalo, Homem, Macaco, Morcego, Baleia, Avestruz, Pinguim, Pato, Águia, Tartaruga, Crocodilo e Cobra. \n");
	printf("\nResponda as perguntas com 's' para sim ou 'n' para não! \n");
	printf("\nInicio da advinhação! \n");
	
	printf("\nSeu animal é um Mamifero?");
	scanf(" %c", &animal);
	fflush(stdin);
	if(animal == 's'){
		printf("\nSeu animal é um Quadrúpede? ");
		scanf(" %c", &animal);
		fflush(stdin);
		
		if(animal == 's'){
			printf("\nSeu animal é Carnívoro? ");
			scanf(" %c", &animal);
			fflush(stdin);
			
			if(animal == 's'){
				printf("\nSeu animal pode ser encontrado em árvores? ");
				scanf(" %c", &animal);
				fflush(stdin);
				
				if(animal == 's'){
					printf("\nO seu animal é um Macaco");
				}
				else{
					printf("\nSeu animal é um Leao"); // "ã" e "é" não consegue aparecer no console dependendo da IDE
				}
		   }
		   
		   else{
		   	printf("\nSeu animal é Herbívoro?");
		   	scanf(" %c", &animal);
		   	fflush(stdin);
		   	
		   	if(animal == 's'){
		   		printf("\nSeu animal é um Cavalo");
			   }
			   else{
			   	printf("\nSeu Animal não foi identificado pelo sistema!");
			   }
		   }
		}
		else{
			printf("\nSeu animal é Carnívoro? ");
			scanf(" %c", &animal);
			fflush(stdin);
			
			if(animal == 's'){
				printf("\nSeu animal se encontra no meio Urbano? ");
				scanf(" %c", &animal);
				fflush(stdin);
				if(animal == 's'){
					printf("\nSeu animal é um Homem");
				}
				else{
					printf("\nSeu animal é uma Baleia");
				}
			}
			else{
				printf("\nSeu animal pode ser encontrado nas árvores?" );
				scanf(" %c", &animal);
				fflush(stdin);
				
				if(animal == 's'){
					printf("\nSeu animal é um Morcego");
				}
				else{
				 	printf("\nSeu Animal não foi identificado pelo sistema!");
					}
				}
			}
		}
			else{
				printf("\nSeu animal é um Quadrúpede? ");
				scanf(" %c", &animal);
				fflush(stdin);
				
				if(animal == 's'){
					printf("\nSeu animal é Carnívoro? ");
					scanf(" %c", &animal);
					fflush(stdin);
					if(animal == 's'){
						printf("\nSeu animal é um Crocodilo");
					}
					else{
						printf("\nSeu animal é Herbívoro? ");
						scanf(" %c", &animal);
						fflush(stdin);
						
						if(animal == 's'){
							printf("\nSeu animal é uma Tartaruga");
						}
						else{
							printf("\nSeu Animal não foi identificado pelo sistema!");
						}
					}
				}
				else{
					printf("\nSeu animal é Carnívoro? ");
					scanf(" %c", &animal);
					fflush(stdin);
					
					if(animal == 's'){
						printf("\nSeu animal pode ser encontrado em árvores? ");
						scanf(" %c", &animal);
						fflush(stdin);
						if(animal == 's'){
							printf("\nSeu animal é uma Águia");
						}
						else{
							printf("\nSeu animal pode ser encontrado no meio Urbano? ");
							scanf(" %c", &animal);
							fflush(stdin);
							if(animal == 's'){
								printf("\nSeu animal é uma Cobra");
							}
							else{
								printf("\nSeu animal é um Pinguim");
							}
						}
					}
					else{
						printf("\nSeu animal é Herbívoro? ");
						scanf(" %c", &animal);
						fflush(stdin);
						
						if(animal == 's'){
							printf("\nSeu animal é possivel ser encontrado no meio urbano? ");
							scanf(" %c", &animal);
							fflush(stdin);
							
							if(animal == 's'){
								printf("\nSeu animal é um Pato");
							}
							else{
								printf("\nSeu animal é uma Avestruz");
							}
						}
						else{
							printf("\nSeu Animal não foi identificado pelo sistema!");
						}
					}
				  }
				}
 return 0;
}
