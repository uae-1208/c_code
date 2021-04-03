#ifndef _GAME_H_                        //头文件
#define _GAME_H_

#include<stdio.h>
#include<stdlib.h>
#include<time.h>
#define ROW 3
#define COL 3
void showmenu(void)
{                                              
	printf("***************************************\n");
	printf("*******1.开始游戏   0.退出游戏*********\n");
	printf("***************************************\n");
	printf("请选择:>");
}

void intiboard(char board[ROW][COL],int row,int col)			//初始化棋盘 
{
	int i,j;
	for(i=0;i<row;i++)
		{
			for(j=0;j<col;j++)
			board[i][j]=' ';
		}
}

void showboard(char board[ROW][COL],int row,int col)
{
	int i,j;
	for(i=0;i<row;i++)
	{
		for(j=0;j<col;j++)
		{
			printf(" %c ",board[i][j]);
			if(j<col-1)
				printf("|");
			else
				printf("\n");
		}
		if(i<row-1)
		{
			for(j=0;j<col;j++)
			{
				printf("---");
				if(j<col-1)
					printf("|");
				else
					printf("\n");
			}
		}
	}
	printf("你的棋子：*\n电脑棋子：#\n\n");
}

void playermove(char board[ROW][COL],int row,int col)
{
	int x,y;
	printf("该你走喽:>\n");
	printf("请输入落子坐标(如1 1):");
	scanf("%d%d",&x,&y);
	while(board[x-1][y-1]!=' ')
	{
		printf("该处已有棋子，要重新输入哇:>");
		scanf("%d%d",&x,&y);
	}
	board[x-1][y-1]='*';
	printf("\n");
}

void computermove(char board[ROW][COL],int row,int col)
{
	int x,y;
	printf("电脑移动:>\n");
	srand((unsigned int) time (NULL));
	x=rand()%3;
	y=rand()%3;
	while(board[x][y] != ' ')
	{
		x=rand()%3;
		y=rand()%3;
	}
	board[x][y]='#';
}

char ifwin(char board[ROW][COL],int row,int col)
{
	int i,j;
	for(i=0;i<row;i++)
		if(board[i][0] == board[i][1] && board[i][0] == board[i][2] && board[i][0] != ' ')
			return board[i][0];
	for(j=0;j<col;j++)
		if(board[0][j] == board[1][j] && board[0][j] == board[2][j] && board[0][j] != ' ')
			return board[0][j];	
	if(board[0][0] == board[1][1] && board[0][0] == board[2][2] && board[0][0] != ' ')
		return board[0][0];
	if(board[0][2] == board[1][1] && board[0][2] == board[2][0] && board[0][2] != ' ')
		return board[2][0];
	for(i=0;i<row;i++)
		for(j=0;j<col;j++)
			if(board[i][j] == ' ')
				return 'c';
	return 'd';
}

#endif

#include "game.h"
void game(void)
{
	char board[ROW][COL]={0};
	char ch='c';  								
	intiboard(board,ROW,COL);
	showboard(board,ROW,COL);
	while(ch == 'c')
	{
		playermove(board,ROW,COL);
		ch=ifwin(board,ROW,COL);
		showboard(board,ROW,COL);
		if(ch != 'c')
			break;
		computermove(board,ROW,COL);
		ch=ifwin(board,ROW,COL);
		showboard(board,ROW,COL);
		if(ch != 'c')
			break;
	}
	switch(ch)
	{
		case '*':printf("太棒啦！你打败了连柯洁都打不过的人工智能！！\n");
				 break;
		case '#':printf("很不幸，电脑赢了。\n");
				 break;		 
		case 'd':printf("平局哦，再接再厉。\n");
				 break;
	}
}

int main(void)
{
	int i;
	showmenu();
	scanf("%d",&i);
	while(!(i==0||i==1))
	{
		printf("都说选择1或0啦，笨！\n");
		printf("请重新选择:>");
		scanf("%d",&i);
	}
	while(i)
	{
		game();
		printf("还想再来一把嘛(0 or 1):>");
		scanf("%d",&i);
	}
	printf("退出成功，你真的不想玩了么呜呜呜。\n");
	system("pause");
}
