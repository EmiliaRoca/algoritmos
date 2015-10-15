# algoritmos
/ practico.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include <conio.h>
#include <string.h>
#include <math.h>
using namespace std;
#define fil 10
#define col 10

struct telemento
{
	int mat[fil][col];
};

void cargar(telemento M[fil][col], int n);
void mostrar2(telemento M[fil][col], int n);
int suma(telemento M[fil][col], int n);

void main()
{int n;
	telemento M[fil][col];

	cout << "Ingrese cantidad de filas=columnas: ";
	cin >> n;

	cargar(M,n);
	mostrar2(M,n);
	suma(M,n);
	getch();
}

void cargar(telemento M[fil][col], int n)
{
	int i, j, k, l;
	for(i=0;i<n;i++)
			for(j=0;j<n;j++)
				for(k=0;k<n;k++)
					for(l=0;l<n;l++)
					{
						cout << "M[" <<i<<", " <<j<<"] ["<<k<<", "<<l<<"]= ";
						cin >> M[i][j].mat[k][l];
				
					}
}
 
void mostrar2(telemento M[fil][col], int n)
{
	int i, j, k, l;
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{
			for(k=0;k<n;k++)
			{
				for(l=0;l<n;l++)
					{
						cout<<M[i][j].mat[k][l]<<" ";
					}
				cout<<endl;
			}
			cout<<endl;
		}
		cout<<endl;
	}
	cout<<endl;
}

int suma(telemento M[fil][col], int n)
{
	int i, j, k, l;
	for(i=0;i<n;i++)
		{for(j=0;j<n;j++)
			{s=0
				for(k=0;k<n;k++)
					}
	                 for(l=0;l<n;l++)
					{
						s=s+mat[ï][j].submat[k][l];
						cuot<<s;
					}
	
	
	}
	
	getch();
}
