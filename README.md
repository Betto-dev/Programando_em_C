# Programando_em_C
Fazendo um programa que lê um número inteiro e o imprime na tela

Codigo 100% Funcionando!

// Desenvolvedor.: Adalberto Fernnandes
// Sistema Versão.: v1.0
// Faça um programa que leia um número inteiro e o imprima na tela

#include<stdio.h>
#include<stdlib.h>
#include<locale>
int main(){
	// Aqui temos uma biblioteca que permite o acentos das palavras no codigo
	setlocale(LC_ALL, "Portuguese");
	// Declarando a varivael de tipo inteiro
	int numero = 0;
	// Solicitando ao usuario a entrada do dado (numero)
	printf("Informe um número inteiro: ");
	// Pegando esse valor e guardando a variavel de forma temporaria 
	scanf("%d", &numero);
	// Mostrando o valor que o usuario digitou
	printf("O numero digitado foi: %d ", numero);
	
	return 0;
}
